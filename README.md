# Predict Customer Personality to Boost Marketing Campaign by Using Machine Learning
Project ini merupakan project yang bertujuan untuk melakukan pediksi perilaku pelanggan guna meningkatkan campaign marketing di suatu perusahaan. Project ini dibuat menggunakan bahasa pemrograman Python

## Daftar Isi
- Analisis Tingkat Konversi Berdasarkan Pendapatan, Pengeluaran dan Usia
- Data Cleaning, Preprocessing, dan Feature Engineering
- Data Modelling
- Analisis Kepribadian Pelanggan Untuk Retargeting Pemasaran

## Bagian 0: Pendahuluan
Sebuah perusahaan dapat berkembang dengan pesat saat mengetahui customer personality nya, sehingga dapat memberikan layanan serta manfaat lebih baik kepada pelanggan yang berpotensi menjadi pelanggan yang loyal. Dengan mengolah data historis marketing campaign, dapat menaikkan performa dan menyasar pelanggan yang tepat agar dapat bertransaksi di platform perusahaan. Dari insight data tersebut, difokuskan membuat sebuah model prediksi kluster sehingga memudahkan perusahaan dalam membuat keputusan.

## Bagian 1: Analisis Tingkat Konversi Berdasarkan Pendapatan, Pengeluaran dan Usia
<p align="center">
  <img src="https://github.com/user-attachments/assets/0e57dd7d-d007-4cd5-bb4b-92210f600731"/>
</p>
Gambar diatas merupakan plot korelasi conversion rate dengan pendapatan, total pengeluaran, serta usia. Hasil penelitian menunjukkan korelasi positif yang signifikan antara pendapatan dan total pengeluaran terhadap tingkat konversi. Ini menunjukkan bahwa semakin besar pendapatan dan pengeluaran total seseorang, semakin besar kemungkinan mereka akan melakukan pembelian.
<p align="center">
  <img src="https://github.com/user-attachments/assets/704d380f-b3a5-4795-9ced-f311ed78cd15"/>
</p>
Dapat dilihat pada plot regresi dengan pendapatan dan total pengeluaran berikut, bahwa adanya korelasi positif yang kuat antara pendapatan dan pengeluaran total, yang menunjukkan hubungan yang signifikan antara tingkat pendapatan dan pola pengeluaran; dengan demikian, semakin tinggi pendapatan seseorang, semakin besar kemungkinan mereka mengeluarkan lebih banyak uang. Dalam dunia bisnis, pemahaman seperti ini dapat membantu bisnis memahami segmen pelanggan yang memiliki potensi pembelian yang lebih besar dan membuat strategi pemasaran yang tepat untuk meningkatkan keterlibatan dan kepuasan pelanggan.

## Bagian 2: Data Cleaning, Preprocessing, dan Feature Engineering
Pada proses ini dilakukan pemrosesan data sekaligus pembersihan data, yang terdiri dari:
1. Pemeriksaan null / missing value pada data
2. Pemeriksaan duplikasi data
3. Pemeriksaan tipe data dan konsistensi nilai
4. Pemeriksaan outlier atau data yang tidak biasa<br>
Hasilnya tertera pada tabel dibawah.<br>
| Asesmen Data       | Temuan                                                                                                     | Penyelesaian                              |
|--------------------|------------------------------------------------------------------------------------------------------------|-------------------------------------------|
| _Null Values_      | Tidak terdapat _null values_                                                                               | -                                         |
| _Duplicate Values_ | Tidak terdapat _duplicate values_                                                                          | -                                         |
| Konsistensi Nilai  | Tipe data `dt_customer` sebaiknya _datetime_                                                               | Mengubah tipe data nya menjadi _datetime_ |
| Nilai Anomali      | Keseluruhan fitur memiliki _outlier_. Terlihat juga fitur `income` dan `year_birth` memiliki nilai ekstrim | _Handling outlier_ menggunakan IQR        |
Selain itu pada tahapan ini, dilakukan pembuatan fitur baru berdasar fitur yang telah ada, bertujuan untuk membuat analisis menjadi lebih bermakna. Fitur baru ini dapat memberi informasi tambahan dengan menggabungkan beberapa fitur yang saling berhubungan untuk membentuk fitur yang lebih baik. Selengkapnya dapat dilihat pada tabel dibawah.


## Bagian 3: Data Modelling


## Bagian 4: Analisis Kepribadian Pelanggan Untuk Retargeting Pemasaran
