# Android için Adguard Homee
- Root yöneticisi için reklamları engelleyen ve modül sistemiyle DNS isteklerini yönlendirip filtreleyen bir araç.
- Twoone3 temelinde IFW kuralları, reklam klasörlerini silme/işgal etme gibi yöntemlerle reklamları devre dışı bırakma.
- 8680'in engelleme kurallarını içerir ve buna ek olarak özel kurallar eklenmiştir.
- Modülün neredeyse tüm alt düzey betiklerini yeniden yapılandırarak daha düşük gecikme, daha iyi performans ve güç tüketimi optimizasyonu sağlar.
- Güncelleme yüklerken ses seviyesini düşürmeyi seçmelisiniz, aksi takdirde yapılandırma dosyası güncellenemez.
- Öğreticiye doğrudan gitmek için bu bağlantıya tıklayın: [Tıklayın](#%E6%95%99%E7%A8%8B%E4%B8%8D%E7%9C%8B%E7%9A%84%E8%AF%9D%E5%87%BA%E4%BA%8B%E5%88%AB%E5%88%B0%E5%A4%84%E6%89%BE%E6%88%91%E9%97%AE%E9%A2%98)

# Risk Uyarısı, Bakmazsanız Beni Suçlamayın
- ⚠️ Modül, kuponların normal şekilde alınamamasına neden olabilir; bu bir yanlış alarm değildir.
- ⚠️ Bazı yazılımlarda reklam izleyerek altın kazanma özelliği normal şekilde kullanılamayabilir; bu bir yanlış alarm değildir.
- ⚠️ Örneğin, Baidu gibi şirketler reklamları finansal ürünlerle bağlar; finansal borçlanma türlerinin kullanılamaması bir yanlış alarm değildir.
- ⚠️ Modül, benzer modüllerle aynı anda kullanılamaz; daha fazla bilgi için öğretici bölümüne bakın.
- ⚠️ Modül, reklamlar ve içerik aynı alan adında olduğunda, örneğin QQ, WeChat, Alipay gibi bazı reklamları engelleyemez.

# Modülün Diğer Çözümlere Kıyasla Avantajları Nelerdir?
- **Özel DNS'e kıyasla avantajları nelerdir?**
  1. Özel DNS, sunucuya sürekli erişim gerektirir; sunucu aşırı yüklendiğinde veya bağlantı sağlanamadığında internet kesintisi olur.
  2. Özel DNS, sunucuya erişim gerektiğinden büyük ağ gecikmesi sorunlarına yol açar (çünkü filtreleme için sunucuya istek gönderip ardından cihazınıza geri dönmesi gerekir).
  3. Özel DNS, verilerin sunucu tarafından işlenmesi nedeniyle veri sızıntısı riski taşır (çünkü özel DNS'in güvenilirliği düşüktür).
  4. Veriler yerel olarak işlenir, bu da gizlilik güvencesini artırır.

- **Hosts'a kıyasla avantajları nelerdir?**
  1. Veriler şifreli olarak iletilir ve DoH (DNS over HTTPS) kullanılır.
  2. DNS kaçırılmasını ve web sayfasının kaçırılma riskini önler.
  3. Tespit edilmesi zordur, nedeni ilk madde ile aynıdır.

- **Li Tiaotiao gibi engelsiz atlama yazılımlarına kıyasla avantajları nelerdir?**
  1. Arka planda düşme veya arka planı öldürmenin engelsizliği geçersiz kılma gibi sorunları yoktur.
  2. Engelsizlik nedeniyle telefonun kare hızı düşmez veya takılmaz, çünkü engelsiz atlama yazılımları sayfa öğelerini gerçek zamanlı olarak tarar.
  3. Hafif çalışma, hızlı pil tüketimi sorunu yoktur.
  4. Modül, uygulama paket adının tespit edilme sorunu yoktur.

- **Lsposed modülüne kıyasla reklam engelleme avantajları nelerdir?**
  1. Tespit edilmesi zordur, çünkü Lsposed reklam engelleme eklentisi uygulamaya Hook fonksiyonu enjekte eder.
  2. Bu modülün engelleme hassasiyeti düşük olsa da, bu tür eklentilere kıyasla daha geniş bir kapsama sahiptir (çünkü bu tür modüller sadece bir veya on kadar uygulamayı engelleyebilir).

# Öğretici, Bakmazsanız Sorun Çıkarsa Beni Her Yerde Aramayın
- Diğer reklam engelleme modüllerini, proxy modüllerini, engelsiz atlama yazılımlarını, VPN proxy reklam engelleme, tarayıcı yerleşik reklam engelleme, özel DNS vb. kapatın veya kaldırın.
- Reklam engellenemiyorsa, önce uygulamanın tüm önbelleğini temizleyin ve arka planı öldürerek yeniden deneyin (hala olmuyorsa, uygulamanın tüm verilerini temizleyin ve yeniden deneyin).
- Magisk çerçevesini kullanıyorsanız, modül yanındaki işlem düğmesine tıklayarak Web UI yöneticisine girebilirsiniz.
- Chash Meta kullanımı nedeniyle normal filtreleme yapılamıyorsa, Chash Meta ayarları-ağda sistem proxy'sini kapatabilirsiniz (test ettim, hala normal proxy yapılabiliyor ve reklamlar filtrelenebiliyor).
- Hız testi: [https://test.ustc.edu.cn/](https://test.ustc.edu.cn/)
- Reklam engelleme oranını test edin (96% veya üzeri normaldir): [https://paileactivist.github.io/toolz/adblock.html](https://paileactivist.github.io/toolz/adblock.html)

# İletişim Bilgileri
- Sohbet grubu: [Gruba katılmak için tıklayın](https://qun.qq.com/universal-share/share?ac=1&authKey=l2FNOfui75SDr9n8qTfNjibiF1aTpQ%2B0cmJrw7iKnj%2B95dyExNG5LrdCJu5%2FEKrQ&busi_data=eyJncm91cENvZGUiOiI3NDY2NDA0NjQiLCJ0b2tlbiI6ImhOUWgzVTFPYnRUcEw1ZEJ1TnhkOGI4b0ZQSFV6cmtuVkludk5EcDR4WTFXSU5PelVmdnZoUHIwOGEreHVnNEYiLCJ1aW4iOiIzMzEzODI0NTc1In0%3D&data=8QbRVdmvcvuIPhoaZYMQRNm8tdG9QvQ_d6dLJvGEW_XEOWLbexxs8SgTRPfW51Tpe7IGWAu3PpizEpFa9oO1LQ&svctype=4&tempid=h5_group_info)
- Geri bildirim ve test grubu: [Gruba katılmak için tıklayın](https://qun.qq.com/universal-share/share?ac=1&authKey=xuYEMvAvyzLDhQ58xxwN71dyblHMrMB9YSG4ZpFpKrFz1NT4WdL19uSE4XJE1dt6&busi_data=eyJncm91cENvZGUiOiI1ODQwNjM0NDMiLCJ0b2tlbiI6Im9aM2R1ejBUeDJSWDVJaWNFdmE3bE5YdDdUam5OczZ3R2Z1MmFrYTlpZXNGV2EySFlZRVQrQ0NDOEhoSGZhTHEiLCJ1aW4iOiIzMzEzODI0NTc1In0%3D&data=e5gCMNYudfN2GeBXHTj6s3dwh37WNTWTcpws90_eZ_huBBXuanzL6MQ1FvfjRxLxN3oraEJUF8QAhN0oYAErKA&svctype=4&tempid=h5_group_info)

# Teşekkür Edilen Projeler
- [AdguardHome_magisk](https://github.com/410154425/AdGuardHome_magisk)
- [akashaProxy](https://github.com/ModuleList/akashaProxy)
- [box_for_magisk](https://github.com/taamarin/box_for_magisk)
- [AdGuardHomeForMagisk](https://github.com/twoone-3/AdGuardHomeForMagisk)

