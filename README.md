# AR Sunglasses Filter (QR → Camera → Face Filter)

A single-file web app that opens the front camera and overlays a sunglasses filter using MediaPipe Face Landmarker.

## Quick Start (GitHub Pages)
1. Create a **public** repository named `AR_Sunglasses_Filter` (any name is fine).
2. Upload the contents of this ZIP (or drag-drop in GitHub web UI).
3. Enable **Settings → Pages → Deploy from branch → `main` / `/ (root)`**.
4. Visit your GitHub Pages URL (https://<your-username>.github.io/<repo>/).

## Files
- `index.html` — The entire app; references MediaPipe via CDN.
- `.nojekyll` — Ensures GitHub Pages serves files without Jekyll processing.
- `LICENSE` — MIT license.

## Notes
- Mobile browsers may require a tap to start camera. Press **Start Camera** when prompted.
- Works on Android Chrome and iOS Safari (front camera by default). Use **Flip Camera** to switch.
- For best results, serve over **HTTPS** (GitHub Pages already is).

© 2025
