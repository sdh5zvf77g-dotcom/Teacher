# Maths Teacher – Progressive Web App

A step-by-step maths practice app that works great when added to the Home Screen on iPhone (including iPhone 15 Pro Max).

## Files
- `index.html` – the app
- `manifest.json` – web app manifest
- `sw.js` – service worker (offline support)
- `icon-192.png`, `icon-512.png`, `apple-touch-icon.png` – icons

## How to put on GitHub Pages

1. Create a new repository (or use an existing one).
2. Upload **all** files in this folder to the root of the repository (or into a `docs` folder if you prefer the docs branch/folder option).
3. In the repo settings → Pages:
   - Source: Deploy from a branch
   - Branch: `main` (or `master`) / root (or `/docs`)
4. Wait 1–2 minutes, then open `https://YOUR-USERNAME.github.io/REPO-NAME/`

## Add to Home Screen on iPhone 15 Pro Max

1. Open the site in **Safari** (not Chrome).
2. Tap the Share button (square with arrow).
3. Scroll down and tap **Add to Home Screen**.
4. The icon (the glowing face) and name “Maths Teacher” should appear.
5. Open it from the Home Screen – it will run in full-screen standalone mode.

## Notes
- Progress is saved in the browser’s localStorage.
- Works offline after the first visit (thanks to the service worker).
- If the icon doesn’t update, delete the old Home Screen icon and add it again.
