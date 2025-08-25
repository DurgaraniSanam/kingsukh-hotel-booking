# Beautiful House — Landing Page

A responsive, laptop-wide landing page showcasing a beautiful house with a lush garden and warm ambient lights. Includes a full-bleed hero section with a dimmed background image, accessible typography, and clean, modern styles.

## ✨ Features

- Full-width hero with **cover/contain** options and dim overlay
- Mobile-first, responsive layout
- Smooth scrolling and basic animations
- Accessible color contrast & semantic HTML
- SEO-ready meta tags and Open Graph placeholders
- Easy deploy to GitHub Pages / Netlify / Vercel

## 🗂 Project Structure

root/
├─ index.html
├─ /assets
│ ├─ images/
│ │ ├─ hero-bg.png
│ │ └─ favicon.svg
│ └─ icons/
├─ /css
│ ├─ styles.css
│ └─ utils.css
├─ /js
│ ├─ main.js
│ └─ helpers.js
└─ README.md



> Adjust file names/paths to match your project.

## 🚀 Getting Started

### Option A — Static (no build tools)
1. Clone or download the repo.
2. Place your hero image at: `assets/images/hero-bg.png`.
3. Open `index.html` in your browser, or run a quick server:
   ```bash
   # Python 3
   python -m http.server 8080

   # Node (http-server)
   npx http-server . -p 8080
