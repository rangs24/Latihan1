# Pembelajaran Version Control System
## Install Git
 cara menginstallnya cukup dengan mengetikan di terminal `sudo apt get-install git`
 cek apakah instalasi sudah selesai menggunakan git --version`
## Konfigurasi Email dan Username
 Jalankan perintah berikut diterminal untuk mengkonfigurasikannya
 `git config --global user.name "username"`
 `git config --global user.email "ex@email.com"`
##Membuat Repository local
- Buat direktory aktif
- Buka direktory tersebut
- Jalankan perintah `mkdir latihan1` (untuk membuat direktory project praktikum pertama)
- Selanjutnya masuk kedalam direktory tersebut dengan perintah cd (change directory) `cd latihan1`
- Jalankan Perintah `git init` (perintah untuk membuat repository lokal)
- Untuk menambahkan file yg baru saja dibuat, gunakan perintah `git add README.md`
- Jalankan perintah `git commit -m "komentar komit yg harus anda isi sendiri sesuai inspirasi anda"`
##Membuat Repository Server
- Server repository yang akan digunakan adalah http://github.com
- Buat akun di server tersebut
- Pada laman github, klik tombol start a project, atau
- Dari menu (icon+) klik New Repository
- Isi nama repository nya
- lalu klik >Create Repository
##Menambahkan Remote Repository
- Jalankan Perintah `git remote add origin https://github.com/"nama isi repository anda".git
- Lalu masukan Username dan Password dari akun github anda
- Jalankan perintah `git push -u origin` (untuk mengirim perubahan pada local repository ke server
- Lalu masukan Username dan Password dari akun github anda

SELESAI
# latihan 1
# latihan 1
