<div align="center">

# ⟨ Akhter Hussain ／⟩
### Frontend Developer Portfolio — Production-Quality HTML5 & CSS3

[![HTML5](https://img.shields.io/badge/HTML5-Semantic-e44d26?style=flat-square&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-BEM_Architecture-264de4?style=flat-square&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![Responsive](https://img.shields.io/badge/Design-Mobile--First-ff6b35?style=flat-square)](#)
[![Accessibility](https://img.shields.io/badge/A11Y-WCAG_Compliant-2e7d32?style=flat-square)](#)
[![Status](https://img.shields.io/badge/Status-Open_to_Internship-1a4fcf?style=flat-square)](#contact)

<br/>

> *"Clean code, proper information architecture, and accessibility are not optional — they are engineering fundamentals."*

<br/>

**[🌐 Live Demo](#) · [📁 GitHub](https://github.com/akhterhussain134) · [💼 LinkedIn](https://www.linkedin.com/in/akhter-hussain-324491357) · [📧 Email](mailto:akhtarwani666@gmail.com)**

</div>

---

## 📌 Table of Contents

- [About the Project](#-about-the-project)
- [Live Preview](#-live-preview)
- [Portfolio Sections](#-portfolio-sections)
- [Technical Features](#-technical-features)
- [CSS Architecture](#-css-architecture)
- [Engineering Principles](#-engineering-principles)
- [Skills & Proficiency](#-skills--proficiency)
- [Services Offered](#-services-offered)
- [Projects Showcased](#-projects-showcased)
- [Certifications](#-certifications)
- [Internship Journey](#-internship-journey)
- [File Structure](#-file-structure)
- [Getting Started](#-getting-started)
- [Design System](#-design-system)
- [Accessibility](#-accessibility)
- [Contact](#-contact)

---

## 🧑‍💻 About the Project

This is a **personal developer portfolio website** built entirely with **semantic HTML5 and modern CSS3** — no frameworks, no preprocessors, no JavaScript UI libraries. Every design decision, layout system, and CSS pattern reflects real-world frontend engineering best practices applied from the ground up.

The portfolio is designed to demonstrate not just aesthetics, but **depth of knowledge**: BEM architecture, CSS custom properties as design tokens, accessibility-first markup, mobile-first responsiveness, and Separation of Concerns — the same principles expected in production environments.

### Why this project stands out:
- ✅ Zero CSS frameworks — 100% handcrafted stylesheet
- ✅ Production-level BEM naming convention throughout
- ✅ Full WCAG accessibility compliance (ARIA, roles, focus management)
- ✅ Design token system via CSS Custom Properties
- ✅ Dual-axis layout strategy: CSS Grid (macro) + Flexbox (micro)
- ✅ Mobile-first responsive design across all breakpoints
- ✅ Open Graph meta tags for rich social sharing
- ✅ Minimal, purposeful JavaScript (nav toggle + year update only)

---

## 🖥️ Live Preview

> *(Replace with your deployed URL — GitHub Pages, Netlify, or Vercel)*

```
https://akhterhussain134.github.io/portfolio
```

To deploy instantly with GitHub Pages:
1. Push this repo to GitHub
2. Go to **Settings → Pages → Source → `main` / `root`**
3. Your site goes live at `https://<username>.github.io/<repo-name>`

---

## 📄 Portfolio Sections

| # | Section | Description |
|---|---------|-------------|
| 1 | **Hero** | Name, title, animated stat counters, code snippet illustration, CTA buttons, scroll indicator |
| 2 | **About** | Bio, education, focus area, availability status, quick-facts list |
| 3 | **Skills & Tools** | Proficiency cards with visual progress bars, productivity tools, certifications |
| 4 | **Services** | Six service offerings with icon cards and category tags |
| 5 | **Engineering Principles** | Six numbered principle articles with code examples |
| 6 | **Projects** | Featured project cards with image previews, tech tags, and GitHub links |
| 7 | **Testimonials** | Mentor and lecturer quote cards with blockquote semantics |
| 8 | **Internship Journey** | Numbered timeline from learning fundamentals to portfolio milestone |
| 9 | **Contact** | Contact info links + accessible HTML form wired to email |
| 10 | **Footer** | Brand, navigation, social links, dynamic year via JS |

---

## ⚙️ Technical Features

### 🔷 HTML5 — Semantic Markup
- `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<aside>`, `<footer>` used throughout — no `<div>` soup
- Single `<h1>` per page with a strict heading hierarchy (`h1 → h2 → h3 → h4`)
- Landmark regions enable screen reader navigation
- `role`, `aria-label`, `aria-labelledby`, `aria-expanded`, `aria-current`, `aria-required`, `aria-hidden` applied throughout
- `<blockquote>` with `<cite>` for testimonials
- `<ol>` for the ordered journey timeline, `<ul role="list">` for skill/project grids
- All interactive elements have keyboard-accessible focus states
- Open Graph meta tags for social previews (`og:title`, `og:description`, `og:type`)
- `<meta name="theme-color">` for mobile browser chrome theming
- `<meta name="description">` optimised for search engines
- `loading="lazy"` on all project images for performance
- `rel="noopener noreferrer"` on all external links for security

### 🔷 CSS3 — Architecture & Layout
- **BEM methodology** applied throughout: `.block__element--modifier`
- **CSS Custom Properties** as a full design token system (colours, typography, spacing, radii, shadows, transitions)
- **CSS Grid** for all macro page layouts (hero, about, skills, services, projects, contact)
- **Flexbox** for all micro component alignment (nav, buttons, cards, badges)
- **CSS `clamp()`** for fluid, viewport-responsive typography
- **CSS animations** on hero rings, badge floats, scroll indicator, code snippet entrance
- **CSS `@keyframes`** for `float`, `ring-pulse`, `slide-up`, `fade-in` effects
- **CSS variables for skill bars** — `--skill-pct` custom property powers all proficiency bar fills
- **17 distinct CSS sections** organised with a documented Table of Contents
- Sticky header with scroll-triggered backdrop filter (CSS `backdrop-filter: blur`)
- Scroll margin on all section targets (`scroll-margin-top`) to account for sticky nav
- Smooth scroll via `scroll-behavior: smooth` on `html`

### 🔷 JavaScript — Minimal & Purposeful
- **Mobile nav toggle** — ARIA-driven open/close with `aria-expanded` state
- **Auto-close on link click** — nav closes when any link is tapped on mobile
- **Dynamic year** — `new Date().getFullYear()` keeps the footer copyright current
- Zero external JS dependencies; zero UI frameworks

### 🔷 Performance
- Google Fonts loaded via `<link rel="preconnect">` for DNS pre-resolution
- All images use `loading="lazy"` to defer off-screen loading
- Font display limited to three families, each loaded with only the weights used
- No render-blocking JS — single `<script>` block at bottom of `<body>`

### 🔷 SEO & Social
- Descriptive `<meta name="description">` for search engine indexing
- Open Graph tags for rich link previews on LinkedIn, Twitter, WhatsApp
- Meaningful, keyword-rich heading structure throughout
- Correct `lang="en"` on `<html>` for language detection

---

## 🏗️ CSS Architecture

The stylesheet (`style.css`) is **1800+ lines** of hand-authored CSS, structured as a professional codebase:

```
style.css
│
├── 01. Custom Properties (Design Tokens)   ← Entire visual language lives here
├── 02. CSS Reset & Base                    ← box-sizing, margin, smooth scroll
├── 03. Typography System                   ← fluid clamp() scale, font stacks
├── 04. Utility Classes                     ← .container, .sr-only, .section
├── 05. Reusable Components                 ← .card, .button, .tag (DRY)
├── 06. Header & Navigation                 ← sticky header, mobile toggle
├── 07. Hero Section                        ← grid, avatar, animations
├── 08. About Section                       ← two-column grid, facts list
├── 09. Skills Section                      ← skill cards, progress bars, certs
├── 10. Services Section                    ← icon service cards
├── 11. Engineering Principles Section      ← numbered article grid
├── 12. Projects Section                    ← project card grid
├── 13. Testimonials Section                ← blockquote cards
├── 14. Internship Journey (Timeline)       ← numbered vertical timeline
├── 15. Contact Section                     ← two-column form layout
├── 16. Footer                              ← three-column footer grid
└── 17. Media Queries                       ← mobile-first breakpoints
```

---

## 📐 Engineering Principles

Six core engineering principles are documented as actual portfolio content, demonstrating professional maturity:

| # | Principle | Implementation |
|---|-----------|---------------|
| 01 | **DRY — Don't Repeat Yourself** | Reusable `.card`, `.button`, `.tag` components; custom property tokens |
| 02 | **Semantic DOM** | Correct use of all HTML5 landmark and sectioning elements |
| 03 | **Separation of Concerns** | HTML = structure only; CSS = presentation only; zero inline styles |
| 04 | **Grid vs Flexbox** | CSS Grid for 2D macro layouts; Flexbox for 1D component alignment |
| 05 | **Information Architecture** | Single `<h1>`, strict heading hierarchy, anchor navigation |
| 06 | **Accessibility (A11Y)** | ARIA attributes, 4.5:1 contrast minimum, keyboard navigation, landmark regions |

---

## 📊 Skills & Proficiency

### Frontend Development
| Skill | Proficiency |
|-------|-------------|
| HTML5 — Semantic markup, accessibility, structure | ████████░░ 85% |
| CSS3 — Grid, Flexbox, animations, custom properties | ████████░░ 82% |
| Flexbox | ████████░░ 82% |
| Responsive Web Design (Mobile-First) | ████████░░ 80% |
| CSS Grid | ███████░░░ 78% |
| Accessibility (A11Y / WCAG) | ███████░░░ 75% |
| Frontend Architecture (BEM, DRY) | ███████░░░ 74% |
| UI/UX Basics — Visual hierarchy, spacing | ███████░░░ 72% |

### Productivity & Tools
`MS Excel / Spreadsheets` · `PowerPoint` · `MS Word` · `Generative AI`

---

## 🛠️ Services Offered

| Service | Tag |
|---------|-----|
| 🖥️ **Web Design** — Visually modern, technically clean layouts | `UI Design` |
| 💻 **Frontend Development** — Pixel-perfect, accessible HTML & CSS | `HTML & CSS` |
| 📱 **Responsive Design** — Mobile-first fluid layouts for all screen sizes | `Mobile-First` |
| ⊞ **UI Engineering** — CSS Grid, Flexbox, BEM for scalable components | `Architecture` |
| 📋 **Landing Page Design** — High-impact, conversion-focused pages | `Marketing` |
| ♿ **Accessible Websites** — WCAG-compliant, keyboard-navigable builds | `WCAG` |

---

## 🚀 Projects Showcased

### 1. 📰 Responsive News Portal
> **Tech Stack:** `HTML5` · `CSS3` · `Java (Frontend)`

A fully responsive news portal website featuring:
- Structured editorial layout with category navigation
- Mobile-first responsive design
- Clean typographic hierarchy for readability

🔗 [View on GitHub](https://github.com/akhterhussain134)

---

### 2. 🤖 Arduino Robotic Car
> **Tech Stack:** `Arduino Uno` · `Ultrasonic Sensor` · `Embedded C`

A hardware project demonstrating cross-disciplinary engineering:
- Autonomous obstacle detection and avoidance in real time
- Ultrasonic sensor-driven logic programmed in Embedded C
- Demonstrates systems thinking beyond the browser

🔗 [View on GitHub](https://github.com/akhterhussain134)

---

### 3. 🔜 Next Project *(In Progress)*
A new frontend project demonstrating advanced CSS architecture and responsive design patterns — coming soon.

---

## 🏅 Certifications

| Certificate | Issuing Body |
|-------------|-------------|
| 🥇 Generative AI | LinkedIn Learning & Microsoft |
| 🥇 EXIN BCS Artificial Intelligence Essentials | EXIN / BCS |
| 🥇 Diploma in Computer Applications (DCA) | Recognised Institute |

---

## 🗺️ Internship Journey

A step-by-step learning roadmap from student to frontend engineer:

```
01 ── HTML5 Fundamentals
      Semantic markup, document structure, heading hierarchy,
      landmark elements, accessibility basics
         │
02 ── CSS Architecture & Layout
      CSS Grid, Flexbox, custom properties, BEM methodology,
      DRY styling principles
         │
03 ── Responsive Web Engineering
      Mobile-first design, fluid typography, adaptive layouts,
      cross-device testing
         │
04 ── Portfolio Project  ✦ Milestone
      Synthesised all principles into this production-quality
      portfolio — a complete frontend engineering demonstration
```

---

## 📁 File Structure

```
portfolio/
│
├── index.html              # Main HTML document (single-page application)
├── style.css               # Full CSS architecture (~1800 lines, 17 sections)
│
└── project images/
    ├── News portal website.PNG
    └── Arduino Robotic car.jpeg
```

> The entire site runs from **two files** — no build tools, no package managers, no dependencies.

---

## 🚀 Getting Started

### Option 1 — Open Locally
```bash
# Clone the repository
git clone https://github.com/akhterhussain134/<repo-name>.git

# Navigate into the directory
cd <repo-name>

# Open in your browser
open index.html
# or double-click index.html in your file manager
```

### Option 2 — Live Server (Recommended for Development)
```bash
# If you have VS Code with Live Server extension:
# Right-click index.html → "Open with Live Server"

# Or use Python's built-in server:
python -m http.server 8000
# Then visit: http://localhost:8000
```

### Option 3 — Deploy to GitHub Pages
1. Push this repository to GitHub
2. Navigate to **Settings → Pages**
3. Set Source to `Deploy from a branch` → `main` → `/ (root)`
4. Click **Save** — live in ~60 seconds

---

## 🎨 Design System

The entire visual language is defined in **CSS Custom Properties** (design tokens), making it easy to update the theme from a single location:

```css
:root {
  /* Palette */
  --clr-primary:    #1a4fcf;   /* Brand blue */
  --clr-accent:     #ff6b35;   /* Warm orange */
  --clr-dark:       #0a1628;   /* Deep navy */
  --clr-bg:         #f5f7fc;   /* Page background */

  /* Typography */
  --font-display:   'Syne',    sans-serif;   /* Headings */
  --font-body:      'Outfit',  sans-serif;   /* Body copy */
  --font-mono:      'DM Mono', monospace;    /* Code snippets */

  /* Fluid Type Scale: --fs-xs (12px) → --fs-5xl (72px) */
  /* Spacing Scale:    --sp-1  (4px)  → --sp-32  (128px) */
}
```

**Google Fonts loaded:** Syne (400/600/700/800) · Outfit (300/400/500/600) · DM Mono (300/400/500)

---

## ♿ Accessibility

This portfolio is built with accessibility as a **first-class engineering requirement**, not an afterthought:

- **Semantic HTML** — screen readers receive meaningful structure
- **ARIA attributes** — `aria-label`, `aria-labelledby`, `aria-expanded`, `aria-current`, `aria-required`, `aria-hidden`, `aria-disabled`, `aria-valuemin/max/now` used precisely
- **Keyboard Navigation** — all interactive elements are fully keyboard-operable
- **Focus Management** — mobile nav closes on link selection; visible focus styles on all interactive elements
- **Colour Contrast** — minimum 4.5:1 ratio (WCAG AA) for all text
- **Skip Link** — `#main-content` anchor for keyboard users
- **Progressive Disclosure** — `aria-expanded` correctly signals nav state to assistive tech
- **ARIA `role` attributes** — `role="list"`, `role="banner"`, `role="contentinfo"`, `role="progressbar"` applied throughout
- **Screen-reader-only text** — `.sr-only` utility class hides decorative elements from assistive technology
- **Alt text** — all meaningful images include descriptive `alt` attributes; decorative elements have `aria-hidden="true"`

---

## 📬 Contact

<div>

| Platform | Link |
|----------|------|
| 📧 Email | [akhtarwani666@gmail.com](mailto:akhtarwani666@gmail.com) |
| 💼 LinkedIn | [linkedin.com/in/akhter-hussain-324491357](https://www.linkedin.com/in/akhter-hussain-324491357) |
| 🐙 GitHub | [github.com/akhterhussain134](https://github.com/akhterhussain134) |

</div>

> **Currently open to:** Frontend Internship Opportunities · Freelance Projects · Collaborations

---

## 📄 License

This project is open source under the [MIT License](LICENSE).
You are welcome to use it as a reference or template — a credit link is appreciated but not required.

---

<div align="center">

**Built with ❤️ and a lot of CSS** · © 2025 Akhter Hussain

`HTML5` · `CSS3` · `BEM` · `A11Y` · `Mobile-First` · `No Frameworks`

</div>
