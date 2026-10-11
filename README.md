# Inventory Management System

## 1. Deskripsi Aplikasi

Inventory Management System adalah aplikasi berbasis web yang dibuat untuk membantu mengelola data barang dan stok persediaan. Aplikasi ini menggunakan PHP sebagai bahasa pemrograman dan MySQL sebagai database untuk menyimpan data.

Aplikasi ini dibuat untuk memudahkan pengguna dalam mengelola produk, kategori, supplier, serta mencatat barang masuk dan barang keluar agar jumlah stok tetap terkontrol.

## 2. Tujuan Aplikasi

Tujuan pembuatan aplikasi ini adalah:
- Memudahkan pengelolaan data produk.
- Mengelola data kategori dan supplier.
- Mencatat transaksi barang masuk dan barang keluar.
- Memantau jumlah stok barang.
- Menampilkan informasi produk yang stoknya hampir habis.
- Menjaga agar data persediaan tersimpan dengan rapi di database.

## 3. Fitur Aplikasi

Fitur yang direncanakan dalam aplikasi ini meliputi:

1. **Login dan Logout** untuk membatasi akses pengguna.
2. **Dashboard** untuk menampilkan ringkasan informasi persediaan.
3. **Pengelolaan Kategori** untuk menambah, melihat, mengubah, dan menghapus kategori.
4. **Pengelolaan Produk** untuk mengelola informasi barang.
5. **Pengelolaan Supplier** untuk menyimpan data pemasok barang.
6. **Barang Masuk** untuk mencatat penambahan stok.
7. **Barang Keluar** untuk mencatat pengurangan stok.
8. **Riwayat Stok** untuk melihat catatan transaksi persediaan.
9. **Pencarian dan Penyaringan Data** untuk memudahkan pencarian produk.
10. **Laporan Persediaan** untuk membantu memantau kondisi stok.

## 4. Teknologi yang Digunakan

- PHP untuk mengolah data dan menjalankan proses aplikasi.
- MySQL untuk menyimpan data.
- HTML untuk menyusun tampilan halaman.
- CSS untuk mengatur tampilan aplikasi.
- JavaScript untuk membantu interaksi pengguna.
- XAMPP sebagai server lokal selama proses pengembangan.
- Visual Studio Code sebagai editor kode.

## 5. Struktur Folder

```text
inventory/
├── config/
│   └── database.php
├── helpers/
│   ├── auth.php
│   ├── validation.php
│   └── escape.php
├── public/
│   ├── login.php
│   ├── logout.php
│   ├── dashboard.php
│   ├── products/
│   ├── categories/
│   ├── suppliers/
│   ├── stock/
│   └── users/
├── views/
│   ├── header.php
│   ├── footer.php
│   ├── navbar.php
│   └── sidebar.php
├── assets/
│   ├── css/
│   │   └── style.css
│   └── js/
│       └── script.js
├── database/
│   └── schema.sql
└── README.md
```

## 6. Database

Aplikasi menggunakan database bernama `inventory_db` yang terdiri dari enam tabel utama:

- `users`: menyimpan data pengguna dan hak akses.
- `categories`: menyimpan kategori produk.
- `products`: menyimpan data produk dan jumlah stok.
- `suppliers`: menyimpan data pemasok.
- `product_suppliers`: menghubungkan produk dengan supplier.
- `stock_movements`: menyimpan riwayat pergerakan stok barang.

## 7. Penutup

Inventory Management System dibuat untuk membantu proses pengelolaan persediaan barang agar lebih mudah, teratur, dan mengurangi kesalahan pencatatan stok. Pengembangan aplikasi ini juga menjadi sarana untuk menerapkan penggunaan PHP, database relasional, pengelolaan sesi login, dan aturan bisnis dalam sebuah aplikasi web.
