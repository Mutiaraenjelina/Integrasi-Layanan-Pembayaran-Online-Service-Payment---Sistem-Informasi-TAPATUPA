# Integrasi Layanan Pembayaran Online (Service-Payment) - Sistem Informasi TAPATUPA

Repositori ini berisi kode sumber dan dokumentasi untuk pengembangan modul pembayaran berbasis **microservice** yang diintegrasikan ke dalam sistem **TAPATUPA** (Transformasi Pengelolaan Aset Tanah Kabupaten Tapanuli Utara). Proyek ini merupakan bagian dari Tugas Akhir mahasiswa Program Studi Teknologi Rekayasa Perangkat Lunak, Institut Teknologi Del.

## 📌 Latar Belakang
Sistem TAPATUPA awalnya dibangun dengan arsitektur monolitik yang memiliki keterbatasan dalam skalabilitas dan pemeliharaan seiring meningkatnya kompleksitas transaksi. Proyek ini melakukan *reengineering* dengan memisahkan modul pembayaran menjadi **service-payment** yang berdiri sendiri untuk meningkatkan keandalan, keamanan, dan fleksibilitas sistem.

## 🚀 Fitur Utama
* **Integrasi Bank Sumut:** Mendukung pembayaran melalui Teller, ATM, dan Mobile Banking.
* **Arsitektur Microservice:** Komunikasi antar layanan yang terstruktur menggunakan API Gateway.
* **Sinkronisasi Data Real-time:** Penggunaan mekanisme *callback* untuk memastikan status transaksi sinkron antara sistem internal dan pihak bank.
* **Keamanan Berlapis:** Implementasi validasi signature/token dan pengujian keamanan menggunakan OWASP ZAP.

## 🛠️ Teknologi yang Digunakan
* **Arsitektur:** Microservices 
* **Komunikasi API:** REST API & API Gateway 
* **Testing Tools:** * **Postman:** Pengujian fungsional dan validasi signature.
  * **Curl:** Pengukuran latency respons API.
  * **OWASP ZAP:** Pemindaian kerentanan keamanan.
* **Monitoring:** Log Service-Payment & Audit Log per Transaksi.

## 📂 Metodologi Pengembangan
Proyek ini dikembangkan menggunakan metode **Prototyping** yang terdiri dari 6 tahapan utama:
1. Analisis Kebutuhan
2. Perancangan Prototype
3. Pembuatan Prototype
4. Evaluasi & Penyempurnaan
5. Pengembangan Sistem Akhir & Integrasi
6. Maintenance & Monitoring


## 📊 Indikator Pengukuran Kinerja
[cite_start]Keberhasilan sistem diukur berdasarkan:
| Aspek | Indikator |
|-------|-----------|
| **Keandalan** | Persentase transaksi berhasil vs gagal |
| **Sinkronisasi** | Akurasi status pembayaran antara sistem & Bank Sumut |
| **Keamanan** | Kemampuan menahan akses tidak sah (Security Test) |

## 👥 Tim Pengembang (Kelompok 16)
* **Mutiara Enjelina** (11422008) 
* **Nehemia Sitorus** (11422028)
* **Efran Rabdo Oktavianus Lumbantoruan** (11422030)

---
© 2025 Program Studi Teknologi Rekayasa Perangkat Lunak - Institut Teknologi Del
