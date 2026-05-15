# Cross Tech Systems Website

Professional, modern website for Cross Tech Systems - IT Support & Technology Solutions located in Cape Town, South Africa.

## 📋 Overview

This website showcases premium laptop bundles, IT services, and professional staff. Built with a tech-forward design featuring a black background with green/white accents and blue highlights.

## 🎨 Design Features

### Color Scheme
- **Primary Black**: `#0a0e27` - Main background
- **Dark Background**: `#0f1428` - Secondary background
- **Accent Green**: `#00d084` - Premium highlights
- **Accent Blue**: `#00a8ff` - Tech highlights
- **White**: `#ffffff` - Text and accents

### Layout Sections
1. **Navigation Bar** - Sticky, responsive with hamburger menu
2. **Hero Section** - Branded logo and company intro
3. **Products Section** - 3 featured laptop bundles with specs and pricing
4. **Services Section** - 4 key service highlights
5. **Special Section** - Staff spotlight and client testimonials
6. **Contact Section** - Contact info and inquiry form
7. **Footer** - Company info and social links

## 📁 File Structure

```
.
├── index.html           # Main HTML structure
├── styles.css           # Primary stylesheet
├── responsive.css       # Mobile & responsive design
├── script.js            # JavaScript functionality
├── README.md            # This file
└── assets/              # Images folder (create this)
    ├── logo-white-green.png      # Navbar logo
    ├── logo-circle.png           # Hero section emblem
    ├── charles-profile.png       # Staff photo
    ├── product1-main.png         # HP Elitebook main image
    ├── product1-angle1.png       # Product 1 angle 1
    ├── product1-angle2.png       # Product 1 angle 2
    ├── product2-main.png         # HP Business Laptop main
    ├── product2-angle1.png       # Product 2 angle 1
    ├── product2-angle2.png       # Product 2 angle 2
    ├── product3-main.png         # ASUS Zenbook main
    ├── product3-angle1.png       # Product 3 angle 1
    └── product3-angle2.png       # Product 3 angle 2
```

## 🚀 Quick Start

### 1. Setup
- Create an `assets` folder in the root directory
- Add all images as referenced above
- Ensure image paths match the HTML references

### 2. Optimize Images
For best performance:
- Use **WebP format** for modern browsers with PNG fallback
- Compress images using tools like TinyPNG or ImageOptim
- Recommended sizes:
  - Hero logo: 350x350px
  - Product main images: 400x300px
  - Thumbnail images: 70x70px
  - Staff photo: 150x150px

### 3. Deployment
- Upload all files to your web hosting
- Ensure `.htaccess` or server is configured for GZIP compression
- Set up SSL/HTTPS
- Configure email service for contact form (optional backend)

## ✨ Features

### Responsive Design
- Desktop (1024px+)
- Tablet (768px - 1024px)
- Mobile (480px - 767px)
- Small Mobile (<480px)
- Landscape orientation support

### Accessibility
- Semantic HTML5 structure
- ARIA labels and roles
- Keyboard navigation support
- Focus indicators
- Alt text for all images
- Screen reader friendly

### Performance
- Optimized CSS with custom properties
- Smooth animations and transitions
- Lazy loading ready
- Service Worker compatible
- Minification ready

### Interactive Elements
- Smooth scroll navigation
- Mobile hamburger menu
- Product gallery zoom
- Hover effects
- Contact form validation
- Scroll-to-top button
- Notification system

## 📱 Browser Support

- Chrome/Edge: Latest 2 versions
- Firefox: Latest 2 versions
- Safari: Latest 2 versions
- Mobile browsers: iOS Safari, Chrome Android

## ⚙️ Customization

### Colors
Modify CSS variables in `styles.css`:
```css
:root {
    --accent-green: #00d084;
    --accent-blue: #00a8ff;
    --primary-black: #0a0e27;
}
```

### Typography
Update font sizes and families in `:root`:
```css
--font-primary: 'Your Font', sans-serif;
--font-size-3xl: 48px;
```

### Contact Information
Update in `index.html`:
- Phone: `081 379 8480`
- Email: `info@crosstechz.co.za`
- Website: `www.crosstechz.co.za`
- Location: `Shop 5, Westgate Shopping Centre, Cape Town`

## 🔗 Links & References

### Contact Details
- **Phone**: 081 379 8480
- **Email**: info@crosstechz.co.za
- **Website**: www.crosstechz.co.za
- **Location**: Shop 5, Westgate Shopping Centre, Cape Town, South Africa

### Products Featured
1. **HP Elitebook 14" Silver** (Lot 35) - R4,499
   - Intel Core i5 (8th Gen)
   - 8GB RAM, 256GB SSD
   - 14" Full HD Display
   - Windows 10 Pro

2. **HP Business Laptop** (Darker Gray) - R4,199
   - Intel Core i5 (7th Gen)
   - 8GB RAM, 256GB SSD
   - 15.6" HD Display
   - Windows 10 Pro

3. **ASUS Zenbook Flip S** (Convertible) - R7,999
   - Intel Core i7 (8th Gen)
   - 16GB RAM, 512GB SSD
   - 13.3" Full HD Touch Display
   - Windows 10 Pro

## 🔒 Security

- Contact form includes basic validation
- CSRF protection ready (implement on backend)
- No sensitive data in frontend
- SSL/HTTPS recommended

## 📊 Analytics Integration

To enable Google Analytics:
1. Add tracking code to `<head>` section
2. Update tracking ID in script.js
3. Events are automatically tracked

## 🆘 Support & Troubleshooting

### Images Not Loading
- Check `assets` folder exists
- Verify image paths are correct
- Check file permissions

### Mobile Menu Not Working
- Clear browser cache
- Check JavaScript is enabled
- Verify hamburger selector in CSS

### Contact Form Not Sending
- Implement backend API endpoint
- Update form action URL
- Check server CORS settings

## 📝 License

This website is custom-built for Cross Tech Systems. All rights reserved.

## 🤝 Contributing

For updates or improvements:
1. Create a new branch
2. Make changes
3. Test on all devices
4. Submit for review

## 📞 Contact for Support

Contact the development team at the business contact information above.

---

**Last Updated**: 2026-05-15  
**Version**: 1.0.0  
**Status**: Production Ready
