# Xetya Wallpapers — GitHub Pages

## Isi
- `wallpapers.json`: daftar gambar untuk Overflight.
- `images/bali/`: 25 gambar JPG.
- `index.html`: galeri pratinjau browser.

## Sebelum publish
1. Buat repository publik bernama `wallpaper-main` (atau sesuaikan semua URL di `wallpapers.json` jika nama repo berbeda).
2. Ganti setiap `USERNAME` di `wallpapers.json` dengan username GitHub Anda.
3. Upload isi folder ini ke root repository.
4. Aktifkan Settings → Pages → Deploy from a branch → `main` → `/(root)`.
5. Setelah deploy, tes:
   - `https://USERNAME.github.io/wallpaper-main/wallpapers.json`
   - `https://USERNAME.github.io/wallpaper-main/`
6. Di Overflight, masukkan URL JSON tersebut sebagai sumber media.

Semua URL `url_img` harus HTTPS dan dapat diakses publik. Overflight mendukung JSON dengan `url_img`.
