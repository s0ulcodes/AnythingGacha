# AnythingGacha Studio

**Collect anything.** A photocard gacha game and binder web app where you can pull, collect, decorate, and organize photocards from any fandom.

![License](https://img.shields.io/badge/license-MIT-blue)
![Platform](https://img.shields.io/badge/platform-web%20%7C%20windows-lightgrey)
![Status](https://img.shields.io/badge/status-active-brightgreen)

---

## Features

- **Gacha Pull** - Pull random photocards from Pinterest using a custom backend
- **Binder** - Organize your collection with sort, filter, and drag-and-drop reordering
- **Card Studio** - Upload your own images to create custom photocards
- **Decorator** - Add frames, stickers, and edit card properties
- **Saved Packs** - Save and reuse gacha search configurations
- **Persistent Storage** - Data saved locally in your browser (IndexedDB)
- **PWA Ready** - Install on mobile devices as a progressive web app
- **Windows App** - Downloadable .exe for Windows users

---

## Live Demo

**[Play on Cloudflare Pages](https://anythinggacha.pages.dev)**

---

## Download

| Platform | Download |
|----------|----------|
| Windows | [AnythingGacha.exe](https://anythinggacha.pages.dev/AnythingGacha.exe) |
| Web | [Play in Browser](https://anythinggacha.pages.dev) |

> **Mac & Linux users**: Please use the web version. The downloadable app is Windows-only (built via GitHub Actions).

---

## Tech Stack

| Component | Technology |
|-----------|------------|
| Frontend | HTML, Tailwind CSS, JavaScript |
| Backend API | Python (Flask), Gradio |
| Image Search | Pinterest (via `pinterest-dl`) |
| Storage | IndexedDB (browser) |
| Hosting | Cloudflare Pages (frontend), Hugging Face Spaces (backend) |

---

## Building the Windows App

```bash
# Install dependencies
npm install

# Build for Windows
npm run build:win

# Output: dist/AnythingGacha.exe