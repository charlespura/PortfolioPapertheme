# paper & pencil · portfolio

A minimalist, tactile portfolio website with a distinctive paper-and-ink aesthetic. Built with HTML, Tailwind CSS, and a custom theme system.

![Light Theme Preview](https://via.placeholder.com/800x400/faf9f6/111111?text=Light+Mode)
![Dark Theme Preview](https://via.placeholder.com/800x400/1a1a1a/ededed?text=Dark+Mode)

## ✦ Overview

paper & pencil is a digital portfolio that embodies minimalist, tactile design principles. Every element reinforces the theme of working with physical materials in a digital space.

### Key Features
- **Dual Theme System** – Light/dark mode with localStorage persistence
- **Tactile Aesthetic** – Paper-like cards, sketchy borders, hand-drawn elements
- **Advanced Parallax** – Scroll and mouse-based 3D effects
- **Scroll Animations** – Elements animate as they enter viewport
- **Fully Responsive** – Adapts from mobile to desktop
- **No Dependencies** – Pure HTML/CSS/JS + Tailwind CDN

## ✦ Theme System

| Theme | Background | Text | Border | Icon |
|-------|------------|------|--------|------|
| **Light** | #faf9f6 | #111111 | #000000 | ☼ |
| **Dark** | #1a1a1a | #ededed | #b0b0b0 | ☾ |

## ✦ Animation Features

### Scroll-Triggered
- Elements slide in at viewport entry (10% threshold)
- Staggered delays: 0.1s to 0.6s
- Types: slide-left, slide-right, slide-up, scale

### Parallax Effects
- **Scroll-based** – Backgrounds move at 0.2x speed
- **Mouse-based** – 3D tilt (5-15° rotation)
- **Floating paper** – 4 drifting shapes
- **Depth layers** – Z-index: 20px, 40px, 60px

### Hover Effects
- Cards lift and shadow increases
- Icons rotate and scale
- Buttons have ripple effect
- Stamps float and pulse

## ✦ Project Structure
paper-pencil-portfolio/
├── index.html # Main portfolio
├── README.md # Documentation
└── assets/
└── picture/
└── ch.jpg # Profile image

text

## ✦ Quick Customization

### Colors (in `<style>`)
```css
:root {  /* light theme */
  --bg-paper: #faf9f6;
  --card-bg: #ffffff;
  --text-primary: #111111;
  --border-strong: #000000;
}
body.dark {  /* dark theme */
  --bg-paper: #1a1a1a;
  --card-bg: #2a2a2a;
  --text-primary: #ededed;
  --border-strong: #b0b0b0;
}
Content to Replace
Profile: Update src="/picture/ch.jpg"

Name: Change "Alex Mercer"

Projects: Titles, descriptions, dates

Contact: Email, phone, address

Social: Instagram, Are.na links

Adding a Project
html
<div class="paper-card p-5 project-card scroll-animation slide-up stagger-1">
  <div class="h-40 ... text-6xl">✻</div>
  <h3 class="text-2xl font-bold">Project Name</h3>
  <p class="flex gap-2"><span class="project-stamp">category</span></p>
  <p class="mt-3">Description text...</p>
  <div class="flex justify-between mt-4">
    <span class="text-xs">2024</span>
    <span class="text-lg">→</span>
  </div>
</div>
Available Icons
✻ ◈ ☲ ▣ ⬚ ◉

Stagger Classes
stagger-1 (0.1s) through stagger-6 (0.6s)

Depth Classes
parallax-depth-1 (20px), depth-2 (40px), depth-3 (60px)

✦ Browser Support
Chrome/Edge, Firefox, Safari (latest)

Mobile browsers (responsive)

IE11 not supported

✦ Performance
Lightweight (<100KB)

Hardware-accelerated animations

Lazy loading images

Mobile-optimized

60fps with will-change

✦ Credits
Design & Development: Charles Pura

Inspiration: Analog sketchbooks, paper crafts

Font: Inter (via Tailwind)

Icons: Unicode symbols

✦ License & Contact
© 2025 paper+pencil — all rights reserved

Contact: hello@paperandpencil.studio
Instagram: @paperandpencil
GitHub: @charlespura

✦ Version History
v2.0.0 (Mar 2026) – Parallax, 3D tilt, floating paper
v1.0.0 (Jan 2025) – Light/dark theme, basic cards

