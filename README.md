# CNN Image Classification - Dataset Caltech 101

Proyek ini merupakan implementasi model Convolutional Neural Network (CNN) untuk klasifikasi citra menggunakan TensorFlow dan Keras. Dataset yang digunakan terdiri dari lebih dari 1000 gambar yang telah dibagi menjadi **training**, **validation**, dan **testing set**.

## 🔍 Deskripsi Proyek

Model CNN dibangun untuk mengklasifikasikan gambar ke dalam beberapa kelas menggunakan arsitektur sederhana berbasis `Sequential`, dengan lapisan `Conv2D`, `MaxPooling2D`, `Flatten`, dan `Dense`.

Target proyek:
- Akurasi minimal **92%** pada data pelatihan dan pengujian.
- Visualisasi akurasi dan loss selama proses pelatihan.
- Menyimpan model ke dalam tiga format:
  - **SavedModel (TensorFlow Standard)**
  - **TF-Lite** (untuk mobile)
  - **TensorFlow.js (TFJS)** (untuk web)

## 🗂️ Struktur Direktori
submission/ ├───tfjs_model/ # Model dalam format TensorFlow.js │ ├───group1-shard1of1.bin │ └───model.json ├───tflite/ # Model dalam format TensorFlow Lite │ ├───model.tflite │ └───label.txt # Label kelas ├───saved_model/ # Model disimpan dalam format SavedModel │ ├───saved_model.pb │ └───variables/ ├───notebook.ipynb # Notebook utama proyek ├───README.md # Dokumentasi proyek └───requirements.txt # Daftar dependensi Python

