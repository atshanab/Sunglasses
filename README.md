# Sunglasses AR (Debug Build)

Use this build to diagnose tracking issues.

**What’s new**
- Uses `window.vision` namespace (correct for the CDN bundle).
- On-screen error box for camera/model/detect errors.
- **Debug landmarks** toggle draws *all* face points — if you don’t see green dots, tracking isn’t running.
- Separate mirroring toggles for front vs. rear cameras.

## Checklist if you see no green dots
1. Page must be served over **HTTPS** (GitHub Pages is fine).
2. Allow **camera permissions** when prompted.
3. Ensure **good lighting** and keep your entire face visible.
4. Try **front camera** first, then tap **Flip Camera**.
5. If your network blocks CDNs, allow `cdn.jsdelivr.net`.
6. Watch the **status**: 
   - "model ready" means the model loaded; 
   - "searching for face…" means it’s running but not finding a face.

## Deploy on GitHub Pages
- Upload these files to your repo root (e.g., `atshanab/Sunglasses`).
- GitHub → **Settings → Pages** → Build and deployment → Source: your default branch, **/(root)**.
- Open: `https://atshanab.github.io/Sunglasses/index.html`

© 2025 • MIT
