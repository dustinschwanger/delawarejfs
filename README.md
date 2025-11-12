# Delaware County Department of Job & Family Services

Official website for Delaware County Job and Family Services, Ohio.

## 🌟 Features

- **WCAG 2.2 AA Compliant** - Full accessibility compliance
- **Responsive Design** - Mobile-first approach using USWDS
- **Enhanced Focus Indicators** - Clear keyboard navigation
- **Screen Reader Optimized** - Proper ARIA labels and semantic HTML
- **Fast & Secure** - Optimized performance with security headers

## 🎯 WCAG 2.2 AA Compliance

This website meets all WCAG 2.2 Level AA success criteria including:

- ✅ 2.4.11 Focus Appearance (enhanced focus indicators)
- ✅ 2.5.8 Target Size (minimum 24x24 CSS pixels)
- ✅ 3.2.6 Consistent Help (help mechanism in consistent location)
- ✅ All WCAG 2.1 Level AA criteria
- ✅ Color contrast ratios meet 4.5:1 (normal text) and 3:1 (large text)
- ✅ Keyboard accessible throughout
- ✅ Screen reader compatible

## 🚀 Deployment

### Railway

This site is configured for one-click deployment on Railway:

1. Connect your GitHub repository to Railway
2. Railway will auto-detect the configuration from `railway.toml`
3. Your site will be live at your Railway domain

### Local Development

```bash
# Install dependencies
npm install

# Run development server
npm run dev

# Production server
npm start
```

Server runs on `http://localhost:3000`

## 📁 File Structure

```
delawarejfs/
├── index.html              # Main homepage
├── styles.css              # Main stylesheet
├── accessibility.css       # WCAG 2.2 compliance styles
├── server.js              # Express server for deployment
├── package.json           # Node.js dependencies
├── railway.toml           # Railway deployment config
├── public/                # Images and assets
│   ├── medicaid.jpg
│   ├── food-assistance.jpg
│   ├── child-care.jpg
│   ├── child-protective.png
│   ├── adoption.png
│   ├── workforce.png
│   └── job.png
├── logo.png              # Delaware JFS logo
├── logo-white.png        # White version of logo
├── hero.png             # Hero section background
└── favicon_1.ico        # Site favicon
```

## 🔒 Security

- HSTS enabled (force HTTPS)
- Content Security Policy implemented
- XSS protection headers
- Clickjacking prevention
- CORS properly configured

## ♿ Accessibility Features

### Navigation
- Skip navigation link
- Keyboard-accessible dropdowns
- Clear focus indicators
- Logical tab order

### Content
- Semantic HTML structure
- Proper heading hierarchy
- Descriptive link text
- Alt text on all images

### Interactive Elements
- Minimum 44x44 pixel tap targets (exceeds WCAG 2.2)
- Enhanced focus appearance
- Focus trap in modal dialogs
- ARIA live regions for dynamic content

### Chat Widget
- Keyboard accessible
- Focus management
- Escape to close
- Screen reader announcements

## 🧪 Testing

### Accessibility Testing Tools
- [WAVE Browser Extension](https://wave.webaim.org/extension/)
- [axe DevTools](https://www.deque.com/axe/devtools/)
- [Lighthouse](https://developers.google.com/web/tools/lighthouse)

### Keyboard Navigation Testing
1. Navigate using Tab/Shift+Tab
2. Test dropdown menus with Arrow keys
3. Test accordions with Enter/Space
4. Ensure all interactive elements are reachable

### Screen Reader Testing
- NVDA (Windows)
- JAWS (Windows)
- VoiceOver (Mac/iOS)
- TalkBack (Android)

## 📞 Contact

**Delaware County Job and Family Services**
145 North Union Street, 2nd Floor
Delaware, Ohio 43015

- **Phone:** 740-833-2300
- **Toll Free:** 800-899-3180
- **Email:** delawarecounty@jfs.ohio.gov

## 📄 License

© 2025 Delaware County Department of Job & Family Services. All rights reserved.

## 🔄 Updates

- **v1.0.0** (2025-11-12) - Initial release with WCAG 2.2 AA compliance
