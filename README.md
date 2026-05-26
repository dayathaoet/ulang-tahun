# Selamat Ulang Tahun 🎂🌸

Proyek ini adalah halaman ucapan ulang tahun interaktif berbasis **HTML + Three.js** dengan elemen 3D dan interaksi sederhana.

## Fitur Utama

- Tampilan kue ulang tahun 3D dengan animasi masuk.
- Teks lilin angka **"30"** di atas kue.
- Efek meniup lilin:
  - Tekan tombol **B** pada keyboard, atau
  - Klik pada api/lilin di area 3D.
- Musik latar (`music/music.mp3`) dengan tombol kontrol suara.
- Surat ucapan yang bisa dibuka lewat tombol **📜 Surat**.
- Kamera 3D dapat diputar (OrbitControls) sehingga objek bisa dilihat dari berbagai sudut.

## Struktur Proyek

\`\`\`
.
├── index.html
└── music/
    └── music.mp3
\`\`\`

## Cara Menjalankan

1. Pastikan semua file ada pada struktur folder di atas.
2. Buka file **index.html** di browser (double click atau via local server).
3. Jika musik tidak otomatis jalan (kebijakan browser), klik layar sekali atau tekan tombol musik.

## Kontrol

- **Putar kamera**: drag pada area canvas.
- **Zoom**: scroll mouse.
- **Tiup lilin**: tekan **B** atau klik api/lilin.
- **Buka surat**: klik tombol **📜 Surat**.
- **Tutup surat**: klik tombol **✕** atau area luar kartu surat.

## Teknologi

- HTML5
- CSS3
- JavaScript (ES Module)
- [Three.js](https://threejs.org/) via CDN:
  - `three.module.js`
  - `OrbitControls`
  - `FontLoader`
  - `TextGeometry`

## Catatan

- Proyek ini menggunakan import module dari CDN (`unpkg`), sehingga membutuhkan koneksi internet saat dijalankan.
- File musik lokal digunakan dari path: `music/music.mp3`.
