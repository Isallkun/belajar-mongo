# Belajar MongoDB

Merupakan mata kuliah basis data lanjut semester 4 di Universitas Yudharta Pasuruan. Repo ini berisi tentang dokumentasi belajar MongoDB saya selama menempuh semester 4.

## Tentang MongoDB

**MongoDB** adalah salah satu database NoSQL yang paling populer. MongoDB adalah database yang berorientasi pada dokumen. Dokumen dalam MongoDB mirip dengan objek JSON. MongoDB menyimpan data dalam bentuk dokumen dan koleksi. Dokumen adalah sekumpulan field dan value. Koleksi adalah sekumpulan dokumen. Setiap dokumen dalam koleksi dapat memiliki struktur yang berbeda. MongoDB menyimpan data dalam format BSON (Binary JSON). BSON adalah representasi biner dari JSON yang dapat digunakan untuk menyimpan dan mengambil data dengan cepat.

## Instalasi MongoDB

Instalasi MongoDB dapat dilakukan dengan mengikuti langkah-langkah berikut:

1. Kunjungi [https://www.mongodb.com/try/download/community](https://www.mongodb.com/try/download/community)
2. Pilih versi MongoDB yang akan diunduh
3. Pilih sistem operasi yang digunakan (disini saya menggunakan windows)
4. Pilih direktori instalasi MongoDB. Secara default, MongoDB akan diinstal di direktori "C:\Program Files\MongoDB". Anda dapat memilih untuk menggunakan lokasi yang berbeda jika diinginkan.
5. Pilih komponen yang ingin Anda instal. Biasanya, Anda dapat membiarkan pilihan default yang disarankan oleh installer MongoDB.
6. Pilih opsi "Complete" untuk menginstal semua komponen MongoDB yang diperlukan.
7. Pilih opsi "Install MongoDB as a Service" agar MongoDB dapat dijalankan sebagai layanan Windows. Opsi ini memungkinkan MongoDB untuk secara otomatis memulai saat sistem dinyalakan.
8. Klik "Install" untuk memulai proses instalasi MongoDB.
9. Tunggu hingga proses instalasi selesai. Setelah selesai, Anda akan melihat pesan bahwa instalasi berhasil
10. Setelah instalasi selesai, Anda perlu menambahkan direktori bin MongoDB ke dalam variabel lingkungan PATH di sistem Anda agar Anda dapat mengakses perintah MongoDB dari mana saja di command prompt. Ikuti langkah berikut:
    - Buka "Control Panel" dan cari "System" atau "System Properties".
    - Klik "Advanced system settings".
    - Di jendela "System Properties", klik "Environment Variables".
    - Di bagian "System variables", cari variabel "Path" dan klik "Edit".
    - Tambahkan jalur direktori bin MongoDB (misalnya, "C:\Program Files\MongoDB\Server\4.4\bin") ke dalam nilai variabel "Path". Pastikan untuk menggunakan jalur yang sesuai dengan versi MongoDB yang Anda instal.
    - Klik "OK" untuk menyimpan perubahan.
11. Untuk memastikan instalasi MongoDB berhasil, buka command prompt baru dan ketik perintah mongo. Jika MongoDB berhasil diinstal, Anda akan melihat prompt MongoDB dan dapat mulai menggunakan perintah-perintah MongoDB.

## Menjalankan MongoDB

Secara default, di windows akan muncul mongoDB Atlas dan mongoDB Compass. Untuk menjalankan MongoDB, Anda dapat menggunakan salah satu dari dua cara berikut:

1. Melalui Command Prompt:
   - Buka Command Prompt dengan cara menekan tombol Windows + R, ketik "cmd" dan tekan Enter.
   - Ketik perintah `mongosh` dan tekan Enter. Ini akan menjalankan server MongoDB.
   - Biarkan Command Prompt tetap terbuka untuk menjalankan server MongoDB.
2. Menggunakan MongoDB Compass:
   - Buka MongoDB Compass, yang biasanya telah diinstal bersamaan dengan MongoDB.
   - Pada tampilan awal, Anda akan melihat opsi "Connect" atau "Connect to Host". Klik opsi tersebut.
   - MongoDB Compass akan mencoba terhubung ke server MongoDB secara otomatis. Jika tidak berhasil, Anda dapat mengklik opsi "Fill in connection fields individually" dan memasukkan detail koneksi secara manual.
   - Setelah terhubung, Anda akan dapat melihat dan mengelola database dan koleksi dalam antarmuka MongoDB Compass.
