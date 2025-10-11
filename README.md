# Lukas - Portfolio Website

A modern, interactive single-page portfolio website showcasing Computer Science projects, skills, and experience.

## 🚀 Features

- **Interactive Particle Background** - Canvas-based floating particles in the hero section that respond to mouse movement
- **3D Flip Cards** - Project cards with smooth 3D flip animation on hover
- **Animated Progress Bars** - Skills section with progress bars that animate on scroll
- **Smooth Scrolling** - Seamless navigation between sections
- **Responsive Design** - Fully optimized for desktop, tablet, and mobile devices
- **Modern UI** - Dark gradient theme with Orbitron font and neon accents
- **Contact Form** - Functional contact form with validation
- **Cursor Trail Effect** - Custom cursor trail for enhanced interactivity (desktop only)
- **Easter Eggs** - Hidden surprises for curious visitors!

## 📁 Project Structure

```
windsurf-project/
├── index.html          # Main HTML file
├── styles.css          # All styling and animations
├── script.js           # JavaScript for interactivity
├── README.md           # This file
└── assets/             # Images and media
    ├── profile.jpg     # Profile picture (placeholder)
    ├── project1.jpg    # Project 1 image (placeholder)
    ├── project2.jpg    # Project 2 image (placeholder)
    └── project3.jpg    # Project 3 image (placeholder)
```

## 🎨 Customization

### Update Personal Information

1. **Hero Section** - Edit the name, bio, and SNHU mention in `index.html` (lines 35-50)
2. **About Section** - Update the about text and stats (lines 75-120)
3. **Projects** - Replace placeholder projects with your own (lines 125-250)
4. **Skills** - Adjust skill percentages and categories (lines 255-320)
5. **Contact Info** - Update email, GitHub, and LinkedIn links (lines 325-360)

### Add Your Images

Place your images in the `assets/` folder:
- `profile.jpg` - Your profile picture (recommended: 400x400px)
- `project1.jpg`, `project2.jpg`, `project3.jpg` - Project screenshots (recommended: 400x300px)

The website includes fallback SVG placeholders if images are missing.

### Color Scheme

Edit CSS variables in `styles.css` (lines 8-16):
```css
:root {
    --primary-gradient: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
    --accent-color: #667eea;
    --highlight-color: #00f2fe;
    /* ... more variables */
}
```

## 🌐 Deployment to GitHub Pages

1. Create a new repository on GitHub
2. Push your code:
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/yourusername/portfolio.git
   git push -u origin main
   ```
3. Go to repository Settings → Pages
4. Select "main" branch and "/" (root) folder
5. Click Save
6. Your site will be live at `https://yourusername.github.io/portfolio/`

## 🛠️ Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Modern styling with Grid, Flexbox, and animations
- **JavaScript (ES6+)** - Interactive features and canvas animations
- **Google Fonts** - Orbitron and Inter fonts
- **Canvas API** - Particle system animation

## 📱 Browser Support

- Chrome (recommended)
- Firefox
- Safari
- Edge
- Mobile browsers (iOS Safari, Chrome Mobile)

## ⚡ Performance

- Optimized particle count for smooth 60fps animation
- Debounced scroll events
- Lazy loading for images
- Minimal dependencies (no frameworks required)
- Lightweight (~50KB total)

## 🎯 Sections

1. **Hero** - Eye-catching introduction with particle animation
2. **About** - Personal bio and statistics
3. **Projects** - 3 featured projects with flip cards
4. **Skills** - Animated progress bars for technical skills
5. **Contact** - Contact form and social links

## 🎨 Design Inspiration

Inspired by modern portfolio sites like LukasCS.com, featuring:
- Dark mode aesthetic
- Gradient accents
- Futuristic typography
- Interactive elements
- Game-like visual effects

## 📝 License

Free to use for personal and commercial projects. Attribution appreciated but not required.

## 🤝 Contributing

Feel free to fork this project and customize it for your own use!

## 📧 Contact

For questions or feedback, reach out via the contact form on the website.

---

**Built with 💜 and ☕ by Lukas**

*"Where code meets creativity"*
