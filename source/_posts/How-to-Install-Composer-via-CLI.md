---
title: How to Install Composer via CLI | Linux
date: 2017-12-06 07:25:34
tags: [
  'Pemrograman',,'Cli'
]
category: [
  'Linux','Web'
]
thumbnail: /asset/composer_logo.jpg
---
![](/asset/composer_logo.jpg)

### Halo sobat - sobat ku yag berbahagia :D

Kali ini kita akan membahas apa itu komposer, cara install composer dan apa sih kegunaan composer itu sendiri

## Apasih __Composer__ itu? 
>__Composer__ adalah dependency manager khusus PHP yang memiliki fungsionalitas seperti Gem (Ruby) atau Maven (Java). Anda bisa menginstall suatu library melalui composer dan composer akan secara otomatis menginstall library lain yang dibutuhkan, tanpa perlu mendownload satu persatu. Mirip dengan apt get install di sistem operasi linux. 

<!-- more -->

### yang kamu butuhin pada tutorial ini
- OS Linux :v
- Iman dan Keyakinan

# Cara 1 | lewat apt-get
buka terminal __``ctrl+alt+t``__ kemudian masukkan command
``` bash
  Abas_$> sudo apt-get install composer
```
jika sudah slesai silahkan ketikkan command berikut untuk mengecek apakah __composer__ berhasil di install apa belum
```
  Abas_$> composer
```
![](/asset/composer.png)
jika berhasil diInstall maka tampilan CLI akan seperti di atas :D

# Cara 2 | lewat __curl__
pertama cek dulu sob, __curl__ kalian udah keinstall apa belum? masukkan command berikut.
``` bash
  Abas_$> curl -V
```

jika sudah ke-install maka akan muncul kurang lebih seperti berikut
``` bash
  Abas_$> curl -V
    curl 7.47.0 (x86_64-pc-linux-gnu) libcurl/7.47.0 GnuTLS/3.4.10 zlib/1.2.8 libidn/1.32 librtmp/2.3
    Protocols: dict file ftp ftps gopher http https imap imaps ldap ldaps pop3 pop3s rtmp rtsp smb smbs smtp smtps telnet tftp 
    Features: AsynchDNS IDN IPv6 Largefile GSS-API Kerberos SPNEGO NTLM NTLM_WB SSL libz TLS-SRP UnixSockets 
```

jika belum ke-install silahkan di install dulu sob, dengan command berikut
``` bash
  Abas_$> sudo apt-get install curl php5-cli git
```

apabila muncul pertanyaan [Y/n] ketik ``y`` kemudian __enter__
selanjutnya ketikan command
``` bash
  Abas_$> curl -sS https://getcomposer.org/installer | sudo php -- --install-dir=/usr/local/bin --filename=composer
```

Composer sobat sudah keinstall di linux kalian :D untuk mengecek nya silahkan ketikan command 
``` bash
  Abas_$> composer
```

## Kegunaan Composer
dari pengalaman saya :D composer sangat berguna ketika kita ingin mengunduh modul - modul dengan mudah hanya dengan mengetikkan comman __```composer install```__ karena dalam composer telah tersedia modul - modul yang siap pakai :D sebagai contohnya penggunaan composer dengan framework PHP [__Laravel__](https://laravel.com).

> ### [__Tutorial Buat Project Laravel dengan Composer__](#) 
  ### [Coming Soon!]

<br><hr>
## __```Reference```__
- [__Dumetschool__](https://www.dumetschool.com)
- [__Digital Ocean__](https://www.digitalocean.com)