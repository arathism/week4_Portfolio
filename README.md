# SecureStack — Business Website

A complete, responsive multi-page website for **SecureStack**, a fictional web development & cybersecurity consulting studio. Built as a Week 4 project for The Developers Arena internship (Option 3 — Professional Services Website).

🔗 **Live site:** https://arathism.github.io/week4_Portfolio/

## About the project

SecureStack offers web development, security audits, and ongoing site monitoring — giving the project a natural reason to include a services breakdown with pricing tiers, a team section, a company timeline, and a validated lead-capture contact form.

## Pages

| Page | Description |
|---|---|
| `index.html` | Homepage — hero, stats, services preview, process, CTA |
| `about.html` | Company story, mission, timeline, team |
| `services.html` | Detailed services, process, pricing tiers |
| `contact.html` | Contact form with client-side validation |

## Tech stack

- Semantic HTML5
- CSS3 (custom properties, mobile-first, no framework)
- Vanilla JavaScript (no libraries)
- Inline SVG for all icons/logo (no raster images)
- Fonts: JetBrains Mono (headings), Inter (body)

## Project structure

```
secure-stack/
├── index.html
├── about.html
├── services.html
├── contact.html
├── css/
│   └── style.css
├── js/
│   └── script.js
├── images/
│   ├── logo.svg
│   └── favicon.svg
└── README.md
```

## Features

- ✅ 4 fully linked pages with consistent nav/footer
- ✅ Mobile-first responsive design (breakpoints at 900px, 860px, 760px, 620px)
- ✅ Hamburger nav on mobile
- ✅ Contact form validated via the HTML5 Constraint Validation API, with inline errors and a live-region success message
- ✅ Animated terminal hero element (respects `prefers-reduced-motion`)
- ✅ Accessibility: skip link, visible focus states, semantic landmarks, labelled form fields, `aria-live` status updates
- ✅ Zero raster images — everything is inline SVG

## Running locally

No build tools required — it's a static site.

```bash
git clone https://github.com/arathism/week4_Portfolio.git
cd week4_Portfolio
python3 -m http.server 8000
# then open http://localhost:8000
```

Or just open `index.html` directly in a browser, or use the VS Code Live Server extension.

## Deployment

Deployed via **GitHub Pages** from the `main` branch, root folder.

## Author

**Arathi S M**
USN: 2AV23CS009
AGMRCET, VTU
Week 4 — The Developers Arena, 2026
