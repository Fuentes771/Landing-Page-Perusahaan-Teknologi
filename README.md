# QuantumNet — Landing Page (Tailwind CSS Only)

Landing page responsif untuk perusahaan teknologi "QuantumNet" yang berfokus pada cybersecurity dan jaringan berbasis AI.

Website ini dibangun hanya dengan HTML + Tailwind CSS (tanpa JavaScript framework dan tanpa bundler). Navigasi mobile menggunakan teknik CSS-only.

## ✨ Fitur Utama

- Header/Navigation: Logo dan menu responsif
- Hero Section: Headline, subjudul, CTA ganda, dan ilustrasi SVG
- Features Section: 3 kartu fitur dengan ikon dan deskripsi
- About Section: Informasi perusahaan + ringkasan solusi
- Contact Form: Form kontak yang sudah di-style (name, email, company, phone, message)
- Footer: Copyright dan social media links

## 🧭 Brand — QuantumNet

- Fokus: Keamanan siber dan jaringan berbasis AI
- Deskripsi: "QuantumNet melindungi sistem digital perusahaan dengan solusi keamanan siber cerdas dan analisis real-time."

## 🧱 Teknologi

- HTML5 statis
- Tailwind CSS
- SVG (inline dan aset logo)

## 📂 Struktur Proyek

```
.
├── assets/
│   └── logo.svg         # Logo QuantumNet (SVG)
├── css/
│   ├── styles.css       # Style Global
├── index.html           # Halaman landing utama
├── LICENSE
└── README.md
```

## 🚀 Cara Menjalankan Lokal

Tidak ada build atau dependency. Cukup buka file `index.html` di browser modern.

- Windows: klik dua kali `index.html` atau buka dengan Edge/Chrome/Firefox
- Alternatif (opsional): jalankan server statis untuk live reload/port tetap

## 🌐 Deploy ke GitHub Pages

1. Commit dan push ke branch `main` repositori ini.
2. Buka Settings → Pages.
3. Pilih "Deploy from a branch", Branch: `main` dan Folder: `/root`.
4. Simpan. Halaman akan tersedia pada URL GitHub Pages repositori Anda.

## 🧰 Kustomisasi Cepat

- Ganti konten brand, headline, dan CTA di section Hero pada `index.html`.
- Update ikon/lorem di bagian Fitur sesuai kebutuhan produk.
- Atur social links di Footer (LinkedIn, GitHub).
- Ubah warna dan nuansa UI dengan utilitas Tailwind (`bg-…`, `text-…`, `from-…`, `to-…`).

## 🔐 Integrasi Form (Saran)

Form saat ini tidak terkoneksi backend (action `#`). Untuk saran selanjutnya, sambungkan ke:

- Layanan form statis (mis. Formspree, Getform) atau
- Endpoint backend Anda (mis. `/api/contact`)

Pastikan melakukan validasi sisi server dan perlindungan spam (captcha/rate limit) jika dibutuhkan.

## 📝 Lisensi

Proyek ini berada di bawah lisensi yang tercantum pada berkas `LICENSE`.