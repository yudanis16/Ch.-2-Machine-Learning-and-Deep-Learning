02_Kelompok_G_1.ipynb:
Notebook ini melakukan klasifikasi data pelanggan bank untuk memprediksi apakah pelanggan akan berhenti menggunakan layanan bank (churn) atau tidak. Proses utama meliputi:
1. Impor dan Pembersihan Data: Data diambil dari sumber eksternal, dan preprocessing dilakukan menggunakan pandas dan numpy.
2. Eksplorasi Data: Melihat struktur data untuk memahami fitur-fitur penting.
3. Feature Engineering: Melakukan scaling pada data untuk mempersiapkannya sebelum pemodelan.
4. Pelatihan dan Evaluasi Model: Menggunakan beberapa model klasifikasi (seperti decision tree atau random forest) untuk memprediksi churn. Parameter terbaik dicari dengan GridSearchCV.
5. Visualisasi Hasil: Hasil evaluasi seperti akurasi dan matriks kebingungan ditampilkan untuk mengukur performa model.
Notebook ini bertujuan untuk menentukan model klasifikasi terbaik yang dapat memprediksi churn dengan akurat.

02-Kelompok G-2.ipynb:
Notebook ini melakukan segmentasi data menggunakan KMeans Clustering pada dataset koordinat (x, y). Tahapan utama meliputi:
1. Impor dan Pembersihan Data: Mengambil dataset dan menghapus kolom yang tidak relevan.
2. Pemodelan Clustering: Menerapkan KMeans untuk membagi data menjadi beberapa cluster berdasarkan kesamaan posisi.
3. Visualisasi Cluster: Menampilkan hasil clustering dalam bentuk scatter plot, sehingga distribusi tiap kelompok dapat dilihat.
Notebook ini bertujuan untuk mengidentifikasi pola dalam data melalui pengelompokan koordinat secara visual.

02-Kelompok G-3.ipynb:
Notebook ini menggunakan Deep Learning dengan model Multilayer Perceptron (MLP) untuk memprediksi harga rumah di California. Proses utama meliputi:
1. Persiapan Data: Memuat dan menampilkan data California Housing, lalu menormalkan fitur-fitur.
2. Pembangunan Model: Menggunakan TensorFlow-Keras untuk membuat model MLP dengan beberapa lapisan tersembunyi.
3. Pelatihan dan Evaluasi: Melatih model dengan data pelatihan dan mengevaluasi kinerjanya dengan data pengujian, termasuk menampilkan grafik loss untuk memantau performa.
Tujuan notebook ini adalah untuk memprediksi harga rumah berdasarkan fitur demografis dan geografis menggunakan model regresi berbasis MLP.


