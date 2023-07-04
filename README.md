# Belajar MongoDB

**MongoDB** adalah salah satu database NoSQL yang paling populer. MongoDB adalah database yang berorientasi pada dokumen. Dokumen dalam MongoDB mirip dengan objek JSON. MongoDB menyimpan data dalam bentuk dokumen dan koleksi. Dokumen adalah sekumpulan field dan value. Koleksi adalah sekumpulan dokumen. MongoDB menyimpan data dalam bentuk dokumen dan koleksi. Dokumen adalah sekumpulan field dan value. Koleksi adalah sekumpulan dokumen.

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
