
## Cara Menjalankan Aplikasi Laravel

1. Jalankan perintah berikut untuk menginstall dependencies:
   ```bash
   composer install
   npm install

2. Copy file `.env.example` dan rename menjadi `.env`:
   ```bash
   .env.example copy paste, Lalu copy tadi Rename Menjadi .env
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

10. Buka browser dan akses aplikasi pada alamat yang ditampilkan (biasanya `(http://127.0.0.1:8000)`).

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


