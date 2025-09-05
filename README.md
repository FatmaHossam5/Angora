# Angora - Professional Web Design Agency

A modern, responsive website for Angora, a creative digital agency specializing in web design, branding, and development services.

## 🌟 Features

### Design & User Experience
- **Modern Hero Section** with dynamic carousel and compelling call-to-action buttons
- **Responsive Design** optimized for all devices (mobile, tablet, desktop)
- **Dynamic Navigation** with scroll-triggered background changes and smooth animations
- **Interactive Team Cards** with hover effects and social media integration
- **Enhanced Contact Form** with real-time validation and loading states
- **Smooth Scrolling** navigation and scroll-to-top functionality

### Performance Optimizations
- **Fast Loading** with optimized image lazy loading and critical CSS
- **SEO Optimized** with proper meta tags and semantic HTML structure
- **Progressive Enhancement** with modern web standards and fallbacks
- **Accessibility Compliant** following WCAG 2.1 guidelines
- **Cross-Browser Compatible** tested across major browsers

### Technical Features
- **CSS Grid & Flexbox** for modern layouts
- **Custom CSS Variables** for consistent theming
- **Intersection Observer** for scroll-triggered animations
- **Performance Monitoring** with built-in metrics
- **Mobile-First Approach** with responsive breakpoints

## 🚀 Quick Start

1. **Clone the repository**
   ```bash
   git clone https://github.com/FatmaHossam5/angora.git
   cd angora
   ```

2. **Open in browser**
   ```bash
   # Simply open index.html in your preferred browser
   open index.html
   ```

3. **For development with live server**
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js
   npx serve .
   ```

## 📁 Project Structure

```
Angora/
├── index.html              # Main HTML file
├── css/
│   ├── style.css          # Custom styles
│   ├── bootstrap.min.css  # Bootstrap framework
│   └── all.min.css        # Font Awesome icons
├── js/
│   └── bootstrap.bundle.min.js
├── images/
│   ├── slideshow-*.jpg    # Hero carousel images
│   ├── member-*.jpg       # Team member photos
│   ├── client-*.png       # Client testimonial avatars
│   └── ...                # Other assets
├── webfonts/              # Font files
└── README.md
```

## 🎨 Customization

### Colors
The project uses CSS custom properties for easy theming:

```css
:root {
    --main-color: #f25454;     /* Primary brand color */
    --spacing-xs: 0.5rem;      /* Small spacing */
    --spacing-sm: 1rem;        /* Medium spacing */
    --spacing-md: 2rem;        /* Large spacing */
    --spacing-lg: 3rem;        /* Extra large spacing */
    --spacing-xl: 4rem;        /* Maximum spacing */
}
```

### Fonts
The project uses **Poppins** from Google Fonts for modern typography:
- Font weights: 300, 400, 600, 700, 900
- Optimized loading with `font-display: swap`

### Images
- **Hero Images**: 1920x1080px recommended
- **Team Photos**: 300x400px recommended
- **Client Avatars**: 100x100px recommended
- All images support lazy loading for better performance

## 📱 Responsive Breakpoints

- **Mobile**: < 576px
- **Small Devices**: 576px - 767px
- **Tablets**: 768px - 991px
- **Desktop**: 992px - 1199px
- **Large Desktop**: ≥ 1200px

## 🔧 Browser Support

- **Chrome**: Latest 2 versions
- **Firefox**: Latest 2 versions
- **Safari**: Latest 2 versions
- **Edge**: Latest 2 versions
- **Mobile Browsers**: iOS Safari, Chrome Mobile

## ⚡ Performance Features

- **Image Optimization**: Lazy loading for below-the-fold content
- **CSS Optimization**: Critical CSS loading and non-critical CSS deferring
- **JavaScript**: Deferred loading and performance monitoring
- **Animations**: Hardware-accelerated with `will-change` properties
- **Reduced Motion**: Respects user preferences for motion sensitivity

## 🎯 SEO Features

- Semantic HTML5 structure
- Open Graph meta tags for social sharing
- Proper heading hierarchy (H1-H6)
- Alt text for all images
- Meta descriptions and keywords
- Schema markup ready structure

## 🛠️ Development

### Prerequisites
- Modern web browser
- Text editor (VS Code recommended)
- Basic knowledge of HTML, CSS, and JavaScript

### Customization Guide

1. **Update Content**: Modify text content in `index.html`
2. **Change Colors**: Update CSS variables in `css/style.css`
3. **Replace Images**: Add new images to `images/` folder
4. **Modify Sections**: Edit HTML structure as needed
5. **Add Features**: Extend JavaScript functionality

### Performance Tips
- Compress images before adding to the project
- Minify CSS and JavaScript for production
- Use WebP format for better image compression
- Consider implementing a CDN for static assets


## 🙏 Credits

- **Bootstrap**: Responsive framework
- **Font Awesome**: Icon library  
- **Google Fonts**: Poppins typography
- **Intersection Observer**: Modern scroll animations
- **CSS Grid & Flexbox**: Modern layout techniques

---

**Angora** - Building great brands through exceptional digital experiences.