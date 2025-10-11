# ⚡ Quick Start Guide

Get your portfolio live in 5 minutes!

## 🎯 Step 1: View Locally (30 seconds)

Simply open `index.html` in your web browser:
- **Windows:** Double-click `index.html`
- **Mac:** Right-click → Open With → Browser
- **Or:** Drag `index.html` into your browser window

The site works immediately with placeholder content!

## ✏️ Step 2: Customize Content (2 minutes)

Edit `index.html` and update these key sections:

### Hero Section (Line ~40)
```html
<span class="glitch" data-text="YOUR_NAME">YOUR_NAME</span>
```

### About Section (Line ~80)
```html
<h3>Hello! I'm YOUR_NAME</h3>
<p>Your bio here...</p>
```

### Contact Section (Line ~330)
```html
<p>youremail@example.com</p>
<p>github.com/yourusername</p>
```

## 🖼️ Step 3: Add Your Images (1 minute)

Place these files in the `assets/` folder:
- `profile.jpg` - Your photo (400x400px)
- `project1.jpg` - Project screenshot (400x300px)
- `project2.jpg` - Project screenshot (400x300px)
- `project3.jpg` - Project screenshot (400x300px)

**Don't have images yet?** No problem! The site has beautiful SVG placeholders.

## 🚀 Step 4: Deploy to GitHub Pages (2 minutes)

### Option A: GitHub Desktop (Easiest)
1. Open GitHub Desktop
2. File → Add Local Repository
3. Select your project folder
4. Click "Publish repository"
5. Go to GitHub.com → Your repo → Settings → Pages
6. Select "main" branch → Save
7. Done! Your site is live at `yourusername.github.io/portfolio`

### Option B: Command Line
```bash
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/yourusername/portfolio.git
git push -u origin main
```

Then enable GitHub Pages in repository settings.

## 🎨 Bonus: Customize Colors (Optional)

Edit `styles.css` (Line ~8):
```css
:root {
    --primary-gradient: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
    --accent-color: #667eea;
    --highlight-color: #00f2fe;
}
```

Pick colors from:
- [Coolors.co](https://coolors.co/)
- [UIGradients](https://uigradients.com/)
- [ColorHunt](https://colorhunt.co/)

## 📱 Test Responsive Design

1. Open your site in browser
2. Press `F12` to open DevTools
3. Click the device icon (top-left)
4. Test different screen sizes

## ✅ Checklist

Before going live, make sure you've updated:
- [ ] Your name in hero section
- [ ] Bio and about text
- [ ] Project titles and descriptions
- [ ] Skills and percentages
- [ ] Contact email and social links
- [ ] Page title in `<title>` tag
- [ ] Meta description for SEO

## 🆘 Need Help?

### Site not loading?
- Make sure all files are in the same folder
- Check browser console (F12) for errors

### Images not showing?
- Verify filenames match exactly (case-sensitive)
- Check images are in `assets/` folder

### Want to customize more?
- See `README.md` for detailed documentation
- See `DEPLOYMENT.md` for hosting options

## 🎉 You're Done!

Your portfolio is now live and ready to share!

**Share it with:**
- LinkedIn profile
- Resume/CV
- GitHub profile README
- Email signature
- Social media

---

**Pro Tips:**
- Update your projects regularly
- Add Google Analytics to track visitors
- Get a custom domain for a professional touch
- Share on social media to get feedback

**Need inspiration?**
- [awwwards.com](https://www.awwwards.com/)
- [dribbble.com](https://dribbble.com/)
- [behance.net](https://www.behance.net/)

Good luck! 🚀
