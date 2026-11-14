# Halo, Dunia

Website hello world sederhana dengan tampilan minimalis dan modern. HTML dan CSS dipisah ke dalam file masing-masing, tanpa framework dan tanpa proses build.

## Fitur

- HTML di `index.html` dan CSS di `style.css` (terpisah, tanpa JavaScript)
- Tampilan responsif untuk desktop dan ponsel
- Mengikuti mode gelap atau terang sesuai pengaturan perangkat
- Menghormati pengaturan "kurangi gerakan" (reduced motion)
- Font dari Google Fonts dengan cadangan font sistem

## Struktur Proyek

```
.
├── index.html   # Halaman utama (HTML)
├── style.css    # Gaya tampilan (CSS)
└── README.md    # Dokumentasi ini
```

## Cara Menjalankan

1. Unduh atau salin `index.html` dan `style.css` ke folder yang sama.
2. Buka `index.html` langsung di browser (klik dua kali atau seret ke jendela browser).

Tidak perlu instalasi apa pun.

## Cara Mengubah

- **Teks:** edit isi tag `<h1>` dan `<p class="lead">` di `index.html`.
- **Warna:** ubah variabel di blok `:root` pada `style.css`.
- **Font:** ganti tautan Google Fonts di `<head>` `index.html`, lalu sesuaikan nama font di `font-family` pada `style.css`.

## Teknologi

- HTML5
- CSS3 (variabel CSS, media query, dan animasi sederhana)
- Google Fonts: