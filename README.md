<table>
  <tr>
    <th colspan="2">DATA MAHASISWA</th>
  </tr>
  <tr>
    <td>Nama</td>
    <td>Roswanda Nuraini</td>
  </tr>
  <tr>
    <td>NIM</td>
    <td>312210328</td>
  </tr>
  <tr>
    <td>Kelas</td>
    <td>TI.22.A3</td>
  </tr>
</table>

# <p align="center">Praktikum8 : PHP dan Database MySQL</p>

# Langkah-langkah praktikum

# Menjalankan MySQL Server

Untuk menjalankan MySQL Server dari menu XAMPP Contol.

![Screenshot (515)](https://github.com/roswanda11/lab8web/assets/115516632/e77897cc-5c66-45a4-900c-f1b4e0154dc8)

# Mengakses MySQL Client menggunakan PHP MyAdmin

Pastikan webserver Apache dan MySQL server sudah dijalankan. Kemudian buka melalui browser: http://localhost/phpmyadmin/

# Membuat Database: Studi Kasus Data Barang

Dengan menggunakan tabel seseorang dapat dengan mudah mengetahui berbagai perubahan (menaik atau menurun) yang telah berlangsung dalam suatu masalah.

1. Membuat Database

        CREATE DATABASE latihan1;

2. Membuat Tabel

        CREATE TABLE data_barang (
         id_barang int(10) auto_increment Primary Key,
         kategori varchar(30),
         nama varchar(30),
         gambar varchar(100),
         harga_beli decimal(10,0),
         harga_jual decimal(10,0),
         stok int(4)
        );

![image](https://github.com/roswanda11/lab8web/assets/115516632/aef58a7e-b196-47db-bd92-989be0f99746)

3. Menambahkan Data

        INSERT INTO data_barang (kategori, nama, gambar, harga_beli, harga_jual, stok)
        VALUES ('Elektronik', 'HP Samsung Android', 'hp_samsung.jpg', 2000000, 2400000, 5),
        ('Elektronik', 'HP Xiaomi Android', 'hp_xiaomi.jpg', 1000000, 1400000, 5),
        ('Elektronik', 'HP OPPO Android', 'hp_oppo.jpg', 1800000, 2300000, 5);
      
      
# Membuat Program CRUD

Buat folder <b>lab8_php_database</b> pada root directory web server (d:\xampp\htdocs)

![Screenshot (516)](https://github.com/roswanda11/lab8web/assets/115516632/8331219b-cc23-4c2e-bb81-e17f3a24d136)

1. Kemudian untuk mengakses direktory tersebut pada web server dengan mengakses URL: http://localhost/lab8_php_database

![image](https://github.com/roswanda11/lab8web/assets/115516632/8123db39-6fd9-43d8-85e1-a4b3c2923c59)

2. Membuat file koneksi database Buat file baru dengan nama ```koneksi.php```




















































