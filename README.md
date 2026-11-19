# Vicky Ibnu Bayanaka — Professional Portfolio

Website portofolio profesional statis untuk menampilkan profil, pengalaman, proyek, pendidikan, keahlian, sertifikasi, dan informasi kontak.

**Live website:** https://resonant-crisp-257f09.netlify.app/

## Teknologi
- HTML5 semantik
- CSS responsif
- JavaScript vanilla tanpa dependensi/build tool
- JSON-LD Schema.org, Open Graph, dan Twitter Card
- XML sitemap, robots.txt, dan SVG favicon

## Struktur repository
- `site/index.html` — halaman utama, styling, navigasi, dan interaksi
- `site/favicon.svg` — ikon tab browser
- `site/robots.txt` — arahan crawling mesin pencari
- `site/sitemap.xml` — peta URL untuk mesin pencari
- `site/assets/vib-logo.webp` — logo WebP untuk navigasi dan hero
- `site/assets/profile.webp` — foto profil WebP yang dioptimalkan
- File sumber PNG/JPG dan dokumen DWG/SKP tetap disimpan di root repository, di luar direktori publikasi.

## Optimasi gambar otomatis
Workflow GitHub Actions pada `.github/workflows/optimize-images.yml` mengonversi logo dan foto profil sumber menjadi WebP di `site/assets/`. Workflow dapat dijalankan manual melalui tab Actions atau saat file sumber berubah. File asli tetap dipertahankan di root.

## Pengembangan dan deployment
Website tidak memerlukan proses build. Netlify membaca `netlify.toml` dan hanya menerbitkan direktori `site/`. Dengan demikian, file sumber besar di root repository tidak ikut dikirim ke publikasi website. Perubahan pada branch produksi Netlify akan memicu deployment otomatis jika integrasi Git aktif.

## Checklist sebelum publikasi
- Periksa tautan CV, LinkedIn, email, WhatsApp, dan Google Drive.
- Uji navigasi, formulir WhatsApp, dan tampilan pada ponsel/tablet/desktop.
- Pastikan logo dan foto profil WebP tersedia di `site/assets/`.
- Periksa sitemap dan robots.txt setelah publikasi.
- Jalankan Lighthouse/PageSpeed Insights setelah website live.

## Catatan akurasi
Ringkasan proyek dan pengalaman harus tetap sesuai dokumen pendukung. Jangan menambahkan angka pencapaian, lingkup tanggung jawab, atau bukti sertifikasi yang belum diverifikasi.
