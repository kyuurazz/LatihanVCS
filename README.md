## Latihan 1
## TUTORIAL MENGGUNAKAN GIT

<p align="center">
 <img src="https://user-images.githubusercontent.com/91085882/137566814-9c8c078c-1c3e-475c-b23d-7f4922f74beb.gif"/>
</p>
<p align="center">
<a href="https://github.com/kyuurazz"><img title="Author" src="https://img.shields.io/badge/Author%20-Bilal%20Hafidz-blue.svg?style=flat&logo=github"></a>
<p align="center">

<p align="center">
<a href="https://github.com/kyuurazz/LatihanVCS#Requirements">Requirements</a> •
<a href="https://github.com/kyuurazz/LatihanVCS#Informasi">Informasi</a> •
<a href="https://github.com/kyuurazz/LatihanVCS#Tutorial">Tutorial</a>
</p>
</div>

# Requirements
- [Git](https://git-scm.com/download)

# Informasi
Apa itu Git?
<p>
Git merupakan software berbasis Version Control System (VCS) yang bertugas untuk mencatat perubahan seluruh file atau repository suatu project. Developer software biasa menggunakan Git untuk distributed revision (VCS terdistribusi), hal ini bertujuan untuk menyimpan database tidak hanya ke satu tempat. Namun semua orang yang terlibat dalam penyusunan kode dapat menyimpan database ini.
</p>

# Tutorial
- Pada saat pertama kali menggunakan Git, perlu dilakukan konfigurasi
Username dan Email. Jalankan perintah berikut:
```bash
> git config --global user.name "username"
> git config --global user.email "email"
```
![Gambar 1](Screenshots/ss1.png)

- Jalankan perintah git init. untuk membuat repository local
```bash
> git init
```
![Gambar 2](Screenshots/ss2.png)

- Untuk membuat file dapat menggunakan Text Editor, Lalu menyimpan
filenya pada repository. Sebagai contoh disini saya akan membuat file README.md dengan perintah berikut
```bash
> echo "# Latihan1" >> README.md
```
![Gambar 3](Screenshots/ss3.png)

- Untuk menambahkan file yang sudah kita buat, gunakan perintah git add (Nama File) atau bisa menggunakan git add . (Jika file nya ada banyak)
```bash
> git add README.md
> git add .
```
![Gambar 4](Screenshots/ss4.png)

- Untuk menyimpan perubahan yang ada kedalam database repository
local, gunakan perintah git commit -m "nama project"
- Dan yang ada di dalam tanda kutip " " itu nama project kita dan jangan sama setiap kali kita upload project
```bash
> git commit -m "First Project"
```
![Gambar 5](Screenshots/ss5.png)

- Untuk menyimpan setiap perubahan pada repository local, gunakan perintah git remote add origin (url)
```bash
> git remote add origin https://github.com/kyuurazz/LatihanVCS.git
```
![Gambar 6](Screenshots/ss6.png)

- Untuk mengirim perubahan pada repository local ke server, gunakan perintah git push
- Perintah ini akan meminta Username dan Password pada akun github mu atau klik Sign in with your browser
```bash
> git push -u origin master
```
![Gambar 7](Screenshots/ss7.png)

- Jika sudah berhasil, maka tampilan nya akan seperti dibawah ini
![Gambar 8](Screenshots/ss8.png)

- Dan file sudah berhasil di upload ke Github anda
![Gambar 9](Screenshots/ss9.png)

- Selesai

## TERIMAKASIH
