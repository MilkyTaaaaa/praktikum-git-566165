# Kaevrin Landing Page

Website landing page untuk brand outdoor "Kaevrin" yang menampilkan produk, testimonial, dan informasi brand.

## Cara Menjalankan
1. Clone repository
2. Buka file index.html di browser

## Screenshot

### Website
![Website](img/website.png)


## 📝 Deskripsi Project
Kaevrin adalah sebuah *landing page* responsif untuk *brand* gaya hidup *outdoor* premium. Website ini menampilkan berbagai perlengkapan inovatif seperti tenda, sepatu, dan tas ransel yang dirancang untuk daya tahan dan kenyamanan maksimal para penjelajah. Repository ini juga digunakan sebagai pemenuhan Tugas Praktikum Pemrograman Web terkait penggunaan Git dan GitHub.

## 🚀 Cara Menjalankan
1. *Clone repository* ini ke lokal menggunakan perintah:
   `git clone https://github.com/MilkyTaaaaa/praktikum-git-566165.git`
2. Buka folder *project* di *code editor* (seperti VS Code).
3. Buka file `index.html` menggunakan *browser* atau ekstensi **Live Server**.

---

## 📚 Perjalanan Praktikum (Langkah-Langkah Tugas)

Project ini diselesaikan melalui beberapa tahapan simulasi alur kerja *software engineering* menggunakan Git:

### Tugas 1: Inisiasi dan Konvensi Commit
* Melakukan *clone repository* kosong dari GitHub ke penyimpanan lokal.
* Membuat file `.gitignore` untuk mengecualikan file seperti `.DS_Store`, `*.log`, dan folder `node_modules/`.
* Membangun file `index.html` dan `style.css` secara bertahap melalui **minimal 5 kali commit** menggunakan standar *Conventional Commits* (seperti `feat:`, `style:`, `chore:`).

### Tugas 2: Branching, Pull Request, dan Branch Protection
* Membuat 3 *branch* terpisah dari `main`:
  1. `feature/navbar`: Untuk menambahkan navigasi utama.
  2. `feature/footer`: Untuk menambahkan *footer* dan info kontak.
  3. `hotfix/typo`: Untuk memperbaiki *typo* pada bagian *Hero Section*.
* Melakukan *Push* pada ketiga *branch* tersebut dan membuat **Pull Request (PR)** di GitHub.
* Melakukan *Merge* pada PR fitur menggunakan metode **Squash and merge**, dan PR perbaikan menggunakan **Merge commit**.
* Menerapkan **Branch Protection Rule** pada *branch* `main` yang mewajibkan adanya Pull Request sebelum *merge* dan menonaktifkan *push* secara langsung.

### Tugas 3: Simulasi Konflik dan Interactive Rebase
* **Simulasi Konflik:** Membuat *branch* `experiment/color-A` dan `experiment/color-B` yang mengubah baris CSS yang sama. Setelah *branch* A di-*merge* ke `main`, *merge* *branch* B menghasilkan konflik. Konflik ini diselesaikan secara manual melalui VS Code (memilih *Accept Current/Incoming Change*).
* **Interactive Rebase:** Membuat *branch* `feature/dark-mode` dengan 3 *commit* terpisah. Kemudian menggunakan perintah `git rebase -i` untuk menggabungkan (*squash*) ketiga *commit* tersebut menjadi satu *commit* yang lebih rapi sebelum di-*merge*.

### Tugas 4: Issue Tracking dan Release
* Membuat minimal 3 **Issues** di GitHub terkait penambahan fitur atau perbaikan *bug*.
* Menutup *Issues* tersebut secara otomatis melalui Pull Request menggunakan *keyword* (contoh: `Closes #1`).
* Mengundang Dosen dan Asisten Dosen sebagai **Collaborator** di *repository*.
* Membuat versi **Release v1.0.0** di GitHub lengkap dengan *tag* dan *changelog*.

---


## Perintah Git

- `git init` → membuat repository
- `git add .` → menambahkan perubahan
- `git commit` → menyimpan perubahan
- `git branch` → membuat branch
- `git checkout` → pindah branch
- `git merge` → menggabungkan branch
- `git rebase -i` → menggabungkan commit
- `git push` → upload ke GitHub


## 💻 Dokumentasi Perintah Git yang Digunakan

* `git clone [url]`: Mengunduh *repository* dari GitHub ke penyimpanan lokal.
* `git add .`: Menambahkan semua perubahan file ke *staging area* sebelum di-*commit*.
* `git commit -m "[pesan]"`: Menyimpan perubahan secara permanen ke *history* Git lokal dengan pesan terstruktur.
* `git push origin [branch]`: Mengunggah perubahan dari *branch* lokal ke *repository* GitHub.
* `git pull origin [branch]`: Mengambil dan menggabungkan pembaruan terbaru dari GitHub ke laptop lokal.
* `git checkout -b [nama-branch]`: Membuat *branch* baru sekaligus langsung berpindah ke *branch* tersebut.
* `git checkout [nama-branch]`: Berpindah ke *branch* yang sudah ada.
* `git merge [nama-branch]`: Menggabungkan *history* dari *branch* lain ke *branch* yang sedang aktif secara lokal.
* `git rebase -i HEAD~3`: Melakukan interaktif *rebase* untuk mengubah atau menggabungkan (*squash*) 3 *commit* terakhir.
* `git log --oneline --graph`: Menampilkan riwayat *commit* dalam bentuk grafis yang ringkas.


### Git Log
![Git Log](img/log1.png)
![Git Log](img/log2.png)
![Git Log](img/log3.png)
![Git Log](img/log4.png)
![Git Log](img/log5.png)
---

### Branch Protection
![Branch Protection](img/branchprotection.png)


