# PBO 2 - Proyek 1 (Laravel)

Nama: Sukma Sastra Wijaya
NIM: 2410010462
Kelas: 5B Ti Reg BJB

## Deskripsi
Proyek 1 mata kuliah PBO 2 mengikuti materi pada repository 
(https://github.com/mirzayogy/laravel5a), berisi pembuatan proyek Laravel 13,
koneksi MySQL, model/migration/seeder Periode, dan template AdminLTE.

## Teknologi
- PHP 8.3
- Laravel 13.35.0
- MySQL (Laragon)
- AdminLTE 4 (public/dist)

## Cara Menjalankan
```
composer install
copy .env.example .env
php artisan key:generate
```
Atur koneksi database di `.env` (DB_DATABASE=db_pbo2_5b), buat databasenya, lalu:
```
php artisan migrate:fresh --seed
php artisan serve
```
Buka http://127.0.0.1:8000

## Struktur yang Dikerjakan
- `app/Models/Periode.php`
- `database/migrations/..._create_periodes_table.php`
- `database/seeders/PeriodeSeeder.php`
- `public/dist` (template AdminLTE)
