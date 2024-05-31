Web Scraping, Business Knowledge dan Practical Statistics:

- Mengambil data dari sumber internet dengan Web Scraping
- Melakukan data preparation sebelum analisis selanjutnya
- Membangun problem statement dengan framework SMART sebagai salah satu langkah business understanding
- Melakukan perhitungan statistik deskriptif
- Melakukan pengujian statistik dan merumuskan hipotesis
- Mengambil insight/informasi dari hasil perhitungan
- Mengambil kesimpulan yang menjawab problem statement

---
## Objectives
Program ini dibuat menganalysis data penjualan seblak dari ratingnya, harganya, banyak terjualnya, kota penjualnya. Untuk nantinya saya dapat berjualan seblak dengan mengetahui bagaimana marketnya di tokopedia agar saat berjualan nantinya saya sudah mengetahui harus dijual dengan harga berapa agar dapat laku dan menguntungkan. Data-data tersebut diambil dengan Web Scraping website tokopedia kategori seblak.


#### A. Web Scraping
1. Lakukan pengambilan data dari halaman pencarian kata kunci produk "seblak".
  https://www.tokopedia.com/search?navsource=&page=1&q=seblak&srp_component_id=02.01.00.00&srp_page_id=&srp_page_title=&st=


#### B. Data Preparation

1. Lakukan eksplorasi data sederhana (menampilkan data, informasi data, cek missing value)
2. Lakukan data cleaning (handle missing value bila ada, mengubah bentuk data menjadi konsisten dan menyesuaikan tipe data)

#### C. Business Understanding/Problem Statement
**`SMART`**

> Specific
* Meningkatkan penjualan produk seblak di Tokopedia.

> Measurment
* Menargetkan peningkatan 20% kenaikan penjualan produk seblak dari jumlah produk seblak yang terjual sebelumnya.

> Achievable
* Melakukan peningkatan kualitas produk seblak selama 1.5 bulan pertama, kemudian melakukan analisis data yang tepat untuk memahami preferensi atau keinginan konsumen di 1.5 bulan berikutnya, dan di bulan ke 4 melakukan optimasi strategi pemasaran online (paid advertisement di social media atau endosrment).

> Relevant
* Peningkatan kualitas seblak, dan optimasi strategi pemasaran akan memberikan stimulasi terhadap target pasar, dan memberikan dampak positif untuk produk seblak.

> Time-Bound
* Mencapai peningkatan penjualan minimal 20% dalam waktu empat bulan.

> Conclusions
* meningkatkan penjualan seblak di tokopedia dengan melakukan improvement produk, analisis keingin konsumen, dan promosi sehingga penjualan dapat naik 20% dalam waktu 4 bulan.

#### D. Analysis
  Dalam melakukan analisa data untuk mencapai tujuan yang diinginkan, kamu perlu mengikuti soal/pertanyaan/instruksi berikut ini:
1. menghitung rata-rata, median, standar deviasi, skewness, dan kurtosis dari kolom harga, banyak produk terjual, dan rating.

2. Menghitung berapa potensi minimum dan maksimum pendapatan jika kamu menjual produk seblak?(menggunakan confidence interval untuk mendapatkan lower value dan upper value dari distribusi populasi pendapatan).

  Anggap data terdistribusi normal dan informasi produk terjual merupakan penjualan produk per bulan. Ambil confidence level 95%.

3. Ingin mengetahui apakah harga barang di Jabodetabek dan di luar Jabodetabek berbeda atau tidak, mengingat biaya bahan baku di kedua lokasi berbeda. (menggunakan uji hipotesis yang diawali dengan menuliskan hipotesis null dan alternatifnya serta menentukan jenis hipotesis yang digunakan).

4. Ingin mengetahui apakah orang lebih cenderung suka dengan produk yang harganya murah? Analisis nilai korelasi dan p-value nya.


#### E. Conclusion
  Berdasarkan analisis yang telah dilakukan penjualan seblak di tokopedia:
  * rata-rata harga seblak yang dijual di tokopedia adalah Rp17.863
  * dengan rata-rata ratingnya 4.89, dapat dikatakan orang-orang menyukai produk seblak yang dijual
  * dengan rata-rata seblak terjual adalah 721.2 seblak, dapat dikatakan banyak orang yang membeli seblak di tokopedia
  * lebih banyak seblak yang terjual jika harganya lebih murah
  * Penjualan di jabodetabek dan di luar jabodetabek memiliki harga yang sama ataupun hampir sama walaupun biaya bahan baku di kedua lokasi berbeda
  * Jika saya memulai menjual seblak di tokopedia pendapatan minimal saya adalah Rp2.921.511 dan pendapatan maksimumnya Rp10.853.461 dalam waktu 1 bulan

  > Dari data-data diatas saya dapat memulai berjualan seblak dengan mengetahui bagaimana marketnya di tokopedia sehingga saat berjualan saya sudah mengetahui harus dijual dengan harga berapa, variasi harga yang saya bisa gunakan agar seblak yang saya jual nanti dapat laku dan menguntungkan.