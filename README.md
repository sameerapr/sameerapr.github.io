# CyberSec From Scratch

An educational cybersecurity blog built for GitHub Pages.

## 🚀 Deploy to GitHub Pages

### Option 1: Direct HTML (Simplest)

1. Create a new repository on GitHub named `yourusername.github.io`
2. Upload all files from this folder to the repository
3. Go to **Settings → Pages → Source** and select "Deploy from a branch"
4. Select `main` branch and `/ (root)` folder
5. Your site will be live at `https://yourusername.github.io` within 2-3 minutes

### Option 2: With Jekyll (For Blog Features)

1. Fork or create a repository
2. Push these files to the repo
3. Go to **Settings → Pages → Source** and select "GitHub Actions"
4. GitHub will automatically build and deploy with Jekyll

## 📁 File Structure

```
├── index.html              # Main landing page + first post
├── about.md                # About page
├── _config.yml             # Jekyll configuration
├── assets/
│   └── css/
│       └── style.css       # Dark cybersecurity theme
└── README.md               # This file
```

## ✏️ Customization Checklist

- [ ] Replace `yourusername` in `_config.yml` with your actual GitHub username
- [ ] Replace `your.email@example.com` in `_config.yml` with your email
- [ ] Update the author name in `index.html` post meta
- [ ] Update navigation links in `index.html` and `about.md`
- [ ] Add your social links (GitHub, Twitter) in the footer
- [ ] Update the site URL in `_config.yml`

## 📝 Adding New Posts

For Jekyll deployment, create new posts in `_posts/` folder with this naming:
```
_posts/YYYY-MM-DD-post-title.md
```

Example front matter:
```yaml
---
layout: post
title: "The Cyber Kill Chain"
date: 2026-08-19
categories: [beginner, theory]
tags: [kill-chain, framework, defense]
---
```

For simple HTML deployment, create new `.html` files and link them from the series navigation.

## 🎨 Theme Features

- Dark cybersecurity aesthetic (GitHub-inspired dark mode)
- Responsive design (mobile-friendly)
- Code blocks with language labels
- Styled tables, info boxes, and disclaimers
- Sticky navigation
- Series navigation for multi-part content

## ⚠️ Legal Notice

This blog is for educational purposes only. All attack techniques are discussed from a defensive perspective with proper disclaimers.

## 📄 License

Content: [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/)
Code: MIT
