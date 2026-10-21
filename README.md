# Tugas 2 — Pengembangan Aplikasi Web
### Mengenal HTML: Website ITERA dengan Struktur Semantik

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![W3C Validated](https://img.shields.io/badge/W3C-Valid%20HTML-1a4b8c?style=for-the-badge)
![Status](https://img.shields.io/badge/status-selesai-brightgreen?style=for-the-badge)

---

| | |
|---|---|
| **Nama**  | Farid Rizky Fauzan |
| **NIM**   | 124140210 |
| **Kelas** | RA |
| **Mata Kuliah** | Pengembangan Aplikasi Web |
| **Tugas** | Tugas 2 — Pertemuan 2: Mengenal HTML |

---

## Deskripsi

Website bertema **Institut Teknologi Sumatera (ITERA)** yang dibangun murni menggunakan **HTML5 semantik**. Fokus utama tugas ini adalah penerapan struktur dokumen yang benar dan bermakna (semantic markup), bukan tampilan visual.

Website terdiri dari dua halaman:

- **`index.html`** — Halaman utama berisi profil ITERA, visi & misi, serta tabel daftar program studi.
- **`berita.html`** — Halaman berita kampus dengan artikel-artikel yang disusun secara semantik.


---

## Elemen Semantik yang Digunakan

| Elemen | Fungsi |
|---|---|
| `<header>` | Logo, judul situs, dan navigasi utama |
| `<nav>` | Menu navigasi antar halaman |
| `<main>` | Konten inti halaman |
| `<section>` | Pengelompokan konten bertopik dengan heading sendiri |
| `<article>` | Konten mandiri (berita, visi, misi) |
| `<aside>` | Konten pendukung/tambahan |
| `<footer>` | Informasi penutup halaman & artikel |
| `<table>` | Data program studi (dengan `<thead>`, `<tbody>`, `<caption>`) |
| `<time>` | Tanggal publikasi berita yang terbaca mesin |

---

## Hasil Validasi W3C

Kedua halaman telah divalidasi menggunakan **[W3C Nu Html Checker](https://validator.w3.org/nu/)**:

| Halaman | Status |
|---|---|
| `index.html` | ✅ No errors or warnings |
| `berita.html` | ✅ No errors or warnings |

> 📄 Bukti validasi lengkap tersedia di file dokumentasi (`Tugas2-dokumentasi.pdf`).

---

<p align="center">Dibuat untuk memenuhi Tugas 2 — Pengembangan Aplikasi Web, Teknik Informatika ITERA</p>

---

# Tugas 3 — Pengembangan Aplikasi Web

### Formulir Pendaftaran & Halaman Detail (Query String)

Halaman web dua layar bertema **elegant modern** dengan form `method="get"`
yang meneruskan data pendaftar ke halaman detail melalui query string.

| | |
|---|---|
| **Nama** | Farid Rizky Fauzan |
| **NIM** | 124140210 |
| **Kelas** | RA |
| **Folder** | [`task_3/`](task_3) |

**Halaman:**

- [`task_3/index.html`](task_3/index.html) — formulir pendaftaran (`method="get"`).
- [`task_3/detail.html`](task_3/detail.html) — ringkasan pendaftar dari query string
  (menampilkan data dummy jika dibuka tanpa parameter).

**Pemenuhan kriteria:**

| Kriteria | Implementasi |
|---|---|
| Dua halaman | Formulir + halaman detail |
| Form method GET | `action="detail.html" method="get"` |
| Data via query string | `nama`, `nim`, `email`, `telepon`, `prodi`, `angkatan`, `gender`, `alamat` |
| Halaman detail dummy | Data contoh tampil saat tidak ada query string |
| Tidak menangkap data | Tanpa backend, cookie, atau penyimpanan |
| Minimal 3 selector CSS | 40+ selector (class, element, pseudo-class, media query) |
| Layout, box, tabel, form | CSS Grid, card, tabel data, styling form |

Dokumentasi lengkap: [`task_3/README.md`](task_3/README.md).
