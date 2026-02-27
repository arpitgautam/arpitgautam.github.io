# Portfolio — arpitgautam.github.io

Personal portfolio site hosted on GitHub Pages.

## Tech Stack
- **Plain HTML/CSS/JS** — no build step, no framework, no bundler
- Deploys automatically to GitHub Pages on push to `main`

## File Structure
```
/
├── index.html       # Single-page portfolio (all sections)
├── style.css        # All styles
├── assets/          # Images, icons, etc.
│   └── profile.jpg  # Profile photo (add when ready)
└── CLAUDE.md        # This file
```

## Design System
- **Style**: Dark editorial
- **Fonts**: DM Serif Display (headings) · DM Sans (body) · JetBrains Mono (labels/mono)
- **Palette**:
  - Background: `#0c0c0f`
  - Surface: `#151519`
  - Text: `#e8e6e1`
  - Accent: `#c9a86c` (gold)
  - Muted: `#9a978f`
  - Border: `#2a2a32`
- **Max width**: `1100px`
- **Layout**: Single-page, smooth-scroll, responsive (mobile-first), scroll-triggered animations via IntersectionObserver

## Sections
1. **Hero** — Name, tagline, CTA buttons
2. **Journey** — Career timeline (Engineer → Senior → Staff → Senior Architect)
3. **Domains** — 6 domain cards (SaaS, E-Commerce, Desktop, Platform, Video, Postage)
4. **About** — Bio + initials placeholder (replace with photo when ready)
5. **Contact** — GitHub and LinkedIn links

## Local Dev Server
```bash
cd ~/Desktop/arpitgautam.github.io
npx live-server
```

## Deployment
Push to `main` — GitHub Pages serves `index.html` from the repo root automatically.
Enable GitHub Pages in repo Settings → Pages → Source: Deploy from branch → `main` / `(root)`.
