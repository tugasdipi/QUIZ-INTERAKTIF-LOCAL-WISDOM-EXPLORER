# Jelajah Kearifan Lokal — Versi Embedded (GitHub Pages)

Website asesmen diagnostik IPS Kelas IX yang sudah siap diunggah ke GitHub Pages.

## Isi paket

- `index.html` — aplikasi lengkap; **seluruh logo dan gambar maskot sudah tertanam langsung** sebagai `data:image/webp;base64` di dalam HTML.
- `.nojekyll` — penanda agar GitHub Pages tidak memproses proyek sebagai situs Jekyll (opsional).
- `README.md` — panduan penggunaan dan deploy.

**Tidak perlu membuat folder `assets`.** Jangan mengubah `index.html` menjadi `index.html.txt`.

## Deploy cepat

1. Ekstrak file ZIP.
2. Buka GitHub, buat repository baru (misalnya `jelajah-kearifan-lokal`).
3. Pilih **Add file → Upload files**. Unggah `index.html` langsung ke direktori utama repository dan klik **Commit changes**. `README.md` serta `.nojekyll` boleh diunggah bersamaan.
4. Buka **Settings → Pages → Build and deployment**, pilih **Deploy from a branch**; branch **main** dan folder **/(root)**; lalu **Save**.
5. Setelah GitHub menerbitkan halaman, buka `https://USERNAME.github.io/jelajah-kearifan-lokal/` dengan mengganti USERNAME dan nama repo.

## Pengujian dan catatan

- Semua gambar dimuat dari isi HTML, bukan file gambar terpisah atau URL eksternal.
- Website berjalan tanpa backend/database dan tidak perlu instalasi npm, build tools, maupun CDN.
- Kuis memiliki 9 soal dan tiga kategori hasil (Bintang, Hati, Pelangi).
- Penghitungan jawaban berlangsung lokal di browser; tidak ada fitur pengiriman nilai ke guru.
- Klik dua kali `index.html` untuk membuka versi lokal di browser, tanpa koneksi internet.
