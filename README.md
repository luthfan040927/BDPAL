# Dataset 
Dataset “Breast Cancer” ini merupakan kumpulan data yang digunakan untuk mendeteksi dan mengklasifikasi kanker payudara berdasarkan gambar mammografi. Dataset ini pertama kali di publikasi pada 25 Juni 2023 dan telah mengalami pembaruan terakhir pada 11 Juli 2024.

Sumber Data : Data ini dikumpulkan dari berbagai rumah sakit dan pusat medis, kemudian di proses dan dianalisis oleh tim peneliti dari JSS Science and Technology University.

Deskripsi Kolom : Dataset ini terdiri dari beberapa fitur yang diekstraksi dari gambar mammografi, antara lain : 
ID Number : Identifikasi unik untuk setiap pasien.
Diagnosis : Diagnosis jaringan payudara, dimana `M` menunjukkan malignan (ganas) dan `B` menunjukkan benign (jinak).
Radius Mean: Rata-rata jarak dari pusat ke titik pada perimeter.
Texture Mean: Standar deviasi nilai skala abu-abu.
Perimeter Mean: Rata-rata ukuran inti tumor.
Area Mean: Luas tumor.
Smoothness Mean: Ukuran variasi lokal dalam panjang radius.
Compactness Mean: Perimeter² / area - 1.0.
Concavity Mean: Keparahan bagian cekung dari kontur.
Concave Points Mean: Jumlah bagian cekung dari kontur.
Symmetry Mean: Simetri tumor.
Fractal Dimension Mean: Ukuran "pendekatan garis pantai".

Informasi Umum : 
Jumlah Instance (Data Sampel) : 569
Jumlah Atribut 32 (terdiri dari 1 kolom ID, 1 kolom diagnosis, dan 30 atribut bernilai kontinu).
Diagnosis : 
M : Malignant (ganas)
B : Benign (jinak)
Distribusi kelas : 
357 kasus jinak
212 kasus ganas

Kelengkapan Data : Tidak ada nilai yang hilang (missing values) dalam dataset ini.

Tujuan : Dataset ini sering digunakan dalam penelitian pengembangan algoritma machine learning untuk memprediksi diagnosis kanker payudara. Model yang dibangun dapat membantu mendeteksi kanker secara dini dan mendukung pengambilan keputusan medis.
