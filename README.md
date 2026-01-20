# VoidLink Website

A modern, responsive website for voidlink.cloud built with HTML, CSS, and JavaScript.

## Features

- 🎨 Modern, clean design with gradient accents
- 📱 Fully responsive (mobile, tablet, desktop)
- ⚡ Smooth animations and transitions
- 🚀 Fast loading and optimized
- ♿ Accessible markup and semantic HTML

## Getting Started

### Local Development

1. Clone or download this repository
2. Open `index.html` in your web browser
3. For a local server (recommended), you can use:

```bash
# Using Python 3
python3 -m http.server 8000

# Using Node.js (with npx)
npx serve

# Using PHP
php -S localhost:8000
```

Then visit `http://localhost:8000` in your browser.

## Deployment

### Option 1: Static Hosting Services (Recommended)

The easiest way to deploy is using static hosting services:

#### **Netlify** (Free & Easy)
1. Go to [netlify.com](https://www.netlify.com)
2. Sign up or log in
3. Drag and drop your project folder onto Netlify's dashboard
4. Configure your domain (voidlink.cloud) in the site settings

#### **Vercel** (Free & Fast)
1. Go to [vercel.com](https://vercel.com)
2. Sign up with GitHub
3. Import your repository
4. Deploy automatically
5. Add your custom domain in project settings

#### **GitHub Pages** (Free)
1. Push your code to a GitHub repository
2. Go to repository Settings > Pages
3. Select your branch and folder
4. Add custom domain in repository settings

### Option 2: Traditional Web Hosting

1. Upload all files to your web hosting provider
2. Ensure `index.html` is in the root directory
3. Point your domain (voidlink.cloud) to your hosting provider's nameservers

### Domain Configuration

After deploying, configure your domain:

1. **Add DNS Records:**
   - If using Netlify/Vercel: They'll provide DNS settings
   - Add an A record or CNAME pointing to your hosting provider

2. **SSL Certificate:**
   - Most modern hosting services provide free SSL certificates
   - Enable HTTPS for your domain

3. **Test:**
   - Visit `voidlink.cloud` to verify everything works

## Customization

### Colors
Edit the CSS variables in `styles.css`:
```css
:root {
    --primary-color: #6366f1;
    --secondary-color: #8b5cf6;
    /* ... more variables */
}
```

### Content
- Edit `index.html` to change text and sections
- Update the contact form action URL (currently just shows an alert)
- Modify the logo text in the navbar

### Add Pages
1. Create new HTML files (e.g., `about.html`)
2. Link to them from the navigation
3. Reuse the same CSS and JS files

## Project Structure

```
voidlink.cloud/
├── index.html      # Main HTML file
├── styles.css      # All styles
├── script.js       # JavaScript functionality
└── README.md       # This file
```

## Next Steps

Consider adding:
- Backend API for contact form submissions
- Blog functionality
- More interactive features
- Analytics (Google Analytics, etc.)
- SEO optimization (meta tags, Open Graph, etc.)

## License

Feel free to use this template for your own projects!
