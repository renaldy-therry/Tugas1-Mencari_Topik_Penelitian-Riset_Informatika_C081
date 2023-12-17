# Tugas Riset Informatika C081 

Nama = Renaldy William Lijaya Therry 
NPM = 20081010179 
Kelas = Riset Informatika C081 
Jurusan = Informatika 
Fakultas = Ilmu Komputer 

**Topik Penelitian**
**ANALISIS DATA COVID 19 DI INDONESIA DENGAN METODE KMEANS TIME SERIES CLUSTERING**

**Latar Belakang**

Pandemi COVID-19 adalah krisis kesehatan global yang telah menimbulkan dampak besar bagi seluruh dunia, termasuk Indonesia. Sejak kasus pertama COVID-19 diumumkan pada Maret 2020, jumlah kasus positif, sembuh, dan meninggal akibat COVID-19 terus meningkat di Indonesia. Hingga Juli 2021, Indonesia telah melaporkan lebih dari 3 juta kasus positif dan lebih dari 80 ribu kematian akibat COVID-19

Dalam upaya mengendalikan penyebaran COVID-19, pemerintah Indonesia telah menerapkan berbagai kebijakan, seperti pembatasan sosial berskala besar (PSBB), pemberlakuan pembatasan kegiatan masyarakat (PPKM), dan program vaksinasi nasional. Namun, kebijakan-kebijakan ini tidak selalu efektif dan konsisten di seluruh provinsi di Indonesia, karena adanya perbedaan karakteristik, kondisi, dan kapasitas daerah

Oleh karena itu, diperlukan analisis data COVID-19 yang dapat memberikan gambaran tentang situasi dan dinamika pandemi di Indonesia, serta mengidentifikasi pola dan faktor-faktor yang mempengaruhi penyebaran COVID-19 di berbagai provinsi. Salah satu metode analisis data yang dapat digunakan adalah kmeans time series clustering.

Kmeans time series clustering adalah metode pengelompokan data berdasarkan kemiripan pola waktu (time series) antara data. Metode ini dapat mengelompokkan data COVID-19 berdasarkan tren dan fluktuasi kasus positif, sembuh, dan meninggal di setiap provinsi, sehingga dapat menghasilkan kelompok-kelompok provinsi yang memiliki karakteristik penyebaran COVID-19 yang serupa

Dengan menggunakan metode kmeans time series clustering, penelitian ini diharapkan dapat memberikan kontribusi dalam hal:

- Memberikan pemahaman yang lebih mendalam tentang situasi dan dinamika pandemi COVID-19 di Indonesia, khususnya di tingkat provinsi.

- Mengidentifikasi faktor-faktor yang mempengaruhi penyebaran COVID-19 di berbagai provinsi, seperti kepadatan penduduk, mobilitas masyarakat, tingkat tes, dan cakupan vaksinasi.

- Memberikan rekomendasi kebijakan yang sesuai dengan kondisi dan kebutuhan masing-masing provinsi dalam menangani pandemi COVID-19.

**Metodologi penelitian**

Penelitian ini menggunakan metode kuantitatif karena menganalisis data dengan menggunakan metode kmeans clustering yang melibatkan matematika di dalamnya

**Metode Penelitian**

1. Analisis data menggunakan Python dan library-library tambahan
2. Data didapatkan dari kaggle dengan data berisi jumlah kematian , kesembuhan per provinsi
3. Data dianalisis mengggunakan Kmeans clustering time series

**Hasil Penelitian**

**Jumlah Kasus Covid Per Cluster**
![kasus](hasil%20penelitian/angka%20kasus%20per%20klaster.png)
Hasil analisis data menggunakan kmeans clustering menunjukkan data terbagi 
atas 6 klaster dengan angka kasus tertinggi berada pada kluster 4 yaitu DKI Jakarta dengan total kasus sebesar 1412511

**Angka Kematian**
![kematian](hasil%20penelitian/angka%20kematian%20per%20kluster.png)
Hasil analisis data menggunakan kmeans clustering menunjukkan data terbagi 
atas 6 klaster dengan angka kematian tertinggi berada pada kluster 2 yaitu Lampung dengan angka kematian 0,554
 

**Dataset**
Dataset didapat dari kaggle dengan link sebagai berikut :\
<https://www.kaggle.com/datasets/hendratno/covid19-indonesia>

(Kobylin & Lyashenko, 2020; Moh. Fatkuroji et al., 2022; Sari & Yunita, 2021)

**Gambar Pendukung**
![dataset](gambar%20pendukung/dataset.png)
![total kasus](gambar%20pendukung/total%20kasus.png)

**Referensi**

[Kobylin, O., & Lyashenko, V. (2020). Time Series Clustering Based on the K-Means Algorithm. *Journal La Multiapp*, *1*(3), 1--7. https://doi.org/10.37899/journallamultiapp.v1i3.191](http://newinera.com/index.php/JournalLaMultiapp/article/download/191/123/)

[Moh. Fatkuroji, Fajrizal, Taslim, Eka Sabna, & Kursiah Warti Ningsih. (2022). Optimasi Nilai K Pada Algoritma k-Means untuk Klasterisasi Data Pasien Covid-19. *Indonesian Journal of Computer Science*, *11*(2), 697--707. https://doi.org/10.33022/ijcs.v11i2.3088](http://ijcs.stmikindonesia.ac.id/ijcs/index.php/ijcs/article/view/3088/66)

[Sari, D. N., & Yunita, I. (2021). Tingkat Keparahan Dan Risiko Penyebaran Covid-19 Di Indonesia Dengan Menggunakan K-Means Clustering. *Seminar Nasional Official Statistics*, *2020*(1), 210--216. https://doi.org/10.34123/semnasoffstat.v2020i1.706](https://prosiding.stis.ac.id/index.php/semnasoffstat/article/view/706/110)
