# 📘 Dokumentasi Panduan Penggunaan Sistem LMS e-Academy

Dokumen ini menjelaskan panduan penggunaan sistem LMS e-Academy untuk dua jenis pengguna utama:

- **Admin (TC, Tim IT)**
- **User (Karyawan / Peserta Pelatihan)**

---

## 🌐 Akses Sistem

![Halaman Login](./docs/images/login-page.png)

- **URL Login:**  
  https://pgieacademy.com/login

---

# 👨‍💻 ROLE: ADMIN (TC, Tim IT)

Admin bertanggung jawab dalam pengelolaan sistem LMS, termasuk pembuatan kelas, pengelolaan user, serta monitoring progress pembelajaran.

---

## 🔐 Login Admin

![Login Admin](./docs/images/admin-login.png)

1. Akses halaman login
2. Masukkan akun admin yang telah disediakan
3. Klik **Login**
4. Jika berhasil, akan masuk ke dashboard admin

---

## 📚 Manajemen Kelas

### ➕ Membuat Kelas Baru

![Menu Kelas](./docs/images/menu-kelas.png)
![Form Tambah Kelas](./docs/images/form-tambah-kelas.png)

Langkah-langkah:
1. Masuk ke menu **Kelas**
2. Klik **Tambah Kelas**
3. Isi informasi:
   - Nama kelas
   - Deskripsi
   - Level user (target peserta)
4. Klik **Simpan**

> Kelas adalah wadah utama yang berisi seluruh materi pembelajaran.

---

### 📝 Mengisi Konten Kelas

![Detail Kelas](./docs/images/detail-kelas.png)

#### 📄 Upload Materi
![Upload Materi](./docs/images/upload-materi.png)

- Format: PDF, PPT, DOC, dll
- Digunakan untuk pembelajaran teori

#### 🎥 Upload Video
![Upload Video](./docs/images/upload-video.png)

- Video pembelajaran
- Bisa berupa file upload atau link

#### ❓ Membuat / Upload Kuis
![Buat Kuis](./docs/images/buat-kuis.png)

- Kuis dibuat per soal
- Tipe: pilihan ganda
- Digunakan sebagai evaluasi peserta

> Kuis menjadi indikator utama kelulusan peserta.

---

## 📊 Monitoring & Progress

### 👀 Melihat Progress Karyawan

![Daftar Kelas](./docs/images/daftar-kelas.png)
![Progress Karyawan](./docs/images/progress-karyawan.png)

Admin dapat memantau:
- Daftar peserta kelas
- Progress pembelajaran
- Nilai kuis

> Digunakan untuk memastikan efektivitas pembelajaran.

---

## 👥 Manajemen Pengguna

![Manajemen User](./docs/images/manajemen-user.png)

### ➕ Tambah User
![Tambah User](./docs/images/tambah-user.png)

- Menambahkan user baru
- Menentukan role & level akses

### ✏️ Update User
![Update User](./docs/images/update-user.png)

- Mengubah data user
- Mengatur akses kelas

---

## 🎓 Approval Sertifikasi

![Approval Sertifikasi](./docs/images/approval-sertifikasi.png)

- Admin memvalidasi user yang telah menyelesaikan kelas
- Jika memenuhi syarat → sertifikat disetujui

---

# 👤 ROLE: USER (CJ, CT, CS, SM, AM, ASM, OT, Existing User)

User adalah peserta yang mengikuti pembelajaran di LMS.

---

## 📝 Registrasi User

![Registrasi User](./docs/images/registrasi-user.png)

### 🆕 User Baru
![User Baru](./docs/images/user-baru.png)

- Belum terdaftar di data absensi
- Harus registrasi manual

### 🔁 Existing User
![Existing User](./docs/images/existing-user.png)

- Sudah terdaftar di sistem absensi
- Bisa langsung login

---

### 🆔 Input NIK

![Input NIK](./docs/images/input-nik.png)

- Wajib memasukkan NIK
- Digunakan untuk validasi data user

---

### 🔗 Update Profile (Existing User)

![Update Profile](./docs/images/update-profile.png)

Jika data tidak sesuai:
https://pgi.cfcindonesia.com/index.php?model=home&action=showprofile

---

## 🔐 Login User

![Login User](./docs/images/login-user.png)

- Login menggunakan akun terdaftar
- Masuk ke dashboard user

---

## 📚 Akses Kelas

![Dashboard User](./docs/images/dashboard-user.png)

- Akses ditentukan oleh **Level User**
- Hanya kelas sesuai level yang bisa diakses

---

## 📖 Detail Kelas

![Detail Kelas User](./docs/images/detail-kelas-user.png)

### 📄 Materi
![Materi](./docs/images/materi.png)

- Dokumen pembelajaran

### 🎥 Video
![Video](./docs/images/video.png)

- Video penjelasan materi

### ❓ Kuis
![Kuis](./docs/images/kuis.png)

- Hanya bisa dikerjakan **1 kali**
- Jangan refresh halaman saat mengerjakan

> Pastikan jawaban sudah benar sebelum submit.

---

## 🔁 Review Kuis

![Review Kuis](./docs/images/review-kuis.png)

- User dapat melihat hasil kuis
- Digunakan untuk pembelajaran ulang

---

## 📜 Progress & History

![History](./docs/images/history.png)

User dapat melihat:
- Riwayat pembelajaran
- Status kelas
- Hasil evaluasi

---

## 🎓 Sertifikasi

![Request Sertifikasi](./docs/images/request-sertifikasi.png)
![Pencapaian Sertifikasi](./docs/images/pencapaian-sertifikasi.png)

1. Menyelesaikan kelas & penilaian
2. Mengajukan request sertifikasi
3. Admin melakukan approval

---
