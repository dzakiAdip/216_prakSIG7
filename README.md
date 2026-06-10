# 🗺️ Praktikum SIG Pertemuan 7 - Peta Interaktif Bandar Lampung

![Leaflet](https://img.shields.io/badge/Leaflet-1.9.4-199900?style=flat-square&logo=leaflet)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6-F7DF1E?style=flat-square&logo=javascript)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3)

## 📋 Informasi Praktikum

| Keterangan | Detail |
|------------|--------|
| **Nama Praktikan** | Muhammad Thoriq Dzaki |
| **NIM / Kelas** | 2300018216 / A |
| **Mata Kuliah** | Praktikum Sistem Informasi Geografis |
| **Hari/Jam** | Rabu, 16.45 WIB |
| **Nama PJ Praktikum** | Nur F. Putri |

---

## 📌 Tentang Proyek

Proyek ini merupakan implementasi **Peta Web Interaktif** menggunakan **Leaflet.js** sebagai bagian dari praktikum Sistem Informasi Geografis. Peta yang dibuat berfokus pada wilayah **Kota Bandar Lampung** dan sekitarnya, menampilkan berbagai objek geografis seperti:

- 🏥 **Rumah Sakit** (2 lokasi)
- 🎓 **Sekolah** (2 lokasi) 
- 🏖️ **Tempat Wisata** (2 lokasi)
- ⚠️ **Zona Berbahaya** (Area Gunung Anak Krakatau)
- 🗺️ **Polygon Area Khusus** (Kawasan Wisata Bahari & Kampus Unila)
- 📊 **GeoJSON** (Wilayah Administrasi Lampung)

---

## 🎯 Fitur Utama

| Fitur | Deskripsi |
|-------|-----------|
| ✅ **Marker Kustom** | Ikon berbeda untuk setiap jenis objek (RS: plus merah, Sekolah: toga hijau, Wisata: pantai biru) |
| ✅ **Popup Informasi** | Setiap marker menampilkan informasi lengkap saat diklik |
| ✅ **Circle Zona Bahaya** | Area rawan bencana dengan radius 12 km (Gunung Anak Krakatau) |
| ✅ **Polygon Area** | Kawasan wisata bahari dan kampus pendidikan |
| ✅ **GeoJSON Layer** | Menampilkan batas administrasi wilayah Lampung |
| ✅ **Legend Interaktif** | Petunjuk visual untuk semua objek di peta |
| ✅ **Skala Peta** | Menampilkan skala metrik di pojok kiri bawah |
| ✅ **Klik Koordinat** | Menampilkan koordinat geografis saat klik pada peta |

---

## 🛠️ Teknologi yang Digunakan

| Teknologi | Fungsi |
|-----------|--------|
| **Leaflet.js 1.9.4** | Library peta interaktif open-source |
| **CartoDB Basemap** | Tile server peta dasar (alternatif OpenStreetMap) |
| **Font Awesome 6** | Ikon untuk marker kustom |
| **Leaflet.AJAX** | Loading file GeoJSON |
| **HTML5 & CSS3** | Struktur dan styling halaman |

---
