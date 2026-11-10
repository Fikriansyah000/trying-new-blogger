# Webblog PT. Wukir Selo Pratama

Repositori ini memuat kode sumber HTML dan aset visual untuk webblog resmi **PT. Wukir Selo Pratama** yang diimplementasikan pada platform Google Blogger (Blogspot). Seluruh struktur halaman, narasi, dan tata letak dirancang mengacu pada brosur resmi perusahaan dengan pendekatan desain **Constructive Industrial Editorial** yang profesional, geometris, informatif, dan bebas dari pola generik AI-slop.

Tautan blog aktif: [ptwukirselopratama1.blogspot.com](https://ptwukirselopratama1.blogspot.com/)  
Repositori GitHub: [github.com/Fikriansyah000/trying-new-blogger](https://github.com/Fikriansyah000/trying-new-blogger)

---

## Tentang PT. Wukir Selo Pratama

* **Badan Usaha:** PT. WUKIR SELO PRATAMA
* **Bidang Usaha:** General Contractor dan Supplier Material Alam (Batu Basalt dan Tanah Liat)
* **Tahun Berdiri:** 2016
* **Domisili Operasional:** Desa Karangkemiri, Kecamatan Jeruklegi, Kabupaten Cilacap, Jawa Tengah
* **Slogan Korporat:** Solusi Material Terpercaya Sejak 2016
* **Slogan Sosial / CSR:** Tumbuh Bersama Masyarakat
* **Visi:** Menjadi general contractor dan supplier material batu basalt dan tanah liat yang terpercaya untuk mendukung kemajuan infrastruktur dan kesejahteraan masyarakat.
* **Misi:** Menyediakan material berkualitas tinggi untuk pembangunan jalan desa dan proyek pertanian sejak 2016.

---

## Pendekatan Desain: Constructive Industrial Editorial

Desain pada repositori ini dirancang khusus untuk merefleksikan karakter industri konstruksi berat dan rekayasa teknik sipil perdesaan, dengan standar visual sebagai berikut:

1. **Bebas dari Pola AI-Slop:**
   * Menghilangkan penggunaan emoji kasual pada antarmuka teks.
   * Menggantikan pola grid kartu seragam yang monoton dengan hierarki visual asimetris yang proporsional.
   * Menampilkan data metrik dampak melalui angka statistik besar (stat callouts) yang diperjelas narasi resmi brosur.

2. **Integrasi Ikon Vektor SVG Presisi:**
   * Keempat ikon infografis utama (Jalan, Truk, Pohon, dan Pekerja) diintegrasikan langsung menggunakan kode vektor SVG inline.
   * Bentuk, siluet, dan proporsi dibuat 100% identik dengan berkas grafis sumber (1.png hingga 4.png), sehingga tampil tajam pada semua resolusi layar (Retina/HD) tanpa membutuhkan pengunggahan berkas manual ke media library eksternal.

3. **Tata Letak Geometris Brosur:**
   * Mengadaptasi skema warna tegas merah-biru dari brosur fisik dengan garis sudut presisi (sharp geometric blocks).
   * Menampilkan dokumentasi riil lapangan dalam format bingkai editorial jurnalistik (Field Dispatch) lengkap dengan metadata waktu, tanggal, dan lokasi.

---

## Struktur Berkas Proyek

```text
├── Beranda.html               Kode HTML halaman Beranda (Hero, metrik dampak, spotlight produk, warta berita)
├── kegiatankomunitas.html     Kode HTML halaman Kegiatan Komunitas (Jadwal, narasi gotong royong, galeri foto, data dampak)
├── Produk.html                Kode HTML halaman Produk & Layanan (Lembar spesifikasi teknis Batu Basalt, tanah liat, jasa kontraktor)
├── profilkami.html            Kode HTML halaman Profil Perusahaan / Mengenai Kami (Visi, misi, struktur organisasi, portofolio)
├── kontak.html                Kode HTML halaman Kontak (Direktori kantor, jam operasional armada, hotline WhatsApp, email)
├── sidebar_gadget.html        Kode HTML widget ringkasan profil rekanan untuk kolom kiri Blogger (Sidebar Bottom)
│
├── konsep_baru/               Direktori berkas implementasi konsep desain non-slop
│   ├── 1.png                  Aset grafis resolusi tinggi (Ikon Perspektif Jalan Merah)
│   ├── 2.png                  Aset grafis resolusi tinggi (Ikon Armada Truk Biru)
│   ├── 3.png                  Aset grafis resolusi tinggi (Ikon Pekerja Konstruksi & Sekop)
│   ├── 4.png                  Aset grafis resolusi tinggi (Ikon Pohon Reboisasi)
│   ├── Beranda.html           Salinan kode implementasi halaman Beranda
│   ├── kegiatankomunitas.html Salinan kode implementasi halaman Kegiatan Komunitas
│   ├── Produk.html            Salinan kode implementasi halaman Produk
│   ├── profilkami.html        Salinan kode implementasi halaman Profil Perusahaan
│   ├── kontak.html            Salinan kode implementasi halaman Kontak
│   └── sidebar_gadget.html    Salinan kode implementasi widget Sidebar
│
└── README.md                  Dokumentasi teknis dan panduan penggunaan repositori
```

---

## Spesifikasi Teknis Antarmuka

| Komponen | Spesifikasi | Keterangan |
| :--- | :--- | :--- |
| **Font Heading** | Poppins (Bold 700) | Karakter tegas, arsitektural, dan mudah dibaca pada judul utama |
| **Font Body Text** | Open Sans (Regular 400, Semi-Bold 600, Bold 700) | Proporsional, bersih, dengan kontras tinggi untuk teks deskripsi panjang |
| **Warna Primer** | Navy Blue (`#0B3D91`) | Melambangkan kepercayaan, stabilitas, dan profesionalitas kontraktor |
| **Warna Aksen** | Crimson Red (`#C8102E`) | Melambangkan kekuatan, energi kerja, garis batas konstruksi, dan tombol tindakan |
| **Warna Dasar & Netral** | Slate & White (`#FFFFFF`, `#F8FAFC`, `#E2E8F0`, `#1E293B`) | Menjamin kenyamanan membaca dan hierarki batas bidang yang terstruktur |
| **Arsitektur Layout** | 2 Kolom (Konten Utama + Sidebar Kiri) | Sesuai rancangan tata letak standar Blogger |

---

## Rincian Halaman dan Narasi Konten

### 1. Halaman Beranda (`Beranda.html`)
* **Hero Banner:** Menampilkan judul utama brosur *"Bersama Membangun Jalan, Wujudkan Harapan Petani"* dengan sub-judul *"Menyediakan Batu Basalt Berkualitas untuk Infrastruktur & Pertanian"* serta pita pengenal *"Solusi Material Terpercaya Sejak 2016"*.
* **Dashboard Metrik Dampak:** Menyajikan 4 ringkasan pencapaian lapangan (2 KM jalan diperkuat, 20 truk tanah liat, reboisasi pohon, dan 50+ pekerja lokal) berbasis ikon vektor SVG.
* **Spotlight Produk Unggulan:** Ulasan material Batu Basalt dengan tiga pilar mutu (*Kuat, Tahan Lama, Ramah Lingkungan*) dan tombol pemesanan cepat via WhatsApp.
* **Warta Berita Terkini:** Cuplikan berita resmi kegiatan gotong royong 13 Oktober 2026.

### 2. Halaman Kegiatan Komunitas (`kegiatankomunitas.html`)
* **Sub-Heading & Jadwal:** Menampilkan sub-judul resmi *"Bersama Membangun dan Mendukung Masyarakat"*, stempel jadwal `Senin, 13 Oktober 2026 • 08.00 WIB`, dan lokasi `Desa Karangkemiri • Jeruklegi • Cilacap`.
* **Laporan Gotong Royong:** Narasi reportase lapangan mengenai kerja sama pekerja proyek dan warga petani dalam pengerasan jalan usaha tani.
* **Galeri Dokumentasi Riil:** Menampilkan dua foto lapangan resolusi tinggi:
  * Dokumentasi 01: Sinergi fisik pekerja berhelm keselamatan kuning dan petani bertopi caping bambu.
  * Dokumentasi 02: Sesi dialog dan evaluasi insinyur lapangan bersama tokoh petani di atas jalan baru.
* **Seksi Dampak untuk Masyarakat:** Penjelasan komprehensif mengenai manfaat ekonomi, efisiensi distribusi panen, akses pendidikan anak-anak desa, serta kutipan komitmen masa depan.

### 3. Halaman Produk & Layanan (`Produk.html`)
* **Lembar Spesifikasi Batu Basalt:** Menampilkan tabel parameter teknis (karakteristik fisik batuan beku vulkanik, ketahanan aus, aplikasi lapis pondasi sub-base, dan ketersediaan ritase dump truck).
* **Portofolio Layanan Lain:** Penjelasan detail suplai tanah liat urugan tahan musim hujan, pekerjaan perbaikan jalan desa, rekayasa infrastruktur jalan tani, dan manajemen proyek general contractor.

### 4. Halaman Profil Perusahaan (`profilkami.html`)
* **Piagam Visi & Misi:** Komitmen korporat jangka panjang dalam mendukung infrastruktur desa sejak 2016.
* **Struktur Organisasi Hierarkis:** Bagan pohon korporat terstruktur dari Direktur Utama, Manajer Operasional, hingga Koordinator Lapangan dan Humas Desa.
* **Portofolio Aktivitas:** Empat bidang kompetensi bernomor indeks teknis (01 Jasa Konstruksi, 02 Agregat Utama, 03 Material Urugan, 04 Rekayasa Infrastruktur).

### 5. Halaman Kontak (`kontak.html`)
* **Direktori Operasional:** Alamat pool operasional Karangkemiri, jam operasional armada (Senin - Sabtu, 07.30 - 17.00 WIB), kontak hotline WhatsApp (088802348412), dan korespondensi surel resmi (pt.wukirselopratama@gmail.com).
* **Panel Aksi Cepat:** Tautan langsung menuju chat WhatsApp terformat, draft email pemesanan, dan navigasi titik lokasi Google Maps.

### 6. Widget Kolom Kiri (`sidebar_gadget.html`)
* Modul ringkas untuk mengisi kolom sidebar kiri (Sidebar Bottom) agar layout 2 kolom seimbang, memuat identitas perusahaan, domisili, nomor kontak, serta tombol penghubung WhatsApp.

---

## Panduan Penerapan ke Dasbor Blogger

Seluruh berkas HTML pada repositori ini menggunakan inline-CSS murni yang aman dan kompatibel dengan parser platform Blogger:

1. **Menerapkan Konten Halaman (Pages):**
   * Buka dasbor **Blogger** > menu **Pages (Halaman)**.
   * Pilih halaman yang ingin diperbarui (misalnya *Beranda*, *Kegiatan Komunitas*, *Produk*, *Profil Kami*, atau *Kontak*).
   * Alihkan mode penulisan ke **HTML View** (ikon pensil di kiri atas editor teks > pilih **HTML View**).
   * Salin seluruh isi kode dari berkas terkait di repositori ini, lalu tempelkan ke editor.
   * Klik tombol **Update (Perbarui)** di sudut kanan atas.

2. **Menerapkan Gadget Sidebar Kolom Kiri:**
   * Buka dasbor **Blogger** > menu **Layout (Tata Letak)**.
   * Gulir ke bagian **Sidebar (Bottom)**.
   * Klik **Add a Gadget (Tambahkan Gadget)** > pilih tipe **HTML/JavaScript**.
   * Kosongkan kolom **Title (Judul)** agar tampilan bersih tanpa header ganda.
   * Salin seluruh isi dari berkas `sidebar_gadget.html` dan tempelkan ke kolom **Content (Konten)**.
   * Klik **Save (Simpan)**.

---

## Layanan & Kontak Resmi

* **Perusahaan:** PT. Wukir Selo Pratama
* **Alamat:** Desa Karangkemiri, Kecamatan Jeruklegi, Kabupaten Cilacap, Jawa Tengah
* **Hotline / WhatsApp:** 088802348412
* **Surel Resmi:** pt.wukirselopratama@gmail.com
* **Alamat Webblog:** https://ptwukirselopratama1.blogspot.com/

