# Tes-Karyawan
Tes Karyawan - Software Developer (Laravel 11 & MySQL)

1. jalankan Web Server, saya sendiri menggunakan XAMPP, Start Apache dan MySQL
2. unduh folder pada repositori https://github.com/fikryfadhillah/Tes-Karyawan/ dengan nama "Laravel 11"
3. buka command prompt pada folder tersebut dan jalankan "C:\Users\fikry\Desktop\Laravel 11> code ."
4. buka terminal dan jalankan "php artisan serve" lalu masuk ke browser dengan alamat database yang saya buat yaitu http://127.0.0.1:8000/todo.

penjelasan :
pada web yang dibuat terdapat field "masukkan nama" untuk menambahkan nama peserta/pegawai/staff pada table absensi, setelah user memasukan nama absensi maka dengan menekan tombol "simpan" pada bagian kanan field maka data tersebut akan tersimpan di database http://localhost/phpmyadmin/index.php?route=/sql&pos=0&db=laravel&table=todo.

selanjutnya nama-nama yang sudah disimpan/dimasukkan akan ditampilkan dan dapat dilihat maksimal 10 nama/halaman ($max_data = 10;) dan akan ditampilkan pada halaman selanjutnya apabila melebihi 10 nama yang dimasukkan.

pada tombol pensil berwarna biru, user dapat merubah nama dari peserta/pegawai/staff denga nama baru, dan juga user dapat menetukan kehadiran atau ketidak hadiran peserta/pegawai/staff dengan menekan tombol (*radio) "Hadir" atau "Tidak Hadir", dan apabila nama yang dipilih memiliki value "Tidak Hadir" maka nama tersebut akan tercoret.

adapun tombol X berwarna merah diperuntukan untuk user yang ingin menghapus data peserta/pegawai/staff yang sudah tersimpan, tombol tersebut ditambahkan _Request Validation_ dimana akan muncul peringatan untuk menkonfirmasi user terhadap data yang akan dihapus.
