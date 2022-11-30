# Hello_Sigma
Final Project Rakamin Academy Data Science Bootcamp Batch 25

# Problem Statement
Berdasarkan data yang dikutip melalui Laporan US Department Transportation dan National Transportation Safety Board.
Diketahui bahwa kendaraan bermobil merupakan moda transportasi yang paling tidak aman..... Pada tahun 2020 saja tercatat sebanyak 5.250.837 kecelakaan terjadi di US dan merenggut korban jiwa hingga 35.766 orang.

Jika berdasarkan data tersebut terdapat besar peluang yang diharapkan dari dilakukannya penjualan Asuransi kendaraan.

Namun berdasarkan dataset yang dimiliki oleh Perusahaan asuransi Hello Sigma
Hanya terdapat 12,3% yang tertarik terhadap asuransi kendaraan dari keseluruhan kustomer yang dimilikinya sebanyak 381.109 data. Hal tersebut membuat perusahaan ingin meningkatkan user interested rate Asuransi Kendaraan. Sehingga terdapat beberapa hal yang perlu dilakukan guna mencapai goals dari business problem tersebut, antara lain:

Goals: Meningkatkan User Interested Rate sebesar 10%
Objective: 
- Memprediksi nasabah yang potensial untuk asuransi kendaraan
- Menemukan faktor penting dan karakteristik utama dari user yang tertarik dengan asuransi kendaraan
- Menemukan metode yang membuat customer tertarik
- Meningkatkan jumlah orang yang tertarik dengan asuransi kendaraan
- Mengimplementasikan pada sebuah simulasi bisnis untuk melihat pengaruh positif model terhadap perusahaan
Business Metrics: User Interested Rate

# EDA
1. Descriptive statistics 
2. Univariate Analysis
3. Multivariate Analysis

Setelah dilakukan pemrosesan pada data hingga mencari model yang relevan, didapatkan kesimpulan sebagai berikut :

# Business Insigth
- Pada nasabah yang tertarik menggunakan Asuransi Kendaraan, kondisi kendaraan sebelumnya lebih banyak yang telah mengalami kerusakan dibandingkan yang belum. 

- Nasabah yang tertarik menggunakan Asuransi Kendaraan baik Male maupun Female tidak terdapat perbedaan yang signifikan.

- Pada kelompok usia kendaraan 1-2 tahun lebih banyak yang tertarik menggunakan asuransi Kendaraan dibandingkan kelompok lain seperti kelompok usia kendaraan <1 tahun dan usia kendaran >2 tahun

- Nasabah yang tertarik menggunakan Asuransi kendaraan, sebelumnya banyak yang belum menggunakan Asuransi Kendaraan.

- Ada 10 kode jenis Policy_Sales_Channel yang paling banyak dalam memberikan kontribusi ketertarikan nasabah menggunakan Asuransi Kendaraan.

- Usia Nasabah dari 33 – 52 merupakan kelompok umur yang paling banyak tertarik menggunakan Asuransi Kendaraan.

- Ada beberapa Region_Code dengan code 28.0, 41.0, 8.0, 46.0, 29.0, dimana wilayah tersebut nasabah yang tertarik menggunakan Asuransi Kendaraan lebih banyak dibandingkan Region lain.

# Data Preprocessing
1. Data Cleansing: 
- Handle missing values
- Handle duplicate data
- Handle Outliers
- Feature Transformation
- Feature Encoding
- Handle Class Imbalance

2. Feature Engineering
- Feature Selection
- Feature Extraction
- Feature Extention

# Modelling
- Split Data Train & Test
- Modelling : Model yang digunakan pada case ini adalah Regresi Logistic dan menggunakan Metric Recall
- Model Evaluation
- Hyperparameter Tuning
- Tuning Threshold
- Gain and Lift

# Business Recomendation
1. Perusahaan dapat memfokuskan pada nasabah yang sebelumnya memiliki Asuransi Kendaraan dan kondisi kendaraanya rusak
2. Memberikan diskon pada beberapa kategori seperti: 
- Drive safe: Semakin sering berkendara semakin mendapat diskon
- Teen Driver: Diskon hingga 25% untuk pengguna sebelum usia 25 tahun
- Steer Clear: Usia dibawah 25 tahun dan tidak terdapat catatan kecelakaan mendapatkan diskon hingag 15%
3. Berpartisipasi dalam kegiatan sosial masyarakat dan memberikan edukasi bahwa tujuan asuransi adalah membantu memberikan rasa aman dan nyaman kepada masyarakat terkait resiko yang akan terjadi kedepannya mengenai penggunaan kendaraan. Kemudian membuat Campaign kegitan sosial untuk membantu perusahaan membangun citra positif yannnng lebih kuat dihadapan masyarakat.
4. Bekerja sama dengan dealer maupun bengkel untuk menawarkan asuransi kepada konsumen mereka yang membeli mobil dengan cash terutama pada usia kendaraan 1-2 tahun.
