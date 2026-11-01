# 📚 Sistem Peminjaman Buku Perpustakaan Berbasis Web
> **Proyek Mata Kuliah:** Rekayasa Perangkat Lunak (RPL)  
> **Status:** 🛠️ In Development / Kebutuhan Akademik

---

## 📌 Sekilas Proyek
Sistem informasi manajemen perpustakaan modern berbasis web yang dirancang khusus untuk memotong jalur birokrasi manual. Aplikasi ini menangani seluruh siklus sirkulasi buku secara digital, cepat, dan transparan untuk meningkatkan efisiensi administrasi perpustakaan.

---

## 📈 Indikator Proyek

| ✨ Fitur Utama | 🛠️ Teknologi Utama | 📄 Status Dokumen |
| :--- | :--- | :--- |
| • Sirkulasi Otomatis <br> • Kalkulator Denda <br> • Multi-level Akses | • Web-Based Architecture <br> • Relational Database <br> • Responsive Layout | • **SRS:** Lengkap & Valid <br> • **UML:** Terintegrasi <br> • **Kode:** 98 Commits |

---

## 🚀 Fitur Unggulan

* **🔐 Multi-user Authentication**
  Pemisahan hak akses yang ketat antara *Super Admin* (Kepala Perpustakaan), *Petugas* (Sirkulasi), dan *Anggota* (Mahasiswa/Siswa).
* **📖 Smart Catalog Search**
  Pencarian buku pintar berdasarkan judul, penulis, penerbit, atau nomor ISBN secara instan.
* **⏱️ Automated Fine Calculator**
  Sistem otomatis menghitung biaya denda per hari secara tepat ketika masa peminjaman melewati batas toleransi.
* **📊 Dashboard Analitik**
  Grafik ringkas untuk memantau buku yang paling populer, tren peminjaman bulanan, dan status kuota rak.

---

## 📂 Arsitektur Repositori

Klik pada folder untuk melihat detail isi dokumen perancangan:

<details>
<summary>📂 <b>SRS (Software Requirements Specification)</b></summary>
<blockquote>
Memuat seluruh dokumen kebutuhan perangkat lunak formal, termasuk deskripsi umum, kebutuhan fungsional (functional requirements), non-fungsional, serta batasan sistem.
</blockquote>
</details>

<details>
<summary>📂 <b>UML (Unified Modeling Language)</b></summary>
<blockquote>
Berisi aset diagram perancangan sistem yang matang:
<ul>
  <li><b>Use Case Diagram:</b> Interaksi aktor terhadap sistem.</li>
  <li><b>Activity Diagram:</b> Alur proses bisnis peminjaman & pengembalian.</li>
  <li><b>Class Diagram:</b> Struktur database dan hubungan antar objek.</li>
</ul>
</blockquote>
</details>

---

## 💻 Panduan Instalasi Lokal

Ikuti 4 langkah mudah berikut untuk menjalankan proyek di komputer Anda:

### 1. Kloning Repositori
```bash
git clone https://github.com
cd rekayasaperangkatlunak
```

### 2. Persiapan Database
* Aktifkan web server lokal Anda (misal: **XAMPP** atau **Laragon**).
* Masuk ke `phpMyAdmin` atau aplikasi database client Anda.
* Buat database baru bernama `db_perpustakaan`.
* *Import* skema database (jika ada file `.sql` di root folder).

### 3. Konfigurasi Aplikasi
Buka folder proyek, sesuaikan kredensial database pada file konfigurasi environment Anda:
```text
DB_HOST = localhost
DB_NAME = db_perpustakaan
DB_USER = root
DB_PASS = 
```

### 4. Jalankan di Browser
Akses aplikasi melalui alamat URL lokal berikut:
```text
http://localhost/rekayasaperangkatlunak
```

---

## 👥 Tim Pengembang

* **Adin Izzulhaq** — *Lead Developer & System Analyst* • [@adinizzulhaq](https://github.com)
* *(Anda bisa menyisipkan nama rekan kelompok kuliah Anda di sini jika ada)*

---
<p align="center">Dibuat dengan 💻 dan ☕ untuk memenuhi Tugas Besar Rekayasa Perangkat Lunak.</p>
