# Minpro 1 - Pemrograman Berbasis Objek

## Identitas

Nama  : Akhmad Rafliansyah

NIM   : 2509116045

Prodi : Sistem Informasi 25'B

Tema  : Sistem Informasi Manajemen Pencucian Kendaraan

## Deskripsi Program

Sistem Informasi Manajemen Pencucian Kendaraan merupakan program berbasis Java yang digunakan untuk mengelola data pencucian kendaraan. 
Program ini membantu pengguna dalam menambahkan, menampilkan, mengubah, dan menghapus data transaksi pencucian kendaraan. Program dibuat
dengan menerapkan konsep Object-Oriented Programming (OOP) seperti class, object, constructor, encapsulation, serta penggunaan ArrayList 
untuk menyimpan data transaksi selama program berjalan.

## Fitur Program

Program memiliki beberapa fitur utama, yaitu:
1. Tambah Data Pencucian
2. Tampilkan Data Pencucian
3. Ubah Data Pencucian
4. Hapus Data Pencucian
5. Keluar dari Program

## Alur Program

Program dimulai dengan menampilkan menu utama yang berisi beberapa pilihan, yaitu tambah data, tampilkan data, ubah data, hapus data, dan keluar
dari program. Pengguna dapat memilih salah satu menu dengan memasukkan angka sesuai pilihan yang tersedia.

<img width="461" height="170" alt="Screenshot 2026-09-10 202316" src="https://github.com/user-attachments/assets/b5c6b95b-a6d5-46e2-a3e8-ae07ccd95a7a" />

1. Tambah Data Pencucian
   
   Pada menu **Tambah Data Pencucian**, pengguna diminta memasukkan data transaksi seperti ID transaksi, ID pelanggan, nama pelanggan, nomor
   telepon, nomor plat kendaraan, jenis kendaraan, dan merk kendaraan. Setelah itu, pengguna memilih jenis layanan pencucian yang tersedia. Sistem
   akan melakukan validasi terhadap input yang diberikan, seperti memastikan ID transaksi tidak kosong dan tidak sama dengan ID transaksi yang
   sudah tersimpan. Pada pilihan layanan, pengguna hanya dapat memasukkan angka 1 sampai 3. Jika pengguna memasukkan huruf atau angka di luar
   pilihan tersebut, sistem akan menampilkan pesan kesalahan dan meminta pengguna memasukkan pilihan kembali. Setelah seluruh data valid, data
   pelanggan, kendaraan, dan layanan akan dibuat menjadi objek dan digabungkan ke dalam objek transaksi. Selanjutnya, objek transaksi tersebut
   disimpan ke dalam `ArrayList`.
   
   <img width="532" height="479" alt="image" src="https://github.com/user-attachments/assets/af460cd7-1800-4e6f-ad38-b80336107d7b" />
   
2. Tampilkan Data Pencucian
   
   Pada menu **Tampilkan Data Pencucian**, sistem akan memeriksa apakah terdapat data transaksi di dalam `ArrayList`. Jika belum terdapat data,
   sistem akan menampilkan informasi bahwa belum ada data pencucian. Jika terdapat data, sistem menggunakan perulangan untuk mengambil setiap
   transaksi dan menampilkan informasi transaksi, pelanggan, kendaraan, serta layanan yang dipilih.
   
   <img width="569" height="371" alt="image" src="https://github.com/user-attachments/assets/963ba85c-9e79-48fe-be71-65697f3edd6c" />
   
3. Ubah Data Pencucian
   
   Pada menu **Ubah Data Pencucian**, pengguna diminta memasukkan ID transaksi yang ingin diubah. Sistem kemudian mencari ID tersebut di dalam
   `ArrayList`. Jika ID ditemukan, pengguna dapat memasukkan data baru untuk nama pelanggan, nomor telepon, jenis kendaraan, dan merk kendaraan.
   Data tersebut kemudian diperbarui menggunakan setter yang terdapat pada masing-masing class. Jika ID transaksi tidak ditemukan, sistem akan
   menampilkan pesan bahwa data tidak ditemukan.
   
   <img width="488" height="345" alt="image" src="https://github.com/user-attachments/assets/db750cb2-847a-48e2-ac26-e0fc4846adbb" />
   
4. Hapus Data Pencucian
   
   Pada menu **Hapus Data Pencucian**, pengguna memasukkan ID transaksi yang ingin dihapus. Sistem mencari transaksi berdasarkan ID tersebut.
   Jika transaksi ditemukan, data akan dihapus dari `ArrayList`. Jika ID tidak ditemukan, sistem akan menampilkan pesan bahwa data tidak ditemukan.
   
   <img width="476" height="271" alt="image" src="https://github.com/user-attachments/assets/db4a7ada-df21-45a3-a4ed-6e276647f618" />
   
5. Keluar dari Program
   
   Setelah setiap proses selesai, program kembali menampilkan menu utama sehingga pengguna dapat memilih proses lainnya. Program akan terus
   berjalan selama pengguna belum memilih menu **Keluar**. Ketika pengguna memilih menu keluar, program akan menampilkan pesan bahwa program
   selesai dan menghentikan proses.
   
   <img width="556" height="286" alt="image" src="https://github.com/user-attachments/assets/bc169e38-f532-470d-a0e9-6ae38596a636" />

## Class yang Digunakan

Program terdiri dari beberapa class, yaitu:
- `Pelanggan` digunakan untuk menyimpan data pelanggan.
- `Kendaraan` digunakan untuk menyimpan data kendaraan.
- `Layanan` digunakan untuk menyimpan data layanan pencucian.
- `Transaksi` digunakan untuk menggabungkan data transaksi, pelanggan, kendaraan, dan layanan.
- `SistemPencucianKendaraan` digunakan sebagai class utama untuk menjalankan program.

## Value-Added

Program memiliki beberapa fitur tambahan, yaitu:
- Menggunakan access modifier `private` pada atribut.
- Menggunakan getter dan setter sebagai penerapan encapsulation.
- Menggunakan constructor pada setiap class.
- Menggunakan validasi input.
- ID transaksi tidak boleh kosong dan tidak boleh sama.
- Pilihan layanan hanya dapat menggunakan angka 1 sampai 3.
- Input huruf pada pilihan layanan akan ditolak dan pengguna diminta memasukkan angka kembali.




