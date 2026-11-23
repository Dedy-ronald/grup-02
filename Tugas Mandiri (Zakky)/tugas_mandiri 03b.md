# Tugas Mandiri 03b — Wireframe HTML/CSS Hitam-Putih
Nama: [zaky]

## 1. Kode HTML & CSS:
```html
<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Wireframe Kartu Produk</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>

  <main class="katalog-container">
    <!-- Kartu Produk 1: Normal / Tersedia -->
    <article class="product-card">
      <div class="image-placeholder">[ Foto Produk ]</div>
      <span class="status-badge">Tersedia</span>
      <h2 class="product-title">Cup Bolu Kukus (Isi 50)</h2>
      <p class="product-price">Rp 8.500</p>
      <button type="button" class="btn btn-active">Tambah ke Keranjang</button>
    </article>

    <!-- Kartu Produk 2: Stok Habis -->
    <article class="product-card out-of-stock">
      <div class="image-placeholder">[ Foto Produk ]</div>
      <span class="status-badge">Stok Habis</span>
      <h2 class="product-title">Mika Brownies Sekat</h2>
      <p class="product-price">Rp 12.000</p>
      <button type="button" class="btn btn-disabled" disabled>Stok Habis</button>
    </article>
  </main>

</body>
</html>
```

* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}

body {
  font-family: sans-serif;
  background-color: #ffffff;
  color: #111111;
  padding: 24px;
}

.katalog-container {
  display: flex;
  gap: 20px;
  flex-wrap: wrap;
}

/* Kartu Produk Wireframe */
.product-card {
  width: 240px;
  border: 2px solid #111111;
  padding: 16px;
  background-color: #ffffff;
  display: flex;
  flex-direction: column;
  gap: 10px;
}

.product-card.out-of-stock {
  border-style: dashed;
  color: #555555;
}

/* Kotak Placeholder Gambar */
.image-placeholder {
  width: 100%;
  height: 130px;
  border: 1px dashed #111111;
  background-color: #f4f4f4;
  display: flex;
  align-items: center;
  justify-content: center;
  font-size: 13px;
  color: #555555;
}

/* Label Status */
.status-badge {
  align-self: flex-start;
  font-size: 12px;
  padding: 3px 8px;
  border: 1px solid #111111;
  background-color: #ffffff;
}

.out-of-stock .status-badge {
  border-color: #777777;
  color: #555555;
}

.product-title {
  font-size: 16px;
  font-weight: bold;
}

.product-price {
  font-size: 14px;
}

/* Gaya Dasar Tombol */
.btn {
  margin-top: 6px;
  padding: 10px 12px;
  font-family: sans-serif;
  font-size: 14px;
  border: 2px solid #111111;
  width: 100%;
}

/* Tombol Aktif (Hitam Solid, Teks Putih) */
.btn-active {
  background-color: #111111;
  color: #ffffff;
  cursor: pointer;
}

.btn-active:hover {
  background-color: #333333;
}

/* Tombol Nonaktif / Disabled (Abu-abu Pudar, Tidak Bisa Diklik) */
.btn-disabled {
  background-color: #e5e5e5;
  color: #777777;
  border-color: #999999;
  cursor: not-allowed;
}

## 2. Refleksi Singkat:
Menyusun wireframe hitam-putih mengingatkan bahwa tata letak yang baik tidak butuh hiasan rumit sejak awal—cukup kejelasan struktur, jarak yang rapi, dan pembedaan status yang langsung terbaca mata. Ketika kondisi "tersedia" dan "stok habis" dibedakan secara tegas lewat bingkai dan status tombol, pengguna bisa mengambil keputusan lebih cepat tanpa menebak-nebak.