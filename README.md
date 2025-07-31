# Modern Portfolio Website

A beautiful, responsive portfolio website built with HTML, CSS, and JavaScript featuring modern design, dark/light theme toggle, and smooth animations.

## Features

- 🎨 **Modern Design**: Clean, professional layout with gradient accents
- 🌙 **Dark/Light Theme**: Toggle between themes with persistent storage
- 📱 **Responsive**: Fully responsive design that works on all devices
- ⚡ **Smooth Animations**: CSS animations and JavaScript interactions
- 🎯 **Interactive Elements**: Hover effects, scroll animations, and more
- 📝 **Contact Form**: Functional contact form with validation
- 🔍 **SEO Optimized**: Semantic HTML structure
- 🚀 **Performance**: Optimized for fast loading

## Sections

1. **Hero Section**: Eye-catching introduction with call-to-action buttons
2. **About Section**: Personal information with statistics
3. **Skills Section**: Organized by categories (Frontend, Backend, Tools)
4. **Projects Section**: Showcase of featured projects
5. **Contact Section**: Contact information and form

## Customization Guide

### Personal Information

Edit the following in `index.html`:

```html
<!-- Update your name -->
<h1 class="hero-title">
    Hi, I'm <span class="highlight">Your Name</span>
</h1>

<!-- Update your title -->
<h2 class="hero-subtitle">Full Stack Developer</h2>

<!-- Update your description -->
<p class="hero-description">
    I create beautiful, functional, and user-centered digital experiences.
    Passionate about clean code and innovative solutions.
</p>

<!-- Update about section content -->
<p>
    I'm a passionate developer with a love for creating innovative digital solutions...
</p>

<!-- Update statistics -->
<div class="stat">
    <h3>3+</h3>
    <p>Years Experience</p>
</div>
```

### Contact Information

Update your contact details in the contact section:

```html
<div class="contact-method">
    <i class="fas fa-envelope"></i>
    <span>your.email@example.com</span>
</div>
<div class="contact-method">
    <i class="fas fa-phone"></i>
    <span>+1 (555) 123-4567</span>
</div>
<div class="contact-method">
    <i class="fas fa-map-marker-alt"></i>
    <span>Your City, Country</span>
</div>
```

### Social Links

Update your social media links:

```html
<div class="social-links">
    <a href="https://github.com/yourusername" class="social-link">
        <i class="fab fa-github"></i>
    </a>
    <a href="https://linkedin.com/in/yourusername" class="social-link">
        <i class="fab fa-linkedin"></i>
    </a>
    <a href="https://twitter.com/yourusername" class="social-link">
        <i class="fab fa-twitter"></i>
    </a>
    <a href="https://instagram.com/yourusername" class="social-link">
        <i class="fab fa-instagram"></i>
    </a>
</div>
```

### Skills

Customize your skills in the skills section:

```html
<div class="skill-category">
    <h3>Frontend</h3>
    <div class="skill-items">
        <div class="skill-item">
            <i class="fab fa-html5"></i>
            <span>HTML5</span>
        </div>
        <!-- Add more skills -->
    </div>
</div>
```

### Projects

Update your projects in the projects section:

```html
<div class="project-card">
    <div class="project-image">
        <i class="fas fa-shopping-cart"></i>
    </div>
    <div class="project-content">
        <h3>E-Commerce Platform</h3>
        <p>A full-stack e-commerce solution with payment integration...</p>
        <div class="project-tech">
            <span>React</span>
            <span>Node.js</span>
            <span>MongoDB</span>
        </div>
        <div class="project-links">
            <a href="https://github.com/yourusername/project" class="project-link">
                <i class="fab fa-github"></i> Code
            </a>
            <a href="https://project-demo.com" class="project-link">
                <i class="fas fa-external-link-alt"></i> Live
            </a>
        </div>
    </div>
</div>
```

## Color Scheme

The website uses CSS variables for easy color customization. Edit the colors in `styles.css`:

```css
:root {
    --primary-color: #6366f1;      /* Main brand color */
    --secondary-color: #8b5cf6;    /* Secondary brand color */
    --accent-color: #06b6d4;       /* Accent color */
    --text-primary: #1f2937;       /* Primary text color */
    --text-secondary: #6b7280;     /* Secondary text color */
    --bg-primary: #ffffff;         /* Primary background */
    --bg-secondary: #f9fafb;       /* Secondary background */
    --bg-tertiary: #f3f4f6;        /* Tertiary background */
    --border-color: #e5e7eb;       /* Border color */
}
```

## Fonts

The website uses the Inter font family. You can change it in `styles.css`:

```css
body {
    font-family: 'Inter', sans-serif;
}
```

To use a different font, update the Google Fonts link in `index.html` and change the font-family in CSS.

## Features Explained

### Theme Toggle
- Click the moon/sun icon in the navigation to toggle between light and dark themes
- Theme preference is saved in localStorage
- Smooth transition between themes

### Mobile Navigation
- Hamburger menu for mobile devices
- Smooth slide-in animation
- Auto-close when clicking navigation links

### Smooth Scrolling
- Navigation links smoothly scroll to sections
- Accounts for fixed navbar height
- Active link highlighting based on scroll position

### Contact Form
- Form validation for required fields and email format
- Success/error notifications
- Simulated form submission (replace with your backend)

### Animations
- Fade-in animations on scroll
- Typing animation for hero title
- Hover effects on cards and buttons
- Parallax effect on hero section

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Performance Tips

1. **Optimize Images**: Replace placeholder icons with optimized images
2. **Minify CSS/JS**: Minify files for production
3. **CDN**: Use CDN for external libraries
4. **Lazy Loading**: Implement lazy loading for images
5. **Caching**: Set appropriate cache headers

## Deployment

### GitHub Pages
1. Push your code to a GitHub repository
2. Go to Settings > Pages
3. Select source branch (usually `main`)
4. Your site will be available at `https://username.github.io/repository-name`

### Netlify
1. Connect your GitHub repository to Netlify
2. Deploy automatically on push to main branch
3. Get a custom domain and SSL certificate

### Vercel
1. Import your GitHub repository to Vercel
2. Automatic deployments on push
3. Custom domain and SSL included

## File Structure

```
portfolio/
├── index.html          # Main HTML file
├── styles.css          # CSS styles and animations
├── script.js           # JavaScript functionality
└── README.md          # This file
```

## Customization Checklist

- [ ] Update personal information (name, title, description)
- [ ] Add your profile picture (replace icon in hero section)
- [ ] Update contact information
- [ ] Add your social media links
- [ ] Customize skills and technologies
- [ ] Add your projects with links
- [ ] Update color scheme if desired
- [ ] Add your own logo/branding
- [ ] Test on different devices
- [ ] Deploy to your preferred platform

## Support

If you need help customizing your portfolio:

1. Check the HTML comments for guidance
2. Review the CSS variables for styling options
3. Test changes in a local development environment
4. Use browser developer tools for debugging

## License

This project is open source and available under the [MIT License](LICENSE).

---

**Happy coding! 🚀** 