# 📘 Dokumentasi Panduan Penggunaan Sistem LMS e-Academy

Dokumen ini menjelaskan panduan penggunaan sistem LMS e-Academy untuk dua jenis pengguna utama:

- **Admin (TC, Tim IT)**
- **User (Karyawan / Peserta Pelatihan)**

---

## 🌐 Akses Sistem

![Login Admin/User](./docs/images/login-admin-user.png)

- **URL Login:**  
  https://pgieacademy.com/login

---

# 👨‍💻 ROLE: ADMIN (TC, Tim IT)

Admin bertanggung jawab dalam pengelolaan sistem LMS, termasuk pembuatan kelas, pengelolaan user, serta monitoring progress pembelajaran.

---

## 🔐 Login Admin

![Sukses Login Admin](./docs/images/sukses-login-admin.png)

1. Akses halaman login
2. Masukkan akun admin yang telah disediakan
3. Klik **Login**
4. Jika berhasil, akan masuk ke dashboard admin

---

## 📚 Manajemen Kelas

### ➕ Membuat Kelas Baru
![Buat Kelas Baru](./docs/images/buat-kelas-baru.png)

![Konten Kelas Admin](./docs/images/konten-kelas-admin.png)

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
#### Detail kelas
#### 📄 Upload Materi
![Upload Materi Video](./docs/images/upload-materi-video.png)


- Format: PDF, PPT, DOC, dll
- Digunakan untuk pembelajaran teori

#### 🎥 Upload Video
![Upload Materi Video](./docs/images/upload-materi-video.png)

- Video pembelajaran
- Bisa berupa file upload atau link

#### ❓ Membuat / Upload Kuis
![Upload Kuis](./docs/images/upload-kuis-admin.png)


- Kuis dibuat per soal
- Tipe: pilihan ganda
- Digunakan sebagai evaluasi peserta

> Kuis menjadi indikator utama kelulusan peserta.

---
## Rilis sertifikat kelas

![rilis sertifikat](./docs/images/rilis-sertifikat.png)  
![rilis sertifikat](./docs/images/generate-sertifikat.png)  

di setiap kelas Admin 
- rilis-sertifikat
- generate nomor sertifikat, valid date, until date 


---

## 📊 List kelas & Progress

### 👀 Kelas saat ini
![Daftar Kelas Admin](./docs/images/daftar-klas-admin.png)  
![Daftar Kelas Admin 2](./docs/images/daftar-klas-admin2.png)

### 👀 Melihat Progress Karyawan
![Progress Karyawan](./docs/images/progres-karyawan-admin.png)


Admin dapat memantau:
- Daftar peserta kelas
- Progress pembelajaran
- Nilai kuis

> Digunakan untuk memastikan efektivitas pembelajaran.

---

## 👥 Manajemen Pengguna

![Kelola Pengguna](./docs/images/kelaola-pengguna-admin.png)  
![Kelola Pengguna 2](./docs/images/kelaola-pengguna-admin2.png)

### ➕ Tambah User
![Tambah Pengguna](./docs/images/tambah-pengguna-admin.png)

- Menambahkan user baru
- Menentukan role & level akses

### ✏️ Update User
![Update Pengguna](./docs/images/update-pengguna-admin.png)


- Mengubah data user
- Mengatur akses kelas

---

## 🎓 Approval Sertifikasi

![Approval Sertifikasi](./docs/images/approval-sertif.png)

- Admin memvalidasi user yang telah menyelesaikan kelas
- Jika memenuhi syarat → sertifikat disetujui

---

# 👤 ROLE: USER (CJ, CT, CS, SM, AM, ASM, OT, Existing User)

User adalah peserta yang mengikuti pembelajaran di LMS.

---

## 📝 Registrasi User

![Registrasi User](./docs/images/registrasi-user.png)

### 🆕 User Baru
![User Baru](./docs/images/user-baru-user.png)

- Belum terdaftar di data absensi
- Harus registrasi manual

### 🔁 Existing User
![User Existing](./docs/images/user-existing-user.png)


- Sudah terdaftar di sistem absensi
- Bisa langsung login

---

### 🆔 Input NIK pengguna baru

![Input NIK](./docs/images/input-nik.png)

- Wajib memasukkan NIK
- Digunakan untuk validasi data user

---

### 🔗 Update Profile (Existing User)

![Update NIK](./docs/images/update-nik-user.png)


Jika data tidak sesuai:
https://pgi.cfcindonesia.com/index.php?model=home&action=showprofile

---

## 🔐 Login User

![Login Existing User](./docs/images/login-existing-user.png)  
![Login Sukses User](./docs/images/login-sukses-user.png)

- Login menggunakan akun terdaftar sistem absen maupun yang baru dibuat 
- Masuk ke dashboard user

---

## 📚 Akses Kelas

![Akses Kelas User](./docs/images/akses-kelas-user.png)

- Akses kelas ditentukan berdasarkan **Level User**
- Hanya kelas sesuai level yang bisa diakses

---

## 📖 Detail Kelas
### 📄 Materi
![Materi](./docs/images/kelas-materi-user.png)

- Dokumen pembelajaran

### 🎥 Video
![Video](./docs/images/kelas-video-user.png)

- Video penjelasan materi

### ❓ Kuis
![Kuis](./docs/images/kelas-kuis-user.png)

- Hanya bisa dikerjakan **1 kali**
- Jangan refresh halaman saat mengerjakan

> Pastikan jawaban sudah benar sebelum submit.

---

## 🔁 Review Kuis

![Review Kuis](./docs/images/review-kuis-user.png)


- User dapat melihat hasil kuis
- Digunakan untuk pembelajaran ulang

---

## 📜 Progress & History

![History](./docs/images/history-user.png)

User dapat melihat:
- Riwayat pembelajaran
- Status kelas
- Hasil evaluasi

---

## 🎓 Sertifikasi

![History](./docs/images/history-user.png)
![Pencapaian Sertifikasi](./docs/images/sertifikat-user.png)

1. Menyelesaikan kelas & penilaian
2. Mengajukan request sertifikasi
3. Admin melakukan approval

---

