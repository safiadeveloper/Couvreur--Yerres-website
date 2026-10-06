# 🏠 Couvreur Yerres – Roofing Company Website

A modern, responsive, single-file website built for a French roofing company, **Couvreur Yerres**. It presents roofing, zinc work, waterproofing, insulation and emergency leak repair services, and includes a detailed **quote (devis) request form**.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)
![Responsive](https://img.shields.io/badge/Responsive-Yes-success)
![Site Language](https://img.shields.io/badge/Site%20language-French-blue)

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
10. [Quote Form Flow](#-quote-form-flow)
11. [Responsive Design](#-responsive-design)
12. [SEO & Accessibility](#-seo--accessibility)
13. [TODO / Placeholders](#-todo--placeholders)
14. [Contact](#-contact)

---

## 📖 Overview

| Detail | Info |
|---|---|
| **Project name** | Couvreur Yerres |
| **Type** | Business / service landing page |
| **Site language** | French (`lang="fr"`) |
| **Main file** | `couvreur-yerres.html` (single file – HTML, CSS and JS inline) |
| **Target audience** | Homeowners and businesses in Yerres (91330) and the surrounding region |
| **Main goal** | Convert visitors into **quote requests** or **emergency calls** |

---

## ✨ Features

- 📞 **Top info bar** – 24/7 leak emergency line, email, free quote within 48 h
- 🧭 **Sticky navbar** with dropdown submenus (shrinks on scroll)
- 🌧️ **Animated hero** – rain effect, drifting clouds, skyline SVG
- 📝 **Detailed quote form** – service type, urgency, city, project details
- 📧 **mailto integration** – submitting the form opens the visitor's email app
- 🏅 **"Why choose us"** – 5 trust cards
- 🏢 **About section** – overlapping, tilted images
- 🛠️ **8 service cards** – images, hover zoom, angled-corner design
- 🚨 **Emergency banner** – 24/7 leak intervention
- 🔢 **3-step process** – consultation → works → final inspection
- 🎞️ **Marquee ticker** – scrolling strip of services
- 🎬 **Scroll-reveal animations** (IntersectionObserver)
- ♿ **Accessibility** – focus-visible outlines, ARIA labels, `prefers-reduced-motion`
- 📱 **Fully responsive** – mobile, tablet, desktop
- 📲 **Safe-area support** – `env(safe-area-inset-*)` for notched phones

---

## 📸 Screenshots

### 1️⃣ Top Bar, Header & Navigation

| Header & Navigation |
|:---:|
| <img src="https://github.com/user-attachments/assets/4da08865-b97e-45ec-a689-6aad0d85339d" alt="Header and navigation" width="100%"> |
| Logo, phone, service area, "Request a quote" button and sticky navbar |

### 2️⃣ Quote (Devis) Section

| Quote Section – Info & Form |
|:---:|
| <img src="https://github.com/user-attachments/assets/25710f50-72ff-4078-a63c-6d2b84394ae7" alt="Quote section" width="100%"> |
| Left: tag, heading, ten-year warranty, callback card · Right: name, phone, email, city, service, timeframe, details |

### 3️⃣ About Section

| About Section |
|:---:|
| <img src="https://github.com/user-attachments/assets/928f2651-d4a8-4939-b1a5-a0e26f3edcf8" alt="About section" width="100%"> |
| Two tilted images (`roof1.jpg`, `roof2.jpg`) that straighten on hover, company intro, qualification badge, phone number and CTA button |

### 4️⃣ Services Section

| Services Grid |
|:---:|
| <img src="https://github.com/user-attachments/assets/b20f13d7-8c6b-4801-9769-50ea32c736d4" alt="Services section" width="100%"> |
| New roofing, Framework, Waterproofing, Cleaning, Zinc work, Roof windows, Facade renovation, Insulation |

### 5️⃣ Emergency Banner & Process Steps

| Emergency Banner & Steps |
|:---:|
| <img src="https://github.com/user-attachments/assets/3173b31d-6a3a-4a71-8e3e-7177c62bda6f" alt="Emergency banner and process steps" width="100%"> |
| "Leak emergency?" 24/7 call-to-action, then 3 steps: consultation, roofing works, final inspection |

### 6️⃣ Footer

| Footer |
|:---:|
| <img src="https://github.com/user-attachments/assets/ff82abea-2bff-4c03-b35c-cc84a3f856c8" alt="Footer" width="100%"> |
| Logo, contact details, service links, legal links, copyright |

---

## 🧰 Tech Stack

| Technology | Used for |
|---|---|
| **HTML5** | Semantic structure (`header`, `nav`, `section`, `article`, `footer`) |
| **CSS3** | Grid, Flexbox, CSS variables, clip-path, keyframe animations |
| **Vanilla JavaScript** | Form → mailto, sticky navbar, scroll reveal |
| **Google Fonts** | Montserrat (headings) + Roboto (body text) |
| **Unsplash** | Service card images (remote URLs) |

> No frameworks, libraries or build tools required.

---

## 📂 Project Structure

```
couvreur-yerres/
│
├── couvreur-yerres.html     # Main file (HTML + CSS + JS)
├── roof.jpg                 # Hero background image
├── roof1.jpg                # About section – image 1
├── roof2.jpg                # About section – image 2
└── README.md
```

---

## 🚀 Installation & Usage

### Option 1 – Open directly in a browser
1. Download or clone the project folder
2. Double-click `couvreur-yerres.html`
3. The site opens in your default browser ✅

### Option 2 – Local server (recommended)

```bash
# Python
python -m http.server 8000

# or Node.js
npx serve .
```

Then open `http://localhost:8000/couvreur-yerres.html`.

### Option 3 – VS Code Live Server
1. Open the folder in VS Code
2. Install the **Live Server** extension
3. Right-click the HTML file → **Open with Live Server**

### Deployment
Free hosting options: **GitHub Pages**, **Netlify**, **Vercel**, **Cloudflare Pages** – just upload the folder.

---

## 🧩 Sections Breakdown

| # | Section | ID / Class | Description |
|:-:|---|---|---|
| 1 | Top bar | `.top` | Emergency line, email, free quote |
| 2 | Header | `.head` | Logo, phone, service area, CTA |
| 3 | Navbar | `.navbar` | Sticky menu with dropdowns |
| 4 | Hero | `#accueil` | Background image, title, skyline SVG |
| 5 | Quote | `#devis` | Info column + detailed form |
| 6 | Ticker | `.tick` | Scrolling services strip |
| 7 | Why us | `.why` | 5 trust cards |
| 8 | About | `#apropos` | Company intro + images |
| 9 | Services | `#services` | 8 service cards + emergency banner |
| 10 | Steps | `.steps` | 3-step process |
| 11 | Footer | `#contact` | Contact details, links, copyright |

---

## 🎨 Customization

### Colors (CSS variables)

Edit these in `:root`:

| Variable | Default | Used for |
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
- **Hero:** replace `roof.jpg` with your own image
- **About:** replace `roof1.jpg` and `roof2.jpg`
- **Services:** swap the `<img src="https://images.unsplash.com/...">` URLs for your own

### Contact details
Update these in the HTML:
- Phone: `01 00 00 00 00` and `tel:+33100000000`
- Email: `Safia34740@gmail.com` (top bar, footer, and the JS `mailto`)
- Address and SIRET: footer placeholders `[Votre adresse]`, `[à compléter]`

---

## 🎬 Animations & Effects

| Effect | Where | Technique |
|---|---|---|
| Falling rain | Hero | `repeating-linear-gradient` + `@keyframes rain` |
| Drifting clouds | Hero | `radial-gradient` + `@keyframes cloud` |
| Skyline rise | Hero SVG | `@keyframes rise` |
| Badge pop-in | Hero | `@keyframes pop` |
| Button shine | `.btn` | Skewed gradient on `::after` |
| Pulsing phone icon | Header | `@keyframes ring` |
| Marquee | Ticker | `@keyframes mq` |
| Card lift & icon spin | Why us | `transform` on hover |
| Image zoom | Service cards | `scale()` on hover |
| Wobble | Emergency button | `@keyframes wob` |
| Floating icons | Steps | `@keyframes bob` |
| Scroll reveal | Cards, titles | `IntersectionObserver` + `.rv` / `.in` |
| Title underline grow | All `h2` | `h2::after` width transition |

---

## 📨 Quote Form Flow

```
Visitor fills in the form
        ↓
JS catches the "submit" event (preventDefault)
        ↓
Email body is built from name, phone, email and message
        ↓
Status message "Votre application e-mail s'ouvre..." is shown
        ↓
A mailto: link opens the visitor's email app
```

**Form fields:**

| Field | Type | Required |
|---|---|:-:|
| Full name | text | ✅ |
| Phone | tel | ✅ |
| Email address | email | ✅ |
| Postcode / City | text | ✅ |
| Type of service | select | ✅ |
| Desired timeframe | select | ❌ |
| Project details | textarea | ✅ |

> 💡 **Note:** The form currently uses `mailto:`, so the visitor needs an email app set up. For a real backend, consider **Formspree**, **EmailJS**, **Netlify Forms**, or your own **PHP / Node API**. The `service`, `delai` and `ville` fields are not currently included in the email body – add them in the JS if needed.

---

## 📱 Responsive Design

| Breakpoint | Changes |
|---|---|
| `≤ 850px` | Quote section becomes single column, form fields stack |
| `≤ 800px` | Forms, About and Footer go single column; navbar items two per row; hero padding adjusts |
| `≤ 650px` | Emergency banner switches to a vertical layout |
| Auto-fit grids | Service and "why us" cards adapt via `minmax()` |

---

## 🔍 SEO & Accessibility

**SEO**
- `lang="fr"` attribute
- Meaningful `<title>` and `<meta name="description">`
- Semantic HTML and a clear heading hierarchy
- `alt` text on images

**Accessibility**
- `aria-label` on navigation and inputs, `aria-hidden` on decorative elements
- `:focus-visible` outlines
- `role="status"` on the success message
- `prefers-reduced-motion` support – animations turn off automatically

---

## ✅ TODO / Placeholders

- [ ] Add the real phone number (`01 00 00 00 00`)
- [ ] Fill in the footer address and SIRET
- [ ] Add `roof.jpg`, `roof1.jpg`, `roof2.jpg` to the project folder
- [ ] Create the privacy policy and legal notice pages (links are currently `#`)
- [ ] Connect the form to a real backend
- [ ] Add individual pages for the "En savoir plus" service buttons
- [ ] Add a Google Maps embed and a testimonials section
- [ ] Clean up duplicate CSS (`.sc`, `.g4`, `.urg` rules are defined twice)
- [ ] Optimize and self-host the Unsplash images for speed

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
