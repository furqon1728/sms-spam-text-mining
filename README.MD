# SMS Filtering dengan NLP dan Text Mining

Proyek ini bertujuan untuk mengimplementasikan teknik **Natural Language Processing (NLP)** dan **Text Mining** dalam mengklasifikasikan pesan SMS, terutama untuk memfilter pesan spam. Proses ini melibatkan tahapan seperti preprocessing, ekstraksi fitur, seleksi fitur, hingga klasifikasi menggunakan algoritma machine learning.

## Fitur Utama
- **Preprocessing Data**:
  - Tokenisasi
  - Case folding (mengubah teks menjadi huruf kecil)
  - Stemming (mengubah kata ke bentuk dasar)
  - Filtering (menghapus stopword)
- **Ekstraksi Fitur**: Menggunakan TF-IDF (Term Frequency-Inverse Document Frequency) untuk merepresentasikan teks secara numerik.
- **Seleksi Fitur**: Menggunakan metode Chi-Square untuk memilih fitur paling relevan.
- **Klasifikasi**: Menggunakan algoritma machine learning untuk mengklasifikasikan pesan sebagai spam atau bukan spam.

## Alur Kerja
1. Memuat dan memproses dataset dari sumber publik atau API.
2. Melakukan ekstraksi fitur dari data teks menggunakan teknik NLP.
3. Melakukan seleksi fitur untuk meningkatkan performa klasifikasi.
4. Melatih dan memvalidasi model klasifikasi menggunakan metrik seperti akurasi, presisi, recall, dan F1-score.
5. Mengevaluasi dan menerapkan model akhir untuk digunakan dalam produksi.
