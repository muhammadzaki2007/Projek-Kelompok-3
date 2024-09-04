# Nama Proyek

Projek Toko Roti SC Smoothies Cookie Shoop.

# Nama Kelompok

Kelompok 3

# Anggota

1. Muhammad Zaki
2. Muhammad najhan nazala lukman
3. Ratih Aulia
4. Gadis Arivia
5. Era Suci
6. Cagiva Nur Stella
7. Shania Amalia Mirza

# Kontribusi

- Muhammad Zaki(be): 95%
- Shania Amalia(fe): 95%
- Ratih Aulia(fe): 20%
- Gadis Arivia(fe): 20%
- Muhammad Najhan(be):20%
- Era Suci(fe): 20%
- Cagiva Nur Stella(fe): 20%


# Toko Roti Kering

Proyek ini adalah aplikasi web untuk toko roti kering yang dikembangkan menggunakan **React.js** di sisi Front-End (FE) dan **Node.js** di sisi Back-End (BE).

## Teknologi yang Digunakan

### Front-End (FE)
- **React.js**: Framework JavaScript yang digunakan untuk membangun antarmuka pengguna yang interaktif.
- **React Router**: Digunakan untuk navigasi halaman di dalam aplikasi.
- **Axios**: Library untuk melakukan HTTP request ke server BE.
- **DaisyUL** : untuk stylesheet.
- **Bootstrap/Tailwind CSS**: Framework CSS untuk mendesain antarmuka yang responsif.

### Back-End (BE)
- **Node.js**: JavaScript runtime di server-side untuk menangani request dari FE.
- **Express.js**: Framework untuk membangun API RESTful yang menangani CRUD operation.
- **MySQL PHP MyAdmin**: Database untuk menyimpan data produk, pesanan, dan pengguna.
- **Mongoose/Sequelize**: ORM (Object-Relational Mapping) untuk MongoDB/MySQL yang mempermudah interaksi dengan database.
- **JWT (JSON Web Token)**: Untuk autentikasi pengguna.
- **bcrypt**: Library untuk mengenkripsi password pengguna.
- **Postman**: untuk test API

## Fitur

### Front-End (FE)
- **Halaman Beranda**: Menampilkan daftar produk roti kering.
- **Detail Produk**: Informasi lengkap tentang setiap produk.
- **Keranjang Belanja**: Fitur untuk menambah produk ke keranjang belanja.
- **Proses Checkout**: Formulir untuk menyelesaikan pembelian dan memasukkan detail pengiriman.
- **Autentikasi Pengguna**: Registrasi dan login pengguna.
- **Halaman About**: menjelaskan tentang aplikasi kami
- **Halaman kontak**: untuk menghubungi kami selaku admin

### Back-End (BE)
- **API Produk**: CRUD operation untuk produk roti kering.
- **API Transaksi** (opsional): Integrasi dengan gateway pembayaran untuk memproses pembayaran.

## Cara Menjalankan Proyek

### Persyaratan
- **Node.js** v14.x atau lebih baru.
- **npm** atau **yarn** sebagai package manager.
- **MySQL PHP MyAdmin** untuk database.
- **Postman** untuk test API

### Langkah-langkah

1. **Clone repository ini**:
   ```bash
   git clone https://github.com/username/toko-roti-kering.git
   cd toko-roti-kering

2. **Install dependesi untuk BE dan FE**

   # Untuk Back-End
cd backend
npm install

# Untuk Front-End
cd ../frontend
npm install

3. **Konfigurasi file environment:**
a. Buat file .env di direktori backend dan isi dengan variabel-variabel yang diperlukan (contoh: DB_URI, JWT_SECRET, dll).
b. Untuk Front-End, buat file .env di direktori frontend jika diperlukan.
   
4. **Menjalankan Back-End:**   
cd backend
npm start

5. **Menjalankan Front-End:**
cd frontend
npm start

6. **Akses Aplikasi:**

a. Front-End akan berjalan di http://localhost:3000.
b. Back-End akan berjalan di http://localhost:5000 atau port yang dikonfigurasi.

## Struktur direktori

 toko-roti-kering/

├── backend/        # Kode untuk Back-End (Node.js, Express, Database)
├── frontend/       # Kode untuk Front-End (React.js)
├── README.md       # Catatan proyek ini
└── .gitignore      # File dan direktori yang tidak dilacak oleh Git

## Kontribusi
Jika Anda ingin berkontribusi pada proyek ini, silakan buat pull request atau issue di repository ini.

## Lisensi
Proyek ini dilisensikan di bawah MIT License.

Catatan ini mencakup deskripsi umum tentang teknologi yang digunakan, fitur yang disediakan oleh Front-End dan Back-End, cara menjalankan proyek, serta informasi tambahan lainnya. Kamu bisa menyesuaikan catatan ini sesuai dengan kebutuhan proyekmu.
