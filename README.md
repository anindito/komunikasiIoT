# Komunikasi IoT & Integrasi Aplikasi — Kode Pendamping

![License](https://img.shields.io/badge/license-MIT-blue)
![Platform](https://img.shields.io/badge/platform-ESP32%20%7C%20Flutter%20%7C%20Web-green)

Repositori resmi kode pendamping buku:

> **Komunikasi IoT & Integrasi Aplikasi: Membangun Sistem IoT End-to-End
> dengan Flutter dan Web**
> Penulis: [Tim Penulis] · Penerbit: [Nama Penerbit] · Edisi: I, 2026

## 🎯 Tentang Buku Ini

Buku ini membahas sistem IoT secara **end-to-end**: dari sensor di breadboard,
melalui protokol komunikasi (MQTT, HTTP, BLE), hingga tampil di aplikasi
pengguna (Web dan Mobile Flutter). Setiap bab dilengkapi **praktek yang bisa
langsung direplikasi**.

## 📚 Daftar Bab

| Bab | Judul | ESP32 | Web | Flutter | Folder |
|-----|-------|:-----:|:---:|:-------:|--------|
| 01 | Pengantar IoT & Arsitektur 3-Tier | — | — | — | [bab-01-pengantar-iot](./bab-01-pengantar-iot) |
| 02 | Dasar Elektronika & Mikrokontroler | ✅ | — | — | [bab-02-mikrokontroler](./bab-02-mikrokontroler) |
| 03 | Toolchain Lengkap | ✅ | ✅ | ✅ | [bab-03-toolchain](./bab-03-toolchain) |
| 04 | Komunikasi Serial (UART, I²C, SPI) | ✅ | — | — | [bab-04-serial-uart-i2c-spi](./bab-04-serial-uart-i2c-spi) |
| 05 | Sensor Umum untuk IoT | ✅ | — | — | [bab-05-sensor](./bab-05-sensor) |
| 06 | Bluetooth Classic & BLE | ✅ | — | — | [bab-06-bluetooth-ble](./bab-06-bluetooth-ble) |
| 07 | RFID, NFC, & Infrared | ✅ | — | — | [bab-07-rfid-nfc-ir](./bab-07-rfid-nfc-ir) |
| 08 | nRF24L01 & Zigbee | ✅ | — | — | [bab-08-nrf24-zigbee](./bab-08-nrf24-zigbee) |
| 09 | Wi-Fi (ESP32 & ESP8266) | ✅ | — | — | [bab-09-wifi](./bab-09-wifi) |
| 10 | LoRa & GSM | ✅ | — | — | [bab-10-lora-gsm](./bab-10-lora-gsm) |
| 11 | HTTP & REST API | ✅ | ✅ | ✅ | [bab-11-http-rest](./bab-11-http-rest) |
| 12 | MQTT & WebSocket | ✅ | ✅ | ✅ | [bab-12-mqtt-websocket](./bab-12-mqtt-websocket) |
| 13 | Firebase, Supabase, Antares | ✅ | ✅ | ✅ | [bab-13-cloud-firebase-supabase-antares](./bab-13-cloud-firebase-supabase-antares) |
| 14 | HTML + CSS + JS Dasar | — | ✅ | — | [bab-14-html-css-js-dasar](./bab-14-html-css-js-dasar) |
| 15 | Fetch API & WebSocket Browser | — | ✅ | — | [bab-15-fetch-websocket](./bab-15-fetch-websocket) |
| 16 | Web Dashboard IoT Lengkap | ✅ | ✅ | — | [bab-16-dashboard-lengkap](./bab-16-dashboard-lengkap) |
| 17 | Pengantar Flutter | — | — | ✅ | [bab-17-flutter-intro](./bab-17-flutter-intro) |
| 18 | Flutter + REST + MQTT | ✅ | — | ✅ | [bab-18-flutter-rest-mqtt](./bab-18-flutter-rest-mqtt) |
| 19 | Flutter + BLE | ✅ | — | ✅ | [bab-19-flutter-ble](./bab-19-flutter-ble) |
| 20 | Proyek Capstone Terintegrasi | ✅ | ✅ | ✅ | [bab-20-capstone](./bab-20-capstone) |

## 🚀 Cara Menggunakan

1. **Clone** repositori ini:
```bash
   git clone https://github.com/anindito/komunikasiIoT.git
   cd komunikasiIoT
```

2. **Masuk ke folder bab** yang sedang Anda pelajari dari buku:
```bash
   cd bab-12-mqtt-websocket
```

3. **Baca README bab tersebut** untuk panduan spesifik (prasyarat, cara run, dsb).

## 🔧 Prasyarat Umum

| Tool | Versi Minimum | Untuk Bab |
|------|---------------|-----------|
| [Arduino IDE](https://www.arduino.cc/en/software) | 2.3+ | 2–13, 18, 19 |
| [Flutter SDK](https://docs.flutter.dev/get-started/install) | 3.16+ | 17–20 |
| [Node.js](https://nodejs.org/) | 18+ | 14–16, 20 |
| [VS Code](https://code.visualstudio.com/) | Terbaru | Semua bab |
| [Mosquitto](https://mosquitto.org/download/) | 2.0+ | 12, 18, 20 |

Panduan instalasi detail: lihat folder [`docs/`](./docs).

## 🔑 Catatan tentang Kredensial

File dengan ekstensi `.example` (mis. `config.h.example`) berisi **template**
untuk kredensial WiFi, broker MQTT, API key, dll. Langkah untuk menggunakan:

1. Salin `config.h.example` menjadi `config.h`
2. Isi dengan kredensial Anda
3. File `config.h` **tidak akan ter-commit** (sudah ada di `.gitignore`)

## 🐛 Troubleshooting

- Masalah setup umum → [`docs/troubleshooting-umum.md`](./docs/troubleshooting-umum.md)
- Masalah spesifik bab → lihat README bab terkait
- Pertanyaan / bug report → [buka Issue](https://github.com/anindito/komunikasiIoT/issues)

## 🤝 Kontribusi

Menemukan typo atau bug di kode? Terima kasih banyak! Silakan baca
[`CONTRIBUTING.md`](./CONTRIBUTING.md) sebelum membuka Pull Request.

## 📄 Lisensi

Kode pada repositori ini dilisensikan di bawah **MIT License** — lihat
[`LICENSE`](./LICENSE).

Isi buku (teks, gambar) dilindungi hak cipta penerbit. Repositori ini hanya
berisi kode pendamping untuk keperluan belajar-mengajar.

## 📬 Kontak

- Author: [@anindito](https://github.com/anindito)
- Email: [email@example.com]
