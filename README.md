# MarkChrome GitHub Pages Launch Package

This package contains a complete static website, browser Markdown editor, logo files, and brochure assets for:

https://aatayyab.github.io/MarkChrome

## Files included

- `index.html` — public marketing website
- `app.html` — hosted MarkChrome editor
- `help.html` — simple user help page
- `brochure.html` — brochure viewer page
- `assets/markchrome-logo.svg` — main logo
- `assets/markchrome-logo.png` — main logo PNG
- `assets/markchrome-icon.svg` — icon / favicon source
- `assets/markchrome-icon.png` — icon PNG
- `assets/markchrome-brochure.png` — downloadable brochure image
- `assets/markchrome-brochure.svg` — editable vector brochure
- `downloads/MarkChrome.html` — standalone downloadable editor app
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
```

### 3. Enable GitHub Pages

1. Go to **Settings** inside the repository.
2. Click **Pages** in the left menu.
3. Under **Build and deployment**, choose:
   - Source: **Deploy from a branch**
   - Branch: **main**
   - Folder: **/ root**
4. Click **Save**.

### 4. Wait for publishing

GitHub usually takes 1–5 minutes to publish the site.

Your final website address will be:

```text
https://aatayyab.github.io/MarkChrome/
```

### 5. Test everything

Open the website and test:

- **Launch Editor** opens `app.html`
- **Download standalone HTML** downloads `downloads/MarkChrome.html`
- **Brochure** opens `brochure.html`
- Contact links open email/phone actions
- Logo and brochure images appear correctly

## Updating contact details

Contact information is currently set to:

```text
Amir Ali Tayyab
Email: aatayyab@yahoo.com
Phone: +1-407-434-1786
```

To change it later, edit the contact section in `index.html` and the footer text in `assets/markchrome-brochure.svg` if you want to regenerate the brochure image.

## Important note

MarkChrome is a static HTML/CSS/JavaScript browser app. It is not affiliated with Google Chrome or Google.
