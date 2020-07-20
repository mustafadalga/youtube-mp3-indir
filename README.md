# Powershell - Youtube Mp3 İndirme

**Script'in kullanılabilmesi için bilgisayarınızda  chocolatey paket yöneticisinin kurulu olması gerekiyor.**

**Chocolatey paket yöneticisini kurmak için bağlantı adresi:** https://chocolatey.org/install


**Chocolatey paket yönetici ile indireceğimiz 2 paket kullanacağız;**


* youtube-dl paketi,
* ffmpeg paketi,



**Youtube-dl paketi kurulumu için;**

```
choco install youtube-dl
```
**ffmpeg paketinin kurulumu için;**

```
choco install ffmpeg
```

Yukarıdaki paketleri kurduktan sonra script'i kullanmaya başlayabilirsiniz.


### Kullanım

```
.\youtube-mp3-indir.ps1 -url videourlsi
```
