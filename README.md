<p align="center">
  <h1 align="center">🎨 ArtCraft Web Apps Suite</h1>
  <p align="center">
    <b>Unofficial Web Mirror & Hub for all 13 Open-Source ArtCraft Creative & Productivity Applications</b><br>
    Rebuilt from scratch in pure Rust • Powered by WebAssembly & WebGPU • 100% Client-Side & Private.
  </p>
</p>

<p align="center">
  <img alt="Unofficial Showcase" src="https://img.shields.io/badge/Showcase-Unofficial%20Community%20Mirror-orange?style=flat-square">
  <img alt="100% Rust" src="https://img.shields.io/badge/100%25-Rust-b7410e?style=flat-square&logo=rust">
  <img alt="WebAssembly" src="https://img.shields.io/badge/WebAssembly-WASM-654ff0?style=flat-square&logo=webassembly">
  <img alt="WebGPU" src="https://img.shields.io/badge/Graphics-WebGPU%20%2F%20WebGL2-059669?style=flat-square">
  <img alt="Deploy" src="https://img.shields.io/badge/Deploy-Vercel-black?style=flat-square&logo=vercel">
  <img alt="License: MIT OR Apache-2.0" src="https://img.shields.io/badge/license-MIT%20%2F%20Apache--2.0-3a3a3a?style=flat-square">
</p>

---

> **⚠️ Notice:** This repository is an **unofficial community web showcase and mirror**. It is an independent project provided for educational, testing, and evaluation purposes. All applications hosted here are open-source projects created by the [ArtCraft](https://getartcraft.com) team ([github.com/storytold](https://github.com/storytold)).

---

## 🚀 Apps Lineup

This web suite hosts the prebuilt WebAssembly editions for all 13 core ArtCraft apps:

| Application | Nominative Comparison | Category | Route |
|---|---|---|---|
| **🖼️ PhotoCraft** | Adobe Photoshop Alternative | Image Editing & PSD Support | `/apps/photocraft/` |
| **✒️ VectorCraft** | Adobe Illustrator Alternative | Precision Vector Illustration | `/apps/vectorcraft/` |
| **☀️ LightCraft** | Adobe Lightroom Alternative | Non-destructive RAW Developing | `/apps/lightcraft/` |
| **🎬 FilmCraft** | Adobe Premiere Pro Alternative | Multi-Track Video Timeline | `/apps/filmcraft/` |
| **✨ EffectCraft** | Adobe After Effects Alternative | Motion Graphics & VFX Compositor | `/apps/effectcraft/` |
| **📰 DesignCraft** | Adobe InDesign Alternative | Desktop Publishing & Page Layout | `/apps/designcraft/` |
| **📐 FigCraft** | Figma Alternative | UI/UX & Component Prototyping | `/apps/figcraft/` |
| **📝 WordCraft** | Microsoft Word Alternative | High-Performance Word Processor | `/apps/wordcraft/` |
| **📊 GridCraft** | Microsoft Excel Alternative | Ultra-Fast Spreadsheet Engine | `/apps/gridcraft/` |
| **📽️ DeckCraft** | Microsoft PowerPoint Alternative | Slide Presentations & Decks | `/apps/deckcraft/` |
| **📄 PdfCraft** | Adobe Acrobat Alternative | Offline PDF Workbench & Tools | `/apps/pdfcraft/` |
| **🎙️ SoundCraft** | Avid Pro Tools Alternative | Digital Audio Workstation (DAW) | `/apps/soundcraft/` |
| **⚙️ CADCraft** | AutoCAD Alternative | 2D/3D Precision CAD & Drafting | `/apps/cadcraft/` |

---

## 🌐 Deploying to Vercel

1. Push this repository to GitHub.
2. In [Vercel](https://vercel.com/), click **"Add New Project"** and select `artcraft-apps`.
3. **Framework Preset:** `Other` (Static Site).
4. **Build Command:** Leave empty (static prebuilt).
5. **Output Directory:** Leave blank / root (`.`).
6. Click **Deploy**!

Both `vercel.json` and `_headers` are preconfigured with `application/wasm` MIME types and immutable caching headers.

---

## 🔒 Privacy & Architecture

- **100% Client-Side Execution:** All calculations, image rendering, and document processing run locally on the visitor's hardware via WebAssembly (`.wasm`) and GPU shaders (`WebGPU` / `WebGL2`).
- **Zero Cloud Storage:** No user canvases, files, or telemetry are ever uploaded or transmitted to an external server.

---

## ⚖️ Legal & Trademark Disclaimers

1. **Credits & Attribution:**
   All thirteen applications were designed, built, and open-sourced by the **ArtCraft development community** at [getartcraft.com](https://getartcraft.com) and [github.com/storytold](https://github.com/storytold) under permissive open-source licenses (MIT License and Apache License 2.0). All rights and code copyright remain with their original authors.

2. **Trademark Notice:**
   All third-party trademarks, product names, trade names, and logos cited (such as *Adobe, Photoshop, Illustrator, Lightroom, Premiere Pro, After Effects, InDesign, Acrobat, Microsoft Word, Excel, PowerPoint, Figma, AutoCAD, Autodesk, Avid, Pro Tools*) are the intellectual property of their respective trademark holders. Mentioning them is strictly for descriptive, identification, and fair-use comparison purposes. This repository and hosted mirror are not sponsored, endorsed, affiliated with, or associated with Adobe Inc., Microsoft Corporation, Figma Inc., Autodesk Inc., Avid Technology, or ArtCraft.
