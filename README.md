# Misi Bintang Bacaan — Pengembaraan Peribahasa

Laman latihan membaca Bahasa Melayu berasaskan HTML, CSS dan JavaScript tanpa framework atau build step.

## Ciri
- Peringkat 1: tiga peribahasa, maksud dan audio bacaan melalui Web Speech API.
- Peringkat 2: ayat contoh dengan paparan warna berselang-seli dan audio setiap ayat.
- Peringkat 3: penjana ayat dan cerita pendek menggunakan templat tempatan; hasil boleh dibacakan dan disalin.
- Responsif untuk telefon dan desktop, navigasi tiga peringkat dan kemajuan sesi.

## Jalankan
Buka `index.html` dalam pelayar moden. Audio paling baik diuji melalui pelayan HTTPS/localhost (contohnya GitHub Pages). Ketersediaan suara `ms-MY` bergantung pada peranti dan pelayar.

## Terbitkan melalui GitHub Pages
1. Muat naik `index.html` dan `README.md` ke repositori GitHub.
2. Pergi ke **Settings → Pages**.
3. Pilih **Deploy from a branch**, pilih `main` dan folder `/ (root)`, kemudian **Save**.

## Nota pedagogi
Warna merah/biru dalam prototaip membezakan bahagian visual secara berselang-seli untuk membantu tumpuan. Ia belum menjadi pengesah automatik suku kata Melayu; guru boleh menyunting data `syllables` di dalam `index.html` untuk menyemak pembahagian mengikut bahan PdP yang digunakan.

Penjana ayat/cerita di versi ini menggunakan templat terbina dalam dan tidak memerlukan token atau kunci API. Jika mahu penjanaan terbuka menggunakan AI, sambungkan melalui backend dan simpan API key di server—jangan masukkan rahsia dalam kod frontend yang diterbitkan kepada umum.

## Aset kartun
Reka bentuk ini menggunakan emoji dan bentuk CSS sebagai maskot sementara. Untuk menggunakan BoBoiBoy/Yaya secara khusus, tambahkan aset yang anda mempunyai kebenaran untuk menggunakannya; jangan menganggap imej rawak daripada web bebas digunakan.
