# Rice Image Classification

Proyek ini merupakan implementasi klasifikasi gambar untuk mendeteksi jenis beras menggunakan model deep learning. Dataset yang digunakan terdiri dari gambar-gambar berbagai jenis beras, dan model dibangun dengan menggunakan TensorFlow dan Keras.

## Informasi Pengembang

- **Nama:** Afifa Nur Mila  
- **Email:** mc200d5x2075@student.devacademy.id  
- **ID Dicoding:** MC200D5x2075  

## Deskripsi Proyek

Proyek ini bertujuan untuk mengklasifikasikan gambar beras ke dalam beberapa kategori menggunakan Convolutional Neural Network (CNN). Model dilatih menggunakan dataset yang telah disediakan dan dievaluasi kinerjanya menggunakan metrik akurasi.

## Struktur Proyek

1. **Import Library**  
   Mengimpor semua library penting seperti TensorFlow, NumPy, Matplotlib, dsb.

2. **Persiapan Data**  
   - Mengunduh dan mengekstrak dataset.
   - Menggunakan `ImageDataGenerator` untuk augmentasi data.
   - Membagi data ke dalam folder `train`, `validation`, dan `test`.

3. **Pembangunan Model**  
   - Menggunakan arsitektur CNN sederhana.
   - Menambahkan layer Convolutional, MaxPooling, dan Dense.
   - Menggunakan fungsi aktivasi `relu` dan `softmax`.

4. **Training Model**  
   - Menggunakan callback `ModelCheckpoint`.
   - Evaluasi model menggunakan data validasi.

5. **Evaluasi Model**  
   - Visualisasi hasil akurasi dan loss.
   - Evaluasi menggunakan data uji.

6. **Prediksi Gambar Baru**  
   - Memuat gambar eksternal dan melakukan prediksi.

## Cara Menjalankan

1. Pastikan Anda memiliki Python dan Jupyter Notebook/Colab.
2. Jalankan seluruh sel dari atas ke bawah.
3. Dataset akan diunduh dan model akan dilatih secara otomatis.

## Dependencies

- TensorFlow
- NumPy
- Matplotlib
- OS
- PIL (Python Imaging Library)

## Hasil

Model mencapai akurasi validasi yang baik dan mampu mengklasifikasikan gambar beras baru dengan cukup akurat.
