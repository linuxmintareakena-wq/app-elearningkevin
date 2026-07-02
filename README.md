# 📚 E-Learning IT&DPK

Sistem E-Learning modern yang dirancang untuk mempermudah manajemen materi pembelajaran dan tugas siswa. Dibangun dengan fokus pada efisiensi, keamanan, dan pengalaman pengguna yang responsif.

## 🚀 Fitur Utama

- **Dashboard Admin:** Kelola data siswa, materi, dan tugas dalam satu panel kendali yang intuitif.
- **Manajemen Siswa:** CRUD data siswa yang cepat dan terintegrasi.
- **Pusat Materi:** Akses materi pembelajaran (PDF) dengan *viewer* yang ramah mobile.
- **Pengumpulan Tugas:** Sistem upload tugas yang terstruktur dengan notifikasi status pengerjaan.
- **Responsif & Aman:** Desain antarmuka *Metro-inspired* yang berjalan lancar di berbagai perangkat serta proteksi akses tingkat lanjut.

## 🛠️ Teknologi yang Digunakan

- **Backend:** PHP (Native/PDO)
- **Frontend:** Bootstrap 5, FontAwesome
- **Database:** MySQL
- **Keamanan:** Session-based authentication & .htaccess protection

## 📂 Struktur Folder

```text
/
├── assets/          # CSS, JS, dan file upload materi
├── config/          # Koneksi database & konfigurasi sistem
├── admin/           # Halaman manajemen admin (CRUD)
├── siswa/           # Panel dashboard & tugas siswa
├── .htaccess        # Konfigurasi keamanan server
└── README.md        # Dokumentasi aplikasi

# 📚 E-Learning IT&DPK

Sistem E-Learning modern yang dirancang untuk mempermudah manajemen materi pembelajaran dan tugas siswa. Dibangun dengan fokus pada efisiensi, keamanan, dan pengalaman pengguna yang responsif.

## 🚀 Fitur Utama

- **Dashboard Admin:** Kelola data siswa, materi, dan tugas dalam satu panel kendali yang intuitif.
- **Manajemen Siswa:** CRUD data siswa yang cepat dan terintegrasi.
- **Pusat Materi:** Akses materi pembelajaran (PDF) dengan *viewer* yang ramah mobile.
- **Pengumpulan Tugas:** Sistem upload tugas yang terstruktur dengan notifikasi status pengerjaan.
- **Responsif & Aman:** Desain antarmuka *Metro-inspired* yang berjalan lancar di berbagai perangkat serta proteksi akses tingkat lanjut.

## 🛠️ Teknologi yang Digunakan

- **Backend:** PHP (Native/PDO)
- **Frontend:** Bootstrap 5, FontAwesome
- **Database:** MySQL
- **Keamanan:** Session-based authentication & .htaccess protection

## 📂 Struktur Folder

```text
/
├── assets/          # CSS, JS, dan file upload materi
├── config/          # Koneksi database & konfigurasi sistem
├── admin/           # Halaman manajemen admin (CRUD)
├── siswa/           # Panel dashboard & tugas siswa
├── .htaccess        # Konfigurasi keamanan server
└── README.md        # Dokumentasi aplikasi

```

## 🔐 Proteksi Keamanan

Aplikasi ini dilengkapi dengan lapisan keamanan:

1. **Session Auth:** Membatasi akses berdasarkan role (Admin/Siswa).
2. **Directory Security:** Mencegah *directory listing* dan akses file sensitif (.env, .sql, .inc).
3. **Custom Error Handling:** Halaman *forbidden* kustom untuk akses yang tidak sah.

## 📝 Lisensi

Proyek ini dibuat untuk kebutuhan internal IT&DPK. Hak cipta dilindungi.

---

*Dibuat dengan semangat untuk pendidikan yang lebih baik.*
