# Lab11web-

nama : rafli maulana aziz

nim : 311910639

kelas :ti19c1

# Langkah-langkah Praktikum
# Buat folder baru dengan nama lab11_php_ci pada docroot webserver (htdocs)
![1](https://user-images.githubusercontent.com/56399268/122621498-f1dc2700-d0bf-11eb-878a-49c506e16cf9.PNG)

# Untuk mengaktifkan ekstentsi tersebut, melalu XAMPP Control Panel, pada bagian Apache klik Config -> PHP.ini
![2](https://user-images.githubusercontent.com/56242226/122332673-07870a80-cf61-11eb-930f-da3cff7b949f.png)

# Pada bagian extention, hilangkan tanda ; (titik koma) pada ekstensi yang akan diaktifkan. Kemudian simpan kembali filenya dan restart Apache web server.
![image](https://user-images.githubusercontent.com/56399268/122621358-7c705680-d0bf-11eb-85c5-019e4ac2a541.png)

# Instalasi Codeigniter 4
Untuk melakukan instalasi Codeigniter 4 dapat dilakukan dengan dua cara, yaitu cara manual dan menggunakan composer. Pada praktikum ini kita menggunakan cara manual.

![4](https://user-images.githubusercontent.com/56242226/122393093-b85fca80-cf9e-11eb-8f91-66ac3f5ff5a4.PNG)
# Menjalankan CLI (Command Line Interface) 
Perintah yang dapat dijalankan untuk memanggil CLI Codeigniter adalah: ( php spark )
![5](https://user-images.githubusercontent.com/56399268/122622165-091c1400-d0c2-11eb-97ed-797ee9728eb2.jpg)

# Mengaktifkan Mode Debugging
Ketika terjadi error pada aplikasi akan ditampilkan pesan kesalahan seperti berikut.

![image](https://user-images.githubusercontent.com/56399268/122622954-93657780-d0c4-11eb-917e-c6fe9cf93ffd.png)

# Ubah nama file env menjadi .env kemudian buka file tersebut dan ubah nilai variable CI_ENVIRINMENT menjadi development
![6](https://user-images.githubusercontent.com/56242226/122393818-7c793500-cf9f-11eb-9f3a-c3732f68e653.PNG)

# Contoh error yang terjadi. Untuk mencoba error tersebut, ubah kode pada file app/Controller/Home.php hilangkan titik koma pada akhir kode.
![7](https://user-images.githubusercontent.com/56242226/122393979-a9c5e300-cf9f-11eb-91e5-618f12837ae2.PNG)

# Routing dan Controller
Router terletak pada file app/config/Routes.php

![8](https://user-images.githubusercontent.com/56242226/122394243-f3aec900-cf9f-11eb-9f83-dfc61dbe0a83.PNG)

#  buka CLI dan jalankan perintah berikut. 
# yaitu php spark
![6](https://user-images.githubusercontent.com/56399268/122622173-0caf9b00-d0c2-11eb-9a05-c34fb66b0da4.jpg)

# Selanjutnya coba akses route yang telah dibuat dengan mengakses alamat url http://localhost:8080/about
![9a](https://user-images.githubusercontent.com/56242226/122394476-3bcdeb80-cfa0-11eb-86a1-a89df6715a29.PNG)

# Membuat Controller
Selanjutnya adalah membuat Controller Page. Buat file baru dengan nama page.php pada direktori Controller kemudian isi kodenya seperti berikut.

![10](https://user-images.githubusercontent.com/56242226/122394552-51431580-cfa0-11eb-9d93-17bf07f36f5f.PNG)

Selanjutnya refresh Kembali browser,

![10a](https://user-images.githubusercontent.com/56242226/122394645-6a4bc680-cfa0-11eb-98d7-29c29e5a2ef1.PNG)

# Tambahkan method baru pada Controller Page seperti berikut.
![11a](https://user-images.githubusercontent.com/56242226/122394885-a3843680-cfa0-11eb-838d-4754a82e550d.PNG)

# Method ini belum ada pada routing, sehingga cara mengaksesnya dengan menggunakan alamat: http://localhost:8080/page/tos
![11](https://user-images.githubusercontent.com/56242226/122394967-b72f9d00-cfa0-11eb-9d94-3b29f33e86dd.PNG)

# Buat file css pada direktori public dengan nama style.css 
![13](https://user-images.githubusercontent.com/56242226/122396548-4ab59d80-cfa2-11eb-86b0-ca0a728808df.PNG)

# Kemudian buat folder template pada direktori view kemudian buat file header.php dan footer.php
![image](https://user-images.githubusercontent.com/56399268/122622681-a75ca980-d0c3-11eb-9c47-479d6905adbb.png)

# footer.php
![image](https://user-images.githubusercontent.com/56399268/122622835-2ce05980-d0c4-11eb-9e2f-749b0a70f2f1.png)


# Kemudian ubah file app/view/about.php seperti berikut
![14a](https://user-images.githubusercontent.com/56242226/122396731-80f31d00-cfa2-11eb-8e0a-e88a4bda4921.PNG)
