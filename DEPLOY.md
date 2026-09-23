# GitHub Pages deployment

Live URL: https://alinobahari7661.github.io/portfolio/

Repository name: `portfolio` (project site, not `username.github.io`).

## Enable GitHub Pages

Repository → Settings → Pages

- Source: Deploy from a branch
- Branch: `main`
- Folder: `/ (root)`

GitHub publishes `index.html` at `/portfolio/`.

## Files that ship

- `index.html` — portfolio homepage
- `styles.css` — visual system and responsive layout
- `cv.html` — web CV with browser print-to-PDF support
- `README.md` — repository overview
- `assets/profile.jpg` — hero portrait
- `assets/og-image.jpg` — Open Graph image
- `assets/favicon.svg` — AN mark
- `assets/ali-nobahari-cv.pdf` — downloadable CV

Sports-team photos and original uncompressed files stay local and are gitignored.

## Rename note

If the previous repo was `Ali-Nobahari`, rename it to `portfolio` with `gh repo rename portfolio`. GitHub keeps a redirect from the old Pages path.
