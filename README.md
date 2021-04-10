# UAS
fungsi php pada tiap fitur dalam data peserta vaksinasi covid19

1. fungsi login, dimana fitur login berfungsi untuk membatasi pengunjung untuk membuka informasi tertentu pada website. 
Pengunjung harus memiliki akun terlebih dahulu untuk mengakses informasi yang dibatasi, sehingga tidak sembarangan pengunjung dapat mengakses informasi tersebut.

2. fungsi input data peserta vaksinasi covid19, berfungsi untuk mengisi data diri peserta, sehingga data tersebut dapat di pakai untuk vaksinasi, antara lain:
+ A. pilih provinsi, dimana pesrta harus memilih provinsi tempat tinggal.
+ B. pilih kab/kota, dimana peserta harus memilih kab/kota tampat tinggal.
+ C. pilih kecamatan, dimana peserta harus memilih kecamatan tempat tinggal.
+ D. pilih jenis faskes, dimana peserta harus memilih jenis faskes antara RSUD dan KLINIK yang ingin di pakai.
+ E. pilih nama faskes, dimana peserta harus memilih nama faskes yang ingin di tujui.
+ F. mengisi NIK, dimana peserta harus mengisi nomer NIK.
+ G. mengisi nama, dimana peserta harus menisi nama peserta untuk data vaksinasi.
+ H. mengisi jenis kelamin, dimana peserta harus mengisi jenis kelamin sesuai dengan identitas peserta.
+ I. mengisi umur, dimana peserta harus mengisi umur sesuai dengan umur peserta.
+ J. mengisi tanggal lahir, dimana pesertaharus mengisi tanggal lahir peserta sesuai dengan data diri peserta.
+ K. mengisi nomer hp, dimana peserta harus mengisi nomer hp untuk nantinya bisadigunakan dalam mengirim hasil atau pesan kepada peserta.
+ L. mengisi alamat, dimana peserta harus mengisi alamat tinggal saat ini.
+ M. menampilkan data diri peserta vaksinasi covid19, dimana data peserta yang sudah berhasil disimpan dapat ditampilkan.
+ N. mengubah data pendaftar yang sudah diinput, dimana berfungsi untuk mengubah data sebelumnya denga data baru peserta.
+ O. menghapus data peserta, dimana data peserta yang bermasalah dapay dihapus dari database.
+ P. mencetak data peserta, dimana data peserta yang sudah di simpan dapat dicetak dengan format .pdf
+ Q. logout sistem, dimana peserta dapat keluar dari sistem ketika sudah selesai mengisi semua data yang diperlukan+ + .

Aplikasi Sederhana Daftar Peserta Vaksinasi Covid-19 terdiri dari :

+ form login
+ form input data
+ simpan data
+ menampilkan data
+ edit data
+ hapus data
+ cetak data

KETERANGAN Fungsi yang ada di php

+ mysqli_connect ( ) : Membuat koneksi ke database
+ mysqli_fetch_array ( ) : Mengambil hasil baris sebagai asosiatif , array numerik , atau keduanya dari database
+ mysqli_query ( ) : Melakukan query terhadap database
+ mysqli_select_db ( ) : Mengubah database default untuk koneksi
+ $_GET dan $_POST : Menampung data atau nilai dari sebuah form
+ $_SESSION : Menyimpan data atau nilai antar proses request
+ window.print() : Menampilkan halaman proses cetak pdf

+  WEBSITE application

+ https://unsmitten-junctions.000webhostapp.com
+ username : 02111223
+ password : unpam
