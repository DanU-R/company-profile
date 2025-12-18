# Company Profile Project

<p align="center">
  <img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="300" alt="Laravel Logo">
</p>

Aplikasi Web Company Profile yang dibangun menggunakan framework **Laravel**. Proyek ini dirancang untuk menyediakan informasi profil perusahaan secara dinamis, profesional, dan responsif.

## 🚀 Fitur Utama
- **Landing Page**: Halaman depan yang menarik untuk menampilkan ringkasan perusahaan.
- **Tentang Kami**: Informasi detail mengenai visi, misi, dan sejarah perusahaan.
- **Layanan/Produk**: Menampilkan daftar layanan atau produk yang ditawarkan.
- **Galeri/Portfolio**: Menampilkan foto kegiatan atau proyek yang telah diselesaikan.
- **Kontak**: Formulir atau informasi kontak untuk memudahkan klien menghubungi perusahaan.
- **Admin Panel**: (Opsional) Manajemen konten melalui dashboard admin.

## 🛠️ Teknologi yang Digunakan
- **Framework:** [Laravel 10.x](https://laravel.com) (atau sesuaikan dengan versi Anda)
- **Database:** MySQL
- **Frontend:** Bootstrap / Tailwind CSS (pilih salah satu)
- **Icons:** FontAwesome / Heroicons

## 💻 Cara Instalasi

Ikuti langkah-langkah berikut untuk menjalankan proyek di komputer lokal Anda:

1. **Clone repositori ini:**
git clone [https://github.com/DanU-R/company-profile.git](https://github.com/DanU-R/company-profile.git)
   cd company-profile
2. Instal dependesi PHP
composer install
3. Instal dependensi Frontend (NPM)
npm install && npm run dev
4. Salin file .env
cp .env.example .env
5. Generate Application Key
php artisan key:generate
6. Konfigurasi Database: Buka file .env dan sesuaikan DB_DATABASE, DB_USERNAME, dan DB_PASSWORD dengan database lokal Anda.
7. Jalankan Migrasi & Seeder
php artisan migrate --seed
8. Jalankan Server
php artisan migrate --seed
Akses di browser: http://localhost:8000

📄 Lisensi

Proyek ini bersifat open-source dan berada di bawah lisensi MIT
