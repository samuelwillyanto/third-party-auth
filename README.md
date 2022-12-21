# third-party-auth

File ini menggunakan Google Authenticator

Dalam project ini, user dapat melakukan reset password dengan verifikasi email (link reset password dikirimkan ke email pengguna) menggunakan mailtrap.io



Langkah instalasi File

1.  Buat database pada xampp admin dengan nama auth

2. Lakukan instalasi file vendor laravel kembali
composer update

3. Jalankan instalasi Laravel UI
composer require laravel/ui --dev

4. Jalankan instalasi Laravel Authentication
php artisan ui bootstrap --auth

5. Jalankan instalasi npm dan compile asset file (perlu instalasi node.js)
npm install && npm run dev

6. Lakukan migrate seluruh tabel yang ada
php artisan migrate

7. Jalankan pada localhost
php artisan serve
