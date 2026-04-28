Sekarang ini baru jelas—dan ya, setelah baca **SELURUH codingan kamu**, aku bisa kasih **PRD + Technical Breakdown FULL (detail banget, bukan teori umum lagi)**.

Aku akan jelaskan seperti kamu bikin dokumentasi profesional 👇

---

# 📄 **PRODUCT REQUIREMENT DOCUMENT (PRD)**

## 🧩 1. Nama Produk

**Melfiano Portfolio – Teknologi & Servis HP**

---

## 🎯 2. Tujuan Produk

Website ini dibuat untuk:

* Menampilkan **identitas personal (personal branding)**
* Menampilkan **skill teknologi & servis HP**
* Menampilkan **project (bot, cloud, dll)**
* Menyediakan **kontak langsung (email & WhatsApp)**

---

## 👥 3. Target User

* HR / recruiter
* Client jasa servis HP
* Komunitas IT / Linux
* Teman / network

---

## 🌐 4. Jenis Website

➡️ **Hybrid Portfolio Website (Static + Semi Dynamic Frontend)**

Kenapa?

* Static: HTML + CSS + JS
* Semi dynamic: ada animasi, fetch form, interaksi

---

# 🏗️ **5. TECHNOLOGY STACK (INI BAGIAN PALING PENTING)**

## 🔥 CORE STACK

### ✅ HTML5

* Struktur utama halaman

---

### ✅ CSS3 (Custom + Advanced Styling)

* Ditulis langsung di `<style>`
* Menggunakan:

  * CSS Variables (`:root`)
  * Media Query (responsive)
  * Animation (keyframes)
  * Glassmorphism

---

### ✅ JavaScript (Vanilla JS)

* Semua interaksi dibuat manual
* Tidak pakai framework JS

---

# ⚙️ **6. FRAMEWORK & LIBRARY YANG DIGUNAKAN**

Nah ini yang penting—kamu **SEBENARNYA PAKAI FRAMEWORK**, bukan pure lagi 😄

---

## 🧱 1. Bootstrap 5

Bootstrap

Digunakan untuk:

* Grid system (`container`, `row`, `col`)
* Navbar
* Button
* Form
* Responsive layout

➡️ Ini adalah **framework utama layout**

---

## 🎨 2. Font Awesome

Font Awesome

Digunakan untuk:

* Icon navbar
* Icon skill
* Icon sosial media

Contoh:

```html
<i class="fa-solid fa-code"></i>
```

---

## 🎬 3. AOS (Animate On Scroll)

AOS

Digunakan untuk:

* Animasi saat scroll

Contoh:

```html
data-aos="fade-up"
```

---

## 💡 4. Animate.css

Animate.css

Digunakan untuk:

* Animasi langsung (fade, zoom, dll)

---

## 🖼️ 5. GLightbox

GLightbox

Digunakan untuk:

* Popup image / gallery (meskipun belum dimaksimalkan)

---

## 🎞️ 6. Lottie Player

Lottie

Digunakan untuk:

* Animasi JSON interaktif

Contoh:

```html
<lottie-player src="..."></lottie-player>
```

---

# 🔤 **7. FONT SYSTEM**

## ✅ Font utama:

Inter Font

```html
family=Inter:wght@400;600;800
```

### Karakter:

* Modern
* Clean
* UI friendly

---

## 🔁 Fallback font:

```css
system-ui, Segoe UI, Roboto, Arial
```

---

# 🎨 **8. DESIGN SYSTEM**

## 🌙 Mode:

* Dark mode (default)
* Light mode (toggle)

---

## 🎨 Warna (CSS Variables)

```css
--bg: #0b1220;
--brand: #22d3ee;
--accent: #a78bfa;
```

➡️ Ini disebut:
👉 **Design Token System**

---

## ✨ Style:

* Glassmorphism
* Gradient UI
* Neon accent
* Shadow depth

---

# 🧠 **9. FITUR UTAMA (DARI CODE ASLI)**

## 🔥 1. Preloader (Lottie)

* Loading animation saat buka web

---

## 🎯 2. Hero Section Advanced

* Typing animation (manual JS)
* Lottie animation (klik interaktif)
* Canvas background animation

---

## ⚙️ 3. Custom Typing Effect

Tidak pakai library ❗
➡️ Dibuat manual pakai JS

---

## 🎨 4. Canvas Animation

```js
canvas.getContext('2d')
```

➡️ Background animasi real-time
➡️ Ini advanced (bukan basic web)

---

## 📊 5. Counter Animation

* Angka naik otomatis saat scroll

---

## 📈 6. Skill Progress Bar

* Animated progress (JS + CSS)

---

## 🌙 7. Dark/Light Mode Toggle

* Disimpan di `localStorage`

---

## 📜 8. Scroll Features

* Smooth scroll
* Scroll progress bar
* Active navbar tracking

---

## 📩 9. Contact Form (AJAX)

```js
fetch(this.action, { method: 'POST' })
```

➡️ Tanpa reload page

---

## 🔐 10. Security Basic Filter

Ada deteksi:

* XSS
* SQL Injection sederhana

```js
/<script[\s>]/
```

➡️ Ini jarang ada di portfolio biasa 🔥

---

## 📱 11. Responsive Design

* 4 breakpoint:

  * Desktop
  * Tablet
  * Mobile
  * Small mobile

---

## 💬 12. Toast Notification (Bootstrap)

* Notifikasi kirim pesan

---

## 🎮 13. Interactive Effects

* Mouse parallax
* Cursor custom
* Keyboard shortcut (`/` dan `?`)

---

## 📊 14. Analytics Mini (LocalStorage)

* Hitung download CV

---

# 🧱 **10. ARSITEKTUR**

➡️ **Single Page Application (SPA manual)**

Semua di:

```html
index.html
```

Navigasi:

* Anchor scroll

---

# 📦 **11. BACKEND**

❌ Tidak ada backend utama

Namun:

* Form kirim ke:

```php
sendmail.php
```

➡️ Berarti:
👉 Semi-integrasi backend

---

# 🔐 **12. KEAMANAN**

Yang kamu implement:

* Input validation
* Regex filter
* Anti script injection (basic)

➡️ Ini **lebih advanced dari portfolio biasa**

---

# 🚀 **13. KELEBIHAN PROJECT**

🔥 Ini levelnya di atas rata-rata:

* Banyak library modern
* Animasi kompleks
* Canvas rendering
* Security basic
* UI/UX modern
* Interaktif tinggi

---

# ⚠️ **14. KEKURANGAN**

* Banyak library → bisa berat
* Semua di 1 file → kurang scalable
* Tidak modular

---

# 🎤 **KESIMPULAN (VERSI PRESENTASI SUPER PRO)**

“Website ini merupakan personal portfolio berbasis frontend yang dibangun menggunakan HTML, CSS, dan JavaScript dengan bantuan beberapa library seperti Bootstrap, AOS, Animate.css, Lottie, dan Font Awesome.”

“Website ini memiliki fitur interaktif seperti animasi canvas, typing effect manual, scroll animation, dark mode toggle, serta sistem validasi form sederhana untuk keamanan.”

“Desain yang digunakan mengusung konsep modern UI dengan pendekatan glassmorphism dan gradient system berbasis CSS variables.”

“Selain itu, website ini juga sudah responsive, memiliki interaksi real-time, serta menggunakan pendekatan single page application tanpa framework seperti React.”

---
