# Portfolio Website

A modern, responsive portfolio website built with HTML, CSS, and JavaScript. Features a clean design, smooth animations, and mobile-first responsive layout.

## Features

- 🎨 **Modern Design**: Clean, professional aesthetic with smooth animations
- 📱 **Responsive Layout**: Mobile-first design that works on all devices
- 🚀 **Smooth Scrolling**: Navigation with smooth scroll behavior
- 📝 **Contact Form**: Functional contact form with validation
- 🌟 **Animations**: Fade-in effects and hover animations
- 📊 **Skills Display**: Organized skill categories with icons
- 💼 **Project Showcase**: Beautiful project cards with technology tags
- 📱 **Mobile Navigation**: Hamburger menu for mobile devices

## File Structure

```
Portfolio/
├── index.html          # Main HTML file
├── styles.css          # CSS styles and responsive design
├── script.js           # JavaScript functionality
└── README.md           # This file
```

## Quick Start

1. **Open the website**: Simply open `index.html` in your web browser
2. **Local development**: Use a local server for best experience
3. **Customize**: Edit the content in `index.html` to match your information

## Customization Guide

### Personal Information

Update the following sections in `index.html`:

#### Hero Section
```html
<h1 class="hero-title">Hi, I'm <span class="highlight">Your Name</span></h1>
<p class="hero-subtitle">Your Title</p>
<p class="hero-description">Your description here</p>
```

#### About Section
```html
<p>Your personal story and background</p>
<div class="about-stats">
    <div class="stat">
        <h3>Your Number</h3>
        <p>Your Stat</p>
    </div>
    <!-- Add more stats as needed -->
</div>
```

#### Skills
Update the skills in each category:
```html
<div class="skill-item">
    <i class="fab fa-react"></i>
    <span>Your Skill</span>
</div>
```

#### Projects
Replace the project cards with your own:
```html
<div class="project-card">
    <div class="project-image">
        <!-- Add your project image here -->
    </div>
    <div class="project-content">
        <h3>Your Project Name</h3>
        <p>Your project description</p>
        <div class="project-tech">
            <span>Technology 1</span>
            <span>Technology 2</span>
        </div>
        <div class="project-links">
            <a href="your-github-link" class="project-link">
                <i class="fab fa-github"></i> Code
            </a>
            <a href="your-live-link" class="project-link">
                <i class="fas fa-external-link-alt"></i> Live
            </a>
        </div>
    </div>
</div>
```

#### Contact Information
```html
<div class="contact-method">
    <i class="fas fa-envelope"></i>
    <span>your.email@example.com</span>
</div>
<div class="contact-method">
    <i class="fas fa-phone"></i>
    <span>Your Phone Number</span>
</div>
<div class="contact-method">
    <i class="fas fa-map-marker-alt"></i>
    <span>Your Location</span>
</div>
```

#### Social Links
```html
<div class="social-links">
    <a href="your-github" class="social-link"><i class="fab fa-github"></i></a>
    <a href="your-linkedin" class="social-link"><i class="fab fa-linkedin"></i></a>
    <a href="your-twitter" class="social-link"><i class="fab fa-twitter"></i></a>
    <a href="your-instagram" class="social-link"><i class="fab fa-instagram"></i></a>
</div>
```

### Styling

#### Colors
Update the color scheme in `styles.css`:
```css
:root {
    --primary-color: #2563eb;
    --secondary-color: #fbbf24;
    --text-color: #1f2937;
    --background-color: #f9fafb;
}
```

#### Fonts
Change the font family in `styles.css`:
```css
body {
    font-family: 'Your Font', sans-serif;
}
```

### Adding Images

1. **Profile Picture**: Replace the placeholder in the hero section
2. **Project Images**: Add real project screenshots
3. **Background Images**: Customize section backgrounds

## Browser Support

- ✅ Chrome (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Edge (latest)
- ✅ Mobile browsers

## Performance Features

- **Lazy Loading**: Images load only when needed
- **Smooth Animations**: Optimized with CSS transforms
- **Responsive Images**: Automatically sized for different screens
- **Minimal Dependencies**: Only Font Awesome for icons

## Deployment

### GitHub Pages
1. Push your code to a GitHub repository
2. Go to Settings > Pages
3. Select source branch (usually `main`)
4. Your site will be available at `https://username.github.io/repository-name`

### Netlify
1. Drag and drop your folder to Netlify
2. Your site will be deployed instantly
3. Get a custom domain if needed

### Vercel
1. Connect your GitHub repository
2. Deploy automatically on push
3. Get preview deployments for pull requests

## Customization Tips

### Adding New Sections
1. Create a new `<section>` in HTML
2. Add corresponding CSS styles
3. Update navigation if needed

### Changing Layout
- Modify CSS Grid and Flexbox properties
- Adjust breakpoints in media queries
- Update container widths and spacing

### Adding Animations
- Use CSS transitions and transforms
- Implement Intersection Observer for scroll animations
- Add hover effects to interactive elements

## Troubleshooting

### Common Issues

**Navigation not working**: Check that all section IDs match the href attributes in navigation links.

**Styles not loading**: Ensure `styles.css` is in the same directory as `index.html`.

**JavaScript errors**: Check browser console for errors and ensure `script.js` is properly linked.

**Mobile menu not working**: Verify that the hamburger button and mobile menu classes are properly set up.

### Performance Issues

- Optimize images before adding them
- Minimize CSS and JavaScript if needed
- Use web fonts sparingly

## Contributing

Feel free to fork this project and customize it for your needs. If you make improvements, consider sharing them back!

## License

This project is open source and available under the [MIT License](LICENSE).

## Support

If you need help customizing your portfolio:
1. Check the browser console for errors
2. Validate your HTML and CSS
3. Test on different devices and browsers
4. Refer to the customization guide above

---

**Happy coding! 🚀** 