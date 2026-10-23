# MarkChrome 2.0 — Universal Markdown Workspace

A free, browser-based Markdown editor with live preview. No account, no server, no install. Your files stay on your device.

- 🌐 **Website & editor:** https://aatayyab.github.io/MarkChrome/
- ⬇️ **Downloads:** https://github.com/aatayyab/MarkChrome/releases/latest
- 📖 **Help guide:** https://aatayyab.github.io/MarkChrome/help.html
- 📄 **Brochure:** https://aatayyab.github.io/MarkChrome/brochure.html

## What's new in Release 2.0

- **Mermaid diagrams** — flowcharts and sequence diagrams from plain text
- **KaTeX math** — inline `$E=mc^2$` and block `$$ … $$` formulas
- **Syntax highlighting** with a one-click Copy button on code blocks
- **Outline sidebar** — clickable table of contents
- **Find & Replace** — Find Next, Replace, Replace All (Ctrl+F / Ctrl+H)
- **Zen mode** — distraction-free writing (Esc to exit, Exit button on phones)
- **Markdown validator** — finds unclosed code blocks, stray `*`, broken table rows
- **Copy Rich Text** — paste formatted content (diagrams included) into Word, Docs or email
- **YAML front matter** display (Hugo, Jekyll, MkDocs)
- **Drag & drop** `.md` / `.txt` files and **paste screenshots** directly
- **3 interface languages** — English, Español, اردو (right-to-left)
- **3 themes** — including a high-contrast mode
- **Shortcodes** — type `//date` or `//table` then Space
- Auto-recovery, HTML & PDF export, Save / Save As, cross-browser file support

> **Note:** In 2.0 the right-hand preview is read-only; all typing happens in the left Markdown pane.
> The app loads its helper libraries (Mermaid, KaTeX, Prism, marked, DOMPurify, html2pdf) from public CDNs, so an internet connection is needed when opening it.

See [CHANGELOG.md](CHANGELOG.md) for the full history.

## Repository structure

```text
MarkChrome/
├── index.html              Public marketing website
├── app.html                Hosted MarkChrome 2.0 editor
├── help.html               User guide
├── brochure.html           Brochure viewer page
├── README.md
├── CHANGELOG.md
├── RELEASE_NOTES_v2.0.md   Text to paste into the GitHub Release
├── .nojekyll               Keeps GitHub Pages simple
├── assets/
│   ├── markchrome-logo.svg / .png
│   ├── markchrome-icon.svg / .png
│   ├── favicon.svg
│   ├── markchrome-brochure.svg / .png
│   └── markchrome-og.svg / .png      (social share image)
└── downloads/
    ├── MarkChrome.html               Standalone downloadable app
    └── MarkChrome-Brochure.png
```

## Run it

- **Online:** open https://aatayyab.github.io/MarkChrome/app.html
- **Offline-ish:** download `downloads/MarkChrome.html` and double-click it (needs internet for the helper libraries).
- **Locally from source:** download this repo and open `index.html`.

## Contact

Amir Ali Tayyab — aatayyab@yahoo.com — +1-407-434-1786
