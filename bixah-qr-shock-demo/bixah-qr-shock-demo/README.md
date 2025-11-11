# Bixah QR Shock Demo (Consent-based)
Static educational page to show how easily a web page can profile a visitor and (with consent) access camera/location — **no storage, no network calls**.

## Quick start (GitHub Pages)
1. Create a new public repo named `bixah-qr-shock-demo`.
2. Upload these files to the repo root.
3. Commit & push.
4. Enable **Settings → Pages → Deploy from branch → `main` / `/root`**.
5. Visit: `https://<your-username>.github.io/bixah-qr-shock-demo/?mode=shock`.

## QR text to print
**Scan to see how a page profiles your device — nothing stored.**

## Files
- `index.html` — the demo page
- `assets/favicon.svg` — simple Bixah shield favicon
- `README.md` — this file
- `LICENSE` — MIT
- `.nojekyll` — ensures GitHub Pages doesn’t process files

## Notes
- Camera & Geolocation are **optional and consent-based**.
- The page **does not upload** any data and **does not store** any data.
- Works offline once cached (for features that don’t require permissions).
