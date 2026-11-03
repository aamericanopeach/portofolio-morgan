# Website portofolio (statis + Pages CMS)

Semua isi website ada di `content/site.json`. Customer cukup mengedit lewat https://pagescms.org
(login dengan GitHub). Foto yang diunggah masuk ke folder `images/`.

## Deploy
1. Upload folder ini ke repository GitHub.
2. Cloudflare Pages -> Connect to Git -> pilih repo. Build command: kosong. Output directory: `/`.

## Tes di komputer
Jangan klik dua kali `index.html` (fetch JSON diblokir browser). Jalankan:
    python3 -m http.server 8000
lalu buka http://localhost:8000
