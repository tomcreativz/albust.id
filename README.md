# albust.id Content Planner (PWA)

500 judul Reels + 100 ide Threads kontroversial (gaya debat) untuk **albust.id** (Financial, Mindset, Syariah x Crypto), dengan checklist "sudah dibuat", pencarian, filter, progres, streak, backup/restore, dan bisa dipasang sebagai aplikasi (PWA, jalan offline).

## Cara publish ke GitHub Pages
1. Buat repository baru di GitHub (misal `albust-planner`), set **Public**.
2. Upload semua isi folder ini (`index.html`, `manifest.json`, `sw.js`, `.nojekyll`, folder `icons/`) ke root repository.
3. Buka **Settings → Pages**. Pada *Build and deployment* pilih **Deploy from a branch**, branch `main`, folder `/ (root)`, lalu Save.
4. Tunggu 1-2 menit. Alamatnya: `https://USERNAME.github.io/albust-planner/`
5. Buka alamat itu di HP lewat Chrome/Safari, lalu **Install / Tambah ke Layar Utama**.

## Catatan
- Progres tersimpan di perangkat (localStorage). Pakai **Pengaturan → Backup** untuk memindahkan antar perangkat.
- Setelah mengedit `index.html`, ubah `VERSION` di `sw.js` supaya pengguna otomatis dapat versi baru.
- Semua path bersifat relatif, jadi aman dipakai di subfolder GitHub Pages.
