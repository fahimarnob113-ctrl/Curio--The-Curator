# CURIO — The Curator

An offline-first, high-capacity, cyberpunk-themed visual catalog and curation dashboard for organizing creative software, game engines, shaders, audio, reference material, and digital assets.

![HTML5](https://img.shields.io/badge/HTML5-Single--File-E34F26?style=flat&logo=html5&logoColor=white)
![Offline](https://img.shields.io/badge/Offline--First-IndexedDB-06B6D4?style=flat)
![Status](https://img.shields.io/badge/Status-Active-10B981?style=flat)

---

## ⚡ Features

- **Multi-Catalog Switching**: Switch seamlessly between distinct catalogs (e.g., *Creative Software & Design Tools*, *Game Dev & Tech Art*, *General Archive*), or create, rename, and delete custom catalogs.
- **Gigabyte-Scale Offline Storage (IndexedDB)**: Replaces standard 5MB browser limits with native **IndexedDB (CyberDB)**, enabling high-resolution image uploads, logos, and screenshot galleries stored locally on your device.
- **ZIP Archive Export & Universal Import**:
  - **Export (.zip)**: Bundles catalog metadata (catalogs.json) and all stored binary image assets into a self-contained .zip archive.
  - **Import**: Supports instant restoration from .zip archives and legacy .json backup files.
- **4 Reactive View Modes**:
  - **Grid View**: Card-based visual gallery with tags, rating stars, and photo preview.
  - **Detailed View**: Expanded two-column view with full notes and multi-image photo gallery rails.
  - **List View**: Compact tabular view for rapid scanning and metadata filtering.
  - **Kanban Board**: Workflow columns (*To Explore*, *In Progress*, *Curated*, *Archived*) with independent column scrolling.
- **Smart Filtering & Scoped Tag Strip**:
  - Context-aware tag strip scoped to the active drawer.
  - Instant tag search box (Filter...) and expandable multi-row cloud.
  - Multi-select status pills and star rating thresholds (1★–5★).
  - Search box with instant keyboard shortcut (/).
- **Zero Build Tools / Single-File Runtime**: Run directly by double-clicking index.html in any modern web browser.

---

## 🚀 Quick Start

1. Clone or download this repository:
   `ash
   git clone https://github.com/fahimarnob113-ctrl/Curio--The-Curator.git
   `
2. Open index.html directly in your browser (Chrome, Edge, Firefox, Brave, Safari).
3. Start curating!

---

## 🗂️ Included Seed Catalogs

- **Creative Software & Design Tools (59 Items)**:
  - *Photo Editing & RAW* (Darktable, RawTherapee, DxO PhotoLab, Capture One, Photoshop, Photopea, Affinity Photo, etc.)
  - *Digital Art & Illustration* (Krita, Clip Studio Paint, Corel Painter, Rebelle, PaintTool SAI, etc.)
  - *Vector & Graphic Design* (Inkscape, Affinity Designer, CorelDRAW, Boxy SVG, etc.)
  - *Publishing & Layout* (InDesign, Affinity Publisher, Scribus, Canva, etc.)
  - *Photo Management & Viewers* (digiKam, XnView MP, FastStone, IrfanView, Photo Mechanic, etc.)
  - *Pixel Art & Animation* (Aseprite, GraphicsGale, Piskel, Pixelorama)
  - *HDR, Panorama & AI Tools* (Topaz Photo AI, Gigapixel, PTGui, Hugin, Nik Collection)
- **Game Dev & Tech Art (4 Items)**:
  - Godot Engine 4.3, Raymarching Signed Distance Fields, Cyberpunk Synthwave OST, Game Programming Patterns.

---

## ⌨️ Keyboard Shortcuts

| Key | Action |
| :--- | :--- |
| / | Focus search bar |
| N / Ctrl+N | Open New Item modal |
| Escape | Close active modal / lightbox |
| ◀ / ▶ | Navigate lightbox gallery images |

---

## 🛡️ License

MIT License. Designed for personal and professional curation.
