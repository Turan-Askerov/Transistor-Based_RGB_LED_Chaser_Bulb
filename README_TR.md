🌈 RGB LED Ampul Yükseltmesi

🎯 Proje Amacı

Bu projenin amacı, standart bir RGB olmayan LED ampulü özel bir RGB ampule dönüştürmektir. Orijinal LED modülü çıkarılıp, 
özel yapım transistör tabanlı sıralı sürücü devresi tarafından kontrol edilen elle monte edilmiş RGB LED'lerle değiştirilmiştir.

🛠️ Bileşenler

💡 Standart LED ampul yuvası (orijinal LED modülü çıkarılmış)

🔵 1 × Mavi LED (≈ 3V)

🟢 1 × Yeşil LED (≈ 3V)

🔴 2 × Kırmızı LED (≈ 2V, düşük parlaklık nedeniyle iki kez kullanıldı)

🔌 USB 5V güç kaynağı

🔧 Transistörler (anahtarlama için)

🔋 Kapasitörler (zamanlama için)

🧲 Dirençler (akım sınırlama ve polarlama)

🪛 Özel bir düzende elle lehimlenmiş bağlantılar

⚙️ Devre Fonksiyonu

- Devre, farklı LED'ler arasında sırayla geçiş yapmak için transistörler, kapasitörler ve dirençler kullanır.

- Her LED sırayla yanarak, herhangi bir mikrodenetleyici olmadan renk değiştiren bir efekt oluşturur.

- Tasarım, 3 bitlik bir asenkron sayıcı veya bir LED takip devresine benzer.

🔌 Çalışma Prensibi

- Güç Girişi: Devre, 5V USB adaptör ile çalışır.

- Sıralı Anahtarlama: RC (direnç-kondansatör) ağları, transistör anahtarlama sürelerini kontrol eder.

- LED Sıralaması: Mavi → Yeşil → Kırmızı → Kırmızı (tekrarlanan döngü).

- Görsel Efekt: Normal bir LED ampulü özel bir RGB lambaya dönüştüren, akıcı bir döngüsel RGB efekti.

📷 Proje Görseli

✨ Önemli Noktalar

- Mikrodenetleyici kullanılmadan tamamen elle üretilmiştir.

- Transistör mantığı ve zamanlama devrelerine dayanmaktadır.

- Özel LED düzenlemesi, renkler arasında parlaklık dengesi sağlar.
