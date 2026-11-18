DRIVER TRACKER – inDrive Edition
PAKET SIAP DIUNGGAH UNTUK INSTALASI PWA ANDROID

Isi:
- index.html: aplikasi utama
- manifest.webmanifest: identitas aplikasi dan ikon
- sw.js: cache/offline service worker
- icon-192.png dan icon-512.png: ikon instalasi

CARA PALING MUDAH MEMASANG DI ANDROID:
1. Unggah SELURUH isi folder ini ke hosting HTTPS (contoh: GitHub Pages).
2. Buka alamat website aplikasi di Google Chrome Android.
3. Buka menu ⋮ Chrome.
4. Pilih "Install app" atau "Tambahkan ke layar utama".
5. Ikuti konfirmasi. Ikon Driver Tracker akan muncul di layar HP.

CATATAN PENTING:
- Ini adalah PWA yang dapat dipasang dari Chrome, bukan APK native.
- Jangan hanya mengunggah index.html. Semua file dalam ZIP harus ikut diunggah dengan struktur folder yang sama.
- Data disimpan lokal di browser/perangkat. Tidak otomatis tersinkron ke cloud dan tidak terhubung ke akun inDrive.
- Ekspor cadangan JSON secara berkala melalui fitur aplikasi.
- Instalasi dan service worker membutuhkan HTTPS (kecuali localhost).
