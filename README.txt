# PrintQuote iPhone app

A private installable web app (PWA) for creating 3D-printing quotes.

## Included pricing defaults
- Filament: £15/kg
- Machine time: £2/hour
- Failed-print allowance: 10%
- Selling fee allowance: 5%
- Target profit margin: 30%
- Deposit: 50%
- Final quote rounds UP to the next whole pound.

## Install on iPhone
This project must be hosted on an HTTPS website before iOS can install it as a Home Screen app.

Simple route using GitHub Pages:
1. On a computer, sign in to GitHub and create a new repository named `printquote`.
2. Upload all files in this folder to the repository's root (index.html, manifest.webmanifest, sw.js, icon-192.png, icon-512.png).
3. In the repository, open Settings > Pages.
4. Under Build and deployment, choose Deploy from a branch, select `main` and `/ (root)`, then Save.
5. Wait for GitHub Pages to publish the site. Open the published HTTPS address in Safari on your iPhone.
6. Tap the Share button in Safari, choose Add to Home Screen, edit the name to PrintQuote if desired, and tap Add.
7. Launch PrintQuote from your Home Screen. Open it once while online so it can cache the app for offline use.

## Important
- Quotes and settings are stored locally in the browser on this iPhone. They are not synced to iCloud or another device.
- Export your saved quotes regularly using Settings > Export saved quotes.
- The app is a quote-management aid, not accounting software. Check actual material, delivery, tax and marketplace fees before sending a final customer quote.
