# Skater Scene — Three.js (Mobile-friendly)

This repo contains an iPhone-friendly Three.js scene that recreates a silhouetted skateboarder against a sunset/puddle backdrop.

## Files
- `index.html` — the full scene (touch controls, reflective puddle with animated ripples, lamps, rail, optional photo backplate).
- `assets/reference.png` — the provided reference photo used as a background backplate (toggle with the **Backplate** button).

## How to run
### iPhone / iPad
1. Download the ZIP from GitHub (or the link provided), unzip in Files.
2. Tap `index.html` → **Open in Safari**.

### Mac / Windows
- Double-click `index.html` to open in Chrome/Safari/Edge.

### Optional: Serve locally
You can also serve it with a tiny local server:
```bash
# Python 3
python3 -m http.server 8000
# Visit http://localhost:8000
```

## Deploy on GitHub Pages
1. Create a new repo and push these files.
2. In **Settings → Pages**, set Source: **Deploy from a branch**, Branch: `main` → `/ (root)`.
3. Open the given URL to view your scene online.

## Notes
- Uses CDN modules for Three.js (no build step).
- Tap the scene to **pause/play** animation. Buttons in the top-right toggle **Ripples** and **Backplate**.
- If you want a **rigged human** instead of a silhouette, drop a `.glb` into `assets/` and I’ll wire it up.
