# Cubing Timer (Web)

Online speedcubing timer with multi-method trainers (CFOP, Beginner CFOP, Roux, ZZ, Petrus, Beginner).

## Run locally

```bash
cd cubing-timer-web
python3 -m http.server 8080
```

Open http://localhost:8080

## Deploy

Upload this folder to any static host:

- GitHub Pages
- Netlify / Cloudflare Pages / Vercel
- Any nginx/Apache static root

No build step required.

## Features

- Timer with inspection, +2/DNF, sessions, ao5/ao12
- Method trainers: CFOP, Beginner CFOP (2-look), Roux, ZZ, Petrus, Beginner
- Themes, fonts, sizes
- Works offline after first visit (service worker)
- Smart-cube BT (Chrome/Edge, HTTPS only)

## Files

| File | Purpose |
|------|---------|
| `index.html` | Full app |
| `manifest.webmanifest` | PWA install |
| `sw.js` | Offline cache |
| `icon-*.png` | App icons |
