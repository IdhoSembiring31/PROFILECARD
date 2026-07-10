# ProfileCard Pro


## 🎯 LANGKAH TERAKHIR:

1. Buka `README.md` di repo GitHub lo.
2. **Hapus semua isi lama**.
3. **Copy-paste** kode README FINAL di atas.
4. **Sesuaikan nama file gambar** jika perlu.
5. **Commit changes**.
6. Buka halaman repo, **screenshot** seluruh halaman.
7. Simpan screenshot sebagai **`readme_github.png`**.

---

**LEVEL 2 BERES, KOCAL!** 😎🔥 Sekarang README lo udah **PROFESIONAL** dan **LENGKAP** sesuai checklist dosen. Gas lanjut ke Level 3!
**Tagline:** Aplikasi Profil & Lokasi Digital dengan Fitur Kamera dan GPS

![Version](https://img.shields.io/badge/version-1.0.1-blue)
![Platform](https://img.shields.io/badge/platform-Android-brightgreen)
![Expo](https://img.shields.io/badge/Expo-54-000020?logo=expo)
![React Native](https://img.shields.io/badge/React_Native-0.76-61DAFB?logo=react)

---

## 📋 Daftar Isi
1. [Fitur Unggulan](#-fitur-unggulan)
2. [Tech Stack](#-tech-stack)
3. [Screenshot Aplikasi](#-screenshot-aplikasi)
4. [Dokumentasi Build & Instalasi](#-dokumentasi-build--instalasi)
5. [Download APK](#-download-apk)
6. [Cara Install di HP](#-cara-install-di-hp)
7. [Cara Setup & Jalankan (Developer)](#-cara-setup--jalankan-developer)
8. [Changelog](#-changelog)
9. [Developer](#-developer)

---

## ✨ Fitur Unggulan
1. **📸 Ambil Foto dari Kamera** – Mengambil foto langsung dari kamera HP.
2. **🖼️ Pilih Foto dari Galeri** – Memilih foto dari galeri HP.
3. **📍 Deteksi Lokasi GPS** – Menampilkan koordinat Latitude & Longitude secara real-time.
4. **🗺️ Buka Google Maps** – Navigasi langsung ke lokasi pengguna.
5. **💾 Penyimpanan Otomatis** – Data profil disimpan dengan AsyncStorage.
6. **ℹ️ Tampilan Versi Aplikasi** – Menampilkan versi app di footer (Bonus A).

---

## 🛠️ Tech Stack

| Teknologi | Kegunaan |
| :--- | :--- |
| **React Native (Expo)** | Membangun antarmuka aplikasi mobile |
| **Expo Image Picker** | Mengambil gambar dari kamera & galeri |
| **Expo Location** | Mengakses GPS untuk mendapatkan koordinat |
| **AsyncStorage** | Menyimpan data profil secara lokal |
| **Expo Constants** | Menampilkan versi aplikasi (Bonus A) |
| **EAS Build** | Cloud build untuk menghasilkan file APK |

---

## 📱 Screenshot Aplikasi

| Halaman Utama | Halaman Lokasi | Halaman Galeri |
| :---: | :---: | :---: |
| ![Home](screenshots/home.png) | ![Lokasi](screenshots/lokasi.png) | ![Galeri](screenshots/galeri.png) |

---

## 🔧 Dokumentasi Build & Instalasi

### 1. Proses Build (EAS Dashboard) — Status FINISHED
<img src="https://github.com/user-attachments/assets/7d3f7247-ddf2-4d18-b305-91527caeb22d" width="600" alt="EAS Build Dashboard" />

---

### 2. Proses Instalasi APK di HP
<div style="display: flex; gap: 10px; flex-wrap: wrap;">
  <img src="https://github.com/user-attachments/assets/fc1b9404-ec42-40fe-8670-724ed23f0da6" width="250" alt="Install dialog 1" />
  <img src="https://github.com/user-attachments/assets/9d34033f-1855-46d0-9ff0-4df9b18fe257" width="250" alt="Install dialog 2" />
</div>

---

### 3. Icon Aplikasi di Home Screen / App Drawer
<img src="https://github.com/user-attachments/assets/a28d0339-2465-4245-82c2-d4b99f9aa505" width="250" alt="Home Screen Icon" />

---

### 4. Live Test (Scrcpy) — Koneksi HP ke Laptop
<img src="screenshots/scrpcy_aktif.png" width="600" alt="Scrcpy Active" />

---

### 5. USB Debugging & ADB Devices
<div style="display: flex; gap: 10px; flex-wrap: wrap;">
  <img src="screenshots/usb_debugging.png" width="250" alt="USB Debugging ON" />
  <img src="screenshots/adb_devices.png" width="400" alt="ADB Devices" />
</div>

---

### 6. Video App Berjalan di HP (Tanpa Expo Go)
<a href="https://github.com/user-attachments/assets/0c6d2415-acce-4d8c-abe7-fc06f308d16a">▶️ Klik di sini untuk melihat video demo</a>

---

### 7. Tampilan Versi App di Footer (Bonus A)
<img src="https://github.com/user-attachments/assets/0c4eab53-94e0-4729-bea2-98d4a56c515f" width="250" alt="Version Display" />

---

### 8. Build Kedua & Perubahan UI (Bonus C)
<img src="https://github.com/user-attachments/assets/7a89603a-3c9f-4669-8e49-721404a745aa" width="600" alt="Second Build" />

---

## 📦 Download APK

| Versi | Link Download |
| :--- | :--- |
| **v1.0.1 (Build Kedua)** | [Download APK v1.0.1](https://expo.dev/accounts/idhos/projects/profilecard-pro/builds/7bcb0baa-f2e2-4cf5-80c9-cb9de2361d1f) |
| **v1.0.0 (Build Pertama)** | [Download APK v1.0.0](https://expo.dev/accounts/idhos/projects/profilecard-pro/builds/0c86acee-33c9-4f25-96d6-78f1818db24d) |

> ⚠️ *Link APK hanya aktif 30 hari sejak build selesai.*

---

## 📲 Cara Install di HP
1. Download file `.apk` dari link di atas.
2. Buka file APK di HP Android.
3. Jika muncul peringatan *"Unknown sources"*, izinkan instalasi.
4. Klik **Install**, tunggu hingga selesai.
5. Buka aplikasi **"ProfileCard Pro"** dari menu utama HP.

---

## 🚀 Cara Setup & Jalankan (Developer)
1. Clone repository ini:
   ```bash
   git clone https://github.com/IdhoSembiring31/ProfileCard-Pro
