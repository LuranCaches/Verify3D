# 3D Project Complexity — Radar (PWA)

Interactive radar + difficulty slider for scoping 3D projects. Installable PWA, offline-ready.

## 🔧 Deploy (One‑click)

[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=<YOUR_GITHUB_REPO_URL>)

**After you push this folder to a public GitHub repo**, replace `<YOUR_GITHUB_REPO_URL>` above with your repo URL, e.g.:

```
https://github.com/yourname/3d-radar
```

Then click the button to create and deploy the site on Netlify.

## 🏗 Local Dev

```bash
# inside this folder
python3 -m http.server 8000
# open http://localhost:8000
```

## 📁 Files

- `index.html` — app UI
- `manifest.webmanifest` — PWA manifest
- `sw.js` — service worker for offline
- `icon-192.png`, `icon-512.png` — app icons
- `netlify.toml` — caching headers
