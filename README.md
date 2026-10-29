# Prakhar Rastogi — Portfolio

Personal portfolio site. Plain HTML/CSS/JS, no build step, deployed to GitHub Pages.

## Structure

```
index.html        page content (edit this to update sections)
styles.css        styling, light/dark theme tokens
script.js         theme toggle + footer year
assets/           favicon and images
.github/workflows/pages.yml   deploys to GitHub Pages on push to main
```

## Run locally

```bash
python3 -m http.server 8000
```

Then open http://localhost:8000.

## Deploy

1. Push to a GitHub repo (name it `prakhar-iit.github.io` to serve at the root domain).
2. In the repo: **Settings → Pages → Source: GitHub Actions**.
3. Every push to `main` redeploys.
