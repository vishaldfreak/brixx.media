# Brixx Media LLC - Website

A modern, professional website for Brixx Media LLC, a media buying agency specializing in Facebook, Google, TikTok, and Native advertising platforms.

## 🚀 Features

- **Responsive Design**: Fully responsive layout that works perfectly on desktop, tablet, and mobile devices
- **Modern UI/UX**: Clean, professional design with smooth animations and transitions
- **Service Showcase**: Dedicated sections for each advertising platform (Facebook, Google, TikTok, Native)
- **Process Overview**: Clear explanation of the media buying process
- **Results Display**: Showcase of key metrics and achievements
- **Contact Form**: Built-in contact form for lead generation
- **SEO Optimized**: Proper meta tags and semantic HTML structure

## 📁 File Structure

```
Brixx.media/
├── index.html          # Main HTML file
├── styles.css          # CSS stylesheet with custom styling
├── script.js           # JavaScript for interactivity
└── README.md          # This file
```

## 🎨 Design Elements

### Color Scheme
- **Primary Color**: #FF6709 (Orange)
- **Secondary Color**: #1a1a2e (Dark Blue)
- **Accent Color**: #16213e (Navy)
- **Background**: #f8f9fa (Light Gray)

### Typography
- **Headers**: Manrope (Bold, 700-800 weight)
- **Body Text**: Open Sans (Regular, 400 weight)
- **Buttons**: DM Sans (Medium, 600 weight)

### Sections
1. **Navigation**: Sticky header with smooth scroll links
2. **Hero Section**: Eye-catching hero with gradient background and key stats
3. **Services**: Four main service cards (Facebook, Google, TikTok, Native)
4. **Process**: Three-step process overview
5. **Results**: Key metrics and achievements
6. **Platforms**: Partner badges and certifications
7. **Contact**: Contact form and company information
8. **Footer**: Brand information and navigation links

## 🛠️ Setup Instructions

1. **Open the website**: Simply open `index.html` in any modern web browser
2. **No build process required**: This is a static HTML/CSS/JS website
3. **Hosting**: Upload all files to any web hosting service

### Recommended Hosting Options
- **Netlify**: Drag and drop the entire folder
- **Vercel**: Connect your repository or upload manually
- **GitHub Pages**: Push to a repository and enable Pages
- **Traditional Hosting**: Upload via FTP to your hosting provider

## ✏️ Customization Guide

### Update Company Information

1. **Address**: Edit the contact section in `index.html` (search for "1309 Coffeen Avenue")
2. **Email**: Update the email address throughout the site (currently set to hello@brixxmedia.com)
3. **Phone**: Add a phone number in the contact section if needed

### Modify Content

- **Hero Title**: Line 36-38 in `index.html`
- **Services**: Lines 87-180 in `index.html`
- **Stats**: Lines 49-61 in `index.html`
- **Results**: Lines 195-216 in `index.html`

### Change Colors

Edit the CSS variables in `styles.css` (lines 11-19):
```css
:root {
    --primary-color: #FF6709;
    --secondary-color: #1a1a2e;
    /* ... other variables ... */
}
```

### Add Analytics

Add your Google Analytics or tracking code in the `<head>` section of `index.html`:
```html
<!-- Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=YOUR-GA-ID"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'YOUR-GA-ID');
</script>
```

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 🔧 Form Integration

The contact form currently logs data to the console. To make it functional:

### Option 1: FormSpree
1. Sign up at [formspree.io](https://formspree.io)
2. Update the form action in `index.html`:
```html
<form action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
```

### Option 2: Netlify Forms
1. Add `netlify` attribute to the form tag:
```html
<form name="contact" method="POST" data-netlify="true">
```

### Option 3: Custom Backend
Update the form submission handler in `script.js` (line 58) to send data to your API endpoint.

## 📊 SEO Optimization

- Meta tags are already included
- Update the following for better SEO:
  - Title tag (line 6 in `index.html`)
  - Meta description (line 7 in `index.html`)
  - Open Graph tags (lines 8-10)
  - Add a sitemap.xml file
  - Add a robots.txt file

## 🚀 Performance Optimization

The website is already optimized with:
- Minimal external dependencies
- Efficient CSS and JavaScript
- Lazy loading potential for images
- Fast load times

For further optimization:
1. Compress and optimize any images you add
2. Minify CSS and JavaScript files for production
3. Enable gzip compression on your server
4. Use a CDN for static assets

## 📞 Support

For questions or customization help, contact:
- **Email**: hello@brixxmedia.com
- **Address**: 1309 Coffeen Avenue STE 1200, Sheridan, WY 82801

## 📝 License

© 2025 Brixx Media LLC. All rights reserved.

---

**Built with modern web standards and best practices for performance and user experience.**

