# Keuangan Desa Candi Badut

Pembungkus GitHub Pages untuk web app Google Apps Script "Keuangan Desa Candi Badut" (Daerah Malang Kota).
Aplikasi dan datanya tetap berjalan di Google Apps Script + Google Sheets. Repo ini hanya menampilkannya di alamat github.io dan membuatnya bisa dipasang di HP.

## Isi
| File | Fungsi |
|---|---|
| `index.html` | Halaman yang menampilkan aplikasi Apps Script |
| `manifest.json` | Info aplikasi untuk "Tambahkan ke layar utama" |
| `sw.js` | Service worker (aplikasi bisa dipasang & cepat dibuka) |
| `icon-192.png`, `icon-512.png` | Ikon aplikasi |
| `.nojekyll` | Supaya GitHub Pages menyajikan file apa adanya |

## Mengganti URL aplikasi
Jika URL deployment Apps Script berubah, edit variabel `URL_APP` di `index.html`.

Aplikasi asli: https://script.google.com/macros/s/AKfycbxXw8D_NxSDXC6h1Rmg-xOhZy-Dckcy6IuzEnZbaXrr3m42VU8SPsR2lb3XGlK3GWg8/exec
