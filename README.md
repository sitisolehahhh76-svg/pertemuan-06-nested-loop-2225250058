## Pertemuan 06 Nested Loop Python

Nama: Siti Solehah
NIM: 2225250058
Kelas: 3B

## Tujuan

Menggunakan nested loop, pola, akumulasi, dan pencacahan.

## Cara Menjalankan

python3 tugas/tabel_perkalian_dan_statistik.py

## Algoritma Tugas 3

Loop luar digunakan untuk mengatur baris, sedangkan loop dalam digunakan untuk mengatur kolom. Akumulator digunakan untuk menghitung jumlah setiap baris dan jumlah keseluruhan. Counter digunakan untuk menghitung banyak hasil perkalian yang genap.

## Hasil Pengujian

Input n = 1 → jumlah pasangan = 1, total semua = 1, banyak hasil genap = 0 → berhasil.

Input n = 2 → jumlah pasangan = 4, total semua = 9, banyak hasil genap = 3 → berhasil.

Input n = 3 → jumlah pasangan = 9, total semua = 36, banyak hasil genap = 5 → berhasil.

Analisis Efisiensi

Untuk input n, badan loop dalam berjalan sebanyak n × n atau n² kali.

## Refleksi

Kesalahan yang ditemukan adalah salah menempatkan inisialisasi total_baris. Perbaikannya adalah menempatkan total_baris = 0 di dalam loop luar sebelum loop dalam, sehingga jumlah setiap baris dihitung dari awal.