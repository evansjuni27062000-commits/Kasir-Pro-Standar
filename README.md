# Kasir Pro Android

Proyek awal aplikasi kasir Android berbasis WebView yang dirancang untuk berjalan offline.

## Fitur versi awal
- Penjualan, keranjang, pembayaran, dan kembalian.
- Produk dengan beberapa satuan dan konversi stok.
- Harga eceran selalu tersedia; harga grosir dan member dapat diaktifkan/nonaktifkan dari Pengaturan.
- Pengelolaan stok dari bagian Produk.
- Riwayat transaksi, laporan sederhana, pelanggan, serta backup/pemulihan JSON.
- Data lokal menggunakan penyimpanan aplikasi (localStorage).

## Build APK melalui GitHub Actions
1. Buat repository GitHub baru.
2. Unggah seluruh isi folder proyek ini (bukan folder ZIP-nya) ke root repository.
3. Buka tab **Actions** dan jalankan workflow **Build Android APK**.
4. Setelah workflow selesai, unduh artifact `Kasir-Pro-debug-apk`.

Catatan: APK perlu diuji di perangkat Android sebelum digunakan untuk transaksi sebenarnya. Selalu buat backup data secara berkala.
