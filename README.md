# Powershell kullanarak youtube'den mp3 indirme


Script'in kullanılabilmesi için bilgisayarınızda  chocolatey paket yöneticisinin kurulu olması gerekiyor.
kurulum için bakınız:https://chocolatey.org/install

Chocolatey paket yönetici ile indireceğimiz 2 paket kullanacağız;
1-)youtube-dl paketi,
2-)ffmpeg paketi,

Youtube-dl paketi kurulumu için;
choco install youtube-dl

ffmpeg paketinin kurulumu için;
choco install ffmpeg


Yukarıdaki paketleri kurduktan sonra script'i kullanmaya başlayabilirsiniz.


Kullanımı 
 .\youtube-mp3-indir.ps1 -url videourlsi
