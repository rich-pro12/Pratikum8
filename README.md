# Pratikum8
NAMA : Richie Pranata

KELAS : TI.24.A.5 

NIM : 312410451

![foto]()

# Flowchart 
![foto]()

Penjelasan Flowchart (Mulai Program): Titik awal dari program.

(Tampilkan Menu): Menampilkan pilihan menu kepada pengguna.

(Pilih Menu): Pengguna memilih salah satu opsi dari menu.

(Tambah Data Mahasiswa): Jika pengguna memilih untuk menambah data, proses ini akan dijalankan, dan setelah selesai, kembali ke menu.

(Tampilkan Data Mahasiswa): Jika pengguna memilih untuk menampilkan data, proses ini akan dijalankan, dan setelah selesai, kembali ke menu.

(Hapus Data Mahasiswa): Jika pengguna memilih untuk menghapus data, proses ini akan dijalankan, dan setelah selesai, kembali ke menu.

(Ubah Data Mahasiswa): Jika pengguna memilih untuk mengubah data, proses ini akan dijalankan, dan setelah selesai, kembali ke menu.

(Keluar dari Program): Jika pengguna memilih untuk keluar, program akan berhenti.

(Tidak Valid): Jika pilihan tidak valid, program akan kembali ke langkah untuk menampilkan menu.

# Penjelasan Program
1. fungsi class
![foto]()
Kelas ini memiliki atribut daftar_mahasiswa, yang merupakan daftar untuk menyimpan data mahasiswa. Metode tambah, tampilkan, hapus, dan ubah digunakan untuk mengelola data mahasiswa.

2.fungsi init
![foto]()
Konstruktor: Metode init adalah konstruktor yang dipanggil saat objek dari kelas Mahasiswa dibuat. Atribut daftar_mahasiswa: Atribut ini adalah list kosong yang akan digunakan untuk menyimpan data mahasiswa dalam bentuk dictionary, di mana setiap dictionary berisi nama dan nilai.

3.Fungsi tambah(nama, nilai):
![foto]()
Fungsi ini digunakan untuk menambahkan data mahasiswa ke dalam list mahasiswa. Data yang ditambahkan adalah nama dan nilai mahasiswa. Setelah menambahkan data, fungsi ini akan mencetak pesan konfirmasi.

4.Fungsi tampilkan():
![foto]()
Fungsi ini menampilkan semua data mahasiswa dalam format tabel. Jika tidak ada data mahasiswa, fungsi ini akan mencetak pesan bahwa tidak ada data yang tersedia. Jika ada data, fungsi ini mencetak tabel dengan nama dan nilai mahasiswa.

5.Fungsi hapus(nama):
![foto]()
Fungsi ini digunakan untuk menghapus data mahasiswa berdasarkan nama. Fungsi ini akan menyaring list mahasiswa untuk menghapus entri yang memiliki nama yang sesuai. Setelah menghapus data, fungsi ini mencetak pesan konfirmasi.

6.Fungsi ubah(nama, nilai_baru):
![foto]()
Fungsi ini digunakan untuk mengubah nilai mahasiswa berdasarkan nama. Fungsi ini mencari mahasiswa dengan nama yang diberikan dan mengubah nilai mereka jika ditemukan. Jika nama tidak ditemukan, fungsi ini akan mencetak pesan bahwa data mahasiswa tidak ditemukan.

7.Bagian if name == "main"::
![foto]()
Bagian ini adalah loop utama yang akan terus berjalan hingga pengguna memilih untuk keluar. Menampilkan menu pilihan kepada pengguna untuk memilih operasi yang diinginkan. Mengambil input dari pengguna dan memanggil fungsi yang sesuai berdasarkan pilihan pengguna.

# Hasil Program 
![foto]()

