# Portfolio

A personal portfolio landing page, built with plain HTML and SCSS and no frameworks. The goal is a fast, minimal one-page site with a dark grid background, expressive typography and subtle animations.

> **Status: work in progress.** The header, hero and footer sections are done. The projects, skills and contact sections are planned.

## What works now

- Page layout with header, hero and footer sections
- Hero headline with an inline link to the (upcoming) projects section
- Animated grid background
- Custom fonts (Manrope and JetBrains Mono), loaded locally
- SCSS architecture split into `core` (reset, variables, typography, grid, layout, animation) and `section` styles

## Planned

- Projects section
- Skills section
- Contact section and links (LinkedIn, GitHub, email)
- English version of the content
- Responsive polish and accessibility check
- Deploy to GitHub Pages

## Tech stack

- HTML5
- SCSS (compiled to `styles/index.css`)
- Local web fonts

## Getting started

```bash
git clone https://github.com/andreyysak/landing.portfolio.git
cd landing.portfolio
```

Open `index.html` in a browser. The compiled stylesheet is committed, so no build step is needed to view the page.

To change the styles, edit the SCSS files and recompile with the [Sass](https://sass-lang.com/install) CLI:

```bash
sass --watch styles/index.scss styles/index.css
```

## Project structure

```text
.
├── index.html
├── fonts/                # Manrope, JetBrains Mono
├── image/                # favicon
└── styles/
    ├── index.scss        # entry point
    ├── index.css         # compiled output
    ├── core/             # reset, fonts, variables, typography, grid, layout, animation
    └── section/          # header, hero, footer
```

## Author

Andrii Sak — frontend developer (React, Next.js, Vue).
[LinkedIn](https://www.linkedin.com/in/andrii-sak-4a3839329/) · [GitHub](https://github.com/andreyysak)
