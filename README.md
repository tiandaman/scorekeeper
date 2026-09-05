# Card Scorekeeper (web)

Upload the **contents of this folder** to the root of a public GitHub repo, then
Settings → Pages → Deploy from a branch → `main` / `/ (root)` → Save.

Your URL: `https://<username>.github.io/<repo>/`

Files:
- `index.html` — the whole app, self-contained
- `manifest.webmanifest`, `icon-180.png`, `icon-512.png` — home-screen install
- `six-seven.gif` — the 67 easter egg (must sit next to index.html)
- `sw.js` — offline cache
- `.nojekyll` — tells Pages to serve the files as-is

To update later: re-upload `index.html` and bump `scorekeeper-web-v1` in `sw.js`.
