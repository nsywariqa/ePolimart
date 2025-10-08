# 🛍️ ePoliMart

**Sistem E-Marketplace Internal untuk Politeknik Negeri Lhokseumawe**

---

### 👥 Tim

* **Nasywa Ariqa Ridha** (Ketua)
* **Adha Gusti Harmadhan** (Anggota)
* **A'llieya Maysarah** (Anggota)
* **Putri Balqis** (Anggota)

---

## 1. 📖 Latar Belakang

Politeknik Negeri Lhokseumawe (PNL) merupakan salah satu perguruan tinggi vokasi negeri di Aceh yang berfokus pada pendidikan terapan di berbagai bidang seperti teknik, bisnis, dan teknologi.
Dengan ribuan mahasiswa aktif serta munculnya berbagai UMKM mahasiswa yang bergerak dalam wirausaha, kebutuhan akan **wadah digital jual-beli internal kampus** semakin meningkat.

Selama ini, transaksi di lingkungan kampus masih dilakukan secara manual atau melalui media sosial, yang menimbulkan beberapa kendala:

* 🔸 **Promosi terbatas:** produk mahasiswa sulit dikenal oleh seluruh civitas kampus.
* 🔸 **Transaksi tidak efisien:** konfirmasi pesanan dan pembayaran dilakukan manual.
* 🔸 **Kesulitan pengelolaan stok dan laporan penjualan.**

💡 **ePoliMart** hadir sebagai platform e-commerce internal kampus yang memfasilitasi jual-beli digital antar mahasiswa Politeknik Negeri Lhokseumawe.
Sistem ini menyediakan fitur pembelian langsung, pembayaran daring, dan laporan penjualan otomatis untuk menciptakan ekosistem ekonomi digital yang **aman, efisien, dan terintegrasi** di lingkungan kampus.

---

## 2. 📦 Ruang Lingkup Sistem

### 🧑‍💼 Admin Kampus (Pengelola Utama)

* Mengelola data penjual, produk, transaksi, dan laporan.
* Memverifikasi pendaftaran penjual baru.
* Mengawasi aktivitas marketplace dan menjaga keamanan sistem.

### 🛒 Penjual (Mahasiswa / UMKM Kampus)

* Mengelola toko online (produk, stok, pesanan, laporan).
* Menerima notifikasi pesanan baru.
* Mengatur status pesanan (diproses, siap diambil, selesai).

### 👨‍🎓 Pembeli (Mahasiswa PNL)

* Melihat katalog produk, menambah produk ke keranjang, checkout, dan pembayaran.
* Melihat status pesanan dan riwayat pembelian.

📌 **Catatan:**

* Setiap penjual memiliki toko dan stok tersendiri.
* Transaksi dilakukan antar mahasiswa di area kampus.
* Metode pembayaran: transfer bank, **QRIS**, atau **COD** sesuai pengaturan admin.

---

## 3. ⚙️ Fitur Utama

### 3.1 Manajemen Produk

* CRUD produk (tambah, edit, hapus).
* Data produk: nama, kategori, harga, stok, deskripsi, gambar, status aktif.
* Admin dapat memverifikasi atau menonaktifkan produk yang tidak sesuai.

### 3.2 Manajemen Stok

* Stok diperbarui otomatis saat transaksi terjadi.
* Riwayat perubahan stok tersimpan dalam sistem.
* Notifikasi stok rendah untuk penjual.

### 3.3 Sistem Pembelian & Pembayaran

* Pembeli dapat checkout dengan beberapa metode pembayaran:

  * Upload bukti transfer (manual)
  * Pembayaran digital via **QRIS**
  * Pembayaran tunai (**COD**)
* Penjual mengonfirmasi pesanan dan memperbarui status.
* Admin memantau semua transaksi aktif.

### 3.4 Laporan & Analitik

* Laporan penjualan per penjual dan total keseluruhan kampus.
* Filter laporan berdasarkan waktu (harian, mingguan, bulanan).
* Statistik produk terlaris & penjual aktif.
* Visualisasi data dengan **Chart.js**.

### 3.5 Multiuser Role

| Role        | Akses                                         |
| ----------- | --------------------------------------------- |
| **Admin**   | Penuh terhadap semua data                     |
| **Penjual** | Kelola toko sendiri                           |
| **Pembeli** | Melihat katalog, berbelanja, memantau pesanan |

### 3.6 Pencarian & Filter Produk

* Pencarian produk berdasarkan nama atau kategori.
* Filter harga, stok, dan toko penjual.

### 3.7 Notifikasi & Konfirmasi

* **Penjual:** pesanan baru, stok menipis, pembayaran diterima.
* **Pembeli:** status pesanan (diproses, dikirim, selesai).
* **Admin:** pendaftaran penjual baru, transaksi mencurigakan.

---

## 4. 🧩 Arsitektur Teknis

### 🔙 Backend Stack

* **Laravel 12** (PHP Framework)
* **MySQL** (Database)

### 🎨 Frontend Stack

* **Blade Templating Engine**
* **Tailwind CSS**

### 📦 Package Tambahan

* [Spatie Laravel Permission](https://spatie.be/docs/laravel-permission) – Manajemen Role & Permission
* [Laravel Excel](https://laravel-excel.com/) – Ekspor laporan transaksi dan stok
* [Chart.js](https://www.chartjs.org/) – Visualisasi data laporan
* **Midtrans / Xendit / Manual Payment Module** – Modul pembayaran digital

---

## 5. 🎯 Manfaat

### Untuk Kampus / Admin

* Mengontrol aktivitas ekonomi mahasiswa secara digital dan transparan.
* Mendukung program kewirausahaan mahasiswa.
* Menjadi wadah resmi & terintegrasi bagi kegiatan UMKM mahasiswa.

### Untuk Penjual (Mahasiswa / UMKM)

* Mengelola toko & stok dengan mudah.
* Mendapat laporan penjualan otomatis.
* Meningkatkan jangkauan promosi di dalam kampus.

### Untuk Pembeli (Mahasiswa)

* Belanja praktis tanpa keluar kampus.
* Transaksi cepat dengan berbagai metode pembayaran.
* Memantau status pesanan secara real-time.

---

## 6. 🧾 Ringkasan

**ePoliMart** adalah sistem e-commerce internal kampus yang dirancang khusus untuk mahasiswa **Politeknik Negeri Lhokseumawe (PNL)**.
Sistem ini menjadi sarana digital bagi mahasiswa untuk berwirausaha di lingkungan kampus dengan fitur pengelolaan toko, transaksi, pembayaran, dan laporan yang **terintegrasi**.

Dengan adanya ePoliMart, PNL dapat membangun budaya **ekonomi kreatif berbasis digital** yang **efisien, aman, dan mendukung pengembangan kewirausahaan mahasiswa** di era modern.

---

