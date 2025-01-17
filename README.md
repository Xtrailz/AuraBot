<p align="left">
	<img src="https://telegra.ph/file/2a994c4949315bb7f51b8.jpg" width="35%" style="margin-left: auto;margin-right: auto;display: block;">
</p>
<h1 align="left">AuraBot</h1>

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/RFIunknown/AuraBot)

[![Run on Repl.it](https://repl.it/badge/github/Xtrailz/AuraBot)](https://repl.it/github/Xtrailz/AuraBot)

[![Grup WhatsApp](https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)](https://chat.whatsapp.com/JYYtEWOhbLs7P2xcaihYhU)

# AuraBot
AuraBot adalah bot whatsapp hasil recode dari FadliDarmawan/haruno.
AuraBot bot dapat di jalankan di Termux, RPP/VPS/Windows, Heroku, Replit.

# Termux
NOTE: untuk pengguna termux yang ingin menggunakan fitur nhentai(dari module nhentai-node-api) harap aktifkan dns (dns.google) agar bisa mengakses fitur (kena internet positif)
```
apt install ffmpeg
apt install imagemagick
apt install nodejs
apt install git
git clone https://github.com/RFIunknown/AuraBot
cd AuraBot
npm i
node . (option)
````

# RDP/VPS/Windows
* Unduh & Instal Git [`Klik Disini`](https://git-scm.com/downloads)
* Unduh & Instal NodeJS [`Klik Disini`](https://nodejs.org/en/download)
* Unduh & Instal FFmpeg [`Klik Disini`](https://ffmpeg.org/download.html) (**Jangan Lupa Tambahkan FFmpeg ke variabel lingkungan PATH**)
* Unduh & Instal ImageMagick [`Klik Disini`](https://imagemagick.org/script/download.php)
```
git clone https://github.com/RFIunknown/AuraBot
cd AuraBot
npm i
node . (option)
```
# Replit
[![Run on Repl.it](https://repl.it/badge/github/Xtrailz/AuraBot)](https://repl.it/github/Xtrailz/AuraBot)
* Klik button
* Buka console
```
npm i
node . (option)
```
# Heroku
[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=github.com/RFIunknown/AuraBot)

*install buildpack
* heroku/nodejs
* https://github.com/jonathanong/heroku-buildpack-ffmpeg-latest.git
* https://github.com/DuckyTeam/heroku-buildpack-imagemagick.git

# Option

## Arguments `node . [--options] [<session name>]`

#### Contoh: `node . --self --restrict --autoread`

### `--self`

Aktifkan mode self (Mengabaikan yang lain)

### `--prefix <prefixes>`

* `prefixes` dipisahkan oleh masing-masing karakter
Setel awalan

### `--server`

Digunakan untuk [heroku](https://heroku.com/) atau pindai melalui situs web

### `--db <json-server-url>`

Gunakan db eksternal alih-alih db lokal, 
Contoh Server `https://json-server.nurutomo.repl.co/`
Code: `https://repl.it/@Nurutomo/json-server`

`node . --db 'https://json-server.nurutomo.repl.co/'`

Server harus memiliki spesifikasi seperti ini

#### GET

```http
GET /
Accept: application/json
```

#### POST

```http
POST /
Content-Type: application/json

{
 data: {}
}
```

### `--big-qr`

Jika qr unicode kecil tidak mendukung

### `--restrict`

Mengaktifkan plugin terbatas (yang dapat menyebabkan nomor Anda **diblokir** jika digunakan terlalu sering)

* Administrasi Grup `add, kick, promote, demote`

### `--img`

Aktifkan pemeriksa gambar melalui terminal

### `--autoread`

Jika diaktifkan, semua pesan masuk akan ditandai sebagai telah dibaca

### `--nyimak`

Tidak ada bot, cukup cetak pesan yang diterima dan tambahkan pengguna ke database

### `--test`

**Development** Testing Mode

### `--trace`

```js
conn.logger.level = 'trace'
```

### `--debug`

```js
conn.logger.level = 'debug'
```

---------

 [![Nurutomo](https://github.com/Nurutomo.png?size=100)](https://github.com/Nurutomo) | [![Ariffb](https://github.com/ariffb25.png?size=100)](https://github.com/ariffb25) | [![Fadli](https://github.com/FadliDarmawan.png?size=100)](https://github.com/FadliDarmawan) | [![Rifai](https://github.com/RFIunknown.png?size=100)](https://github.com/RFIunknown)
----|----|----|----
[Nurutomo](https://github.com/Nurutomo) | [Ariffb](https://github.com/ariffb25) | [Fadli](https://github.com/FadliDarmawan) | [Rifai](https://github.com/RFIunknown)
 Penulis / Pencipta | Penulis ulang | Pengembang ulang | Pengembang Ulang


