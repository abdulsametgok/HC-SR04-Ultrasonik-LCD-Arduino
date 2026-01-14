# HC-SR04-Ultrasonik-LCD-Arduino
HC-SR04 Ultrasonik Mesafe Sensörü ve 16x2 LCD Projesi
Proje açıklaması eklendi.

Bu Arduino projesi, HC-SR04 ultrasonik sensörü kullanarak nesnelerin mesafesini ölçer ve ölçülen değerleri 16x2 LCD ekranda gerçek zamanlı gösterir. Kırmızı ve yeşil LED’ler ile nesnelere olan mesafe görsel olarak da takip edilebilir.

Özellikler

Gerçek zamanlı mesafe ölçümü (cm ve inç)

16x2 LCD ekran çıktısı

LED göstergeler (isteğe bağlı buzzer ile sesli uyarı)

Arduino ile mikrodenetleyici kontrolü

Kullanılan Malzemeler

Arduino Uno/Nano

HC-SR04 Ultrasonik Sensör

16x2 LCD ekran

LED’ler (Kırmızı, Yeşil)

220 Ω Dirençler

Breadboard ve bağlantı kabloları

USB kablosu

Devre Bağlantıları

HC-SR04: VCC→5V, GND→GND, TRIG→D9, ECHO→D10

LCD: VSS→GND, VDD→5V, RS→D2, RW→GND, E→D3, D4→D4, D5→D5, D6→D6, D7→D7, A→5V/220Ω, K→GND

LED’ler: Kırmızı LED (<10 cm), Yeşil LED (≥10 cm)

Çalışma Prensibi

HC-SR04 ultrasonik darbe gönderir.

Arduino yankının geri dönme süresini ölçer.

Mesafe hesaplanır: Mesafe = (Süre × Ses Hızı) / 2

Sonuç LCD ekranda ve LED’lerde gösterilir.
