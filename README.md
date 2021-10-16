## Latihan 1
## TUTORIAL MENGGUNAKAN GIT

<p align="center">
 <img src="https://user-images.githubusercontent.com/91085882/137566814-9c8c078c-1c3e-475c-b23d-7f4922f74beb.gif"/>
</p>
<p align="center">
<a href="https://api.whatsapp.com/send?phone=628979234468"><img alt="WhatsApp" src="https://img.shields.io/badge/My-Whatsapp-%23017e40?style=for-the-badge&logo=whatsapp&logoColor=white"/></a></p>
<p align="center">
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
<img src="https://user-images.githubusercontent.com/91085882/137571404-8393bdd6-a910-418a-8f69-cce05ac756cb.png">

- Jalankan perintah git init. untuk membuat repository local
```bash
> git init
```
<img src="https://user-images.githubusercontent.com/91085882/137571564-da9c1c69-0bcf-4053-b890-34311f77046d.png">

- Untuk membuat file dapat menggunakan Text Editor, Lalu menyimpan
filenya pada repository. Sebagai contoh disini saya akan membuat file README.md dengan perintah berikut
```bash
> echo "# Latihan1" >> README.md
```
<img src="https://user-images.githubusercontent.com/91085882/137571839-020c463a-5789-4354-b3c0-3b0a160b7f44.png">

- Untuk menambahkan file yang sudah kita buat, gunakan perintah git add (Nama File) atau bisa menggunakan git add . (Jika file nya ada banyak)
```bash
> git add README.md
> git add .
```
<img src="https://user-images.githubusercontent.com/91085882/137572207-d67bd8af-bf62-414d-886b-32c2866a77fb.png">

- Untuk menyimpan perubahan yang ada kedalam database repository
local, gunakan perintah git commit -m "nama project"
- Dan yang ada di dalam tanda kutip " " itu nama project kita dan jangan sama setiap kali kita upload project
```bash
> git commit -m "First Project"
```
<img src="https://user-images.githubusercontent.com/91085882/137572483-a13054e8-190d-4748-9d1f-1a23635dd9dc.png">

- Untuk menyimpan setiap perubahan pada repository local, gunakan perintah git remote add origin (url)
```bash
> git remote add origin https://github.com/kyuurazz/LatihanVCS.git
```
<img src="https://user-images.githubusercontent.com/91085882/137573795-885c1421-5397-4f92-b0b0-130c95417573.png">

- Untuk mengirim perubahan pada repository local ke server, gunakan perintah git push
- Perintah ini akan meminta Username dan Password pada akun github mu
```bash
> git push -u origin master
```
<img src="https://user-images.githubusercontent.com/91085882/137573735-0409af06-a809-416a-b897-e2c8f7625bdf.png">
- Selesai

# TERIMAKASIH
