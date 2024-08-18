# Sistem Informasi Akademik Perguruan Tinggi

**Sistem Informasi Akademik Perguruan Tinggi** / **SIAKAD - PT** adalah aplikasi pengolahan data akademik perguruan tinggi berbasis web dimana data yang dikelolah mulai dari data kemahasiswaan, data tenaga pedidik dan data akademik lainnya. Aplikasi ini menggunakan framework [codeigniter](https://codeigniter.com) dan beberapa template untuk bagian frontend nya.


# Instalasi

1. Pertama - tama siapkan database **SIAKAD**
2. Buka file **configuration.php** lalu lakukan beberapa pengaturan seperti ini:
    * Masukkan base url ```var $_site_url = 'http://contoh-url/'```
	* Jika aplikasi dalam sub folder seperti **localhost/siakad-pt/** maka property ini diisi sesuai dengan nama sub folder, jika tidak dalam sub folder makan kosong kan saja ```var $_sub_domain = 'siakad-pt'```
    * Masukkan host database ```var $_hostname = ''```
    * Masukkan username database ```var $_database_user = ''```
	* Masukkan password database ```var $_database_password = ''```
	* Masukkan nama database ```var $_database_name = ''```
    * Masukkan nama perguruan tinggi ```var $_pt_name = 'Nama PT'```
3. Install semua package require yang sudah ada dalam file **composer.json**. Ini memerlukan composer untuk melakukan penginstalan.
4. Setelah package yang dibutuhkan sudah terinstall maka aplikasi sudah siap digunakan.
