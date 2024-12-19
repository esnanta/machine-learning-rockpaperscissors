# Klasifikasi Gambar Rock-Paper-Scissors

Proyek ini merupakan bagian dari pembelajaran Machine Learning Pemula yang bertujuan untuk membuat model klasifikasi gambar Rock-Paper-Scissors menggunakan TensorFlow dan Google Colaboratory. Berikut adalah detail spesifikasi dan langkah-langkah pengerjaan proyek.

## Spesifikasi Proyek

1. **Dataset:**
   - Dataset yang digunakan adalah "rockpaperscissors".
   - Dataset dapat diunduh menggunakan perintah `wget` dari link berikut:
     ```bash
     wget https://github.com/dicodingacademy/assets/releases/download/release/rockpaperscissors.zip
     ```

2. **Pembagian Dataset:**
   - Dataset dibagi menjadi **train set** dan **validation set**.
   - Ukuran validation set adalah 40% dari total dataset.
     - Data training: 1314 sampel.
     - Data validasi: 874 sampel.

3. **Implementasi Augmentasi Gambar:**
   - Menggunakan teknik augmentasi gambar untuk meningkatkan performa model.
   - Implementasi augmentasi dilakukan dengan **Image Data Generator** dari TensorFlow/Keras.

4. **Model:**
   - Model yang digunakan adalah model Sequential dari TensorFlow/Keras.
   - Model dilatih tidak lebih dari 30 menit pada Google Colaboratory.
   - Akurasi model minimal 85%.

## Persiapan Lingkungan Kerja

1. **Google Colaboratory:**
   - Pastikan program dijalankan di Google Colaboratory untuk memanfaatkan GPU.

2. **Pustaka yang Dibutuhkan:**
   - TensorFlow
   - Matplotlib
   - Numpy

## Langkah-Langkah Pengerjaan

1. **Unduh dan Ekstrak Dataset:**
   ```python
   !wget https://github.com/dicodingacademy/assets/releases/download/release/rockpaperscissors.zip
   !unzip rockpaperscissors.zip
   ```

2. **Pembagian Dataset:**
   - Gunakan TensorFlow atau library lainnya untuk membagi dataset menjadi train set dan validation set.

3. **Augmentasi Gambar:**
   - Terapkan augmentasi seperti rotasi, flipping, zoom, dll., menggunakan `ImageDataGenerator`.

4. **Pembuatan Model:**
   - Gunakan arsitektur model Sequential dengan beberapa lapisan, seperti:
     - Convolutional Layer
     - MaxPooling Layer
     - Dense Layer

5. **Pelatihan Model:**
   - Latih model menggunakan dataset yang sudah diproses.
   - Pastikan waktu pelatihan tidak melebihi 30 menit.

6. **Evaluasi Model:**
   - Pastikan akurasi model minimal 85% pada data validasi.

## Hasil Akhir
- Model yang mampu mengklasifikasikan gambar Rock-Paper-Scissors dengan akurasi minimal 85%.
- Program yang telah dijalankan dan divalidasi pada Google Colaboratory.

## Lisensi
Proyek ini dibuat untuk tujuan pembelajaran dan merupakan bagian dari modul pembelajaran Machine Learning Pemula dari Dicoding Academy.
