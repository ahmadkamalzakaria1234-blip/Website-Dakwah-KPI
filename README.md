# TUGAS KELOMPOK
**Mata Kuliah:** Perancangan Sistem Informasi
**Topik:** Arsitektur Informasi: Taksonomi, Labeling, dan Navigasi Pesan
**Program Studi:** Komunikasi dan Penyiaran Islam (KPI)

---

## Studi Kasus: Rancang Website Dakwah Mahasiswa KPI

**Instruksi:**
Anda diminta untuk merancang Arsitektur Informasi untuk sebuah website bernama **"Dakwah KPI"**. Website ini ditujukan untuk mahasiswa dan masyarakat umum yang ingin belajar Islam secara modern.

---

## Tugas 1: Struktur Taksonomi

### Pengertian
Taksonomi adalah skema **pengelompokan informasi** berdasarkan kategori-kategori tertentu agar konten dapat ditemukan dengan mudah oleh pengguna. Dalam website **Dakwah KPI**, kami menggunakan taksonomi **hierarkis (bertingkat)** sebagai dasar utama, karena sesuai dengan sistematika keilmuan Islam yang sudah dikenal masyarakat.

### Struktur Taksonomi Website Dakwah KPI

- **Beranda**
- **Aqidah** (Kategori 1)
  - Rukun Iman & Maknanya
  - Tauhid Uluhiyah & Rububiyah
  - Mengenal Asmaul Husna
  - Iman kepada Hari Akhir
  - Menjawab Syubhat Aqidah
- **Fiqih & Ibadah** (Kategori 2)
  - Panduan Shalat Lengkap
  - Tata Cara Puasa & Zakat
  - Fiqih Muamalah Modern
  - Fiqih Pernikahan & Keluarga
  - Tanya Jawab Hukum Islam
- **Akhlak** (Kategori 3)
  - Akhlak di Era Digital
  - Tips Menjaga Lisan di Era Digital
  - Adab Pergaulan Islami
  - Sabar & Syukur dalam Kehidupan
  - Mengelola Emosi secara Islami
- **Sejarah Islam** (Kategori 4)
  - Sirah Nabawiyah
  - Kisah Para Sahabat
  - Peradaban Islam Klasik
  - Islam di Nusantara
  - Tokoh Ulama Inspiratif
- **Al-Qur'an & Hadis** (Kategori 5)
  - Tadabbur Ayat Pilihan
  - Tafsir Tematik Modern
  - Hadis Pilihan Kehidupan
  - Belajar Tajwid Dasar
  - Program Hafalan Qur'an
- **Dakwah Digital** (Kategori 6)
  - Konten Dakwah Media Sosial
  - Podcast & Video Ceramah
  - Literasi Digital Islami
  - Komunitas & Forum Diskusi
  - Kalender Kajian Online
- **Tanya Ustaz** (Layanan)

### Diagram Pohon (Tree Structure)

```
Dakwah KPI
|
+-- Beranda
|
+-- Aqidah
|   +-- Rukun Iman & Maknanya
|   +-- Tauhid Uluhiyah & Rububiyah
|   +-- Mengenal Asmaul Husna
|   +-- Iman kepada Hari Akhir
|   \-- Menjawab Syubhat Aqidah
|
+-- Fiqih & Ibadah
|   +-- Panduan Shalat Lengkap
|   +-- Tata Cara Puasa & Zakat
|   +-- Fiqih Muamalah Modern
|   +-- Fiqih Pernikahan & Keluarga
|   \-- Tanya Jawab Hukum Islam
|
+-- Akhlak
|   +-- Akhlak di Era Digital
|   +-- Tips Menjaga Lisan di Era Digital  **(fokus studi kasus)**
|   +-- Adab Pergaulan Islami
|   +-- Sabar & Syukur dalam Kehidupan
|   \-- Mengelola Emosi secara Islami
|
+-- Sejarah Islam
|   +-- Sirah Nabawiyah
|   +-- Kisah Para Sahabat
|   +-- Peradaban Islam Klasik
|   +-- Islam di Nusantara
|   \-- Tokoh Ulama Inspiratif
|
+-- Al-Qur'an & Hadis
|   +-- Tadabbur Ayat Pilihan
|   +-- Tafsir Tematik Modern
|   +-- Hadis Pilihan Kehidupan
|   +-- Belajar Tajwid Dasar
|   \-- Program Hafalan Qur'an
|
+-- Dakwah Digital
|   +-- Konten Dakwah Media Sosial
|   +-- Podcast & Video Ceramah
|   +-- Literasi Digital Islami
|   +-- Komunitas & Forum Diskusi
|   \-- Kalender Kajian Online
|
\-- Tanya Ustaz
```

