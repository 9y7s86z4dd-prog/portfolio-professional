# Vicky Ibnu Bayanaka — Professional Portfolio

Website portofolio profesional statis untuk menampilkan profil, pengalaman, proyek, pendidikan, keahlian, sertifikasi, dan informasi kontak.

**Live website:** https://resonant-crisp-257f09.netlify.app/

## Teknologi
- HTML5 semantik
- CSS responsif dengan pendekatan mobile-first
- JavaScript vanilla tanpa dependensi/build tool
- JSON-LD Schema.org (Person)
- Open Graph dan Twitter Card
- XML sitemap, robots.txt, SVG favicon

## Struktur file
- `index.html` — halaman utama, styling, navigasi, dan interaksi
- `favicon.svg` — ikon tab browser
- `robots.txt` — arahan crawling mesin pencari
- `sitemap.xml` — peta URL untuk mesin pencari
- `assets/vib-logo.webp` — logo WebP untuk navigasi dan hero
- `assets/profile.webp` — foto profil WebP yang dioptimalkan
- `Futuristic VIB Skyline Emblem.png` dan `Vicky Ibnu Bayanka_202121017.jpg` — file sumber asli yang dipertahankan

## Konten
Website mencakup ringkasan profil, tiga ringkasan pengalaman proyek, riwayat magang dan observasi lapangan, pendidikan, keahlian teknis, sertifikasi, tautan CV/dokumentasi, serta formulir kontak yang menyiapkan pesan WhatsApp.

## Optimasi gambar otomatis
Workflow GitHub Actions pada `.github/workflows/optimize-images.yml` mengonversi logo dan foto profil sumber menjadi WebP saat file sumber atau workflow diperbarui, serta dapat dijalankan manual melalui tab Actions. Foto profil dibatasi hingga 900×1100 piksel dan logo hingga 1200×1200 piksel untuk menekan ukuran unduhan tanpa mengubah file sumber.

## Pengembangan dan deployment
Website tidak memerlukan proses build. Perubahan pada branch `main` akan dipublikasikan oleh Netlify apabila integrasi continuous deployment aktif. Periksa status deploy di dashboard Netlify setelah setiap pembaruan.

## Checklist sebelum publikasi
- Periksa seluruh tautan CV, LinkedIn, email, WhatsApp, dan Google Drive.
- Pastikan foto, logo, dan dokumen pendukung dapat diakses publik sesuai kebutuhan.
- Uji navigasi, formulir WhatsApp, dan tampilan pada ponsel/tablet/desktop.
- Daftarkan sitemap di Google Search Console dan lakukan inspeksi URL.
- Jalankan Lighthouse/PageSpeed Insights setelah situs live.
- Ganti ilustrasi proyek dengan foto/dokumen proyek asli yang telah mendapat izin publikasi bila tersedia.

## Catatan akurasi
Ringkasan proyek dan pengalaman harus tetap sesuai dokumen pendukung. Jangan menambahkan angka pencapaian, lingkup tanggung jawab, atau bukti sertifikasi yang belum diverifikasi.
