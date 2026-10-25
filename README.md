# jenerik-yayin

Jenerik oyununun herkese açık sayfaları ve oyun içeriği. GitHub Pages ile
`https://akmiraltunakar.github.io/jenerik-yayin/` adresinden yayınlanır.

- `index.html` — oyunun tanıtım ve destek sayfası (mağazalardaki web sitesi / destek adresi)
- `gizlilik.html` — gizlilik politikası (mağazalardaki gizlilik adresi)
- `content.json` — uygulamanın güncelleme beklemeden indirdiği dizi ve karakter içeriği

`gizlilik.html`, `content.json` ve `img/` elle düzenlenmez: ana depoda
`python tool/publish_site.py` ile üretilir. Sonra burada commit atıp gönder.

AdMob'un aradığı `app-ads.txt` bu depoda değil, alan adının kökünde
(`akmiraltunakar.github.io` deposunda) durur ve bütün uygulamalar için geçerlidir.
