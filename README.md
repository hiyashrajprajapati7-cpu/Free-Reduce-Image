# Free Reduce Image — 100% Private Batch Image Optimizer & Reducer 🚀

> Intelligently compress, resize, format-convert, and batch-optimize images directly in your browser with zero server uploads and zero privacy compromise.

![License](https://img.shields.io/badge/License-MIT-blue.svg)
![Astro](https://img.shields.io/badge/Astro-5.0-BC52EE.svg)
![Tailwind](https://img.shields.io/badge/Tailwind-4.0-38B2AC.svg)
![Client-Side](https://img.shields.io/badge/Client--Side-100%25%20Private-emerald.svg)

---

## ✨ Features

- **⚡ Smart Auto Reducer**: Perceptually compress images by up to 85% without noticeable loss of visual clarity.
- **🎯 Exact Target File Size (KB/MB)**: Binary search algorithm to meet strict upload caps (e.g. `< 50 KB`, `< 100 KB`, `< 200 KB`, `< 1 MB`) for government visa forms, passport portals, and job applications.
- **📐 Dimensions & DPI Resizer**: Resize pixel dimensions, scale percentages, and set print-ready DPI resolutions (72, 150, 300, 600 DPI) with Cover/Contain/Stretch fit modes.
- **🛂 Dedicated Passport Photo Preset**: Preset to 2x2 inch (51x51mm) or 35x45mm at 300 DPI and strictly `< 240 KB`.
- **🔄 Next-Gen Format Conversion**: Instant client-side conversion between WebP, AVIF, JPEG, PNG, BMP, GIF, and SVG.
- **📦 Batch Multi-File Processing & 1-Click ZIP**: Drop 50, 100, or more images at once and download all optimized results in a single organized `.zip` archive using JSZip.
- **👁️ Interactive Split Comparison Slider**: Dual-layer before vs after split comparison slider with draggable partition.
- **🛡️ 100% Private & In-Browser**: Built entirely with HTML5 Canvas, Web Workers, and client-side JavaScript. Photos never touch a server. Automatic EXIF and GPS metadata stripper.
- **🌙 Full Dark Mode Support**: Vercel/Geist inspired design system with pitch-black surfaces, zero flash of unstyled content (FOUC), and automatic system theme detection.

---

## 🛠️ Tech Stack

- **Framework**: [Astro](https://astro.build/) (Static Site Generation)
- **Styling**: [Tailwind CSS v4](https://tailwindcss.com/) & Geist Design System tokens
- **Image Processing**: HTML5 Offscreen Canvas API, Web Workers, Binary Search Compression
- **Archive Engine**: JSZip (In-Browser ZIP Generation)

---

## 🚀 Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/hiyashrajprajapati7-cpu/Free-Reduce-Image.git
cd Free-Reduce-Image
```

### 2. Install dependencies
```bash
npm install
```

### 3. Start development server
```bash
npm run dev
```
Open **[http://localhost:4321](http://localhost:4321)** in your browser.

### 4. Build for production
```bash
npm run build
npm run preview
```

---

## 📄 License
Released under the [MIT License](LICENSE).
