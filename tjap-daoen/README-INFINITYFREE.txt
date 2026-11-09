PANDUAN HOSTING TJAP DAON DI INFINITYFREE

1. Buat akun/domain di InfinityFree.
2. Buka Control Panel > MySQL Databases, lalu buat database baru.
3. Catat MySQL Hostname, MySQL Database Name, MySQL Username, dan password database.
4. Edit config/database.php dan ganti 4 nilai contoh dengan data dari panel. Jangan gunakan localhost atau username root.
5. Buka Online File Manager atau FTP. Masuk ke folder htdocs.
6. Upload ISI folder tjap-daoen (bukan folder luarnya) ke htdocs. Pastikan index.php berada langsung di htdocs/index.php.
7. Buka phpMyAdmin dari panel InfinityFree. Pilih database yang baru dibuat.
8. Klik Import, pilih database.sql, lalu jalankan import.
9. Buka domain website untuk mengecek halaman utama, produk, detail, kontak, dan admin.

LOGIN ADMIN AWAL
Username: admin
Password: admin123
Segera ganti password setelah berhasil masuk. Jangan bagikan kredensial database.

CATATAN
- Database harus dibuat dari panel InfinityFree terlebih dahulu.
- File SQL ini tidak membuat database baru; import saat database yang benar sudah dipilih.
- Jika upload dilakukan ke subfolder, link website perlu disesuaikan lagi. Paket ini disiapkan untuk upload langsung ke htdocs.
