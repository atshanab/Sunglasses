# Sunglasses AR (Face Tracked) — Fix Build

This version ensures the sunglasses **always draw**:
- Waits for the embedded sunglasses image to load; uses a **fallback outline** until ready.
- Adds **Show landmarks** to verify tracking visually.
- Mirrors only for the **front camera** by default (configurable for rear).

## Deploy on GitHub Pages
1. Upload all files to your repo root (e.g., `atshanab/Sunglasses`).
2. GitHub → **Settings → Pages → Build and deployment** → Source: your default branch, **/(root)**.
3. Open: `https://atshanab.github.io/Sunglasses/index.html`

A `qr.png` is included that points there.

© 2025 • MIT
