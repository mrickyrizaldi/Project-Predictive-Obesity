# Laporan Proyek Machine Learning - Muhammad Ricky Rizaldi

## Domain Proyek
### Latar Belakang
Obesitas kini menjadi tantangan kesehatan yang signifikan, tidak hanya di tingkat global tetapi juga nasional. Berdasarkan data terbaru dari World Health Organization (WHO), pada tahun 2022 terdapat 2,5 miliar orang dewasa berusia 18 tahun ke atas yang mengalami kelebihan berat badan dan lebih dari 890 juta yang hidup dengan obesitas. Yang menunjukkan bahwa sekitar 43% populasi dewasa dunia mengalami kelebihan berat badan serta 16% di antaranya termasuk dalam kategori obesitas. Prevalensi overweight ini bervariasi secara regional, mulai dari 31% di kawasan Asia Tenggara dan Afrika hingga 67% di kawasan Amerika (WHO, 2024). Di Indonesia sendiri, tren serupa juga muncul dimana berdasarkan data Riskesdas menunjukkan bahwa prevalensi obesitas meningkat dari 10,5% pada tahun 2007 menjadi 21,8% pada tahun 2018 (Badriyah and Pratiwi, 2024), dimana presentase yang lebih tinggi dimiliki oleh perempuan sebanyak 29,6% dibandingkan laki-laki yang hanya 25% (Nasim et al., 2024). Kekhawatiran juga muncul pada kelompok usia muda. Di seluruh dunia, terdapat 37 juta anak di bawah usia 5 tahun mengalami kelebihan berat badan pada tahun 2022. Sementara itu, lebih dari 390 juta anak dan remaja usia 5–19 tahun juga mengalami kelebihan berat badan, serta 160 juta yang hidup dengan obesitas, angka ini meningkat pesat dari hanya 8% pada tahun 1990 menjadi 20% pada 2022. Kenaikan ini terjadi merata pada anak laki-laki maupun perempuan, masing-masing mencapai 21% dan 19%. Di Afrika, jumlah anak di bawah usia 5 tahun yang overweight meningkat hampir 23% sejak tahun 2000, dan hampir setengah dari total anak yang overweight di dunia berada di Asia (WHO, 2024).

### Mengapa dan Bagaimana Masalah Ini Harus Diselesaikan
Secara medis, obesitas meningkatkan risiko penyakit metabolik seperti diabetes tipe 2, hipertensi, dislipidemia, serta penyakit jantung, melalui mekanisme seperti resistensi insulin, gangguan hormon leptin, dan aktivasi sistem saraf simpatis serta sistem renin-angiotensin (Badriyah and Pratiwi, 2024). Selain itu, kondisi ini juga berhubungan dengan gangguan pernapasan seperti sleep apnea dan penyakit hati berlemak non-alkohol serta memiliki dampak psikologis pada anak dan remaja seperti meningkatnya risiko depresi dan kecemasan (Nasim et al., 2024). Selain itu, dalam skala global, obesitas menjadi salah satu penyebab utama meningkatnya beban penyakit tidak menular dan terbukti memperparah kondisi pasien saat terinfeksi Covid-19 (Badriyah and Pratiwi, 2024). Berdasarkan itu, obesitas menjadi sangat perlu untuk ditangani agar tidak sampai menimbulkan atau memperparah penyakit-penyakit lainnya.

Obesitas disebabkan oleh kombinasi kompleks antara faktor genetik, perilaku, dan lingkungan. Secara genetik, beberapa individu memang memiliki kecenderungan alami untuk menyimpan lemak lebih banyak akibat mutasi gen yang memengaruhi metabolisme (Saraswati et al., 2021). Namun, gaya hidup juga memainkan peran besar. Pola makan tinggi kalori, minim aktivitas fisik, kebiasaan jajan, kurang tidur, tingginya durasi screen time serta moda transportasi yang kurang aktif  memperbesar risiko penambahan berat badan. Selain itu, seiring bertambahnya usia terutama setelah 25 tahun dan saat menopause yang mengakibatkan laju metabolisme tubuh menurun, membuat penumpukan lemak lebih mudah terjadi (Saraswati et al., 2021; Sukmawati et al., 2024). Oleh karena itu, obesitas tidak bisa dilihat dari satu sisi saja, melainkan perlu ditangani dengan pendekatan yang menyeluruh dan multidisipliner.

