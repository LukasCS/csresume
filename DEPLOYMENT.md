# 🚀 Deployment Guide

## Quick Start - GitHub Pages

### Step 1: Prepare Your Repository

1. Create a new repository on GitHub (e.g., `portfolio`)
2. Make sure your repository is public (required for free GitHub Pages)

### Step 2: Upload Your Files

**Option A: Using Git Command Line**
```bash
# Navigate to your project folder
cd c:\Users\lukas\CascadeProjects\windsurf-project

# Initialize git repository
git init

# Add all files
git add .

# Commit your changes
git commit -m "Initial portfolio website"

# Add your GitHub repository as remote
git remote add origin https://github.com/YOUR_USERNAME/portfolio.git

# Push to GitHub
git branch -M main
git push -u origin main
```

**Option B: Using GitHub Desktop**
1. Open GitHub Desktop
2. File → Add Local Repository
3. Select your project folder
4. Publish repository to GitHub

**Option C: Manual Upload**
1. Go to your GitHub repository
2. Click "Add file" → "Upload files"
3. Drag and drop all files
4. Commit changes

### Step 3: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click **Settings** (top right)
3. Scroll down to **Pages** (left sidebar)
4. Under "Source", select:
   - Branch: `main`
   - Folder: `/ (root)`
5. Click **Save**
6. Wait 1-2 minutes for deployment
7. Your site will be live at: `https://YOUR_USERNAME.github.io/portfolio/`

### Step 4: Add Your Images

1. Add your images to the `assets/` folder:
   - `profile.jpg` - Your profile picture
   - `project1.jpg` - First project screenshot
   - `project2.jpg` - Second project screenshot
   - `project3.jpg` - Third project screenshot

2. Commit and push the changes:
```bash
git add assets/
git commit -m "Add portfolio images"
git push
```

## Alternative Hosting Options

### Netlify (Recommended for Beginners)

1. Go to [netlify.com](https://www.netlify.com/)
2. Sign up with GitHub
3. Click "New site from Git"
4. Select your repository
5. Click "Deploy site"
6. Your site is live! (with custom domain support)

**Advantages:**
- Automatic deployments on push
- Free SSL certificate
- Custom domain support
- Faster than GitHub Pages

### Vercel

1. Go to [vercel.com](https://vercel.com/)
2. Sign up with GitHub
3. Import your repository
4. Click "Deploy"
5. Done!

**Advantages:**
- Instant deployments
- Excellent performance
- Free SSL and custom domains

### Traditional Web Hosting

Upload via FTP to any web host:
1. Connect to your hosting via FTP client (FileZilla, etc.)
2. Upload all files to `public_html` or `www` folder
3. Access via your domain

## Customization Checklist

Before deploying, make sure to update:

- [ ] Name in hero section
- [ ] Bio and description
- [ ] SNHU mention (if applicable)
- [ ] Upcoming projects list
- [ ] About section text
- [ ] Age and personal details
- [ ] Project cards (titles, descriptions, tech stack)
- [ ] Skills and percentages
- [ ] Contact information (email, GitHub, LinkedIn)
- [ ] Profile image
- [ ] Project images
- [ ] Footer text
- [ ] Page title and meta description

## Testing Before Deployment

1. **Local Testing:**
   - Open `index.html` in your browser
   - Test all links and animations
   - Check responsive design (resize browser)
   - Test contact form

2. **Validation:**
   - HTML: [validator.w3.org](https://validator.w3.org/)
   - CSS: [jigsaw.w3.org/css-validator](https://jigsaw.w3.org/css-validator/)

3. **Performance:**
   - Test on [PageSpeed Insights](https://pagespeed.web.dev/)
   - Optimize images if needed

## Custom Domain Setup

### For GitHub Pages:

1. Buy a domain (Namecheap, Google Domains, etc.)
2. Add a `CNAME` file to your repository with your domain:
   ```
   yourdomain.com
   ```
3. In your domain registrar, add DNS records:
   - Type: `A`, Host: `@`, Value: `185.199.108.153`
   - Type: `A`, Host: `@`, Value: `185.199.109.153`
   - Type: `A`, Host: `@`, Value: `185.199.110.153`
   - Type: `A`, Host: `@`, Value: `185.199.111.153`
   - Type: `CNAME`, Host: `www`, Value: `YOUR_USERNAME.github.io`

4. In GitHub repository settings → Pages, enter your custom domain
5. Enable "Enforce HTTPS"
6. Wait 24-48 hours for DNS propagation

## Troubleshooting

### Site not loading after deployment
- Wait 2-5 minutes after enabling GitHub Pages
- Check that `index.html` is in the root folder
- Verify branch and folder settings in GitHub Pages

### Images not showing
- Check file paths are correct
- Ensure images are in the `assets/` folder
- Verify image file names match exactly (case-sensitive)
- Push images to GitHub if missing

### Styles not applying
- Clear browser cache (Ctrl+F5)
- Check `styles.css` is in the same folder as `index.html`
- Verify no typos in the `<link>` tag

### JavaScript not working
- Check browser console for errors (F12)
- Ensure `script.js` is in the same folder
- Verify the `<script>` tag is before `</body>`

## Performance Optimization

### Image Optimization
```bash
# Compress images before uploading
# Recommended tools:
# - TinyPNG (tinypng.com)
# - Squoosh (squoosh.app)
# - ImageOptim (Mac)
```

### Enable Caching
Add a `.htaccess` file (for Apache servers):
```apache
<IfModule mod_expires.c>
  ExpiresActive On
  ExpiresByType image/jpg "access plus 1 year"
  ExpiresByType image/jpeg "access plus 1 year"
  ExpiresByType image/png "access plus 1 year"
  ExpiresByType text/css "access plus 1 month"
  ExpiresByType application/javascript "access plus 1 month"
</IfModule>
```

## SEO Optimization

1. **Update meta tags** in `index.html`:
```html
<meta name="description" content="Your custom description">
<meta name="keywords" content="portfolio, web developer, game developer">
<meta property="og:title" content="Your Name - Portfolio">
<meta property="og:description" content="Your description">
<meta property="og:image" content="assets/preview.jpg">
```

2. **Add a sitemap.xml**
3. **Submit to Google Search Console**
4. **Add Google Analytics** (optional)

## Support

If you encounter issues:
1. Check the browser console (F12) for errors
2. Validate your HTML and CSS
3. Review the README.md for common solutions
4. Check GitHub Pages documentation

---

**Good luck with your deployment! 🚀**
