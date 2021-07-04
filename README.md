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

# Kemudian ubah file app/view/about.php seperti berikut
![14a](https://user-images.githubusercontent.com/56242226/122396731-80f31d00-cfa2-11eb-8e0a-e88a4bda4921.PNG)

# selanjutnya refresh tampilan tersebut:
![image](https://user-images.githubusercontent.com/56399268/122623904-22c05a00-d0c8-11eb-9e9b-2237c2020f1e.png)


# melanjutkan praktikum selanjutnya 


# Membuat Database dan Membuat Tabel
![1](https://user-images.githubusercontent.com/56242226/123265954-c32dd880-d525-11eb-8482-8e7061725a63.PNG)

# Konfigurasi koneksi database
Selanjutnya membuat konfigurasi untuk menghubungkan dengan database server. 
Konfigurasi dapat dilakukan dengan du acara, yaitu pada file app/config/database.php
atau menggunakan file .env. Pada praktikum ini kita gunakan konfigurasi pada file .env. 

![2a](https://user-images.githubusercontent.com/56242226/123266120-ebb5d280-d525-11eb-8b1d-205257065232.PNG)

# Membuat Model
Selanjutnya adalah membuat Model untuk memproses data Artikel. Buat file baru pada direktori app/Models dengan nama ArtikelModel.php

![3](https://user-images.githubusercontent.com/56242226/123266380-291a6000-d526-11eb-9d5d-4a67f7d12081.PNG)

# Membuat Controller
Buat Controller baru dengan nama Artikel.php pada direktori app/Controllers.

![4](https://user-images.githubusercontent.com/56242226/123266466-42231100-d526-11eb-8e8b-245dfddbd593.PNG)

# Membuat View
Buat direktori baru dengan nama artikel pada direktori app/views, kemudian buat file baru dengan nama index.php. 

![5](https://user-images.githubusercontent.com/56242226/123266591-61ba3980-d526-11eb-9623-d0deb6c256cf.PNG)

# Selanjutnya buka browser kembali, dengan mengakses url http://localhost:8080/artikel

![image](https://user-images.githubusercontent.com/56398559/123503197-a4d9f100-d67b-11eb-8238-f33fb1621d61.png)

# Belum ada data yang diampilkan. Kemudian coba tambahkan beberapa data pada database agar dapat ditampilkan datanya.

![6](https://user-images.githubusercontent.com/56242226/123267066-c8d7ee00-d526-11eb-90e6-b68ac9689909.PNG)

# Refresh kembali browser, sehingga akan ditampilkan hasilnya.

![image](https://user-images.githubusercontent.com/56398559/123503225-cdfa8180-d67b-11eb-9253-9e5de09c694c.png)

# Membuat Tampilan Detail Artikel
Tampilan pada saat judul berita di klik maka akan diarahkan ke halaman yang berbeda. Tambahkan fungsi baru pada Controller Artikel dengan nama view().

![7](https://user-images.githubusercontent.com/56242226/123267238-fae95000-d526-11eb-892e-edcfeafd202d.PNG)

# Membuat View Detail
Buat view baru untuk halaman detail dengan nama app/views/artikel/detail.php.

![8](https://user-images.githubusercontent.com/56242226/123267321-12c0d400-d527-11eb-984e-b050d35ee41e.PNG)

# Membuat Routing untuk artikel detail
Buka Kembali file app/config/Routes.php, kemudian tambahkan routing untuk artikel detail.

![9](https://user-images.githubusercontent.com/56242226/123267389-2835fe00-d527-11eb-99cd-709de5be4b61.PNG)

# Kemudian Refresh kembali 

![image](https://user-images.githubusercontent.com/56398559/123503247-f8e4d580-d67b-11eb-8886-06c2a25fcbaf.png)

# Membuat Menu Admin
Menu admin adalah untuk proses CRUD data artikel. Buat method baru pada Controller Artikel dengan nama admin_index().

![10](https://user-images.githubusercontent.com/56242226/123281008-823cc080-d533-11eb-86e5-d9e3aa241872.PNG)

# Selanjutnya buat view untuk tampilan admin dengan nama admin_index.php

![11](https://user-images.githubusercontent.com/56242226/123281230-b4e6b900-d533-11eb-858d-1d9ec3293c4d.PNG)

# Tambahkan routing untuk menu admin seperti berikut:

![11b](https://user-images.githubusercontent.com/56242226/123281550-fa0aeb00-d533-11eb-868b-e1b5b18ae9d0.PNG)

setelah itu Akses menu admin dengan url http://localhost:8080/admin/artikel

![image](https://user-images.githubusercontent.com/56398559/123503309-6b55b580-d67c-11eb-9d66-6d5003fed2de.png)

# Menambah Data Artikel
Tambahkan fungsi/method baru pada Controller Artikel dengan nama add().

![14](https://user-images.githubusercontent.com/56242226/123282716-f75cc580-d534-11eb-9d94-44589339039c.PNG)

Kemudian buat view untuk form tambah dengan nama form_add.php

![14a](https://user-images.githubusercontent.com/56242226/123282730-f88df280-d534-11eb-9e2f-07e5f7f19411.PNG)

Setelah itu klik tambah artikel maka tampilan nya seperti berikut ..

![image](https://user-images.githubusercontent.com/56398559/123503321-8b857480-d67c-11eb-844c-5b102154bc19.png)

# Mengubah Data
Tambahkan fungsi/method baru pada Controller Artikel dengan nama edit(). 

![15](https://user-images.githubusercontent.com/56242226/123282738-f9bf1f80-d534-11eb-96c1-9016307cee76.PNG)

Kemudian buat view untuk form tambah dengan nama form_edit.php

![15a](https://user-images.githubusercontent.com/56242226/123282741-fa57b600-d534-11eb-98f1-1ec2573eb220.PNG)

maka tampilan nya seperti ini 

![image](https://user-images.githubusercontent.com/56398559/123503346-bbcd1300-d67c-11eb-8ac7-849f150e566e.png)

# Menghapus Data
Tambahkan fungsi/method baru pada Controller Artikel dengan nama delete(). 

![16](https://user-images.githubusercontent.com/56242226/123282778-004d9700-d535-11eb-813b-9fdc9d330244.PNG)

# Membuat Tabel User

![1](https://user-images.githubusercontent.com/56242226/124339633-0b11c700-dbda-11eb-9075-e99bbfc5de29.PNG)

# Membuat Model User
Selanjutnya adalah membuat Model untuk memproses data Login. Buat file baru pada direktori app/Models dengan nama UserModel.php

![2](https://user-images.githubusercontent.com/56242226/124339635-0fd67b00-dbda-11eb-98b6-e7a936598a73.PNG)

# Membuat Controller User
Buat Controller baru dengan nama User.php pada direktori app/Controllers.Kemudian tambahkan method index() untuk menampilkan daftar user, dan method login() untuk proses login.

![3](https://user-images.githubusercontent.com/56242226/124339636-106f1180-dbda-11eb-9989-7693056efae7.PNG)

![3a](https://user-images.githubusercontent.com/56242226/124339637-11a03e80-dbda-11eb-8e2d-a35044e0588b.PNG)

# Membuat View Login
Buat direktori baru dengan nama user pada direktori app/views, kemudian buat file baru dengan nama login.php.

![4](https://user-images.githubusercontent.com/56242226/124339639-1238d500-dbda-11eb-9400-6da08a2364dc.PNG)

