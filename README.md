# Sentimen Analysis with LDA Model

Proyek ini merupakan implementasi analisis sentimen menggunakan **Linear Discriminant Analysis (LDA)**. Notebook ini mengeksplorasi data ulasan (review) untuk mengklasifikasikan sentimen menjadi kategori positif dan negatif, serta melalui tahapan preprocessing, ekstraksi fitur, dan klasifikasi.

## 🔍 Tujuan Proyek

- Menerapkan model **Linear Discriminant Analysis (LDA)** untuk analisis sentimen.
- Melakukan preprocessing teks (cleansing, tokenizing, stopword removal, stemming).
- Mengevaluasi performa model klasifikasi berdasarkan metrik akurasi, precision, recall, dan F1-score.

## 🧰 Teknologi dan Tools

- Python
- Jupyter Notebook
- Scikit-learn
- Pandas
- Numpy
- Sastrawi (untuk stemming Bahasa Indonesia)
- Matplotlib, Seaborn (visualisasi)

## 🗃️ Dataset

Dataset yang digunakan merupakan kumpulan ulasan dalam Bahasa Indonesia. Dataset dibagi menjadi dua label utama:
- **Positif**
- **Negatif**

> *Catatan: Dataset ini dapat berupa file CSV yang berisi dua kolom utama, yaitu `text` (isi ulasan) dan `label` (sentimen).*

## 🔄 Alur Proses

1. **Import Library**
2. **Load Dataset**
3. **Preprocessing Text**
   - Case folding
   - Cleansing (menghapus tanda baca, angka, dan simbol)
   - Tokenizing
   - Stopword removal
   - Stemming (menggunakan Sastrawi)
4. **Ekstraksi Fitur**
   - Menggunakan TF-IDF Vectorizer
5. **Pembagian Data**
   - Training dan testing split
6. **Modeling**
   - Penerapan Linear Discriminant Analysis (LDA)
7. **Evaluasi Model**
   - Akurasi, confusion matrix, classification report

## 📊 Hasil

Model LDA menunjukkan performa klasifikasi sentimen yang cukup baik terhadap dataset ulasan. Hasil evaluasi menggunakan confusion matrix dan classification report ditampilkan untuk mengukur kualitas prediksi.

## 📁 Struktur File

