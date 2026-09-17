# PDF Merger

A single self-contained web app for merging PDFs, compressing PDFs, and compressing JPEG/PNG images — entirely in the browser. No backend, no build step, no npm install.

## How to run

**Option 1 — just open it**
Double-click `index.html`. It opens in your default browser and works immediately.

**Option 2 — VS Code + Live Server**
1. Open this folder in VS Code.
2. Install the "Live Server" extension (by Ritwick Dey).
3. Right-click `index.html` → "Open with Live Server".

**Option 3 — any static server**
From this folder, run one of:
```
python3 -m http.server 8000
```
or
```
npx serve .
```
Then visit the printed local URL in your browser.

## Notes

- Requires an internet connection on first load (it pulls pdf-lib, pdf.js, and JSZip from a CDN). Everything after that — merging, compressing, previewing — runs locally in your browser; no files are ever uploaded anywhere.
- The ad slot in the footer is a placeholder. AdMob (the ad unit IDs from the Google AdMob app) only works inside native mobile apps, not websites — for ads on this site you'll need a Google AdSense account and its snippet instead.
