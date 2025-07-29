# Apple Site Demo

A responsive Apple-style website showcasing the MacBook Pro 2024. Built with vanilla HTML and CSS.

## 🚀 Features

- **Apple-inspired Design**: Clean, minimalist interface
- **Responsive Layout**: Mobile-first with progressive enhancement
- **Interactive Elements**: Hover effects, dropdown cart, video modal
- **Smooth Animations**: CSS-based fade-in animations
- **No JavaScript Required**: CSS-only interactions

## 🛠️ Tech Stack

- HTML5
- CSS3 (Custom Properties, Flexbox, Grid)
- Font Awesome Icons
- Google Fonts (Open Sans)

## 📁 Project Structure

```
apple-site-demo/
├── index.html          # Main HTML file
├── styles.css          # CSS stylesheet
├── images/             # Project images
└── README.md           # This file
```

## 🚀 Quick Start

1. Clone the repository
2. Open `index.html` in your browser
3. Or serve locally: `python -m http.server 8000`

## 🎨 Design System

### Colors
- Text: `#bbbbbb`
- Background: Dark gradient
- Buttons: Orange to blue gradient
- Cart Badge: Purple `#5120d2`

### Typography
- Font: Open Sans
- Weights: 100, 200, 400, 600
- Responsive sizing

### Breakpoints
- Mobile: < 460px
- Tablet: 460px - 1100px
- Desktop: > 1100px

## 🎯 Components

### Header
- Sticky navigation
- Apple logo and menu
- Cart with dropdown

### Hero Section
- Product showcase
- Call-to-action buttons
- Video modal

### Specs Grid
- Performance metrics
- Responsive layout

### Footer
- Multi-column layout
- Breadcrumbs and legal links

## 🔧 Customization

### Change Colors
```css
:root {
    --text-color: #your-color;
    --primary-color: #your-accent;
}
```

### Add Components
Follow BEM naming:
```css
.new-component { }
.new-component__element { }
```

## 📱 Responsive Design

- Mobile-first approach
- Progressive enhancement
- Touch-friendly interactions
- Optimized typography

## 🌐 Browser Support

- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+

## 📝 Development Notes

- CSS Custom Properties for maintainability
- BEM methodology for scalable CSS
- Mobile-first responsive design
- CSS-only animations for performance

---

**Note**: Demo project for educational purposes. Not affiliated with Apple Inc. 