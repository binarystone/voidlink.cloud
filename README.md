# VoidLink

A modern, responsive website template built with HTML, CSS, and JavaScript featuring space-themed animations.

## Features

- 🎨 Modern, clean design with gradient accents
- 📱 Fully responsive (mobile, tablet, desktop)
- ⚡ Smooth animations and transitions
- 🚀 Fast loading and optimized
- 🌌 Space-themed background with void clouds, lightning effects, and spaceship
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

### GitHub Pages (Recommended)

1. Fork or clone this repository
2. Go to repository Settings > Pages
3. Select "Deploy from a branch"
4. Choose your branch and `/ (root)` folder
5. Save and wait for deployment
6. Your site will be available at `https://username.github.io/repository-name`

### Other Hosting Options

#### **Netlify** (Free & Easy)
1. Go to [netlify.com](https://www.netlify.com)
2. Sign up or log in
3. Drag and drop your project folder onto Netlify's dashboard
4. Deploy automatically

#### **Vercel** (Free & Fast)
1. Go to [vercel.com](https://vercel.com)
2. Sign up with GitHub
3. Import your repository
4. Deploy automatically

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

### Space Animation
The space animation includes:
- Twinkling stars background
- Drifting void clouds (nebula effects)
- Random lightning/electrostatic discharge
- Flying spaceship with engine trail

To modify the animation, edit the CSS classes starting with `.space-container`, `.stars`, `.void-cloud`, `.lightning`, and `.spaceship`.

### Add Pages
1. Create new HTML files (e.g., `about.html`)
2. Link to them from the navigation
3. Reuse the same CSS and JS files

## Project Structure

```
project/
├── index.html      # Main HTML file
├── styles.css      # All styles
├── script.js       # JavaScript functionality
└── README.md       # This file
```

## License

Feel free to use this template for your own projects!
