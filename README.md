# <a href="" target="_blank">Repo: Waifu</a>

## Mata Kuliah
Sebagai tugas praktikum: [1] Bahasa Pemrograman | Universitas Pelita Bangsa. 

### Cara menggunakan Git
1. Memilih Git Bash yang sesuai,
> disini saya menggunakan Start in: *%HOMEDRIVE%%HOMEPATH%* .
<p align="left">
  <img src="/ss/1.png" width="450">
</p>

    %HOMEDRIVE%%HOMEPATH%

  _ *%HOMEDRIVE%%HOMEPATH%* berfungsi agar /home/ yang akan digunakan nanti berada pada User yang logon saat ini.

2. Konfigurasi Git Config secara Global,
> bisa juga secara individual repository.
<p align="left">
  <img src="/ss/2.png" width="350">
</p>

    git config --global user.name "6xatz"
    git config --global user.email "airalva@gmail.com"

Kalau typo (awokawok typo), santai aja. Bisa pake perintah *--reset-author* kok.

3. Membuat Repository secara lokal pada drive dan menginisiasi Git,
> disarankan membuat repository didalam folder kosong agar /home/ tidak berantakan.
<p align="left">
  <img src="/ss/3.png" width="350">
</p>

    pwd
    mkdir waifu
    cd waifu
    git init

*pwd* berfungsi untuk memeriksa tempat Git bekerja saat ini.
*mkdir* berfungsi untuk membuat folder atau direktori.
*cd* berfungsi untuk masuk ke sebuah direktori (*cd ..* untuk kembali).
*git init* berfungsi untuk menginisiasi Git pada sebuah repository.

4. Membuat Repository secara lokal pada drive dan menginisiasi Git,
> karena kita membuat "README.md" nanti pada pembuatan repository pastikan kalian uncentang: create README.md .
<p align="left">
  <img src="/ss/4.png" width="350">
</p>

    echo "# waifu" >> README.md

*echo* berfungsi untuk mengirim perintah ke konsol.
*"# waifu"* berfungsi untuk mengeksekusi perintah pada repository yang dituliskan.
*README.md* berfungsi untuk membuat README.md .

## Documentation
All associated resources. are licensed under the [MIT License](https://mit-license.org/).
