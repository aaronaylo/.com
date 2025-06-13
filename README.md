# Aaron Aylo - Personal Website

A modern, responsive personal website built with HTML, CSS, and JavaScript featuring smooth animations, mobile-friendly design, and professional styling.

## 🌟 Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Modern UI/UX**: Clean, professional design with smooth animations
- **Interactive Elements**: Hover effects, typing animation, and smooth scrolling
- **Contact Form**: Functional contact form with validation
- **Mobile Navigation**: Collapsible mobile menu
- **Social Links**: Easy access to your social media profiles
- **Fast Loading**: Optimized for performance
- **SEO Friendly**: Proper meta tags and semantic HTML

## 🚀 Quick Start

1. **Clone or Download**: Get the files to your local machine
2. **Customize**: Edit the content to match your information
3. **Deploy**: Upload to your hosting provider or use GitHub Pages

## 📝 Customization Guide

### Personal Information

Edit the following sections in `index.html`:

#### Hero Section
```html
<h1 class="hero-title">
    Hi, I'm <span class="text-gradient">Your Name</span>
</h1>
<p class="hero-subtitle">Your Title Here</p>
<p class="hero-description">
    Your personal description...
</p>
```

#### About Section
- Update the about text
- Modify the statistics (years experience, projects completed, etc.)

#### Skills Section
- Add or remove skill categories
- Update skill tags to match your expertise

#### Projects Section
- Replace placeholder projects with your actual work
- Update project titles, descriptions, and technologies
- Add links to live demos and source code

#### Contact Information
```html
<div class="contact-method">
    <h4>Email</h4>
    <p>your-email@example.com</p>
</div>
```

### Social Media Links

Update social media links in the hero section:
```html
<div class="hero-social">
    <a href="https://github.com/yourusername" class="social-link">
        <i class="fab fa-github"></i>
    </a>
    <!-- Add more social links -->
</div>
```

### Colors and Styling

The website uses CSS custom properties for easy customization. Main colors are defined in `styles.css`:

- Primary gradient: `#667eea` to `#764ba2`
- Text colors: Various shades of gray
- Background: White and light gray

To change colors, update the gradient values throughout the CSS file.

### Adding Your Photo

Replace the avatar placeholder:
1. Add your photo to the project folder
2. Update the `.hero-avatar` section in `index.html`:
```html
<div class="hero-avatar">
    <img src="your-photo.jpg" alt="Your Name">
</div>
```
3. Update the CSS to style your image properly

## 🌐 Deployment Options

### GitHub Pages (Recommended)

1. **Create a Repository**:
   - Go to GitHub and create a new repository
   - Name it `yourusername.github.io` for a user site, or any name for a project site

2. **Upload Files**:
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git remote add origin https://github.com/yourusername/yourusername.github.io.git
   git push -u origin main
   ```

3. **Enable GitHub Pages**:
   - Go to repository Settings
   - Scroll to Pages section
   - Select source: Deploy from a branch
   - Select branch: main
   - Click Save

4. **Access Your Site**:
   - Your site will be available at `https://yourusername.github.io`

### Other Hosting Options

- **Netlify**: Drag and drop the folder to Netlify
- **Vercel**: Connect your GitHub repository
- **Traditional Web Hosting**: Upload files via FTP

## 📱 Mobile Optimization

The website is fully responsive and includes:
- Mobile navigation menu
- Touch-friendly buttons and links
- Optimized images and fonts
- Fast loading on mobile networks

## 🔧 Technical Details

### File Structure
```
personal-website/
├── index.html          # Main HTML file
├── styles.css          # All CSS styles
├── script.js           # JavaScript functionality
└── README.md           # This file
```

### Dependencies
- Font Awesome (CDN) - For icons
- Google Fonts (CDN) - Inter font family

### Browser Support
- Chrome (recommended)
- Firefox
- Safari
- Edge
- Mobile browsers

## 🎨 Customization Tips

### Adding New Sections
1. Add HTML structure to `index.html`
2. Add corresponding CSS styles to `styles.css`
3. Update navigation menu if needed

### Changing Animations
- Modify CSS animations in `styles.css`
- Adjust JavaScript animations in `script.js`
- Use `transition` and `transform` properties for smooth effects

### Form Integration
The contact form currently shows a success message. To make it functional:
1. Sign up for a form service (Formspree, Netlify Forms, etc.)
2. Update the form action and method
3. Modify JavaScript validation as needed

## 📧 Contact Form Setup

### Using Formspree (Recommended)
1. Sign up at [Formspree.io](https://formspree.io)
2. Create a new form
3. Update your HTML form:
```html
<form class="contact-form" action="https://formspree.io/f/your-form-id" method="POST">
```

### Using Netlify Forms
1. Add `data-netlify="true"` to your form tag
2. Deploy to Netlify
3. Forms will automatically work

## 🚀 Performance Optimization

- Images are optimized for web
- CSS and JavaScript are minified for production
- CDN resources for faster loading
- Semantic HTML for better SEO

## 📈 SEO Features

- Proper meta tags
- Semantic HTML structure
- Alt tags for images
- Descriptive page title
- Open Graph tags (add for social sharing)

## 🤝 Contributing

Feel free to submit issues and pull requests to improve the template!

## 📄 License

This project is open source and available under the MIT License.

## 💡 Tips for Success

1. **Keep Content Updated**: Regular updates show you're active
2. **Add Real Projects**: Replace placeholder projects with actual work
3. **Optimize Images**: Use compressed images for faster loading
4. **Test on Multiple Devices**: Ensure it works on all screen sizes
5. **Monitor Analytics**: Use Google Analytics to track visitors

---

**Built with ❤️ for Aaron Aylo**

For questions or support, feel free to reach out! 