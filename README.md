# 📚 Sistem Peminjaman Buku Perpustakaan Berbasis Web

[![GitHub license](https://shields.io)](LICENSE)
[![GitHub stars](https://shields.io)](https://github.com)
[![GitHub issues](https://shields.io)](https://github.com)

Proyek ini merupakan sistem informasi manajemen perpustakaan yang dikembangkan untuk memenuhi tugas mata kuliah **Rekayasa Perangkat Lunak (RPL)**. Sistem ini dirancang untuk mempermudah proses administrasi sirkulasi buku, mulai dari pendataan, peminjaman, pengembalian, hingga pemantauan status buku secara efisien dan berbasis web.

---

## 🚀 Fitur Utama

- **Autentikasi & Otorisasi:** Pemisahan hak akses antara admin perpustakaan, petugas, dan anggota (mahasiswa/siswa).
- **Manajemen Katalog Buku:** Mempermudah pencarian, penambahan, pembaruan, dan penghapusan data buku.
- **Sirkulasi Digital:** Pencatatan otomatis transaksi peminjaman dan pengembalian buku.
- **Kalkulasi Denda:** Penghitungan otomatis biaya denda jika terjadi keterlambatan pengembalian buku.
- **Laporan Real-time:** Dashboard statistik untuk memantau jumlah buku yang sering dipinjam, total anggota aktif, dan riwayat transaksi.

---

## 🛠️ Tumpukan Teknologi (Tech Stack)

Sistem ini dibangun menggunakan teknologi berikut:

* **Frontend:** HTML5, CSS3, JavaScript (Opsional: Bootstrap / Tailwind CSS)
* **Backend:** PHP / Node.js / Python (Sesuaikan dengan yang digunakan)
* **Database:** MySQL / PostgreSQL
* **Dokumentasi & Desain:**
  * `SRS/` : Dokumen *Software Requirements Specification* lengkap.
  * `UML/` : Diagram alur sistem (Use Case, Activity, Class Diagram, dll.).

---

## 📂 Struktur Repositori

```text
rekayasaperangkatlunak/
├── SRS/                # Dokumentasi Spesifikasi Kebutuhan Perangkat Lunak
├── UML/                # File diagram perancangan sistem (Unified Modeling Language)
└── README.md           # Dokumentasi utama proyek
```

---

## 💻 Cara Instalasi & Menjalankan Proyek

Ikuti langkah-langkah berikut untuk menjalankan proyek ini di lingkungan lokal Anda:

### 1. Prasyarat
Pastikan Anda sudah menginstal aplikasi berikut di komputer Anda:
- Git
- Web Server Lokal (misal: XAMPP / Laragon untuk PHP+MySQL, atau Node.js jika menggunakan JavaScript backend)

### 2. Kloning Repositori
```bash
git clone https://github.com
cd rekayasaperangkatlunak
```

### 3. Konfigurasi Database
1. Buka MySQL server Anda (phpMyAdmin atau sejenisnya).
2. Buat database baru dengan nama `db_perpustakaan`.
3. Impor file `.sql` (jika ada) ke dalam database tersebut.

### 4. Menjalankan Aplikasi
Pindahkan folder proyek ke direktori server lokal Anda (misal `htdocs` untuk XAMPP) dan akses melalui browser:
```text
http://localhost/rekayasaperangkatlunak
```

---

## 🖼️ Tangkapan Layar (Screenshots)

| Halaman Utama (Katalog) | Dashboard Admin |
| --- | --- |
| *[Tambahkan Gambar Di Sini]* | *[Tambahkan Gambar Di Sini]* |

---

## 👥 Kontributor

* **Adin Izzulhaq** - *Developer & Sistem Analis* - [@adinizzulhaq](https://github.com/adinizzulhaq)
* *(Tambahkan nama anggota tim Anda di sini jika ada)*
