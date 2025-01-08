# OrderFlow - E-Commerce Clothing Store
OrderFlow adalah platform e-commerce modern yang khusus menjual pakaian, dilengkapi dengan proses pemesanan yang mudah, fitur wishlist, dan update promosi real-time.

## 🌟 Fitur Utama

### 1. Pemilihan Produk
- Jelajahi berbagai item pakaian
- Lihat informasi detail produk termasuk harga dan deskripsi
- Tambah/hapus item ke wishlist
- Kartu produk interaktif dengan efek hover

### 2. Pengalaman Berbelanja
- Proses checkout bertahap
- Pemilihan ukuran (S, M, L, XL)
- Pengisian informasi pengiriman
- Ringkasan pesanan

### 3. Sistem Pembayaran
- Beberapa metode pembayaran:
  - Transfer Bank
  - E-Wallet
  - Virtual Account
- Update status pembayaran real-time
- Proses transaksi yang aman

### 4. Antarmuka Pengguna
- Desain responsif
- Manajemen wishlist interaktif
- Marquee promosi real-time
- Keranjang belanja dengan efek animasi
- Halaman sukses dengan konfirmasi pesanan

## 🚀 Memulai

### Persyaratan Sistem
- PHP 5.4 atau lebih tinggi
- Database MySQL
- Web Server (Apache/Nginx)
- Composer

### Instalasi

1. Clone repository:
git clone https://github.com/username-anda/orderflow.git
2. Install dependensi:
composer install
3. Konfigurasi database:
- Buat database MySQL baru
- Update `config.php` dengan kredensial database Anda:
$host = "localhost";
$username = "username_anda";
$password = "password_anda";
$database = "database_anda";
4. Siapkan struktur database:
- Import skema SQL yang disediakan
- Pastikan semua tabel terbuat dengan benar

## 💻 Cara Penggunaan

### Alur Pelanggan

1. **Pemilihan Produk**
   - Lihat produk yang tersedia
   - Klik pada item yang diinginkan
   - Tambahkan ke wishlist (opsional)

2. **Pemilihan Ukuran**
   - Pilih ukuran yang sesuai
   - Lanjut ke detail pengiriman

3. **Informasi Pengiriman**
   - Masukkan detail pelanggan:
     - Nama Lengkap
     - Nomor Telepon
     - Alamat Lengkap
   - Validasi format input

4. **Review Pesanan**
   - Cek detail produk
   - Konfirmasi informasi pengiriman
   - Lihat total harga termasuk ongkos kirim

5. **Proses Pembayaran**
   - Pilih metode pembayaran
   - Selesaikan pembayaran
   - Terima konfirmasi pesanan
