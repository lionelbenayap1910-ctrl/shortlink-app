# 🔗 Pendekin.link

**Pendekin.link** adalah aplikasi web pemendek tautan (URL shortener) yang simpel, ringan, dan berjalan sepenuhnya di browser.  
Dibuat dengan HTML, CSS, dan JavaScript murni — tanpa backend, tanpa database eksternal. Semua data tersimpan di `localStorage` perangkat kamu.

## ✨ Fitur

- 🔽 **Memendekkan URL panjang** menjadi tautan pendek
- ✏️ **Custom alias** — buat short link sesuai keinginan (contoh: `pendekin.link/promo-42`)
- 🎲 **Random slug** otomatis jika custom alias dikosongkan
- 📋 **Salin tautan** dengan satu klik
- 🔁 **Redirect otomatis** — saat mengakses `pendekin.link/go/[slug]` akan diarahkan ke URL asli
- 📜 **Riwayat tautan** — semua short link yang pernah dibuat tersimpan
- 🗑️ **Hapus tautan** dari riwayat kapan saja
- 💾 **Data lokal** — tidak ada server, privasi tetap terjaga

## 🖼️ Tampilan

- Desain minimalis, bersih, dan responsif
- Warna netral dengan aksen biru
- Mudah digunakan di desktop maupun ponsel

## 🚀 Cara Menggunakan

### 1. Jalankan secara lokal

Karena ini murni frontend, kamu bisa langsung membuka file `index.html` di browser:

```bash
# Clone repositori (atau download file)
git clone https://github.com/username/pendekin-link.git
cd shortlink-app

# Buka dengan browser
open index.html   # macOS
start index.html  # Windows
xdg-open index.html # Linux
