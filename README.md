# soosub.github.io

Personal academic website of Joost Bus, built with the [al-folio](https://github.com/alshedivat/al-folio) Jekyll theme and deployed to GitHub Pages via GitHub Actions.

## Editing

- **Bio / homepage:** `_pages/about.md`
- **Publications:** `_bibliography/papers.bib`
- **CV:** `_data/cv.yml`
- **Social links:** `_data/socials.yml`
- **Site config:** `_config.yml`
- **Profile photo:** `assets/img/prof_pic.jpg`

## Local preview (optional)

Requires Ruby + Bundler:

```bash
bundle install
bundle exec jekyll serve
```

## Deployment

Pushing to `main` triggers `.github/workflows/deploy.yml`, which builds the site and
publishes it to the `gh-pages` branch. In **Settings → Pages**, set the source to
**Deploy from a branch → `gh-pages` / root**. The repository must be **public** for
GitHub Pages to serve it (on a free account).
