# Priyanshi Bisht — Data Analyst Portfolio

A single-page, story-driven personal portfolio built with 3D visuals and scroll-based animation.

🔗 **Live site:** https://priyanshibishtportfolio.netlify.app/

## About

This site walks visitors through Priyanshi's journey as a Data Analyst — from education and internship experience to tools, projects, and certifications — as a scrollable narrative rather than a static resume page.

## Tech Stack

- **HTML5** — layout, responsive design, monochrome theme
- **[Three.js](https://threejs.org/)** (r128) — 3D particle field background + rotating "insight core" hero visual
- **[GSAP](https://gsap.com/) + ScrollTrigger** — scroll-based reveal animations and timeline progress
- **Vanilla JavaScript** — cursor-based 3D tilt on cards, mouse-reactive 3D scene

No build step or dependencies required — it's a static `index.html` with all JS libraries loaded via CDN.

## Project Structure

```
priyanshi-portfolio/
├── index.html          # Entire site: markup, styles, and scripts
├── assets/
│   ├── photo.jpg        # Profile photo used in the About section
│   └── resume.pdf       # Downloadable resume (linked from Hero + Contact buttons)
└── README.md
```

Keep the `assets/` folder alongside `index.html` when you move, clone, or deploy the project — the site references these files by relative path.

## Sections

1. **Hero** — intro, role, resume download, 3D "insight core"
2. **About** — summary + profile photo + quick stats
3. **Journey** — animated timeline of education & internship
4. **Skills** — toolkit broken into programming, visualization, and analytical abilities
5. **Projects** — PhonePe Analytics Dashboard, Regional Sales Dashboard, Fertilisers Sales Dashboard
6. **Certifications & Awards** — linked certificates (Forage, Simplilearn)
7. **Education**
8. **Contact** — resume download, email, WhatsApp, LinkedIn, GitHub, Instagram

## Running Locally

Just open `index.html` in any modern browser — no server or install needed.

```bash
git clone https://github.com/EthicallyInclined/priyanshi-portfolio.git
cd priyanshi-portfolio
open index.html   # or double-click the file
```

## Deploying

This is a static site, so it works out of the box with:

- **GitHub Pages** — enable Pages on this repo, set source to `main` branch / root, done.
- **Netlify** — drag-and-drop the folder or connect the repo.

## Contact

- LinkedIn: [priyanshi-bisht-9396ab300](https://www.linkedin.com/in/priyanshi-bisht-9396ab300)
- GitHub: [@EthicallyInclined](https://github.com/EthicallyInclined)
- Instagram: [@ethically_inclined](https://instagram.com/ethically_inclined)
- Email: priyanshibisht11082005@gmail.com
