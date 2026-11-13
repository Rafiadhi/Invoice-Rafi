# Invoice Studio

Web invoice generator (satu file, tanpa build). Fitur: template invoice, kolom tambahan, status DP/Lunas, riwayat, kirim WhatsApp, unduh PDF (Letter) & PNG.

## Pasang di GitHub Pages
1. Buat repository baru di GitHub, upload `index.html` dan `README.md`.
2. Buka **Settings → Pages**.
3. Di **Build and deployment**, pilih **Deploy from a branch**, branch `main`, folder `/ (root)`, lalu **Save**.
4. Tunggu 1-2 menit, web bisa dibuka di `https://USERNAME.github.io/NAMA-REPO/`.

## Catatan
- Data (template, riwayat, profil) tersimpan di browser (localStorage) per perangkat.
- Butuh internet untuk memuat font Montserrat/Poppins, html2canvas, dan jsPDF dari CDN.
- Gambar latar sudah tertanam di `index.html`.
