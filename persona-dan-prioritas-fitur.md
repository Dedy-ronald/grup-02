# Persona Merchant & Prioritas Fitur Platform UMKM
## 1. Lembar Persona Pedagang UMKM

* **Profil:** Mas yanto (24 Tahun) — Pemilik *"toko plastik dan bahan kue"*, cibinong, bogor
* **Perilaku Teknologi:** Menggunakan HP Android kelas menengah, dan juga komputer.
* **Masalah Terbesar (*Pains*):** 
  * repot melayani pembeli walk in yang menanyakan barang harga sehingga harus bolak balik mengambil/mengecek barang serta menghadapi proses tawar menawar.
  * pernah mengalami human eror berupa barang pesanan yang lupa dimasukkan ke dalam paket pelanggan.
  * **Kutipan Asli:** *"Kalau lewat hp atau whatsapp jarang terkendala sih jek, paling yang dateng langsung biasanya, nanya2 barang sama harga jadi harus bolak balik ambil barang dan ada jugaa yang nawar2 gitu. Kalau salah catat ga pernah jekk cuma kadang ada barang yang lupa di taruh kalau ada pesanan gitu jadi minta maaf sama pelanggannya"*
* **Harapan Utama (*Gains*):** dapat meningkatkan pengelolaan usaha dengan beralih menggunakan aplikasi digital.

### Catatan Evaluasi Hipotesis Wawancara
* **Hipotesis Terbukti:** Pencatatan stok masih dilakukan secara manual/mengandalkan ingatan serta rawan human error (barang pesanan lupa dimasukkan), dan narasumber memiliki keterbukaan untuk beralih ke aplikasi.
* **Hipotesis Terbantah:**  Dugaan bahwa pedagang sering kewalahan melayani pesanan lewat WhatsApp dan bingung menggunakan teknologi baru di HP tidak terbukti—justru pelayanan via WhatsApp jarang terkendala dan narasumber sebagai Gen Z sudah familiar dengan teknologi.

---

## 2. Tabel Prioritas Fitur (Metode MoSCoW)

Berdasarkan hasil **Uji Cepat**, berikut adalah pemilahan 10 ide fitur untuk rilis pertama di Bulan 2 (maksimal 3 fitur **Wajib Ada**):

| No | Ide Fitur | Kategori | Alasan Berdasarkan Persona & Uji Cepat |
| :--- | :--- | :--- | :--- |
| 1 | **Katalog** | **Wajib Ada** | Menggantikan pencatatan manual dan ketergantungan pada ingatan, sehingga data stok serta varian produk (plastik dan bahan kue) terorganisir dengan rapi di satu tempat. |
| 2 | **Dashboard Penjual** | **Wajib Ada** |Membantu pedagang memantau status stok secara cepat (real-time) untuk meminimalisir barang pesanan yang lupa dimasukkan dan mengetahui kapan harus melakukan restock. |
| 3 | **Automisasi** | **Penting** | Mempermudah pengelolaan inventaris yang beragam dan memiliki banyak variasi ukuran/berat (seperti berbagai jenis plastik dan bahan kue) tanpa repot menghitung manual. |
| 4 | **Kolom pencarian** | **Penting** | Membantu pedagang atau pembeli mencari barang dan mengecek harga dengan cepat tanpa harus bolak-balik mengambil barang fisik saat melayani pembeli walk-in. |
| 5 | **WA in web** | **Pelengkap** | Mengintegrasikan atau memudahkan pengelolaan pesanan yang masuk via WhatsApp karena sebagian pelanggan kerap memesan melalui jalur tersebut. |
| 6 | **Navbar iklan/promo** | **Pelengkap** |  Digunakan untuk menampilkan informasi promo atau diskon menarik guna mengurangi proses tawar-menawar harga dengan pembeli langsung. |
| 7 | **Integrasi pihak ketiga** | **Nanti dulu** | Fokus utama saat ini adalah menyelesaikan masalah operasional internal (stok dan pencatatan pesanan), sehingga integrasi eksternal yang kompleks belum mendesak untuk tahap awal. |


---

## 3. Catatan Hasil Kritik AI & Keputusan Squad

Setelah menguji persona dan 3 fitur **Wajib Ada** menggunakan asisten AI, berikut evaluasi dan keputusan akhir squad:

* **Masukan AI yang Dipakai:** 
  * *Kritik AI:* AI menyarankan agar Jangan buat fitur yang terlalu rumit dulu. Karena masalah terbesar Mas Yanto adalah kerepotan melayani pembeli walk-in dan barang pesanan yang kadang lupa dimasukkan, pastikan versi pertama aplikasi Anda benar-benar fokus menjadi katalog digital yang cepat diakses (baik lewat HP maupun komputer toko) serta dilengkapi fitur checklist pesanan."**.
  * *Alasan Squad:* Diterima sepenuhnya karena selaras dengan kondisi narasumber yang sibuk melayani pembeli.
* **Masukan AI yang Ditolak:** 
  * *Kritik AI:* AI menyarankan untuk menunda fitur automisasi Berdasarkan masalah Mas Yanto, prioritas utamanya saat ini adalah mendigitalisasi data produk agar mudah dicek saat pembeli datang (walk-in) dan meminimalisir barang pesanan yang lupa dimasukkan. Fitur automasi inventaris yang rumit (seperti otomatisasi perhitungan varian berat/ukuran yang kompleks) belum mendesak di tahap awal. Yang jauh lebih penting untuk versi pertama adalah Katalog yang rapi dan Dashboard/Indikator Status Stok Cepat untuk mengecek barang secara real-time.
  * *Alasan Squad:* Ditolak berdasarkan data wawancara. Masalah terbesar narasumber bukanlah pembeli yang chat di luar jam operasional, melainkan pembeli yang langsung datang ke toko bolak balik hanya untuk bertanya harga.
