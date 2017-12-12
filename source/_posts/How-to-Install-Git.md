---
title: What is Git and How to Install it
keywords: [
  'how to install git',
  'cara menginstall git',
  'install','how to','git'
]
date: 2017-12-09 12:49:17
thumbnail: /asset/git.svg
tags: ['Pemrograman','Cli']
category: ['Cross-Platform ']
---
![](/asset/git.svg)
## __``Git?``__ Anu.. itu makanan apa ya? :v
> _**``Git``** is a **free** and **open source** distributed **version control** system designed to handle everything from small to very large projects with **speed** and **efficiency**._ 

>_**``Git``** adalah sistem **kontrol versi** terdistribusi yang bersifat **bebas** dan **open source** untuk menghandle suatu projek dari sekala kecil maupun dalam sekala besar dengan **cepat** dan **efisien**._
<pre style="text-align:right"><b>-Git</b></pre>

<!-- more -->

## Dari pengalaman yang saya rasakan,..
__Git__ itu sangatlah berguna ketika kita sedang mengerjakan project yang sifatnya team atau dibuat lebih dari 1/2 orang, karena dengan memakai __Git__ kita dapat berkolaborasi dalam proses pengerjaan suatu project

## Lets Start
Oke langsung saja kita coba untuk menginstall __Git__ nya :D untuk tutorial ini kita ada 2 type pengingstalan, untuk __Linux__ dan __Windows__

# Install di -Linux 
Untuk pengguna Linux seperti biasa kita akan menggunakan CLI(Command Line Interfaces) :D jadi yang pertama seperti biasa buka __Terminal__ sobat dengan Shotcut __``ctr+alt+t``__, jika sudan silahkan  ketikan command
``` bash
  Abas_$> sudo apt update
```
``apt get update`` berfungsi untuk mengupdate repository yang ada di milik OS Linux kita. kemudian ketikan command
``` bash
  Abas_$> sudo apt install git
```
jika muncul pemberitahuan [Y/n] ketik ``y`` kemudian enter, tunggu proses selesai. jika sudah coba sobat ketikan command
``` bash
  Abas_$> git
```
jika proses installasi berhasil maka akan terlihat seperti pada gambar dibawah :D
![](/asset/git-command.png)
### Cukup simple bukan ? :D

# Install di -Windows
untuk pengingstalan pada windows kita akan menggunakan __Git Bash__, master atau installernya bisa sobat download [__disini__](https://git-for-windows.github.io/)
![](/asset/git-bash-download.png)
silahkan klik tombol download seperti yang ada pada gambar diatas, kemudian akan menuju halaman versi git, karena kita pake OS __windows__ kita pilih master/installernya dengan extensi __.exe__ silahkan sesuaikan __arsitektur__ OS sobat jika __32bit__ silahkan pilih yang __32bit__ jika __64bit__ silahkan pilih master/installernya yang __64bit__ seperti pada gambar dibawah

![](/asset/list-git-bash.png)

jika sudah didownload masternya silahkan dibuka, tinggal __next.. next__ aja :D wkwk jika sudah slesai proses installasi buka di __Start Menu__ dan ketikan **_``git bash``_** 
### Yeps, All done :D git sudah terinstall di OS windows sobat :D
Tampilah dari terminal __git bash__ tidak jauh berbeda dengan terminal di linux :D dan juga perintah-perintah yang digunakan sama persis antara linux dan windows karena kita menggunakan command line __git__
- - - - -

## Hal pertama yang perlu sobat lakukan setelah install __``git``__ :D
### Setting User.name dan User.email
hal yang pertama sebelum semuanya terjadi, mwehehe sobat harus set dulu identitas sobat kepada __git__ jangan khawatir, kita mulai dengan santai, buka __terminal__ jika sobat pake __Linux__ atau buka __git bash__ jika sobat pake windows. kemudian ketikan command
``` bash
  Abas_$> git config --global user.name ^username
  Abas_$> git config --global user.name ^email

  NOTE:
  ^username  : adalah username yang sobat punya di akun github
  ^email     : adalah email yang terdaftar di akun github sobat
```
mungkin sebagian dari sobat bertanya-tanya 
## __```Kenapa sih kok harus setting begini segala?```__
sebenarnya ini hanya untuk menyertakan identitas sobat ketika akan mengupload/(__PUSH__) project sobat ke github, jadi orang akan tahu siapa yang mengupload project sobat. 
## __```Loh? kan sudah masukkan username dan password?```__
sebenerrnya itu hanya untuk mengautentikasi apakah yang mengupload project ke repo sobat itu benar sobat sendiri.
> ketika kita akan mengupload/(__PUSH__) project kita akan diminta autentikasi akun kita. dengan memasukkan __username__ dan __password__ tapi santai, saya jamin itu __Aman__

### Ok, sekian Tutorial hari ini :D kita lanjut ke selanjut nya yaitu
> ## ``Basic Tutorial Git + Github`` [SOON]