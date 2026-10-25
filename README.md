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

## Kuis Formatif

1. Apa perbedaan string dan list pada Python?
String adalah kumpulan karakter yang digunakan untuk menyimpan teks, sedangkan list adalah kumpulan elemen yang dapat berisi berbagai jenis data. String bersifat immutable, sedangkan list dapat diubah setelah dibuat.

2. Mengapa string disebut immutable?
String disebut immutable karena karakter di dalamnya tidak dapat diubah secara langsung setelah string dibuat. Jika ingin mengubah teks, kita perlu membuat string baru.

3. Apa hasil dari "'Python'[1:4]"?
Hasilnya adalah "yth". Indeks dimulai dari 0, sehingga slicing mengambil karakter pada indeks 1, 2, dan 3, tetapi tidak mengambil indeks 4.

4. Apa fungsi "strip()"?
Method "strip()" digunakan untuk menghapus spasi atau karakter tertentu di bagian awal dan akhir string. Method ini tidak menghapus spasi berlebih di antara kata.

5. Kapan "lower()" lebih tepat daripada "title()"?
"lower()" lebih tepat ketika teks perlu diubah menjadi huruf kecil seluruhnya, misalnya untuk membandingkan teks tanpa membedakan huruf besar dan kecil. Sementara itu, "title()" digunakan untuk membuat huruf pertama setiap kata menjadi huruf kapital.

6. Apa perbedaan "split()" dan "join()"?
"split()" digunakan untuk memisahkan string menjadi beberapa bagian dalam bentuk list. Sementara itu, "join()" digunakan untuk menggabungkan beberapa string menjadi satu string dengan pemisah tertentu.

7. Bagaimana memeriksa apakah kata "'data'" terdapat dalam suatu string?
Kita dapat menggunakan operator "in".

Contoh:

teks = "Pengolahan data mahasiswa"
print("data" in teks)

Hasil:

True

8. Apa arti hasil "-1" dari "find()"?
Hasil "-1" menunjukkan bahwa teks atau karakter yang dicari tidak ditemukan di dalam string.

9. Mengapa normalisasi teks perlu dilakukan sebelum perbandingan?
Normalisasi teks diperlukan agar format teks menjadi konsisten, misalnya dengan menghapus spasi berlebih dan menyamakan penggunaan huruf besar atau kecil. Dengan demikian, perbandingan teks dapat dilakukan dengan lebih tepat.

10. Perintah apa yang digunakan untuk mengirim commit ke GitHub?
Perintah yang digunakan adalah "git push".

Contoh:

git push

Jika baru pertama kali menghubungkan branch lokal ke repository GitHub, perintah yang dapat digunakan adalah:

git push -u origin main