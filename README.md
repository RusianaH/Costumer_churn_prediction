# Customer Churn Prediction

## Deskripsi Proyek

Proyek ini bertujuan untuk memprediksi apakah pelanggan dari layanan telekomunikasi akan berhenti berlangganan (churn) atau tidak berdasarkan data historis pelanggan. Dengan menggunakan teknik machine learning, proyek ini mencoba untuk mengidentifikasi pelanggan yang berisiko churn sehingga perusahaan dapat mengambil tindakan preventif.

## Data

Dataset yang digunakan dalam proyek ini memiliki kolom-kolom berikut:

1. **state**: Nama negara bagian tempat pelanggan berada.
2. **account_length**: Jumlah hari sejak pelanggan menjadi pelanggan.
3. **area_code**: Kode area telepon pelanggan.
4. **international_plan**: Menunjukkan apakah pelanggan memiliki paket internasional atau tidak.
5. **voice_mail_plan**: Menunjukkan apakah pelanggan memiliki paket voicemail atau tidak.
6. **number_vmail_messages**: Jumlah pesan voicemail yang diterima oleh pelanggan.
7. **total_day_minutes**: Total menit panggilan di siang hari.
8. **total_day_calls**: Total panggilan yang dilakukan di siang hari.
9. **total_day_charge**: Total biaya panggilan di siang hari.
10. **total_eve_minutes**: Total menit panggilan di malam hari.
11. **total_eve_calls**: Total panggilan yang dilakukan di malam hari.
12. **total_eve_charge**: Total biaya panggilan di malam hari.
13. **total_night_minutes**: Total menit panggilan di malam hari.
14. **total_night_calls**: Total panggilan yang dilakukan di malam hari.
15. **total_night_charge**: Total biaya panggilan di malam hari.
16. **total_intl_minutes**: Total menit panggilan internasional.
17. **total_intl_calls**: Total panggilan internasional yang dilakukan.
18. **total_intl_charge**: Total biaya panggilan internasional.
19. **number_customer_service_calls**: Jumlah panggilan layanan pelanggan yang dilakukan oleh pelanggan.
20. **churn**: Menunjukkan apakah pelanggan berhenti berlangganan (churn) dari layanan atau tidak (target yang akan diprediksi).

## Langkah-langkah Proyek

### 1. Membagi Data Menjadi Training, Validation, dan Test Sets
Data dibagi menjadi tiga set untuk melatih, memvalidasi, dan menguji model. Pembagian ini memastikan bahwa model diuji pada data yang tidak terlihat sebelumnya dan memberikan evaluasi yang adil terhadap kinerja model.

### 2. Membersihkan Data dan Menangani Missing Values
Data diperiksa untuk nilai yang hilang dan anomali lainnya. Teknik-teknik seperti imputasi atau penghapusan nilai yang hilang digunakan untuk memastikan kualitas data.

### 3. Menganalisis Data dan Memilih Fitur yang Relevan
Analisis data dilakukan untuk memahami distribusi data, korelasi antar fitur, dan untuk memilih fitur-fitur yang relevan yang akan digunakan dalam pembuatan model.

### 4. Membangun Model Klasifikasi dan Melatihnya pada Training Set
Model klasifikasi, seperti Logistic Regression, Decision Tree, atau Random Forest, dibangun dan dilatih menggunakan training set. Model ini digunakan untuk memprediksi apakah pelanggan akan churn atau tidak.

### 5. Mengevaluasi Kinerja Model pada Validation dan Test Sets
Model dievaluasi menggunakan validation dan test sets untuk memastikan kinerja yang baik. Metrik-metrik seperti accuracy, precision, recall, dan F1-score digunakan untuk mengevaluasi kinerja model.

### 6. Refining Model dan Mengujinya pada Data Dunia Nyata
Model yang telah dilatih dan dievaluasi kemudian di-refine untuk meningkatkan kinerja. Setelah itu, model diuji pada data dunia nyata untuk memastikan kemampuannya dalam memprediksi churn.

## Hasil

Hasil dari analisis ini mencakup insight tentang faktor-faktor yang mempengaruhi churn pelanggan serta model prediksi yang dapat digunakan untuk menentukan apakah seorang pelanggan akan churn atau tidak.
