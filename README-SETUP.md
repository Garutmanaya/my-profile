# Publishing the profile

## GitHub browser view
`README.md` renders directly in GitHub. It contains the complete CV.

## GitHub Pages
Enable **Settings → Pages → Deploy from a branch**, select `main` and `/ (root)`.
Jekyll renders `index.md` using the simple `_layouts/default.html` layout.

## Downloadable PDF
`assets/resume.pdf` is the matching downloadable PDF. The Pages toolbar links to it.

## Editing
Update `README.md`, then copy the body to `index.md` after its YAML front matter. Re-export `assets/resume.pdf` after substantive changes. The initial PDF is generated from the same Markdown text; automated PDF regeneration is not yet wired into GitHub Actions.

## Editorial review
See `REVIEW.md`. Current contact details and certain project specifics intentionally remain unverified.
