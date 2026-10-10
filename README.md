# Parhuta Steam - Kasir & Admin Panel

Aplikasi web kasir untuk jasa steam kendaraan (satu file `index.html`, tanpa build).

## Fitur
- Kasir: input transaksi, nomor struk otomatis, cetak struk
- Admin: dasbor, pembukuan, komisi operator, rekap harian, pengaturan, ekspor Excel

## Menjalankan
Buka `index.html` di browser, atau aktifkan GitHub Pages:
Settings > Pages > Source: `main` branch, folder `/ (root)`.

## Catatan
- Data disimpan di `localStorage` browser (per perangkat). Untuk sinkron real-time, ganti fungsi `ld`/`sv` di `index.html` dengan Firebase Firestore.
- Login admin masih di-hardcode di fungsi `doLogin()`. Jangan dipakai apa adanya di repo publik; ganti dengan Firebase Authentication.
