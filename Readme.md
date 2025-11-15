# Lasa E-commerce | لسع للتجارة الإلكترونية

A modern, bilingual e-commerce website designed for the Sudan market with Arabic as the default language.

## 🌟 Features

- **Bilingual Support**: Full Arabic and English language support with RTL/LTR text direction
- **Responsive Design**: Works perfectly on mobile, tablet, and desktop devices
- **Product Catalog**: Browse products by categories (Electronics, Fashion, Home, Beauty)
- **Shopping Cart**: Add items to cart with visual feedback
- **Modern UI**: Beautiful gradient colors with blue, cyan, gold, and white theme
- **Product Ratings**: 5-star rating system for each product
- **Search Functionality**: Search bar for finding products (ready for backend integration)
- **Newsletter Subscription**: Email collection for marketing campaigns

## 🎨 Color Scheme

- Primary: Blue (#2563eb)
- Secondary: Cyan/Turquoise (#06b6d4)
- Accent: Gold/Yellow (#eab308)
- Neutral: White, Gray shades

## 🚀 Live Demo

Visit the live site at: `https://[your-username].github.io/lasa-ecommerce/`

## 📦 Installation & Deployment

### Option 1: GitHub Pages (Recommended)

1. **Create a new repository on GitHub**
   - Go to https://github.com/new
   - Name it: `lasa-ecommerce`
   - Make it public
   - Do not initialize with README

2. **Upload files**
   - Click "uploading an existing file"
   - Drag and drop `index.html` and `README.md`
   - Commit the files

3. **Enable GitHub Pages**
   - Go to repository Settings
   - Click on "Pages" in the left sidebar
   - Under "Source", select "main" branch
   - Click "Save"
   - Your site will be live at: `https://[your-username].github.io/lasa-ecommerce/`

### Option 2: Using Git Command Line

```bash
# Clone or initialize repository
git init
git add .
git commit -m "Initial commit: Lasa E-commerce website"

# Add remote and push
git remote add origin https://github.com/[your-username]/lasa-ecommerce.git
git branch -M main
git push -u origin main
```

Then enable GitHub Pages in repository settings as described above.

## 📁 File Structure

```
lasa-ecommerce/
├── index.html          # Main website file (complete single-file application)
└── README.md          # This file
```

## 🔧 Customization

### Adding Products

Edit the `products` array in the JavaScript section:

```javascript
const products = [
    {
        id: 1,
        name: { ar: 'اسم المنتج', en: 'Product Name' },
        price: 850,
        image: '🎧', // Use emoji or replace with image URL
        category: 'electronics',
        rating: 4.5
    },
    // Add more products...
];
```

### Changing Colors

Modify the gradient classes in the `<style>` section:

```css
.gradient-blue {
    background: linear-gradient(135deg, #2563eb 0%, #06b6d4 100%);
}

.gradient-gold {
    background: linear-gradient(135deg, #eab308 0%, #f59e0b 100%);
}
```

### Updating Contact Information

Find the contact section in the footer and update:

```html
<li>📧 info@lasa-sd.com</li>
<li>📱 +249 XXX XXX XXX</li>
<li>📍 Khartoum, Sudan</li>
```

## 🌐 Language Support

The website supports both Arabic (RTL) and English (LTR) with:
- Automatic text direction switching
- Complete UI translations
- Proper alignment for both languages

Toggle between languages using the button in the top-right corner.

## 🛠️ Technologies Used

- HTML5
- CSS3 (Tailwind CSS via CDN)
- Vanilla JavaScript
- No build process required
- No external dependencies (except Tailwind CDN)

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 🔮 Future Enhancements

- Backend integration for real product data
- Payment gateway integration
- User authentication and accounts
- Order tracking system
- Product reviews and ratings
- Wishlist functionality
- Advanced search and filtering
- Admin dashboard

## 📄 License

© 2025 Lasa E-commerce. All rights reserved.

## 🤝 Contributing

This is a demonstration project. For production use, consider:
- Adding a backend (Node.js, PHP, Python)
- Implementing a database (MySQL, MongoDB)
- Adding payment processing (Stripe, PayPal)
- Setting up proper hosting
- Implementing security measures

## 📞 Support

For questions or support, contact:
- Email: info@lasa-sd.com
- Location: Khartoum, Sudan

---

**Made for Sudan Market | صنع للسوق السوداني** 🇸🇩
