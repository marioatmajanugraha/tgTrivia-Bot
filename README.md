## tgTrivia Bot 🎮
Script ini digunakan untuk mengotomatiskan tugas, Hourly Trivia, dan Daily Missions di game TG Trivia.
![GlH7zOoa8AECwSe](https://github.com/user-attachments/assets/df8ba9ce-0b44-42ae-9520-a4a6e92b75c0)
## 📌 Fitur
- ✅ Auto completion untuk semua tugas (Standard, Special, Partners) menggunakan token dari tokens.txt
- ❓ Auto jawab Hourly Trivia dengan retry jika gagal mendapatkan pertanyaan
- 🎁 Auto klaim Daily Missions dan Mystery Box dengan menampilkan hasil reward
- 🔌 Dukungan proxy (proxy.txt) untuk koneksi aman
- 🚫 Mencegah duplikat klaim tugas dengan log di claim.txt
- ⚡ Desain console log yang keren dengan warna, emoji, dan informasi detail
- 🎮 Proses semua token sebelum menunggu iterasi berikutnya untuk efisiensi

## 🎮 Link Garapan : [tgTrivia-Game](https://t.me/tgtrivia_bot/TriviaGame?startapp=8B6QLLB2)

## 🚀 Cara Penggunaan
1. **Clone repository ini**
```
git clone https://github.com/balveerxyz/TGTrivia-Bot.git
cd TGTrivia-Bot
```

2. **Install Dependencies**
```
npm install axios chalk cfonts http-proxy-agent socks-proxy-agent
```

3. **Siapkan file tokens**
Buat file tokens.txt dan isi dengan token akses, satu token per baris. Contoh:

```
eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9...
eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9...
```

4. **(Opsional) Buat proxy.txt jika ingin menggunakan proxy**. Contoh:
```
http://username:password@host:port
socks5://username:password@host:port
```

5. **Jalankan Script**
```
node index.obf
OR
Double click Run.bat
```

6. **Ikuti Instruksi**
Pilih apakah ingin menggunakan proxy (y/n)
Script akan berjalan otomatis untuk menyelesaikan tugas, Hourly Trivia, dan Daily Missions

## ⚠️ Disclaimer
Gunakan script ini dengan bijak dan sesuai aturan game.

Developer tidak bertanggung jawab atas penyalahgunaan atau banned akun.

## 🤝 Kontribusi
Jika ingin berkontribusi, silakan fork repo ini dan ajukan pull request! Kami terbuka untuk ide baru dan perbaikan.

📞 Kontak
Jika ada pertanyaan, hubungi: [@balveerxyz](https://t.me/balveerxyz)

Join channel Telegram gratis: [t.me/airdroplocked](https://t.me/airdroplocked)