Penanganan obesitas seringkali baru dilakukan ketika kondisi sudah parah, sementara metode tradisional seperti pemeriksaan BMI manual atau wawancara kesehatan kurang efisien untuk deteksi skala besar dan cenderung melewatkan individu berisiko tinggi. Di daerah terpencil, keterbatasan tenaga medis dan fasilitas juga menjadi kendala dalam penilaian yang akurat. Oleh karena itu, proyek ini bertujuan mengembangkan model klasifikasi berbasis machine learning yang mampu memprediksi tingkat obesitas menggunakan data gaya hidup, pola makan, dan kondisi fisik individu dengan membaginya menjadi tujuh kelas yaitu Insufficient_Weight, Normal_Weight, Overweight_Level_I, Overweight_Level_II, Obesity_Type_I, Obesity_Type_II, Obesity_Type_III. Dengan memanfaatkan kemampuan machine learning dalam mengenali pola kompleks antarvariabel, model ini diharapkan dapat memberikan deteksi dini yang lebih akurat dan personal, sehingga mendukung intervensi tepat guna dalam preventive obesitas.

### Penelitian Terkait
Berbagai penelitian telah memanfaatkan machine learning untuk memprediksi dan mengklasifikasikan obesitas berdasarkan gaya hidup dan pola makan. dengan data studi di Meksiko menunjukkan bahwa algoritma Support Vector Machine (SVM) memiliki akurasi lebih tinggi (89%) dibanding Naïve Bayes (65%) dalam memprediksi tingkat obesitas menggunakan data dari Kaggle (Ardianta et al., 2024). Di Indonesia, penelitian pada mahasiswa menggunakan data dari accelerometer menunjukkan bahwa Random Forest memiliki akurasi tertinggi (71,09%) dibanding KNN, Decision Tree, dan CVR dalam memprediksi risiko obesitas berdasarkan aktivitas fisik dan perilaku sedentari (Hardwis & Jajat, 2024). Penelitian lain juga membandingkan AdaBoost dan XGBoost, di mana XGBoost menunjukkan keunggulan signifikan dengan akurasi 92% dibandingkan 40% pada AdaBoost dalam mengolah data kompleks (Sukmawati et al., 2024). Selain itu, penelitian menggunakan data studi di Meksiko, Peru, dan Kolombia melaporkan bahwa Random Forest mampu mencapai akurasi 93,38% dalam mengklasifikasikan tingkat obesitas, terutama pada kategori obesitas tipe I dan III, serta mengungguli algoritma KNN dan Naïve Bayes (Aini et al., 2024). Hal ini membuktikan bahwa dengan pendekatan machine learning dapat digunakan untuk melakukan prediksi obesitas.

