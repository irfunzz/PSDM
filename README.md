## ✨ PSDM — Astra Magnifica

![Astra Magnifica]
*Website resmi Divisi Pengembangan Sumber Daya Manusia (PSDM) untuk rangkaian acara Astra Magnifica*

Repositori ini berisi **halaman web statis** berbasis HTML, CSS, dan JavaScript yang ringan, responsif, serta mudah dikustomisasi sebagai media informasi, presentasi, dan dekorasi visual selama event berlangsung.

---

## 📘 Tentang Proyek

Website ini dibuat khusus untuk mendukung Divisi PSDM pada event **Astra Magnifica** dengan berbagai halaman interaktif dan tematik:

- `index.html` → Landing page utama  
- `countdown.html` → Countdown menuju acara  
- `adventure-start.html` → Halaman bertema petualangan  
- `indexstarwars.html` → Halaman bertema Star Wars  
- `thankyou.html` → Halaman ucapan terima kasih  
- `sorry.html` → Custom error / “sorry” page  

Semua halaman dapat digunakan sebagai media presentasi, dekorasi digital, atau informasi tambahan selama rangkaian kegiatan.

---

## 📂 Struktur Direktori
```
```plaintext
PSDM/
├── index.html              # Landing page utama
├── countdown.html          # Halaman countdown acara
├── adventure-start.html    # Halaman tema petualangan
├── indexstarwars.html      # Halaman tema Star Wars
├── thankyou.html           # Halaman ucapan terima kasih
├── sorry.html              # Custom error / sorry page
├── assets/                 # gambar, font, icon (opsional)
├── css/
│   └── style.css
└── js/
    ├── main.js
    └── countdown.js
```
---

## 🚀 Cara Menjalankan Proyek

Proyek ini **100% client-side**, tidak memerlukan server.

```bash
# 1. Clone repositori
git clone https://github.com/irfunzz/PSDM.git
cd PSDM

# 2. Buka file HTML langsung di browser
# Misalnya:
open index.html          # macOS
start index.html         # Windows
xdg-open index.html      # Linux
```

Atau cukup drag & drop file HTML ke browser favoritmu!

---

## 🎨 Kustomisasi

Semua elemen mudah diubah sesuai identitas visual Astra Magnifica:

| Elemen              | File yang diedit                  | Keterangan                              |
|---------------------|-----------------------------------|-----------------------------------------|
| Warna & Font        | `css/style.css`                   | Ubah variabel CSS atau override class  |
| Teks & Konten       | File `.html` masing-masing        | Edit langsung di dalam tag HTML         |
| Animasi & Interaksi | `js/main.js`, `js/countdown.js`   | Tambah/modifikasi efek JavaScript       |
| Gambar & Aset       | `assets/`                         | Ganti dengan aset resmi event           |
| Tema Khusus         | File HTML tema (adventure/starwars) | Sesuaikan cerita & visual               |

---

## 🌐 Deployment (Hosting)

Proyek siap di-deploy ke hosting statis gratis:

### Rekomendasi:
- **GitHub Pages** (paling mudah)
- Netlify
- Vercel
- Cloudflare Pages

### Deploy ke GitHub Pages (cepat):
1. Buka **Settings** → **Pages**
2. Pilih branch `main` → folder `/ (root)`
3. Save → situs otomatis live dalam 1-2 menit!

Contoh URL: `https://irfunzz.github.io/PSDM`

---

## 📄 Lisensi

- Konten dan kode yang dibuat oleh Divisi PSDM dapat digunakan secara **bebas** untuk keperluan internal maupun publik Astra Magnifica.
- Jika menggunakan template/aset pihak ketiga (contoh: HTML5UP, dll), wajib mematuhi lisensi aslinya.

---

## 🤝 Kontribusi

Kontribusi sangat terbuka dari seluruh anggota Divisi PSDM & panitia Astra Magnifica!

### Cara berkontribusi:
```bash
# 1. Fork repositori ini
# 2. Buat branch baru
git checkout -b fitur/nama-fitur

# 3. Lakukan perubahan
# 4. Commit & push
git commit -m "Menambahkan fitur XYZ"
git push origin fitur/nama-fitur

# 5. Buat Pull Request dengan deskripsi jelas

**Divisi PSDM Astra Magnifica 2024**  
*May the force of human development be with you.* 🌟
