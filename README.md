# Laporan-modul-1-dan-2-prak-Basis-Data
### Nama     : Muhammad Wahyu Firmansyah
### Kelas    : XI Rpl 2
### NO.Absen : 12

## Modul 1

### 1.Install Xampp terlebih dahulu

![image](https://user-images.githubusercontent.com/92255670/190301531-fff847a3-2912-499c-90dc-98b112097e43.png)


### 2.aktifkan mysql di xampp

![image](https://user-images.githubusercontent.com/92255670/190300828-bc545470-06b3-49e6-86c7-2a8d147eab8f.png)

### 3.kemudian masuk ke command prompt 

![image](https://user-images.githubusercontent.com/92255670/190300950-b3c6cf63-dc30-454a-88ea-089139b4a69b.png)

- ### Cara membuat title


title nama_kaliam

![image](https://user-images.githubusercontent.com/113568261/190320280-2f2cc319-5303-46a8-b594-e2db2bf89c66.png)


### 4.Masuk direktori Mysql 


cd xampp/mysql/bin


![image](https://user-images.githubusercontent.com/113568261/190320386-83cfa9d0-bf03-47bf-b147-a21bb7d40ed1.png)


### 5.ketik syntaks berikut untuk masuk ke MariaDB

mysql -u root


![image](https://user-images.githubusercontent.com/113568261/190320785-935bade5-4e3f-47cc-a032-0eb669b39991.png)


*Di atas sudah bisa menuliskan query*



>## Modul 2
- ### Cara melihat daftar database

show databases;


![image](https://user-images.githubusercontent.com/113568261/190320974-c0ec64b5-aa16-4e73-b357-72a21791fba1.png)


- ### Cara membuat database

create database nama_database;

![image](https://user-images.githubusercontent.com/113568261/190321401-bcdbabd6-83e1-4a56-82fc-80c4faa37a4f.png)


- ### Cara memilih dan masuk dafar database yang kita inginkan 


use nama_database;


- ### Cara membuat table

create table name_table(nama varchar(50)not null,no int(3)not null);


![image](https://user-images.githubusercontent.com/113568261/190327591-4b2c70ab-767e-4e42-8aad-1409ad9e5b88.png)


- ### Cara melihat daftar table

show tables;

![image](https://user-images.githubusercontent.com/113568261/190327784-a02ac95e-cc86-4c19-bfe0-4bbd2f740644.png)


- ### Cara melihat isi (struktur) di sebuah tabel


desc name_table;


![image](https://user-images.githubusercontent.com/113568261/190328095-e918299e-ad77-4342-8afa-9dfc4031c5a9.png)
