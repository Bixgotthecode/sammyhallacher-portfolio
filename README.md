# Engineering Portfolio

A modern, responsive portfolio website showcasing engineering projects, skills, and experience. Built with HTML5, CSS3, and JavaScript, designed to be hosted on GitHub Pages.

## Features

- **Responsive Design**: Optimized for all devices (desktop, tablet, mobile)
- **Modern UI/UX**: Clean, professional design with smooth animations
- **Interactive Elements**: Smooth scrolling, hover effects, and form validation
- **GitHub Pages Ready**: Configured for easy deployment on GitHub Pages
- **SEO Optimized**: Proper meta tags and semantic HTML structure
- **Accessibility**: WCAG compliant with proper ARIA labels and keyboard navigation

## Sections

- **Hero**: Introduction with call-to-action buttons
- **About**: Personal information and statistics
- **Projects**: Featured projects with technology tags and links
- **Skills**: Technical skills organized by category
- **Contact**: Contact form and social media links

## Technologies Used

- HTML5
- CSS3 (Grid, Flexbox, Animations)
- JavaScript (ES6+)
- Font Awesome Icons
- Google Fonts (Inter)

## Getting Started

### Prerequisites

- A GitHub account
- Basic knowledge of HTML, CSS, and JavaScript (for customization)

### Installation

1. **Fork or Clone this repository**
   ```bash
   git clone https://github.com/yourusername/engr_portfolio.git
   cd engr_portfolio
   ```

2. **Customize the content**
   - Edit `index.html` to update personal information
   - Modify `styles.css` to change colors, fonts, or layout
   - Update `script.js` for additional functionality

3. **Deploy to GitHub Pages**
   - Go to your repository settings
   - Scroll down to "Pages" section
   - Select "Deploy from a branch"
   - Choose "main" branch and "/ (root)" folder
   - Click "Save"

4. **Access your portfolio**
   - Your site will be available at: `https://yourusername.github.io/engr_portfolio`

## Customization Guide

### Personal Information

Update the following in `index.html`:

```html
<!-- Update name and title -->
<h1 class="hero-title">Hi, I'm <span class="highlight">Your Name</span></h1>
<h2 class="hero-subtitle">Your Title</h2>

<!-- Update contact information -->
<p>your.email@example.com</p>
<p>linkedin.com/in/yourprofile</p>
<p>github.com/yourusername</p>
```

### Projects

Replace the example projects in the projects section:

```html
<div class="project-card">
    <div class="project-image">
        <i class="fas fa-laptop-code"></i>
    </div>
    <div class="project-content">
        <h3>Your Project Name</h3>
        <p>Project description...</p>
        <div class="project-tech">
            <span class="tech-tag">Technology</span>
        </div>
        <div class="project-links">
            <a href="https://github.com/yourusername/project" class="project-link">
                <i class="fab fa-github"></i> GitHub
            </a>
            <a href="https://yourproject.com" class="project-link">
                <i class="fas fa-external-link-alt"></i> Live Demo
            </a>
        </div>
    </div>
</div>
```

### Skills

Update the skills section with your technologies:

```html
<div class="skill-item">
    <i class="fab fa-python"></i>
    <span>Python</span>
</div>
```

### Colors and Styling

Modify the CSS variables in `styles.css`:

```css
:root {
    --primary-color: #667eea;
    --secondary-color: #764ba2;
    --text-color: #333;
    --background-color: #ffffff;
}
```

## File Structure

```
engr_portfolio/
├── index.html          # Main HTML file
├── styles.css          # CSS styles and responsive design
├── script.js           # JavaScript functionality
├── README.md           # Project documentation
└── .gitignore          # Git ignore file
```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Performance

- Optimized images and assets
- Minified CSS and JavaScript (for production)
- Lazy loading for better performance
- Responsive images

## Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is open source and available under the [MIT License](LICENSE).

## Contact

- **Email**: your.email@example.com
- **LinkedIn**: [Your LinkedIn Profile](https://linkedin.com/in/yourprofile)
- **GitHub**: [Your GitHub Profile](https://github.com/yourusername)

## Acknowledgments

- Font Awesome for the icons
- Google Fonts for the Inter font family
- GitHub Pages for hosting
- The open-source community for inspiration and resources

---

**Note**: Remember to replace all placeholder information with your actual details before deploying!
