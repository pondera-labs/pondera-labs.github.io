# Pondera Website

Static GitHub Pages site for Pondera.

The site is intentionally simple:

- `index.html` contains the current one-page marketing/architecture draft.
- `.github/workflows/pages.yml` deploys the repository root to GitHub Pages.
- There is no build step yet.

Local preview:

```bash
python -m http.server 8080
```

Then open `http://localhost:8080`.
