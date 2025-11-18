# Portfolio Sederhana - Angger Bayu Sentiko

Portfolio website sederhana untuk menampilkan proyek dan informasi pribadi. Dibuat oleh Angger Bayu Sentiko, mahasiswa Teknik Informatika Universitas Pamulang.

## 🌟 Fitur

- ✅ **Desain Minimalis** - Clean dan sederhana
- ✅ **Fully Responsive** - Bisa di desktop, tablet, dan mobile
- ✅ **Smooth Scrolling** - Navigasi yang halus
- ✅ **Contact Form** - Formulir kontak dengan validasi
- ✅ **Portfolio Gallery** - Menampilkan proyek-proyek
- ✅ **Animasi Simple** - Efek scroll dan hover

## 📁 Struktur File

```
portfolio/
├── index.html              # Halaman utama
├── css/
│   └── style.css          # Semua style dalam 1 file
├── js/
│   └── main.js            # JavaScript functionality
├── assets/
│   └── images/
│       ├── profile.jpg    # Foto profil
│       └── projects/      # Gambar proyek
└── README.md              # Ini file ini
```

## 🚀 Cara Pakai

1. **Download** semua file
2. **Buka** `index.html` di browser
3. **Edit** konten sesuai kebutuhan:
   - Ganti nama dan informasi personal
   - Update portfolio projects
   - Ganti link social media
   - Update contact form

## 🎨 Yang Bisa Diedit

### Personal Info
```html
<!-- Hero section -->
<h1>Halo, Saya <span>Angger Bayu Sentiko</span></h1>
<p class="subtitle">Mahasiswa Teknik Informatika</p>

<!-- About section -->
<strong>Nama:</strong> Angger Bayu Sentiko
<strong>Pendidikan:</strong> Teknik Informatika - Universitas Pamulang
```

### Portfolio Projects
```html
<div class="portfolio-item">
    <div class="portfolio-image">
        <img src="assets/images/projects/project1.jpg" alt="Project 1">
    </div>
    <div class="portfolio-content">
        <h3>Nama Project</h3>
        <p>Deskripsi singkat project...</p>
        <div class="portfolio-tech">
            <span>HTML</span>
            <span>CSS</span>
            <span>JavaScript</span>
        </div>
        <div class="portfolio-links">
            <a href="#" class="btn-small">Demo</a>
            <a href="#" class="btn-small-outline">Code</a>
        </div>
    </div>
</div>
```

### Social Links
```html
<!-- Hero social -->
<a href="https://github.com/username" class="social-link">
    <i class="fab fa-github"></i>
</a>

<!-- Contact social -->
<a href="https://linkedin.com/in/username">
    <i class="fab fa-linkedin"></i>
</a>
```

### Contact Info
```html
<div class="contact-item">
    <i class="fas fa-envelope"></i>
    <div>
        <strong>Email</strong>
        <span>angger.bayu@email.com</span>
    </div>
</div>
```

## 🎨 Warna Tema

Ganti warna di CSS:
```css
:root {
    --primary-color: #4a69bd;    /* Warna utama */
    --secondary-color: #6c5ce7;  /* Warna sekunder */
    /* ... */
}
```

## 📱 Responsive

Portfolio ini sudah responsive:
- **Desktop** - Layout 2 kolom
- **Tablet** - Layout 1 kolom
- **Mobile** - Layout 1 kolom dengan hamburger menu

## 🔧 Customization

### Tambah Project Baru
1. Copy `<div class="portfolio-item">`
2. Ganti info project
3. Upload gambar ke `assets/images/projects/`

### Ganti Foto Profil
- Upload foto ke `assets/images/profile.jpg`
- Ukuran recommended: 400x400px

### Update Skills
Edit di bagian "Keahlian":
```html
<div class="skill-tags">
    <span class="skill-tag">HTML</span>
    <span class="skill-tag">CSS</span>
    <span class="skill-tag">JavaScript</span>
    <span class="skill-tag">Skill Baru</span>
</div>
```

## 🌐 Deploy

### GitHub Pages
1. Push ke GitHub
2. Settings > Pages
3. Select branch

### Netlify
1. Drag & drop folder ke Netlify

### Hosting Lain
2. Upload semua file ke public_html

## 📊 Browser Support

- Chrome ✅
- Firefox ✅
- Safari ✅
- Edge ✅

## 🎯 Untuk Pemula

Portfolio ini perfect untuk:
- Mahasiswa yang mau buat portfolio pertama
- Developer pemula
- Freelancer yang butuh website simple
- Portofolio untuk job interview

## 🆘 Need Help?

Jika ada masalah:
1. Cek file path (gambar, css, js)
2. Pastikan semua file terupload
3. Test di browser modern
4. Cek console untuk error (F12)

---

**Made with ❤️ by Angger Bayu Sentiko**
Teknik Informatika - Universitas Pamulang