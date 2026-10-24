# catbot-releases# 🐱 CatBOT Official Release `v1.0.0-fw1.4.1`

![Platform](https://img.shields.io/badge/Platform-Android%20%7C%20ESP32--C3-brightgreen?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Stable-blue?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-orange?style=for-the-badge)

> **CatBOT** adalah ekosistem robot kucing pintar interaktif yang ditenagai oleh **ESP32-C3** dan dikontrol via aplikasi **Flutter Android** melalui protokol Bluetooth Low Energy (BLE).

---

## 📑 Quick Download & Assets

| File | Tipe | Deskripsi |
| :--- | :---: | :--- |
| 📱 **`catbot.apk`** | Mobile App | Aplikasi Android Flutter untuk kontrol BLE & interaksi AI |
| ⚡ **`catbot_firmware.bin`** | Firmware | Binary siap flash untuk ESP32-C3 (OLED + I2S Audio + Sensors) |
| ⚙️ **`update.json`** | Metadata | Config file untuk fitur Auto-Update / OTA internal app |

---

## ✨ Key Features & Highlights

- **📡 BLE Nordic UART Service:** Komunikasi dua arah berkecepatan tinggi antara HP dan robot.
- **👀 OLED Animated Expressions:** Animasi ekspresi mata dinamis (`IDLE`, `HAPPY`, `DIZZY`, `TALKING`).
- **🤖 Fast AI REST API Integration:** Terintegrasi dengan model LLM via Groq/OpenRouter API.
- **🛠️ Optimized Build System:** Konfigurasi Gradle & Kotlin yang stabil dan bebas cache issue.

---

## 🛠️ How to Use

1. **Unduh `catbot.apk`** lalu install di smartphone Android kamu.
2. **Flash `catbot_firmware.bin`** ke modul ESP32-C3 milikmu.
3. Buka aplikasi CatBOT, sambungkan ke perangkat **`CatBot-BLE`**, dan mulailah berinteraksi!
