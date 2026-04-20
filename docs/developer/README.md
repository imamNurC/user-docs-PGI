# 📦 Setup Lokal development & deployment – e-Academy

## 🚀 Instalasi Awal

Jalankan langkah berikut hanya sekali saat pertama setup:

```bash
git clone https://github.com/imamNurC/e-Academy.git
cd e-Academy
composer install
npm install
cp .env.example .env
php artisan key:generate
php artisan migrate
```

## 📥 Import Data (Opsional)

Download file SQL, lalu letakkan di folder `/database`, kemudian jalankan:

```bash
php artisan db:seed
```

## ▶️ Menjalankan Aplikasi

```bash
php artisan serve
```

> Jalankan sekali saja, selanjutnya cukup akses via browser.

---

## 🎨 Jika Ada Perubahan Tampilan

```bash
npm run build
```

---

## 🔧 Inisiasi Git (Awal Saja)

```bash
git remote add origin https://github.com/imamNurC/e-Academy.git
```

---

## 🔄 Update Perubahan dari Local

```bash
git add (file update yang di pilih)
git commit -m "deskripsi perubahan"
git push origin main
```

---

## 🌐 Deploy ke Server (cPanel via SSH)

```bash
cd experimental/e-Academy/
eval "$(ssh-agent -s)"
ssh-add ~/.ssh/this_cpanel_server
git fetch origin
git pull origin main
```

---

## 🗄️ Jika Ada Perubahan Struktur Database

```bash
php artisan migrate
```

---

## ⚡ Jika Ada Perubahan Tampilan / Cache

```bash
php artisan optimize
php artisan optimize:clear
```

---

## 📝 Catatan

-  Pastikan file `.env` sudah dikonfigurasi sesuai environment server.
- Jika melakukan export data dari database prod, pastikan 
```bash
- export data only
- pindahkan posisi 'tr_pilihan_kelas_user' paling atas tabel tr
- hapus data dari tabel "migrations" dan "sessions"
- agar objek media sinkron export juga public/storage dari cpanel ke lokal komputer
```
- Jangan commit file `.env` ke repository.
- Jalankan `php artisan serve` hanya untuk development (bukan production).

