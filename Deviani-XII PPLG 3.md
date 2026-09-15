# Jawaban STS Version Control - Deviani XII PPLG 3

## 1. Apa yang dimaksud dengan GitHub?
GitHub adalah platform berbasis web untuk hosting dan manajemen kode sumber (*source code*) yang menggunakan sistem Git. GitHub memudahkan para pengembang untuk berkolaborasi, melacak perubahan pada kode, dan mengelola proyek pemrograman secara bersama-sama secara daring.

## 2. Apa Fitur dan Komponen Utama GitHub?
* **Repository (Repo):** Tempat penyimpanan seluruh file proyek beserta riwayat versinya.
* **Branch:** Cabang ruang kerja terpisah untuk mengembangkan fitur atau memperbaiki bug tanpa merusak kode utama.
* **Commit:** Catatan atau snapshot dari perubahan kode yang telah disimpan.
* **Pull Request (PR):** Fitur untuk menggabungkan perubahan dari suatu branch ke branch utama (*merge*) setelah melalui proses review.
* **Issue & Project Board:** Fitur untuk melacak tugas, bug, dan manajemen alur kerja proyek.

## 3. Sebutkan Alur Utama (GitHub Workflow)?
1. **Clone/Fork:** Mengambil salinan repository ke komputer lokal atau akun pribadi.
2. **Branching:** Membuat branch baru untuk mengerjakan fitur atau tugas tertentu.
3. **Coding & Commit:** Menulis kode, membuat perubahan, lalu menyimpan riwayat perubahannya (*commit*).
4. **Push:** Mengirimkan branch dan perubahan dari komputer lokal ke GitHub.
5. **Pull Request & Merge:** Mengajukan penggabungan kode ke branch utama agar bisa ditinjau dan disatukan.

## 4. Apa keuntungan utama dari pembatasan branch main?
* **Menjaga Kestabilan Kode:** Memastikan kode yang ada di branch utama (*main atau master*) selalu bersih, stabil, dan siap digunakan atau dirilis tanpa error yang tidak diinginkan.
* **Keamanan Kolaborasi:** Mencegah anggota tim melakukan perubahan langsung yang berisiko merusak atau menimpa kode penting milik orang lain.
* **Kontrol Kualitas (Code Review):** Setiap perubahan baru wajib melalui proses pemeriksaan (*Pull Request*) terlebih dahulu sebelum disatukan ke sistem utama.
