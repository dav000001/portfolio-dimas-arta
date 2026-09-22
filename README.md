# Dimas Arta® — Portfolio Website

> **Product Designer × Creative Developer**  
> An ultra-crafted, high-fidelity portfolio website built directly from Figma design with modern web technologies.

---

## 🌟 Overview

This repository contains the official portfolio website for **Dimas Arta®**, featuring a sleek dark-mode aesthetic with neon lime accents (`#b8ff3d`), precise typography, interactive case studies, and responsive design down to the pixel.

* **Figma Source**: [View Design on Figma](https://www.figma.com/design/cp0tLiHtXHvyMQvLMQKkiL/Untitled?node-id=0-1)
* **Design Philosophy**: *"Merancang produk digital yang terasa hidup."* (Crafting digital products that feel alive.)

---

## 📸 Key Sections

1. **Header & Navigation**
   - Brand Monogram (`DA`) and official signature.
   - Smooth-scrolling navigation links (*Profil*, *Keahlian*, *Proyek*, *Pengalaman*).
   - Real-time availability indicator badge (*Tersedia untuk Q4*) with pulse animation.

2. **Hero Section**
   - Impactful typography using **Space Grotesk** & **Inter**.
   - Dual Call-to-Action buttons with micro-interactions.
   - Key credibility metrics (+8 years, 32 products, 4.9/5 satisfaction).
   - High-fidelity portrait showcase with ambient glow & coordinate tag (`JAKARTA · 06°12′S`).

3. **Profile Statement**
   - Core philosophy: *"Strategi yang tajam. Eksekusi yang berkarakter."*
   - Bio spanning 8 years of cross-disciplinary craft.

4. **Expertise Grid (Keahlian)**
   - `01` Product Strategy (Research, problem framing, roadmap, validation).
   - `02` Experience Design (User flow, interaction, design systems).
   - `03` Creative Development (Living interfaces through code & motion).
   - `04` Design Leadership (Team alignment, craft quality, product decisions).

5. **Featured Projects (Studi Kasus Terpilih)**
   - **Nusa Finance**: Investment app with **+38% user activation**.
   - **Ruang Energi**: Industrial control system with **–42% operator response time**.
   - **Kala Studio**: Dynamic digital identity with **2.6× quality inquiries**.

6. **Experience & Process**
   - Career timeline across Orbit Digital, Gojek Creative Labs, & Independent Studio.
   - 4-step creative workflow: **Pahami** → **Bentuk** → **Bangun** → **Belajar**.

7. **Testimonial & Contact Callout**
   - Endorsement from Maya Pranoto (VP Product, Nusa Finance).
   - High-contrast Neon Lime Banner for collaboration inquiries.
   - Direct interactive email trigger (`halo@dimasarta.design`).

8. **Footer & Live Clock**
   - Dynamic real-time Jakarta time counter (`JKT HH:MM · GMT+7`).
   - Social links (LinkedIn, Dribbble, Instagram, Read.cv).

---

## ⚡ Tech Stack

* **Build Tool**: [Vite](https://vite.dev/) — Next generation frontend tooling.
* **Styling**: [Tailwind CSS v4](https://tailwindcss.com/) — High-performance utility-first CSS framework.
* **Typography**: Google Fonts ([Space Grotesk](https://fonts.google.com/specimen/Space+Grotesk) & [Inter](https://fonts.google.com/specimen/Inter)).
* **Assets**: High-resolution optimized PNG & SVG assets directly extracted from Figma.

---

## 🎨 Design Tokens & Palette

| Token | Hex Value | Usage |
|---|---|---|
| **Accent Lime** | `#b8ff3d` | CTA buttons, active badges, highlights |
| **Dark Canvas** | `#07080b` | Primary background |
| **Card Surface** | `#0e1015` | Cards, containers, sections |
| **Border Dark** | `#252a35` | Outlines, separators, grid lines |
| **Text Primary** | `#f2f4f8` | Headings, prominent copy |
| **Text Muted** | `#969eae` | Captions, descriptions, metadata |
| **Accent Blue** | `#6b7cff` | Process step numbers & ambient glow |

---

## 🚀 Getting Started

### Prerequisites
Make sure you have Node.js (v18+) and npm installed:
```bash
node -v
npm -v
```

### 1. Clone the repository
```bash
git clone https://github.com/dav000001/portfolio-dimas-arta.git
cd portfolio-dimas-arta
```

### 2. Install dependencies
```bash
npm install
```

### 3. Run development server
```bash
npm run dev
```
Open [http://localhost:5173](http://localhost:5173) in your browser.

### 4. Build for production
```bash
npm run build
```
The optimized production output will be generated in the `dist/` directory.

---

## 📁 Directory Structure

```
├── public/
│   └── assets/                  # High-res images & SVGs extracted from Figma
│       ├── portrait.png
│       ├── project-nusa.png
│       ├── project-ruang-energi.png
│       ├── project-kala.png
│       ├── testimonial-maya.png
│       └── status.svg
├── src/
│   └── style.css                # Tailwind CSS v4 setup & custom tokens
├── index.html                   # Semantic markup & interactive elements
├── package.json                 # Project dependencies & scripts
├── vite.config.js               # Vite & Tailwind configuration
└── README.md                    # Documentation
```

---

## 📄 License

Created for educational & portfolio presentation purposes.  
Original design copyright © 2026 Dimas Arta. Built with care.