### Prinsip yang Digunakan

| Prinsip | Penerapan dalam Dakwah KPI |
| :--- | :--- |
| **Konsisten** | Semua kategori menggunakan nama disiplin ilmu Islam yang sudah dikenal (Aqidah, Fiqih, Akhlak, dst.). |
| **Mudah Dipahami** | Menghindari istilah teknis yang asing; menggunakan bahasa yang akrab di kalangan mahasiswa dan masyarakat umum. |
| **Relevan** | Setiap kategori dipilih berdasarkan kebutuhan nyata target pengguna: mahasiswa KPI dan masyarakat yang ingin belajar Islam modern. |

---

## Tugas 2: Labeling

### Pengertian
Labeling adalah proses **pemberian nama atau istilah** pada setiap elemen dalam sistem informasi. Label yang baik menjadi jembatan bahasa antara sistem dengan pemahaman pengguna, sehingga pengguna langsung mengerti isi sebelum mengklik.

### Daftar Labeling Menu & Kategori

| Label | Posisi | Mengapa Label Ini Dipilih |
| :--- | :--- | :--- |
| **Beranda** | Menu utama (posisi 1) | Istilah universal yang sudah dikenali semua kalangan sebagai halaman pembuka website. |
| **Aqidah** | Menu utama (posisi 2) | Istilah resmi keilmuan Islam yang langsung dipahami oleh mahasiswa KPI dan masyarakat Muslim umum. |
| **Fiqih & Ibadah** | Menu utama (posisi 3) | Menggabungkan dua konsep agar cakupannya jelas: teori hukum Islam sekaligus praktik ibadah sehari-hari. |
| **Akhlak** | Menu utama (posisi 4) | Satu kata yang padat makna, sangat relevan dengan kehidupan digital generasi muda. |
| **Sejarah Islam** | Menu utama (posisi 5) | Label deskriptif yang langsung menjelaskan isi tanpa jargon, mudah dipahami siapapun. |
| **Al-Qur'an & Hadis** | Menu utama (posisi 6) | Menggabungkan dua sumber utama Islam dalam satu menu sehingga pengguna tidak perlu mencari di dua tempat berbeda. |
| **Dakwah Digital** | Menu utama (posisi 7) | Membedakan konten berbasis teknologi dari konten teks biasa; menarik perhatian generasi muda. |
| **Tanya Ustaz** | Tombol CTA (kanan atas) | Label aksi yang mengundang interaksi, terasa personal, hangat, dan membangun koneksi dengan pengguna. |
| **Tips Menjaga Lisan di Era Digital** | Konten di bawah Akhlak | Judul spesifik yang menjawab kebutuhan nyata: bagaimana beretika dalam komunikasi di media sosial. |
| **Kajian Terbaru** | Sidebar / Footer | Menunjukkan konten yang segar dan aktual, mendorong pengguna untuk kembali mengunjungi website. |

### Perbandingan: Label Buruk vs Label Baik

