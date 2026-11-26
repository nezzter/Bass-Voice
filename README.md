Static web app (HTML5 + CSS3 + Vanilla JS + Web Audio API): records voice from the microphone, deepens it toward bass, and saves the result as .mp3 (with .wav fallback export).

The entire app is a single index.html file in the root directory. The only external dependency is the lamejs MP3 encoder loaded via CDN (jsDelivr, with cdnjs and unpkg fallbacks).

Local Setup
Simplest way: open index.html in a browser.

If the browser blocks microphone access on file://, start a local server: python -m http.server 8000 and open http://localhost:8000.

Publish to GitHub Pages (Free, 24/7)
Create a repository on github.com (e.g., bas-glos, public).

Upload index.html and README.md to the root directory (Add file → Upload files → Commit).

Go to Settings → Pages → Source: Deploy from a branch → Branch: main, folder / (root) → Save.

After 1–2 minutes, the site is live at `