# 💰 Smart Expense Tracker

<div align="center">

### Aplikasi Manajemen Keuangan Pribadi dengan Analisis Data & Machine Learning

Kelola pemasukan, pengeluaran, anggaran, target tabungan, dan analisis keuangan dalam satu aplikasi.

![Flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge\&logo=flutter\&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=for-the-badge\&logo=dart\&logoColor=white)
![NodeJS](https://img.shields.io/badge/Node.js-339933?style=for-the-badge\&logo=nodedotjs\&logoColor=white)
![Express](https://img.shields.io/badge/Express.js-000000?style=for-the-badge\&logo=express\&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge\&logo=mysql\&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge\&logo=python\&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge\&logo=scikitlearn\&logoColor=white)

</div>

---

# 📖 Tentang Proyek

**Smart Expense Tracker** adalah aplikasi manajemen keuangan pribadi yang dirancang untuk membantu pengguna mencatat pemasukan dan pengeluaran, mengelola anggaran bulanan, memantau target tabungan, serta memperoleh wawasan keuangan melalui analisis data dan Machine Learning.

Proyek ini dikembangkan oleh tim yang terdiri dari **4 anggota** dengan pembagian tugas:

* 🎨 Frontend Development
* ⚙️ Backend Development
* 🗄️ Database & DevOps
* 🤖 Data Analytics & Machine Learning

---

# ✨ Fitur Utama

## 🔐 Autentikasi

* Registrasi akun
* Login pengguna
* Logout
* JWT Authentication
* Keamanan password

---

## 💵 Manajemen Transaksi

* Tambah pemasukan
* Tambah pengeluaran
* Edit transaksi
* Hapus transaksi
* Riwayat transaksi
* Filter transaksi berdasarkan kategori dan tanggal

---

## 📊 Manajemen Anggaran

* Membuat budget bulanan
* Monitoring penggunaan budget
* Progress penggunaan anggaran
* Peringatan ketika budget hampir habis

---

## 🎯 Target Tabungan

* Membuat target tabungan
* Memantau progres tabungan
* Menentukan deadline target
* Tracking pencapaian target

---

## 📈 Dashboard Keuangan

* Total saldo saat ini
* Total pemasukan
* Total pengeluaran
* Statistik keuangan bulanan
* Ringkasan kondisi keuangan

---

## 📄 Laporan Keuangan

* Laporan bulanan
* Analisis kategori pengeluaran
* Ringkasan transaksi
* Riwayat keuangan

---

## 🤖 Fitur Machine Learning

### Prediksi Pengeluaran

Memprediksi jumlah pengeluaran bulan berikutnya berdasarkan data historis pengguna.

### Analisis Pola Pengeluaran

Menganalisis kebiasaan belanja dan pola keuangan pengguna.

### Financial Health Score

Memberikan skor kesehatan finansial berdasarkan kondisi keuangan pengguna.

### Smart Recommendation

Memberikan rekomendasi pengelolaan keuangan secara otomatis.

### Anomaly Detection

Mendeteksi pengeluaran tidak biasa atau mencurigakan.

---

# 🛠️ Teknologi yang Digunakan

| Kategori         | Teknologi             |
| ---------------- | --------------------- |
| Frontend         | Flutter, Dart         |
| Backend          | Node.js, Express.js   |
| Authentication   | JWT                   |
| Database         | MySQL                 |
| Analisis Data    | Python, Pandas, NumPy |
| Machine Learning | Scikit-Learn          |
| Version Control  | Git & GitHub          |

---

# 🏗️ Arsitektur Sistem

```text
Flutter App
     │
     ▼
Node.js + Express API
     │
     ▼
MySQL Database
     │
     ▼
Python Analytics & ML
     │
     ▼
Financial Insights & Prediction
```

---

# 📁 Struktur Repository

```text
Smart-Expense-Tracker/
│
├── frontend/
│   ├── lib/
│   ├── assets/
│   └── pubspec.yaml
│
├── backend/
│   ├── controllers/
│   ├── routes/
│   ├── middleware/
│   └── server.js
│
├── analytics/
│   ├── models/
│   ├── notebooks/
│   └── prediction.py
│
├── database/
│   ├── schema.sql
│   └── seed.sql
│
├── docs/
│
└── README.md
```

---

# 🚀 Panduan Instalasi

## Persyaratan

Pastikan perangkat telah terpasang:

* Flutter SDK
* Dart SDK
* Node.js
* MySQL
* Python 3.10+
* Git

---

# 📱 Instalasi Frontend

```bash
cd frontend

flutter pub get

flutter run
```

---

# ⚙️ Instalasi Backend

```bash
cd backend

npm install

npm run dev
```

Buat file `.env`:

```env
PORT=5000

DB_HOST=localhost
DB_USER=root
DB_PASSWORD=password
DB_NAME=smart_expense_tracker

JWT_SECRET=your_secret_key
```

---

# 🗄️ Instalasi Database

Membuat database:

```sql
CREATE DATABASE smart_expense_tracker;
```

Import schema:

```bash
mysql -u root -p smart_expense_tracker < schema.sql
```

Import data awal:

```bash
mysql -u root -p smart_expense_tracker < seed.sql
```

---

# 🤖 Instalasi Modul Machine Learning

Install dependency Python:

```bash
cd analytics

pip install pandas numpy scikit-learn matplotlib
```

Menjalankan model prediksi:

```bash
python prediction.py
```

---

# ▶️ Menjalankan Proyek

### Menjalankan Backend

```bash
cd backend
npm run dev
```

### Menjalankan Frontend

```bash
cd frontend
flutter run
```

### Menjalankan Modul Analitik

```bash
cd analytics
python prediction.py
```

---

# 📡 Gambaran API

## Authentication

```http
POST /api/auth/register
POST /api/auth/login
```

## Transaksi

```http
GET /api/transactions
POST /api/transactions
PUT /api/transactions/:id
DELETE /api/transactions/:id
```

## Budget

```http
GET /api/budgets
POST /api/budgets
PUT /api/budgets/:id
```

## Target Tabungan

```http
GET /api/goals
POST /api/goals
```

## Analitik

```http
GET /api/analytics
GET /api/predictions
```

---

# 🧠 Modul Machine Learning

Modul Machine Learning bertugas untuk:

* Memprediksi pengeluaran bulan berikutnya
* Menghitung Financial Health Score
* Menganalisis pola pengeluaran pengguna
* Memberikan rekomendasi keuangan
* Mendeteksi transaksi yang tidak biasa

---

# 📸 Tampilan Aplikasi

## Dashboard

> Screenshot dashboard akan ditambahkan di sini.

## Halaman Transaksi

> Screenshot halaman transaksi akan ditambahkan di sini.

## Analisis Keuangan

> Screenshot analisis keuangan akan ditambahkan di sini.

## Prediksi Pengeluaran

> Screenshot fitur prediksi akan ditambahkan di sini.

---

# 🗺️ Roadmap Pengembangan

## Versi 1.0

* [x] Login & Register
* [x] Manajemen Transaksi
* [x] Budget Bulanan
* [x] Target Tabungan

## Versi 1.1

* [ ] Laporan Keuangan
* [ ] Notifikasi
* [ ] Export PDF

## Versi 2.0

* [ ] AI Recommendation yang lebih cerdas
* [ ] OCR Scan Struk Belanja
* [ ] Integrasi Rekening Bank
* [ ] Dukungan Multi Mata Uang

---

# 👥 Tim Pengembang

| Posisi                     | Tanggung Jawab                        |
| -------------------------- | ------------------------------------- |
| Frontend Developer         | Flutter UI, Dashboard, Authentication |
| Backend Developer          | REST API, Business Logic              |
| Database & DevOps Engineer | Database, Deployment, CI/CD           |
| Data Analyst & ML Engineer | Analisis Data, Prediksi, AI           |

---

# 🔄 Alur Pengembangan Git

## Strategi Branch

```text
main
│
├── frontend
├── backend
├── database
└── analytics
```

### Workflow

1. Membuat branch fitur
2. Melakukan pengembangan
3. Commit perubahan
4. Push ke GitHub
5. Membuat Pull Request
6. Code Review
7. Merge ke branch utama

---

# 🤝 Kontribusi

Kontribusi sangat terbuka untuk pengembangan proyek ini.

Langkah-langkah:

```bash
git checkout -b feature/nama-fitur
git commit -m "Menambahkan fitur baru"
git push origin feature/nama-fitur
```

Kemudian buat Pull Request untuk proses review.

---

# 📜 Lisensi

Proyek ini menggunakan lisensi **MIT License**.

Silakan lihat file `LICENSE` untuk informasi lebih lanjut.

---

# 🌟 Ucapan Terima Kasih

Terima kasih kepada:

* Flutter Community
* Node.js Community
* Scikit-Learn Community
* Open Source Contributors

---

<div align="center">

### 💰 Smart Expense Tracker

Dibangun menggunakan Flutter, Node.js, MySQL, dan Machine Learning.

**Kelola Keuangan Lebih Cerdas, Lebih Mudah, dan Lebih Terarah.**

</div>
