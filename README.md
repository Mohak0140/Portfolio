# Software Engineer Portfolio

A cutting-edge portfolio website with software engineering theme, 3D effects, horizontal scrolling, and terminal-inspired design - perfect for showcasing your coding skills and landing that dream internship!

## ✨ Features

### 💻 Software Engineering Theme
- Terminal-inspired design with command line aesthetics
- Neon green color scheme with cyberpunk vibes
- Code syntax highlighting and monospace fonts
- Binary code animations and matrix effects
- Glitch effects and tech-inspired elements

### 🚀 3D Effects & Animations
- Three.js powered 3D particle background with neon colors
- Floating wireframe geometric shapes
- GSAP scroll-triggered animations
- Horizontal scrolling sections for immersive experience
- Interactive terminal-style elements

### 📱 Responsive Design
- Mobile-first approach
- Works on all devices (desktop, tablet, mobile)
- Adaptive navigation with hamburger menu
- Optimized for different screen sizes

### 🎯 Interactive Features
- Horizontal scrolling skills and projects sections
- Terminal-style command line interface
- Animated skill bars with neon effects
- Counting animations for statistics
- Hover effects with neon glows and micro-interactions
- Matrix rain effects and binary code animations
- Contact form with cyberpunk styling

### ⚡ Performance Optimized
- Fast loading with optimized assets
- Debounced scroll events
- Lazy loading for images
- Efficient animations

## 🛠️ Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Modern styling with CSS Grid, Flexbox, and custom properties
- **JavaScript** - Interactive functionality
- **Three.js** - 3D graphics and animations
- **GSAP** - Professional animations
- **Font Awesome** - Icons
- **Google Fonts** - Typography (Inter)

## 🚀 Quick Start

1. **Clone or Download** the files to your local machine
2. **Open `index.html`** in your web browser
3. **Customize** the content with your information
4. **Deploy** to your preferred hosting platform

## 📝 Customization Guide

### Personal Information
Replace the placeholder content in `index.html`:

```html
<!-- Update these sections with your information -->
<span class="hero-name">Your Name</span>
<p class="hero-description">Your description here...</p>
<img src="your-photo.jpg" alt="Your Name" id="avatar-img">
```

### Skills Section
Modify the skills in the HTML and adjust the skill levels:

```html
<div class="skill-level" data-level="90"></div> <!-- Change the percentage -->
```

### Projects
Update the project cards with your actual projects:

```html
<div class="project-card">
    <div class="project-image">
        <img src="your-project-image.jpg" alt="Project Name">
    </div>
    <div class="project-content">
        <h3>Your Project Name</h3>
        <p>Your project description...</p>
        <div class="project-tech">
            <span class="tech-tag">Technology</span>
        </div>
    </div>
</div>
```

### Contact Information
Update your contact details:

```html
<div class="contact-item">
    <i class="fas fa-envelope"></i>
    <span>your.email@example.com</span>
</div>
```

### Colors and Styling
Customize the color scheme in `styles.css`:

```css
:root {
    --primary-color: #6366f1;        /* Main brand color */
    --secondary-color: #f59e0b;      /* Accent color */
    --gradient-primary: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
}
```

## 📁 File Structure

```
portfolio/
├── index.html          # Main HTML file
├── styles.css          # CSS styles
├── script.js           # JavaScript functionality
└── README.md           # Documentation
```

## 🎨 Sections Overview

### 1. Hero Section
- Animated 3D background
- Professional avatar with floating icons
- Call-to-action buttons
- Scroll indicator

### 2. About Section
- Personal introduction
- Education and focus areas
- Animated statistics counters

### 3. Skills Section
- Categorized skills (Frontend, Backend, Tools)
- Animated progress bars
- Technology icons

### 4. Projects Section
- Featured project showcase
- Hover effects and overlays
- Technology tags
- Links to live demos and code

### 5. Contact Section
- Contact form with validation
- Social media links
- Contact information

## 🔧 Advanced Customization

### Adding New Animations
Use GSAP for custom animations:

```javascript
gsap.fromTo('.your-element', 
    { opacity: 0, y: 50 },
    {
        opacity: 1,
        y: 0,
        duration: 1,
        scrollTrigger: {
            trigger: '.your-element',
            start: 'top 80%'
        }
    }
);
```

### Modifying 3D Effects
Customize the Three.js background in `script.js`:

```javascript
// Change particle count
const particlesCount = 1000; // Increase/decrease for more/fewer particles

// Change colors
const particlesMaterial = new THREE.PointsMaterial({
    color: '#your-color',
    size: 0.005
});
```

## 📱 Browser Support

- Chrome (recommended)
- Firefox
- Safari
- Edge
- Mobile browsers

## 🚀 Deployment Options

### GitHub Pages
1. Push your code to a GitHub repository
2. Go to Settings → Pages
3. Select source branch (usually `main`)
4. Your site will be available at `username.github.io/repository-name`

### Netlify
1. Drag and drop your folder to [netlify.com](https://netlify.com)
2. Your site will be deployed instantly with a custom URL

### Vercel
1. Import your GitHub repository to [vercel.com](https://vercel.com)
2. Deploy with automatic builds

## 💡 Tips for Internship Applications

1. **Customize Content**: Replace all placeholder content with your actual information
2. **Add Real Projects**: Showcase your best work with live demos and GitHub links
3. **Update Skills**: Reflect your current skill levels accurately
4. **Professional Photo**: Use a high-quality, professional headshot
5. **Contact Information**: Ensure all contact details are current and professional
6. **Performance**: Test the site on different devices and browsers
7. **SEO**: Update the page title and meta descriptions

## 🐛 Troubleshooting

### Common Issues

**3D effects not working:**
- Ensure Three.js is loaded properly
- Check browser console for errors
- Try a different browser

**Animations not smooth:**
- Check if GSAP is loaded
- Reduce particle count for better performance
- Test on a faster device

**Mobile responsiveness issues:**
- Test on actual devices
- Use browser developer tools
- Check CSS media queries

## 📞 Support

If you need help customizing the portfolio or encounter any issues:

1. Check the browser console for error messages
2. Verify all CDN links are working
3. Test on different browsers
4. Ensure all files are in the same directory

## 🔄 Updates and Maintenance

- Regularly update your projects and skills
- Keep contact information current
- Test the site periodically on different devices
- Update CDN links if they become outdated

## 📄 License

This portfolio template is free to use for personal and commercial projects. Attribution is appreciated but not required.

---

**Good luck with your internship applications! 🚀**

Remember to customize this portfolio with your unique personality and showcase your best work. The modern design and interactive features will help you stand out from other candidates.