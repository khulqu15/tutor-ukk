[<img src="public/image/dev/banner.png" width="70%" style="margin-left:15%">](https://sidescript.id)

# Tutorial UKK - 12 RPL SMKN 1 Purwosari

> Tutorial UKK / Tugas Akhir dengan Studi Kasus website online shop dengan nama **Jualin**

Clone Project "Tutorial UKK" caranya buka terminal lalu masuk ke xampp/htdocs.

```console
cd C://xampp/htdocs
```
Lalu clone repositori github dengan cara mengetik command (Pastikan kamu punya akun github terlebih dahulu). apabila tidak kamu bisa daftar github disini [Signup Github](https://github.com/signup) 

```console
git clone https://github.com/khulqu15/tutor-ukk
```

Setelah itu, install composer laravel terlebih dahulu agar laravel bisa digunakan (Pastikan koneksi kalian stabil), dengan command dibawah ini.

```console
composer install
```

Ketika sudah diinstall, untuk memastikan depedensi kalian sudah autoload, jalankan command dibawah ini

```console
composer dump-autoload
```

Generate environment aplikasi kalian, dengan command dibawah ini

```console
php artisan key:generate
```

### **Buat database baru di phpmyadmin dengan nama "Jualin"**

lalu ganti environtment database project kalian, dengan membuka file .env (kalau tidak ada, buat file baru dengan nama .env, copy isi dari file .env.example ke file baru .env),

```php
DB_DATABASE=Jualin
```

Gunakan fitur migration pada laravel dengan menggunakan command

```console
php artisan migrate:fresh
```

Agar data tidak kosong, kalian bisa gunakan fitur seeder dengan menggunakan command

```console
php artisan db:seed
```
----------
## **Developed by**
#Silahkan DM saya untuk tanya kalau ada error, Klik gambar dibawah ini.

[<img src="public/image/dev/dev.png" width="400px">](https://instagram.com/khulqu.py)
