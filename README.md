#latihan1

1.	download GIT, Buka website resminya Git (git-scm).
![image](https://user-images.githubusercontent.com/56473376/67137947-e7bcb200-f266-11e9-9087-783a02bf4ce2.png)
2.	 Lalu klik download 2.23.0 for windows, lalu akan muncul tampilan seperti ini. Kemudian unduh git sesuai dengan arsitektur komputer kita. Kalau menggunakan git 64bit,unduh yang 64 bit begitu juga kalau menggunakan 32bit
![image](https://user-images.githubusercontent.com/56473376/67137973-5c8fec00-f267-11e9-9016-74129b4f6918.png)
3.Klik bit git yang akan diunduh,lalu akan muncul tampilan save file. 
![image](https://user-images.githubusercontent.com/56473376/67137989-9234d500-f267-11e9-99a5-cd0d907079d8.png)
4.Tunggu sampai proses download selesai
![image](https://user-images.githubusercontent.com/56473376/67138002-c8725480-f267-11e9-9aed-12dd5dcfc978.png)
5.	Pada saat pertama kali menggunakan git, perlu dilakukan konfigurasi  username dan user.email 
![image](https://user-images.githubusercontent.com/56473376/67138015-f6f02f80-f267-11e9-84f0-634987546df8.png)
6.	Buat direktory project praktikum pertama dengan nama latihan1
 $mkdir latihan1 dan cd latihan1
![image](https://user-images.githubusercontent.com/56473376/67138022-0f604a00-f268-11e9-8581-0def1caa5419.png)
7.	Lalu jalankan perintah git init,untuk membuat repository local.
$git init 
![image](https://user-images.githubusercontent.com/56473376/67138033-30c13600-f268-11e9-8919-557f4b02fc45.png)
8.	Kemudian tambahkan file baru pada repository
$echo “latihan 1”>>README.md
![image](https://user-images.githubusercontent.com/56473376/67138046-4c2c4100-f268-11e9-9912-69f75d35276f.png)
9.	Menyimpan perubahan ke database
$git commit –m “file pertama saya”
![image](https://user-images.githubusercontent.com/56473376/67138051-65cd8880-f268-11e9-86ea-4d7ed161ed22.png)
10.	Menambahkan remote repository
$git remote add origin https://github.com/anzela24.git
![image](https://user-images.githubusercontent.com/56473376/67138061-872e7480-f268-11e9-80bd-e474cdcb027d.png)
