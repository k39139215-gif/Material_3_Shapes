# 🎨 Google Material Design 3 Expressive Shapes Library

[![Material Design 3](https://img.shields.io/badge/Material_Design-3.0_Expressive-7C4DFF?logo=material-design&logoColor=white)](https://m3.material.io/)
[![Format](https://img.shields.io/badge/Format-SVG_Vector-FF5722?logo=svg&logoColor=white)]()
[![Shapes](https://img.shields.io/badge/Catalog-70%2B_Variants-00B0FF)]()
[![License: Proprietary](https://img.shields.io/badge/License-Proprietary_All_Rights_Reserved-red.svg)](LICENSE)

A complete vector asset collection and interactive preview catalog implementing Google's **Material Design 3 (Material You) Expressive Shape System**. Includes raw mathematical outline SVGs and gradient/color-styled variants for modern card containers, hero imagery, avatars, and chip components.

---

## 🌟 Catalog Overview

Contains **70+ production-ready SVG assets** spanning the complete Material 3 geometric family:

* **Geometric & Curved:** Circles, Squares, Ovals, Pills, Arches, Semicircles, Slanted boxes.
* **Organic & Dynamic:** Fans, Clovers, Sunny stars, Flowers, Puffs, Clouds, Scallops, Soft bursts.
* **Polygonal & Pointed:** Triangles, Diamonds, Pentagon, Hexagon, Octagon, Decagon, Dodecagon.
* **Expressive Starbursts:** 4-point, 6-point, 8-point, 12-point stars, Pixel stars, and Banners.
* **Each Shape Includes:**
  1. **Raw Vector (`*_styled.svg`):** Pure mathematical coordinate path ready for CSS fills or mask-image cropping.
  2. **Styled Variant (`*.svg`):** Pre-styled with Material You dynamic color tokens and gradient palettes.

---

## 🖥️ Interactive Web Preview

Open `preview.html` in any web browser to view the live grid of all 70+ rendered shapes:

```bash
# Preview directly in default browser (Windows)
start preview.html
```

---

## 📁 Repository Structure

```text
Material_3_Shapes/
├── preview.html       # Interactive responsive grid previewing all shapes
├── 01_circle.svg      # Styled Material 3 circle
├── 01_circle_styled.svg
├── 04_arch.svg        # Modern expressive arch container
├── 10_fan.svg         # Expressive fan container
├── 15_clover.svg      # Organic 4-leaf clover shape
├── 25_star_8.svg      # 8-point expressive star
└── ... (70+ SVG vector assets)
```

---

## 🚀 How to Use in Web & UI Projects

### 1. Direct SVG Embedding:
```html
<img src="04_arch.svg" alt="M3 Arch Shape" width="120" height="120" />
```

### 2. CSS Masking:
```css
.m3-avatar {
  width: 96px;
  height: 96px;
  mask-image: url('04_arch_styled.svg');
  mask-size: contain;
  mask-repeat: no-repeat;
}
```

---

## ⚖️ Intellectual Property & License

**Copyright (c) 2026 Kartik. All Rights Reserved.**

This repository and its vector assets are published for **viewing, evaluation, and design demonstration purposes only**. No permission is granted to reproduce, distribute, or bundle this collection into competing commercial design packages. See the [LICENSE](LICENSE) file for complete legal terms.
