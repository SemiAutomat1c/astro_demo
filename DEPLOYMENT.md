# Astro Demo - Deployment Guide

## 🚀 Quick Deploy to Vercel

### Option 1: Using Vercel CLI (Fastest)

```bash
# Install Vercel CLI globally
npm i -g vercel

# Navigate to project directory
cd /Users/ryandeniega/Documents/Repo/astro_demo

# Deploy (follow prompts)
vercel

# For production deployment
vercel --prod
```

### Option 2: Using Vercel Dashboard

1. **Push to GitHub first:**
```bash
cd /Users/ryandeniega/Documents/Repo/astro_demo
git add .
git commit -m "Initial Astro demo project"
git remote add origin https://github.com/YOUR_USERNAME/astro-demo.git
git push -u origin main
```

2. **Deploy on Vercel:**
   - Go to https://vercel.com/new
   - Import your GitHub repository
   - Vercel will auto-detect Astro
   - Click "Deploy"

### Build Settings (Auto-detected)
- **Framework Preset**: Astro
- **Build Command**: `npm run build`
- **Output Directory**: `dist`
- **Install Command**: `npm install`

---

## 📊 Post-Deployment Checklist

### 1. Test PageSpeed Scores
```bash
# After deployment, test at:
https://pagespeed.web.dev/

# Enter your deployed URL
# Expected scores:
# - Performance: 95+
# - Accessibility: 100
# - Best Practices: 100
# - SEO: 100
```

### 2. Verify Functionality
- [ ] All sections load correctly
- [ ] Navigation links scroll smoothly
- [ ] Responsive design works on mobile
- [ ] No console errors
- [ ] Meta tags are correct (view source)

### 3. Update Application
Add to your job application:

```
6. Astro Demo - Modern Landing Page
   Live Demo: [YOUR-VERCEL-URL]
   Completion Time: ~10 hours
   Built with Astro, TypeScript, Tailwind CSS v4. Demonstrates framework 
   proficiency with 95+ PageSpeed scores, zero JavaScript by default, 
   and excellent SEO optimization.
```

---

## 🎯 Alternative Deployment Options

### Netlify
```bash
# Build command
npm run build

# Publish directory
dist

# Deploy
netlify deploy --prod
```

### GitHub Pages
```bash
# Install gh-pages
npm install -D gh-pages

# Add to package.json scripts:
"deploy": "npm run build && gh-pages -d dist"

# Deploy
npm run deploy
```

### Cloudflare Pages
1. Connect GitHub repository
2. Build command: `npm run build`
3. Output directory: `dist`
4. Deploy

---

## 📝 Performance Optimization Tips

Already implemented in this project:
- ✅ Minimal JavaScript (Astro default)
- ✅ Optimized fonts (Google Fonts with preconnect)
- ✅ Semantic HTML structure
- ✅ Proper meta tags for SEO
- ✅ Responsive images
- ✅ Clean CSS with Tailwind

---

## 🔗 Useful Links

- [Astro Deployment Docs](https://docs.astro.build/en/guides/deploy/)
- [Vercel Astro Guide](https://vercel.com/docs/frameworks/astro)
- [PageSpeed Insights](https://pagespeed.web.dev/)

---

**Ready to deploy? Run `vercel` in the project directory!**
