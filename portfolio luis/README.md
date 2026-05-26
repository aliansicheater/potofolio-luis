# Portfolio Luis Ismail, S.Tr.Kom

Web portfolio profesional dengan WebGL animated background.

## 🚀 Deploy ke Vercel

### Cara 1 — Drag & Drop (Paling Mudah)
1. Buka [vercel.com](https://vercel.com) → Login / daftar gratis
2. Klik **"Add New Project"**
3. Pilih **"Browse"** → upload folder ini
4. Klik **Deploy** → selesai! URL siap dalam ~1 menit

### Cara 2 — Via GitHub
1. Upload folder ini ke GitHub repository baru
2. Buka [vercel.com](https://vercel.com) → **"Import Git Repository"**
3. Pilih repo → Deploy

### Cara 3 — Vercel CLI
```bash
npm i -g vercel
cd portfolio/
vercel --prod
```

## 📁 Struktur File
```
portfolio/
├── vercel.json          ← konfigurasi Vercel
└── public/
    ├── index.html       ← halaman utama
    ├── photo.jpg        ← foto utama (seragam PNS coklat)
    ├── photo-formal.jpg ← foto formal (seragam putih)
    └── sertifikat.pdf   ← sertifikat Google Gemini Educator
```

## ✨ Fitur
- WebGL animated background dengan mouse tracking
- Progressive asset loading dengan loader animasi
- Custom cursor
- Scroll reveal animations
- Modal sertifikat PDF
- Fully responsive (mobile-friendly)
- SEO-ready
