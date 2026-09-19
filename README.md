# Portfolio — Tarun Sharma

Personal portfolio site of **Tarun Sharma**, an AI Engineer working on Generative AI
and Large Language Model systems in Python, Docker and FastAPI.

**Live site:** https://shar4645.github.io/My-Portfolio/

## About

A single-page portfolio covering my work at Ethara AI, selected Generative AI
projects, technical skills, education and contact details.

## Built with

- Plain HTML and CSS — no framework, no build step, no dependencies
- Vanilla JavaScript for the interactive canvas, theme toggle and scroll progress
- HTML canvas for the animated latent-space field behind the hero
- Inline SVG for the project architecture diagrams
- Google Fonts: Sora, Manrope and JetBrains Mono

Everything lives in a single `index.html`, including the portrait as an embedded
base64 image — one file, no external assets to host.

## Features

- Day and night themes, following the system setting by default and remembered per visitor
- Responsive from phone width upward
- Cursor-reactive particle field in the hero, inspired by nearest-neighbour retrieval
- Respects `prefers-reduced-motion` — every animation falls back to a static state
- Hosted free on GitHub Pages

## Running locally

Clone the repository and open `index.html` in any browser. There is nothing to install.

```bash
git clone https://github.com/Shar4645/My-Portfolio.git
cd My-Portfolio
open index.html      # on Windows: start index.html
```

## Deploying

The site is served by GitHub Pages from the `main` branch, root folder
(Settings → Pages → Deploy from a branch). Any push to `main` republishes it.

## Contact

- **Email:** tarunsharma.ts2003@gmail.com
- **LinkedIn:** https://www.linkedin.com/in/tarun-sharma-031852267/
- **GitHub:** https://github.com/Shar4645
