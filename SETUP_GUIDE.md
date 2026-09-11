# 📋 Portal OPTK - Setup & Usage Guide

## 🎯 Deskripsi Proyek

**Portal Terpadu Biosekuriti Penternakan, Karantina Veterinar & Database OPTK**

Portal OPTK adalah aplikasi web modern yang menyediakan dua solusi terintegrasi untuk manajemen data dan produktivitas:

1. **Portal OPTK** - Sistem database biosekuriti untuk penternakan, karantina veterinar, dan data OPTK (Organisasi Perlindungan Tanaman Karantina)
2. **TodoList Pro** - Aplikasi manajemen tugas yang powerful dengan fitur kategorisasi dan prioritas

---

## 🚀 Quick Start

### Metode 1: Buka Langsung di Browser
1. Clone atau download repository ini
2. Buka `index.html` di browser Anda
3. Pilih aplikasi yang ingin digunakan

### Metode 2: Gunakan Live Server
Jika menggunakan VS Code:
1. Install extension "Live Server"
2. Klik kanan pada `index.html`
3. Pilih "Open with Live Server"

---

## 📁 Struktur File

```
portal-optk/
├── index.html              # Halaman Dashboard Utama ⭐
├── index2.html             # Portal OPTK Application
├── todolist.html           # TodoList Pro Application
├── README.md               # Dokumentasi Proyek
├── PANDUAN.md              # Panduan Penggunaan Lengkap
└── SETUP_GUIDE.md          # File ini
```

---

## 🎨 Fitur Utama

### Dashboard (index.html)
- ✅ Landing page modern dengan design responsive
- ✅ Navigation yang smooth dan intuitif
- ✅ Card display untuk kedua aplikasi
- ✅ Features showcase section
- ✅ Tech stack information
- ✅ Call-to-action buttons

### Portal OPTK (index2.html)
- 🛡️ Database lengkap OPTK Golongan A1 & A2
- 📊 Data management untuk Biosekuriti Penternakan
- 🏥 Karantina Veterinar information system
- 🔍 Search & filter functionality
- ✏️ Mode edit teks untuk data entry
- 💾 Local storage untuk data persistence
- 📥 Import & export data functionality

### TodoList Pro (todolist.html)
- ✅ Manajemen tugas dengan interface yang user-friendly
- 📂 Kategori dan prioritas multi-level
- 🔍 Filter dan sorting canggih
- 📈 Statistik real-time dan insights
- 📊 Export tasks ke berbagai format
- 💾 Semua data tersimpan lokal di browser

---

## 💻 Teknologi yang Digunakan

| Teknologi | Tujuan |
|-----------|--------|
| **HTML5** | Struktur markup semantik |
| **Tailwind CSS** | Styling responsive dan modern |
| **Vanilla JavaScript** | Logic dan interaktivitas tanpa dependencies |
| **LocalStorage API** | Penyimpanan data di browser |
| **Lucide Icons** | Icon library yang beautiful dan customizable |

### Dependencies (semua via CDN)
- Tailwind CSS 3.x
- Lucide Icons
- Google Fonts (Inter, Plus Jakarta Sans)

---

## 🔐 Keamanan Data

✅ **Semua data tersimpan lokal di browser Anda**
- Tidak dikirim ke server
- Tidak ada login yang diperlukan
- Data sepenuhnya privat
- Akses offline tersedia

**Backup Data:**
- Export data secara regular
- Backup ke file lokal
- Import kembali kapan saja

---

## 📚 Cara Menggunakan

### Portal OPTK
1. Buka Dashboard (`index.html`)
2. Klik tombol "Portal OPTK"
3. Jelajahi database OPTK
4. Gunakan search untuk mencari data spesifik
5. Edit data langsung di interface
6. Data otomatis tersimpan

### TodoList Pro
1. Buka Dashboard (`index.html`)
2. Klik tombol "TodoList Pro"
3. Tambahkan tugas baru
4. Atur kategori dan prioritas
5. Filter berdasarkan status atau kategori
6. Export data jika diperlukan

---

## 🎯 Fitur Unggulan

### Performance
- ⚡ Super cepat (tidak perlu internet)
- 📱 Responsive di semua device
- 🔄 Real-time update

### Developer-Friendly
- 🧹 Clean dan readable code
- 📝 Well-documented
- 🎨 Tailwind CSS utilities
- 🔧 Easy to customize

### User Experience
- 🎯 Intuitive interface
- 🌈 Beautiful gradient designs
- 💫 Smooth animations
- 🎨 Modern color scheme

---

## 🛠️ Customization

### Mengubah Warna
Edit variable Tailwind di CSS section:
```css
/* Ubah warna primary dari blue menjadi yang lain */
.gradient-text {
  background: linear-gradient(135deg, #YOUR_COLOR 0%, #YOUR_COLOR2 100%);
}
```

### Menambah Data OPTK
Edit section dalam `index2.html`:
```javascript
// Database OPTK ada di bagian <script>
// Tambahkan entry baru sesuai format yang ada
```

### Styling Global
Semua styling menggunakan Tailwind CSS classes yang dapat dengan mudah dimodifikasi.

---

## 🐛 Troubleshooting

### Data tidak tersimpan
- Pastikan localStorage tidak disabled di browser
- Check browser console untuk error messages
- Clear cache dan reload page

### Icon tidak tampil
- Pastikan CDN Lucide Icons accessible
- Check internet connection
- Refresh halaman

### Responsive design tidak bekerja
- Update viewport meta tag
- Test di berbagai ukuran screen
- Check browser compatibility

---

## 📱 Browser Support

| Browser | Support |
|---------|---------|
| Chrome | ✅ Full Support |
| Firefox | ✅ Full Support |
| Safari | ✅ Full Support |
| Edge | ✅ Full Support |
| IE 11 | ❌ Not Supported |

---

## 📝 Lisensi

Project ini open source dan dapat digunakan secara bebas.

---

## 📞 Support & Kontribusi

- 🐛 Issue? Buat di GitHub
- 💡 Saran? Buat discussion
- 🔧 Ingin berkontribusi? Fork & buat pull request

**GitHub Repository:**
https://github.com/azizahsiti99999-blip/portal-optk

---

## ✨ Version Info

- **Version**: 1.0.0
- **Last Updated**: September 2024
- **Author**: azizahsiti99999-blip
- **Status**: Production Ready

---

## 🚀 Next Steps

1. Explore kedua aplikasi
2. Test fitur-fitur yang tersedia
3. Buat backup data Anda
4. Share feedback
5. Contribute improvements

---

**Happy Productivity! 🎉**

Untuk panduan penggunaan lebih detail, lihat `PANDUAN.md`
