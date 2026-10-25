# Pertemuan 10 — String dan Pengolahan Teks Python

## 1. Tujuan
Program ini dibuat untuk mempelajari pengolahan string menggunakan Python, seperti membersihkan spasi, mengubah huruf menjadi format yang sesuai, memisahkan kata, menggabungkan kata, mencari kata, menghitung jumlah kata, dan membuat inisial nama.

Praktik ini terdiri dari enam file latihan dan satu program Tugas 4 tentang normalisasi data mahasiswa.

## 2. Materi yang Dipelajari
Materi yang dipelajari pada Pertemuan 10 meliputi:
1. Dasar-dasar string dalam Python.
2. Indeks dan slicing pada string.
3. Penggunaan method string, seperti "upper()", "lower()", "strip()", dan "title()".
4. Pembersihan teks menggunakan "replace()".
5. Memisahkan dan menggabungkan kata menggunakan "split()" dan "join()".
6. Pencarian kata menggunakan "in", "find()", dan "count()".
7. Penggunaan fungsi untuk mengolah data teks.

## 3. Struktur Folder
pertemuan-10-string-NIM/
├── latihan/
│   ├── 01_dasar_string.py
│   ├── 02_indeks_slicing.py
│   ├── 03_method_string.py
│   ├── 04_bersihkan_teks.py
│   ├── 05_split_join.py
│   └── 06_pencarian_kata.py
├── tugas/
│   └── normalisasi_data_mahasiswa.py
└── README.md

## 4. Algoritma Tugas 4
Program normalisasi data mahasiswa dilakukan dengan langkah-langkah berikut:
1. Memasukkan nama lengkap mahasiswa.
2. Membersihkan spasi berlebih pada nama.
3. Mengubah nama menjadi format huruf kapital yang sesuai.
4. Memasukkan kode kelas.
5. Mengubah kode kelas menjadi huruf kapital dan mengganti spasi dengan tanda hubung.
6. Menghitung jumlah kata pada nama.
7. Mengambil huruf pertama setiap kata untuk membuat inisial.
8. Menampilkan nama bersih, kode kelas, jumlah kata, dan inisial.

## 5. Cara Menjalankan Program
Program dijalankan melalui terminal di Visual Studio Code.
Untuk menjalankan salah satu file latihan, gunakan perintah berikut:
python latihan/01_dasar_string.py
Untuk menjalankan program Tugas 4, gunakan perintah berikut:
python tugas/normalisasi_data_mahasiswa.py
Masukkan nama mahasiswa dan kode kelas ketika diminta, kemudian periksa hasil yang ditampilkan pada terminal.

## 6. Hasil Pengujian (Test Case)
Test Case 1

Input:

- Nama: "aan hendrayana"
- Kode kelas: "pmat a 2026"

Hasil yang diharapkan:

Nama bersih : Aan Hendrayana
Kode kelas : PMAT-A-2026
Jumlah kata : 2
Inisial     : AH

Hasil aktual: Sesuai dengan hasil yang diharapkan.

Status: Berhasil.

Test Case 2

Input:

- Nama: "  siti    nurhaliza"
- Kode kelas: "  pmat   b   2026"

Hasil yang diharapkan:

Nama bersih : Siti Nurhaliza
Kode kelas : PMAT-B-2026
Jumlah kata : 2
Inisial     : SN

Hasil aktual: Sesuai dengan hasil yang diharapkan.

Status: Berhasil.

## 7. Refleksi
Melalui praktik ini, saya memahami bahwa string dapat digunakan untuk mengolah data teks, seperti membersihkan spasi, mengubah kapitalisasi, memisahkan kata, dan mencari informasi tertentu. Saya juga belajar menggunakan fungsi agar program lebih terstruktur dan dapat digunakan kembali.

Kesalahan yang dapat terjadi dalam pengolahan teks adalah spasi berlebih dan format huruf yang tidak konsisten. Hal tersebut dapat diatasi menggunakan method string yang sesuai.

## 8. Kesimpulan
String dalam Python dapat digunakan untuk mengolah teks secara sederhana dan terstruktur. Dengan memanfaatkan method string dan fungsi, data mahasiswa yang awalnya tidak konsisten dapat dinormalisasi agar lebih mudah dibaca dan digunakan.

## 9. Bantuan dan Referensi
Materi utama: Bahan Ajar Algoritma dan Pemrograman, Pertemuan 10 — String dan Pengolahan Teks dalam Python.
Perangkat yang digunakan: Visual Studio Code dan Python.