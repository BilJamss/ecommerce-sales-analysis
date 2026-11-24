# E-Commerce Sales Analysis

## Tentang Proyek

Proyek ini bertujuan menganalisis data transaksi E-Commerce Indonesia periode Desember 2023 hingga November 2025 menggunakan Python. Analisis dilakukan untuk memahami tren pembayaran, kategori produk, wilayah transaksi, metode pembayaran, diskon, dan pembatalan pesanan.

## Tujuan Analisis

1. Menganalisis tren penjualan dan total pembayaran berdasarkan periode transaksi.
2. Mengidentifikasi kategori produk dengan jumlah pesanan tertinggi.
3. Mengidentifikasi provinsi dengan nilai transaksi terbesar.
4. Menganalisis pola diskon, metode pembayaran, dan pembatalan pesanan.

## Tools yang Digunakan

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab

## Tahapan Analisis

1. Business Understanding
2. Import Library
3. Import Dataset
4. Data Understanding
5. Data Preprocessing
6. Exploratory Data Analysis (EDA)
7. Analysis Process
8. Insight and Recommendations
9. Exporting Data

## Hasil Analisis

| Indikator | Hasil |
|---|---|
| Pembayaran bulanan tertinggi | Rp71.193.097 (September 2024) |
| Kategori dengan pesanan terbanyak | Celengan (5.869 pesanan) |
| Provinsi dengan pembayaran tertinggi | Jawa Barat (Rp276.992.073) |
| Metode pembayaran terpopuler | COD (11.538 pesanan) |
| Pembatalan oleh pembeli | 1.912 pesanan |

## Insight

- Aktivitas pembayaran tertinggi terjadi pada September 2024.
- Celengan menjadi kategori dengan jumlah pesanan tertinggi.
- Jawa Barat menjadi provinsi dengan nilai pembayaran terbesar.
- COD mendominasi penggunaan metode pembayaran.
- Pembatalan pesanan paling banyak dilakukan oleh pembeli.

## Catatan Data

- Analisis kategori produk menggunakan jumlah pesanan, bukan kontribusi pendapatan per kategori.
- Data Desember 2024 dan Juli 2025 menggunakan kolom waktu pengiriman diatur sebagai alternatif tanggal transaksi karena kolom waktu pesanan dibuat tidak tersedia.
- Total pembayaran merupakan nilai pada tingkat pesanan sehingga perlu diperhatikan dalam proses agregasi.

## Struktur Repository

- `Ecommerce_Sales_Analysis.ipynb` — Notebook analisis dan visualisasi data.
- `README.md` — Dokumentasi proyek.
