# Customer Behaviour Analysis

Proyek analisis data retail dan e-commerce untuk memahami perilaku belanja pelanggan, mengidentifikasi preferensi produk, mengevaluasi pengaruh diskon, serta menganalisis faktor-faktor yang berkaitan dengan nilai transaksi dan kepuasan pelanggan menggunakan Python dan Power BI.

## 1. Gambaran Umum Proyek

Proyek ini berfokus pada analisis perilaku belanja pelanggan berdasarkan dataset simulasi retail dan e-commerce di India.

Bisnis retail membutuhkan pemahaman mengenai pola pembelian pelanggan, kategori produk yang memberikan nilai penjualan tertinggi, respons terhadap diskon, serta faktor yang memengaruhi kepuasan pelanggan. Informasi tersebut dapat membantu bisnis dalam menentukan strategi penjualan, promosi, dan peningkatan layanan.

Melalui proyek ini, dilakukan pengolahan dan eksplorasi data untuk mengidentifikasi pola pembelian, preferensi produk, perilaku pelanggan berulang, serta hubungan antara karakteristik transaksi dan pengalaman berbelanja.

Hasil analisis kemudian disajikan dalam dashboard interaktif menggunakan Power BI untuk mempermudah pemantauan KPI dan penyampaian insight bisnis.

## 2. Tujuan Proyek

- Menganalisis pola dan tren pembelian pelanggan.
- Mengidentifikasi kategori produk dan kanal pembelian dengan nilai transaksi tertinggi.
- Menganalisis perilaku pelanggan satu kali dan pelanggan berulang.
- Mengevaluasi hubungan antara kuantitas pembelian, diskon, dan nilai transaksi.
- Menganalisis kepuasan pelanggan berdasarkan rating dan waktu pengiriman.
- Menyusun rekomendasi strategi bisnis berdasarkan hasil analisis.

## 3. Dataset

Dataset yang digunakan adalah **Customer Shopping Trends Indian** yang diperoleh dari Kaggle.

