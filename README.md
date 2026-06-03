# Andes Resilience Web

A minimalist, high-performance, and mobile-first static landing page for **Andes Resilience**. Designed for maximum digital resilience, speed, and clean code architecture.

## Tech Stack
- **HTML5** (Semantic structure)
- **Pico CSS** (Minimalist, lightweight CSS framework for semantic HTML)
- **GitHub Pages** (Production hosting and deployment via global CDN)

## Architecture
This repository uses a single-repo, subdirectory architecture to manage language mutations efficiently without duplicity of core assets.

```text
├── index.html        # Main English landing page (andesresilience.com)
├── es/
│   └── index.html    # Spanish landing page ([andesresilience.com/es/](https://andesresilience.com/es/))
├── assets/           # Shared production assets (Pico CSS, images, icons)
└── README.md         # System documentation
```
