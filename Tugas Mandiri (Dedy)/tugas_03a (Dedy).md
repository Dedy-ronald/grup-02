# Tugas Mandiri 03a — Observasi Hambatan UX
Nama: [Dedy]

## 1. Situasi Pengamatan:
Ayah saya ingin mentransfer uang ke rekening saudara menggunakan aplikasi mobile banking, namun beliau sempat bingung dan hampir salah melakukan transaksi.

## 2. Masalah UX yang Ditemukan:
Pada halaman konfirmasi transfer, tombol "Batal" dan tombol "Lanjut/Transfer" diletakkan bersebelahan dengan ukuran, bentuk, dan warna latar belakang yang hampir serupa (hanya dibedakan oleh garis tepi tipis). Selain itu, teks peringatan di atas tombol menggunakan istilah perbankan yang kaku dan berukuran kecil. Ayah saya sempat ragu tombol mana yang harus ditekan dan hampir menekan tombol "Batal" karena posisinya berada di sisi kanan yang biasa beliau tekan untuk melanjutkan langkah.

## 3. Prinsip Emas UX yang Dilanggar:
- **Prinsip 1 (Konsistensi & Standar):** Posisi tombol aksi utama ("Lanjut") diletakkan di sebelah kiri, berlawanan dengan kebiasaan umum aplikasi seluler yang menempatkan tombol aksi positif di sebelah kanan.
- **Prinsip 3 (Hierarki Visual & Kontras):** Tidak ada perbedaan warna yang mencolok antara tombol aksi utama dan tombol pembatalan, sehingga pengguna sulit membedakan prioritas tindakan secara sekilas.
- **Prinsip 4 (Pencegahan Kesalahan):** Penempatan dua tombol berlawanan fungsi secara berdekatan tanpa jarak yang cukup meningkatkan risiko pengguna salah pencet saat terburu-buru.

## 4. Solusi Perbaikan Berdasarkan Prinsip UX:
Berikan kontras warna yang tegas pada tombol aksi utama (misalnya warna biru solid dengan teks putih untuk "Transfer") dan buat tombol "Batal" hanya berupa teks biasa (*ghost button*) tanpa bingkai agar tidak bersaing secara visual. Posisikan tombol utama di sisi kanan atau buat tombol melebar penuh (*full-width*) secara vertikal dengan jarak antar-tombol minimal 16 pixel agar lebih aman disentuh.
