# Mayank Saxena - Portfolio Website

A beautiful, modern, and responsive portfolio website showcasing my skills, experience, and achievements as a Backend Developer.

## 🌟 Features

- **Modern Design**: Clean, professional design with beautiful gradients and animations
- **Responsive**: Fully responsive design that works on all devices
- **Smooth Animations**: AOS (Animate On Scroll) library for engaging animations
- **Interactive Elements**: Hover effects, smooth scrolling, and interactive components
- **Contact Form**: Functional contact form with validation
- **Performance Optimized**: Fast loading with optimized assets
- **SEO Friendly**: Proper meta tags and semantic HTML

## 🚀 Live Demo

[View Live Portfolio](https://yourusername.github.io/portfolio)

## 📁 Project Structure

```
portfolio/
├── index.html          # Main HTML file
├── styles.css          # CSS styles and animations
├── script.js           # JavaScript functionality
├── README.md           # This file
└── MayankSaxena_Resume.tex  # Original LaTeX resume
```

## 🛠️ Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Modern styling with Flexbox and Grid
- **JavaScript**: Interactive functionality
- **AOS Library**: Scroll animations
- **Font Awesome**: Icons
- **Google Fonts**: Inter font family

## 📱 Sections

1. **Hero Section**: Introduction with animated code display
2. **About**: Personal information and key statistics
3. **Experience**: Timeline of work experience
4. **Skills**: Technical skills organized by category
5. **Publications**: Research papers and publications
6. **Contact**: Contact form and social links

## 🚀 Deployment Options

### Option 1: GitHub Pages (Recommended - FREE)

1. **Create a GitHub Repository**:
   ```bash
   # Initialize git repository
   git init
   git add .
   git commit -m "Initial portfolio commit"
   ```

2. **Push to GitHub**:
   ```bash
   # Create a new repository on GitHub named 'portfolio' or 'yourusername.github.io'
   git remote add origin https://github.com/yourusername/portfolio.git
   git branch -M main
   git push -u origin main
   ```

3. **Enable GitHub Pages**:
   - Go to your repository on GitHub
   - Click on "Settings" tab
   - Scroll down to "GitHub Pages" section
   - Select "Deploy from a branch"
   - Choose "main" branch and "/ (root)" folder
   - Click "Save"

4. **Your site will be available at**: `https://yourusername.github.io/portfolio`

### Option 2: Netlify (FREE)

1. **Sign up for Netlify**: Go to [netlify.com](https://netlify.com)

2. **Deploy from Git**:
   - Click "New site from Git"
   - Connect your GitHub account
   - Select your portfolio repository
   - Deploy settings: Build command (leave empty), Publish directory: `/`
   - Click "Deploy site"

3. **Custom Domain** (Optional):
   - Go to "Domain settings"
   - Add your custom domain
   - Follow DNS configuration instructions

### Option 3: Vercel (FREE)

1. **Sign up for Vercel**: Go to [vercel.com](https://vercel.com)

2. **Import Project**:
   - Click "New Project"
   - Import your GitHub repository
   - Vercel will auto-detect it's a static site
   - Click "Deploy"

3. **Your site will be available at**: `https://your-project-name.vercel.app`

### Option 4: Surge.sh (FREE)

1. **Install Surge**:
   ```bash
   npm install --global surge
   ```

2. **Deploy**:
   ```bash
   # Navigate to your project directory
   cd /path/to/your/portfolio
   
   # Deploy
   surge
   ```

3. **Follow the prompts** to create an account and choose a domain

## 🔧 Customization

### Update Personal Information

1. **Edit `index.html`**:
   - Update name, email, phone number
   - Change social media links
   - Modify experience details
   - Update skills and publications

2. **Customize Colors** (in `styles.css`):
   ```css
   :root {
       --primary-color: #6366f1;
       --secondary-color: #8b5cf6;
       --accent-color: #fbbf24;
   }
   ```

3. **Add/Remove Sections**:
   - Duplicate existing sections
   - Update navigation menu
   - Modify CSS as needed

### Add New Features

- **Blog Section**: Add a blog with markdown support
- **Projects Gallery**: Showcase your projects with images
- **Resume Download**: Add a downloadable PDF version
- **Dark Mode**: Implement theme switching
- **Multi-language**: Add internationalization

## 📊 Performance Optimization

- **Image Optimization**: Use WebP format and compress images
- **Minification**: Minify CSS and JavaScript for production
- **CDN**: Use CDN for external libraries
- **Lazy Loading**: Implement lazy loading for images
- **Caching**: Set proper cache headers

## 🔍 SEO Optimization

- **Meta Tags**: Update title, description, and keywords
- **Open Graph**: Add social media meta tags
- **Structured Data**: Add JSON-LD schema markup
- **Sitemap**: Generate XML sitemap
- **Robots.txt**: Add robots.txt file

## 📧 Contact Form Setup

The current contact form shows a success message. To make it functional:

### Option 1: Formspree (FREE)
1. Sign up at [formspree.io](https://formspree.io)
2. Create a new form
3. Update the form action in `index.html`:
   ```html
   <form action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
   ```

### Option 2: Netlify Forms
1. Add `netlify` attribute to form:
   ```html
   <form netlify>
   ```
2. Deploy to Netlify
3. Forms will be available in Netlify dashboard

### Option 3: EmailJS (FREE)
1. Sign up at [emailjs.com](https://emailjs.com)
2. Configure email service
3. Update JavaScript to use EmailJS API

## 🎨 Design Customization

### Color Scheme
The current design uses a purple-blue gradient theme. You can customize:

```css
/* Primary gradient */
background: linear-gradient(135deg, #6366f1, #8b5cf6);

/* Accent color */
background: linear-gradient(135deg, #fbbf24, #f59e0b);
```

### Typography
The site uses Inter font family. You can change it in `styles.css`:

```css
body {
    font-family: 'Your-Font-Name', sans-serif;
}
```

### Animations
Customize animation durations and effects in `script.js`:

```javascript
AOS.init({
    duration: 1000,  // Animation duration
    easing: 'ease-in-out',  // Animation easing
    once: true,  // Animate only once
});
```

## 🐛 Troubleshooting

### Common Issues

1. **Images not loading**: Check file paths and ensure images exist
2. **Fonts not loading**: Verify Google Fonts link is correct
3. **Animations not working**: Check if AOS library is loaded
4. **Mobile menu not working**: Ensure JavaScript is properly loaded

### Browser Compatibility

- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+

## 📈 Analytics

Add Google Analytics to track visitors:

1. Create a Google Analytics account
2. Get your tracking ID
3. Add this code before `</head>` in `index.html`:

```html
<!-- Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=GA_TRACKING_ID"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'GA_TRACKING_ID');
</script>
```

## 🤝 Contributing

Feel free to fork this project and customize it for your own portfolio!

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 📞 Support

If you have any questions or need help with deployment, feel free to reach out!

---

**Made with ❤️ by Mayank Saxena** 