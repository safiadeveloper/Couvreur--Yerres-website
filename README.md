# 🏠 Couvreur Yerres – Site Web Artisans Couvreurs

Ek modern, responsive, single-file website jo ek French roofing company (**Couvreur Yerres**) ke liye banayi gayi hai. Website mein couverture, zinguerie, étanchéité, isolation aur emergency fuite repair services ko professional tareeqe se show kiya gaya hai, saath mein ek detailed **devis (quote) form** bhi hai.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)
![Responsive](https://img.shields.io/badge/Responsive-Yes-success)
![Language](https://img.shields.io/badge/Langue-Français-blue)

---

## 📑 Table of Contents

1. [Overview](#-overview)
2. [Features](#-features)
3. [Screenshots](#-screenshots)
4. [Tech Stack](#-tech-stack)
5. [Project Structure](#-project-structure)
6. [Installation & Usage](#-installation--usage)
7. [Sections Breakdown](#-sections-breakdown)
8. [Customization](#-customization)
9. [Animations & Effects](#-animations--effects)
10. [Quote Form Working](#-quote-form-working)
11. [Responsive Design](#-responsive-design)
12. [SEO & Accessibility](#-seo--accessibility)
13. [TODO / Placeholders](#-todo--placeholders)
14. [Contact](#-contact)

---

## 📖 Overview

| Detail | Info |
|---|---|
| **Project Name** | Couvreur Yerres |
| **Type** | Business / Service Website (Landing Page) |
| **Language** | Français (`lang="fr"`) |
| **Main File** | `couvreur-yerres.html` (single HTML file – CSS + JS inline) |
| **Target Audience** | Particuliers & professionnels (Yerres 91330 aur aas-paas ka region) |
| **Main Goal** | Visitors ko **devis request** ya **emergency call** ke liye convert karna |

---

## ✨ Features

- 📞 **Top info bar** – urgence 7j/7, email, devis gratuit sous 48h
- 🧭 **Sticky navbar** with dropdown submenus (scroll par compact ho jata hai)
- 🌧️ **Animated hero** – rain effect, moving clouds, skyline SVG
- 📝 **Detailed quote form** – service type, délai, ville, message
- 📧 **mailto integration** – form submit par email app khulti hai
- 🏅 **"Pourquoi nous choisir"** – 5 trust cards
- 🏢 **About section** – overlapping tilted images
- 🛠️ **8 service cards** – images, hover zoom, clip-path design
- 🚨 **Emergency banner** – 24h/24 fuite intervention
- 🔢 **3-step process** – consultation → travaux → inspection
- 🎞️ **Marquee ticker** – scrolling services strip
- 🎬 **Scroll-reveal animations** (IntersectionObserver)
- ♿ **Accessibility** – focus-visible, aria labels, `prefers-reduced-motion`
- 📱 **Fully responsive** – mobile, tablet, desktop
- 📲 **Safe-area support** – iPhone notch / bars ke liye `env(safe-area-inset-*)`

---

## 📸 Screenshots

> **Note:** Neeche ke image paths ke mutabiq apne screenshots `screenshots/` folder mein save karein (names exactly same rakhein).

### 1️⃣ Top Bar, Header & Navigation

| Desktop View | Mobile View |
|:---:|:---:|
| ![Header Desktop](screenshots/01-header-desktop.png) | ![Header Mobile](screenshots/01-header-mobile.png) |
| Logo, phone, zone d'intervention, "Demander un devis" button aur sticky navbar | Mobile par navbar items wrap ho kar 2-column ban jate hain |

### 2️⃣ Hero Section

| Desktop View | Mobile View |
|:---:|:---:|
| ![Hero Desktop](screenshots/02-hero-desktop.png) | ![Hero Mobile](screenshots/02-hero-mobile.png) |
| Background image (`roof.jpg`) + overlay, badge, big title "Artisans couvreurs", skyline SVG | Same hero, font sizes `clamp()` se auto adjust |

### 3️⃣ Devis (Quote) Section

| Left Column – Info & Trust | Right Column – Form |
|:---:|:---:|
| ![Devis Info](screenshots/03-devis-info.png) | ![Devis Form](screenshots/03-devis-form.png) |
| Tag, heading, garantie décennale, callback card | Nom, téléphone, email, ville, service, délai, détails |

### 4️⃣ Ticker & "Pourquoi nous choisir ?"

| Marquee Ticker | Why Choose Us (5 Cards) |
|:---:|:---:|
| ![Ticker](screenshots/04-ticker.png) | ![Why Us](screenshots/04-why-us.png) |
| Gold rotated strip jo services ko loop mein scroll karti hai | Hover par cards upar uthte hain aur icon 360° rotate hota hai |

### 5️⃣ About Section (À propos)

| Images & Layout | Text & Checklist |
|:---:|:---:|
| ![About Images](screenshots/05-about-images.png) | ![About Text](screenshots/05-about-text.png) |
| Do tilted images (`roof1.jpg`, `roof2.jpg`) jo hover par seedhi hoti hain | Company intro, qualification badge, phone aur CTA button |

### 6️⃣ Services Section

| Services Grid (Row 1) | Services Grid (Row 2) |
|:---:|:---:|
| ![Services 1](screenshots/06-services-1.png) | ![Services 2](screenshots/06-services-2.png) |
| Toiture neuve, Charpente, Étanchéité, Nettoyage | Zinguerie, Fenêtres de toit, Ravalement, Isolation |

### 7️⃣ Emergency Banner & Process Steps

| Urgence Banner | Comment fonctionnons-nous ? |
|:---:|:---:|
| ![Urgence](screenshots/07-urgence.png) | ![Steps](screenshots/07-steps.png) |
| "Une urgence fuite ?" – 7j/7 & 24h/24 call-to-action | 3 steps: Consultation, Travaux, Inspection finale |

### 8️⃣ Footer

| Footer Desktop | Footer Mobile |
|:---:|:---:|
| ![Footer Desktop](screenshots/08-footer-desktop.png) | ![Footer Mobile](screenshots/08-footer-mobile.png) |
| Logo, contact, liens services, mentions légales, copyright | Single column layout |

---

## 🧰 Tech Stack

| Technology | Use |
|---|---|
| **HTML5** | Semantic structure (`header`, `nav`, `section`, `article`, `footer`) |
| **CSS3** | Grid, Flexbox, CSS variables, clip-path, keyframe animations |
| **Vanilla JavaScript** | Form → mailto, sticky navbar, scroll reveal |
| **Google Fonts** | Montserrat (headings) + Roboto (body) |
| **Unsplash** | Service card images (remote URLs) |

> ❌ Koi framework / library / build tool ki zaroorat nahi.

---

## 📂 Project Structure

```
couvreur-yerres/
│
├── couvreur-yerres.html     # Main file (HTML + CSS + JS)
├── roof.jpg                 # Hero background image
├── roof1.jpg                # About section – image 1
├── roof2.jpg                # About section – image 2
├── screenshots/             # README ke screenshots
│   ├── 01-header-desktop.png
│   ├── 01-header-mobile.png
│   ├── 02-hero-desktop.png
│   ├── 02-hero-mobile.png
│   ├── 03-devis-info.png
│   ├── 03-devis-form.png
│   ├── 04-ticker.png
│   ├── 04-why-us.png
│   ├── 05-about-images.png
│   ├── 05-about-text.png
│   ├── 06-services-1.png
│   ├── 06-services-2.png
│   ├── 07-urgence.png
│   ├── 07-steps.png
│   ├── 08-footer-desktop.png
│   └── 08-footer-mobile.png
└── README.md
```

---

## 🚀 Installation & Usage

### Option 1 – Direct browser mein kholein
1. Project folder download / clone karein
2. `couvreur-yerres.html` par double-click karein
3. Website browser mein khul jayegi ✅

### Option 2 – Local server (recommended)

```bash
# Python
python -m http.server 8000

# ya Node.js
npx serve .
```

Phir browser mein kholein: `http://localhost:8000/couvreur-yerres.html`

### Option 3 – VS Code Live Server
1. VS Code mein folder open karein
2. **Live Server** extension install karein
3. HTML file par right-click → **Open with Live Server**

### Hosting (Deploy)
Free hosting options: **GitHub Pages**, **Netlify**, **Vercel**, **Cloudflare Pages** – bas folder upload karein.

---

## 🧩 Sections Breakdown

| # | Section | ID / Class | Description |
|:-:|---|---|---|
| 1 | Top Bar | `.top` | Urgence, email, devis gratuit |
| 2 | Header | `.head` | Logo, phone, zone, CTA |
| 3 | Navbar | `.navbar` | Sticky menu + dropdowns |
| 4 | Hero | `#accueil` | Background image, title, skyline SVG |
| 5 | Devis | `#devis` | Info + detailed form |
| 6 | Ticker | `.tick` | Scrolling services strip |
| 7 | Why Us | `.why` | 5 trust cards |
| 8 | About | `#apropos` | Company intro + images |
| 9 | Services | `#services` | 8 service cards + urgence banner |
| 10 | Steps | `.steps` | 3-step process |
| 11 | Footer | `#contact` | Contact, links, copyright |

---

## 🎨 Customization

### Colors (CSS Variables)

`:root` mein ye variables change karein:

| Variable | Default | Use |
|---|---|---|
| `--navy` | `#0e1738` | Main dark blue (headings, footer) |
| `--red` | `#f2542d` | Primary accent (buttons, icons) |
| `--gold` | `#f5b301` | Secondary accent (ticker, highlights) |
| `--bg` | `#eef0f5` | Page background |
| `--txt` | `#6b7280` | Body text |

### Fonts

```html
<link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@500;600;700;800&family=Roboto:wght@400;500&display=swap" rel="stylesheet">
```

### Images
- **Hero:** `roof.jpg` ko apni image se replace karein
- **About:** `roof1.jpg`, `roof2.jpg` replace karein
- **Services:** `<img src="https://images.unsplash.com/...">` URLs apni images se badlein

### Contact Details
Ye jagah update karein:
- Phone: `01 00 00 00 00` aur `tel:+33100000000`
- Email: `Safia34740@gmail.com` (top bar, footer, JS `mailto`)
- Address & SIRET: footer mein `[Votre adresse]`, `[à compléter]`

---

## 🎬 Animations & Effects

| Effect | Where | Technique |
|---|---|---|
| Rain falling | Hero | `repeating-linear-gradient` + `@keyframes rain` |
| Moving clouds | Hero | `radial-gradient` + `@keyframes cloud` |
| Skyline rise | Hero SVG | `@keyframes rise` |
| Badge pop-in | Hero | `@keyframes pop` |
| Button shine | `.btn` | `::after` skewed gradient |
| Pulsing phone icon | Header | `@keyframes ring` |
| Marquee | Ticker | `@keyframes mq` |
| Card lift & icon spin | Why Us | `transform` on hover |
| Image zoom | Service cards | `scale()` on hover |
| Shake effect | Urgence button | `@keyframes wob` |
| Floating icons | Steps | `@keyframes bob` |
| Scroll reveal | Cards, titles | `IntersectionObserver` + `.rv` / `.in` |
| Title underline grow | All `h2` | `h2::after` width transition |

---

## 📨 Quote Form Working

```
User form fill karta hai
        ↓
JS "submit" event pakadta hai (preventDefault)
        ↓
Nom, téléphone, email, message se email body banti hai
        ↓
"Votre application e-mail s'ouvre..." message show hota hai
        ↓
mailto: link se user ki email app khulti hai
```

**Form Fields:**

| Field | Type | Required |
|---|---|:-:|
| Nom & Prénom | text | ✅ |
| Téléphone | tel | ✅ |
| Adresse E-mail | email | ✅ |
| Code Postal / Ville | text | ✅ |
| Type de Prestation | select | ✅ |
| Délai souhaité | select | ❌ |
| Détails du projet | textarea | ✅ |

> 💡 **Note:** Abhi `mailto:` use ho raha hai, to user ki email app khulna zaroori hai. Real backend ke liye **Formspree**, **EmailJS**, **Netlify Forms** ya apna **PHP / Node API** use kar sakte hain. Is waqt `service` aur `délai` fields ka data email body mein shamil nahi hai – chahein to JS mein add kar dein.

---

## 📱 Responsive Design

| Breakpoint | Changes |
|---|---|
| `≤ 850px` | Devis section single column, form fields stack |
| `≤ 800px` | Forms/About/Footer single column, navbar items 2-per-row, hero padding adjust |
| `≤ 650px` | Urgence banner vertical layout |
| Auto-fit grids | Service & why-us cards `minmax()` se khud adjust |

---

## 🔍 SEO & Accessibility

**SEO**
- `lang="fr"` attribute
- Meaningful `<title>` aur `<meta name="description">`
- Semantic HTML tags aur heading hierarchy
- Image `alt` text

**Accessibility**
- `aria-label` on nav, inputs aur decorative elements (`aria-hidden`)
- `:focus-visible` outlines
- `role="status"` success message par
- `prefers-reduced-motion` support – animations off ho jati hain
- Color contrast navy/white base par

---

## ✅ TODO / Placeholders

- [ ] Real phone number lagana (`01 00 00 00 00`)
- [ ] Footer address aur SIRET fill karna
- [ ] `roof.jpg`, `roof1.jpg`, `roof2.jpg` files folder mein add karna
- [ ] Privacy policy aur mentions légales pages banana (abhi `#` links hain)
- [ ] Real backend form integration
- [ ] "En savoir plus" buttons ke liye individual service pages
- [ ] Google Maps embed aur testimonials section
- [ ] Duplicate CSS cleanup (`.sc`, `.g4`, `.urg` rules do jagah define hain)
- [ ] Unsplash images ko local optimize kar ke host karna (speed ke liye)

---

## 📬 Contact

| | |
|---|---|
| 📧 **Email** | Safia34740@gmail.com |
| 💼 **LinkedIn** | [safiadeveloper](https://linkedin.com/in/safiadeveloper) |
| 🐙 **GitHub** | [safiadeveloper](https://github.com/safiadeveloper) |
| 🌐 **Portfolio** | [safiabibiportfolio.site](https://safiabibiportfolio.site) |

---

<p align="center">Made with ❤️ by <b>Safia Bibi</b> · © 2026 Couvreur Yerres</p>
