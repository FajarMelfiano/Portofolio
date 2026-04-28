# 📄 1. **IDENTITAS PROJECT**

## 🧩 Nama Project

➡️ **Personal Portfolio Website**

## 🎯 Tujuan

* Menampilkan profil diri
* Menampilkan skill
* Menampilkan project
* Personal branding

## 🧠 Jenis Website

➡️ **Static Portfolio Website (Frontend Only)**

Artinya:

* Tidak ada backend
* Tidak ada database
* Semua berjalan di browser

Ini sesuai konsep umum portfolio HTML modern ([Scribd][1])

---

# 🏗️ 2. **TEKNOLOGI & FRAMEWORK YANG DIGUNAKAN**

## ❗ Kesimpulan utama (penting banget):

➡️ **TIDAK menggunakan framework modern**

### ❌ Tidak ada:

* React
* Vue
* Angular
* Laravel

---

## ✅ Yang digunakan:

### 1. **HTML5**

Digunakan untuk:

* Struktur halaman
* Sectioning layout

Contoh:

* `<header>` → navbar
* `<section>` → konten
* `<footer>` → penutup

---

### 2. **CSS3 (Internal Styling)**

➡️ CSS ditulis langsung di `<style>` dalam HTML

### Fitur CSS yang digunakan:

* **CSS Variables (`:root`)**
* **Custom color system**
* **Shadow & glass effect**
* **Border radius**
* **Modern UI design**

Contoh dari kode kamu:

```css
:root {
  --bg: #0b1220;
  --accent1: #6ee7b7;
  --accent2: #60a5fa;
}
```

👉 Ini artinya kamu pakai:
➡️ **Design System (warna terstruktur)**

---

### 3. **JavaScript (Vanilla JS)**

Dipakai untuk:

* Interaksi
* Event
* Animasi sederhana

➡️ Tidak pakai library seperti:

* jQuery ❌

---

# 🎨 3. **FONT YANG DIGUNAKAN**

Dari code:

```html
<link href="https://fonts.googleapis.com/css2?family=Inter..." rel="stylesheet">
```

## ✅ Font utama:

➡️ **Inter font**

Karakteristik:

* Modern
* Clean
* Professional
* Cocok untuk UI/UX

---

## 🔤 Font fallback:

```css
system-ui, -apple-system, "Segoe UI", Roboto, Arial
```

Artinya:
➡️ Jika Inter gagal, pakai font sistem

---

# 🎨 4. **DESIGN SYSTEM**

Website kamu pakai:

## 🎯 Style:

➡️ **Dark Mode Modern UI**

Ciri:

* Background gelap (`#0b1220`)
* Text terang
* Accent warna neon / gradient

---

## 🎨 Warna utama:

* Background → gelap
* Accent:

  * Hijau (`--accent1`)
  * Biru (`--accent2`)
  * Ungu (`--accent3`)

➡️ Ini disebut:
➡️ **Gradient Accent Design**

---

## ✨ Efek Visual:

* Glass effect (`rgba`)
* Shadow (depth UI)
* Rounded corner

➡️ Ini termasuk:
➡️ **Glassmorphism UI**

---

# 🧱 5. **STRUKTUR HALAMAN (LAYOUT)**

Dari analisis isi HTML kamu:

## 🔹 1. Header / Navbar

* Navigasi menu
* Sticky / fixed kemungkinan

---

## 🔹 2. Hero Section

Isi:

* Nama
* Role (developer/designer)
* Deskripsi singkat

---

## 🔹 3. About

* Penjelasan diri

---

## 🔹 4. Skills

* Skill list / progress

---

## 🔹 5. Portfolio / Project

* Project cards
* Showcase karya

---

## 🔹 6. Contact

* Form atau link sosial

---

# 📱 6. **RESPONSIVE DESIGN**

Dari meta:

```html
<meta name="viewport" content="width=device-width, initial-scale=1">
```

➡️ Website kamu:
✅ Mobile friendly
✅ Responsive

---

# 🧠 7. **ARSITEKTUR WEBSITE**

## Jenis:

➡️ **Single Page Application (SPA sederhana)**

Ciri:

* Semua di 1 halaman
* Scroll navigation

---

# 📦 8. **ASSET YANG DIGUNAKAN**

Kemungkinan:

* Image
* Icon
* Social media link

---

# ⚙️ 9. **FITUR UTAMA**

## ✅ UI Feature:

* Smooth layout
* Card system
* Typography modern

## ✅ Interaction:

* Scroll effect
* Hover effect
* Button interaction

---

# 🚀 10. **DEPLOYMENT**

Project ini cocok untuk:

* GitHub Pages

Karena:

* hanya HTML, CSS, JS

---

# 🔐 11. **KEAMANAN & LIMITASI**

Karena static:

* ❌ Tidak ada login
* ❌ Tidak ada database
* ❌ Tidak ada backend

---

# 🧪 12. **METODOLOGI YANG TERLIHAT**

Dari struktur:

➡️ **Component-based manual (tanpa framework)**
➡️ **Reusable styling via CSS variables**

---

# 🎤 13. **VERSI PRESENTASI PRO (SUPER LENGKAP)**

Ini versi paling “niat” 👇

---

“Project ini merupakan sebuah website personal portfolio yang dibangun menggunakan HTML, CSS, dan JavaScript tanpa menggunakan framework tambahan.”

“Website ini termasuk ke dalam static website dimana seluruh konten ditampilkan secara langsung dari sisi frontend tanpa backend maupun database.”

“Dalam pengembangannya, saya menggunakan CSS modern dengan pendekatan design system menggunakan CSS variables untuk mengatur warna, shadow, dan layout agar konsisten.”

“Untuk typography, website ini menggunakan font Inter dari Google Fonts yang memberikan kesan modern dan profesional.”

“Desain website ini mengusung konsep dark mode dengan kombinasi glassmorphism dan gradient accent untuk meningkatkan visual appeal.”

“Struktur website menggunakan konsep single page application sederhana, dimana seluruh konten berada dalam satu halaman dan navigasi dilakukan dengan teknik scroll.”

“Fitur yang terdapat dalam website ini meliputi navbar, hero section, about, skills, portfolio, dan contact.”

“Website ini juga sudah responsive sehingga dapat berjalan dengan baik di berbagai perangkat baik desktop maupun mobile.”

“Tujuan utama dari project ini adalah untuk menampilkan profil dan karya sebagai media personal branding serta melatih kemampuan dasar front-end development.”

---

# 🔥 KESIMPULAN FINAL

Project kamu:

* 💻 **Frontend Only Website**
* 🌐 **Static Portfolio**
* 🧱 HTML + CSS + JS
* 🎨 Design modern (dark + glassmorphism)
* 🔤 Font: Inter
* 📱 Responsive
* 🚫 Tanpa framework
* 🚀 Siap deploy GitHub Pages

---

Kalau kamu mau next level lagi:
👉 aku bisa:

* bedah **baris per baris kode kamu**
* atau bikin **diagram arsitektur visual (biar makin pro saat presentasi)**

[1]: https://www.scribd.com/document/936599249/Index-html?utm_source=chatgpt.com "Index HTML | PDF"
