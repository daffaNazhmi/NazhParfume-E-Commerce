<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://github.com/user-attachments/assets/398ef60d-ec5d-4bd6-8b0e-261eecf63b72" width="800" alt="Laravel Logo"></a></p>

## Tentang NazhParfume-E-Commerce

Folder ini berisikan tentang website penjualan parfum menggunakan laravel 11. Didalamnya sudah terdapat fitur authentikasi dan sudah terintegrasi login dengan google, lalu ada fitur keranjang, detail parfum dan profil checkout dimana semua fitur yang sudah terkoneksi dengan database mysql. Desain NazhParfume-E-Commerce sangat sederhana sehingga penonton atau pelihat tidak kesulitan melihatnya. How to use :

- Buka git bash / terminal lalu clone repo ini : git clone https://github.com/daffaNazhmi/NazhParfume-E-Commerce.git
- impor database db_nazhparfumelaravel.sql (ada di github ini)
- Jalankan migration : php artisan migrate
- Install folder vendor : composer install
- Tambahkan di file .env : DB_DATABASE=db_nazhparfumelaravel
- Jalankan : php artisan serve