| Label Buruk (Ambigu) | Label Baik (Jelas & Komunikatif) | Analisis |
| :--- | :--- | :--- |
| **Konten** | **Artikel Islami** | "Konten" terlalu umum. "Artikel Islami" langsung memberikan kejelasan tentang isi dan topiknya. |
| **Media** | **Video Kajian** | "Media" bisa berarti gambar, video, atau audio. "Video Kajian" jauh lebih spesifik dan informatif. |
| **Info** | **Jadwal Kajian & Info Terbaru** | "Info" terlalu luas. Memisahnya menjadi label yang spesifik membantu pengguna menemukan apa yang mereka cari. |
| **Layanan** | **Tanya Ustaz** | "Layanan" terasa korporat dan dingin. "Tanya Ustaz" lebih komunikatif dan membangun rasa kedekatan. |
| **Materi** | **Kajian Tauhid** | "Materi" tidak memberikan konteks apapun. "Kajian Tauhid" langsung memberikan nilai dakwah yang spesifik. |

### Prinsip Labeling yang Diterapkan

1. **Jelas dan Sederhana:** Menggunakan kosakata yang umum dan mudah dimengerti oleh seluruh target audiens, dari mahasiswa hingga masyarakat awam.
2. **Konsisten:** Gaya penulisan seragam di seluruh halaman; tidak berganti-ganti antara "Kajian", "Pengajian", dan "Materi" untuk konten yang sama.
3. **Berorientasi Pengguna:** Label dipilih dari sudut pandang audiens — "Apa yang mereka cari?" bukan "Apa yang ingin kita beri nama?"
4. **Ringkas:** Maksimal 3–4 kata per label menu agar nyaman dibaca di layar kecil (perangkat mobile).

---

## Tugas 3: Rancang Navigasi

### Pengertian
Navigasi adalah mekanisme yang memungkinkan pengguna untuk **bergerak** dari satu halaman ke halaman lain dalam sistem informasi. Navigasi yang baik memastikan pengguna tidak "tersesat" dan dapat menemukan konten yang mereka inginkan dengan cepat dan mudah.

### Skenario User Flow

**Tujuan:** Pengguna ingin menemukan konten **"Tips Menjaga Lisan di Era Digital"** yang berada di bawah kategori **Akhlak**.

#### Alur Navigasi (User Flow)

```
[MULAI]
   |
   v
[1] Pengguna membuka website Dakwah KPI
    (mengetik URL atau mengklik tautan dari media sosial)
   |
   v
[2] Halaman Beranda (Home) ditampilkan
    --> Pengguna melihat menu navigasi utama di bagian atas halaman
   |
   |-----------------------------------------------|
   | Jalur A: Navigasi Manual                      | Jalur B: Fitur Pencarian
   v                                               v
[3A] Klik menu "Akhlak"                       [3B] Klik ikon Search
     di navigasi utama (navbar)                    --> Ketik: "menjaga lisan"
   |                                               |
   v                                               |
[4A] Halaman Kategori Akhlak terbuka               |
     --> Pengguna melihat daftar sub-kategori      |
         dan artikel dalam kategori Akhlak         |
   |                                               |
   |-----------------------------------------------|
   |
   v
[5] Pengguna menemukan dan mengklik judul artikel:
    +-------------------------------------------------------+
    |  "Tips Menjaga Lisan di Era Digital"                  |
    |   Kategori: Akhlak > Akhlak di Era Digital            |
    +-------------------------------------------------------+
   |
   v
[6] Halaman artikel terbuka -- pengguna membaca konten
   |
   v
[7] Di bagian bawah artikel, sistem menampilkan:
    "Artikel Terkait di Kategori Akhlak"
    --> Pengguna dapat melanjutkan membaca konten lain
   |
   v
[SELESAI]
```

#### Penjelasan Setiap Langkah

| Langkah | Aksi Pengguna | Tampilan/Respons Sistem |
| :--- | :--- | :--- |
| **1** | Membuka browser, mengetik URL atau klik tautan | Halaman Beranda (Home) dimuat |
| **2** | Melihat tampilan Beranda | Navbar dengan 7 menu utama tampil di bagian atas |
| **3A** | Klik menu **"Akhlak"** di navbar | Halaman kategori Akhlak terbuka |
| **3B** | Klik ikon Search, ketik kata kunci | Hasil pencarian muncul, artikel relevan ditampilkan |
| **4** | Melihat daftar konten kategori Akhlak | Daftar sub-kategori dan artikel ditampilkan |
| **5** | Klik judul **"Tips Menjaga Lisan di Era Digital"** | Halaman artikel penuh terbuka |
| **6** | Membaca artikel | Konten lengkap, gambar, dan poin-poin ditampilkan |
| **7** | Selesai membaca | Sistem merekomendasikan artikel terkait di kategori Akhlak |

