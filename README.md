# 🌊 TidalUI - Modern Landing Page Template

A sleek, fully responsive landing page template built with **HTML5** and **Tailwind CSS**. Designed for startups, creative agencies, and modern software products.

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-3.0+-38bdf8?logo=tailwind-css)

## ✨ Features

* **Fully Responsive:** Looks great on mobile, tablet, and desktop.
* **Sticky Navigation:** Includes a backdrop-blur effect and a smooth mobile slide-over menu.
* **Modern Hero Section:** Split layout with gradient typography and imagery.
* **Feature Grid:** Auto-responsive grid layout with SVG icons.
* **Contact Form:** Clean, styled form inputs (UI only).
* **No Build Step Required:** Uses the Tailwind Play CDN for instant prototyping.

## 🛠 Tech Stack

* **HTML5:** Semantic markup.
* **Tailwind CSS (CDN):** Styled via utility classes.
* **Vanilla JavaScript:** Lightweight script for handling the mobile menu toggle.

## 🚀 Quick Start

Since this project uses the Tailwind CDN, you don't need to install Node.js or run complex build commands to see it work.

1.  **Download** the `index.html` file.
2.  **Open** the file directly in your web browser (Chrome, Safari, Firefox, etc.).
3.  **That's it!** You should see the fully styled website.

> **Note:** An internet connection is required to load the Tailwind CSS library and the Unsplash placeholder images.

## 🎨 Customization

### Changing Colors
This template uses a custom configuration script in the `<head>` to define brand colors. Look for this section in the code to change the theme:

```html
<script>
  tailwind.config = {
    theme: {
      extend: {
        colors: {
          brand: {
            500: '#06b6d4', // Change this hex code for your primary color
            600: '#0891b2',
          },
          // ...
        }
      }
    }
  }
</script>
