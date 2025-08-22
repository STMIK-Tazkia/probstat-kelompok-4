*Prediksi Kinerja Akademik Mahasiswa
Perbandingan Logistic Regression (SGD) dan Random Forest*

Proyek ini bertujuan untuk membangun model machine learning untuk memprediksi kinerja akademik mahasiswa menggunakan dataset Student Performance Prediction dari Kaggle. Dua algoritma yang dibandingkan adalah Logistic Regression dengan optimisasi Stochastic Gradient Descent (SGD) dan Random Forest.

Struktur Proyek

-PaperJournal/ – Naskah akhir proyek (format .docx dan .pdf)

-Proposal/ – Dokumen proposal awal penelitian dan perencanaan model

-SourceCode/ – Notebook Jupyter berisi preprocessing, modeling, evaluasi, dan visualisasi

-Dataset/ – Dataset Student Performance Prediction (format .csv/.xlsx)

README.md – Dokumentasi lengkap proyek

Deskripsi Dataset
-Sumber: Kaggle – Student Performance Prediction Dataset

-Jumlah sampel: 145 mahasiswa

-Jumlah fitur: 14 atribut prediktor

-Target: Grade nilai akhir (AA, BA, BB, CB, CC, DC, DD, FD, FF)

Contoh fitur:
-Study hours (lama belajar)

-Attendance (tingkat kehadiran)

-Class participation (partisipasi kelas)

-Exam performance (hasil ujian)

Metodologi
1. Preprocessing

Data cleaning (menangani missing values)
Encoding variabel kategorikal (label encoding / one-hot encoding)
Normalisasi fitur numerik (StandardScaler)
Split data (80% training, 20% testing)

2. Modeling

Algoritma: Logistic Regression (SGD), Random Forest
Tools: Python, scikit-learn, pandas, numpy
Evaluasi: Akurasi, Precision, Recall, F1-score, ROC-AUC

3. Visualisasi

Heatmap korelasi antar fitur
Confusion Matrix
ROC Curve & AUC
Feature Importance

Tujuan Proyek

-Membandingkan efektivitas Logistic Regression (SGD) dan Random Forest

-Menganalisis trade-off antara efisiensi komputasi (Logistic Regression) dan akurasi/stabilitas prediksi (Random Forest)

-Memberikan gambaran pemanfaatan machine learning dalam mendukung sistem prediksi kinerja akademik mahasiswa

Penulis

Shanaya Balghis Riyona (241552010012)
Shifi Amalia Zein (241552010013)

Institusi

STMIK Tazkia – Program Studi Teknik Informatika
Mata Kuliah Statistik dan Probabilitas – Semester II – Tahun Akademik 2024/2025
Dosen Pengampu: Bapak Hendri Setiawan, S.Kom., M.T.

Lisensi Dataset
Dataset tersedia secara publik di Kaggle dengan lisensi Creative Commons CC BY 4.0


