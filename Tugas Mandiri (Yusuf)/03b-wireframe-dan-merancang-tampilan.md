# Tugas Mandiri 03b — Wireframe HTML/CSS Hitam-Putih
Nama: [Muhammad Yusuf Ali Rahman]

## 1. Kode HTML & CSS:
<html>
  <head>
    <style>
      body {
        font-family: sans-serif;
        padding: 20px;
        background-color: #f9f9f9;
      }
      .container {
        display: flex;
        gap: 20px;
      }
      .card {
        border: 2px solid #000;
        padding: 15px;
        width: 200px;
        background-color: #fff;
      }
      .product-title {
        font-weight: bold;
        margin-bottom: 10px;
      }
      .price {
        margin-bottom: 15px;
      }
      /* Tombol Aktif (Stok Ada) */
      .btn-active {
        background-color: #000;
        color: #fff;
        border: 2px solid #000;
        padding: 8px 12px;
        cursor: pointer;
        width: 100%;
      }
      /* Tombol Nonaktif (Stok Habis) */
      .btn-disabled {
        background-color: #fff;
        color: #888;
        border: 2px solid #888;
        padding: 8px 12px;
        cursor: not-allowed;
        width: 100%;
      }
    </style>
  </head>
  <body>
    <div class="container">
      <!-- Produk Normal (Stok Ada) -->
      <div class="card">
        <div class="product-title">Produk A</div>
        <div class="price">Rp 50.000</div>
        <button class="btn-active">Beli Sekarang</button>
      </div>

      <!-- Produk Stok Habis -->
      <div class="card">
        <div class="product-title">Produk B</div>
        <div class="price">Rp 75.000</div>
        <button class="btn-disabled" disabled>Stok Habis</button>
      </div>
    </div>
  </body>
</html>

## 2. Refleksi Singkat:
Mengubah kerangka (wireframe) menjadi kode HTML dan CSS hitam-putih membantu saya melihat bentuk dasar tata letak suatu halaman dengan jelas—termasuk cara membedakan tampilan tombol saat produk bisa dibeli dan saat stoknya kosong, agar nanti lebih mudah dipelajari pada tahap pembuatan aplikasi selanjutnya.