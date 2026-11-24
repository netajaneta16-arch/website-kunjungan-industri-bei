WEBSITE KUNJUNGAN INDUSTRI BEI

Website ini adalah situs statis dan dapat dijalankan langsung dengan membuka
index.html. Semua aset gambar dan video berada di folder assets.

DEPLOY KE GITHUB PAGES

1. Buat repositori GitHub baru. Agar dapat diakses semua orang, pilih Public.
2. Unggah seluruh isi folder ini ke branch main, termasuk folder
   .github/workflows.
3. Buka Settings > Pages pada repositori, lalu pilih GitHub Actions sebagai
   Build and deployment source.
4. Buka tab Actions dan jalankan ulang workflow "Deploy to GitHub Pages".
   Tunggu hingga workflow berhasil.
5. URL publik situs akan ditampilkan di Settings > Pages dan ringkasan workflow.

Setiap push ke branch main atau master akan memublikasikan ulang situs.
Workflow juga dapat dijalankan secara manual dari tab Actions.

Jangan menambahkan access token atau rahasia ke file website. Jika token
pernah dibagikan atau tertempel di chat, segera revoke token tersebut di
pengaturan Developer settings > Personal access tokens GitHub.

Video vlog:
Bagian Video Vlog memutar file MP4
assets/WhatsApp Video 2026-11-24 at 08.13.26.mp4 menggunakan kontrol HTML.
Jika nama atau lokasi file berubah, perbarui source video di index.html.
