## What is Kerfline?

Kerfline is a free drawing program for making **vector drawings**: pictures made of lines and shapes instead of pixels. A vector drawing stays sharp at any size, and machines can follow its lines exactly. That is why laser cutters, vinyl cutters, CNC routers and printers all work from vector files.

With Kerfline you draw shapes, curves and text on a page, then save the design in the file type your machine or project needs. It's made by **SRIVELTECH** for students, teachers, STEM clubs, makerspaces and anyone who makes things.

- **Free.** One version with everything included. Nothing to buy, ever.
- **No account.** No sign-in, no ads, no tracking.
- **Private.** Your drawings stay on your own computer and are never uploaded.
- **Works offline.** Use it in a browser or install it on Windows; no internet needed after that.

## What can you use it for?

| You want to… | Kerfline helps by… |
|---|---|
| **Cut or engrave on a laser cutter** (boxes, keychains, signs, puzzles) | One click turns a line into a cut line (red), score line (blue) or engraving (black fill). Export DXF or SVG for your laser software. |
| **Cut stickers, decals or T-shirt designs** on a vinyl cutter | Draw or import a design, apply the vinyl style, export SVG. |
| **Design parts for CNC routers** | Exact sizes in millimetres, DXF export with smooth, accurate curves. |
| **Make posters, flyers, certificates and logos** | Text in built-in fonts, colours and gradients, multiple pages, PDF and PNG export. |
| **Teach design and technology** | Runs in a browser on school PCs and Chromebooks with no install and no student accounts. |
| **Prepare outlines for 3D printing projects** | Export an SVG outline to bring into your 3D design tool. |
| **Edit an SVG you found or made elsewhere** | Opens SVG files as shapes you can change. |

## Download

| Option | For | How |
|---|---|---|
| **Windows app** | Your own PC | Download `Kerfline-Setup-0.1.0.exe` from [Releases](../../releases/latest) and run it. |
| **Web app** | Any computer, Chromebooks, school PCs | Open [kerfline.surge.sh](https://kerfline.surge.sh). Nothing to install. |
| **Offline file** | No internet, or a USB stick | Download [`Website/kerfline.html`](Website/kerfline.html) (click **Download raw file**) and open it in Chrome or Edge. |

### Installing on Windows
1. Run `Kerfline-Setup-0.1.0.exe`. No administrator password is needed.
2. Windows may say **"Windows protected your PC"**, because the installer isn't code-signed yet. Click **More info → Run anyway**.
3. Open Kerfline from the desktop shortcut or the Start menu.

Uninstall from **Windows Settings → Apps**. Uninstalling never deletes your drawings.

Works on Windows 10 and 11 (64-bit). Installer about 103 MB; about 321 MB once installed. Full steps: [How to install Kerfline](Desktop%20App/How%20to%20install%20Kerfline.txt).

## Features

**Drawing**
- Rectangle, ellipse, polygon and star, freehand, Bézier and pen tools
- Node editing with the Shape tool
- Text in five built-in open fonts, and text to curves
- Weld, Trim, Intersect, Combine, Group, Align
- Solid and gradient fills, outlines, opacity
- Layers, multiple pages, rulers, guides and snapping

**Made for making**
- **Maker styles:** one click for laser cut (red hairline), score (blue), engrave (black fill) or vinyl cut
- **DXF export** for laser and CNC: millimetres, curves accurate to 0.05 mm, colours laser software understands
- Export **SVG**, **PDF** (all pages), **PNG** and **DXF**
- Import SVG files as editable shapes, and pictures (PNG, JPG, GIF, WebP)

**Never lose work**
- Saves after every change
- Offers to restore your work after a crash
- The Windows app saves every drawing as a file in `D:\KerflineDrawings` (or `Documents\KerflineDrawings`)
- Deleted drawings go to a `Deleted` folder, and each save keeps the previous version
- **Files never expire:** every version opens every older file

<p align="center"><img src="screenshots/kerfline-home.png" alt="The Kerfline home screen with New drawing, Open a .svd file and a recent drawing"></p>

## Keyboard shortcuts

| Key | Tool | Key | Tool |
|---|---|---|---|
| `V` | Pick | `F6` | Rectangle |
| `F10` | Shape (edit nodes) | `F7` | Ellipse |
| `Z` / `H` | Zoom / Pan | `Y` | Polygon / star |
| `F5` | Freehand | `F8` | Text |
| `B` | Bézier | `I` | Copy colours from an object |
| `P` | Pen | `F4` | Fit page in window |

Also: `Ctrl+Z` undo · `Ctrl+Y` redo · `Ctrl+D` duplicate · `Ctrl+G` / `Ctrl+U` group / ungroup · `Ctrl+L` combine · `Ctrl+Q` convert to curves · `Ctrl+I` import · `Ctrl+E` export · `Ctrl+S` save.

## Where your drawings are saved

| Version | Where |
|---|---|
| Windows app | `.svd` files in `D:\KerflineDrawings`. Change it with **File → Change drawings folder…** |
| Web app | Your own browser. Use **Download .svd** to keep a copy as a file. |

Nothing is ever uploaded.

## What's in this repository

| Folder / file | What it is |
|---|---|
| [`Website/`](Website/) | The Kerfline website, ready to publish: [home page](Website/index.html), [the app](Website/app/index.html), [offline file](Website/kerfline.html), [privacy page](Website/privacy.html) |
| [`Desktop App/`](Desktop%20App/) | [How to install Kerfline](Desktop%20App/How%20to%20install%20Kerfline.txt). The installer itself is under [Releases](../../releases/latest). |
| [`screenshots/`](screenshots/) | The pictures in this README |
| [`Read me first.txt`](Read%20me%20first.txt) | Plain-text guide to this folder |

### Publishing the website yourself
Publish the `Website` folder with any static host. For example, with [Surge](https://surge.sh):

```bash
surge Website kerfline.surge.sh
```

<p align="center"><img src="screenshots/kerfline-website.png" width="640" alt="The Kerfline website home page: Draw it. Cut it. Free."></p>

## Privacy

Kerfline collects nothing. There are no accounts, cookies, analytics or ads, and the app makes no network calls. See the [privacy page](Website/privacy.html).

## Credits

- Created by **SRIVELTECH**.
- Built-in fonts: Inter, Lora, JetBrains Mono, Bebas Neue and Pacifico, used under the SIL Open Font License 1.1.
- Built with React, TypeScript, Vite, paper.js, opentype.js and Electron.
- Kerfline is independent software. It isn't affiliated with any other drawing application.

---

<p align="center">Made with care by SRIVELTECH, for makers and learners everywhere.</p>
