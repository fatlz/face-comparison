# Aplikasi Perbandingan Wajah AI

Aplikasi web berbasis browser untuk menganalisis tingkat kemiripan antara dua foto wajah menggunakan teknologi Machine Learning.

## ⚠️ Penafian Penting
Aplikasi ini ditujukan **hanya untuk tujuan edukasi, eksperimen, dan hiburan**.
* **Batasan Akurasi:** Model saat ini mungkin menunjukkan ketidakkonsistenan. Dalam beberapa kasus, orang yang sama dinilai memiliki kemiripan rendah, sementara orang yang berbeda bisa menunjukkan hasil yang tidak terduga.
* **Faktor Penentu:** Akurasi sangat dipengaruhi oleh kualitas gambar, pencahayaan, sudut wajah, dan ekspresi. Aplikasi ini **tidak** ditujukan untuk verifikasi identitas resmi atau tujuan keamanan.

## 🚀 Fitur Utama
* **Analisis Mendalam:** Mendeteksi usia, jenis kelamin, dan ekspresi wajah.
* **Metrik Matematis:** Menggunakan *Euclidean Distance* dan *Cosine Similarity* untuk menghitung skor kemiripan.
* **UI Modern:** Menggunakan desain *glassmorphism* untuk tampilan yang estetis.
* **Pemrosesan Lokal:** Analisis dilakukan langsung di dalam browser pengguna.

## 🛠 Teknologi yang Digunakan
* **Frontend:** HTML5, CSS3, Vanilla JavaScript.
* **AI Library:** [face-api.js](https://github.com/justadudewhohacks/face-api.js) (berbasis TensorFlow.js).

## 📋 Cara Menjalankan
1. Simpan kode ke dalam file bernama `index.html`.
2. Buka file tersebut menggunakan browser web modern (Chrome, Firefox, Edge).
3. Pastikan perangkat terhubung ke internet saat pertama kali dibuka, karena aplikasi akan mengunduh model AI (sekitar 5-10MB).

## 💡 Tips & Troubleshooting
* **Gagal Memuat Model:** Jika aplikasi berhenti di status "Loading", silakan segarkan (refresh) halaman.
* **Deteksi Wajah:** Gunakan foto yang jelas, menghadap ke depan, dan pencahayaan yang cukup agar hasil lebih akurat. Hindari penggunaan filter pada foto.