# OSINT Track

Sebuah alat sederhana untuk melacak informasi menggunakan beberapa paket penting melalui Termux.

## Instalasi

Jalankan perintah di bawah ini untuk menginstal dependensi yang diperlukan:

```bash
pkg update && pkg upgrade
pkg install openssl curl jq ruby -y
gem install lolcat
git clone https://github.com/Lubebansokhekel/OsintTrack
cd OsintTrack
bash OsintTrack.sh
