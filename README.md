# Konsultasi Rumah Sakit Personality — PWA awal

## Isi
- `index.html`: antarmuka demo.
- `manifest.json`: identitas aplikasi yang dapat dipasang.
- `service-worker.js`: cache dasar untuk membuka aplikasi kembali.
- `icons/`: ikon aplikasi 192px dan 512px.

## Cara mencoba
PWA perlu dijalankan melalui `localhost` atau hosting HTTPS. Membuka `index.html` langsung dari folder (`file://`) tidak cukup untuk menguji pemasangan PWA.

Untuk uji lokal:
1. Ekstrak ZIP.
2. Buka terminal di folder ini.
3. Jalankan `python -m http.server 8000`.
4. Buka `http://localhost:8000` di Chrome.

## Catatan penting
Ini masih prototype front-end. Chat hanya simulasi lokal; telepon/video, OTP, akun, database, jadwal dinamis, dan keamanan produksi belum dibuat. Jangan gunakan data pasien nyata.
