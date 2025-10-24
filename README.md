# SIM Penjualan

Aplikasi **Sistem Informasi Manajemen (SIM) Penjualan** untuk mengelola data barang, transaksi, pelanggan, dan laporan penjualan harian/bulanan. Proyek ini ditujukan sebagai dasar aplikasi kasir/penjualan skala kecil–menengah.

> Kode utama berada di folder `sim-penjualan/`.

---

## ✨ Fitur Utama

- **Master Data Barang** – tambah, ubah, hapus, dan pencarian.
- **Transaksi Penjualan** – keranjang (cart), simpan transaksi, cetak/unduh nota.
- **Pelanggan (opsional)** – CRUD data pelanggan.
- **Laporan** – rekap harian/mingguan/bulanan, ekspor CSV/PDF *(jika diimplementasikan)*.
- **Hak Akses Dasar** – login admin/kasir *(opsional)*.

> Beberapa fitur bersifat placeholder — sesuaikan dengan implementasi aktual di folder `sim-penjualan`.

---

## 🧰 Tech Stack

- **Backend:** PHP (native / framework ringan jika ada)
- **Database:** MySQL / MariaDB
- **Web Server:** Apache atau Nginx
- **Frontend:** HTML, CSS, JavaScript (vanilla/jQuery)

---

## ✅ Prasyarat

- **PHP** 8.x (min. 7.4) dengan ekstensi `mysqli` atau `pdo_mysql`
- **MySQL/MariaDB**
- **Composer** *(jika proyek memakai dependensi)*
- **Apache/Nginx** atau **PHP built-in server** untuk development
- Alternatif cepat: **XAMPP/MAMP/Laragon**

---

## 🚀 Cara Menjalankan (Lokal)

1) **Clone repo**
```bash
git clone https://github.com/Mizyal13/sim.git
cd sim/sim-penjualan

