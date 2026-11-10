# AutoFix Car Repair - Technical Documentation

## Overview
AutoFix is a premium, high-performance HTML5 template specifically designed for automotive repair shops, mechanics, and service centers. This document provides a deep-dive into the technical architecture, component structure, and design principles used in this template.

## Table of Contents
1. [Project Structure](#project-structure)
2. [Features](#features)
3. [Technical Architecture](#technical-architecture)
4. [CSS Design Tokens](#css-design-tokens)
5. [JavaScript Implementation](#javascript-implementation)
6. [Responsive Logic](#responsive-logic)
7. [Browser Compatibility](#browser-compatibility)
8. [Credits](#credits)

---

## 1. Project Structure
The template follows a clean and modular directory organization:
```text
/car-repair-template
│
├── index.html              # Main one-page landing experience
├── css/
│   └── styles.css          # Core design and layout system
├── js/
│   └── main.js             # Navigation, animation and slider logic
├── images/                 # Theme graphics and automotive assets
├── fonts/                  # Custom iconography and web fonts
├── documentation.md        # Technical Documentation (Markdown)
├── documentation.html      # Technical Documentation (HTML)
├── user-guide.md           # User Maintenance Guide (Markdown)
└── user-guide.html         # User Maintenance Guide (HTML)
```

## 2. Features
AutoFix is packed with enterprise-grade features for automotive businesses:
- **Hero Slider**: Interactive, fade-animation slider for high-impact visual first impressions.
- **Service Catalog**: Structured grid layout for showcasing different automotive repair specialties.
- **Guarantee Badge**: High-trust visual section with hover animations.
- **Stats Counter**: JavaScript-driven numeric counters for business metrics.
- **Testimonial Engine**: Slide-based customer review system with avatar support.
- **Contact Integration**: Clean contact layouts with interactive address and social markers.

## 3. Technical Architecture

### HTML5 Standards
- **Semantic Components**: Use of `<header>`, `<main>`, `<section>`, and `<footer>` for optimal accessibility and indexing.
- **SEO Ready**: Meta tags, open-graph protocols, and optimized heading hierarchy come pre-configured.

### CSS3 Framework (Native)
- **Fluid Layout**: Built using CSS Flexbox and Grid, ensuring zero reliance on heavy external frameworks like Bootstrap.
- **BEM Naming**: CSS classes follow a modified Block-Element-Modifier convention for easier maintenance.

## 4. CSS Design Tokens
The entire visual identity is centralized via CSS variables in `css/styles.css`:

```css
:root {
    /* Primary Brand Colors */
    --color-primary: #ff4d4d;    /* Signature Mechanic Red */
    --color-secondary: #1a1a1a;  /* Industrial Charcoal */
    --color-accent: #f0f0f0;     /* Metallic Silver */
    
    /* Global Typography */
    --font-heading: 'Montserrat', sans-serif;
    --font-body: 'Roboto', sans-serif;
}
```

## 5. JavaScript Implementation
`js/main.js` governs all the template's interactive logic without any external library dependencies (Vanilla JS).

- **Navigation Logic**: Manages the sticky header state and mobile menu toggling.
- **Slider Controller**: A custom light-weight slider script for the Hero and Testimonial sections.
- **Intersection Observer**: Used for "Animate on Scroll" effects to ensure peak performance.

## 6. Responsive Logic
AutoFix is built with a **Mobile-First** approach.
- **Mobile (< 768px)**: Optimized single-column flows and touch-friendly navigation.
- **Tablet (768px - 1024px)**: Dual-column service grids and fluid margins.
- **Desktop (> 1024px)**: Multi-column layouts with interactive hover states.

## 7. Browser Compatibility
Optimized for the latest versions of:
- Google Chrome
- Mozilla Firefox
- Microsoft Edge
- Apple Safari

## 8. Credits
- **Fonts**: Google Fonts (Montserrat, Roboto)
- **Imagery**: Unsplash (Royalty-free automotive imagery)
- **Icons**: Custom SVG set
- **Developed by**: [TemplateLayer.com](https://templatelayer.com)
