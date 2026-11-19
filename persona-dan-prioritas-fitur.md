
# Persona Merchant & Prioritas Fitur Platform UMKM
## 1. Lembar Persona Pedagang UMKM

* **Profil:** Mas Dimas (29 Tahun) — Pemilik *"Kopi & Dimsum Pojok"*, Yogyakarta
* **Perilaku Teknologi:** Menggunakan HP Android kelas menengah (RAM 4GB), aktif membalas pesan lewat WhatsApp Business, rutin mengunggah foto menu ke Instagram Story & status WA, namun belum pernah memakai aplikasi kasir (POS) karena merasa tampilannya terlalu rumit.
* **Masalah Terbesar (*Pains*):** 
  * Pembeli sering menanyakan daftar menu, harga, dan ketersediaan varian rasa lewat chat satu per satu setiap malam.
  * Pesanan sering terlewat atau salah catat saat jam ramai karena chat pembeli bertumpuk dengan chat pribadi.
  * **Kutipan Asli:** *"Kalau lagi rame di gerobak, susah banget balesin WA satu-satu yang cuma nanya 'Bang, dimsum mentai masih ada nggak? Harganya berapa?'. Kadang pas dibales orangnya udah keburu beli di tempat lain."*
* **Harapan Utama (*Gains*):** Punya satu tautan (link) daftar menu yang selalu update soal stok dan harga, supaya pembeli bisa langsung pilih menu dan kirim format pesanan yang rapi ke WhatsApp.

### Catatan Evaluasi Hipotesis Wawancara
* **Hipotesis Terbukti:** Pedagang sangat membutuhkan tombol pemesanan yang langsung mengarah ke WhatsApp karena mereka sudah terbiasa bertransaksi di sana dan enggan belajar sistem pembayaran baru.
* **Hipotesis Terbantah:** Awalnya tim mengira pedagang butuh fitur rekap laporan keuangan bulanan otomatis. Faktanya, narasumber sudah nyaman mencatat pemasukan harian di buku tulis dan justru lebih pusing mengurus stok harian yang cepat habis.

---

## 2. Tabel Prioritas Fitur (Metode MoSCoW)

Berdasarkan hasil **Uji Cepat**, berikut adalah pemilahan 10 ide fitur untuk rilis pertama di Bulan 2 (maksimal 3 fitur **Wajib Ada**):

| No | Ide Fitur | Kategori | Alasan Berdasarkan Persona & Uji Cepat |
| :--- | :--- | :--- | :--- |
| 1 | **Indikator Status Stok Cepat (Tersedia/Menipis/Habis)** | **Wajib Ada** | Pedagang hanya mencatat barang ketika stoknya sudah mulai sedikit atau habis untuk di-order ulang.. |
| 2 | **Daftar Belanja Ulang Otomatis (Auto-Restock List)** | **Wajib Ada** | Pedagang mencatat barang yang menipis secara manual untuk keperluan order ke pemasok (supplier). |
| 3 | **Kategorisasi Produk & Varian Ukuran/Berat** | **Wajib Ada** | Jenis barang sangat beragam dan memilliki banyak spesifikasi (Plastik: kantong, mika, cup, sedotan; bahan kue: tepung, gula, cokelat, messes, mentega). |
| 4 | **Fitur untuk Mengatasi Kerepotan Pelayanan di Toko Fisik (Walk-in)** | **Penting** | Pedagang sering kerepotan harus bolak-balik mengambil dan mengecek harga saat pembeli datang langsung dan bertanya-tanya. |
| 5 | **Katalog QR Code di Meja Kasir / Depan Toko** | **Penting** | Mayoritas pembeli datang langsung ke toko (walk-in) untuk melihat-lihat dan menanyakan barang serta harga. |
| 6 | **Tampilan Harga Bertingkat (Eceran vs. Grosir) yang Transparan** | **Pelengkap** |  Pembeli yang datang langsung sering melakukan tawar-menawar harga. |
| 7 | **Fitur Share Katalog Cepat untuk Balas Chat Tanya Harga** | **Pelengkap** | Banyak pembeli di WhatsApp hanya bertanya harga dan ketersediaan stok tanpa langsung membeli. |
| 8 | **Rekap Pesanan Otomatis ke WhatsApp (1-Click WA Order)** | **Nanti Dulu** | Pelanggan tetap sudah terbiasa memesan via WhatsApp, sementara non-pelanggan sering bertanya stok dan harga lewat chat. |
| 9 | **Fitur "Pesan Ulang" (Repeat Order) untuk Pelanggan Tetap** | **Nanti Dulu** | Pembeli yang memesan via WhatsApp umumnya adalah pelanggan tetap yang membeli kebutuhan rutin. |
| 10 | **Unggah Produk Cepat / Bulk Upload via Foto** | **Nanti Dulu** | Narasumber adalah Gen Z yang melek teknologi, tetapi stok barang di toko plastik dan bahan kue jumlahnya ratusan item. |

---

## 3. Catatan Hasil Kritik AI & Keputusan Squad

Setelah menguji persona dan 3 fitur **Wajib Ada** menggunakan asisten AI, berikut evaluasi dan keputusan akhir squad:

* **Masukan AI yang Dipakai:** 
  * *Kritik AI:* AI menyarankan agar memperjelas skala inventaris (berapa banyak SKU atau jenis barang yang dimiliki) dan karakteristik produk bahan kue (apakah banyak barang curah atau pertimbangan yang perhitungannya rumit)"**.
  * *Alasan Squad:* Diterima sepenuhnya karena selaras dengan kondisi narasumber yang sibuk melayani pembeli.
* **Masukan AI yang Ditolak:** 
  * *Kritik AI:* AI menyarankan untuk menunda fitur daftar belanja ulang otomatis karena berdasarkan wawancara, masalah terbesar mas yanto saat ini adalah pencatatan stok manual dan barang pesanan yang sering lupa ditaruh atau dimasukkan, bukan kesulitan menghitung kapan harus belanja ke suplier..
  * *Alasan Squad:* Ditolak berdasarkan data wawancara. Masalah terbesar narasumber bukanlah pembeli yang chat di luar jam operasional, melainkan pembeli yang langsung datang ke toko bolak balik hanya untuk bertanya harga.
