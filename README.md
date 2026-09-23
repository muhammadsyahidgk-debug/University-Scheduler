# Jadwal & Tugas

Web sederhana untuk atur jadwal pelajaran dan daftar tugas. Semua data tersimpan di browser (localStorage) — tidak perlu server atau database.

## Cara hosting gratis di GitHub Pages

1. Buat repository baru di GitHub (public), misalnya `jadwal-tugas`.
2. Upload file `index.html` dari folder ini ke repo tersebut (lewat web GitHub: **Add file → Upload files**, atau via `git push`).
3. Buka **Settings → Pages** di repo.
4. Di bagian **Build and deployment**, pilih:
   - Source: `Deploy from a branch`
   - Branch: `main` , folder `/ (root)`
5. Klik **Save**. Tunggu 1–2 menit, GitHub akan kasih link seperti:
   `https://<username-kamu>.github.io/jadwal-tugas/`

Selesai — buka link itu di HP atau laptop mana saja.

## Catatan

- Karena data disimpan di localStorage, jadwal/tugas yang kamu isi hanya tersimpan di browser & perangkat yang kamu pakai saat itu. Kalau buka dari HP dan laptop, datanya tidak otomatis sinkron.
- File `index.html` sudah lengkap (HTML+CSS+JS jadi satu), jadi tidak perlu file tambahan.
