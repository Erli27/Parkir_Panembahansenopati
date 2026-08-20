# 🏥 Sistem Informasi Manajemen RSUD (Parkir & Manajemen Pengguna)

Proyek berbasis web PHP Native untuk mengelola sistem di lingkungan RSUD, yang mencakup manajemen parkir, pengelolaan pengguna, autentikasi, serta pencatatan aktivitas (log). 
wireframe/mockup ui, ux design (user experirnce), flowchart/userflow & erd & basis data : https://erli27.github.io/muckupui/

---

## 📂 Struktur Direktori & File

Berikut adalah daftar file utama yang terdapat di dalam direktori proyek `C:\xampp\htdocs\rsud`:

* **`index.php`** : Halaman utama atau titik masuk (entry point) aplikasi.
* **`form_login.php`** : Halaman antarmuka untuk proses masuk/login pengguna.
* **`aksi_login.php`** : Skrip backend untuk memproses autentikasi dan validasi login.
* **`logout.php`** : Skrip untuk mengakhiri sesi pengguna (logout).
* **`cek_db`** : Berkas untuk melakukan pengecekan koneksi atau status basis data.
* **`koneksi.php`** : Berkas konfigurasi utama untuk menghubungkan aplikasi dengan database MySQL.

### 👥 Manajemen Pengguna & Hak Akses
* **`form_daftar.php`** : Halaman pendaftaran akun baru.
* **`crud_user.php`** : Pengelolaan data pengguna (Create, Read, Update, Delete).
* **`edit_user.php`** : Halaman untuk mengubah data pengguna tertentu.
* **`hapus_user.php`** : Skrip backend untuk menghapus data pengguna dari sistem.

### 📊 Dashboard Berdasarkan Peran (Role)
* **`dashboard_admin.php`** : Tampilan panel kendali khusus untuk Administrator.
* **`dashboard_owner.php`** : Tampilan panel kendali khusus untuk Pemilik/Owner.
* **`dashboard_user.php`** : Tampilan panel kendali untuk pengguna biasa.
* **`dashboard_parkir.php`** : Tampilan panel kendali khusus untuk manajemen sistem parkir.

### 🚗 Modul Parkir & Kendaraan
* **`area_slot.php`** : Pengaturan atau pemantauan area dan slot parkir.
* **`kendaraan.php`** : Pengelolaan data kendaraan yang masuk dan keluar.
* **`cetak_karcis.php`** : Fitur untuk mencetak karcis parkir.

### ⚙️ Utilitas & Pendukung Lainnya
* **`crud_tarif.php`** : Pengaturan tarif layanan/parkir.
* **`log_aktifitas.php`** : Pencatatan riwayat aktivitas pengguna di dalam sistem.

---

## 🚀 Cara Instalasi & Menjalankan Proyek

1. Pastikan Anda telah menginstal **XAMPP** di komputer Anda.
2. Salin (copy) folder `rsud` ini direktori `C:\xampp\htdocs\`.
3. Nyalakan layanan **Apache** dan **MySQL** melalui XAMPP Control Panel.
4. Buat database baru di phpMyAdmin (sesuaikan dengan nama yang terpanggil di `koneksi.php`).
5. Impor file database SQL yang dibutuhkan (jika tersedia).
6. Buka peramban (browser) dan akses melalui tautan:
   `http://localhost/rsud/`# Parkir_Panembahansenopati
