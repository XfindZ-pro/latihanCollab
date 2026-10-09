# 🚀 Latihan Kolaborasi GitHub - ISCOM Mentoring 2026

Selamat datang di repository latihan kolaborasi Git & GitHub untuk peserta **Mentoring ISCOM**! 

Repository ini dibuat sebagai wadah praktik bagi para peserta untuk mempelajari dasar-dasar kerja tim menggunakan Git & GitHub, seperti **Forking/Branching**, melakukan **Commit**, hingga mengirimkan **Pull Request (PR)** pertama kalian.

---

## 🎯 Tujuan Latihan
1. Memahami alur kerja (workflow) **Git & GitHub** dalam tim.
2. Melatih cara membuat **Branch baru**.
3. Menambahkan data diri kalian ke dalam berkas `README.md`.
4. Mengirim **Pull Request (PR)** dan menangani review atau konflik sederhana.

---

## 📋 Panduan Langkah-Langkah (Step-by-Step)

### 1. Fork / Clone Repository
Buka repository ini di GitHub, kemudian:
- **Jika ini repo publik bersama:** `Fork` repo ini ke akun GitHub kalian masing-masing, lalu `clone` repo hasil fork kalian ke komputer local.
- **Jika kalian sudah menjadi collaborator:** Langsung `clone` repository ini ke komputer local kalian.

```bash
git clone https://github.com/USERNAME_KALIAN/latihanCollab.git
cd latihanCollab
```

### 2. Buat Branch Baru
Selalu buat branch baru sebelum melakukan perubahan, **jangan langsung di branch `main`**!  
Format nama branch yang disarankan: `feat/nama-kalian` (contoh: `feat/budi-santoso`).

```bash
git checkout -b feat/nama-kalian
```

### 3. Tambahkan Data Diri Kalian
Edit berkas [`README.md`](file:///d:/Kuliah/ISCOM/2026/pesertaCollab/latihanCollab/README.md) ini, lalu tambahkan data baris baru pada **Tabel Peserta Mentoring** di bagian bawah sesuai dengan format yang disediakan.

### 4. Simpan Perubahan & Commit
Setelah menambahkan data diri, simpan file dan jalankan perintah berikut di terminal:

```bash
# Cek status file yang diubah
git status

# Tambahkan file ke staging area
git add README.md

# Buat commit dengan pesan yang jelas
git commit -m "feat: tambah data diri [Nama Kalian]"
```

### 5. Push Branch ke GitHub
Kirimkan branch baru kalian ke GitHub:

```bash
git push origin feat/nama-kalian
```

### 6. Buat Pull Request (PR)
1. Buka halaman repository di GitHub.
2. Kalian akan melihat tombol **"Compare & pull request"**. Klik tombol tersebut.
3. Berikan judul PR yang informatif, contoh: `feat: Menambahkan data diri [Nama Kalian]`.
4. Tambahkan deskripsi singkat di kolom PR.
5. Klik **Create pull request**.
6. Tunggu Mentor/Admin melakukan review dan melakukan **Merge** ke branch `main`.

---

## 👥 Tabel Peserta Mentoring ISCOM

Silakan tambahkan data kalian pada baris paling bawah tabel di bawah ini:

| No. | Nama Lengkap | Angkatan / Jurusan | Username GitHub | Pesan / Hobi |
| :---: | :--- | :--- | :--- | :--- |
| 1 | Contoh Participant | 2026 / Sistem Informasi | [@githubuser](https://github.com/githubuser) | Semangat belajar Git & GitHub bersama ISCOM! 🚀 |
<!-- Tambahkan baris baru di bawah ini -->

---

## 💡 Cheatsheet Git Command

| Perintah Git | Fungsi |
| :--- | :--- |
| `git status` | Melihat status file dan branch saat ini |
| `git branch` | Melihat daftar branch di local |
| `git checkout -b <nama-branch>` | Membuat dan berpindah ke branch baru |
| `git add .` | Menambahkan seluruh perubahan ke staging area |
| `git commit -m "pesan"` | Menyimpan snapshot perubahan dengan pesan |
| `git push origin <nama-branch>` | Mengunggah branch ke repository GitHub |
| `git pull origin main` | Mengambil & memperbarui kode terbaru dari branch `main` |

---

## 🛡️ Etika & Aturan Kolaborasi
- 🛑 **Dilarang keras** mengubah atau menghapus data milik peserta lain!
- 📝 Gunakan pesan commit yang rapi dan deskriptif.
- 💬 Hargai masukan dari mentor atau peserta lain saat proses code review.

---

<p align="center">
  <b>ISCOM Mentoring 2026</b> • Learn, Collaborate & Grow Together! 💙
</p>
