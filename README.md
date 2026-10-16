# Visualisasi Data Sleep Health

Di repo ini saya membuat visualisasi data dari dataset kebiasaan tidur dan gaya hidup, memakai Python dan Matplotlib. Datanya adalah hasil data cleansing dari tugas sebelumnya, jadi sudah rapi dan siap dipakai untuk dibuat grafik.

Langkah-langkahnya saya ikuti dari materi Data Visualization di kelas. Mulai dari membuat line chart dasar, lalu belajar mengatur ukuran grafik, judul, label sumbu, warna garis, grid, sampai menambahkan teks penjelasan langsung di grafik. Setelah itu saya lanjut ke bar chart, histogram, dan subplot.

## Isi Repository

- `2418064DataVisualization.ipynb`: notebook tempat semua visualisasi dibuat (dijalankan di Google Colab)
- `sleep_health_data_bersih_2.csv`: dataset yang divisualisasikan, berisi 200 responden dan 20 kolom

## Tentang Datanya

Ada 200 responden dengan 20 kolom. 13 kolom adalah data asli (usia, gender, durasi tidur, skor kualitas tidur, skor stres, dan lain-lain), sedangkan 7 kolom lainnya hasil pengelompokan dari kolom asli, misalnya kelompok usia, kategori durasi tidur, dan total tidur sehari (tidur malam ditambah tidur siang).

## Grafik yang Dibuat

1. Line chart: rata-rata lama tidur siang di tiap kelompok usia
2. Bar chart: jumlah responden di tiap kategori durasi tidur
3. Histogram: sebaran durasi tidur
4. Bar chart: rata-rata kualitas tidur berdasarkan rentang durasi tidur
5. Bar chart: rata-rata kualitas tidur berdasarkan rentang skor stres
6. Bar chart: rata-rata kualitas tidur berdasarkan tingkat stres
7. Subplot: pengaruh kafein, alkohol, dan olahraga terhadap kualitas tidur
8. Subplot: kategori kualitas tidur, perbandingan gender, dan total tidur sehari

## Apa yang Saya Temukan

- Makin tua usia responden, makin lama mereka tidur siang. Kelompok usia 50 tahun ke atas rata-rata tidur siang sekitar 24 menit, dua kali lebih lama dari kelompok usia 24 tahun ke bawah (sekitar 12 menit).
- Sekitar 34% responden tidur kurang dari 6 jam. Rata-rata durasi tidur semua responden 6,52 jam, sedikit di bawah anjuran 7 jam.
- Makin lama tidur, kualitas tidurnya cenderung makin bagus.
- Stres paling terlihat pengaruhnya. Responden dengan stres rendah punya rata-rata skor kualitas tidur 6,66, sedangkan yang stresnya tinggi hanya 3,46.
- Kafein, alkohol, dan olahraga ternyata pengaruhnya kecil terhadap kualitas tidur di data ini.

## Cara Menjalankan

1. Upload `sleep_health_data_bersih_2.csv` ke Google Drive, ke folder `DATMIN` di dalam `Colab Notebooks`.
2. Buka `2418064DataVisualization.ipynb` di Google Colab.
3. Kalau lokasi file di Drive kamu berbeda, ubah alamat file di bagian Load Dataset.
4. Jalankan semua sel dari atas ke bawah (Runtime lalu Run all).

## Tools

Python, pandas, Matplotlib, Google Colab

## Penulis

Maya Via Agustin Rahayu (NIM 2418064)
Teknik Informatika, Institut Teknologi Nasional Malang
