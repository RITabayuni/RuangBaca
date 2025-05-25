# 📚 Digital Library - Laravel Project

<p align="center">
  <a href="https://laravel.com" target="_blank">
    <img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo">
  </a>
</p>

## 📖 Tentang Proyek

Proyek ini merupakan sistem digitalisasi perpustakaan berbasis web yang terinspirasi dari **RuangBaca FILKOM UB**. Dibuat dengan Laravel, sistem ini memungkinkan pengguna untuk melihat dan meminjam buku secara online, sesuai dengan peran pengguna masing-masing.

### 🎭 Jenis Pengguna

- **Admin**  
  Mengelola buku (tambah, edit, hapus) dan mengelola data peminjaman.

- **Login User (Member)**  
  Melihat daftar buku dan melakukan peminjaman.

- **Guest (Tanpa Login)**  
  Hanya dapat melihat daftar buku tanpa fitur peminjaman.

## 🚀 Fitur Utama

- 🔐 Autentikasi (login & register)
- 📚 CRUD Buku (admin)
- 📥 Peminjaman Buku (member)
- 👀 Daftar Buku (guest & member)
- 🔒 Hak akses berdasarkan role
- 📥 WaitingList Buku (member)
- 📥 Pengembalian Buku (member)

## 🛠️ Teknologi yang Digunakan

- Laravel 10.x
- Blade Template Engine
- MySQL / MariaDB
- Bootstrap / TailwindCSS (jika digunakan)
- Laravel Breeze / Jetstream (jika autentikasi dipakai)

## ⚙️ Instalasi

```bash
git clone https://github.com/username/nama-project.git
cd nama-project
composer install
cp .env.example .env
php artisan key:generate
# Konfigurasi database di file .env
php artisan migrate
php artisan serve