### Referensi
1. [Obesity and overweight, WHO (2024)](https://www.who.int/news-room/fact-sheets/detail/obesity-and-overweight) 
2. [Hubungan Obesitas dengan Kejadian Hipertensi dan Hiperglikemia di Indonesia, Badriyah and Pratiwi (2024)](https://jurnal.fkm.untad.ac.id/index.php/ghidza/article/view/1021)
3. [Klasifikasi Obesitas Dengan Algoritma C5.0 Berdasarkan Pola Makan Dan Kondisi Fisik, Nasim et al. (2024)](https://ejournal.bsi.ac.id/ejurnal/index.php/khatulistiwa/article/view/23974)
4. [Literature Review : Faktor Risiko Penyebab Obesitas, Saraswati et al. (2021)](https://ejournal.undip.ac.id/index.php/mkmi/article/view/34930)
5. [Evaluasi Kinerja Algoritma AdaBoost dan XGBoost Menggunakan Dataset Penyakit Obesitas Pada Populasi Dewasa, Sukmawati et al. (2024)](https://ejurnal.ung.ac.id/index.php/jji/article/view/27342)
6. [Optimalisasi Prediksi Tingkat Obesitas di Negara Mexico Menggunakan Perbandingan Support Vector Machine dan Naïve Bayes, Ardianta et al. (2024)](https://proceeding.unpkediri.ac.id/index.php/inotek/article/view/5099)
7. [Analisis Resiko Obesitas Berdasarkan Aktivitas Fisik: Implementasi Metode Artificial Intelligence Machine Learning, Hardwis & Jajat (2024)](https://jurnal.unigal.ac.id/JKP/article/view/16884)
8. [Penggunaan Data Mining untuk Prediksi tingkat Obesitas di Meksiko Menggunakan Metode Random Forest, Aini et al. (2024)](https://proceeding.unpkediri.ac.id/index.php/inotek/article/view/5062)

## Business Understanding

Pada bagian ini, kamu perlu menjelaskan proses klarifikasi masalah.

Bagian laporan ini mencakup:

### Problem Statements

Menjelaskan pernyataan masalah latar belakang:
- Pernyataan Masalah 1
- Pernyataan Masalah 2
- Pernyataan Masalah n

### Goals

Menjelaskan tujuan dari pernyataan masalah:
- Jawaban pernyataan masalah 1
- Jawaban pernyataan masalah 2
- Jawaban pernyataan masalah n

Semua poin di atas harus diuraikan dengan jelas. Anda bebas menuliskan berapa pernyataan masalah dan juga goals yang diinginkan.

**Rubrik/Kriteria Tambahan (Opsional)**:
- Menambahkan bagian “Solution Statement” yang menguraikan cara untuk meraih goals. Bagian ini dibuat dengan ketentuan sebagai berikut: 

    ### Solution statements
    - Mengajukan 2 atau lebih solution statement. Misalnya, menggunakan dua atau lebih algoritma untuk mencapai solusi yang diinginkan atau melakukan improvement pada baseline model dengan hyperparameter tuning.
    - Solusi yang diberikan harus dapat terukur dengan metrik evaluasi.

## Data Understanding
Paragraf awal bagian ini menjelaskan informasi mengenai data yang Anda gunakan dalam proyek. Sertakan juga sumber atau tautan untuk mengunduh dataset. Contoh: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Restaurant+%26+consumer+data).

Selanjutnya uraikanlah seluruh variabel atau fitur pada data. Sebagai contoh:  

### Variabel-variabel pada Restaurant UCI dataset adalah sebagai berikut:
- accepts : merupakan jenis pembayaran yang diterima pada restoran tertentu.
- cuisine : merupakan jenis masakan yang disajikan pada restoran.
- dst

**Rubrik/Kriteria Tambahan (Opsional)**:
- Melakukan beberapa tahapan yang diperlukan untuk memahami data, contohnya teknik visualisasi data atau exploratory data analysis.

## Data Preparation
Pada bagian ini Anda menerapkan dan menyebutkan teknik data preparation yang dilakukan. Teknik yang digunakan pada notebook dan laporan harus berurutan.

**Rubrik/Kriteria Tambahan (Opsional)**: 
- Menjelaskan proses data preparation yang dilakukan
- Menjelaskan alasan mengapa diperlukan tahapan data preparation tersebut.

## Modeling
Tahapan ini membahas mengenai model machine learning yang digunakan untuk menyelesaikan permasalahan. Anda perlu menjelaskan tahapan dan parameter yang digunakan pada proses pemodelan.

**Rubrik/Kriteria Tambahan (Opsional)**: 
- Menjelaskan kelebihan dan kekurangan dari setiap algoritma yang digunakan.
- Jika menggunakan satu algoritma pada solution statement, lakukan proses improvement terhadap model dengan hyperparameter tuning. **Jelaskan proses improvement yang dilakukan**.
- Jika menggunakan dua atau lebih algoritma pada solution statement, maka pilih model terbaik sebagai solusi. **Jelaskan mengapa memilih model tersebut sebagai model terbaik**.

## Evaluation
Pada bagian ini anda perlu menyebutkan metrik evaluasi yang digunakan. Lalu anda perlu menjelaskan hasil proyek berdasarkan metrik evaluasi yang digunakan.

Sebagai contoh, Anda memiih kasus klasifikasi dan menggunakan metrik **akurasi, precision, recall, dan F1 score**. Jelaskan mengenai beberapa hal berikut:
- Penjelasan mengenai metrik yang digunakan
- Menjelaskan hasil proyek berdasarkan metrik evaluasi

Ingatlah, metrik evaluasi yang digunakan harus sesuai dengan konteks data, problem statement, dan solusi yang diinginkan.

**Rubrik/Kriteria Tambahan (Opsional)**: 
- Menjelaskan formula metrik dan bagaimana metrik tersebut bekerja.

**---Ini adalah bagian akhir laporan---**

_Catatan:_
- _Anda dapat menambahkan gambar, kode, atau tabel ke dalam laporan jika diperlukan. Temukan caranya pada contoh dokumen markdown di situs editor [Dillinger](https://dillinger.io/), [Github Guides: Mastering markdown](https://guides.github.com/features/mastering-markdown/), atau sumber lain di internet. Semangat!_
- Jika terdapat penjelasan yang harus menyertakan code snippet, tuliskan dengan sewajarnya. Tidak perlu menuliskan keseluruhan kode project, cukup bagian yang ingin dijelaskan saja.
