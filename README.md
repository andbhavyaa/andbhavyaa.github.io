# Bhavyaa's Portfolio

Plain HTML/CSS/JS. No build step, no dependencies.

## Run it
1. Unzip the folder.
2. Double-click `index.html` to open it in your browser.
   (Or, for a local server: `python3 -m http.server 8000` in this folder, then visit http://localhost:8000)

Internet is needed once for the Google Fonts (Playfair Display, Caveat, Inter).

## Modes
- Toggle "minimal / maximal" at the top right. The choice is remembered.
- Direct links: `index.html?mode=minimal` or `?mode=maximal`

## Edit
- Text lives in `index.html` (maximal section, then minimal section).
- Photos are in `assets/`. Replace with the same file names.
- Colors are CSS variables at the top of the `<style>` block.
- Skeldir/RailMadad cards link to your GitHub profile; swap in the repo URLs.

## Deploy free
Drag this folder onto Netlify Drop, or push to GitHub and enable GitHub Pages.
