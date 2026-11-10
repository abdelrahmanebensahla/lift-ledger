# Lift Ledger

Installable workout logger (PWA). Static files, no build step. Data is stored on the device (localStorage) with JSON backup export/import.

## Deploy
- Vercel: `npx vercel --prod` from this folder, or import the GitHub repo in Vercel (framework: Other, no build command, output: root).
- Any static host works (Netlify, Cloudflare Pages, GitHub Pages).

## Install on iPhone
Open the URL in Safari, tap Share, then Add to Home Screen.

## Files
- index.html: the whole app
- sw.js: offline cache (bump VERSION on each release)
- manifest.webmanifest + icons/: home-screen install
- vercel.json: cache headers so updates reach installed apps
