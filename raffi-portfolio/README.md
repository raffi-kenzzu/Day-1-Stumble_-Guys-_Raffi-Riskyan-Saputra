# Portfolio — Raffi Riskyan Saputra

Website CV/portfolio statis menggunakan HTML, CSS, dan JavaScript.

## Cara menjalankan
1. Ekstrak file ZIP.
2. Buka folder `raffi-portfolio`.
3. Klik dua kali `index.html` untuk melihat website di browser.

## Cara mengubah isi
- Edit teks, sertifikat, pengalaman, email, dan tautan media sosial di `index.html`.
- Edit warna dan tampilan di `style.css`.
- Edit interaksi menu di `script.js`.
- Bagian foto saat ini masih berupa placeholder "RS". Ganti bagian `.avatar-placeholder` di `index.html` dengan elemen gambar, lalu simpan foto di folder `assets`.

Contoh mengganti placeholder foto:
```html
<div class="avatar-placeholder">
  <img src="assets/foto-raffi.jpg" alt="Foto Raffi">
</div>
```
Tambahkan CSS:
```css
.avatar-placeholder img {
  width: 100%;
  height: 100%;
  object-fit: cover;
  border-radius: 9px;
}
```

## Upload ke GitHub
1. Buat repository baru di GitHub, misalnya `raffi-portfolio`.
2. Upload seluruh isi folder ini (index.html, style.css, script.js, README.md, dan folder assets).
3. Buka **Settings → Pages**.
4. Pada **Build and deployment**, pilih **Deploy from a branch**.
5. Pilih branch `main` dan folder `/ (root)`, lalu klik **Save**.
6. Tunggu proses selesai. GitHub akan menampilkan alamat website di bagian Pages.

## Catatan
Konten pengalaman PKL dan sertifikat perlu kamu cocokkan dengan kegiatan serta dokumen asli. Jangan cantumkan tugas atau sertifikasi yang belum pernah kamu lakukan/peroleh.
