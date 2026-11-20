# SouthLinks Tennis Court — Booking (versi demo)

Versi demo untuk dicoba lewat GitHub Pages. Tampilan dan alurnya sama dengan versi asli:
pilih tanggal, court, lama main (minimal 1 jam), jam mulai per 30 menit, harga otomatis,
persetujuan tidak bisa refund, dan reschedule kalau hujan. Tombol WhatsApp tetap membuka chat ke admin.

**Batasan demo:** data booking hanya tersimpan di browser / HP yang dipakai (localStorage).
Admin di HP lain tidak melihat pesanan tamu, dan tidak ada password admin.
Untuk dipakai beneran, upload versi PHP (folder `tennis-booking`) ke hosting.

- Halaman tamu: `index.html`
- Dashboard admin (demo): `admin.html`

## Cara upload ke GitHub Pages (lewat browser, tanpa install apa-apa)

1. Buat akun / login di https://github.com
2. Klik **+** (kanan atas) → **New repository**
   - Repository name: misalnya `southlinks-tennis`
   - Pilih **Public** (GitHub Pages gratis hanya untuk repo public)
   - Klik **Create repository**
3. Di halaman repo baru, klik link **uploading an existing file**
4. Klik **choose your files**, buka folder `tennis-booking-github-upload`, pilih ketiga file
   (`index.html`, `admin.html`, `README.md`) → klik **Commit changes**
5. Buka **Settings** → **Pages** → bagian *Build and deployment*:
   Source = **Deploy from a branch**, Branch = **main** dan folder **/ (root)** → **Save**
6. Tunggu 1–2 menit, refresh halaman Pages. Link muncul di atas, bentuknya:
   `https://NAMA-AKUN.github.io/southlinks-tennis/`
   - Halaman pesan: link di atas
   - Admin demo: link di atas + `admin.html`
