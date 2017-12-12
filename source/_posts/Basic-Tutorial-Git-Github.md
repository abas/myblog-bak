---
title: Basic Tutorial Git + Github
ketword: [
  'tutorial git',
  'ngegit',
  'belajar git',
  'github',
  'belajar github',
  'basic git',
  'tutorial','git','basic'
]
date: 2017-12-12 11:38:51
tags: [
  'Cli','Pemrograman'
]
category: ['Cross-Platform']
thumbnail: /asset/git-github.svg
---
![](/asset/git-github.svg)
### Bismillah, kali ini kita akan belajar basic __``nge-Git``__ :D
tapi sebelum itu kita pelajari dulu flow-nya atau alur program-nya ya sob :D jadi alur __``Git``__ itu seperti ketika sobat **download >< upload**, bedanya dalam __``Git``__ itu jadi __push >< pull__ 
alur penggunaan git seperti pada gambar dibawah
``` bash git
  PUSH : UPLOAD
  PULL : DOWNLOAD
```
<!-- more -->
![](/asset/git-design-pattern.svg)
## Inisialisasi -__``git init``__
``` bash contoh
  Abas_$> git init
```
berfungsi untuk menginisialisasi directory sebagai __local__ repository, maksudnya kita akan membuat folder yang di__init__ sebagai __local__ repository atau singkat nya __``folder yang akan di upload``__

## Tracked File -__``git add {nama.file}/{nama.directory}``__
``` bash contoh
  Abas_$> git add README.md
```
berfungsi untuk mengtrack __new/modified__ file, jadi ketika ada file baru atau file yang termodifikasi maka untuk mengupload ke [__github__](https://github.com) repository kita perlu meng-track file tersebut baru bisa kita upload sob :D

## Commit Message -__``git commit -m '{message}'``__
``` bash contoh
  Abas_$> git commit -m 'ini adalah pesan perubahan'
```
ketika kita push perubahan pada [__github__](https://gtihub.com) tentu kita perlu menyertakan atau memberitahu apasih yang kita rubah disitu? jadi __git commit__ itu berfungsi memberi pesan commit atau pesan perubahan yang terjadi pada [__github__](https://github.com) repository

## Push Update -__``git push {nama.remote} {nama.branch}``__
``` bash contoh
  Abas_$> git push origin master
```
untuk melakukan perubahan pada [__github__](https://github.com) repository kita gunakan command ``git push`` diatas terdapat __origin__ yang berarti nama remote yang kita gunakan, remote disini yaitu alamat repository [__github__](https://github.com) yang akan kita update, sementara __master__ adalah nama branch(cabang) yang kita gunakan
