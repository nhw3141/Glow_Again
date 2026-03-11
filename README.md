# Glow_Again
# Soft Support Scan

A cute pastel single page website that shows a “portrait scan” loading effect and then releases floating comfort messages.

Important notes:
- This is a visual comfort page, not real face analysis.
- The camera preview stays on-device. Nothing is uploaded or saved.

## Run locally
Just open `index.html` in your browser.

If your browser blocks camera on file URLs, use a simple local server:
- Python: `python3 -m http.server 8080`
Then open `http://localhost:8080`

## Publish on GitHub Pages
1. Create a new repository (public is easiest).
2. Upload `index.html` and `README.md` to the repo root.
3. Go to Settings → Pages.
4. Under “Build and deployment”, choose:
   - Source: Deploy from a branch
   - Branch: `main` and folder `/ (root)`
5. Save. Your site will appear at:
   `https://YOUR_USERNAME.github.io/YOUR_REPO_NAME/`
