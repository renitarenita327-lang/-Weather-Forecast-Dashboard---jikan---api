# 🌤️ Favorite City Weather Dashboard

## Deskripsi

Favorite City Weather Dashboard adalah aplikasi web sederhana yang menampilkan informasi cuaca dari beberapa kota favorit menggunakan API cuaca. Aplikasi ini dibuat dengan HTML, CSS, dan JavaScript serta memanfaatkan data cuaca secara real-time melalui API.

Website ini memiliki tampilan yang responsif dan modern sehingga pengguna dapat melihat kondisi cuaca dengan mudah.

---

## Tujuan

* Mempelajari penggunaan API pada aplikasi web.
* Memahami cara mengambil data menggunakan JavaScript (`fetch`).
* Menampilkan data dari API ke dalam halaman website secara dinamis.
* Melatih kemampuan membuat antarmuka web yang menarik dan responsif.

---

## Fitur

* Menampilkan daftar kota favorit.
* Menampilkan informasi cuaca secara real-time.
* Menampilkan:
  * Nama kota
  * Suhu
  * Kondisi cuaca
  * Ikon cuaca
  * Kelembapan udara
  * Kecepatan angin
  * Lokasi
  * Grafik Suhu
* Tampilan responsif pada berbagai ukuran layar.
* Desain modern dengan hero section dan kartu cuaca.

---

## Teknologi yang Digunakan

* HTML5
* CSS3
* JavaScript (ES6)
* Weather API

---

## Struktur Folder

```text
Favorite-City-Weather-Dashboard/
│
├── index.html        # Halaman utama
├── style.css         # File tampilan website
├── script.js         # Mengambil dan menampilkan data API
└── README.md         # Dokumentasi proyek
```

---

## Cara Menjalankan

1. Unduh atau clone repository.
2. Buka folder proyek menggunakan Visual Studio Code.
3. Masukkan API Key pada file `script.js` 
4. Jalankan menggunakan Live Server atau buka file `index.html` melalui browser.
5. Data cuaca akan ditampilkan secara otomatis.

---

## Cara Kerja Aplikasi

1. Saat halaman dibuka, JavaScript akan mengirim permintaan ke Weather API.
2. API mengembalikan data cuaca dalam format JSON.
3. JavaScript membaca data tersebut.
4. Informasi cuaca ditampilkan ke dalam kartu-kartu pada halaman website.
5. Pengguna dapat melihat kondisi cuaca setiap kota secara langsung.

---

## Keunggulan Aplikasi
1. Antarmuka sederhana dan mudah digunakan.
2. Data diperoleh secara real-time.
3. Tidak memerlukan database.
4. Mudah dikembangkan menjadi aplikasi cuaca yang lebih kompleks.
5. Mendukung berbagai perangkat (Responsive Design).

## Kelebihan

1. Menggunakan data cuaca terbaru.
2. Struktur kode sederhana sehingga mudah dipelajari.
3. Cocok sebagai proyek pembelajaran API.
4. Desain modern dan menarik.
5. Mudah dikembangkan untuk fitur tambahan.

## Kekurangan
1. Membutuhkan koneksi internet.
2. Bergantung pada layanan Weather API.
3. Data tidak dapat ditampilkan apabila API mengalami gangguan.
5. Beberapa API memiliki batas jumlah request harian.

## Hasil

Aplikasi berhasil menampilkan informasi cuaca dari beberapa kota favorit secara real-time dengan antarmuka yang sederhana, menarik, dan mudah digunakan.

---

## Kesimpulan

Favorite City Weather Dashboard merupakan aplikasi web sederhana yang berhasil mengimplementasikan konsep pemrograman berbasis API. Aplikasi ini memanfaatkan HTML sebagai struktur halaman, CSS untuk mempercantik tampilan, serta JavaScript untuk mengambil, mengolah, dan menampilkan data cuaca secara dinamis dari Weather API.

Melalui proyek ini, pengembang memperoleh pemahaman mengenai proses komunikasi antara website dan server, penggunaan Fetch API, pengolahan data JSON, serta penerapan desain web yang responsif. Proyek ini menjadi dasar yang baik untuk mengembangkan aplikasi web yang lebih kompleks dengan integrasi layanan API lainnya.