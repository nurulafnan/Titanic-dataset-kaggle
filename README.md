# Titanik-Dataset
Tujuan :
Membangun model prediksi berdasarkan fitur tertentu dengan memanfaatkan teknik Data Science dan Machine Learning untuk memperkirakan peluang seorang penumpang bertahan dari tragedi Titanic.

Dataset di ambil dai kaggle memiliki 12 kolom yang masing-masing diberi nama sebagai header. Header kolom ini berfungsi sebagai label untuk setiap jenis data yang terdapat dalam kolom tersebut.

PassengerId: Nomor unik yang diberikan kepada setiap penumpang. Survived: Menunjukkan apakah penumpang tersebut selamat (1) atau tidak (0) dalam suatu peristiwa, kemungkinan besar tenggelamnya kapal Titanic. Pclass: Kelas tiket yang dibeli oleh penumpang. Name: Nama lengkap penumpang. Sex: Jenis kelamin penumpang (male/female). Age: Usia penumpang. SibSp: Jumlah saudara dan pasangan yang ikut dalam perjalanan. Parch: Jumlah orang tua dan anak yang ikut dalam perjalanan. Ticket: Nomor tiket penumpang. Fare: Harga tiket yang dibayarkan. Cabin: Nomor kabin penumpang. Embarked: Pelabuhan keberangkatan.

Contoh Penggunaan
Langkah Pemrosesan Data: Pembacaan Data: File CSV dibaca menggunakan read_csv. Pembagian Data: Data dipisahkan menjadi training dan testing set menggunakan train_test_split. Mungkin ada penanganan data kosong seperti dropna atau fillna, meski belum disebut secara eksplisit.
Model yang Dilatih: Logistic Regression Random Forest Classifier dengan 100 estimators dan kriteria "Gini". K-Nearest Neigbors. XGBoost dengan 500 estimators.
Evaluasi dan Metode Scoring: Evaluasi setiap model menggunakan: Akurasi (accuracy_score) Confusion Matrix Classification Report (precision, recall, F1-score) Hasil visualisasi Confusion Matrix menggunakan heatmap dari Seaborn. Dibuat perbandingan akurasi model menggunakan bar chart, yang menunjukkan perbedaan performa antar model.
Hasil yang Ditampilkan: Masing-masing model memberikan nilai score baik untuk training maupun testing set. Akurasi tiap model ditampilkan untuk mengetahui mana yang paling unggul. Ada upaya membandingkan beberapa algoritma (Logistic Regression, Random Forest) dalam hal akurasi.
