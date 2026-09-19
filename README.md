# 🌐 Nexus Digital Studio - Multi-Page HTML Website (1 HTML : 1 CSS)

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Architecture](https://img.shields.io/badge/Architecture-1%20HTML%20%3A%201%20CSS-10b981?style=for-the-badge)

Aplikasi web modern berdesain *Glassmorphism Dark Mode* yang terstruktur secara 1-ke-1: **setiap 1 file HTML memiliki 1 file CSS khusus masing-masing**.

---

## 📁 Pasangan File HTML dan CSS

Seluruh proyek ini terdiri dari 9 pasang file HTML & CSS terpisah plus file `common.css` untuk *Design Tokens*:

| Halaman | File HTML | File CSS Khusus | Deskripsi Singkat |
|---|---|---|---|
| **1. Beranda** | [index.html](index.html) | [index.css](index.css) | Hero section, statistik interaktif, & sorotan utama |
| **2. Tentang** | [about.html](about.html) | [about.css](about.css) | Profil perusahaan, visi, misi, & nilai utama |
| **3. Layanan** | [services.html](services.html) | [services.css](services.css) | 6 bidang spesialisasi layanan |
| **4. Portofolio** | [portfolio.html](portfolio.html) | [portfolio.css](portfolio.css) | Galeri proyek interaktif dengan filter kategori |
| **5. Fitur** | [features.html](features.html) | [features.css](features.css) | Arsitektur & ekosistem fitur modern |
| **6. Blog** | [blog.html](blog.html) | [blog.css](blog.css) | Publikasi artikel teknis & wawasan berita |
| **7. Tim** | [team.html](team.html) | [team.css](team.css) | Profil jajaran pimpinan & engineer |
| **8. FAQ** | [faq.html](faq.html) | [faq.css](faq.css) | Akordeon pertanyaan umum (Pusat Bantuan) |
| **9. Kontak** | [contact.html](contact.html) | [contact.css](contact.css) | Formulir kirim pesan & info lokasi |

---

## 🛠️ Struktur Seluruh File Proyek

```text
git-github-collab/
├── index.html        # HTML Halaman Beranda
├── index.css         # CSS Halaman Beranda
├── about.html        # HTML Halaman Tentang Kami
├── about.css         # CSS Halaman Tentang Kami
├── services.html     # HTML Halaman Layanan
├── services.css      # CSS Halaman Layanan
├── portfolio.html    # HTML Halaman Portofolio
├── portfolio.css     # CSS Halaman Portofolio
├── features.html     # HTML Halaman Fitur Utama
├── features.css      # CSS Halaman Fitur Utama
├── blog.html         # HTML Halaman Blog
├── blog.css          # CSS Halaman Blog
├── team.html         # HTML Halaman Tim
├── team.css          # CSS Halaman Tim
├── faq.html          # HTML Halaman FAQ (Pertanyaan Umum)
├── faq.css           # CSS Halaman FAQ
├── contact.html      # HTML Halaman Kontak
├── contact.css       # CSS Halaman Kontak
├── common.css        # Base Stylesheet & Design System
└── README.md         # Dokumentasi Lengkap Proyek
```

---

## 🎨 Arsitektur CSS (Modular 1 HTML : 1 CSS)

Setiap file CSS khusus memuat `@import url('common.css');` di baris teratasnya untuk mengimpor variabel warna, reset, header, dan footer bersama, kemudian dilanjutkan dengan gaya visual yang spesifik untuk halaman HTML tersebut.

- **Background Dark Mode**: `#070a11` (Deep Dark Navy)
- **Glassmorphism**: Semi-transparent background `rgba(15, 23, 42, 0.65)` & blur `16px`.
- **Tipografi**: Google Fonts *Outfit* & *Plus Jakarta Sans*.

---

## 💻 Cara Menjalankan Di Lokal Browser

Cukup buka file `index.html` langsung di browser pilihan Anda. Navigasi menu utama di bagian atas memungkinkan Anda berpindah halaman secara penuh dengan file CSS tersendiri di tiap halaman.

---

## 🌿 Panduan Kolaborasi Git & GitHub

```bash
# 1. Cek status repositori
git status

# 2. Tambahkan perubahan file
git add .

# 3. Commit perubahan
git commit -m "feat: tambahkan halaman FAQ dan arsitektur 1 HTML : 1 CSS"

# 4. Push ke GitHub
git branch -M main
git push -u origin main
```
