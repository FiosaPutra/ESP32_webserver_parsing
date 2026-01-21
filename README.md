
---

# ESP32 WebServer
Projek ini menggunakan ESP32 Sebagai transmitter data sensor (DHT11) ke local WebServer. Ada beberapa poin pada program .ino ini seperti:

- Menggunakan SSID dan Password pada WiFi.begin();
- WebServer dapat dikostumasi dengan format HTML
- Data yang di-parsing dalam bentuk string, sehingga bisa dalam bentuk batch (format JSON menyusul)
- Terdiri dari 4 total tombol trigger untuk mengaktifkan akuator (LED/Relay; bisa ditambah)
- Data sensor dengan DHT11/DHT22 yaitu nilai Suhu dan Kelembaban

## 🛠️ Teknologi
- ESP32
- Arduino IDE
- WebServer
- HTML
- Sensor DHT11/DHT22

## ▶️ Cara Menjalankan
Sketch Kasar untuk Rangkaian DHT dan Aktuator(LED) yaitu:
<img src="esp32222.png" width="500"/>
