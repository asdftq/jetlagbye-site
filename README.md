# Jet Lag Bye - Jet Lag App Landing Page

A modern, minimal static website for the Jet Lag Bye jet lag app. Designed for GitHub Pages deployment.

## 🚀 Quick Start

### Deploy to GitHub Pages

1. Create a new repository on GitHub
2. Push this folder to the repository:
   ```bash
   cd jetlag-app
   git init
   git add .
   git commit -m "Initial commit"
   git remote add origin https://github.com/YOUR_USERNAME/jetlagbye.git
   git push -u origin main
   ```
3. Go to Repository Settings → Pages
4. Set source to "Deploy from a branch" → main → / (root)
5. Your site will be live at `https://YOUR_USERNAME.github.io/jetlagbye/`

### Local Development

Just open `index.html` in your browser. No build step required.

For live reload during development:
```bash
npx serve .
```

## 📁 Structure

```
jetlag-app/
├── index.html          # Homepage
├── faq.html            # FAQ page
├── privacy.html        # Privacy policy
├── terms.html          # Terms of service
├── support.html        # Support page
├── css/
│   └── style.css       # All styles
├── js/                 # (empty, minimal JS inline)
├── images/             # (add your images here)
└── README.md
```

## 🎨 Design System

### Colors
- Background: `#0a0a0f` (deep space black)
- Primary: `#6366f1` (indigo)
- Accent: `#f59e0b` (amber)
- Text: `#f5f5f7` (off-white)

### Typography
- Font: Inter (Google Fonts)
- Weights: 200, 400, 500, 600, 700

### Features
- Dark mode native
- Responsive (mobile-first)
- CSS animations (fade-in on scroll)
- No JavaScript frameworks
- < 20KB total CSS

## 📝 Customization

### Update App Store Link
Search for `#download` and replace the placeholder href with your actual App Store URL.

### Update Contact Email
Replace `support@jetlagbye.app`, `privacy@jetlagbye.app`, and `legal@jetlagbye.app` with your actual email addresses.

### Add Real Testimonials
Edit the testimonials section in `index.html` with real user reviews.

### Add Images
1. Create OG image (1200x630px) → `images/og-image.png`
2. Add app screenshots for mockups
3. Update meta tags with image URLs

### Custom Domain
1. Add a `CNAME` file with your domain (e.g., `jetlagbye.app`)
2. Configure DNS with your registrar
3. Enable HTTPS in GitHub Pages settings

## 🔍 SEO

Included:
- Semantic HTML5
- Meta descriptions
- Open Graph tags
- Twitter cards
- Structured data (JSON-LD)
- FAQ schema markup

### Target Keywords
- jet lag app
- circadian rhythm
- beat jet lag
- travel sleep
- melatonin timing

## 📊 Analytics

Add your analytics by inserting the script before `</head>`:

```html
<!-- Plausible (privacy-friendly) -->
<script defer data-domain="jetlagbye.app" src="https://plausible.io/js/script.js"></script>

<!-- Or Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=G-XXXXXXX"></script>
```

## 📱 App Store Requirements

Before submitting your iOS app:
1. Update App Store link in all pages
2. Ensure privacy policy matches your app's data collection
3. Verify terms of service covers your features
4. Add required App Store badges if needed

## 📄 License

© 2026 Jet Lag Bye. All rights reserved.
