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

## 🗃️ Included Pre-Loaded Catalogs (487 Items Across 6 Catalogs)

CURIO comes pre-loaded with curated reference libraries:

1. **🎨 Creative Software & Design Tools (59 Items / 7 Drawers)**
   - *Photo Editing & RAW, Digital Art & Illustration, Vector Design, Publishing, Asset Managers, Pixel Art, HDR & AI Plugins.*
2. **🎮 Games Master List (246 Items / 23 Eras & Platforms)**
   - *Arcade & Early Home, 8-bit, 16-bit, Early 3D / 5th Gen, 6th Gen, Game Boy Advance, 7th Gen, Nintendo DS, 8th Gen, Modern / 9th Gen, Indie Standouts, Mobile, J2ME / Feature Phone, E-Sports, RPGs, MMORPGs, PC Golden Age, Sports & Racing, Rhythm & VR, Dreamcast, Neo Geo, Sandbox / UGC, MAME Classics.*
3. **📱 Smartphones & Feature Phones: 2004–2024 (51 Items / 8 Eras)**
   - *Feature Phone Era, iPhone/Android Launch, Smartphone Boom, Peak Wars, Notch & Foldables, Recent Era (2021–2024), Major Controversies (Antennagate, Bendgate, Note 7, Batterygate, Huawei Ban), and Modern Minimalist Dumbphones.*
4. **💻 Operating System Version Histories (64 Items / 5 Families)**
   - *Windows (1.0 to 11), Mac OS (System 1 to macOS 15 Sequoia), Android (1.5 Cupcake to 15), iOS (iPhone OS 1 to iOS 18), and Major Linux Distributions (Debian, Arch, Ubuntu, Mint, Fedora, Red Hat, Pop!_OS, SteamOS, Gentoo, Kali, Alpine).*
5. **🕹️ Game Dev & Tech Art (4 Items / 4 Drawers)**
   - *Game Design & Engines, Shaders & Tech Art, Audio & Soundtracks, Reference & Docs.*
6. **📚 Full Combined Library (63 Items / 11 Drawers)**

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
