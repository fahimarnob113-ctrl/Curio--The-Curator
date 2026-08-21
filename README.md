# CURIO — The Curator

An offline-first, high-capacity visual catalog, asset organizer, and curation dashboard designed for game developers, digital artists, researchers, and creators.

![CURIO Dashboard](Screenshots/curio-dashboard.png)

[![HTML5 Single File](https://img.shields.io/badge/Architecture-Single--File%20HTML-E34F26?style=flat-square&logo=html5&logoColor=white)](index.html)
[![Storage Engine](https://img.shields.io/badge/Storage-IndexedDB%20(Gigabyte%20Scale)-06B6D4?style=flat-square)](index.html)
[![Offline Ready](https://img.shields.io/badge/Offline-100%25%20Local-10B981?style=flat-square)](index.html)
[![License](https://img.shields.io/badge/License-MIT-blue?style=flat-square)](LICENSE)

---

## 🌟 What is CURIO?

**CURIO** is a lightweight, zero-dependency curation workbench that lives in a single standalone HTML file. It allows you to collect, review, tag, rate, and organize software tools, digital assets, documentation, shaders, audio packs, and creative workflows with zero server setup.

Unlike traditional cloud bookmarkers or notes apps, CURIO runs completely on your local machine, persists data in high-capacity **IndexedDB**, and packages backups into clean **`.zip` archives** containing both your structured JSON metadata and actual image files.

---

## 🎯 Practical Use-Cases

### 🎮 1. Game Development & Tech Art Hub
- **Engines & Frameworks**: Track engine versions (Godot, Unreal, Unity, Bevy, Raylib) with feature notes and license types.
- **Shaders & VFX**: Collect GLSL/HLSL raymarching algorithms, distance functions, compute shader references, and procedural textures.
- **Audio & OSTs**: Organize retro synthwave tracks, Foley sound packs, and audio middleware tools.
- **Technical Reference**: Store game programming patterns, math cheatsheets, and architecture diagrams.

### 🎨 2. Digital Art & Illustration Suite
- **Painting & Inking**: Compare specialized brush engines (Krita, Clip Studio Paint, Rebelle, PaintTool SAI).
- **Vector & UI Design**: Organize hybrid vector/raster suites (Affinity Designer, Inkscape, Boxy SVG, CorelDRAW).
- **Pixel Art & Spriting**: Manage sprite animation tools (Aseprite, GraphicsGale, Pixelorama, Piskel).

### 📸 3. Photography & RAW Processing Stash
- **RAW Developers**: Catalog Lightroom alternatives (Darktable, RawTherapee, DxO PhotoLab, Capture One).
- **AI Enhancement**: Track neural upscalers (Topaz Photo AI, Gigapixel) and specialized plugins (Nik Collection, HDR tools).
- **High-Speed Culling**: Compare fast asset managers and metadata viewers (digiKam, Photo Mechanic, FastStone, IrfanView).

### 📚 4. Book Publishing & Typography Desk
- **Desktop Publishing**: Track layout software (Adobe InDesign, Affinity Publisher 2, Scribus, QuarkXPress).
- **Print-on-Demand**: Organize self-publishing toolkits (Blurb BookWright, LibreOffice Draw, brand-kit platforms).

### 🛠️ 5. Personal Toolkit & Knowledge Vault
- Create independent catalogs for bookmarks, self-hosted Docker apps, open-source utilities, and hardware schematics.

---

## ⚡ Core Features

- **🗂️ Multi-Catalog Switching**: Switch instantly between independent catalogs (*Creative Tools*, *Game Dev*, *Combined Library*) with separate drawers, tags, and search scopes. Create, rename, or delete catalogs at will.
- **💾 Gigabyte-Scale Local Storage (IndexedDB)**: Bypasses restrictive 5MB browser `localStorage` limits with native **IndexedDB (`CyberDB`)**. Upload high-resolution screenshot galleries and logos stored permanently on your disk.
- **📦 True ZIP Archive Backup & Universal Restore**:
  - **Export (`.zip`)**: Bundles metadata (`catalogs.json`) and extracts all uploaded image Blobs into real `.jpg`/`.png` files in an `/images/` subfolder.
  - **Universal Import**: Drop either a `.zip` archive or `.json` file to restore your entire database seamlessly.
- **🎛️ 4 Switchable View Modes**:
  - **Grid View**: Visual card matrix with tags, rating stars, and instant edit actions.
  - **Detailed View**: Expanded two-column layout showing multi-photo galleries and comprehensive notes.
  - **List View**: Dense tabular view for quick scanning and metadata comparison.
  - **Kanban Board**: Workflow pipeline (*To Explore*, *In Progress*, *Curated*, *Archived*) with independent column scrolling.

| Grid Gallery | Kanban Workflow |
| :---: | :---: |
| ![Grid View](Screenshots/curio-dashboard.png) | ![Kanban View](Screenshots/Kanban%20View.png) |

| Detailed List | Edit & Curate Dialog |
| :---: | :---: |
| ![List View](Screenshots/List-view.png) | ![Edit View](Screenshots/Edit-view.png) |

- **🏷️ Scoped Tag Cloud with Live Search**:
  - Contextual tag strip that adapts to the currently active drawer.
  - Instant tag search box (`Filter...`) with expand/collapse view and item frequency badges.
- **⌨️ Speed & Accessibility**: Full keyboard navigation (`/` to focus search, `N` for new item, `Esc` to dismiss modals).

---

## 🚀 Getting Started

1. **Clone the Repository**:
   `ash
   git clone https://github.com/fahimarnob113-ctrl/Curio--The-Curator.git
   `
2. **Launch**:
   Double-click index.html in any modern web browser (Chrome, Edge, Firefox, Brave, Safari, Opera).
3. **No Setup Required**: No Node.js, Python server, or build step needed.

---

## 🗃️ Included Seed Data (63 Curated Tools)

The default build includes a pre-loaded library of **63 creative tools** across **11 categories**:

| Category / Drawer | Item Count | Featured Software |
| :--- | :---: | :--- |
| **Photo Editing & RAW** | 19 | Darktable, RawTherapee, DxO PhotoLab, Luminar Neo, ON1 Photo RAW, Photoshop, Photopea, GIMP, Affinity Photo 2 |
| **Digital Art & Illustration** | 9 | Krita, Clip Studio Paint, Corel Painter, Rebelle 3, PaintTool SAI, Autodesk SketchBook, MediBang Paint |
| **Vector & Graphic Design** | 6 | Inkscape, Affinity Designer 2, CorelDRAW, Gravit Designer, Boxy SVG, Xara Designer Pro |
| **Publishing & Layout** | 8 | Adobe InDesign, QuarkXPress, Affinity Publisher 2, Canva, LibreOffice Draw, Scribus, Blurb BookWright |
| **Photo Management & Viewers** | 7 | digiKam, XnView MP, FastStone Image Viewer, IrfanView, Adobe Bridge, Photo Mechanic |
| **Pixel Art & Animation** | 4 | Aseprite, GraphicsGale, Piskel, Pixelorama |
| **HDR, Panorama & AI Tools** | 6 | Topaz Photo AI, Topaz Gigapixel AI, PTGui, Hugin, Nik Collection (DxO) |
| **Game Design & Tech Art** | 4 | Godot Engine 4.3, Raymarching SDF Guide, Cyberpunk Synthwave OST, Game Programming Patterns |

---

## ⌨️ Keyboard Shortcuts

| Shortcut | Description |
| :---: | :--- |
| / | Focus global search box |
| N / Ctrl+N | Open New Item curation modal |
| Escape | Dismiss active modal, drawer settings, or lightbox |
| ◀ / ▶ | Navigate lightbox gallery images |

---

## 📄 License

Distributed under the **MIT License**. Free for personal and commercial use.
