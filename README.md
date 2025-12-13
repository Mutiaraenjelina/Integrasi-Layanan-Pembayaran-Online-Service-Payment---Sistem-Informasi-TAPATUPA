# Integrasi Layanan Pembayaran Online (Service-Payment) - Sistem Informasi TAPATUPA

Repositori ini berisi kode sumber dan dokumentasi untuk pengembangan modul pembayaran berbasis **microservice** yang diintegrasikan ke dalam sistem **TAPATUPA** (Transformasi Pengelolaan Aset Tanah Kabupaten Tapanuli Utara). Proyek ini merupakan bagian dari Tugas Akhir mahasiswa Program Studi Teknologi Rekayasa Perangkat Lunak, Institut Teknologi Del.

## 📌 Latar Belakang
[cite_start]Sistem TAPATUPA awalnya dibangun dengan arsitektur monolitik yang memiliki keterbatasan dalam skalabilitas dan pemeliharaan seiring meningkatnya kompleksitas transaksi[cite: 63, 64]. [cite_start]Proyek ini melakukan *reengineering* dengan memisahkan modul pembayaran menjadi **service-payment** yang berdiri sendiri untuk meningkatkan keandalan, keamanan, dan fleksibilitas sistem[cite: 70, 71].

## 🚀 Fitur Utama
* [cite_start]**Integrasi Bank Sumut:** Mendukung pembayaran melalui Teller, ATM, dan Mobile Banking[cite: 85].
* [cite_start]**Arsitektur Microservice:** Komunikasi antar layanan yang terstruktur menggunakan API Gateway[cite: 146, 195].
* [cite_start]**Sinkronisasi Data Real-time:** Penggunaan mekanisme *callback* untuk memastikan status transaksi sinkron antara sistem internal dan pihak bank[cite: 160].
* [cite_start]**Keamanan Berlapis:** Implementasi validasi signature/token dan pengujian keamanan menggunakan OWASP ZAP[cite: 208, 222].

## 🛠️ Teknologi yang Digunakan
* [cite_start]**Arsitektur:** Microservices [cite: 138]
* [cite_start]**Komunikasi API:** REST API & API Gateway [cite: 97, 146]
* [cite_start]**Testing Tools:** * **Postman:** Pengujian fungsional dan validasi signature[cite: 225].
  * [cite_start]**Curl:** Pengukuran latency respons API[cite: 216].
  * [cite_start]**OWASP ZAP:** Pemindaian kerentanan keamanan[cite: 221].
* [cite_start]**Monitoring:** Log Service-Payment & Audit Log per Transaksi[cite: 211, 218].

## 📂 Metodologi Pengembangan
[cite_start]Proyek ini dikembangkan menggunakan metode **Prototyping** yang terdiri dari 6 tahapan utama[cite: 167, 183]:
1. Analisis Kebutuhan
2. Perancangan Prototype
3. Pembuatan Prototype
4. Evaluasi & Penyempurnaan
5. Pengembangan Sistem Akhir & Integrasi
6. Maintenance & Monitoring


## 📊 Indikator Pengukuran Kinerja
[cite_start]Keberhasilan sistem diukur berdasarkan[cite: 208]:
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
