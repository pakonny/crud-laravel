Berikut adalah **README.md** yang menarik dan sesuai dengan perintah Anda untuk dokumentasi proyek Laravel di GitHub:

```markdown
<p align="center">
    <a href="https://laravel.com" target="_blank">
        <img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo">
    </a>
</p>

<p align="center">
    <a href="https://github.com/laravel/framework/actions"><img src="https://github.com/laravel/framework/workflows/tests/badge.svg" alt="Build Status"></a>
    <a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
    <a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
    <a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

## Cara Menjalankan Aplikasi Laravel

1. Jalankan perintah berikut untuk menginstall dependencies:
   ```bash
   composer install
   npm install
   ```

2. Copy file `.env.example` dan rename menjadi `.env`:
   ```bash
   cp .env.example .env
   ```

3. Konfigurasi database di file `.env` dengan menggunakan MySQL, sesuaikan nama database sesuai keinginan.

4. Pastikan server Laragon berjalan.

5. Jalankan perintah untuk membuat aplikasi key:
   ```bash
   php artisan key:generate
   ```

6. Buat link penyimpanan untuk produk image:
   ```bash
   php artisan storage:link
   ```

7. Lakukan migrasi database:
   ```bash
   php artisan migrate
   ```

8. Jalankan proses build front-end:
   ```bash
   npm run dev
   ```

9. Buka terminal baru dan jalankan perintah untuk memulai server:
   ```bash
   php artisan serve
   ```

10. Buka browser dan akses aplikasi pada alamat yang ditampilkan (biasanya `http://localhost:8000`).

## Cara Uji Coba CRUD

1. Buka terminal baru di VSCode atau terminal lainnya.

2. Jalankan perintah untuk melakukan semua test:
   ```bash
   php artisan test
   ```

3. Jika hanya ingin menjalankan test CRUD, gunakan perintah:
   ```bash
   php artisan test --filter=ProdukTest
   ```

```
