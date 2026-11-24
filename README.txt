WEBSITE KUNJUNGAN INDUSTRI BEI

Website ini adalah situs statis dan dapat dijalankan langsung dengan membuka
index.html. Semua aset gambar berada di folder assets.

DEPLOY KE GITHUB PAGES

1. Buat repositori GitHub baru. Agar dapat diakses semua orang, pilih Public.
2. Unggah seluruh isi folder ini ke branch main, termasuk folder
   .github/workflows.
3. Buka tab Actions dan tunggu workflow "Deploy to GitHub Pages" berhasil.
   Workflow akan mengaktifkan GitHub Pages dan menerbitkan file situs.
4. URL publik situs akan ditampilkan di Settings > Pages dan ringkasan workflow.

Setiap push ke branch main atau master akan memublikasikan ulang situs.
Workflow juga dapat dijalankan secara manual dari tab Actions.

Jangan menambahkan access token atau rahasia ke file website. Jika token
pernah dibagikan atau tertempel di chat, segera revoke token tersebut di
pengaturan Developer settings > Personal access tokens GitHub.

Catatan:
Bagian video masih berupa placeholder karena file vlog 90 detik belum
ditambahkan. Untuk menampilkan video, tambahkan file ke assets dan ubah
bagian video-placeholder di index.html menjadi elemen video HTML.