**Sumber Dataset:** [Customer Shopping Trends Indian – Kaggle](https://www.kaggle.com/datasets/rewantbhriguvanshi/customer-shopping-trends-indian)

Dataset merupakan data simulasi (dummy) yang menggambarkan transaksi retail dan e-commerce di India selama periode Januari 2023 hingga Desember 2024.

Dataset terdiri dari **10.000 baris dan 26 kolom**, dengan informasi yang mencakup:

- **Informasi Pelanggan:** Usia, jenis kelamin, lokasi, status berlangganan, dan frekuensi pembelian.
- **Informasi Transaksi:** ID transaksi, ID pelanggan, tanggal pembelian, kanal pembelian, jumlah barang, dan nilai pembelian.
- **Informasi Produk:** Kategori produk, nama barang, merek, warna, dan ukuran.
- **Promosi dan Pembayaran:** Persentase diskon, acara promosi, biaya pengiriman, dan metode pembayaran.
- **Pengalaman Pelanggan:** Waktu pengiriman, rating pelanggan, dan status pengembalian barang.

## 4. Tools dan Teknologi

| Tools | Penggunaan |
|---|---|
| Python | Pengolahan dan analisis data |
| Pandas | Manipulasi dan pembersihan data |
| NumPy | Pengolahan data numerik |
| Matplotlib | Visualisasi data |
| Seaborn | Visualisasi dan eksplorasi data |
| Power BI | Pembuatan dashboard interaktif |

## 5. Tahapan Analisis

### 5.1 Data Loading dan Data Cleaning

Memuat dataset ke dalam Python, memeriksa struktur dan tipe data, serta memastikan kualitas data sebelum dilakukan analisis lebih lanjut.

### 5.2 Exploratory Data Analysis (EDA)

Melakukan eksplorasi untuk memahami karakteristik transaksi dan perilaku pelanggan melalui:

- Analisis distribusi demografi pelanggan.
- Analisis tren dan nilai pembelian.
- Analisis performa kategori dan produk.
- Analisis kanal pembelian online dan offline.
- Analisis metode pembayaran dan distribusi diskon.

### 5.3 Customer Behaviour Analysis

Menganalisis perilaku pembelian pelanggan melalui beberapa aspek:

- Perbandingan pelanggan satu kali dan pelanggan berulang.
- Analisis nilai pembelian berdasarkan kelompok usia.
- Analisis hubungan kuantitas pembelian dan nilai transaksi.
- Analisis preferensi kategori produk.
- Analisis respons pelanggan terhadap diskon.

### 5.4 Customer Satisfaction Analysis

Mengevaluasi pengalaman pelanggan berdasarkan rating yang diberikan, termasuk:

- Perbandingan rating kanal online dan offline.
- Distribusi rating pelanggan.
- Analisis hubungan waktu pengiriman dengan kepuasan pelanggan.

### 5.5 Dashboard Development

Membangun dashboard interaktif menggunakan Power BI untuk menyajikan KPI utama, distribusi transaksi, performa produk, perilaku pelanggan, serta indikator kepuasan pelanggan.

## 6. Hasil Analisis

Hasil analisis menunjukkan beberapa pola utama dari 10.000 transaksi dan 3.291 pelanggan.

### Key Performance Indicators (KPI)

| Indikator | Hasil |
|---|---:|
| Total Purchase Amount | ₹65 juta |
| Total Transaksi | 10.000 |
| Total Pelanggan | 3.291 |
| Rata-rata Rating | 3,48 |

### Insight Utama

1. **Dominasi Kanal Online:** Sekitar 74% nilai pembelian berasal dari kanal online, yaitu sekitar ₹48 juta, sedangkan kanal offline menyumbang sekitar ₹17 juta.

2. **Pelanggan Berulang:** Sekitar 82% pelanggan merupakan pelanggan berulang. Hal ini menunjukkan bahwa sebagian besar pelanggan telah melakukan lebih dari satu kali pembelian.

3. **Performa Kategori Produk:** Footwear menjadi kategori dengan nilai pembelian tertinggi, yaitu sekitar ₹37 juta, meskipun jumlah item terjual pada kategori Clothing lebih banyak. Hal ini menunjukkan adanya perbedaan nilai pembelian per item antar kategori.

4. **Kuantitas dan Nilai Transaksi:** Sekitar 69% transaksi hanya berisi satu item. Rata-rata nilai pembelian meningkat seiring bertambahnya kuantitas, dari sekitar ₹4,5 ribu untuk satu item menjadi ₹16,3 ribu untuk empat item.

5. **Pola Penggunaan Diskon:** Sekitar 67% transaksi menggunakan diskon sebesar 0–10%. Nilai pembelian rata-rata terlihat lebih tinggi pada kelompok diskon besar, tetapi jumlah transaksinya relatif sedikit.

6. **Distribusi Nilai Pelanggan:** Sepuluh pelanggan dengan nilai pembelian tertinggi hanya menyumbang sekitar 2% dari total pembelian. Hal ini menunjukkan bahwa nilai transaksi tidak hanya bergantung pada segelintir pelanggan.

7. **Kepuasan Pelanggan:** Rata-rata rating kanal online sebesar 3,42, lebih rendah dibandingkan kanal offline sebesar 3,66. Sebagian besar rating berada pada angka 3 dan 4.

8. **Pengaruh Waktu Pengiriman:** Rating pelanggan relatif stabil pada kisaran 3,6–3,7 untuk pengiriman yang lebih cepat, kemudian menurun hingga sekitar 2,7 ketika waktu pengiriman mencapai sekitar enam hari atau lebih.

## 7. Rekomendasi Bisnis

Berdasarkan hasil analisis, berikut beberapa rekomendasi yang dapat dipertimbangkan:

| Area | Rekomendasi Strategi |
|---|---|
| Pengiriman Online | Mempercepat proses pengiriman dan meningkatkan kualitas layanan logistik untuk memperbaiki kepuasan pelanggan. |
| Retensi Pelanggan | Menerapkan program loyalitas dan reminder pembelian untuk mendorong pelanggan satu kali melakukan pembelian kembali. |
| Nilai Transaksi | Menggunakan strategi bundling dan cross-selling untuk meningkatkan jumlah item dalam setiap transaksi. |
| Kategori Produk | Memprioritaskan promosi pada kategori Footwear yang memiliki nilai pembelian tinggi serta mengembangkan kontribusi kategori Accessories. |
| Strategi Diskon | Melakukan evaluasi dan pengujian lebih lanjut terhadap efektivitas diskon, terutama pada kelompok diskon tinggi yang memiliki jumlah transaksi terbatas. |

## 8. Dashboard Power BI

Hasil analisis disajikan dalam dashboard interaktif menggunakan Power BI yang menampilkan:

- KPI total purchase amount, jumlah transaksi, jumlah pelanggan, dan rata-rata rating.
- Perbandingan nilai pembelian kanal online dan offline.
- Performa kategori dan produk.
- Distribusi kuantitas pembelian dan nilai transaksi.
- Analisis diskon dan kelompok usia pelanggan.
- Perbandingan rating berdasarkan kanal pembelian dan waktu pengiriman.

### Dashboard Preview

<!-- Tambahkan screenshot dashboard di sini -->

<!-- Contoh: ![Customer Behaviour Dashboard](images/dashboard-overview.png) -->

**File Dashboard:** `Customer Shopping Behaviour Dashboard.pbix`

## 9. Struktur Repository

| File | Deskripsi |
|---|---|
| `Customer_Behaviour.ipynb` | Notebook Python berisi proses data loading, data cleaning, eksplorasi, dan analisis perilaku pelanggan. |
| `customer_shopping_behavior-clean.csv` | Dataset yang telah dibersihkan dan digunakan dalam analisis. |
| `Customer Shopping Behaviour Dashboard.pbix` | File dashboard interaktif Power BI. |
| `requirements.txt` | Daftar library Python yang dibutuhkan untuk menjalankan proyek. |

## 10. Cara Menjalankan Proyek

1. Clone repository:

   ```bash
   git clone https://github.com/yosephinecahayap/DP-customer-behaviour.git
   ```

2. Masuk ke direktori proyek.

3. Install library Python yang dibutuhkan:

   ```bash
   pip install -r requirements.txt
   ```

4. Buka file `Customer_Behaviour.ipynb` menggunakan Jupyter Notebook atau Google Colab.

5. Pastikan file `customer_shopping_behavior-clean.csv` berada di direktori yang sesuai dengan lokasi notebook.

6. Jalankan setiap cell secara berurutan untuk melihat proses pengolahan dan analisis data.

7. Buka file `Customer Shopping Behaviour Dashboard.pbix` menggunakan Power BI Desktop untuk melihat dashboard interaktif.

## 11. Informasi Proyek

- **Nama Proyek:** Customer Behaviour Analysis
- **Jenis Proyek:** Data Analysis Project
- **Domain:** Retail & E-Commerce
- **Dataset:** Customer Shopping Trends Indian
- **Fokus:** Customer Behaviour, Sales Analysis, dan Customer Satisfaction
- **Metode:** Data Cleaning, Exploratory Data Analysis (EDA), dan Business Insight Analysis
- **Tools:** Python dan Power BI
