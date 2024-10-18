
## Cara Menjalankan Aplikasi Laravel

1. Jalankan proses build front-end:
   ```bash
   npm run dev
   ```

2. Buka terminal baru dan jalankan perintah untuk memulai server:
   ```bash
   php artisan serve
   ```

3. Buka browser dan akses aplikasi pada alamat yang ditampilkan (biasanya `http://127.0.0.1:8000`).

4. Setelah halaman Laravel default muncul, pilih login jika sudah memiliki akun atau register untuk membuat akun baru.

5. Setelah berhasil login atau register, dashboard toko akan muncul dengan pesan "kamu telah login."

6. Masuk ke halaman produk, di mana terdapat 3 data dummy dari seeder.

7. Jika ingin menambah produk, klik tombol "Tambah" di pojok kiri atas. Isi form yang muncul untuk produk baru, lalu klik "Kirim" saat selesai.

8. Produk berhasil ditambahkan, dan akan muncul pesan di bawah logo.

9. Untuk mengedit produk, tekan tombol "Edit" di bawah produk, ubah data sesuai keinginan, lalu klik "Kirim." Pesan berhasil akan muncul di bawah logo.

10. Untuk menghapus produk, masuk ke halaman edit produk dan klik tombol "Delete" di pojok kanan atas, lalu konfirmasi penghapusan. Pesan berhasil dihapus akan muncul di bawah logo.

11. Anda juga dapat mencari produk dengan mengetik nama produk di input search, dan hasil pencarian akan menampilkan produk yang sesuai.

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

