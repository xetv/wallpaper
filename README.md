# Xetya Wallpapers — Overflight / Projectivy

Paket konfigurasi ringan, tanpa file gambar. URL gambar menunjuk ke repository `xetv/wallpaper` pada branch `main`.

## File
- `wallpapers.json`: daftar 25 wallpaper Bali untuk Overflight.
- `index.html`: galeri pratinjau yang membaca `wallpapers.json` dari GitHub Pages.
- `README.md`: panduan singkat.

## Publish
1. Upload isi paket ini ke root repository publik `xetv/wallpaper` (repository yang sama dengan folder `images/bali/`).
2. Pastikan folder gambar sudah ada di `main/images/bali/` dan nama file cocok dengan `wallpapers.json`.
3. Aktifkan GitHub Pages: Settings → Pages → Deploy from a branch → `main` → `/(root)`.
4. URL JSON untuk Overflight: `https://xetv.github.io/wallpaper/wallpapers.json`
5. URL gambar memakai format Raw GitHub, misalnya `https://raw.githubusercontent.com/xetv/wallpaper/refs/heads/main/images/bali/beratan-puraulundanu.jpg`.

Catatan: paket ini tidak menyertakan gambar. URL gambar hanya akan berfungsi jika file terkait memang sudah ada pada repository `xetv/wallpaper` dengan nama dan jalur yang sama.
