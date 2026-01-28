# PWA Starter (iPhone + Android)

## What this gives you
- Installable on Android (manifest + service worker)
- Add-to-Home-Screen on iPhone (apple-touch-icon + meta tags)
- Offline support (basic cache)

## Use it
1) Put your existing game HTML inside `index.html` (replace the <main> content).
2) Host this folder on HTTPS (Netlify, Vercel, GitHub Pages, Cloudflare Pages).
3) Open the URL on your phone and install:
   - iPhone: Share → Add to Home Screen
   - Android: Install app / Add to Home screen

## Important
- Service workers require HTTPS (localhost is OK for testing).
- iOS has some PWA limitations.
