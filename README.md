# Web-Security-Scanner

Copy code
# Web Güvenlik Tarayıcı

Bu Python script'i, belirli bir web sayfasını tarayarak sayfadaki tüm bağlantıları (linkleri) bulur ve her bir bağlantı için basit bir güvenlik taraması gerçekleştirir. Temel amaç, potansiyel güvenlik risklerini belirlemek ve kullanıcıyı bu risklere karşı uyarabilmektir.

## Kullanım

1. Python yüklü değilse, [Python'un resmi web sitesinden](https://www.python.org/) Python'u indirip yükleyin.

2. Gerekli kütüphaneleri yüklemek için terminal veya komut istemcisine şu komutu yazın:

   ```bash
   pip install requests beautifulsoup4
security_scanner.py dosyasını bir metin düzenleyiciyle açın ve target_url değişkenine taranacak web sayfasının URL'sini girin.

Terminal veya komut istemcisinde şu komutu çalıştırarak script'i başlatın:

python security_scanner.py

Dikkat
Bu script sadece basit bir güvenlik taraması yapmaktadır. Gerçek bir güvenlik taraması için daha karmaşık ve kapsamlı kontrollerin yapılması gerekebilir.

