# paper & pencil · portfolio

A minimalist, tactile portfolio website with a distinctive paper-and-ink aesthetic. Built with HTML, Tailwind CSS, and a custom theme system that celebrates monochromatic design.

![Light Theme Preview]
![Dark Theme Preview]

## ✦ Overview

paper & pencil is a digital portfolio that embodies the philosophy of its creator: minimalist, tactile, and rooted in analog design principles. Every element—from the paper-textured cards to the hand-drawn borders—reinforces the theme of working with physical materials in a digital space.

### Key Features

- **Dual Theme System** – Seamless light/dark mode with persistent user preference
- **Tactile Aesthetic** – Paper-like cards with sketchy borders, drop shadows, and hand-drawn elements
- **Fully Responsive** – Adapts gracefully from mobile to desktop
- **Smooth Animations** – Subtle fade-ins and hover effects using Animate.css
- **Scroll-Triggered Animations** – Elements animate as they enter the viewport
- **Advanced Parallax Effects** – Multi-layered parallax with mouse and scroll interactions
- **3D Depth Layers** – Elements positioned at different depths for immersive experience
- **Accessible Navigation** – Smooth scroll to sections with clear visual feedback
- **No Dependencies** – Pure HTML/CSS/JS with Tailwind for utility classes

## ✦ Theme System

The site features two carefully crafted themes:

| Theme | Background | Text | Accent | Icon |
|-------|------------|------|--------|------|
| **Light** | Off-white paper (#faf9f6) | Deep black (#111111) | Pure black borders | ☼ Sun |
| **Dark** | Deep charcoal (#1a1a1a) | Soft white (#ededed) | Silver borders (#b0b0b0) | ☾ Moon |

The theme toggle:
- Saves preference in `localStorage`
- Persists across sessions
- Updates all CSS variables dynamically
- Maintains visual consistency across all components

## ✦ Animation & Parallax Features

### Scroll-Triggered Animations
- Elements fade and slide in when they enter the viewport
- Staggered delays for sequential reveals (0.1s to 0.6s)
- Multiple animation types: slide-left, slide-right, slide-up, scale

### Parallax Effects
- **Scroll-based parallax** – Background patterns and elements move at different speeds
- **Mouse move parallax** – 3D tilt effects that follow cursor movement
- **Floating paper elements** – Abstract paper shapes drift diagonally
- **Depth layers** – Elements positioned at different Z-depths (20px, 40px, 60px)
- **Section backgrounds** – Subtle diagonal patterns that move independently

### Interactive Hover Effects
- Cards lift and cast stronger shadows
- Project icons rotate and scale
- Stamp badges float and pulse
- Buttons have ripple effects
- Text links underline and slide
