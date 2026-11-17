# Tugas Mandiri 03b — Wireframe HTML/CSS Hitam-Putih

Nama: [Dedy]

## 1. Kode HTML & CSS:

```html
<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Wireframe Kartu Produk</title>
  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
      font-family: sans-serif;
    }

    body {
      padding: 24px;
      background-color: #ffffff;
    }

    .product-grid {
      display: flex;
      gap: 16px;
      flex-wrap: wrap;
    }

    /* Gaya Dasar Kartu Produk (Stok Tersedia) */
    .card {
      width: 220px;
      border: 2px solid #000000;
      border-radius: 16px;
      overflow: hidden;
      background-color: #ffffff;
      display: flex;
      flex-direction: column;
    }

    .card-image {
      height: 180px;
      background-color: #d9d9d9;
      border-bottom: 2px solid #000000;
      position: relative;
      padding: 12px;
      display: flex;
      align-items: flex-end;
    }

    .card-body {
      padding: 16px;
      display: flex;
      flex-direction: column;
      gap: 8px;
    }

    .product-title {
      font-size: 16px;
      font-weight: normal;
      color: #000000;
    }

    .product-price {
      font-size: 14px;
      color: #000000;
      margin-bottom: 8px;
    }

    /* Tombol Aktif */
    .btn {
      width: 100%;
      padding: 10px 12px;
      border-radius: 20px;
      font-size: 12px;
      cursor: pointer;
      text-align: center;
    }

    .btn-active {
      background-color: #d9d9d9;
      border: 2px solid #000000;
      color: #000000;
    }

    /* Gaya Khusus Kartu Stok Habis */
    .card.out-of-stock {
      border-color: #a6a6a6;
    }

    .card.out-of-stock .card-image {
      border-bottom: none;
    }

    .badge-detail {
      background-color: #ffffff;
      border: 1.5px solid #000000;
      border-radius: 12px;
      padding: 4px 10px;
      font-size: 11px;
      color: #000000;
    }

    .card.out-of-stock .product-title,
    .card.out-of-stock .product-price {
      color: #8c8c8c;
    }

    /* Tombol Nonaktif (Disabled) */
    .btn-disabled {
      background-color: #e6e6e6;
      border: none;
      color: #8c8c8c;
      cursor: not-allowed;
    }
  </style>
</head>
<body>

  <div class="product-grid">
    <!-- Kartu 1: Stok Tersedia -->
    <div class="card">
      <div class="card-image"></div>
      <div class="card-body">
        <h3 class="product-title">Nasi Padang</h3>
        <p class="product-price">Rp. 20.000</p>
        <button class="btn btn-active">Tambahkan ke keranjang</button>
      </div>
    </div>

    <!-- Kartu 2: Stok Habis -->
    <div class="card out-of-stock">
      <div class="card-image">
        <span class="badge-detail">Lihat Detail</span>
      </div>
      <div class="card-body">
        <h3 class="product-title">Pisang Keju Coklat</h3>
        <p class="product-price">Rp. 15.000</p>
        <button class="btn btn-disabled" disabled>Stok Habis</button>
      </div>
    </div>
  </div>

</body>
</html>
```

## 2. Refleksi Singkat:

Mengubah *wireframe* menjadi kode HTML dan CSS statis hitam-putih membantu saya memahami struktur hierarki komponen kartu produk secara nyata. Saya jadi melihat bagaimana perubahan *state* (kondisi stok tersedia vs habis) memengaruhi hierarki visual—mulai dari warna garis tepi (*border*), kontras teks, hingga penggunaan atribut `disabled` pada tombol—sebagai dasar pembuatan *props* dan *conditional rendering* di React nanti.
