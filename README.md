# SVG Recolor — Figma Plugin

Recolor hardcoded SVG colors directly in Figma — no more fiddling with hue-rotation effect sliders.

## What it does

- **Vector layers** — scans all solid fill and stroke colors across every descendant layer and lets you swap them directly
- **Rasterized SVGs** — when Figma converts an SVG to image fills, the plugin reads the pixel data, finds the distinct colors, and does pixel-level color replacement at full resolution

## How to use

1. Select any layer (group, frame, vector, or image)
2. Open the plugin — it scans and lists every color found
3. Click a color swatch on the right to pick your replacement
4. Hit **Apply colors**

## Installing locally

1. Clone or download this repo
2. Open Figma Desktop → **Plugins → Development → Import plugin from manifest…**
3. Select `manifest.json`

## Publishing to the Figma Community

1. Change `"id"` in `manifest.json` to a unique reverse-domain ID (e.g. `"com.yourname.svg-recolor"`)
2. Import locally, test, then **Plugins → Development → ⋯ → Publish**
