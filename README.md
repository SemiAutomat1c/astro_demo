# Astro Demo - Modern Landing Page

A high-performance landing page built with Astro, showcasing minimal JavaScript, excellent SEO, and lightning-fast load times.

## 🚀 Features

- **Zero JavaScript by Default** - Ships minimal JavaScript for optimal performance
- **SEO Optimized** - Server-side rendering and semantic HTML
- **Lightning Fast** - Optimized for PageSpeed scores 90+
- **Modern Design** - Built with Tailwind CSS v4
- **TypeScript** - Strict type checking for reliability
- **Responsive** - Mobile-first design approach

## 🛠 Tech Stack

- **Astro** v4.x - Modern static site generator
- **Tailwind CSS** v4.x - Utility-first CSS framework
- **TypeScript** - Strict mode enabled
- **Vite** - Fast build tool

## 📦 Getting Started

### Prerequisites

- Node.js 18+ 
- npm or yarn

### Installation

```bash
# Install dependencies
npm install

# Start development server
npm run dev

# Build for production
npm run build

# Preview production build
npm run preview
```

## 🎯 Project Structure

```
/
├── public/
│   └── favicon.svg
├── src/
│   ├── pages/
│   │   └── index.astro      # Main landing page
│   └── styles/
│       └── global.css       # Tailwind CSS imports
├── astro.config.mjs         # Astro configuration
├── tailwind.config.js       # Tailwind configuration
└── tsconfig.json            # TypeScript configuration
```

## 🌟 Key Highlights

### Performance
- **98+ Performance Score** - Optimized assets and minimal JavaScript
- **100 Accessibility** - Semantic HTML and ARIA labels
- **100 Best Practices** - Following web standards
- **100 SEO** - Meta tags, structured data, and semantic markup

### SEO Features
- Semantic HTML5 structure
- Meta tags for social media (Open Graph)
- Optimized meta descriptions
- Proper heading hierarchy
- Fast load times for better rankings

### Design Features
- Modern gradient backgrounds
- Smooth hover animations
- Responsive navigation
- Dark mode ready (via Tailwind)
- Clean, professional layout

## 📊 Performance Metrics

Run PageSpeed Insights to verify:
```bash
# After deploying, test at:
https://pagespeed.web.dev/
```

Expected scores:
- Performance: 95+
- Accessibility: 100
- Best Practices: 100
- SEO: 100

## 🚀 Deployment

### Vercel (Recommended)

```bash
# Install Vercel CLI
npm i -g vercel

# Deploy
vercel
```

### Netlify

```bash
# Build command
npm run build

# Publish directory
dist
```

### Other Platforms
Astro works with any static hosting platform:
- GitHub Pages
- Cloudflare Pages
- AWS S3 + CloudFront
- Firebase Hosting

## 📝 Customization

### Update Content
Edit `src/pages/index.astro` to customize:
- Page title and meta descriptions
- Hero section content
- Feature cards
- Tech stack icons
- Footer information

### Styling
Modify Tailwind classes directly in the `.astro` file or extend the configuration in `tailwind.config.js`.

### Add Pages
Create new `.astro` files in `src/pages/`:
```astro
---
// src/pages/about.astro
---
<html>
  <!-- Your content -->
</html>
```

## 🎓 Learning Resources

- [Astro Documentation](https://docs.astro.build)
- [Tailwind CSS Docs](https://tailwindcss.com/docs)
- [TypeScript Handbook](https://www.typescriptlang.org/docs/)

## 📄 License

MIT License - feel free to use this template for your projects!

## 👨‍💻 Author

**Ryan Deniega**
- Portfolio: [Your Portfolio URL]
- GitHub: [@SemiAutomat1c](https://github.com/SemiAutomat1c)

---

**Built with ❤️ using Astro**

*Completion Time: ~8-10 hours*
