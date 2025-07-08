# Android için Adguard Home
- DNS isteklerini yeniden yönlendirerek ve filtreleyerek reklam engelleyen ve modül sistemiyle çalışan kök yöneticiye sahip
- Twoone3'e göre IFW kuralları eklenmiş, reklam klasörleri silinmiş/işgal edilmiş
- 8680 adet engelleme kuralı entegre edilmiş ve özel kurallar eklenmiştir
- Modülün neredeyse tüm alt komut dosyaları yeniden yapılandırılmış, daha düşük gecikme, daha iyi performans ve enerji optimizasyonu sağlar
- Yükleme veya güncelleme sırasında ses düğmesini aşağıya basarak ilerlemek zorundasınız, aksi takdirde yapılandırma dosyaları güncellenmez
- [Tıklayarak öğreticiye geçin](#%C3%96%C4%9Freticiyi-Okumazsan%C4%B1z-Yap%C4%B1lan-Hatalar-Benim-Sorumlulu%C4%9Fumda-De%C4%9Fildir)

# Risk Uyarısı, Okumazsanız Sorumluluk Kabul Etmem
- ⚠️ Modül kuponların normal şekilde kullanılmasını engelleyebilir, kullanılamaması durumu "yanlışlıkla engelleme" değildir
- ⚠️ Bazı uygulamalarda reklama karşılık jeton alma özelliği çalışmayabilir, bu da "yanlışlıkla engelleme" değildir
- ⚠️ Örneğin Baidu gibi şirketler reklamları finansal ürünlere bağlamış olabilir, finansal kredi işlemleri çalışmıyorsa bu "yanlışlıkla engelleme" değildir
- ⚠️ Modül aynı türden diğer modüllerle birlikte kullanılmamalıdır, daha fazla bilgi için "Öğretici" bölümüne bakınız
- ⚠️ Modül QQ, WeChat, Alipay gibi aynı alan adına sahip reklam ve içerikleri engelleyemez

# Modül Diğer Yöntemlere Göre Ne Avantaj Sağlar?
### Özel DNS'e göre avantajları:
1. Özel DNS sunucuları sürekli olarak erişim gerektirdiği için sunucu aşırı yüklenirse veya bağlantı koparsa internet kesintisi yaşanabilir
2. Özel DNS'e erişim gerektiği için yüksek ağ gecikmeleri yaşanabilir (sunucudan filtreleme sonrası cihazınıza dönüşte)
3. Tüm veriler sunucuda işlendiği için veri sızıntısı riski vardır (özel DNS güvenilirliği düşük olabilir)
4. Veriler yerel olarak işlendiği için gizlilik daha yüksek

### Hosts'a göre avantajları:
1. Veriler şifreli olarak iletilir ve DoH (DNS over HTTPS) ile korunur
2. DNS yönlendirmesine karşı koruma sunar, web sayfalarının yönlendirilmesini engeller
3. Tespit edilme riski düşüktür, çünkü ilk maddedeki gibi şifreli iletim yapılır

### Lih跳跳 (Lih Tiaotiao) gibi engelsiz atlama yazılımlarına göre avantajları:
1. Arka plana geçme veya arka plan uygulamasının kapatılması engelsiz atlama özelliğini etkilemez
2. Gerçek zamanlı sayfa öğeleri taranmadığı için telefonunuzun kare hızında düşüş yaşanmaz
3. Hafif çalıştığı için pil tüketimi konusunda endişe yoktur
4. Uygulama paket adı tespiti sorunu yoktur

### Lsposed reklam engelleme modüllerine göre avantajları:
1. Lsposed modülleri uygulamalara fonksiyon enjekte ederek çalıştığı için tespit edilme riski düşüktür
2. Bu modül reklam engelleme hassasiyeti düşük olsa da bu modüller yalnızca birkaç uygulamayı engelleyebilirken, bu modül çok daha fazlasını kapsar

# Öğretici, Okumazsanız Yapılan Hatalar Benim Sorumluluğumda Değildir
- Diğer reklam engelleyici modüller, proxy modülleri, engelsiz atlama yazılımları, VPN proxy reklam engelleyiciler, tarayıcı içi reklam engelleyiciler, özel DNS vs. tüm bunları kapatın veya kaldırın
- Reklamlar engellenmiyorsa öncelikle ilgili uygulamanın tüm önbelleğini temizleyip arka planı kapatıp yeniden deneyin (hala engellenmiyorsa, uygulamanın tüm verilerini silip yeniden deneyin)
- Eğer Magisk kullanıyorsanız modülün yanındaki işlem düğmesine basarak Web UI yönetim paneline erişebilirsiniz
- Chash Meta kullanıyorsanız ve filtreleme çalışmıyorsa Chash Meta ayarları > Ağ kısmından sistem proxy'sini kapatın (testlerimde yine proxy çalışmaya devam etti ve reklamlar filtrelendi)
- Hız testi: https://test.ustc.edu.cn/
- Reklam engelleme testi (engelleme oranı %96 veya üzeri normaldir): https://paileactivist.github.io/toolz/adblock.html

# İletişim Bilgileri
- Sohbet Grubu: [Gruba Katılın](https://qun.qq.com/universal-share/share?ac=1&authKey=l2FNOfui75SDr9n8qTfNjibiF1aTpQ%2B0cmJrw7iKnj%2B95dyExNG5LrdCJu5%2FEKrQ&busi_data=eyJncm91cENvZGUiOiI3NDY2NDA0NjQiLCJ0b2tlbiI6ImhOUWgzVTFPYnRUcEw1ZEJ1TnhkOGI4b0ZQSFV6cmtuVkludk5EcDR4WTFXSU5PelVmdnZoUHIwOGEreHVnNEYiLCJ1aW4iOiIzMzEzODI0NTc1In0%3D&data=8QbRVdmvcvuIPhoaZYMQRNm8tdG9QvQ_d6dLJvGEW_XEOWLbexxs8SgTRPfW51Tpe7IGWAu3PpizEpFa9oO1LQ&svctype=4&tempid=h5_group_info)
- Test ve Geri Bildirim Grubu: [Gruba Katılın](https://qun.qq.com/universal-share/share?ac=1&authKey=xuYEMvAvyzLDhQ58xxwN71dyblHMrMB9YSG4ZpFpKrFz1NT4WdL19uSE4XJE1dt6&busi_data=eyJncm91cENvZGUiOiI1ODQwNjM0NDMiLCJ0b2tlbiI6Im9aM2R1ejBUeDJSWDVJaWNFdmE3bE5YdDdUam5OczZ3R2Z1MmFrYTlpZXNGV2EySFlZRVQrQ0NDOEhoSGZhTHEiLCJ1aW4iOiIzMzEzODI0NTc1In0%3D&data=e5gCMNYudfN2GeBXHTj6s3dwh37WNTWTcpws90_eZ_huBBXuanzL6MQ1FvfjRxLxN3oraEJUF8QAhN0oYAErKA&svctype=4&tempid=h5_group_info)

# Teşekkür Edilen Projeler
- [AdguardHome_magisk](https://github.com/410154425/AdGuardHome_magisk)
- [akashaProxy](https://github.com/ModuleList/akashaProxy)
- [box_for_magisk](https://github.com/taamarin/box_for_magisk)
- [AdGuardHomeForMagisk](https://github.com/twoone-3/AdGuardHomeForMagisk)
