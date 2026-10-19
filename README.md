# Prediksi Risiko Diabetes dengan K-Nearest Neighbors (KNN)

Program web sederhana untuk mengklasifikasikan pasien baru sebagai **Risiko Rendah (0)** atau **Risiko Tinggi (1)** menggunakan algoritma KNN.

## Atribut
Usia, BMI, Glukosa, Tekanan Darah, Riwayat Keluarga

## Fitur
- Dataset 10 pasien (P01–P10)
- Input data pasien baru dan nilai K
- Opsi normalisasi Min-Max
- Tabel jarak Euclidean dan K tetangga terdekat
- Hasil prediksi berdasarkan suara mayoritas

## Cara Menjalankan
1. Unduh atau clone repositori ini.
2. Buka file `knn_diabetes.html` di browser (klik dua kali), atau di VS Code gunakan ekstensi **Live Server**.

Tidak membutuhkan instalasi apa pun.

## Hasil Studi Kasus
Pasien baru (42, 28.5, 130, 128, 1) dengan K = 3: tetangga terdekat P04, P05, P10 (semua Tinggi), sehingga diprediksi **Risiko Tinggi**.
