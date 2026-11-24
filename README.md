# Hari Guru Nasional — Bu Elly Wandira

Website ucapan Hari Guru spesial dari Hendar. Dibuat responsif untuk HP dan siap deploy ke Railway.

## Deploy melalui GitHub ke Railway
1. Ekstrak ZIP ini.
2. Buat repository baru di GitHub.
3. Upload **isi folder project** (package.json, server.js, dan folder public) ke repository. Jangan upload file ZIP ke dalam repository.
4. Buka Railway → New Project → Deploy from GitHub Repo.
5. Pilih repository tersebut.
6. Railway akan membaca `package.json` dan menjalankan perintah `npm start`.
7. Setelah deploy selesai, buka Settings → Networking → Generate Domain.

Tidak perlu mengisi Environment Variables tambahan. Railway otomatis menyediakan `PORT`.

## Struktur
- `package.json` — dependency dan perintah start
- `server.js` — server Express untuk Railway
- `public/index.html` — halaman hitung mundur sampai 25 November 2026 pukul 00.00 WIB
- `public/surat.html` — halaman ucapan dan surat spesial yang otomatis terbuka setelah hitung mundur selesai

## Kustomisasi
Untuk mengubah tulisan, edit `public/index.html`. Nama guru dan kredit Hendar sudah terpasang.
