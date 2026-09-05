# VOID Gaming Lounge — Mobile Menu

Static site. No build step, no dependencies.

## Deploy to GitHub Pages

1. Upload the **contents of this folder** to the root of `VoidGamingEg/Menu` on `main`
   — keep the structure: `index.html`, `support.js`, `assets/`.
2. Settings → Pages → Deploy from a branch → `main` / `/ (root)` → Save.
3. Live in ~1 minute at https://voidgamingeg.github.io/Menu/
4. Point the in-lounge QR code at that URL.

Do not nest the files in a subfolder — Pages serves `index.html` from the repo root.

## Weight

Photos are mobile-optimised (760px wide, ~40-70KB each) and load only as each
category comes into view, so the first screen paints immediately.

## Editing

Prices and items live in `index.html`. Re-export from the design project rather than
hand-editing if you can — that keeps the A4 print menu in sync.
