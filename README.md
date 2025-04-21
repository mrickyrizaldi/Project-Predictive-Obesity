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

### Solution Statements
- **Solusi 1:** Menerapkan tahapan Exploratory Data Analysis untuk mengidentifikasi faktor-faktor yang berpengaruh, baik positif dan negatif. Dengan melakukan analisis korelasi antar fitur, visualisasi korelasi ataupun dengan teknik statistik eksploratif. Pada tahapan ini diharapkan semua fitur memiliki pengaruh terhadap tingkat obesitas seseorang agar membuktikan bahwa prediksi memang dipengaruhi berbagai faktor kompleks seperti pada tujuan awal.
- **Solusi 2:** Menguji coba beberapa algoritma model machine learning, dalam hal ini penelitian akan fokus menggunakan model ensemble yang telah terbukti memiliki akurasi yang baik berdasarkan penelitian terkait yaitu memanfaatkan algoritma Random Forest dan Boosting Algorithm. Kemudian akan dilakukan evaluasi secara menyeluruh menggunakan metrik akurasi sebagai pembanding utama yang mengukur persentase prediksi benar dibandingkan total sampel serta precision, recall, dan F1-Score untuk metrik tambahan. Selain itu digunakan juga classification reports untuk memberikan detail metrik untuk setiap kelas yang diprediksi dan confusion matrix untuk menunjukkan jumlah prediksi benar dan salah untuk setiap kelas. Model dengan hasil evaluasi terbaik akan dipilih sebagai baseline model.
- **Solusi 3:** Model yang dihasilkan pada tahap modeling belum tentu optimal sehingga perlu dilakukan proses Hyperparameter tuning untuk mendapatkan parameter basemodel yang terbaik sehingga dapat meningkatkan performa model terutama berdasarkan metrik akurasinya  dengan menggunakan teknik Random Search agar mengurangi waktu pencarian parameter optimal. Setelah parameter optimal didapat akan dilakukan training ulang dan dilakukan evaluasi menyeluruh dan jika terbukti meningkatkan akurasi dibandingkan basemodel, maka model dengan parameter hasil fine tuning akan dipilih menjadi model akhir.

