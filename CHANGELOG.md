# Changelog

All notable changes to **MarkChrome** will be documented in this file.

---

## [3.1.0] — 2026-11-13
### 🚀 Major New Features & Enhancements
- **Integrated Workspace Architecture:** Updated `app.html` with a robust workspace UI structure and streamlined file export helpers for seamless local Markdown workflows.
- **Polished Dark-Mode Aesthetics:** Enhanced CSS variables and layout padding for a cleaner, high-performance visual coding environment.

---

## [3.0.0] — 2026-11
### 🚀 Major New Features & Enhancements
- **Default Visual WYSIWYG Editor (Mode 2):** Introduced direct document editing on the rendered preview pane, allowing users to write and format content like a standard word processor with instant background Markdown synchronization.
- **Seamless Mode Switcher:** Added a top-bar mode toggle enabling instantaneous switching between the Visual Editor (Mode 2) and the classic dual-pane Markdown workspace (Mode 1).
- **Advanced Document Formatting:** Enhanced parsing and support for GitHub Flavored Markdown (GFM) tables, task checklists (`- [x]`), custom highlights, strikethrough styling, and YAML front matter blocks.
- **Upgraded Rich-Text & Media Export:** Improved clipboard copy functionality that translates complex elements—including rendered Mermaid.js diagrams and KaTeX mathematical formulas—directly into rich-text destinations like email clients or word processors.
- **Optimized Interface & Localization:** Refined the user interface styling, landing pages, and documentation to support dual-mode layouts while preserving English, Spanish, and Urdu (RTL) localization and multi-theme engines (Dark, Light, High Contrast).

---

## [2.0.0] — 2026-05
### 🚀 Major New Features & Enhancements
- **Live Split-Pane Workspace:** Introduced synchronized split-pane scrolling for instant side-by-side Markdown editing and rendering.
- **Diagrams & Math Integration:** Added native browser rendering support for Mermaid.js flowcharts and KaTeX mathematical typesetting (`$E=mc^2$).
- **Outline Sidebar & Navigation:** Implemented a clickable table of contents sidebar mapping every document heading for instant navigation.
- **Find & Replace Engine:** Built-in Ctrl+F / Ctrl+H search and replace bar directly inside the editor interface.
- **Zen Mode & Validator:** Added distraction-free full-screen writing mode and a one-click Markdown validator to check for unclosed code blocks and broken tables.
- **Multi-Language & Multi-Theme Support:** Added language switcher for English, Español, and Urdu (with full right-to-left layout) alongside Dark, Light, and High-Contrast themes.
- **Auto-Recovery:** Enabled local browser caching every 3 seconds to protect against accidental tab closures.

---

## [1.0.0] — 2026-01
### 🌱 Initial Release
- **Core Markdown Editor:** Initial release of MarkChrome as a lightweight, browser-based Markdown editor requiring no installation, database, or server account.
- **Local File Operations:** Basic support for opening, editing, and saving local `.md` and `.txt` files directly through the browser.
- **Basic Export Options:** Basic HTML export and raw text copy utilities.
