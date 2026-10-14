# Log Dokumentasi Prompt & Pengembangan - TaskMate (Modul 06)

## Informasi Proyek
- **Nama Aplikasi:** TaskMate (Aplikasi Produktivitas Mahasiswa & Profesional)
- **Sumber Desain:** Figma (Node ID 50-3, TaskMate Project)
- **Standar Pengerjaan:** HTML5 Semantic Markup, W3C-Compliant, Tanpa CSS/Framework Eksternal.

---

## Riwayat Perintah (Prompt) & Iterasi Pengembangan

### 1. Inisialisasi Struktur Direktori & Aset
- **Prompt/Instruksi:** "Buat struktur folder proyek lengkap untuk TaskMate yang mencakup folder `assets/images/` dengan aset SVG ikon dan 12 file HTML utama secara terstruktur."
- **Hasil & Implementasi:** 
  - Menyusun seluruh berkas HTML mulai dari Landing Page (`index.html`), Dashboard, Manajemen Tugas, Autentikasi, hingga Pengaturan.
  - Menyesuaikan ekstensi file SVG ikon pendukung (`avatar-user.svg`, `hero-illustration.svg`, dll.) agar sesuai standar W3C.

### 2. Penerapan HTML5 Semantik Murni
- **Prompt/Instruksi:** "Kembangkan kode sumber halaman HTML5 menggunakan tag semantik murni (`header`, `nav`, `main`, `section`, `article`, `aside`, `dl`, dan `footer`) tanpa menggunakan inline style ataupun berkas CSS eksternal."
- **Hasil & Implementasi:** 
  - Menghindari penggunaan pembungkus `<div>` yang berlebihan.
  - Menggunakan elemen form semantik yang lengkap dengan `<fieldset>`, `<legend>`, serta keterikatan atribut `for` pada label dan `id` pada input untuk aksesibilitas.

### 3. Perbaikan Hirarki Heading & Validasi W3C
- **Prompt/Instruksi:** "Periksa seluruh file HTML menggunakan W3C Nu HTML Checker, lalu perbaiki error hirarki heading yang melompat tingkat."
- **Hasil & Implementasi:** 
  - Memperbaiki struktur heading pada `notifikasi.html` dan halaman lainnya agar berurutan secara konsisten dari `<h1>` ke `<h2>` dan `<h3>` tanpa melompati level.
  - Memastikan seluruh berkas HTML lolos uji validasi W3C dengan status *No errors or warnings to show*.