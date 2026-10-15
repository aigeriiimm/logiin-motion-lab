# Login Motion Lab — fancy login page

Week 06 lab · Web Service Design. Vue + Vite + CSS + localStorage.

**Live page:** https://YOUR-LOGIN.github.io/YOUR-REPO/
**Repository:** https://github.com/YOUR-LOGIN/YOUR-REPO

## What was done
- `src/storage.js` — checkpoints 07–09 (`setItem`, `getItem`, `removeItem`).
- `src/motion.css` — checkpoints 01–06 (focus ring, button hover/press, shake,
  spinner, panel transition, `prefers-reduced-motion`) + fancy design layer:
  animated gradient hero with floating glow blobs, glassmorphism card,
  gradient headings, shimmer button, staggered entrance, animated success badge,
  responsive layout.
- `.github/workflows/deploy.yml` — builds with Vite and publishes to GitHub Pages.

## Run locally
```
npm ci
npm run dev
```
Node 24.12+ (24.x) or 22.18+ (22.x).

Demo only: passwords are never saved or checked.
