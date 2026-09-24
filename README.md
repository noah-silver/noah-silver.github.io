# noah-silver-site

Personal website for Noah Silver, built with [Quarto](https://quarto.org).

## Edit and preview

```bash
quarto preview
```

Pages are `index.qmd`, `about.qmd`, `writing.qmd`, and `projects.qmd`. Styles live in `styles/theme.scss`. Papers are in `papers/`.

## Publish

Pushing to `main` runs `.github/workflows/publish.yml`, which renders the site and deploys it to GitHub Pages.
