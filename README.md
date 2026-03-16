# 🚀 Space Portfolio — Vallabhani Akhil

An interactive, cinematic space explorer portfolio where each section of the portfolio is a planet in a journey through space. Built as a single HTML file with no frameworks.

![Space Portfolio](https://img.shields.io/badge/Status-Live-00ff88?style=flat-square) ![HTML](https://img.shields.io/badge/HTML-Single%20File-00f5ff?style=flat-square) ![GSAP](https://img.shields.io/badge/GSAP-3.12.2-ff6a00?style=flat-square)

---

## 🌌 Live Demo

**[🚀 portfolio-ruby-two-la288a0nww.vercel.app](https://portfolio-ruby-two-la288a0nww.vercel.app/)**

---

## 🪐 The Journey

The portfolio is structured as a cinematic space journey across 5 planets:

| # | Planet | Section | Color |
|---|--------|---------|-------|
| 01 | Planet AKHIL | About Me | Cyan |
| 02 | Skill Nebula | Skills & Tech Stack | Purple |
| 03 | Career Orbit | Experience & Education | Green |
| 04 | Project Station | Projects | Orange |
| 05 | Contact Void | Contact & Links | Pink |

---

## ✨ Features

- **Cinematic loading screen** — spaceship assembles itself part by part with a 0→100% progress bar before launch
- **3D animated planets** — each planet is canvas-rendered with terrain, craters, cloud layers, polar caps, atmosphere glow and a terminator shadow edge. Planet 4 (Project Station) has Saturn-style rings
- **Directional spaceship travel** — ship flies left-to-right when going forward, right-to-left when going back, with a -10°/+10° tilt during travel
- **Fire & smoke trail** — 3-layer canvas particle system: fire particles (orange/yellow with glow), smoke particles, spark particles — all spawning from the engine nozzle
- **Orbiting satellite** — animated SVG satellite with solar panels orbiting every planet in an elliptical path
- **Impact shake** — planet side shakes on landing
- **Nebula pulse** — 4 background nebula clouds breathe and expand independently
- **Space debris** — 22 rotating asteroid fragments slowly drifting across the void
- **Shooting meteors** — occasional meteors fly diagonally across the background
- **Staggered content reveal** — GSAP timeline animates headings, dividers, body text, badges and tags in sequence on each landing
- **Custom cursor** — glowing ring cursor that changes color to match the active planet
- **Breadcrumb trail** — visited planets appear as glowing orbs on the left, clickable to revisit
- **Nav dots** — right side dots unlock one by one as you progress through the journey
- **Resume download** — PDF embedded directly in the HTML, downloads with one click (no server needed)
- **Back & Forward navigation** — Launch to Next Planet and Prev Planet buttons, both with full travel animations
- **All links live** — Mailvox, GitHub Profile Roaster, Snoutsy, GitHub, LinkedIn, Email

---

## 🛠️ Tech Stack

| Technology | Usage |
|------------|-------|
| HTML5 / CSS3 | Structure and styling |
| Vanilla JavaScript | All logic and interactivity |
| [GSAP 3.12.2](https://greensock.com/gsap/) | All animations and timelines |
| [GSAP MotionPathPlugin](https://greensock.com/motionpath/) | Ship travel arc paths |
| Canvas API | Planet rendering, star field, particle trails, debris, nebula |
| Google Fonts | Orbitron, Share Tech Mono, Rajdhani |

No build step. No frameworks. No dependencies beyond GSAP via CDN.

---

## 🚀 Getting Started

### Run locally
Just open the file in any browser:
```bash
# Clone the repo
git clone https://github.com/Akhil14324/space-portfolio.git

# Open in browser
open space-portfolio.html
# or just double-click the file
```

### Deploy to Vercel
```bash
# Install Vercel CLI
npm i -g vercel

# Deploy
vercel --prod
```

### Deploy to GitHub Pages
1. Go to repo **Settings → Pages**
2. Set source to **main branch / root**
3. GitHub Pages will serve `index.html` — rename the file to `index.html` first

---

## 📁 Project Structure

```
space-portfolio/
│
├── space-portfolio.html    # The entire portfolio — single self-contained file
└── README.md               # This file
```

Everything — HTML, CSS, JavaScript, fonts (via CDN), GSAP (via CDN), and the resume PDF (base64 embedded) — lives in one file.

---

## 🎮 Controls

| Action | Result |
|--------|--------|
| Click **Launch to Next Planet** | Ship flies to next planet with trail |
| Click **‹ Prev Planet** | Ship flies back to previous planet |
| Click **breadcrumb orb** (left) | Jump to any visited planet |
| Click **nav dot** (right) | Jump to any visited planet |
| Click **Download Resume** | Downloads PDF resume (on Planet AKHIL) |
| Hover over planet labels | Tooltip appears |

---

## 📡 Contact

| | |
|--|--|
| **Email** | akhilvallabhani@gmail.com |
| **GitHub** | [github.com/Akhil14324](https://github.com/Akhil14324) |
| **LinkedIn** | [linkedin.com/in/akhilvallabhani](https://www.linkedin.com/in/akhilvallabhani/) |

---

> Built with 🛸 and way too many GSAP timelines.
