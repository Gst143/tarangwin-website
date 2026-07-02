# Tarang Win - Production Website

A complete, production-ready responsive website for the Tarang Win Android app - a skill-based quiz contest platform.

## 🚀 Features

- **Pure HTML5, CSS3, JavaScript** - No frameworks, no Bootstrap
- **Material 3 UI** - Modern Material Design 3 components
- **Glassmorphism Design** - Beautiful glass-like effects
- **Mobile First** - Responsive design optimized for mobile devices
- **SEO Optimized** - Meta tags, sitemap, robots.txt
- **PWA Ready** - Progressive Web App manifest included
- **GitHub Pages Ready** - Can be deployed directly to GitHub Pages
- **Firebase Hosting Ready** - Compatible with Firebase Hosting
- **Netlify Ready** - Can be deployed to Netlify

## 📁 Project Structure

```
TarangWin WebSite/
├── index.html                      # Homepage
├── about.html                      # About Us page
├── features.html                   # Features page
├── faq.html                        # FAQ page
├── contact.html                    # Contact page
├── support.html                    # Support page
├── privacy-policy.html             # Privacy Policy
├── terms-conditions.html          # Terms & Conditions
├── refund-policy.html              # Refund Policy
├── responsible-gaming.html          # Responsible Gaming
├── skill-game-declaration.html     # Skill Game Declaration
├── account-deletion.html           # Account Deletion
├── 404.html                        # 404 Error page
├── style.css                       # Main CSS (Material 3 + Glassmorphism)
├── responsive.css                  # Responsive CSS (Mobile First)
├── app.js                          # JavaScript for interactivity
├── robots.txt                      # SEO robots file
├── sitemap.xml                     # SEO sitemap
├── manifest.json                   # PWA manifest
├── favicon.ico                     # Favicon (to be added)
├── favicon.svg                     # SVG Favicon (to be added)
├── apple-touch-icon.png            # Apple Touch Icon (to be added)
├── favicon-32x32.png               # 32x32 Favicon (to be added)
├── favicon-16x16.png               # 16x16 Favicon (to be added)
└── README.md                       # This file
```

## 🎨 Design System

### Colors (Material 3)
- **Primary:** #6750A4
- **Secondary:** #625B71
- **Tertiary:** #7D5260
- **Error:** #B3261E
- **Background:** #FFFBFE
- **Surface:** #FFFBFE

### Glassmorphism
- **Glass Background:** rgba(255, 255, 255, 0.25)
- **Glass Border:** rgba(255, 255, 255, 0.5)
- **Glass Blur:** blur(12px)
- **Glass Shadow:** 0 8px 32px 0 rgba(31, 38, 135, 0.15)

### Typography
- **Font Family:** Roboto
- **Base Size:** 16px
- **Headings:** 700 weight
- **Body:** 400 weight

## 📱 Pages

### Main Pages
1. **Home** - Landing page with hero, features, contest types
2. **About** - Company story, mission, vision, team
3. **Features** - Detailed feature list and highlights
4. **FAQ** - Frequently asked questions with accordion
5. **Contact** - Contact form and information
6. **Support** - Support center with categories

### Legal Pages
7. **Privacy Policy** - Data collection and usage policy
8. **Terms & Conditions** - Terms of service
9. **Refund Policy** - Refund rules and process
10. **Responsible Gaming** - Responsible gaming practices
11. **Skill Game Declaration** - Legal declaration of skill-based gaming
12. **Account Deletion** - Account deletion process

### Error Page
13. **404** - Custom 404 error page

## 🚀 Deployment

### GitHub Pages
1. Push the code to a GitHub repository
2. Go to repository Settings > Pages
3. Select the main branch as source
4. Your site will be live at `https://username.github.io/repository-name`

### Firebase Hosting
```bash
# Install Firebase CLI
npm install -g firebase-tools

# Login
firebase login

# Initialize
firebase init

# Deploy
firebase deploy
```

### Netlify
1. Push code to GitHub
2. Connect repository to Netlify
3. Deploy automatically on push

## 🔧 Customization

### Update Domain
Replace `https://tarangwin.com` with your actual domain in:
- All HTML files (meta tags, canonical URLs)
- sitemap.xml
- robots.txt

### Update Contact Information
Update in all HTML files:
- Email: tsp.chainpura@gmail.com
- Phone: +91 9982892888
- Address: India

### Add Favicons
Create and add favicon files:
- favicon.ico
- favicon.svg
- apple-touch-icon.png (180x180)
- favicon-32x32.png
- favicon-16x16.png
- Additional sizes for PWA (72, 96, 128, 144, 152, 192, 384, 512)

Use tools like:
- https://favicon.io/
- https://realfavicongenerator.net/

### Update Social Links
Replace `#` with actual social media URLs in footer.

## 📝 SEO

The website includes:
- Meta tags for title, description, keywords
- Open Graph tags for social sharing
- Twitter Card tags
- Canonical URLs
- robots.txt
- sitemap.xml

Update these with your actual content before deployment.

## ♿ Accessibility

The website includes:
- Semantic HTML
- ARIA labels
- Keyboard navigation
- Focus indicators
- Skip to content link
- Alt text for images (when added)
- Color contrast compliance

## 🔒 Security

- No sensitive data in client-side code
- HTTPS recommended for production
- CSP headers can be added via hosting
- Form validation on client and server side

## 📊 Analytics

Add your analytics tracking code in the `<head>` section of all HTML files:
- Google Analytics
- Firebase Analytics
- Other analytics services

## 🎯 Performance

The website is optimized for:
- Fast loading (minimal dependencies)
- Lazy loading for images
- Smooth animations
- Optimized CSS
- Efficient JavaScript

## 📱 PWA Features

The manifest.json includes:
- App name and description
- Theme colors
- Icons (to be added)
- Display mode
- Orientation
- Shortcuts

Add actual icon files to complete PWA setup.

## 🤝 Support

For support, email: tsp.chainpura@gmail.com

## 📄 License

Copyright © 2024 Tarang Win. All rights reserved.

---

**Note:** This is a production-ready website template. Customize it according to your brand, add actual content, and deploy to your preferred hosting platform.
