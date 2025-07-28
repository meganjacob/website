# Personal Portfolio Website

A modern, responsive personal portfolio website built with HTML, CSS, and JavaScript. Perfect for hosting on GitHub Pages.

## Features

- 🎨 **Modern & Aesthetic Design** - Clean, professional layout with eye-catching elements
- 📱 **Fully Responsive** - Works perfectly on all devices
- ⚡ **Fast & Lightweight** - Optimized for performance
- 🎯 **Multiple Sections** - Intro, About, Experience, Projects, Achievements, Gallery
- 🌟 **Interactive Elements** - Smooth animations, hover effects, and transitions
- 📸 **Image Gallery** - Lightbox functionality for viewing images
- 📊 **Statistics Display** - Animated counters and progress indicators
- 🎭 **Creative Elements** - Floating animations, gradient text, and parallax effects

## Sections Included

1. **Hero Section** - Introduction with profile picture and key statistics
2. **About Section** - Personal description and skills
3. **Work Experience** - Timeline-based experience showcase
4. **Projects** - Portfolio of work with technology tags
5. **Achievements** - Awards and recognition
6. **Image Gallery** - Photo grid with lightbox functionality
7. **Contact** - Contact information and social links

## Customization Guide

### 1. Personal Information

Edit the following in `index.html`:

- **Name**: Replace "Your Name" throughout the file
- **Profile Picture**: Update the image URL in the hero section
- **Contact Information**: Update email, phone, and location
- **Social Links**: Add your actual social media URLs

### 2. Content Updates

#### Hero Section
```html
<h1 class="hero-title">
    <span class="gradient-text">Hello, I'm</span><br>
    Your Name
</h1>
<p class="hero-subtitle">Your Title</p>
<p class="hero-description">Your description here</p>
```

#### Statistics
```html
<div class="stat">
    <span class="stat-number">5+</span>
    <span class="stat-label">Years Experience</span>
</div>
```

#### Skills
```html
<div class="skill-tags">
    <span class="skill-tag">JavaScript</span>
    <span class="skill-tag">React</span>
    <!-- Add your skills -->
</div>
```

### 3. Work Experience

Update the timeline items in the experience section:

```html
<div class="timeline-item">
    <div class="timeline-marker"></div>
    <div class="timeline-content">
        <div class="timeline-header">
            <h3>Your Job Title</h3>
            <span class="company">Company Name</span>
            <span class="duration">2022 - Present</span>
        </div>
        <p>Job description</p>
        <div class="achievements">
            <span class="achievement">• Achievement 1</span>
            <span class="achievement">• Achievement 2</span>
        </div>
    </div>
</div>
```

### 4. Projects

Update the project cards with your actual projects:

```html
<div class="project-card">
    <div class="project-image">
        <img src="project-image-url" alt="Project Name">
        <div class="project-overlay">
            <div class="project-links">
                <a href="live-url" class="project-link"><i class="fas fa-external-link-alt"></i></a>
                <a href="github-url" class="project-link"><i class="fab fa-github"></i></a>
            </div>
        </div>
    </div>
    <div class="project-content">
        <h3>Project Name</h3>
        <p>Project description</p>
        <div class="project-tech">
            <span class="tech-tag">Technology 1</span>
            <span class="tech-tag">Technology 2</span>
        </div>
    </div>
</div>
```

### 5. Achievements

Update the achievement cards:

```html
<div class="achievement-card">
    <div class="achievement-icon">
        <i class="fas fa-trophy"></i>
    </div>
    <h3>Achievement Title</h3>
    <p>Achievement description</p>
    <span class="achievement-year">2023</span>
</div>
```

### 6. Gallery Images

Replace the placeholder images with your own:

```html
<div class="gallery-item">
    <img src="your-image-url" alt="Image Description">
    <div class="gallery-overlay">
        <h3>Image Title</h3>
        <p>Image description</p>
    </div>
</div>
```

### 7. Color Scheme

To change the color scheme, update the CSS variables in `styles.css`:

```css
/* Primary gradient colors */
background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);

/* You can replace with your preferred colors */
background: linear-gradient(135deg, #your-color-1 0%, #your-color-2 100%);
```

## Hosting on GitHub Pages

### Method 1: Direct Upload

1. Create a new repository on GitHub
2. Upload all files (`index.html`, `styles.css`, `script.js`)
3. Go to repository Settings → Pages
4. Select "Deploy from a branch"
5. Choose "main" branch and "/ (root)" folder
6. Click "Save"

### Method 2: Using GitHub CLI

```bash
# Initialize git repository
git init

# Add all files
git add .

# Commit changes
git commit -m "Initial commit"

# Create repository on GitHub
gh repo create your-portfolio --public

# Push to GitHub
git push -u origin main

# Enable GitHub Pages
gh repo edit --enable-pages
```

### Method 3: Using GitHub Desktop

1. Open GitHub Desktop
2. Create new repository
3. Add all files to the repository
4. Commit and push to GitHub
5. Enable GitHub Pages in repository settings

## File Structure

```
your-portfolio/
├── index.html          # Main HTML file
├── styles.css          # CSS styles
├── script.js           # JavaScript functionality
└── README.md           # This file
```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## Performance Features

- Optimized images with proper sizing
- Minimal JavaScript for fast loading
- CSS animations using GPU acceleration
- Responsive images with appropriate formats
- Lazy loading for better performance

## Customization Tips

1. **Images**: Use optimized images (WebP format recommended)
2. **Fonts**: The site uses Inter font from Google Fonts
3. **Icons**: Font Awesome icons are included
4. **Animations**: All animations are CSS-based for performance
5. **SEO**: Update meta tags and descriptions for better SEO

## Troubleshooting

### Common Issues

1. **Images not loading**: Check image URLs and ensure they're accessible
2. **Styles not applying**: Verify CSS file is in the same directory as HTML
3. **JavaScript not working**: Check browser console for errors
4. **Mobile menu not working**: Ensure JavaScript file is properly linked

### Performance Optimization

1. Compress images before uploading
2. Minimize CSS and JavaScript files for production
3. Use CDN for external resources
4. Enable gzip compression on your server

## License

This project is open source and available under the [MIT License](LICENSE).

## Support

If you need help customizing or hosting your portfolio, feel free to:

1. Check the browser console for errors
2. Verify all file paths are correct
3. Ensure all external resources are accessible
4. Test on different browsers and devices

## Credits

- Fonts: [Inter](https://fonts.google.com/specimen/Inter) by Google Fonts
- Icons: [Font Awesome](https://fontawesome.com/)
- Images: [Unsplash](https://unsplash.com/) (placeholder images)

---

**Happy coding! 🚀** 