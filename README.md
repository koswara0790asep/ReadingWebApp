# 📖 NeoReader — Dokumen & Musik dalam Satu Aplikasi

NeoReader adalah aplikasi web berbasis **HTML, CSS, dan JavaScript (Vanilla)** yang memungkinkan pengguna untuk:

* 📂 Membaca berbagai jenis dokumen
* 🎵 Memutar musik secara langsung
* 💾 Menyimpan semua data secara offline menggunakan **IndexedDB**

Dibuat dengan gaya desain **Neo-Brutalism**, aplikasi ini fokus pada performa, kesederhanaan, dan pengalaman pengguna yang interaktif.

---

## 🌐 Demo

> *(Opsional - tambahkan jika sudah deploy ke GitHub Pages)*

```bash
https://koswara0790asep.github.io/ReadingWebApp
```

---

## ✨ Fitur Utama

### 📂 Manajemen Dokumen

* Upload & drag-and-drop file:

  * PDF
  * TXT
  * Markdown (.md)
  * HTML
  * RTF
* Viewer dokumen langsung di browser
* Pencarian teks dalam dokumen
* Zoom in / zoom out
* Highlight pencarian
* Hapus dokumen (dengan konfirmasi)

---

### 🎵 Manajemen Musik

* Upload file audio:

  * MP3, WAV, OGG, FLAC, AAC
* Pemutar musik built-in:

  * ▶ Play / Pause
  * ⏭ Next / ⏮ Previous
  * 🔀 Shuffle
  * 🔁 Repeat
  * 🔊 Volume control
* Progress bar & seek
* Auto-detect durasi audio

---

### 💾 Penyimpanan (Offline First)

* Menggunakan **IndexedDB**
* Data tersimpan permanen di browser
* Tidak memerlukan backend/server
* Estimasi penggunaan storage (Quota API)

---

### 📊 Monitoring Storage

* Menampilkan total penggunaan storage
* Progress bar kapasitas (visual)
* Peringatan jika storage hampir penuh

---

### 🎨 UI / UX

* Desain **Neo-Brutalism**
* Responsive (desktop & mobile)
* Animasi interaktif
* Toast notification
* Modal konfirmasi
* Custom scrollbar

---

### 📱 Mobile Friendly

* Sidebar dapat dibuka/tutup
* Navigasi panel dokumen & musik
* Optimasi tampilan layar kecil

---

## 🧱 Teknologi yang Digunakan

* **HTML5**
* **CSS3**

  * Flexbox & Grid
  * Custom Properties (CSS Variables)
  * Animations
* **JavaScript (Vanilla)**

  * IndexedDB API
  * File API
  * Audio API
  * Storage API

---

## 📁 Struktur Project

```bash
index.html
```

> Project ini menggunakan **single file architecture** (semua kode dalam satu file).

---

## 🚀 Cara Menjalankan

1. Clone repository:

```bash
git clone https://github.com/koswara0790asep/ReadingWebApp.git
```

2. Masuk ke folder project:

```bash
cd neoreader
```

3. Buka file:

```bash
index.html
```

4. Jalankan di browser:

* Google Chrome (disarankan)
* Microsoft Edge
* Firefox

---

## 🎮 Shortcut Keyboard

| Shortcut   | Fungsi             |
| ---------- | ------------------ |
| `Space`    | Play / Pause musik |
| `Alt + →`  | Next track         |
| `Alt + ←`  | Previous track     |
| `Ctrl + +` | Zoom in dokumen    |
| `Ctrl + -` | Zoom out dokumen   |
| `Ctrl + 0` | Reset zoom         |
| `Esc`      | Tutup panel mobile |

---

## 📌 Kelebihan

* ✅ Tanpa backend (100% frontend)
* ✅ Offline-ready
* ✅ Multi-fungsi (dokumen + musik)
* ✅ UI unik & modern
* ✅ Cocok untuk pembelajaran & portfolio

---

## ⚠️ Limitasi

* Penyimpanan tergantung quota browser
* File besar bisa mempengaruhi performa
* Tidak ada sinkronisasi antar device

---

## 💡 Pengembangan Selanjutnya

* Cloud sync (Firebase / Supabase)
* User authentication
* Tag & kategori file
* Bookmark halaman dokumen
* Dark/Light mode toggle
* Progressive Web App (PWA)
* Export / import data

---

## 🤝 Kontribusi

Kontribusi sangat terbuka!

1. Fork repository
2. Buat branch baru
3. Commit perubahan
4. Buat Pull Request

---

## 📜 Lisensi

Bebas digunakan untuk:

* Pembelajaran
* Pengembangan pribadi
* Portfolio

---

## 👨‍💻 Author

Dibuat sebagai project eksplorasi:

* Web Storage (IndexedDB)
* File Handling
* UI Neo-Brutalism

---

## ⭐ Dukungan

Jika project ini bermanfaat:

* ⭐ Star repository ini
* 🍴 Fork dan kembangkan

---

> *"Baca dokumen, nikmati musik, semua dalam satu tempat."* 🎧📖
