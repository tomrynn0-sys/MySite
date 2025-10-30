# Personal Portfolio Website

A modern, responsive personal portfolio website showcasing coding projects and Python automation scripts. Built with HTML, CSS, and JavaScript, ready for GitHub Pages hosting.

## 🌟 Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Modern UI**: Clean, minimalist design with smooth animations
- **SEO Optimized**: Proper meta tags and semantic HTML structure
- **Fast Loading**: Optimized images and efficient CSS/JS
- **Contact Form**: Functional contact form with validation
- **Project Showcase**: Beautiful project cards with links and descriptions
- **Product Sales**: Ready-to-sell Python automation scripts
- **Interactive Elements**: Smooth scrolling, hover effects, and mobile navigation

## 📁 File Structure

```
portfolio/
├── index.html          # Homepage with hero section and skills
├── projects.html       # Project showcase page
├── products.html       # Python scripts for sale
├── about.html          # About me page
├── contact.html        # Contact form and information
├── styles.css          # Main stylesheet
├── main.js            # Interactive functionality
└── README.md          # This file
```

## 🚀 Quick Start

### 1. Fork and Clone

1. Fork this repository on GitHub
2. Clone your forked repository:
```bash
git clone https://github.com/YOUR_USERNAME/portfolio.git
cd portfolio
```

### 2. Customize Content

Replace placeholder content with your information:

- **Your Name**: Replace "Your Name" throughout all HTML files
- **Email**: Update `your.email@example.com` in contact.html
- **Social Links**: Update GitHub, LinkedIn, and Twitter URLs
- **Projects**: Replace project descriptions and links with your actual projects
- **About**: Update your personal story and experience
- **Images**: Replace placeholder images with your actual photos and screenshots

### 3. Local Testing

Test the website locally before deploying:

```bash
# Using Python 3
python -m http.server 8000

# Using Python 2
python -m SimpleHTTPServer 8000

# Using Node.js
npx serve .
```

Then open `http://localhost:8000` in your browser.

## 📤 GitHub Pages Deployment

### Method 1: Automatic Deployment (Recommended)

1. Push your changes to the main branch:
```bash
git add .
git commit -m "Initial portfolio setup"
git push origin main
```

2. Enable GitHub Pages:
   - Go to your repository settings
   - Navigate to "Pages" section
   - Select "Deploy from a branch"
   - Choose "main" branch and "/ (root)" folder
   - Click "Save"

3. Your website will be available at:
   `https://YOUR_USERNAME.github.io/portfolio/`

### Method 2: Manual Deployment

1. Create a `gh-pages` branch:
```bash
git checkout --orphan gh-pages
git rm -rf .
git checkout main -- .
git add .
git commit -m "Initial GitHub Pages deployment"
git push origin gh-pages
```

2. Enable GitHub Pages in repository settings

## 🎨 Customization Guide

### Colors and Styling

The website uses a modern color scheme that can be easily customized in `styles.css`:

- **Primary Color**: `#2563eb` (blue)
- **Secondary Color**: `#1e40af` (dark blue)
- **Text Color**: `#333` (dark gray)
- **Background**: `#fff` (white)

### Images

Replace placeholder images with your own:

1. **Hero Image**: Add your professional photo or workspace image
2. **Project Screenshots**: Replace with actual screenshots of your projects
3. **Product Images**: Create custom graphics for your Python scripts

### Content Updates

1. **Homepage**: Update skills, services, and featured projects
2. **Projects**: Add your actual projects with real links
3. **Products**: Create descriptions for scripts you want to sell
4. **About**: Write your personal story and experience
5. **Contact**: Update contact information and social links

## 🔧 Technical Details

### Technologies Used

- **HTML5**: Semantic markup and modern features
- **CSS3**: Flexbox, Grid, animations, and responsive design
- **JavaScript**: ES6+ with modern DOM manipulation
- **Google Fonts**: Inter font family for clean typography
- **Unsplash**: High-quality placeholder images

### Browser Support

- Chrome 60+
- Firefox 60+
- Safari 12+
- Edge 79+

### Performance Features

- Optimized CSS with minimal unused styles
- Efficient JavaScript with modern ES6+ features
- Responsive images with proper sizing
- Minimal external dependencies

## 📱 Mobile Optimization

The website is fully responsive and includes:

- Mobile-first design approach
- Touch-friendly navigation
- Optimized font sizes for small screens
- Responsive images and layouts
- Smooth mobile interactions

## 🔒 Security Considerations

- Form validation on both client and server side
- No sensitive data exposure
- Secure contact form handling
- Proper input sanitization

## 📈 SEO Features

- Semantic HTML structure
- Proper meta tags
- Open Graph tags for social sharing
- Structured data markup
- Fast loading times
- Mobile-friendly design

## 🤝 Contributing

Feel free to submit issues and pull requests to improve the portfolio template.

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 📞 Support

If you need help with customization or deployment:

1. Check the [GitHub Issues](https://github.com/yourusername/portfolio/issues)
2. Create a new issue with your question
3. Join our community discussions

---

**Built with ❤️ for the developer community**

*This portfolio template is designed to help developers showcase their work effectively while maintaining a professional online presence.*