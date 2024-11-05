# Smart Detector Chicken Coop

Proyek ini adalah sistem IoT untuk monitoring suhu, kelembapan, dan gas amonia di kandang ayam. Sistem menggunakan ESP32 sebagai mikrokontroler utama, dan memanfaatkan cloud platform untuk penyimpanan data, analitik, serta notifikasi.

## Fitur Utama
- Monitoring suhu, kelembapan, dan kadar gas amonia real-time.
- Notifikasi otomatis saat kondisi kritis.
- Kendali otomatis untuk sistem kipas atau misting.

## Struktur Proyek
- *hardware/*: Dokumentasi perangkat keras, termasuk diagram rangkaian dan daftar komponen.
- *firmware/*: Kode untuk ESP32 yang membaca data sensor dan mengirimkannya ke cloud.
- *cloud/*: Pengaturan server dan fungsi cloud untuk penyimpanan data dan notifikasi.
- *dashboard/*: Aplikasi dashboard untuk memantau data secara real-time.
- *docs/*: Dokumentasi lengkap untuk instalasi, pemakaian, dan pemeliharaan.

## Cara Memulai
1. *Instalasi Perangkat Keras*: Lihat diagram di hardware/circuit_diagram.png.
2. *Firmware ESP32*: Unggah kode di firmware/ ke ESP32.
3. *Cloud Platform*: Konfigurasi platform cloud sesuai petunjuk di cloud/README.md.
4. *Dashboard*: Jalankan aplikasi dashboard menggunakan petunjuk di dashboard/README.md.

## Lisensi
Proyek ini dilisensikan di bawah MIT License. Lihat LICENSE untuk detail.
