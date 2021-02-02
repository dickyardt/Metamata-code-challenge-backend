# Metamata-Challenge
Membuat media untuk berbagi cerita; website sederhana untuk membaca dan memposting cerita;

## Cara Instalasi
- Clone repository

- Install composer
```sh
$ composer install
```
- Copy .env.example dan rename menjadi .env

- Jalankan perintah 
```sh
$ php artisan key:generate
```
- Buat database baru dengan nama **homestead**

- Jalankan perintah
```sh
$ php artisan migrate
```

- Jalankan perinath
```sh
$ php artisan serve
```