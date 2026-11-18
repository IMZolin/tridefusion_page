# TriDeFusion-v2 project page

Static academic project page for the TriDeFusion-v2 paper.

## Run locally

From this directory, run:

```bash
python3 -m http.server 8000
```

Open <http://localhost:8000> in a browser.

## Deploy

The GitHub Actions workflow in `.github/workflows/pages.yml` publishes the repository root to GitHub Pages on pushes to `main` or `master`. In the repository settings, set **Pages → Build and deployment → Source** to **GitHub Actions**.
