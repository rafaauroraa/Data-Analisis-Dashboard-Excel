# SYUKA-SYUKA | Dashboard Analisis Penjualan Minuman

## Tujuan 
Menyajikan analisis penjualan minuman Syuka-Syuka selama tahun 2024 dalam bentuk dashboard interaktif. Dashboard ini dirancang untuk menunjukkan performa bisnis secara menyeluruh, seperti produk yang paling diminati, periode penjualan tertinggi, serta potensi strategi yang dapat diterapkan untuk meningkatkan omzet.

## Dataset
<a href="https://github.com/rafaauroraa/Data-Analisis-Dashboard-Excel/blob/main/Project%20Excel%20-%20Analisis%20Penjualan%20Minuman%20Syukasyuka%20-%20Rafa%20Aurora%20Affariha.xlsx">DataExcel</a>

Sumber data: Dataset yang disusun untuk keperluan simulasi penjualan minuman.

Periode waktu: Januari – Desember 2024 (12 bulan)

Dataset terdiri dari 5 sheet utama:
- Data Transaksi
- Data Referensi
- Pertanyaan Bisnis
- Pivot Table (Analisis)
- Dashboard Interaktif

## Pertanyaan Bisnis (Key Performance Indicator)
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
- Data transaksi dan data referensi kemudian diintegrasikan menggunakan fitur Data Model di Excel, sehingga analisis antar tabel dapat dilakukan secara efisien tanpa perlu menggabungkan data secara manual misalnya dengan rumus VLOOKUP/HLOOKUP).
- Analisis dilakukan menggunakan PivotTable lanjutan, mencakup perhitungan total, jumlah unik (distinct count), serta pengelompokan berdasarkan kategori, ukuran, dan dimensi waktu (bulan dan hari).
- Hasil analisis divisualisasikan dengan berbagai jenis PivotChart seperti bar chart, column chart, pie chart, dan line chart untuk memberikan sudut pandang yang komprehensif terhadap data.
- Dashboard dikembangkan secara interaktif dengan memanfaatkan Slicer, Timeline, dan rumus GETPIVOTDATA, sehingga data dapat disajikan secara dinamis dan fleksibel, serta mampu menyampaikan insight bisnis secara ringkas dan akurat.

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

## Business Insights (Kritis & Strategis)
Produk Unggulan
- Thai Tea tercatat sebagai minuman terlaris dengan total penjualan sebanyak 3.850 minuman. Hal ini menunjukkan potensi besar untuk pengembangan promosi lebih lanjut. Salah satunya menggabungkan produk Thai Tea dengan produk lain dalam satu paket promosi (promosi bundling) untuk meningkatkan nilai transaksi per pembelian dengan mendorong konsumen membeli lebih dari satu item.
- Kategori Milk Tea Series mendominasi penjualan dengan kontribusi sebesar 38,3%, menunjukkan preferensi konsumen terhadap minuman berbasis teh dan susu. Sehingga pengembangan menu baru yang tetap berbasis teh dan susu dapat menjadi langkah strategis untuk memperluas pilihan konsumen tanpa keluar dari preferensi utama pasar.
- Kategori Tea Series mencatat penjualan terendah (25%), namun memiliki potensi untuk menjangkau segmen pasar yang lebih spesifik, seperti konsumen yang menghindari susu atau mencari pilihan lebih ringan dan menyegarkan. Dengan strategi seperti rebranding—misalnya menonjolkan nilai low calorie dan health-friendly—kategori ini dapat dikembangkan sebagai pelengkap strategis untuk memperluas pilihan dan meningkatkan loyalitas pelanggan. 

Strategi Ukuran dan Kategori
- Distribusi penjualan berdasarkan ukuran tergolong merata (Small 33,1% | Regular 33,8% | Large 33,2%), menunjukkan tidak adanya preferensi ukuran yang dominan. Hal ini membuka peluang untuk strategi upselling. Untuk mendorong pembelian ukuran Large, dapat diterapkan strategi diskon upsizing, yaitu memberikan insentif harga agar konsumen tertarik melakukan upgrade ukuran. Strategi ini memanfaatkan persepsi value for money dan efektif diterapkan pada kategori dengan pendapatan tinggi seperti Creamy Series.

Momentum Penjualan
- Bulan Juli mencatat pendapatan tertinggi sebesar Rp23.165.000. Meskipun penyebab pastinya belum dapat dipastikan, lonjakan ini kemungkinan berkaitan dengan periode libur sekolah atau momen kenaikan kelas. Temuan ini memberi indikasi awal adanya potensi pola musiman, yang dapat dijajaki lebih lanjut melalui strategi promosi temporer, seperti peluncuran varian edisi liburan atau bundling khusus pembelian keluarga selama kuartal tersebut. Namun, untuk mengonfirmasi pola musiman secara lebih akurat, dibutuhkan data historis jangka panjang.
- Hari Selasa mencatat penjualan tertinggi secara tahunan, yaitu 585 pesanan dengan total 4.137 minuman terjual. Temuan ini cukup menarik karena hari kerja di awal pekan umumnya bukan merupakan puncak penjualan dalam industri F&B. Namun, analisis per bulan menunjukkan bahwa hari tersibuk dapat bervariasi, sehingga efektivitas promosi berbasis hari tetap (seperti “Promo Selasa”) sebaiknya diuji coba terlebih dahulu sebelum diterapkan secara rutin.

## Final Conclusion
Analisis penjualan minuman Syuka-Syuka selama tahun 2024 menunjukkan bahwa strategi penjualan dapat difokuskan pada optimalisasi produk unggulan (Thai Tea dan kategori Milk Tea Series), peningkatan nilai transaksi melalui upselling ukuran Large, serta promosi musiman untuk mendorong pertumbuhan transaksi dan memperluas jangkauan pasar secara berkelanjutan.


