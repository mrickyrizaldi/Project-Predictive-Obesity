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
Tujuan dari proyek ini adalah untuk mengembangkan model klasifikasi tingkat obesitas berdasarkan data gaya hidup, pola makan, dan kondisi fisik individu menjadi tujuh kelas berbeda yaitu **Insufficient_Weight, Normal_Weight, Overweight_Level_I, Overweight_Level_II, Obesity_Type_I, Obesity_Type_II, dan Obesity_Type_III**. Pembagian ini dibuat untuk memberikan tingkat ketelitian lebih baik, sehingga sistem dapat mendeteksi risiko sejak dini dan menyesuaikan intervensi berdasarkan tingkat keparahan untuk mencegah dampak-dampak buruk akibat obesitas. Disamping itu, ini dilakukan agar pendekatan yang digunakan tidak bersifat umum, melainkan presisi dan personal. Misalnya, individu dengan Overweight_Level_I membutuhkan edukasi gaya hidup, sedangkan Obesity_Type_III membutuhkan penanganan medis lebih serius. Dengan demikian, sistem ini tidak hanya mampu mengidentifikasi kondisi obesitas secara akurat, tetapi juga memberikan manfaat praktis bagi pengambilan keputusan di bidang kesehatan masyarakat. Oleh karena itu, di bawah ini akan dirumuskan beberapa pernyataan masalah yang akan diselesaikan dalam proyek ini:

### Problem Statements
1. Bagaimana mengidentifikasi faktor-faktor utama dalam kondisi fisik, gaya hidup dan kebiasaan individu yang berkorelasi dengan tingkat obesitas?
2. Bagaimana merancang model klasifikasi obesitas berbasis machine learning yang mampu membedakan tujuh kategori tingkat obesitas secara akurat?
3. Bagaimana mengoptimalkan performa prediksi model agar dapat digunakan sebagai alat bantu deteksi obesitas yang akurat dan efisien?

### Goals
1. Mengidentifikasi faktor-faktor yang paling signifikan dan relevan dalam memengaruhi tingkat obesitas melalui analisis korelasi, visualisasi distribusi data, dan teknik statistik eksploratif. Proses ini bertujuan untuk memahami bagaimana variabel tertentu berkaitan dengan tingkat obesitas seseorang.
2.  Mengembangkan model yang mampu memprediksi tingkat obesitas secara otomatis dan akurat berdasarkan data yang tersedia menggunakan beberapa algoritma optimal serta melakukan perbandingan performa antar model yang telah dibuat untuk pemilihan model terbaik.
3.  Menentukan baseline model dan menerapkan optimasi hyperparameter tuning pada semua parameter model menggunakan teknik Random Search untuk meningkatkan akurasi dan keandalan prediksi berdasarkan parameter terbaik yang diperoleh. 

**Solution Statements**:
- **Solusi 1:** Menerapkan tahapan Exploratory Data Analysis untuk mengidentifikasi faktor-faktor yang berpengaruh, baik positif dan negatif. Dengan melakukan analisis korelasi antar fitur, visualisasi korelasi ataupun dengan teknik statistik eksploratif. Pada tahapan ini diharapkan semua fitur memiliki pengaruh terhadap tingkat obesitas seseorang agar membuktikan bahwa prediksi memang dipengaruhi berbagai faktor kompleks seperti pada tujuan awal.
- **Solusi 2:** Menguji coba beberapa algoritma model machine learning, dalam hal ini penelitian akan fokus menggunakan model ensemble yang telah terbukti memiliki akurasi yang baik berdasarkan penelitian terkait yaitu memanfaatkan algoritma Random Forest dan Boosting Algorithm. Kemudian akan dilakukan evaluasi secara menyeluruh menggunakan metrik akurasi sebagai pembanding utama yang mengukur persentase prediksi benar dibandingkan total sampel serta precision, recall, dan F1-Score untuk metrik tambahan. Selain itu digunakan juga classification reports untuk memberikan detail metrik untuk setiap kelas yang diprediksi dan confusion matrix untuk menunjukkan jumlah prediksi benar dan salah untuk setiap kelas. Model dengan hasil evaluasi terbaik akan dipilih sebagai baseline model.
- **Solusi 3:** Model yang dihasilkan pada tahap modeling belum tentu optimal sehingga perlu dilakukan proses Hyperparameter tuning untuk mendapatkan parameter basemodel yang terbaik sehingga dapat meningkatkan performa model terutama berdasarkan metrik akurasinya  dengan menggunakan teknik Random Search agar mengurangi waktu pencarian parameter optimal. Setelah parameter optimal didapat akan dilakukan training ulang dan dilakukan evaluasi menyeluruh dan jika terbukti meningkatkan akurasi dibandingkan basemodel, maka model dengan parameter hasil fine tuning akan dipilih menjadi model akhir.

