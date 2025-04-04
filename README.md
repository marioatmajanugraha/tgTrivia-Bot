# TGTrivia-Bot 🎮

Script ini digunakan untuk mengotomatiskan tugas, bermain Hourly Trivia, dan membuka Mystery Box di TG Trivia secara efisien!

![tgTrivia](https://github.com/user-attachments/assets/10ed1d7b-b15f-431b-ad9b-66b011bb4e93)

## 📌 Fitur

- ✅ Auto Login menggunakan authString dari `auth.txt` dan menyimpan token ke `tokens.txt` 
- ✅ Auto Completion untuk semua tugas (Daily, Partner, Regular) menggunakan token 
- ✅ Auto Play Hourly Trivia dengan pemilihan jawaban otomatis (benar atau acak jika tidak diketahui) 
- ✅ Auto Open Mystery Box dan klaim Daily Check-in dengan laporan hadiah 
- ✅ Countdown Timer interaktif untuk menampilkan waktu tunggu sebelum iterasi berikutnya 
- ✅ Dukungan Proxy (`proxy.txt`) untuk koneksi aman 

## 🚀 Cara Penggunaan

### 1. Clone Repository Ini

```sh
git clone https://github.com/marioatmajanugraha/tgTrivia-Bot.git
cd tgTrivia-Bot
```

### 2. Install Dependencies

```sh
npm install axios chalk cfonts http-proxy-agent socks-proxy-agent
```

### 3. Siapkan File yang Dibutuhkan

- isi file auth.txt

```sh
user=%7B%2....
```

- isi proxy pada file proxy.txt

```sh
http://username:password@host:port
socks5://username:password@host:port
```

**⚡ Token akan otomatis disimpan ke tokens.txt setelah login berhasil.**

### 4. Jalankan Script

```sh
node index.obf.js
```

### 5. Ikuti Instruksi

- Pilih apakah ingin menggunakan proxy (`y/n`).
- Script akan otomatis melakukan login, menyimpan token, dan menjalankan semua tugas, Hourly Trivia, serta Mystery Box dalam loop dengan countdown timer.

## ⚠️ Disclaimer

Gunakan script ini dengan bijak dan sesuai aturan TG Trivia.

Developer tidak bertanggung jawab atas penyalahgunaan atau banned akun.

## 🤝 Kontribusi

Jika ingin berkontribusi, silakan fork repo ini dan ajukan pull request! Kami terbuka untuk ide baru dan perbaikan.

## 📞 Kontak

Jika ada pertanyaan, hubungi: [@balveerxyz](https://t.me/balveerxyz)

Join channel Telegram gratis: [t.me/airdroplocked](https://t.me/airdroplocked)

