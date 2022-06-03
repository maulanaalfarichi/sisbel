# sisbel - Sistem Belajar (Laravel)
Langkah :
1. import "db_laravel" ke database sever kalian. setting koneksi database pada "app > config > database.php", sesuaikan.
2. copy file "basic_laravel4" ke web server kalian. untuk membuka aplikasi, buka browser > ketik "http://localhost/basic_laravel4/public".
3. isi password dan username masing-masing "admin".
4. selamat menikmati.. enjoy.

NB:
- Aplikasi ini menggunakan Way Generator untuk mempermudah kita dalam menggunakan laravel. 

composer.json > require:
1. "way/generators": "dev-master"
2. "binarix/foundation-pagination": "dev-master"

app.php > providers :
1. 'Way\Generators\GeneratorsServiceProvider'
2. 'Binarix\FoundationPagination\FoundationPaginationServiceProvider'
