MVC_buku_109062500053

# MVC PHP Native - Data Buku

Aplikasi CRUD sederhana untuk mempelajari pola Model-View-Controller pada PHP Native dengan tema Manajemen Data Buku.

## Kebutuhan
- PHP 8.0 atau lebih baru
- MySQL/MariaDB
- Web server lokal seperti XAMPP atau Laragon
- Git

## Instalasi
1. Clone atau salin project ke folder web server (`C:\laragon\www\MVC_buku`).
2. Import `database/perpustakaan.sql` ke database MySQL.
3. Sesuaikan koneksi pada `config/database.php`.
4. Buka `http://localhost/MVC_buku/public/index.php`.

## Struktur MVC
- `app/models/` : akses dan operasi data buku.
- `app/controllers/` : alur request dan pemanggilan Model/View.
- `app/views/` : tampilan HTML.
- `config/` : konfigurasi koneksi database.
- `database/` : skema dan data awal SQL.
- `public/` : entry point aplikasi.

## Fitur
- Menampilkan data buku
- Menambah data buku
- Mengubah data buku
- Menghapus data buku

## Histori Git
* 7057f3d (HEAD -> main) feat: add complete CRUD routing
* b818c24 feat: add complete student CRUD views
* 685bfad feat: add complete student CRUD controller
* a3bfa9f feat: add complete student CRUD model
* 0bf8567 feat: add PDO database connection
* caf8366 chore: initialize mvc php native project
* 25f1b9b feat: add student database schema and seed data
* 281c5bc chore: initialize mvc php native project