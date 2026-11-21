# Prince Sen — Portfolio Website

Personal portfolio of **Prince Sen**, Senior Software Developer at Coforge (British Airways client) — Python, Django, FastAPI, RAG AI, PostgreSQL optimisation and full-stack development. Based in Dwarka, New Delhi.

Live repository: https://github.com/prince8076/portfolio-website

## What's on the page

Single-page static site (`index.html`, no build step) with:

- **Hero** — massive stacked typography (PRINCE / outlined SEN) with per-character rise animation, a Three.js WebGL particle network + floating wireframe geometry, parallax orbs and floating skill chips, scroll-scrubbed hero exit, and Prince's GitHub profile photo in a premium 3D-tilt frame (rotating amber ring, PS monogram badge, and a PS monogram fallback panel if the avatar ever fails to load)
- **01 · About / Summary**
- **02 · Key Highlights** — quantified wins (−78% anti-phishing response, −65% SaunaSpot API time, −60% RAG+GIS query time, 800ms→200ms endpoints, 95% uptime at 1,000+ req/sec, −70% database hits)
- **03 · Skills** — Languages, Backend, AI/ML, Databases, Real-time, Testing/DevOps, Frontend
- **04 · Experience** — Coforge (British Airways) · Bombay Softwares · EkVayu Tech (Indian Air Force) · Success Webtech · Amosta (intern), with a scroll-filled timeline
- **05 · Projects** — including the live [Shreeji Corporates](https://www.shreejicorporates.com/) trophy website
- **06 · Education** — PG Diploma in AI & ML, IIT Jodhpur (CGPA 8.75); B.Tech CSE (CGPA 7.1)
- **07 · Publications** — 2 Springer papers, 2025 (SharPy; Microgrid cybersecurity)
- **08 · Contact** — email, phone, LinkedIn, GitHub; resume available on request by email

Redesign v2 (2026-11-21, MotionSites-inspired): rebuilt using the free MotionSites portfolio prompts — Laptop Portfolio (rich black #030304, glass nav with glowing CTA, hero chips, stats band, animated skill bars, filterable projects with modal case studies, 4-step Process, contact form), Sphere Gallery (giant outlined "PRINCE SEN" watermark behind the hero), Dark Portfolio (horizontal scrolling project strip) and Sea Ring (Instrument Serif italic accents, gently bobbing highlight cards). The paid Dark/Ink Portfolio prompts were used as visual reference only; no paid plan was bought.

Design: bespoke dark editorial identity in the spirit of the Shreeji Corporates site — single molten-amber accent on near-black, Space Grotesk display type, film grain, editorial grid lines, cinematic skills marquee, custom cursor follower, 3D-tilt cards with glare. All resume facts are taken verbatim from Prince's resume; no salary/CTC information appears anywhere.

## Run locally

No build tooling needed — just open `index.html` in a browser, or serve it:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Deploy on GitHub Pages

1. Push `index.html` and this `README.md` to the `main` branch.
2. Repo **Settings → Pages → Source: Deploy from a branch → `main` / (root)**.
3. The site goes live at https://prince8076.github.io/portfolio-website/

## Notes

- The hero portrait loads from Prince's public GitHub avatar (`avatars.githubusercontent.com/u/62479635`). If it cannot load, a PS monogram panel is shown instead — the layout never breaks.
- If the Three.js CDN or WebGL is unavailable, the hero automatically falls back to a lightweight Canvas 2D particle network, and then to CSS gradients — content is never blank.
- Heavy 3D is reduced on small screens, animation is disabled for `prefers-reduced-motion`, and tilt only runs on devices with a fine pointer.
- **Resume download:** to offer a direct download, add the resume PDF to this repo (e.g. `Prince-Sen-Resume.pdf`) and link it from the Contact section. Until then, the page notes that the resume is available on request by email.

## Contact

- Email: princesen00c@gmail.com
- Phone: +91-9773823909
- LinkedIn: https://www.linkedin.com/in/prince-sen-7a5339301/
- GitHub: https://github.com/prince8076
