
# Manthar Ali Sandano — Developer Portfolio

> A single-page, animation-driven portfolio built from scratch — no frameworks, no build tools, just clean HTML, CSS, and JavaScript doing the heavy lifting.

[![Live Demo](https://img.shields.io/badge/Live-Demo-00E5FF?style=flat-square)](https://Manthar-Ali-sandano.github.io/<your-repo>/)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)](#)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)](#)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)](#)
[![GSAP](https://img.shields.io/badge/GSAP-88CE02?style=flat-square&logo=greensock&logoColor=white)](#)

---

## 🧠 Overview

I built this portfolio to solve a simple problem: **most developer portfolios look the same.**

So instead of grabbing a template, I wrote one from scratch — a fully interactive, animated, themeable single-page app that runs entirely in the browser with zero dependencies to install and zero build steps to run.

It's my digital handshake: who I am, what I build, what I teach, and how to reach me.

---

## ⚙️ What's Under the Hood

I approached this like a real product, not a static page. Here's what I engineered:

### 🎨 Design System
- **CSS custom properties** power the entire theme (colors, gradients, radii, easing curves) — flip one attribute and the whole site re-skins.
- **Dark / Light mode** with `localStorage` persistence and a smooth 500ms transition. No flash of wrong theme on reload.
- **Glassmorphism panels** using `backdrop-filter` + subtle borders for depth without heaviness.

### 🎬 Motion & Interaction
- **GSAP + ScrollTrigger** drives all scroll-based reveals, animated stat counters, and the experience timeline progress bar.
- **Custom cursor** with a lagging ring (lerp animation via `requestAnimationFrame`) that reacts to hoverable elements.
- **Magnetic buttons** that subtly follow the pointer, plus **Material-style ripple** on click.
- **Typed.js** cycles through my roles in the hero — because one job title never tells the whole story.
- **VanillaTilt** adds 3D parallax to project cards on hover.
- **Canvas Confetti** fires on resume download, contact submit, and a hidden coffee-counter easter egg.

### 🧩 Engineering Decisions
- **Zero build step.** No Webpack, no Vite, no npm. Open `index.html` — it works. Deploy anywhere.
- **Single-file architecture.** HTML, CSS, and JS live in one file for portability. Easy to audit, easy to fork.
- **Graceful degradation.** `@media (prefers-reduced-motion: reduce)` kills all animation for users who need it.
- **Progressive enhancement.** Everything critical works without JS; the animations are the cherry on top.
- **Performance-conscious.** Particles capped at 44, blobs use `transform` (GPU-friendly), no layout thrash on scroll.

### 📱 Responsive by Default
- Mobile-first CSS with breakpoints at 900px, 768px, and 640px.
- Hamburger nav slides in from the right with a proper focus flow.
- Chips, custom cursor, and floating badges auto-disable on touch devices.

### ♿ Accessibility
- Semantic HTML throughout (`<nav>`, `<section>`, `<footer>`, `<button>`).
- ARIA labels on every icon-only control.
- Keyboard-navigable — every interactive element is a real `<a>` or `<button>`.
- Respects reduced-motion and high-contrast preferences.

---

## 🧰 Tech Stack

| Layer | Tools |
|---|---|
| **Markup** | HTML5 (semantic) |
| **Styling** | CSS3 — custom properties, Grid, Flexbox, `backdrop-filter`, mask-composite |
| **Logic** | Vanilla JavaScript (ES6+) — no framework |
| **Animation** | GSAP 3 + ScrollTrigger |
| **Extras** | Typed.js · VanillaTilt · Canvas Confetti |
| **Icons** | Font Awesome 6 |
| **Type** | Sora · Inter · JetBrains Mono (Google Fonts) |

---

## 📂 Project Structure
