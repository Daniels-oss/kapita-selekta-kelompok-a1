# EMR RS Pratama Teluk Biru - Kelompok A1

Repositori ini berisi purwarupa aplikasi *Electronic Medical Record* (EMR) berbasis web untuk RS Pratama Teluk Biru (Rumah Sakit Tipe D). Proyek ini merupakan tugas akhir mata kuliah Kapita Selekta Jalur A (Sistem Informasi).

## 👥 Anggota Kelompok (A1)
- **Muh Ammar Faiqsyah** (Koordinator & Penulis)
- **Khusnul Khatimah** (Analis Kasus)
- **Muh Alghifari** (Perancang UI/UX)
- **Muhammad Luthfi Sam** (Pengembang & Penguji)

## 🎯 Tujuan Proyek
Membangun sistem EMR yang mampu:
1. Mencegah pendaftaran nomor rekam medis ganda dengan pencarian validasi NIK.
2. Memfasilitasi pencatatan keluhan, diagnosis berstandar ICD-10, dan tindakan klinis.
3. Mempercepat dokter dalam menelusuri riwayat kunjungan pasien secara instan.
4. (Nilai Tambah) Mengotomatisasi laporan jumlah kunjungan secara *real-time*.

## 🛠️ Teknologi & Versi yang Digunakan
- **Frontend:** React.js (Vite)
- **Database & Auth:** Firebase Firestore & Firebase Authentication
- **Linting:** ESLint

## 🗂️ Sumber Data
**Peringatan Etika Data:** 
Seluruh data yang digunakan dalam sistem ini (data pasien dan data kunjungan) adalah **100% DATA FIKTIF / SINTETIS**. Tidak ada data identitas pasien nyata yang digunakan, dimasukkan, maupun disimpan di dalam repositori atau basis data aplikasi ini. Kode ICD-10 menggunakan standar publik dasar.

## 🚀 Cara Menjalankan Proyek Secara Lokal
Ikuti langkah berikut untuk menjalankan aplikasi:

1. Kloning repositori ini:
   `git clone https://github.com/username-kamu/nama-repo-kamu.git`
2. Masuk ke direktori proyek:
   `cd emr-rs-teluk-biru`
3. Unduh semua dependensi:
   `npm install`
4. Jalankan server lokal:
   `npm run dev`
5. Buka peramban (*browser*) dan akses tautan lokal yang diberikan (biasanya `http://localhost:5173`).

*(Catatan: Konfigurasi akses database Firebase sudah diatur untuk tahap pengembangan. Tidak ada API Key krusial yang dipublikasikan secara berbahaya)*