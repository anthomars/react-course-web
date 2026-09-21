# PremCourse

PremCourse adalah website katalog kursus online yang dibuat dengan React. Website ini menampilkan kelas terbaru, testimonial peserta, FAQ, serta halaman syarat dan ketentuan dalam antarmuka yang responsif.

## Fitur

- Landing page dengan hero section dan ajakan melihat kelas.
- Daftar kelas terbaru dan seluruh kelas beserta harga, rating, dan tombol pembelian.
- Carousel testimonial menggunakan Swiper.
- FAQ berbentuk accordion.
- Navigasi antarhalaman menggunakan React Router.
- Navbar yang berubah saat halaman di-scroll.
- Animasi halaman dengan Animate.css dan AOS.
- Layout responsif berbasis Bootstrap.

## Teknologi

- [React](https://react.dev/) 19
- [Vite](https://vite.dev/) 8
- [React Router](https://reactrouter.com/)
- [React Bootstrap](https://react-bootstrap.netlify.app/) dan Bootstrap 5
- [Swiper](https://swiperjs.com/)
- [AOS](https://michalsnik.github.io/aos/)
- Animate.css

## Persyaratan

- Node.js 20.19+ atau 22.12+
- npm

## Instalasi dan penggunaan

1. Clone repository dan masuk ke folder project.

   ```bash
   git clone <url-repository>
   cd react-course-web
   ```

2. Pasang dependency:

   ```bash
   npm install
   ```

3. Jalankan server development:

   ```bash
   npm run dev
   ```

   Buka alamat yang ditampilkan Vite, biasanya `http://localhost:5173`.

## Script npm

| Script | Keterangan |
| --- | --- |
| `npm run dev` | Menjalankan server development dengan hot reload |
| `npm run build` | Membuat build production di folder `dist` |
| `npm run preview` | Menjalankan preview dari build production |
| `npm run lint` | Memeriksa kode menggunakan Oxlint |

## Rute aplikasi

| Rute | Halaman |
| --- | --- |
| `/` | Beranda |
| `/kelas` | Daftar kelas |
| `/testimonial` | Testimonial peserta |
| `/faq` | Pertanyaan yang sering diajukan |
| `/terms` | Syarat dan ketentuan |

## Struktur direktori

```text
src/
├── assets/           # Gambar dan aset statis
├── components/       # Navbar, footer, FAQ, dan utilitas bersama
├── data/             # Data kelas, testimonial, navigasi, dan FAQ
├── pages/            # Komponen halaman berdasarkan rute
├── dist/css/         # CSS aplikasi
├── App.jsx           # Konfigurasi layout dan routing
└── main.jsx          # Entry point React
public/               # Favicon dan aset publik
```

## Build production

Gunakan perintah berikut untuk membuat bundle production:

```bash
npm run build
```

Hasil build berada di folder `dist` dan dapat disajikan menggunakan hosting statis apa pun yang mendukung single-page application (SPA).

## Catatan

Project ini saat ini merupakan frontend statis. Data kelas, testimonial, dan FAQ disimpan di `src/data/index.js`; belum tersedia backend, autentikasi, maupun proses pembayaran.

## Lisensi

Belum ada lisensi open source yang ditentukan untuk project ini.
