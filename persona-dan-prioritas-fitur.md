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
| 1 | **Tampilan Katalog Produk (Foto, Nama, Harga, Status Stok)** | **Wajib Ada** | Menjawab langsung *pain* utama Mas Dimas agar pembeli tidak perlu bertanya harga dan ketersediaan menu berulang kali lewat chat. |
| 2 | **Tombol Pesan Otomatis ke WhatsApp (Format Rapi)** | **Wajib Ada** | Sesuai kebiasaan teknologi narasumber yang mengandalkan WA Business, sekaligus mencegah kesalahan pencatatan pesanan. |
| 3 | **Saklar Ubah Status Stok (Tersedia / Habis)** | **Wajib Ada** | Sangat krusial karena stok dimsum sering habis mendadak di jam ramai; pedagang butuh tombol sekali klik yang praktis di layar HP. |
| 4 | **Form Tambah & Edit Menu Baru** | **Penting** | Berguna saat ada menu musiman, namun di awal rilis masih bisa dibantu oleh tim developer jika pedagang belum sempat memperbarui sendiri. |
| 5 | **Filter Kategori Menu (Kopi, Non-Kopi, Camilan)** | **Penting** | Membantu pembeli mencari menu lebih cepat, tetapi jumlah menu Mas Dimas saat ini belum terlalu banyak (sekitar 15 item). |
| 6 | **Kolom Pencarian Nama Produk** | **Pelengkap** | Cukup membantu kenyamanan pembeli, tapi belum mendesak selama daftar katalog masih bisa digulir dalam satu halaman singkat. |
| 7 | **Label Promo / Menu Terlaris (*Best Seller*)** | **Pelengkap** | Menarik perhatian pembeli, namun tidak menyelesaikan masalah utama antrean chat dan pengecekan stok. |
| 8 | **Integrasi Pembayaran Otomatis (QRIS / Transfer Virtual Account)** | **Nanti Dulu** | Terlalu kompleks untuk dibangun di Bulan 2 dan berisiko membuat pedagang ragu karena terbiasa menerima pembayaran tunai/QRIS statis. |
| 9 | **Dashboard Laporan Keuangan & Grafik Penjualan** | **Nanti Dulu** | Terbantah saat wawancara; narasumber lebih memilih mencatat keuangan secara manual di buku tulis. |
| 10 | **Fitur Ulasan & Rating Pelanggan** | **Nanti Dulu** | Tidak menjawab penderitaan utama pedagang saat ini dan membutuhkan moderasi tambahan agar tidak disalahgunakan. |

---

## 3. Catatan Hasil Kritik AI & Keputusan Squad

Setelah menguji persona dan 3 fitur **Wajib Ada** menggunakan asisten AI, berikut evaluasi dan keputusan akhir squad:

* **Masukan AI yang Dipakai:** 
  * *Kritik AI:* AI menyarankan agar fitur pengelolaan stok tidak dibuat dalam bentuk form angka yang rumit, melainkan cukup tombol geser (*toggle*) sederhana **"Tersedia / Habis"**.
  * *Alasan Squad:* Diterima sepenuhnya karena selaras dengan kondisi narasumber yang sibuk melayani pembeli di gerobak dan hanya punya waktu beberapa detik untuk memperbarui status menu lewat HP.
* **Masukan AI yang Ditolak:** 
  * *Kritik AI:* AI menyarankan untuk menunda fitur **Saklar Ubah Status Stok** ke fase berikutnya dan menggantinya dengan fitur **Jam Buka/Tutup Toko Otomatis**.
  * *Alasan Squad:* Ditolak berdasarkan data wawancara. Masalah terbesar narasumber bukanlah pembeli yang chat di luar jam operasional, melainkan pembeli yang kecewa saat toko masih buka tetapi varian dimsum favoritnya sudah habis terjual.