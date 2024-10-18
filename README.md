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

10. Buka browser dan akses aplikasi pada alamat yang ditampilkan (biasanya `http://127.0.0.1:8000`).

11. Setelah halaman Laravel default muncul, pilih login jika sudah memiliki akun atau register untuk membuat akun baru.

12. Setelah berhasil login atau register, dashboard toko akan muncul dengan pesan "kamu telah login."

13. Masuk ke halaman produk, di mana terdapat 3 data dummy dari seeder.

14. Jika ingin menambah produk, klik tombol "Tambah" di pojok kiri atas. Isi form yang muncul untuk produk baru, lalu klik "Kirim" saat selesai.

15. Produk berhasil ditambahkan, dan akan muncul pesan di bawah logo.

16. Untuk mengedit produk, tekan tombol "Edit" di bawah produk, ubah data sesuai keinginan, lalu klik "Kirim." Pesan berhasil akan muncul di bawah logo.

17. Untuk menghapus produk, masuk ke halaman edit produk dan klik tombol "Delete" di pojok kanan atas, lalu konfirmasi penghapusan. Pesan berhasil dihapus akan muncul di bawah logo.

18. Anda juga dapat mencari produk dengan mengetik nama produk di input search, dan hasil pencarian akan menampilkan produk yang sesuai.

## Cara Uji Coba Aplikasi

1. Buka terminal di VSCode dan ketik perintah berikut untuk mengetes seluruh fitur aplikasi:
   ```bash
   php artisan test
   ```

2. Jika hanya ingin menguji fitur CRUD, jalankan perintah:
   ```bash
   php artisan test --filter=ProdukTest
   ```
```



