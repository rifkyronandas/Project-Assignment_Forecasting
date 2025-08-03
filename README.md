# Project-Assignment_Forecasting
Proyek ini merupakan analisis mendalam terhadap data penjualan selama tahun 2019. Analisis ini bertujuan untuk mengekstrak wawasan bisnis yang berharga, seperti tren penjualan, produk terlaris, hingga waktu puncak pemesanan. Notebook ini mencakup langkah-langkah mulai dari pemrosesan data, pembersihan, hingga analisis eksplorasi


Dataset
Dataset yang digunakan terdiri dari 12 file CSV terpisah, masing-masing berisi data penjualan bulanan dari Januari hingga Desember 2019. Setiap file memiliki kolom berikut:

Order ID: ID unik untuk setiap pesanan.

Product: Nama produk yang dipesan.

Quantity Ordered: Jumlah produk yang dipesan.

Price Each: Harga per unit produk.

Order Date: Tanggal dan waktu pesanan.

Purchase Address: Alamat pengiriman.

Dalam tahap pemrosesan awal, semua file ini digabungkan menjadi satu dataset tunggal untuk analisis yang komprehensif.

Pustaka yang Digunakan
*pandas: Untuk manipulasi dan analisis data.
*numpy: Untuk operasi numerik.
*matplotlib & seaborn: Untuk visualisasi data.
*itertools & collections: Untuk analisis kombinasi produk.
*statsmodels: Untuk analisis statistik dan deret waktu.

Analisis yang Dilakukan
Notebook ini mencakup beberapa analisis kunci:

Pembersihan Data: Mengatasi nilai yang hilang, duplikat, dan kesalahan tipe data.

Rekayasa Fitur: Membuat fitur baru seperti total pendapatan per pesanan dan jam pemesanan.

Analisis Tren Penjualan: Menganalisis tren penjualan harian, mingguan, dan bulanan untuk memahami pola musiman.

Analisis Produk Terlaris: Mengidentifikasi 10 produk teratas berdasarkan pendapatan dalam 3 bulan terakhir.

Analisis Bundling Produk: Menemukan 10 pasangan produk yang paling sering dibeli bersamaan untuk potensi strategi bundling.

Analisis Jam Sibuk (Rush Hour): Menentukan jam-jam puncak pemesanan berdasarkan jumlah pesanan dan total pendapatan.

Hasil dan Wawasan
Metrik Pemasaran Utama:

Total Pendapatan: $34,456,867.65

Jumlah Pesanan: 178,406

Jumlah Barang Terjual: 208,771

Rata-rata Barang per Transaksi: 1.17

Rata-rata Pengeluaran per Transaksi: $193.14

Produk Terlaris (3 Bulan Terakhir):
Macbook Pro Laptop, iPhone, dan ThinkPad Laptop menjadi produk dengan pendapatan tertinggi.

Peluang Bundling:
Kombinasi seperti "Google Phone & USB-C Charging Cable" dan "iPhone & Lightning Charging Cable" sangat sering dibeli bersama.

Jam Sibuk:
Puncak pesanan terjadi pada sore hari, menunjukkan waktu yang optimal untuk aktivitas pemasaran.

Kontributor
Muhammad Rifky Ronanda Suryatama - Analisis dan Pengembangan
