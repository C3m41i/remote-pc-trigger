# ⚡ Remote PC Power Trigger (ESP8266 & Telegram Bot)

Masaüstü bilgisayarımın güç tuşunu (Power Switch) fiziksel olarak tetiklemek ve bilgisayarı uzaktan açıp kapatabilmek için geliştirdiğim donanım/IoT projesi.

### 🔧 Kullanılan Donanım ve Teknolojiler
- **Mikrodenetleyici:** ESP8266 / NodeMCU
- **Donanım:** 5V Röle Modülü (Anakart Power SW pinlerine paralel bağlı)
- **Yazılım & Kontrol:** Telegram Bot API (C++ / Arduino IDE, AI destekli kodlama ile geliştirildi)

### 🚀 Nasıl Çalışır?
ESP8266 evdeki Wi-Fi ağına bağlanır ve Telegram üzerinden gelen güvenli komutları dinler. Tetikleme komutu geldiğinde röleyi kısa süreliğine kapatarak anakart üzerindeki güç pinlerini kısa devre yapar ve bilgisayarı başlatır.
