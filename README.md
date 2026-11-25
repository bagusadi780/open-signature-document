# Open Signature Document

**100% gratis dan aman selamanya. Kami tidak menyimpan apa pun — semua bisa diaudit di repo ini.**

Alat tanda tangan PDF online yang berjalan sepenuhnya di browser. Gambar tanda tangan dengan halus, ketik, atau unggah gambar — lalu tempel ke dokumen PDF dan unduh hasilnya. Tanpa akun, tanpa unggah ke server, tanpa pelacakan.

## Kenapa bisa dipercaya

- **100% client-side.** File PDF tidak pernah meninggalkan perangkatmu. Tidak ada server, tidak ada database, tidak ada tempat untuk menyimpan apa pun.
- **Open source.** Seluruh kode ada di repo ini dalam satu file `index.html` — silakan audit sendiri.
- **Gratis selamanya.** Tidak ada paywall, tidak ada batas halaman, tidak ada watermark.

## Fitur

- Gambar tanda tangan (garis halus mengikuti kecepatan goresan), mode ketik dengan font tulisan tangan, atau unggah foto tanda tangan (latar otomatis transparan)
- Banyak stempel per dokumen: tanda tangan, teks bebas, dan tanggal otomatis
- Editor penempatan visual: seret, ubah ukuran, atur transparansi, terapkan ke semua halaman
- Navigasi thumbnail halaman, zoom, undo/redo
- Deteksi PDF terkunci kata sandi/rusak dan batas ukuran 30 MB
- Isi dokumen tidak diubah — tanda tangan ditempel sebagai lapisan di atasnya

## Stack

Satu file HTML statis (HTML/CSS/JavaScript vanilla, tanpa framework, tanpa backend) dengan tiga library dari CDN jsDelivr:

- [signature_pad](https://github.com/szimek/signature_pad) — menggambar tanda tangan
- [PDF.js](https://mozilla.github.io/pdf.js/) (Mozilla) — render pratinjau PDF
- [pdf-lib](https://pdf-lib.js.org/) — menempel tanda tangan & ekspor PDF

## Menjalankan sendiri

Unduh `index.html`, lalu buka langsung di browser — atau hosting di layanan statis mana pun (Cloudflare Pages, Netlify, GitHub Pages, Vercel). Tidak ada proses build.

Situs resmi: [bytedash.tech](https://bytedash.tech/)

## Lisensi

MIT — lihat [LICENSE](LICENSE).
