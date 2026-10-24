# ArchCAD M3 - Progressive Web Application (PWA)

Complete, ready-to-deploy architectural CAD and 3D massing web application optimized for iPad Air M3, Apple Pencil, and Safari.

## Package Contents
- `index.html`: Complete dual-engine application (2D drafting canvas + Three.js 3D massing viewport + DXF parser/exporter).
- `manifest.json`: Web App Manifest with relative paths (`./`) configured for GitHub Pages subfolder hosting.
- `sw.js`: Service Worker providing offline caching and PWA installation capability.
- `icon-192.png`: 192x192 high-resolution app icon.
- `icon-512.png`: 512x512 high-resolution app icon.

## How to Deploy to GitHub Pages in 2 Minutes
1. Unzip this package.
2. Initialize and push to your GitHub repo:
   ```bash
   git init
   git add .
   git commit -m "Deploy ArchCAD M3 PWA"
   git branch -M main
   git remote add origin https://github.com/<your-username>/<your-repo-name>.git
   git push -u origin main
   ```
3. In your GitHub repository:
   - Go to **Settings** > **Pages**.
   - Under **Build and deployment > Branch**, choose `main` and root `/`.
   - Click **Save**.
4. Open the deployed URL (`https://<your-username>.github.io/<your-repo-name>/`) on your iPad Air in Safari.
5. Tap **Share** > **Add to Home Screen** to install as a full-screen native iPad application.