### Breadcrumb Navigasi

Breadcrumb menunjukkan posisi pengguna di dalam struktur website secara real-time:

```
Beranda  >  Akhlak  >  Akhlak di Era Digital  >  Tips Menjaga Lisan di Era Digital
```

Breadcrumb memungkinkan pengguna kembali ke halaman sebelumnya hanya dengan satu klik, tanpa harus menekan tombol "Back" di browser.

### Jenis Navigasi yang Digunakan

| Jenis Navigasi | Penerapan dalam Dakwah KPI |
| :--- | :--- |
| **Navigasi Utama** | Menu di bagian atas (header): Beranda, Aqidah, Fiqih & Ibadah, Akhlak, Sejarah Islam, Al-Qur'an & Hadis, Dakwah Digital, Tanya Ustaz. |
| **Navigasi Sekunder** | Sub-menu yang muncul saat kursor berada di atas menu utama. Contoh: hover "Akhlak" memunculkan daftar sub-kategori di bawahnya. |
| **Breadcrumb** | Jalur navigasi yang selalu tampil di setiap halaman artikel untuk menunjukkan posisi pengguna. |
| **Search (Pencarian)** | Kolom pencarian di navbar dengan placeholder: *"Cari kajian, artikel, atau ustaz..."* |

### Prinsip Navigasi yang Diterapkan

- **Maksimal 3 Klik:** Pengguna dapat menemukan konten apapun dalam maksimal 3 kali klik dari halaman Beranda.
- **Konsisten:** Posisi dan tampilan navigasi sama di setiap halaman agar pengguna tidak bingung.
- **Breadcrumb Selalu Tampil:** Membantu pengguna mengetahui posisi mereka dan memudahkan navigasi mundur.
- **Search Terintegrasi:** Kotak pencarian selalu tersedia di navbar sebagai jalur alternatif yang cepat.
- **Mobile-Friendly:** Menu berubah menjadi *hamburger menu* di perangkat mobile agar tetap mudah diakses.
- **Highlight Aktif:** Menu yang sedang aktif ditandai secara visual sehingga pengguna tahu sedang berada di halaman mana.

---

## Kesimpulan

| Elemen | Peran Utama | Penerapan dalam Dakwah KPI |
| :--- | :--- | :--- |
| **Taksonomi** | Struktur (Kerangka) | 6 kategori utama berbasis disiplin keilmuan Islam ditambah layanan Tanya Ustaz. |
| **Labeling** | Bahasa (Papan Nama) | Label jelas, ringkas, dan berorientasi pengguna; menghindari istilah yang ambigu. |
| **Navigasi** | Akses (Jalan) | User flow maksimal 3 klik, dilengkapi breadcrumb dan fitur pencarian terintegrasi. |

Ketiga elemen ini bekerja secara terpadu. Taksonomi yang baik tidak akan berdampak apapun jika labelnya membingungkan. Label yang bagus pun tidak berguna jika navigasinya sulit. Website **Dakwah KPI** dirancang agar pesan dakwah tidak hanya benar secara substansi, tetapi juga **mudah ditemukan, dipahami, dan dirasakan** oleh mahasiswa dan masyarakat umum.

---

> **"Pesan yang baik tidak hanya benar secara substansi, tetapi juga mudah ditemukan, dipahami, dan dirasakan oleh audiensnya."**

---

**Referensi:**
- Morville, P., & Rosenfeld, L. (2006). *Information Architecture for the World Wide Web*. O'Reilly Media.
- Garrett, J. J. (2010). *The Elements of User Experience: User-Centered Design for the Web and Beyond*. New Riders.
- Modul Perkuliahan Pertemuan 5 – Arsitektur Informasi: Taksonomi, Labeling, dan Navigasi Pesan. Program Studi KPI.
