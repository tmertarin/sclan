# LocalRemote - LAN Tarayıcı ve Cihaz İzleyici

**LocalRemote** bir Windows Forms uygulamasıdır. Bu uygulama, yerel ağınızdaki cihazları tarar, IP adreslerini, hostname'lerini ve çevrimiçi/çevrimdışı durumlarını görüntüler. Kullanıcı dostu arayüzü sayesinde ağdaki cihazları hızlı ve kolay bir şekilde izleyebilirsiniz.

## Özellikler

- **Ağ Tarama:** 192.168.1.0/24 IP aralığındaki cihazları tarar.
- **Ping Kontrolü:** Her bir cihaz için ping gönderir ve çevrimiçi/çevrimdışı durumlarını kontrol eder.
- **Durum Renkleri:** Çevrimdışı cihazlar kırmızı, çevrimiçi cihazlar ise yeşil renkte gösterilir.
- **Hostname Görüntüleme:** IP adresinin yanında cihazların hostname'leri de görüntülenir.
- **Asenkron İşlem:** Tarama ve ping işlemleri asenkron olarak yapılır, böylece performans artışı sağlanır.

## Kullanım

1. Uygulama başlatıldığında, ağdaki cihazlar taranmaya başlar.
2. Tarama sonuçları, IP adresi, hostname ve cihaz durumu (Online/Offline) şeklinde `ListView`'da görüntülenir.
3. Çevrimdışı cihazlar kırmızı, çevrimiçi cihazlar ise yeşil renkte işaretlenir.

## Gereksinimler

- .NET Framework 4.7.2 veya daha yüksek
- Windows işletim sistemi

## Kurulum

1. **GitHub'dan klonlayın** veya projeyi indirin:
    ```bash
    git clone https://github.com/yourusername/LocalRemote.git
    ```

2. Visual Studio ile projeyi açın ve **Build** işlemini gerçekleştirin.

3. Uygulamayı çalıştırın ve ağdaki cihazları taramaya başlayın!

## Lisans

Bu proje [MIT Lisansı](https://opensource.org/licenses/MIT) altında lisanslanmıştır.

## Katkıda Bulunma

Katkıda bulunmak isterseniz, lütfen bir pull request oluşturun veya bir issue açın. Her türlü katkı memnuniyetle karşılanır!

---

**LocalRemote** projesi, ağ tarama ve cihaz izleme gibi temel işlevleri kolayca gerçekleştirebileceğiniz basit bir araçtır. Geliştiriciler ve ağ yöneticileri için faydalı olabilir.

