# José Bobes - Personal Portfolio

A minimalist, elegant portfolio website showcasing projects in software engineering and research.

## ✨ Features

- **Minimalist Design**: Clean, neutral color palette with typography-focused layout
- **Advanced JavaScript Effects**: Smooth animations inspired by Scriptaculous
  - Cubic bezier easing transitions
  - Intersection Observer API for scroll-triggered animations
  - Subtle parallax effects on mouse movement
  - Staggered card animations
  - Smooth scroll reveal animations
- **Responsive Layout**: Fully optimized for all screen sizes (desktop, tablet, mobile)
- **Fast & Lightweight**: Pure HTML, CSS, and vanilla JavaScript (no dependencies)
- **Professional Navigation**: Direct links to GitHub, Google Scholar, ORCID, and LinkedIn
- **Accessible**: Semantic HTML and keyboard-friendly navigation

## 🚀 Live Demo

**Website**: https://jrbobes.github.io

Deployed automatically on GitHub Pages.

## 📁 File Structure

```
jrbobes.github.io/
├── index.html          # Main portfolio page
├── README.md           # This file
└── virusing/           # Legacy redirect
    └── index.html      # Redirects to hantavirus tracker
```

## 🎨 Design Principles

### Visual Hierarchy
- **Typography-first approach**: Light font weights (300-400) with precise letter-spacing
- **Neutral palette**: Pure blacks, whites, and grays for timeless elegance
- **Whitespace**: Generous spacing for clarity and focus
- **Geometric layout**: Square corners and sharp edges for modern minimalism

### Interactive Elements
- **Smooth transitions**: All interactions use cubic-bezier easing for fluid motion
- **Grayscale images**: Professional aesthetic with subtle color on hover
- **Hover states**: Understated elevation and underline animations
- **Scroll animations**: Elements reveal as they enter the viewport

## 🛠️ Technologies

- **HTML5**: Semantic markup
- **CSS3**: Modern styling with animations and responsive design
- **Vanilla JavaScript**: 
  - Intersection Observer for efficient scroll detection
  - Mouse parallax effects
  - Smooth scroll navigation
  - Reveal animations on scroll

## 📋 Sections

### Navigation
- **Left**: Name and subtitle
- **Right**: Quick links to all professional profiles
  - GitHub
  - Google Scholar
  - ORCID
  - LinkedIn

### Hero
- Large, impactful headline
- Scroll indicator with gentle animation

### About
- Professional image (grayscale with hover effect)
- Bio and expertise overview
- Three focused paragraphs highlighting skills

### Featured Projects
- **Hantavirus Epidemic Tracker**: Real-time epidemiological tracking and visualization
- **Next-gen-somnus**: ML algorithms for sleep recording analysis
- **HITL Cancer Research**: Human-in-the-Loop learning applied to oncology

Each project includes:
- Descriptive image
- Project title and description
- Direct link to project

### Footer
- Copyright information
- Link to GitHub profile

## 🎬 Animation Techniques

1. **Cubic Bezier Easing**: `cubic-bezier(0.4, 0, 0.2, 1)` for professional motion
2. **Intersection Observer**: Efficient viewport-based animations
3. **Scale & Transform**: Subtle growth and movement on interaction
4. **Grayscale Filtering**: Image reveals color on hover
5. **Staggered Delays**: Sequential animation timing for visual flow

## 📱 Responsive Breakpoints

- **Desktop**: 1024px+ (full horizontal navigation)
- **Tablet**: 768px - 1023px (adjusted spacing and sizes)
- **Mobile**: < 768px (vertical navigation, single-column layout)

## ✍️ Customization

### Edit Content
Open `index.html` and modify:
- Navigation links (lines 568-597)
- Hero headline (line 604)
- About section text (lines 622-631)
- Project cards (lines 642-671)
- Footer content (line 678)

### Change Colors
Update CSS variables in the `<style>` section:
```css
:root {
    --primary-dark: #1a1a1a;
    --primary-light: #ffffff;
    --neutral-light: #f5f5f5;
    --accent: #4a4a4a;
}
```

### Modify Images
Replace image URLs in the `<img>` tags:
- About section image (line 618)
- Project card images (lines 643, 653, 663)

## 📄 License

Feel free to use this as a template for your own portfolio!

---

**Made with ❤️ by José Bobes**

For updates and improvements, visit: https://github.com/jrbobes/jrbobes.github.io
