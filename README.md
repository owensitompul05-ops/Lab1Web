# Lab1Web — Praktikum 1: HTML Dasar

Repository ini berisi tugas Praktikum 1 mata kuliah Pemrograman Web,
membahas struktur dokumen HTML, tag, atribut, heading, paragraf,
pemformatan teks, hyperlink, gambar, list, dan komentar HTML.

## Struktur Folder

Lab1Web/
├── index.html
├── halaman2.html
├── images/
│   ├── profil.jpg
│   └── capture.png
└── README.md


## Penjelasan Langkah Praktikum

### 1. Membuat Struktur Dasar HTML
File `index.html` dibuat dengan struktur dasar HTML5: `<!DOCTYPE html>`,
`<html>`, `<head>` (berisi `<title>`), dan `<body>`.

### 2. Membuat Paragraf
Dua paragraf ditambahkan menggunakan tag `<p>` untuk menjelaskan topik
pembelajaran HTML dasar.

### 3. Menambahkan Judul
Heading `<h1>` digunakan untuk judul utama ("Profil Mahasiswa") dan
`<h2>` untuk subjudul seperti "Data Diri", "Keahlian", dan "Target
Belajar".

### 4. Memformat Teks
Tag `<b>`, `<i>`, dan `<strong>` digunakan untuk menebalkan/memiringkan
teks penting. Tag `<sub>` dan `<sup>` digunakan pada contoh notasi
H₂O dan x².

### 5. Menyisipkan Gambar
Gambar profil disimpan di folder `images/` dan ditampilkan dengan tag
`<img>` beserta atribut `src`, `width`, `alt`, dan `title`.

### 6. Mengatur Ukuran Gambar
Atribut `width` digunakan untuk mengatur lebar tampilan gambar tanpa
mengubah file aslinya.

### 7. Menambahkan Hyperlink
Dibuat file `halaman2.html` sebagai halaman kedua. Navigasi antar
halaman dibuat dengan tag `<a>` dan atribut `href`, termasuk tautan ke
website eksternal (Google) dan anchor link menuju bagian tertentu pada
halaman (`#materi`).

### 8. Menambahkan List
Daftar keahlian dibuat dengan `<ul>` (unordered list) dan daftar target
belajar dibuat dengan `<ol>` (ordered list).

### 9. Menambahkan Komentar
Komentar HTML (`<!-- ... -->`) ditambahkan pada beberapa bagian kode
untuk menandai section tertentu, seperti bagian navigasi, profil, dan
keahlian.

### 10. Menggabungkan Semua Elemen
Seluruh elemen di atas digabungkan menjadi satu halaman utuh pada
`index.html` sebagai halaman Profil Mahasiswa.

## Screenshot

![Capture Output](images/capture.png)

## Jawaban Pertanyaan Praktikum

1. **Fungsi `<!DOCTYPE html>`** — Memberitahu browser bahwa dokumen
    menggunakan standar HTML5, agar browser me-render halaman sesuai
    standar tersebut.
2. **Perbedaan tag, elemen, dan atribut** — Tag adalah penanda
    pembuka/penutup (`<p>`, `</p>`); elemen adalah gabungan tag
    pembuka, isi, dan tag penutup; atribut adalah informasi tambahan
    yang ditulis di dalam tag pembuka (misalnya `href`, `src`).
3. **Perbedaan `<p>` dan `<br>`** — `<p>` membuat paragraf baru dengan
    jarak/margin di atas dan bawahnya, sedangkan `<br>` hanya
    memindahkan teks ke baris baru tanpa membuat paragraf baru.
4. **Fungsi atribut `href`** — Menentukan URL atau alamat tujuan dari
    sebuah hyperlink pada tag `<a>`.
5. **Hyperlink internal vs eksternal** — Hyperlink internal mengarah
    ke halaman/bagian dalam website yang sama (misalnya
    `halaman2.html`), sedangkan hyperlink eksternal mengarah ke website
    lain di luar domain (misalnya `https://www.google.com`).
6. **Fungsi `src` dan `alt` pada `<img>`** — `src` menentukan lokasi
    atau path file gambar yang ditampilkan, sedangkan `alt` memberikan
    teks alternatif jika gambar gagal dimuat serta membantu
    aksesibilitas.
7. **Perbedaan `<ul>` dan `<ol>`** — `<ul>` menampilkan daftar tanpa
    urutan/nomor (bullet), sedangkan `<ol>` menampilkan daftar
    berurutan dengan nomor.
8. **Jika path gambar salah** — Gambar tidak akan tampil di browser,
    biasanya hanya muncul ikon gambar rusak beserta teks dari atribut
    `alt`.
9. **Pentingnya struktur heading terstruktur (h1–h6)** — Membantu
    pembaca dan mesin pencari memahami hierarki dan struktur konten
    halaman, serta meningkatkan aksesibilitas dan SEO.
10. **Fungsi komentar `<!-- ... -->`** — Memberi catatan/penjelasan
     pada kode tanpa ditampilkan di browser, serta dapat digunakan
     untuk menonaktifkan sementara bagian kode saat proses pengembangan.

---
Dibuat untuk memenuhi tugas Praktikum 1: HTML Dasar — Mata Kuliah
Pemrograman Web, Universitas Pelita Bangsa.