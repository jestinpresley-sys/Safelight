# Safelight

A layered image editor that runs entirely in the browser. It's one HTML file with no build step and no dependencies beyond Google Fonts.

## Features

- **Layers:** visibility, opacity, 16 blend modes, reorder, duplicate, merge and flatten.
- **Layer masks:** paint black to hide and white to reveal.
- **Adjustment layers:** Levels, Curves, Hue/Saturation, Brightness/Contrast and more, each with its own mask.
- **Layer styles:** drop shadow, outer glow, stroke and color overlay.
- **Editable text layers:** text stays editable through moves, transforms and resizes.
- **Selections:** marquee (rectangle or ellipse), lasso and magic wand, with add, subtract, intersect, inverse and feather.
- **Painting and retouching:** brush, eraser, clone stamp, spot healing, paint bucket, gradient, shapes and eyedropper.
- **Free transform:** scale, rotate and flip a layer or a selection.
- **Crop tool:** social aspect-ratio presets (1:1, 4:5, 9:16, 16:9, 1.91:1), with optional resizing of the output.
- **Destructive adjustments:** Levels, Curves, Hue/Saturation, Posterize, Gaussian blur, Invert, Black & white and Sepia.
- **Undo and redo:** up to 50 steps, plus a clickable History panel.
- **Projects:** autosave to the browser (IndexedDB), with a Projects list and portable `.safelight.json` project files.
- **Export:** PNG or JPEG.

## Run it

Open `index.html` in a browser. No server is needed.

To host it on GitHub Pages:

1. Go to **Settings › Pages**.
2. Set the source to **Deploy from a branch**, branch `main`, folder `/ (root)`.

## Keyboard shortcuts

| Key | Tool / action |
| --- | --- |
| V, M, L, W, C | Move, Marquee, Lasso, Magic wand, Crop |
| B, E, S, J | Brush, Eraser, Clone stamp, Spot healing |
| G, I, T, U | Paint bucket / Gradient, Eyedropper, Type, Shape |
| H, Z, Space | Hand, Zoom, temporary pan |
| [ and ] | Brush size |
| X, D | Swap colors, default colors |
| Ctrl/⌘ + Z, Ctrl/⌘ + Shift + Z | Undo, redo |
| Ctrl/⌘ + Alt + T | Free transform |
| Ctrl/⌘ + L, Ctrl/⌘ + M, Ctrl/⌘ + U | Levels, Curves, Hue/Saturation |
| Ctrl/⌘ + S | Save project |
| Ctrl/⌘ + Shift + E | Export image |

## Notes

- Projects are stored in the browser you use. To move one to another device, use **File › Download project file**, then open it there with **File › Open…**.
- Image export and project files download as normal files in a browser. Inside claude.ai they go through Claude's download prompt instead.
