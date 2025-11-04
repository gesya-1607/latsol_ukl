# latsol_ukl
# Aplikasi Presensi Online

## 📌 Deskripsi Singkat
Aplikasi ini merupakan **RESTful API** untuk sistem **Presensi Online**, dibuat menggunakan **NestJS** (framework Node.js).  
API ini memungkinkan pengguna (siswa atau karyawan) untuk:
- melakukan login menggunakan token (JWT),
- mencatat kehadiran (check-in/check-out),
- dan mengelola data pengguna.

Proyek ini dikembangkan sebagai bagian dari **latihan dan evaluasi kesiapan UKL**.

---

## Fitur Utama
1. **Manajemen Pengguna**
   - Tambah, ubah, hapus, dan lihat data pengguna (siswa/karyawan).
   - Setiap pengguna memiliki `id`, `nama`, `email`, dan `password`.

2. **Autentikasi (JWT Token)**
   - Login menggunakan email dan password.
   - Mendapatkan token untuk mengakses endpoint presensi.

3. **Presensi Harian**
   - Pengguna dapat melakukan **check-in** dan **check-out**.
   - Data kehadiran otomatis mencatat waktu dan tanggal.

4. **Keamanan**
   - Semua endpoint presensi dilindungi dengan **token autentikasi (Bearer Token)**.
