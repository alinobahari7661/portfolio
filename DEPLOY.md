# GitHub Pages deployment

## 1. Create the repository

For the main personal site, create:

`YOUR_GITHUB_USERNAME.github.io`

Upload the contents of this folder to the repository root.

## 2. Replace placeholders

Before publishing:

- Replace `https://github.com/` with your actual GitHub profile URL.
- Replace `https://www.linkedin.com/` with your actual LinkedIn profile URL.
- If desired, replace the email address with the public email you want to expose.

## 3. Enable GitHub Pages

Repository → Settings → Pages

- Source: Deploy from a branch
- Branch: `main`
- Folder: `/ (root)`

GitHub will publish `index.html`.

## 4. Optional custom domain

A custom domain can be added later from the Pages settings.

## Files

- `index.html` — portfolio homepage
- `styles.css` — visual system and responsive layout
- `cv.html` — web CV with browser print-to-PDF support
- `README.md` — GitHub profile README content
- `assets/profile.png` — supplied professional portrait
