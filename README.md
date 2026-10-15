<div align="center">
  <img src="https://github.com/user-attachments/assets/bc206a62-4b37-4064-a1af-872e7a157463" width="200" alt="MENTARI Logo">

  # MENTARI MOD
  ### *Manajemen Terpadu Pembelajaran Daring*

  [![GitHub issues](https://img.shields.io/github/issues/alfinasinaja/mentari-modv2?color=green&style=for-the-badge)](https://github.com/alfinasinaja/mentari-modv2/issues)
  [![GitHub stars](https://img.shields.io/github/stars/alfinasinaja/mentari-modv2?style=for-the-badge)](https://github.com/alfinasinaja/mentari-modv2/stargazers)
  [![GitHub license](https://img.shields.io/github/license/alfinasinaja/mentari-modv2?style=for-the-badge)](LICENSE)
</div>

## Tentang MENTARI MOD

**MENTARI MOD** adalah ekstensi browser untuk platform **MENTARI** (*Manajemen Terpadu Pembelajaran Daring*) Universitas Pamulang. Ekstensi ini membantu mahasiswa melihat forum diskusi, quiz, dan kuesioner yang belum dikerjakan dari satu popup, serta mempermudah penggunaan MENTARI dengan berbagai shortcut.

Repositori ini adalah **modifikasi** dari proyek [MENTARI MOD](https://github.com/lukman754/Mentari-Unpam) oleh [Lukman Muludin](https://github.com/lukman754), yang dirilis di bawah lisensi MIT. Lihat bagian [Atribusi dan Lisensi](#-atribusi-dan-lisensi).

<div align="center">
  <img alt="Tampilan MENTARI MOD" src="https://raw.githubusercontent.com/alfinasinaja/mentari-modv2/refs/heads/gh-pages/src/assets/mockup.png" />
</div>

## ✨ Fitur Utama

### 🧭 Popup Mentari Mod

Tombol **Mentari Mod** muncul di header MENTARI. Klik untuk membuka popup yang berisi beberapa tab:

| Tab | Fungsi |
| --- | --- |
| **Forum** | Daftar quiz, forum diskusi, dan kuesioner yang belum selesai di **semua pertemuan** dari semua mata kuliah. Ada juga link cepat ke halaman presensi. |
| **Riwayat** | Riwayat topik dan balasan forum yang sudah kamu kirim, dikelompokkan per mata kuliah. Setiap topik punya link langsung ke halaman forumnya. |
| **Mahasiswa** | Daftar mahasiswa per kelas, lengkap dengan NIM dan peringkat jumlah peserta. |
| **Pengaturan** | Pengaturan tampilan dan konfigurasi popup. |

### 📚 Pelacakan Forum Diskusi

- Forum yang belum dibalas ditandai di tab **Forum**, dari semua pertemuan sekaligus, tanpa perlu membuka pertemuan satu per satu.
- Isi topik bisa dibaca langsung di popup.
- Balasan bisa dikirim langsung dari popup. Form balasan mendukung pemilihan tujuan balasan dan lampiran.

### 🗂️ Riwayat Forum per Mata Kuliah

- Menampilkan semua topik yang pernah kamu balas, dari semua pertemuan, dikelompokkan per mata kuliah.
- Riwayat diambil dari server MENTARI, jadi balasan yang dikirim lewat Mentari Mod maupun langsung di MENTARI ikut muncul.
- Data dimuat saat mata kuliah dibuka. Tombol refresh di tab Riwayat memuat ulang data.

### 📝 Kuesioner

- Kuesioner yang belum diisi tampil di tab **Forum**.
- Di halaman kuesioner, ekstensi bisa memilih jawaban default **"Ya"** untuk setiap pertanyaan, lalu menekan tombol submit.
- Gunakan fitur ini dengan bijak dan pastikan jawabannya sesuai dengan kondisi kamu.

### ⚡ QuickSurvey

Di halaman survei my.unpam, panel QuickSurvey membantu mengisi survei dengan cepat. Ada tiga mode:
- **Setuju**: memilih opsi setuju di semua pertanyaan.
- **Random**: memilih jawaban secara acak.
- **Bintang 1–5**: memberi rating yang sama untuk semua pertanyaan.

### 🗓️ Presensi

Di halaman my.unpam, popup presensi menampilkan kelas dan item presensi. Ada juga link cepat ke halaman presensi dari tab Forum.

### 📋 Salin Topik Forum

Di halaman topik forum, tombol **Salin Topik** menyalin isi topik ke clipboard, misalnya untuk ditempel ke catatan.

### 🐔 Mentari Fox Playground

Panel kecil di halaman dashboard MENTARI berisi pet mini yang bisa kamu ajak main (rubah dan ayam). Mode malam dan siang berganti otomatis mengikuti jam perangkat: malam dimulai pukul 18.00 dan berakhir pukul 05.59. Tombol 🌙 atau tombol **N** tetap bisa dipakai untuk mengubahnya secara manual.

### 🎨 Tampilan

- Popup dan semua komponen memakai tema bertema matahari (warna oranye dan kuning).
- Halaman login MENTARI mendapat kartu informasi versi dan tampilan latar yang diperbarui.

## 🔄 Perbedaan dari Versi Asli

- Tampilan popup dan komponen lain dibuat ulang dengan tema matahari.
- Tab **Riwayat** baru untuk melihat topik dan balasan forum per mata kuliah.
- Mode malam dan siang pada pet berganti otomatis sesuai jam perangkat.
- Pesan error dari server dibuat lebih jelas.

## 📦 Download

<p align="center">
  <a href="https://github.com/alfinasinaja/mentari-modv2/releases/latest" style="display: block; width: 60%;">
    <img src="https://img.shields.io/badge/⬇%20Download-Mentari%20Mod-00C853?style=for-the-badge&logo=github&logoColor=white"/>
  </a>
</p>

## 🛠️ Cara Instalasi

### Windows / macOS (Chrome, Edge, Brave)

```
1. Unduh file ZIP ekstensi dari halaman Releases
2. Ekstrak file ZIP ke folder di komputer Anda
3. Buka browser Chromium (Chrome, Edge, atau Brave)
4. Ketik chrome://extensions/ di address bar
5. Aktifkan "Mode Pengembang" (toggle di pojok kanan atas)
6. Klik "Load unpacked" dan pilih folder hasil ekstraksi
7. Ekstensi siap digunakan
```

### Mises Browser (iOS / Android)

```
1. Unduh Mises Browser dari App Store atau Play Store
2. Buka Mises Browser di perangkat Anda
3. Ketuk menu (tiga titik) di pojok kanan atas
4. Pilih "Extensions"
5. Aktifkan "Developer Mode"
6. Klik "+ (from .zip/.crx/.user.js)"
7. Pilih file ZIP Mentari Mod
8. Refresh halaman MENTARI
```

## ❓ FAQ

**Di halaman mana ekstensi ini bekerja?**
Di halaman MENTARI (`mentari.unpam.ac.id`) dan my.unpam (`my.unpam.ac.id`). Di halaman lain, ekstensi tidak aktif.

**Apakah ekstensi ini mengerjakan quiz atau forum secara otomatis?**
Tidak. Tab Forum hanya menampilkan daftar yang belum selesai dan memudahkan kamu membalas. Pengisian kuesioner dan QuickSurvey hanya berjalan saat kamu menekan tombolnya atau membuka halamannya, dan tetap menjadi tanggung jawab kamu.

**Popup tidak bisa dibuka atau daftar forum kosong. Apa yang harus dilakukan?**
Muat ulang halaman MENTARI, lalu klik tombol refresh di popup. Pastikan kamu sudah login.

**Riwayat tidak menampilkan balasan terbaru?**
Tekan tombol refresh di tab Riwayat. Data diambil ulang dari server MENTARI.

**Kenapa tombol Mentari Mod tidak muncul di header?**
Pastikan ekstensi sudah aktif di `chrome://extensions/` dan halaman sudah dimuat ulang. Tombol hanya muncul di halaman MENTARI yang punya header dengan tombol tema.

## 📄 Atribusi dan Lisensi

Proyek ini dilisensikan di bawah [MIT License](LICENSE).

- Proyek asli: [MENTARI MOD](https://github.com/lukman754/Mentari-Unpam) oleh [Lukman Muludin](https://github.com/lukman754). Hak cipta © 2025 Lukman Muludin.
- Modifikasi dan pengembangan lanjutan: © 2026 Alfinas Sandi.

Lisensi MIT mengizinkan penggunaan, penyalinan, modifikasi, dan distribusi, dengan syarat notice hak cipta dan teks lisensi tetap disertakan. Jangan menghapus file `LICENSE` maupun atribusi di atas.

## ⚠️ Disclaimer

Mentari Mod adalah proyek independen. Proyek ini **tidak berafiliasi secara resmi** dengan Universitas Pamulang maupun pengelola platform MENTARI. Penggunaan ekstensi sepenuhnya menjadi tanggung jawab pengguna. Pastikan penggunaannya mengikuti kebijakan dan ketentuan platform yang berlaku.

---

<div align="center">
  <p>Dibuat dengan ❤️ untuk mahasiswa UNPAM</p>
  <p>Terima kasih kepada <a href="https://github.com/lukman754">Lukman Muludin</a> atas proyek aslinya.</p>
</div>