## Data Understanding
Dataset yang digunakan pada proyek klasifikasi tingkat obesitas ini terdiri dari 2.111 baris data, 17 fitur, dan 1 target berisi 7 kelas yang dikumpulkan dari individu yang berasal dari negara Mexico, Peru, dan Kolombia. Dataset ini mencakup data terkait kebiasaan makan, aktivitas fisik, serta kondisi fisik pengguna. Sekitar 23% data dikumpulkan langsung dari pengguna melalui platform daring, sedangkan 77% lainnya dihasilkan secara sintetis menggunakan teknik oversampling SMOTE melalui Weka. Dataset ini dapat diakses melalui tautan berikut: [Obesity Levels - Kaggle Dataset](https://www.kaggle.com/datasets/fatemehmehrparvar/obesity-levels)

### Variabel-variabel pada Obesity Levels Dataset adalah sebagai berikut:
- **Gender**: Jenis kelamin responden `(Kategorikal: Male/Female)`.
- **Age**: Usia responden dalam tahun `(Kontinu)`.
- **Height**: Tinggi badan dalam meter `(Kontinu)`.
- **Weight**: Berat badan dalam kilogram `(Kontinu)`.
- **family_history_with_overweight**: Riwayat keluarga dengan kelebihan berat badan `(Biner: yes/no)`.
- **FAVC**: Sering mengonsumsi makanan berkalori tinggi? `(Biner: yes/no)`.
- **FCVC**: Frekuensi konsumsi sayuran dalam makanan harian `(Diskrit: 1-3)`, angka mungkin mewakili sedikit/tidak ada, sedang dan tinggi.
- **NCP**: Jumlah makanan utama per hari `(Kontinu: 1-4)`.
- **CAEC**: Kebiasaan ngemil di antara waktu makan `(Kategorikal: no, sometimes, frequently, always)`.
- **SMOKE**: Apakah merokok? `(Biner: yes/no)`.
- **CH2O**: Konsumsi air harian `(Kontinu: 1-3 liter)`.
- **SCC**: Monitor kalori harian yang dikonsumsi `(Biner: yes/no)`.
- **FAF**: Frekuensi aktivitas fisik `(Kontinu: 0-3)`, angka mungkin mewakili tidak ada, jarang, sering dan selalu.
- **TUE**: Waktu yang dihabiskan untuk perangkat teknologi per hari `(Diskrit: 0-2)`, angka mungkin mewakili sedikit/tidak ada, sedang dan tinggi.
- **CALC**: Frekuensi konsumsi alkohol `(Kategorikal: no, sometimes, frequently, always)`.
- **MTRANS**: Moda transportasi utama yang digunakan `(Kategorikal: Public_Transportation, Walking, Automobile, Motorbike, Bike)`.
- **NObeyesdad**: Label target yang menunjukkan tingkat obesitas `(Kategorikal: Insufficient_Weight, Normal_Weight, Overweight_Level_I, Overweight_Level_II, Obesity_Type_I, Obesity_Type_II, dan Obesity_Type_III)`:

### Tahapan Pemahaman Data
1. Tahapan pertama adalah melakukan Exploratory Data Analisis menggunakan `.info()` untuk menampilkan ringkasan informasi struktur dataset berupa tipe data dan jumlah dataset, kemudian melakukan metode statistik deskriptif dari kolom numerik dengan fungsi `.describe()` untuk mengetahui sebaran data dan gambaran distribusi data, selanjutnya menampilkan daftar nilai unik (kategori) pada setiap fitur kategorikal untuk memahami variasi data dari tiap kategori.
   
      ![image](https://github.com/user-attachments/assets/e3d33cf4-41ae-499e-9850-76d31433105f)
      ![image](https://github.com/user-attachments/assets/ddec28e4-813c-421b-816d-19202204c3d0)
      ![image](https://github.com/user-attachments/assets/b93ba1af-b814-4134-9690-28b3eea7bb7d)

2. Tahapan selanjutnya adalah melakukan EDA sebagai pertimbangan apa yang harus ditangani pada tahapan preprocessing nantinya meliputi pengecekan jumlah nilai yang hilang (missing values) menggunakan `isnan().sum()`, jumlah baris data yang duplikat menggunakan `.duplicated().sum()`, dan pengecekan fitur yang mengandung outliers menggunakan IQR method. Selain itu juga dilakukan visualisasi untuk membantu memahami bagaimana distribusi data kategorikal dan numerikal serta sebaran data untuk visualisasi statistik maupun outliers dari data. Kemudian yang terakhir yaitu melakukan pengecekan fitur redundan dan korelasi fitur dengan target menggunakan visualisasi heatmap correlation untuk mengetahui fitur mana yang berguna untuk model nantinya.

      ![image](https://github.com/user-attachments/assets/847e88f0-d665-4392-8d57-39dcf323e724)
      ![image](https://github.com/user-attachments/assets/a90e2696-0114-4341-be6f-1a9df4dd5728)
      ![image](https://github.com/user-attachments/assets/97704200-0be1-43c6-913e-cf8d6edacf71)
      ![image](https://github.com/user-attachments/assets/d16d6ab8-8fff-42f5-8a35-e592dbda5516)
      ![image](https://github.com/user-attachments/assets/9617f1f9-5361-40b3-91ec-c158ae2fd80a)
![image](https://github.com/user-attachments/assets/4e9d4009-3039-45fe-98d5-bb228b445f7e)

Pada Tahapan diketahui bahwa beberapa fitur seperti age dan NCP memiliki outliers, terdapat data duplicate yang perlu ditangani, tidak ada missing value, distribusi target sudah cukup seimbang antara kelasnya. Pada korelasi fitur numerikal tidak ada fitur yang multikolinearitas. **Jadi fokus pembersihan data adalah menghapus data duplikat dan mengurangi outliers saja**. Dilihat dari heatmap korelasi, fitur dengan korelasi positif tertinggi dengan target adalah weight, age, FAVC dan family_history_with_overweight. selain itu beberapa fitur memiliki korelasi positif dan negatif yang kecil dalam rentang -0.35 sampai 0.25.

## Data Preparation
Data preparation atau data preprocessing adalah tahapan penting dalam proses analisis data dan machine learning. Tanpa preprocessing yang baik, data yang kotor, tidak lengkap, atau tidak konsisten dapat menyebabkan hasil analisis yang salah, model yang kurang akurat, dan keputusan yang tidak tepat. Oleh karena itu, tahapan preprocessing diperlukan untuk memastikan data siap dan optimal untuk menghasilkan insight dan model yang berkualitas. Berdasarkan hasil Exploratory Data Analysis tadi terdapat beberapa hal yang harus dilakukan:
1. **Membersihkan data duplikat**, Pada tahapan sebelumnya telah dilakukan pengecekan jumlah data duplikat yang terdeteksi sebanyak 24 baris. Oleh karena itu, dilakukan penghapusan baris data yang terdeteksi sebagai duplikat dengan tetap mempertahankan satu data asli yang valid. Tujuannya adalah untuk menghindari bias dalam pelatihan model, menjaga akurasi evaluasi, serta mengoptimalkan efisiensi komputasi dan kualitas distribusi data.

      ![image](https://github.com/user-attachments/assets/cf2f1334-1fcb-41e6-a144-6aec6ed5befd)
      ![image](https://github.com/user-attachments/assets/b54c93d7-428f-4a50-bcb1-2d00990c4631)

2. **Menangani data outliers**, Pada tahapan sebelumnya, data outliers telah dideteksi menggunakan metode Interquartile Range (IQR) yang bekerja berdasarkan perhitungan nilai-nilai yang berada di luar rentang `[Q1 − 1.5 × IQR, Q3 + 1.5 × IQR]` di mana Q1 dan Q3 adalah kuartil pertama dan ketiga dari distribusi data. Outliers terlihat dominan pada fitur Age dan NCP, namun hal tersebut merepresentasikan variasi alami dari data sehingga penanganannya tidak dapat dilakukan secara langsung melalui penghapusan atau capping. Sebagai solusi maka dilakukan log transform pada fitur **Age** untuk mengurangi skewness dan membatasi dominasi nilai ekstrem sehingga distribusi menjadi lebih seimbang dan model dapat belajar dengan lebih baik. Sementara itu, untuk fitur **NCP**, nilai outlier akan dibiarkan saja karena nilainya merupakan hasil variasi kategorikal alami, korelasinya dengan target sangat rendah dan distribusinya bersifat multimodal sehingga sulit ditangani dengan transformasi sederhana. Selain itu, terdapat satu outlier ekstrem pada fitur **Weight dan Height** yang merupakan nilai maksimum tidak wajar yang akan langsung dihapus agar tidak mempengaruhi nilai statistik keseluruhan seperti rata-rata dan standar deviasi. Adapun transformasi log pada fitur Age menggunakan rumus:

$$
X_{\text{new}} = log(x+1)
$$

3. **Data Splitting**, setelah data dirasa bersih, selanjutnya dilakukan tahapan splitting data dengan membaginya menjadi data training dan testing dengan perbandingan 80:20, serta menggunakan metode stratified sampling untuk memastikan proporsi tiap kelas target tetap seimbang pada kedua subset data. Tujuan dari pemisahan ini adalah untuk menghindari overfitting, menilai performa model secara objektif pada data yang belum pernah dilihat, serta memastikan model mampu melakukan generalisasi dengan baik terhadap data baru.

      ![image](https://github.com/user-attachments/assets/66148db1-4455-46ea-a81a-265c86599a6f)

4. **Data Encoding**, pada data terdapat 9 fitur termasuk target yang bertipe data object (kategorikal), data ini tidak bisa langsung di proses oleh model machine learning sehingga perlu dilakukan encoding yaitu mengubah nilai kategori menjadi nilai numerikal. pada kasus ini dilakukan **label encoding** dengan map untuk fitur yang tidak memiliki urutan seperti Gender, FAVC, SCC, SMOKE dan family_history_with_overweight yang hanya terdiri dari 2 unique kategori, **ordinal encoding** menggunakan map untuk fitur berbasis frekuensi seperti CAEC dan CALC, dan **one-hot encoding** untuk fitur tanpa urutan dengan dengan multikelas seperti MTRANS yang terpecah menjadi MTRANS_Public_Transportation, MTRANS_Automobile, MTRANS_Walking, MTRANS_Motorbike dan MTRANS_Bike. serta **label encoding** dengan map untuk target tingkat obesitas (NObeyesdad). Encoding dilakukan pada data training dan testing yang dihasilkan setelah melalui tahapan data splitting hal ini dilakukan agar mencegah kebocoran data dan memperkuat generalisasi data baru.
   
5. **Data Scaling**, fitur numerikal yang ada dalam dataset masih dalam rentang yang berbeda-beda sehingga perlu dibuat seragam melalui proses scaling, Meskipun model ensemble seperti Random Forest dan Gradient Boosting yang digunakan dalam penelitian ini tidak bergantung pada skala fitur karena tidak menggunakan pendekatan berbasis jarak namun proses scaling tetap dilakukan untuk menjaga konsistensi preprocessing, mempermudah integrasi antar model, serta mencegah dominasi fitur dengan skala besar dalam tahap seleksi atau eksplorasi fitur. Pada penelitian ini menggunakan metode MinMax Scaling, yaitu teknik penskalaan yang mengubah nilai fitur ke dalam rentang 0 hingga 1, teknik ini dipilih karena sederhana, tidak mengubah distribusi asli data secara signifikan, dan cocok untuk menjaga proporsi nilai dalam fitur yang memiliki skala berbeda.. Rumus MinMax Scaling adalah:

$$
X_{\text{scaled}} = \frac{X - X_{\text{min}}}{X_{\text{max}} - X_{\text{min}}}
$$

   dimana :
   - $` X `$ adalah nilai original.
   - $` X_{\text{min}} `$ dan $` X_{\text{max}} `$ adalah nilai minimum dan maksimum dari fitur.

Setelah selesai melakukan semua tahapan ini, data akhirnya siap digunakan untuk melatih model machine learning.

## Modeling
Tahapan ini membahas mengenai model machine learning yang digunakan untuk menyelesaikan permasalahan klasifikasi obesitas berdasarkan data gaya hidup dan kondisi fisik pengguna. Penelitian ini menggunakan dua model ensemble yaitu Random Forest dan Gradient Boosting, untuk membandingkan performa masing-masing dan menentukan model terbaik yang akan digunakan sebagai solusi.

### 1. Inisialiasi Model
Dua model utama yang digunakan dalam eksperimen ini adalah RandomForestClassifier dan GradientBoostingClassifier dari pustaka scikit-learn. Inisialisasi awal dilakukan dengan parameter default sebelum dilakukan optimasi. Berikut ini adalah algoritma model yang digunakan dengan parameter yang diatur secara default serta kelebihan dan kekurangan dari masing-masing algoritma:
1. **Random Forest** adalah algoritma ensemble learning yang digunakan untuk tugas klasifikasi dan regresi. Ia bekerja dengan membangun banyak pohon keputusan (decision trees) selama proses pelatihan, lalu menggabungkan hasil prediksi dari masing-masing pohon untuk menghasilkan output akhir yang lebih akurat dan stabil.
   - Parameter Utama:   
         `n_estimators: 100` (Jumlah pohon dalam hutan)  
         `max_depth: None` (Kedalaman maksimum pohon)  
         `max_features: 'sqrt'` (Jumlah maksimum fitur yang dipertimbangkan saat split)  
         `min_samples_split: 2`  (Minimal jumlah sampel untuk memisahkan node)  
         `min_samples_leaf: 1` (Jumlah minimal sampel di setiap daun)  
         `bootstrap: True` (bootstrap sampling untuk menciptakan keragaman antar pohon)  
   - Kelebihan: Mampu menangani data non-linear dan kompleks, tahan terhadap overfitting, cocok untuk klasifikasi multi-kelas, dan menyediakan informasi pentingnya fitur.
   - Kekurangan: Kurang interpretatif, proses pelatihan lebih lambat, dan membutuhkan tuning parameter agar performa optimal.

2. **Gradient Boosting** adalah algoritma ensemble learning yang membangun model secara bertahap dari banyak pohon keputusan lemah (shallow trees). Setiap pohon baru dilatih untuk memperbaiki kesalahan dari pohon sebelumnya, dengan cara meminimalkan fungsi loss menggunakan pendekatan gradien. Proses ini membuat model menjadi sangat kuat meskipun dimulai dari pohon-pohon yang sederhana.
   - Parameter Utama:  
         `n_estimators: 100` (Jumlah pohon lemah yang akan dibangun secara berurutan)  
         `learning_rate: 0.1` (Seberapa besar kontribusi tiap pohon terhadap model akhir)  
         `max_depth: 3` (Kedalaman maksimum tiap pohon lemah)  
         `subsample: 1.0` (Proporsi sampel yang digunakan untuk melatih tiap pohon)  
         `min_samples_split: 2` (Jumlah minimum sampel untuk membagi node)  
         `min_samples_leaf: 1` (Jumlah minimum sampel pada daun)  
   - Kelebihan: Sangat akurat untuk tugas klasifikasi dan regresi, mampu menangkap hubungan non-linear kompleks, dan fleksibel dalam penggunaan fungsi loss serta 
     menyediakan informasi pentingnya fitur.
   - Kekurangan: Proses pelatihan cenderung lebih lambat dan rentan terhadap overfitting jika tidak dituning dengan baik serta lebih sensitif terhadap outlier dan noise 
     dibanding Random Forest.

### 2. Penentuan Model Terbaik
Berdasarkan hasil pelatihan model terpisah menggunakan data pelatihan (X_train, y_train) yang telah diproses dan di-split sebelumnya yang kemudian dievaluasi menggunakan data uji (X_test, y_test) dengan metrik evaluasi seperti akurasi, precision, recall, dan F1-score serta classification report dan confusion matrix menunjukan model default dari Gradient Boosting memiliki performa paling baik dimana:
1. Performa metrik yang lebih baik dengan akurasi, precision, recall, dan F1 score sebesar 0.97 pada data testing dan 1.0 pada data training, Walaupun menunjukkan adanya sedikit potensi overfitting namun hanya memiliki sedikit kesalahan dalam prediksi (kesalahan tidak jauh antar multi-kelas). dibandingkan dengan model random forest yang hanya sebesar 0.95 pada data testing dan 1.0 pada training dan kesalahan prediksi yang jauh dari kelasnya, model GDB masih lebih unggul
2. Walaupun memiliki waktu pelatihan yang sedikit lebih lama yaitu sekitar 11 detik dibanding Random Forest yang hanya sekitar 1 detik, namun perbedaan ini tidak terlalu berdampak sehigga masalah waktu tidak akan menjadi pertimbangan dalam kasus ini.

Berdasarkan alasan diatas menjadikan model Gradient Boosting sebagai pilihan yang cocok untuk kasus ini. Walaupun model masih mengalami potensi overfitting namun masih bisa diatasi dengan melakukan fine tuning pada model Gradient Boosting yang dipilih untuk membuat model semakin akurat dengan parameter optimal.

### 3. Tahapan Fine Tuning  
Model Gradient Boosting yang menunjukkan performa awal lebih baik kemudian dituning menggunakan RandomizedSearchCV untuk meningkatkan performanya lebih lanjut. Adapun parameter yang akan dituning adalah seperti berikut:

   ![image](https://github.com/user-attachments/assets/0f152f90-8e0a-4625-a4c1-e0599686e1ad)
      
Menggunakan `n_iter = 100` yang akan mencoba 100 kombinasi parameter berbeda secara acak, `cv=5` yang membagi data menjadi 5 bagian dan akan diuji secara bergantian sehingga total fits adalah `5 folds × 100 candidates = 500 fits` yang artinya model dilatih dan diuji sebanyak 500 kali. Metrik akurasi digunanakan sebagai metrik evaluasi untuk memilih model terbaik selama pencarian parameter. **Random Search** dipilih karena memungkinkan pencarian ruang hyperparameter yang lebih luas secara lebih efisien dalam sisi waktu dibandingkan Grid Search karena tidak semua kombinasi diuji, melainkan hanya sebagian acak. Dalam Random Search, parameter-parameter dicoba secara acak dalam ruang parameter yang telah ditentukan, sehingga meskipun jumlah iterasi lebih sedikit, peluang untuk menemukan kombinasi yang optimal tetap tinggi. sehingga dihasilkan parameter optimal yaitu:  
`Best Params: {'learning_rate': np.float64(0.1834840422988522), 'max_depth': 8, 'max_features': None, 'min_samples_leaf': 9, 'min_samples_split': 11, 'n_estimators': 112, 'subsample': np.float64(0.9909204441552655)}`   
kemudian dilakukan training ulang dengan parameter yang sudah didapat dan diperoleh akurasi sebesar 0.98 (meningkat sebesar 0.1 dibanding model default) dan menghasilkan prediksi yang semakin membaik.

### 4. Tahapan Feature Selection
Karena kemungkinan model masih membaca fitur yang tidak terlalu berkaitan yang ditunjukkan dengan potensi overfitting sehingga langkah fine tuning saja tidak cukup maka selanjutnya adalah perlu dilakukan seleksi fitur. Seleksi fitur dilakukan berdasarkan feature importance yang disediakan oleh model Gradient Boosting. Feature importance adalah ukuran yang menunjukkan seberapa penting setiap fitur dalam membuat keputusan yang tepat dalam model. Fitur yang memiliki nilai importance lebih tinggi dianggap lebih penting dan lebih berkontribusi pada kemampuan model dalam melakukan prediksi yang akurat, sedangkan fitur dengan nilai importance rendah dapat diabaikan. Melalui proses ini, fitur-fitur yang tidak relevan atau kurang berpengaruh terhadap hasil model akan dihilangkan, yang membantu dalam mengurangi kompleksitas model, meningkatkan kecepatan pelatihan model, dan meningkatkan interpretabilitas model.
      
   ![image](https://github.com/user-attachments/assets/a5df5f00-33f9-4794-8ea7-5c4b488e4361)

Terlihat hanya 15 fitur yang memiliki importance terhadap model sehingga akan dilakukan pemilihan kepada 15 fitur tersebut dan karena fitur yang tidak memiliki importance masih memiliki alasan logis untuk dihilangkan seperti kendaraan yang tidak memerlukan aktifitas fisik yaitu mobil, public_trans, motor dan sepeda serta fitur smoking yang mungkin kurang relevan terhadap obesity. Selanjutnya dilakukan training ulang menggunakan parameter hasil fine tuning dan fitur yang sudah diseleksi hasilnya cukup baik dimana model dengan fine tuning dan feature selection berdasarkan importance fitur menunjukkan akurasi paling maksimum yaitu sebesar 0.99 meningkat dibanding model fine-tuning saja yang hanya 0.98. Hal ini menunjukan model semakin mengurangi potensi overfitting dan menghasilkan prediksi yang lebih baik.

## Evaluation
Dalam proyek klasifikasi obesitas ini, digunakan beberapa metrik evaluasi untuk mengukur performa model machine learning, yaitu akurasi, precision, recall, dan F1-score. Metrik-metrik ini dipilih karena sesuai dengan tujuan dari proyek, yaitu mengklasifikasikan kategori obesitas dengan tingkat kesalahan yang seminimal mungkin, terutama dalam konteks data multi-kelas.

### Penjelasan Metrik Evaluasi
1. **Accuracy**  
   Akurasi mengukur seberapa banyak prediksi yang benar dari keseluruhan prediksi yang dilakukan, dalam konteks ini, akurasi menunjukkan persentase prediksi yang benar terhadap total prediksi 
   yang dibuat model untuk setiap kelas obesitas. Formula untuk akurasi adalah:

   $$\text{Accuracy} = \frac{TP + TN}{TP + TN + FP + FN}$$

   Di mana TP = True Positive, TN = True Negative, FP = False Positive, dan FN = False Negative.
   Metrik ini cocok digunakan saat distribusi kelas cukup seimbang dan kesalahan di semua kelas memiliki dampak yang sebanding dan jika ingin memperoleh gambaran umum seberapa baik model dalam 
   memprediksi kelas yang benar.

2. **Precision**
   Precision mengukur seberapa banyak prediksi yang benar dari semua prediksi yang diberi label positif oleh model (dalam hal ini adalah kelas obesitas tertentu). Formula untuk precision adalah:

   $$\text{Precision} = \frac{TP}{TP + FP}$$

   Precision yang tinggi menunjukkan bahwa ketika model memprediksi kelas tertentu, kemungkinan besar prediksi tersebut adalah benar. Cocok untuk konteks di mana false positive perlu 
   diminimalkan.

3. **Recall**
   Recall mengukur seberapa banyak kasus positif yang berhasil ditemukan oleh model di antara semua kasus yang seharusnya positif. dalam hal ini menunjukkan seberapa banyak orang yang benar- 
   benar termasuk dalam kategori obesitas tertentu dapat terdeteksi dengan benar oleh model. Formula untuk recall adalah:

   $$\text{Recall} = \frac{TP}{TP + FN}$$

   Recall tinggi berarti model mampu menangkap hampir semua kasus yang benar-benar positif.Cocok untuk konteks di mana false negative perlu diminimalkan.

4. **F1-Score**
   F1-score adalah rata-rata harmonis dari precision dan recall yang memberikan gambaran yang lebih seimbang jika terjadi trade-off antara keduanya. Formula F1-score adalah:

   $$\text{F1 Score} = 2 \times \frac{\text{Precision} \times \text{Recall}}{\text{Precision} + \text{Recall}}$$

   Nilai F1-score yang tinggi berarti model dapat menangkap banyak kasus obesitas (recall) dengan sedikit kesalahan prediksi (precision). F1-Score berguna ketika ada ketidakseimbangan antara 
   precision dan recall dan memerlukan metrik tunggal untuk menilai keseimbangan antara keduanya

### Alat Bantu Visualisasi Metrik
1. **Confusion matrix** adalah alat evaluasi yang sering digunakan dalam klasifikasi untuk memvisualisasikan kinerja model dengan membandingkan prediksi model terhadap nilai sebenarnya (true values). Matrix ini menunjukkan bagaimana model mengklasifikasikan setiap kelas dalam masalah klasifikasi, terutama untuk memahami kesalahan yang terjadi antara kelas-kelas.
2. **Classification report** adalah ringkasan dari berbagai metrik evaluasi yang digunakan untuk menilai performa model dalam masalah klasifikasi mencakup metrik-metrik seperti Precision, Recall, F1-Score, dan Support untuk setiap kelas yang ada dalam dataset. terdapat ringkasan macro average yang merupakan rata-rata metrik (precision, recall, dan F1) untuk semua kelas tanpa memperhitungkan ketidakseimbangan jumlah sampel antar kelas dan weighted average yang merupakan rata-rata metrik dengan mempertimbangkan jumlah sampel untuk setiap kelas, sehingga kelas yang lebih besar memiliki pengaruh lebih besar terhadap hasil rata-rata.

### Hasil Evaluasi Proyek
Evaluasi dilakukan terhadap dua model, yaitu Random Forest dan Gradient Boosting, baik pada parameter default maupun setelah dilakukan hyperparameter tuning dan feature selection.
1. Evaluasi Model Default

   ![image](https://github.com/user-attachments/assets/7ab3db43-2327-450f-855f-8f3a094f0587)
   ![image](https://github.com/user-attachments/assets/0da61381-21f0-426f-9e3e-13657b538124)
   ![image](https://github.com/user-attachments/assets/e696ad5c-2429-4e69-b833-16f8432144cf)
   ![image](https://github.com/user-attachments/assets/c526127e-8ed2-42c8-b4b1-0b0377e12233)

   Evaluasi awal pada model Random Forest dan Gradient Boosting menunjukkan performa sempurna pada data training (nilai 1.0 di semua metrik), namun menunjukkan potensi overfitting. Pada data 
   testing, Random Forest memperoleh skor 0.95, sedangkan Gradient Boosting mencatat skor lebih tinggi yaitu 0.97 di semua metrik. Hasil ini menunjukkan bahwa Gradient Boosting lebih stabil 
   dan generalizable dibandingkan Random Forest. Pada classification report juga akurasi, presisi, recall dan F1-score setiap kelas pada model Gradient Boosting lebih tinggi sehingga secara 
   keseluruhan, model Gradient Boosting menunjukkan kinerja yang lebih baik dibandingkan Random Forest dalam semua aspek evaluasi, menjadikannya kandidat yang lebih potensial untuk ditingkatkan 
   lebih lanjut melalui proses hyperparamter tuning.
   
2. Evaluasi Setelah Fine Tuning

   ![image](https://github.com/user-attachments/assets/9652977d-1588-46b3-8c4d-4c8cc2efe4b1)
   ![image](https://github.com/user-attachments/assets/bb13d446-09ca-457f-a3a1-fc76be376902)
   ![image](https://github.com/user-attachments/assets/6a20b25b-bbce-4e99-9f77-6628f7f2fe3a)

   Evaluasi Gradient Boosting setelah fine tuning juga menunjukkan semua metrik pada data training dengan nilai 1.0 namun hasil testingnya meningkat menjadi 0.98 dari model dengan parameter 
   default. Pada Classification Reports juga nilai akurasi, presisi, recall, dan F1-score tiap kelas semakin baik dan prediksi salahnya semakin berkurang.

3. Evaluasi Setelah Feature Selection

   ![image](https://github.com/user-attachments/assets/5eb19e06-7628-473a-a012-29095f4d8269)
   ![image](https://github.com/user-attachments/assets/24363e9c-0bc8-420e-89a6-6f414f2fede2)

   Setelah dilakukan fine tuning, dilakukan juga feature selection dan dapat dilihat pada classification report terdapat peningkatan semua metrik menjadi 0.99 yang semakin meminimalkan 
   overfitting. selain itu tiap kelas juga semakin baik performa tiap kelasnya.

## Kesimpulan
Berdasarkan evaluasi yang dilakukan terhadap dua model, Random Forest dan Gradient Boosting, dapat disimpulkan bahwa Gradient Boosting merupakan model dengan performa terbaik untuk menyelesaikan permasalahan klasifikasi obesitas berbasis data gaya hidup dan kondisi fisik. Meskipun kedua model menunjukkan hasil sempurna pada data pelatihan, Gradient Boosting secara konsisten menghasilkan metrik evaluasi yang lebih tinggi dan stabil pada data pengujian, baik dalam kondisi default maupun setelah dilakukan peningkatan melalui fine tuning dan feature selection. Proses hyperparameter tuning pada Gradient Boosting berhasil meningkatkan akurasi dari 0.97 menjadi 0.98, serta meningkatkan nilai precision, recall, dan F1-score pada masing-masing kelas. Peningkatan selanjutnya melalui feature selection menghasilkan akurasi sebesar 0.99 dan kinerja model yang lebih efisien serta minim overfitting. Secara keseluruhan, proses evaluasi menunjukkan bahwa dengan pendekatan bertahap dan komprehensif, performa model dapat ditingkatkan secara signifikan dan menghasilkan prediksi yang lebih akurat serta dapat diandalkan.

