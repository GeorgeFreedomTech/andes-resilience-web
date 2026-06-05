# Andes Resilience Web

A minimalist, high-performance, and mobile-first static landing page for **Andes Resilience** (Physical restoration, structural alignment, and functional movement resilience). 

Built with a focus on **digital resilience** — zero-backend architecture, zero trackers, ultra-fast load times, and maximum privacy. Engineered to convert clientele directly via WhatsApp communication channel.

## Tech Stack
- **HTML5** (Semantic structure)
- **Pico CSS** (Minimalist, lightweight CSS framework for semantic HTML)
- **GitHub Pages** (Production hosting and deployment via global CDN)

## Key Features

*   **Zero Bloat:** No databases, no external JavaScript frameworks, and no cookie-consent banners required.
*   **High-Conversion Architecture:** Fully streamlined funnel focused on a single call-to-action (Direct Phone & WhatsApp link).
*   **Dual-Language Infrastructure:** Built-in support for English (default) and Spanish locales, utilizing fully relative pathways to allow standalone offline execution.

## Architecture
This repository uses a single-repo, subdirectory architecture to manage language mutations efficiently without duplicity of core assets.

```text
├── index.html        # Main English landing page (andesresilience.com)
├── es/
│   └── index.html    # Spanish landing page ([andesresilience.com/es/](https://andesresilience.com/es/))
└── static/           # Shared production assets (Pico CSS, images, icons)
│   └── IMG
│   │   └── hero.jpg
│   │   └── favicon.png
│   └── CSS
│       └── custom.css
│       └── pico.min.css
└── README.md         # System documentation
```
