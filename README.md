# Itzfizz Assignment — Scroll-Driven Hero Section Animation

A premium scroll-driven hero section with smooth GSAP animations, inspired by modern automotive landing pages.

## 🔗 Live Demo

**[View Live Demo](https://itzfizz-assignment.vercel.app/)**

## 📖 Project Overview

This project recreates a hero section animation featuring:
- **Scroll-driven animations** tied to scroll progress (not time-based)
- **Smooth initial load animations** with staggered reveals
- **Premium motion quality** using GSAP and transform properties
- **Responsive design** across desktop, tablet, and mobile devices

## ✨ Features

### 1. Hero Section Layout
- Full-screen hero section occupying the first viewport
- Letter-spaced headline: **W E L C O M E  I T Z F I Z Z**
- Impact metrics/statistics with animated counters
- Two-column layout on desktop (text left, visual right)

### 2. Initial Load Animation
- Custom loading screen with progress bar
- Staggered letter reveal for logo
- Smooth fade-in for headlines with slide-up effect
- Statistics animate in one-by-one with subtle delays
- Premium, fluid motion throughout

### 3. Scroll-Based Animation (Core Feature)
- Hero section responds dynamically to page scroll
- Visual elements move smoothly based on scroll position
- Animation tied to scroll progress using GSAP ScrollTrigger
- Natural easing and interpolation for fluid motion

### 4. Motion & Performance
- Optimized animations using `transform` properties (translate, scale, rotate)
- Hardware-accelerated CSS animations
- Minimal layout reflows for smooth 60fps performance
- Custom cursor with hover effects

## 🛠️ Tech Stack

| Technology | Purpose |
|------------|---------|
| **HTML5** | Semantic markup structure |
| **CSS3** | Styling, animations, responsive design |
| **JavaScript** | Interactivity and animation logic |
| **GSAP** | Advanced scroll and intro animations |
| **ScrollTrigger** | Scroll-based animation triggers |

## 📁 Project Structure

```
itzfiz/
├── index.html      # Main HTML file with embedded CSS & JS
└── README.md       # Project documentation
```

## 🚀 Getting Started

### Local Development

1. Clone the repository:
   ```bash
   git clone https://github.com/BALAJIBHARGAV6/Itzfizz-assignment.git
   ```

2. Navigate to the project folder:
   ```bash
   cd Itzfizz-assignment
   ```

3. Open `index.html` in your browser or use a local server:
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js
   npx serve
   ```

4. Visit `http://localhost:8000` in your browser

## 🎯 Key Implementation Details

### GSAP Animations
- **ScrollTrigger** for scroll-based animations
- **Timeline animations** for sequenced intro effects
- **Stagger effects** for multiple element animations
- **Custom easing** for natural motion feel

### Performance Optimizations
- GPU-accelerated transforms only
- `will-change` hints for animated elements
- Debounced scroll handlers
- Optimized SVG graphics

### Responsive Design
- Mobile-first approach
- Fluid typography using `clamp()`
- Adaptive layouts for all screen sizes
- Touch-friendly interactions

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## 📄 License

This project is created as part of the Itzfizz assignment.

## 👤 Author

**Balaji Bhargav**
- GitHub: [@BALAJIBHARGAV6](https://github.com/BALAJIBHARGAV6)

---

*Built with ❤️ for Itzfizz*
