# SYUKA-SYUKA | Dashboard Analisis Penjualan Minuman

## Tujuan 
Proyek ini bertujuan untuk menganalisis data penjualan minuman dari UMKM fiktif Syuka-Syuka guna memperoleh insight bisnis yang dapat digunakan untuk pengambilan keputusan strategis.
Analisis difokuskan pada identifikasi produk unggulan, tren penjualan, serta peluang peningkatan omzet berdasarkan data transaksi tahun 2024.

## Dataset
<a href="https://github.com/rafaauroraa/Data-Analisis-Dashboard-Excel/blob/main/Project%20Excel%20-%20Analisis%20Penjualan%20Minuman%20Syukasyuka%20-%20Rafa%20Aurora%20Affariha.xlsx">Data Excel</a>

Dataset berisi data transaksi penjualan selama tahun 2024 dengan variabel utama:
Tanggal penjualan
Nama produk & kategori
Ukuran minuman (Small, Regular, Large)
Jumlah terjual (cup)
Harga per cup
Total pendapatan

Data disimulasikan berdasarkan skenario penjualan UMKM minuman dan digunakan untuk latihan analisis bisnis.

## Pertanyaan Bisnis 
- Berapa total pendapatan penjualan selama periode berjalan?
- Berapa total pesanan (order) yang diterima?
- Berapa total minuman yang terjual?
- Apa saja 3 (tiga) produk minuman yang paling laris?
- Bagaimana distribusi jumlah penjualan berdasarkan kategori minuman?
- Bagaimana distribusi penjualan berdasarkan ukuran minuman?
- Bagaimana pendapatan jika dilihat dari kategori dan ukuran?
- Bagaimana tren pendapatan dari waktu ke waktu?
- Hari apa yang menjadi hari tersibuk dalam satu minggu?

## Proses Analisis
- Proses dimulai dengan melakukan persiapan dan pembersihan data, termasuk menghapus data duplikat, memperbaiki format data, serta menghitung total harga. Selain itu, kolom tambahan berupa nama hari juga dibuat untuk mendukung analisis waktu.
- Data transaksi dan data referensi kemudian diintegrasikan menggunakan fitur Data Model di Excel, sehingga analisis antar tabel dapat dilakukan secara efisien tanpa perlu menggabungkan data secara manual misalnya dengan rumus VLOOKUP/HLOOKUP.
- Analisis dilakukan menggunakan PivotTable lanjutan, mencakup perhitungan total, jumlah unik (distinct count), serta pengelompokan berdasarkan kategori, ukuran, dan dimensi waktu (bulan dan hari).
- Hasil analisis ditampilkan dalam berbagai jenis PivotChart, seperti bar chart, column chart, pie chart, dan line chart, untuk memberikan gambaran data yang lebih menyeluruh.
- <a href="https://github.com/rafaauroraa/Data-Analisis-Dashboard-Excel/blob/main/Project%20Excel%20-%20Analisis%20Penjualan%20Minuman%20Syukasyuka%20-%20Rafa%20Aurora%20Affariha.xlsx">Dashboard</a> dikembangkan secara interaktif dengan bantuan Slicer, Timeline, dan rumus GETPIVOTDATA, sehingga penyajian data menjadi dinamis dan fleksibel. 

## Dashboard
![Dashboard Analisis Penjualan Minuman Syuka-Syuka - Rafa Aurora A](https://github.com/user-attachments/assets/5419bc74-46c5-456c-8360-c71eba5665ae)

## Ringkasan Dashboard
- Total Pendapatan: Rp 249.108.000
- Total Pesanan: 1.433 pesanan
- Total Minuman Terjual: 27.730 minuman
- Minuman Terlaris: Thai Tea (3.850 minuman)
- Kategori Terpopuler: Milk Tea Series (38,3% penjualan)
- Ukuran Terlaris: Regular (33,8% penjualan)
- Pendapatan Tertinggi: Kategori Creamy Series dengan Ukuran Large (Rp.45.710.000,00)
- Bulan dengan Pendapatan Tertinggi: Bulan Juli (Rp.23.165.000,00)
- Hari Tersibuk: Selasa (585 pesanan dengan 4.137 minuman terjual)

## Insight Bisnis
Produk Unggulan
- Thai Tea tercatat sebagai minuman terlaris dengan total penjualan sebanyak 3.850 minuman. Hal ini menunjukkan potensi besar untuk pengembangan promosi lebih lanjut. Salah satunya menggabungkan produk Thai Tea dengan produk lain dalam satu paket promosi (promosi bundling) untuk meningkatkan nilai transaksi per pembelian dengan mendorong konsumen membeli lebih dari satu item.
- Kategori Milk Tea Series mendominasi penjualan dengan kontribusi sebesar 38,3%, menunjukkan preferensi konsumen terhadap minuman berbasis teh dan susu. Sehingga pengembangan menu baru berbasis teh dan susu dapat menjadi langkah strategis untuk memperluas pilihan konsumen.
- Kategori Tea Series mencatat penjualan terendah (25%), namun memiliki potensi untuk menjangkau segmen pasar yang lebih spesifik, seperti konsumen yang menghindari susu atau mencari minuman lebih ringan dan menyegarkan. Strategi seperti rebranding, misalnya dengan menonjolkan nilai low calorie dan health friendly, bisa dikembangkan sebagai strategi untuk memperluas pilihan dan meningkatkan loyalitas pelanggan.

Strategi Ukuran dan Kategori
- Distribusi penjualan berdasarkan ukuran tergolong merata (Small 33,1% | Regular 33,8% | Large 33,2%), menunjukkan tidak adanya preferensi ukuran yang dominan. Hal ini bisa dimanfaatkan untuk menerapkan strategi upselling. Salah satu caranya adalah dengan menawarkan diskon untuk upsizing, agar konsumen lebih tertarik memilih ukuran Large. Strategi ini mengandalkan persepsi value for money dan paling efektif diterapkan pada kategori dengan pendapatan tinggi, seperti Creamy Series.

Momentum Penjualan
- Bulan Juli mencatat pendapatan tertinggi sebesar Rp23.165.000. Meskipun penyebab pastinya belum dapat dipastikan, kenaikan ini kemungkinan dipengaruhi oleh libur sekolah. Hal ini memberi indikasi awal adanya potensi pola musiman yang dapat dimanfaatkan menggunakan strategi promosi temporer, seperti peluncuran varian edisi liburan atau bundling khusus pembelian keluarga selama periode tersebut. 
- Hari Selasa mencatat penjualan tertinggi sepanjang tahun, yaitu 585 pesanan dengan total 4.137 minuman terjual. Temuan ini cukup menarik, karena hari kerja di awal pekan biasanya bukan puncak penjualan dalam industri F&B. Namun, analisis per bulan menunjukkan bahwa hari tersibuk bervariasi, sehingga strategi promosi berbasis hari tetap (seperti “Promo Selasa”) sebaiknya diuji coba terlebih dahulu sebelum dijadikan strategi rutin.

## Kesimpulan
Analisis penjualan minuman Syuka-Syuka selama tahun 2024 menunjukkan bahwa strategi penjualan dapat difokuskan pada dua hal utama, yaitu mengoptimalkan performa produk unggulan seperti Thai Tea dan Milk Tea Series untuk menjaga kontribusi penjualan utama dan meningkatkan nilai transaksi melalui strategi upselling ke ukuran Large, dengan pendekatan seperti diskon upsizing atau bundling harga.
