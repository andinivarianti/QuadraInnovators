# Group 4 - QuadraInnovators
Final Project Data Science Bootcamp 

## Descriptive Statistics
Dataset terdiri dari 19,158 baris dan 13 kolom dengan tipe data numerical dan categorical, semuanya sesuai dengan isi data.
Terdapat missing values pada 8 kolom, namun tidak ada duplicate values.
Kolom training_hours memiliki outlier signifikan, dengan perbedaan besar antara median (rendah) dan nilai maksimum (336).

## Univariate Analysis
Lebih banyak kandidat yang tidak mencari perubahan pekerjaan (0.0) dibandingkan yang mencari (1.0).
Mayoritas berasal dari jurusan STEM dan berpendidikan graduate. 
Gender didominasi oleh pria, dengan pengalaman kerja relevan lebih banyak.
Kandidat yang tidak terdaftar di kursus universitas mendominasi.
Experience paling banyak >20 tahun, dan mayoritas memiliki waktu 1 tahun sejak pekerjaan terakhir.
Ukuran perusahaan paling banyak di rentang 50-99 karyawan.
Tipe perusahaan didominasi oleh Pvt Ltd.
Outliers: Terlihat pada kolom training_hours (nilai sangat tinggi) dan city_development_index (nilai sangat rendah).

## Multivariate Analysis
Korelasi antar kolom numerik:
City_development_index: Memiliki korelasi negatif yang moderat dengan target (-0.34), yang menunjukkan bahwa semakin tinggi City Development Index, semakin rendah kemungkinan kandidat mencari pekerjaan baru.
Training_hours: Memiliki korelasi positif yang sangat lemah dengan target (0.05), yang menunjukkan hubungan yang sangat kecil antara training hours dengan niat kandidat untuk mencari pekerjaan baru.
Target: Korelasi negatif dengan city_development_index (-0.34) dan korelasi positif lemah dengan training_hours (0.05).

Perbandingan education level dengan kolom Lain:
Kandidat dengan education level Graduate cenderung memiliki nilai tertinggi di setiap perbandingan dengan kolom lain, menunjukkan bahwa kandidat dengan pendidikan lanjutan lebih dominan dalam kategori-kategori tersebut.

Boxplot Training Hours:
Tidak ada perbedaan yang signifikan antara candidates looking for job change dan not looking for job change dalam training hours. Namun, keduanya memiliki outliers yang menunjukkan adanya variasi besar dalam jumlah training hours yang dimiliki oleh kandidat.

Matriks Korelasi setelah data cleaning:
Data cleaning telah dilakukan, dan matriks korelasi digunakan untuk mengidentifikasi hubungan antar fitur dalam dataset, memberikan wawasan tentang pola dan keterkaitan antar variabel.
