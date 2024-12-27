# Pratikum8
NAMA : Richie Pranata

KELAS : TI.24.A.5 

NIM : 312410451
# Diagram Class
![foto](https://raw.githubusercontent.com/rich-pro12/foto1/7e4c46996be59e801118adadbe38e9ee45590fdd/Screenshot%202024-12-27%20163248.png)

# Flowchart 
![foto](https://raw.githubusercontent.com/rich-pro12/foto1/91154b47e11b9ab161dbe63a8a7aa93afb904900/Screenshot%202024-12-27%20165849%20.png)

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
   
![foto](https://raw.githubusercontent.com/rich-pro12/foto1/9fc05550f83dc6bf197489f639655d8e8d0f2a01/Screenshot%202024-12-27%20170256.png)

Kelas ini memiliki atribut daftar_mahasiswa, yang merupakan daftar untuk menyimpan data mahasiswa. Metode tambah, tampilkan, hapus, dan ubah digunakan untuk mengelola data mahasiswa.

2.fungsi unit

![foto](https://raw.githubusercontent.com/rich-pro12/foto1/1213603d7675dec44852d9e222d4349b8872f35b/2.%20Fungsi%20Unit%20.png)

Konstruktor: Metode init adalah konstruktor yang dipanggil saat objek dari kelas Mahasiswa dibuat. Atribut daftar_mahasiswa: Atribut ini adalah list kosong yang akan digunakan untuk menyimpan data mahasiswa dalam bentuk dictionary, di mana setiap dictionary berisi nama dan nilai.

3.Fungsi tambah(nama, nilai):

![foto](https://raw.githubusercontent.com/rich-pro12/foto1/5bca65d949df03d327ae2c02d80a79a70bd4b610/3.%20Fungsi%20Tambahan%20nama%20.jpg)

Fungsi ini digunakan untuk menambahkan data mahasiswa ke dalam list mahasiswa. Data yang ditambahkan adalah nama dan nilai mahasiswa. Setelah menambahkan data, fungsi ini akan mencetak pesan konfirmasi.

4.Fungsi tampilkan():

![foto](https://raw.githubusercontent.com/rich-pro12/foto1/87fe6b7c30a9858c61b53871b0bfd259e08bbc68/4.%20Fungsi%20Tampilkan.png)

Fungsi ini menampilkan semua data mahasiswa dalam format tabel. Jika tidak ada data mahasiswa, fungsi ini akan mencetak pesan bahwa tidak ada data yang tersedia. Jika ada data, fungsi ini mencetak tabel dengan nama dan nilai mahasiswa.

5.Fungsi hapus(nama):

![foto](https://raw.githubusercontent.com/rich-pro12/foto1/747e3a0e1637c38bb991721d78a53eadbedb3ca7/5.%20Fungsi%20Hapus.png)

Fungsi ini digunakan untuk menghapus data mahasiswa berdasarkan nama. Fungsi ini akan menyaring list mahasiswa untuk menghapus entri yang memiliki nama yang sesuai. Setelah menghapus data, fungsi ini mencetak pesan konfirmasi.

6.Fungsi ubah(nama, nilai_baru):

![foto](https://raw.githubusercontent.com/rich-pro12/foto1/93daa7f89c9c9d26ad698861af968a8b9e7bb607/6.Fungsi%20Ubah.png)

Fungsi ini digunakan untuk mengubah nilai mahasiswa berdasarkan nama. Fungsi ini mencari mahasiswa dengan nama yang diberikan dan mengubah nilai mereka jika ditemukan. Jika nama tidak ditemukan, fungsi ini akan mencetak pesan bahwa data mahasiswa tidak ditemukan.

7.Bagian if name == "main": :

![foto](https://raw.githubusercontent.com/rich-pro12/foto1/80b0c5dbccd01643d47b373321ad71569b425ef6/7.%20Bagian%20if%20name%20.png)

Bagian ini adalah loop utama yang akan terus berjalan hingga pengguna memilih untuk keluar. Menampilkan menu pilihan kepada pengguna untuk memilih operasi yang diinginkan. Mengambil input dari pengguna dan memanggil fungsi yang sesuai berdasarkan pilihan pengguna.

# Hasil Program 

![foto](https://raw.githubusercontent.com/rich-pro12/foto1/b8796f3059bf55601cca3ead35e98e19fa12a8bc/Hasil%20pemrog.jpg)

