# AutoFix Car Repair - User Guide

## Table of Contents
1. [Introduction](#introduction)
2. [Getting Started](#getting-started)
3. [File Structure](#file-structure)
4. [Customization Guide](#customization-guide)
5. [Section Editing](#section-editing)
    - [Header & Navigation](#header-navigation)
    - [Hero Slider Section](#hero-section)
    - [About Us Section](#about-section)
    - [Guarantee Section](#guarantee-section)
    - [Service Cards](#service-section)
    - [Testimonials Slider](#reviews-section)
    - [Interactive Contact Form](#contact-section)
    - [Footer Section](#footer-section)
6. [Adding Content](#adding-content)
    - [Adding New Services](#adding-services)
    - [Adding New Slides](#adding-slides)
    - [Adding Gallery Images](#adding-gallery)
7. [Component Guide](#component-guide)
    - [Buttons & Actions](#buttons)
    - [Icons & Glyphs](#icons)
    - [Typography Hierarchy](#typography)
8. [Theme & Styling](#theme-and-styling)
    - [Primary Brand Colors](#brand-colors)
    - [Customizing Shadows](#shadows)
    - [Transitions](#transitions)
9. [JavaScript Library](#js-logic)
    - [Navigation Behavior](#nav-logic)
    - [Slider Configuration](#slider-config)
    - [Counter Logic](#counter-logic)
10. [Responsive Maintenance](#responsive-maintenance)
11. [SEO Perfection](#seo-optimization)
12. [Performance Tuning](#performance)
13. [Deployment Guide](#deployment)
14. [Troubleshooting](#troubleshooting)
15. [Frequently Asked Questions](#faqs)

---

## 1. Introduction
Welcome to the AutoFix Car Repair template! This premium HTML5 solution is designed to give your automotive business a rugged and professional digital store-front. This guide is your complete companion for transforming this template into your specific automotive brand.

### Core Philosophy
- **Industry First**: Rugged edges and metallic accents for the automotive niche.
- **Conversion-Led**: Clear CTAs for "Booking an Appointment" and "Viewing Services".
- **Zero bloat**: High-performance code with zero framework dependencies.

## 2. Getting Started
### Prerequisites
- **Text Editor**: We highly recommend Visual Studio Code.
- **Image Editing**: Basic knowledge of image resizing (Photoshop or Canva).
- **Basic HTML**: Familiarity with tags and common attributes.

### Installation
1. Extract the `car-repair-template.zip`.
2. Open the resulting folder in your code editor.
3. Launch `index.html` in your browser to verify the site is running correctly.

## 3. File Structure
```text
/car-repair-template/
│
├── index.html              # The master landing page
├── css/
│   └── styles.css          # The master design system
├── js/
│   └── main.js             # Interaction engine
├── images/                 # Automotive assets folder
│   ├── hero/               # Background covers
│   ├── services/           # Mechanic specialized images
│   └── icons/              # UI markers
├── documentation.md        # Technical technical specs (MD)
└── user-guide.md           # This comprehensive guide (MD)
```

## 4. Customization Guide
### Quick Setup Checklist
1. **Brand Name**: Update your business name in the header and footer.
2. **Contact Details**: Update the phone number and address in the Contact section.
3. **Hero Slider**: Upload 3 high-impact car images for the first impression.
4. **Service List**: Refine the services to matches exactly what your shop offers.

## 5. Section Editing

### Header & Navigation
Located at the top of the page. It manages your logo and site-wide navigation.
```html
<header class="header" id="header">
    <div class="header-container">
        <!-- Logo -->
        <a href="#" class="logo">
            <span class="logo-text">Auto<span>Fix</span></span>
        </a>
        
        <!-- Links -->
        <nav class="nav-menu">
            <a href="#services" class="nav-link">Our Services</a>
            <a href="#contact" class="nav-link">Contact</a>
        </nav>
    </div>
</header>
```

### Hero Slider Section (index.html)
The primary visual hook.
```html
<section class="hero">
    <div class="heroSlider">
        <div class="hero-slide active">
            <div class="bg" style="background-image: url('images/hero1.jpg');"></div>
            <div class="content">
                <h1>Full-Service Repair</h1>
                <p>Pro maintenance and certified technicians.</p>
            </div>
        </div>
    </div>
</section>
```

### Service Cards
A grid-based section showing off your mechanic specialties.
```html
<div class="service-card">
    <img src="images/services/brakes.jpg" alt="Brake Repair" class="service-image">
    <div class="service-content">
        <h3 class="title">Brake Service</h3>
        <p>Complete rotor and pad replacements.</p>
        <a href="#contact" class="btn-link">Book Now</a>
    </div>
</div>
```

## 6. Adding Content

### Adding New Services
To add a new service:
1. Copy an existing `.service-card` div from the services grid.
2. Replace the `src` of the image with a new 600x400 image.
3. Update the `h3` title and the `p` description.
4. Ensure the `.animate` classes are maintained for the slide-up effect.

### Adding New Slides
1. Open `index.html` and look for the `.hero-slider` container.
2. Duplicate a `.hero-slide` div.
3. Update the background image URL.
4. Add a new `.hero-nav-dot` for navigation parity in the `heroNav` section.

## 7. Component Guide

### Buttons & Actions
- **.btn-primary**: The signature Mechanic Red button for main CTAs.
- **.btn-outline**: Elegant transparent button for secondary info.
- **.back-to-top**: Floating action button that appears after scrolling.

### Typography Hierarchy
- **Montserrat**: Used for industrial-grade headings (h1, h2, h3).
- **Roboto**: Used for high-readability body text and descriptions.

## 8. Theme & Styling

### Primary Brand Colors
Customizing colors is safe and centralized in `styles.css`.
```css
:root {
    --color-primary: #ff4d4d;    /* The signature red */
    --color-secondary: #1a1a1a;  /* The industrial dark grey */
    --color-accent: #ffffff;     /* The highlight white */
}
```

## 9. JavaScript Library
`main.js` governs the interactive logic:
- **Sticky State**: The header gains a `.sticky` class when scrolling past 100px.
- **Numeric Counter**: Animates numbers from zero to the value in the `data-target` attribute.
- **Testimonial Switcher**: Manages the fading between customer reviews.

## 10. Responsive Maintenance
AutoFix is built to look stunning on all screens:
- **Mobile**: The menu collapses into a hamburger icon at 768px.
- **Desktop**: Features full hover interactivity and high-res imagery.

## 11. SEO Perfection
- **Title Tags**: Ensure your `<title>` includes your city name (e.g., "AutoFix | Car Repair in Chicago").
- **Meta Description**: Update the 150-character summary in the head to include your primary services.
- **Alt Tags**: Add descriptions like `alt="ASE Certified Mechanic working on Ford engine"` to every primary image.

## 12. Deployment Guide
### Steps to Launch
1. Ensure all placeholder images are replaced with your own.
2. Test the "Back to Top" functionality.
3. Upload the entire project folder to your web server (Netlify, Vercel, or HostGator).

## 13. Troubleshooting
### The slider isn't moving?
Ensure `main.js` is linked correctly at the bottom of the body. If using external libraries, check that they don't conflict with our native slider logic.

### Images look blurry?
Ensure your Hero images are at least 1920px wide and your Service images are at least 600px wide.

## 14. FAQs
**Can I receive emails through the contact form?**
Yes! Link your form to a service like **Formspree** or **Netlify Forms** using the `action` attribute in the `<form>` tag.

**How do I change the speed of the slider?**
Locate the `setInterval` in `main.js` inside the `sliderInit()` function and adjust the millisecond value.

**What size should the Logo be?**
The logo is designed for a height of ~40-60px. If you use a taller logo, adjust the `padding` of the `.header`.

---
Developed by [TemplateLayer.com](https://templatelayer.com)
"The Industrial Gold Standard for Automotive Web Templates."