## Data Understanding
Dataset yang digunakan pada proyek klasifikasi tingkat obesitas ini terdiri dari 2.111 baris data, 17 fitur, dan 1 target berisi 7 kelas yang dikumpulkan dari individu yang berasal dari negara Mexico, Peru, dan Kolombia. Dataset ini mencakup data terkait kebiasaan makan, aktivitas fisik, serta kondisi fisik pengguna. Sekitar 23% data dikumpulkan langsung dari pengguna melalui platform daring, sedangkan 77% lainnya dihasilkan secara sintetis menggunakan teknik oversampling SMOTE melalui Weka. Dataset ini dapat diakses melalui tautan berikut: [Obesity Levels Dataset - Kaggle](https://www.kaggle.com/datasets/fatemehmehrparvar/obesity-levels)

### Variabel-variabel pada Obesity Levels Dataset adalah sebagai berikut:
- **Gender**: Jenis kelamin responden (Kategorikal: Male/Female).
- **Age**: Usia responden dalam tahun (Kontinu).
- **Height**: Tinggi badan dalam meter (Kontinu).
- **Weight**: Berat badan dalam kilogram (Kontinu).
- **family_history_with_overweight**: Riwayat keluarga dengan kelebihan berat badan (Biner: yes/no).
- **FAVC**: Sering mengonsumsi makanan berkalori tinggi? (Biner: yes/no).
- **FCVC**: Frekuensi konsumsi sayuran dalam makanan harian (Diskrit: 1-3), angka mungkin mewakili sedikit/tidak ada, sedang dan tinggi.
- **NCP**: Jumlah makanan utama per hari (Kontinu: 1-4).
- **CAEC**: Kebiasaan ngemil di antara waktu makan (Kategorikal: no, sometimes, frequently, always).
- **SMOKE**: Apakah merokok? (Biner: yes/no).
- **CH2O**: Konsumsi air harian (Kontinu: 1-3 liter).
- **SCC**: Monitor kalori harian yang dikonsumsi (Biner: yes/no).
- **FAF**: Frekuensi aktivitas fisik (Kontinu: 0-3), angka mungkin mewakili tidak ada, jarang, sering dan selalu.
- **TUE**: Waktu yang dihabiskan untuk perangkat teknologi per hari (Diskrit: 0-2), angka mungkin mewakili sedikit/tidak ada, sedang dan tinggi.
- **CALC**: Frekuensi konsumsi alkohol (Kategorikal: no, sometimes, frequently, always).
- **MTRANS**: Moda transportasi utama yang digunakan (Kategorikal: Public_Transportation, Walking, Automobile, Motorbike, Bike).
- **NObeyesdad**: Label target yang menunjukkan tingkat obesitas (Kategorikal: Insufficient_Weight, Normal_Weight, Overweight_Level_I, Overweight_Level_II, Obesity_Type_I, Obesity_Type_II, dan Obesity_Type_III):

### Tahapan Pemahaman Data
![image](https://github.com/user-attachments/assets/ddec28e4-813c-421b-816d-19202204c3d0)


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
