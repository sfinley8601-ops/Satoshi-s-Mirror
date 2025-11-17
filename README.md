# Satoshi's Mirror Website

Complete website for the Satoshi's Mirror documentary series.

## 📁 Files Included

- `index.html` - Homepage with countdown timer
- `about.html` - About page with series info
- `episodes.html` - Episodes listing
- `support.html` - Lightning wallet support page
- `styles.css` - Main stylesheet
- `pages.css` - Additional page styles
- `script.js` - JavaScript for countdown timer
- `README.md` - This file

## 🚀 Deployment Options

### Option 1: GitHub Pages (Free & Easy)

1. Create a GitHub account if you don't have one
2. Create a new repository called "satoshismirror"
3. Upload all files to the repository
4. Go to Settings → Pages
5. Select "Deploy from main branch"
6. Your site will be live at: `username.github.io/satoshismirror`

### Option 2: Netlify (Free with Custom Domain)

1. Create account at netlify.com
2. Drag and drop the entire folder
3. Site goes live instantly
4. Connect your satoshismirror.com domain in settings

### Option 3: Traditional Hosting

Upload all files via FTP to your hosting provider's public_html folder.

## 🔧 Setup Steps

### 1. Add Your Hero Image

Replace the background in `styles.css` (line 147):
```css
background: 
    linear-gradient(180deg, rgba(10,10,10,0.7) 0%, rgba(10,10,10,0.9) 100%),
    url('hero-image.jpg') center/cover no-repeat;
```

Upload your Bitcoin vault door image as `hero-image.jpg` in the same folder.

### 2. Connect Domain (After Deployment)

In Namecheap dashboard:
- Go to Domain List → Manage
- Advanced DNS tab
- Add these records:

**For GitHub Pages:**
```
Type: A Record
Host: @
Value: 185.199.108.153

Type: CNAME
Host: www
Value: yourusername.github.io
```

**For Netlify:**
Netlify will provide the DNS records in their dashboard.

## ⚙️ Customization

### Update Social Links
Edit the social links in all HTML files:
- YouTube: `https://youtube.com/@satoshismirror`
- Twitter/X: Update when you have handle
- Instagram: `https://www.instagram.com/satoshis_mirror`
- TikTok: `https://www.tiktok.com/@satoshis_mirror`
- Reddit: `https://www.reddit.com/u/SatoshisMirror`

### Change Colors
Edit `styles.css` (lines 9-15):
```css
:root {
    --primary-teal: #1a4d4d;
    --primary-cyan: #2a7d7d;
    --accent-gold: #d4a044;
    --accent-orange: #ff8c42;
    --bg-dark: #0a0a0a;
    --bg-darker: #050505;
    --text-light: #e0e0e0;
    --text-dim: #a0a0a0;
}
```

### Update Launch Date
Edit `script.js` (line 3):
```javascript
const launchDate = new Date('January 3, 2026 12:00:00 EST').getTime();
```

## 📱 Features

✅ Fully responsive (mobile, tablet, desktop)
✅ Countdown timer to Episode 1 launch
✅ Lightning wallet integration
✅ All social media links
✅ Clean anime-inspired design
✅ Fast loading (no heavy frameworks)
✅ SEO optimized

## 🎨 Design

- Color scheme: Teal/Cyan + Gold/Orange
- Inspired by: Ghost in the Shell, Cowboy Bebop
- Typography: Clean, modern, readable
- Animations: Subtle glitch effects

## 📧 Support

Lightning Address: satoshis-mirror@rizful.com

## 🔗 Social Media

- YouTube: [@satoshismirror](https://youtube.com/@satoshismirror)
- Instagram: [@satoshis_mirror](https://www.instagram.com/satoshis_mirror)
- TikTok: [@satoshis_mirror](https://www.tiktok.com/@satoshis_mirror)
- Reddit: [u/SatoshisMirror](https://www.reddit.com/u/SatoshisMirror)

---

Created by [LineTrash](https://twitter.com/LineTrash)
