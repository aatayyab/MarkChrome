# MarkChrome GitHub Pages Launch Package

This package contains a complete static website, browser Markdown editor, logo files, and brochure assets for:

https://aatayyab.github.io/MarkChrome[cite: 5]

## Files included

- `index.html` — public marketing website[cite: 5]
- `app.html` — hosted MarkChrome editor (fully updated with local auto-recovery, cross-browser file support, HTML/PDF export, and theme toggle)
- `help.html` — simple user help page (or utilize the built-in app modal)
- `brochure.html` — brochure viewer page
- `assets/markchrome-logo.svg` — main logo
- `assets/markchrome-logo.png` — main logo PNG
- `assets/markchrome-icon.svg` — icon / favicon source
- `assets/markchrome-icon.png` — icon PNG
- `assets/markchrome-brochure.png` — downloadable brochure image
- `assets/markchrome-brochure.svg` — editable vector brochure
- `downloads/MarkChrome.html` — standalone downloadable editor app (updated with latest features)
- `downloads/MarkChrome-Brochure.png` — downloadable brochure copy
- `.nojekyll` — keeps GitHub Pages simple for static files

## Launch instructions for GitHub Pages

### 1. Create the GitHub repository

1. Sign in to GitHub.
2. Click **New repository**.
3. Repository name must be exactly: `MarkChrome`
4. Owner should be: `aatayyab`
5. Choose **Public**.
6. Click **Create repository**.

### 2. Upload the website files

1. Open the new `MarkChrome` repository.
2. Click **Add file** → **Upload files**.
3. Upload the contents of this folder, not the folder itself.
4. Make sure `index.html` is visible in the root of the repository.
5. Click **Commit changes**.

Correct structure:

```text
MarkChrome/
├── index.html
├── app.html
├── help.html
├── brochure.html
├── .nojekyll
├── assets/
│   ├── markchrome-logo.svg
│   ├── markchrome-logo.png
│   ├── markchrome-icon.svg
│   ├── markchrome-icon.png
│   ├── markchrome-brochure.png
│   └── markchrome-brochure.svg
└── downloads/
    ├── MarkChrome.html
    └── MarkChrome-Brochure.png
