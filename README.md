# 📖 Novelita – Website Novel Remaja

Website katalog novel remaja bertema **pink + biru** yang imut. Pilih genre, cari judul, lalu klik sampul buku untuk melihat **sekilas cerita, ilustrasi adegan, kutipan favorit, dan tokoh-tokohnya**.

## ✨ Fitur
- 4 genre: 💖 Romance, ⚡ Action, 🔮 Fiksi, 🧭 Adventure
- Filter genre dan pencarian judul/penulis secara langsung
- Pop-up detail buku: sinopsis, 3 ilustrasi adegan, kutipan, profil tokoh
- Semua ilustrasi berupa SVG buatan sendiri (tanpa gambar eksternal)
- Responsif untuk HP dan laptop, mendukung navigasi keyboard
- Tanpa framework dan tanpa instalasi

## 📁 Struktur Proyek
```
novelita/
├── index.html   # kerangka halaman
├── style.css    # tema pink-biru dan animasi
├── script.js    # data buku, filter, dan pop-up detail
└── README.md
```

## 🚀 Cara Menjalankan
1. Unduh atau *clone* repositori ini.
2. Buka `index.html` di browser. Selesai!

## 🌐 Publikasi dengan GitHub Pages
1. Buat repositori baru di GitHub, lalu unggah semua file.
2. Buka **Settings → Pages**.
3. Pada *Source*, pilih **Deploy from a branch**, branch `main`, folder `/ (root)`.
4. Simpan, lalu tunggu beberapa menit. Situs akan aktif di `https://username.github.io/nama-repo/`.

Atau lewat terminal:
```bash
git init
git add .
git commit -m "Website novel remaja pertama"
git branch -M main
git remote add origin https://github.com/username/nama-repo.git
git push -u origin main
```

## ➕ Menambah Buku Baru
Buka `script.js`, lalu tambahkan objek baru di array `BOOKS`:
```js
{ id: 9, title: "Judul Buku", author: "Nama Penulis", genre: "romance", // romance | action | fiksi | adventure
  pages: 200, rating: 4.5, age: "13+",
  c1: "#FF8FB8", c2: "#B8E1FF", icon: "heart",
  synopsis: "Sinopsis singkat…",
  quote: "Kutipan favorit…",
  scenes: [["heart","star","Caption adegan 1"], ["moon","heart","Caption 2"], ["star","heart","Caption 3"]],
  chars: ["Tokoh A – deskripsi", "Tokoh B – deskripsi"] }
```
Ikon yang tersedia: `moon, heart, star, bolt, shield, planet, rocket, compass, mountain, cat, cup, door, mail`.

## 🎨 Palet Warna
| Nama | Hex |
|---|---|
| Pink permen | `#FF8FB8` |
| Biru langit | `#7CC8FF` |
| Ungu tinta (teks) | `#3B2A63` |
| Kuning bintang | `#FFE08A` |

## 📌 Catatan
Judul, penulis, dan isi cerita pada contoh ini fiktif dan dibuat sebagai contoh. Ganti dengan koleksi novelmu sendiri.

## 📄 Lisensi
Bebas dipakai dan dimodifikasi untuk belajar (MIT License).
