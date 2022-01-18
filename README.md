# Tutorial UKK - 12 RPL SMKN 1 Purwosari
Clone Project "Tutorial UKK" caranya buka terminal lalu masuk ke xampp/htdocs.

```console
$ cd C://xampp/htdocs
```
Lalu clone repositori github dengan cara mengetik command (Pastikan kamu punya akun github terlebih dahulu). apabila tidak kamu bisa daftar github disini [Signup Github](https://github.com/signup) 

```console
$ git clone https://github.com/khulqu15/tutor-ukk
```

Setelah itu, install composer laravel terlebih dahulu agar laravel bisa digunakan (Pastikan koneksi kalian stabil), dengan command dibawah ini.

```console
$ composer install
```

Ketika sudah diinstall, untuk memastikan depedensi kalian sudah autoload, jalankan command dibawah ini

```console
$ composer dump-autoload
```

Generate environment aplikasi kalian, dengan command dibawah ini

```console
$ php artisan key:generate
```

``
