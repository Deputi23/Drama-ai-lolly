# LOLLY AI DRAMA STUDIO – Android Edition

Versi 1.0 PWA untuk membuat paket produksi micro drama 60 detik.

## Fitur
- Form konsep cerita dan karakter
- Generate 8 adegan (total 60 detik)
- Dialog dan prompt video per adegan
- Salin prompt per adegan atau semua sekaligus
- Ekspor TXT dan JSON
- Menyimpan proyek terakhir di perangkat
- PWA dan cache offline setelah pertama kali dibuka

## Batasan penting
Versi ini tidak merender video AI. Fitur generate membuat naskah, storyboard, dan prompt secara lokal tanpa API/kredit. Rendering video tetap memerlukan layanan video generator eksternal yang memiliki akses gratis. Tidak ada jaminan layanan eksternal gratis tanpa batas.

## Deploy GitHub Pages
1. Ekstrak ZIP.
2. Unggah `index.html`, `manifest.webmanifest`, `sw.js`, dan `README.md` ke root repository.
3. GitHub → Settings → Pages.
4. Source: Deploy from a branch; Branch: `main`; Folder: `/ (root)`.
5. Save, tunggu Actions selesai, lalu buka URL Pages.
6. Di Chrome Android, menu ⋮ → Tambahkan ke layar utama / Install app.
