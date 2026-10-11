# Laporan Praktikum Desain Web A
## Pertemuan 4 — Box Model, Class Reusable, dan Responsive Layout

### Identitas Praktikan
- Nama: Muhammad Ryza Mahameru
- NIM: 4525210048
- Program Studi: Teknik Informatika
- Fakultas: Teknik
- Universitas: Universitas Pancasila
- Mata Kuliah: Praktikum Desain Web A
- Pertemuan: 4

### 1. Tujuan Praktikum
1. Memisahkan struktur halaman HTML dan tampilan CSS.
2. Menggunakan box model untuk mengatur ukuran dan jarak elemen.
3. Memanfaatkan class reusable untuk menghindari penulisan aturan berulang.
4. Membuat tampilan yang menyesuaikan layar desktop maupun ponsel.
5. Mengatur tiga kartu layanan dengan Flexbox.
6. Menyimpan gaya halaman pada file CSS eksternal.

### 2. Dasar Teori
**Box model** terdiri dari content, padding, border, dan margin. Dengan `box-sizing: border-box`, padding dan border dihitung sebagai bagian dari lebar elemen.

**Class reusable** merupakan selector CSS yang dapat digunakan pada lebih dari satu elemen. Pada proyek ini, `.heading` mengatur judul bagian dan `.btn` mengatur tombol.

**Flexbox** membantu menyusun kartu layanan dalam satu baris. Ketika lebar layar mengecil, susunannya diubah menjadi kolom.

**Media query** memungkinkan aturan tertentu aktif sesuai ukuran layar. Proyek ini menggunakan `@media (max-width: 767px)` untuk menata ulang navigasi, jarak, ukuran judul, dan kartu.

### 3. Alat dan Bahan
- HTML5 dan CSS3
- Visual Studio Code
- Browser seperti Google Chrome atau Microsoft Edge
- Live Server (opsional)

### 4. Struktur Proyek
```text
arunika_tema_baru/
├── index.html
├── css/
│   └── style.css
└── README.md
```

### 5. Pembahasan
Landing page Arunika Studio terdiri dari navigasi, bagian pengenalan, tiga kartu layanan, dan informasi kontak. Isi teks diperbarui agar lebih menekankan layanan kreatif dan solusi digital.

Warna hijau hutan digunakan untuk header dan footer, krem sebagai latar, serta jingga sebagai aksen tombol dan penanda kartu. Kombinasi ini memberikan kesan hangat sekaligus tetap menjaga kontras teks.

Class `.heading` dan `.btn` menunjukkan penggunaan gaya yang dapat dipakai kembali. Bagian layanan menggunakan Flexbox agar kartu tersusun sejajar pada desktop. Media query mengubah kartu menjadi satu kolom pada layar di bawah 768px.

### 6. Cara Menjalankan
1. Ekstrak folder proyek.
2. Buka folder `arunika_tema_baru` melalui VS Code.
3. Pastikan file `index.html` dan folder `css` berada pada tingkat yang sama.
4. Buka `index.html`, lalu pilih **Open with Live Server** atau jalankan file melalui browser.
5. Untuk memeriksa versi ponsel, buka Developer Tools dan aktifkan Device Toolbar.

### 7. Kesimpulan
Pembuatan halaman ini menerapkan pemisahan HTML dan CSS, box model, class reusable, Flexbox, serta media query. Konten dan palet warna diubah, sedangkan struktur utama, navigasi, jumlah kartu layanan, dan perilaku responsif tetap dipertahankan.
