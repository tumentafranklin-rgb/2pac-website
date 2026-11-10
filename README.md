# Car Repair - Auto Service Website Template

A premium, modern, and fully responsive website template designed for auto repair shops, car service centers, and automotive businesses.

## 🚗 Features

- **Modern Design** - Dark theme with vibrant red accents
- **Fully Responsive** - Works on all devices (desktop, tablet, mobile)
- **Smooth Animations** - Scroll-triggered animations and transitions
- **Interactive Sliders** - Hero and testimonials sliders with auto-play
- **Clean Code** - Well-organized and commented code
- **SEO Optimized** - Includes meta tags and Open Graph data
- **No Dependencies** - Pure HTML5, CSS3, and JavaScript

## 📁 File Structure

```
car-repair-template/
├── index.html          # Main HTML file
├── css/
│   └── styles.css      # All styles with CSS variables
├── js/
│   └── main.js         # JavaScript functionality
├── images/             # Your images go here
├── fonts/              # Custom fonts (if needed)
└── README.md           # This file
```

## 🎨 Customization

### Changing Colors

Open `css/styles.css` and modify the CSS custom properties at the top:

```css
:root {
  /* Primary Colors */
  --primary-red: #e31e25;        /* Main accent color */
  --primary-red-dark: #c41a20;   /* Darker shade */
  
  /* Background Colors */
  --bg-dark: #1a1a2e;            /* Main background */
  --bg-darker: #0f0f1a;          /* Darker sections */
  
  /* ...more variables */
}
```

### Changing Fonts

Replace the Google Fonts link in `index.html`:

```html
<link href="https://fonts.googleapis.com/css2?family=YOUR+FONT&display=swap" rel="stylesheet">
```

Then update the font variables in CSS:

```css
:root {
  --font-primary: 'Your Font', sans-serif;
  --font-secondary: 'Your Other Font', sans-serif;
}
```

### Replacing Images

1. Add your images to the `images/` folder
2. Update the image paths in `index.html`

For hero slider background:
```html
<div class="hero-slide-bg" style="background-image: url('images/your-image.jpg');"></div>
```

For service cards:
```html
<img src="images/your-service-image.jpg" alt="Service Name" class="service-image">
```

### Updating Content

All text content is in `index.html`. Simply search and replace:

- Company name: Search for "Car Repair"
- Contact information: Update address, phone, hours
- Service descriptions: Modify the service card content
- Testimonials: Update client names and reviews

## 📱 Sections Included

1. **Header** - Sticky navigation with logo
2. **Hero** - Full-screen slider with call-to-action buttons
3. **About** - Company introduction with features
4. **Guarantee** - 100% satisfaction guarantee banner
5. **Advantages** - 4 key benefits with icons
6. **Services** - 6 service cards with images
7. **Stats** - Counter animation for key metrics
8. **Testimonials** - Client feedback slider
9. **Contact** - Address, phone, hours, social links
10. **Footer** - Copyright and legal links

## 🔧 JavaScript Features

- Sticky header on scroll
- Hero slider with auto-play and navigation
- Testimonials slider with dots navigation
- Mobile hamburger menu
- Smooth scroll navigation
- Active nav link highlighting
- Back-to-top button
- Scroll-triggered animations
- Stats counter animation

## 📦 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Opera (latest)

## 📄 License

This template is sold under a standard commercial license. You may use it for:
- Personal projects
- Client projects
- Commercial websites

You may NOT:
- Resell or redistribute the template
- Include in other templates/products for resale

## 🆘 Support

For questions or support, contact us through our website: [https://templatelayer.com/](https://templatelayer.com/)

---

Template originally created by [TemplateLayer](https://templatelayer.com)
