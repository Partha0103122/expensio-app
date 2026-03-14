# Expensio 💰

A personal expense tracker PWA with Google Sheets sync and live EUR ↔ INR conversion.

## Features
- Log expenses with store, category, quantity, and notes
- Enter amounts in EUR or INR — auto-converts using live rate
- Google Sheets auto-sync (one row per expense)
- Loan EMI tracker — know exactly how many euros to transfer monthly
- Works offline — syncs when back online
- Installable as a PWA on Android, iPhone, and desktop

## Deploy to GitHub Pages

1. Upload all these files to your `Expensio` GitHub repository (maintain the folder structure)
2. Make sure GitHub Pages is enabled on the `main` branch (Settings → Pages)
3. Your app will be live at: `https://partha0103122.github.io/Expensio`

## Files
```
index.html      ← Main app
manifest.json   ← PWA manifest
sw.js           ← Service worker (offline support)
icons/
  icon-192.png  ← App icon
  icon-512.png  ← App icon (large)
```

## How to upload files to GitHub

### Option A — GitHub Web UI (easiest)
1. Go to your repo: https://github.com/partha0103122/Expensio
2. Click **"Add file" → "Upload files"**
3. Drag and drop all files (index.html, manifest.json, sw.js, and the icons folder)
4. Click **"Commit changes"**

### Option B — Git command line
```bash
git clone https://github.com/partha0103122/Expensio.git
cd Expensio
# Copy files here, then:
git add .
git commit -m "Add Expensio PWA"
git push
```

## Install as PWA
- **Android (Chrome):** Open the URL → tap the 3-dot menu → "Add to Home screen"
- **iPhone (Safari):** Open the URL → tap Share → "Add to Home Screen"
- **Desktop (Chrome):** Open the URL → click the install icon in the address bar
