# IIM Mumbai Mess Menu – PWA

A tiny installable web app that shows the current or next mess meal based on day/time (IST).  
Host it for free on **GitHub Pages**.

## Files
- `index.html` – single-page app
- `menu.json` – **edit this** to change menu or timings
- `manifest.webmanifest` – app metadata for Add-to-Home-Screen
- `service-worker.js` – offline caching
- `assets/icon-192.png`, `assets/icon-512.png` – app icons

## How to deploy on GitHub Pages
1. Create a new public repo, e.g., `mess-menu`.
2. Upload all files from this folder to the repo root.
3. In repo Settings → Pages → **Deploy from Branch**, choose `main` and `/ (root)`.  
   Your app will be live at `https://<your-username>.github.io/mess-menu/`.

## How to update the menu
- Open `menu.json` on GitHub and click **Edit**. Commit changes.
- Refresh the app. It will pull the latest JSON and also work offline.

## Add to Home Screen (Android/iOS)
- Open the URL in Chrome (Android) or Safari (iOS).
- Use **Add to Home screen** / **Add to Home Screen** from the browser menu.  
- Or tap the **Install** button inside the app when it appears (Chrome).

## Note
- Time windows are set to IST in `menu.json`. The app uses the device local time.
- If you want to force IST even when travelling, we can add an option later.

© 2025
