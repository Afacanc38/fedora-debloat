# fedora-debloat
Hiç kullanmadığım uygulamaları kaldıran ve [video oynatma sıkıntısını gideren](https://www.technopat.net/sosyal/konu/fedorada-internet-uezerinden-video-oynatma-sorununu-giderme.1486721/) bir script. Kendinize göre düzenleyebilirsiniz.
## Komutların açıklaması
- `notify-send`: Kullanıcıya masaüstü bildirimleri göndermesini sağlar.
- `dnf`: Fedora'nın öntanımlı dosya yöneticisidir.
<br>Not: `root` olarak değil, normal kullanıcı olarak başlatın.
```
git clone https://github.com/Afacanc38/fedora-debloat.git
cd fedora-debloat
./fedora-kurulum-sonrası
