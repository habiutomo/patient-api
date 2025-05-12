# Patient API

Patient API adalah sebuah proyek yang dibangun untuk menyediakan layanan API terkait manajemen pasien. Proyek ini menggunakan teknologi PHP dan Blade untuk mengembangkan backend yang kuat dan responsif.

## Fitur

- **Manajemen Pasien**: Tambah, ubah, hapus, dan lihat data pasien.
- **Autentikasi**: Sistem login dan registrasi untuk memastikan keamanan data.
- **RESTful API**: Endpoint yang dapat diakses untuk integrasi dengan aplikasi lain.
- **Pencarian Cepat**: Kemampuan untuk mencari data pasien dengan cepat dan efisien.

## Teknologi yang Digunakan

Proyek ini dibangun dengan menggunakan:

- **Blade**: 60.7% dari kode.
- **PHP**: 38.7% dari kode.
- **Lainnya**: 0.6%.

## Instalasi

1. Clone repository ini:
   ```bash
   git clone https://github.com/habiutomo/patient-api.git
Masuk ke direktori proyek:
bash
cd patient-api
Instal dependensi dengan Composer:
bash
composer install
Konfigurasikan file .env Anda:
Salin file .env.example menjadi .env.
Isi detail database dan pengaturan lainnya sesuai kebutuhan Anda.
Jalankan migrasi database:
bash
php artisan migrate
Jalankan server lokal:
bash
php artisan serve
Cara Penggunaan
Akses server lokal melalui browser atau aplikasi API client (seperti Postman) di alamat:

Code
http://localhost:8000
Gunakan endpoint yang tersedia untuk berinteraksi dengan API. Contoh:

GET /api/patients untuk mendapatkan daftar pasien.
POST /api/patients untuk menambahkan pasien baru.
Kontribusi
Kami sangat menghargai kontribusi Anda! Jika Anda ingin berkontribusi pada proyek ini, silakan:

Fork repository ini.
Buat branch baru untuk fitur atau perbaikan Anda:
bash
git checkout -b fitur-baru
Commit perubahan Anda:
bash
git commit -m "Menambahkan fitur baru"
Push branch Anda:
bash
git push origin fitur-baru
Buat Pull Request ke repository ini.
Lisensi
Proyek ini menggunakan lisensi MIT. Lihat file LICENSE untuk detail lebih lanjut.

Dikembangkan dengan ❤️ oleh habiutomo
