# Tugas Individu 3 — Formulir Pendaftaran & Halaman Detail

Halaman web sederhana bertema **elegant modern** yang memenuhi kriteria Tugas
Individu 3 mata kuliah Pengembangan Aplikasi Web.

| | |
|---|---|
| **Nama** | Farid Rizky Fauzan |
| **NIM** | 124140210 |
| **Kelas** | RA |
| **Mata Kuliah** | Pengembangan Aplikasi Web |
| **Folder** | `task_3` |

---

## Struktur Folder

```
task_3/
├── index.html          # Halaman pendaftaran (form method GET)
├── detail.html         # Halaman detail / ringkasan pendaftar
├── assets/
│   └── style.css       # Seluruh desain (layout, box, tabel, form)
└── README.md
```

## Dua Halaman

| Halaman | Fungsi |
|---|---|
| `index.html` | Formulir pendaftaran dengan `method="get"` dan `action="detail.html"` |
| `detail.html` | Menampilkan data pendaftar dari query string (fallback data dummy) |

## Pemenuhan Kriteria

| Kriteria | Implementasi |
|---|---|
| Form dengan method GET | `<form action="detail.html" method="get">` |
| Data dilempar via query string | Field `nama`, `nim`, `email`, `telepon`, `prodi`, `angkatan`, `gender`, `alamat` |
| Halaman detail berisi data dummy | Data contoh ditampilkan saat `detail.html` dibuka tanpa query string |
| Tidak menangkap/menyimpan data | Tidak ada backend, `localStorage`, cookie, maupun pengiriman data ke server |
| Minimal 3 selector CSS | Lebih dari 40 selector (class, element, pseudo-class, media query) |
| Layout, box, tabel, form memakai CSS | CSS Grid, card/box dengan border & shadow, tabel data, styling form |

## Cara Menjalankan

Buka `index.html` langsung di browser, isi formulir, lalu tekan
**Kirim & Lihat Detail**. Browser akan membuka:

```
detail.html?nama=...&nim=...&email=...&telepon=...&prodi=...&angkatan=...&gender=...&alamat=...&syarat=setuju
```

Halaman detail membaca query string tersebut untuk ditampilkan pada tabel.
Jika dibuka tanpa parameter, halaman menampilkan data dummy.

> Catatan: JavaScript pada `detail.html` hanya dipakai untuk **menampilkan**
> query string ke tabel. Tidak ada data yang dikirim, disimpan, atau diproses
> lebih lanjut.
