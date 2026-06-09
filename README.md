# 🍽️ Taste Trove

> A **premium, fully responsive restaurant website** featuring modern glassmorphism design, interactive menu showcase, and customer reviews. Built with clean HTML, CSS, and vanilla JavaScript for optimal performance.

<div align="center">

![HTML5](https://img.shields.io/badge/HTML5-E34C26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Responsive](https://img.shields.io/badge/Responsive-Mobile%20First-brightgreen?style=flat-square)
![License: MIT](https://img.shields.io/badge/License-MIT-green.svg?style=flat-square)

[Features](#features) • [Getting Started](#getting-started) • [Design System](#design-system) • [Pages](#pages)

</div>

---

## ✨ Features

- **Fully Responsive Design** - Optimized for desktop, tablet, and mobile devices
- **Modern Glassmorphism UI** - Premium aesthetic with frosted glass effects
- **Rich Saddle Brown Palette** - Warm, elegant color scheme
- **Interactive Menu** - Organized categories with detailed item descriptions
- **Customer Reviews Section** - Polished review cards with ratings
- **Image Gallery** - Showcase of dishes, staff, and atmosphere
- **Smooth Animations** - Elegant transitions and hover effects
- **Contact Form** - Easy-to-use inquiry and reservation page
- **Fast Performance** - Vanilla JavaScript, zero dependencies

---

## 🛠️ Tech Stack

| Component | Technology |
|-----------|-----------|
| **Frontend** | HTML5, CSS3 |
| **Scripting** | Vanilla JavaScript (ES6+) |
| **Design** | Responsive, Mobile-First |
| **Fonts** | Playfair Display, Roboto |
| **Deployment** | Static Site (GitHub Pages ready) |

---

## 📁 Project Structure

```
Taste-Trove/
├── index.html           # Homepage
├── Menu.html            # Menu page with all items
├── Review.html          # Customer reviews section
├── Gallery.html         # Image gallery showcase
├── About.html           # Restaurant information
├── ContactUs.html       # Contact & reservations
├── styles/
│   └── global.css       # Main stylesheet with variables
├── scripts/
│   └── main.js          # JavaScript functionality
└── images/              # All image assets
    ├── hero/
    ├── menu-items/
    ├── gallery/
    └── icons/
```

---

## 🎨 Design System

**Color Palette:**
- **Primary:** `#8B4513` (Saddle Brown) - Main brand color
- **Accent:** `#D2691E` (Chocolate) - Highlights and CTAs
- **Background:** `#FFF8E7` (Cosmic Latte) - Light cream
- **Text:** `#2C2C2C` (Dark Gray) - Primary text

**Typography:**
- **Headings:** Playfair Display (serif) - Elegant and premium
- **Body:** Roboto (sans-serif) - Clean and readable

**Effects:**
- Glassmorphism with semi-transparent backdrops
- Subtle shadows and depth
- Smooth hover transitions
- Animated navigation

---

## 🚀 Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- Optional: A local web server (for development)

### Installation

1. **Clone the Repository**
   ```bash
   git clone https://github.com/MuhammadHammadCS/Taste-Trove-.git
   cd Taste-Trove
   ```

2. **Open in Browser**
   
   Simply open `index.html` in your preferred browser:
   ```bash
   # On macOS
   open index.html
   
   # On Linux
   xdg-open index.html
   
   # On Windows
   start index.html
   ```

3. **Or Run a Local Server** (recommended for development)
   ```bash
   # Using Python 3
   python -m http.server 8000
   
   # Using Python 2
   python -m SimpleHTTPServer 8000
   
   # Using Node.js (http-server)
   npx http-server
   ```
   
   Then open `http://localhost:8000` in your browser

---

## 📄 Pages Overview

### 🏠 Homepage (`index.html`)
- Hero section with call-to-action
- Featured specialties
- Quick restaurant highlights
- Navigation to other pages

### 🍴 Menu (`Menu.html`)
- Organized menu categories
- Detailed item descriptions
- Pricing information
- Professional item presentation

### ⭐ Reviews (`Review.html`)
- Customer testimonials
- Star ratings
- Professional review cards
- Elegant layout

### 🖼️ Gallery (`Gallery.html`)
- Visual showcase of dishes
- Restaurant atmosphere photos
- Staff and team images
- Responsive image grid

### ℹ️ About (`About.html`)
- Restaurant story and history
- Mission statement
- Values and philosophy
- Team information

### 📞 Contact (`ContactUs.html`)
- Contact form for inquiries
- Reservation requests
- Location and hours
- Social media links

---

## 🎯 Key Features Explained

### Responsive Design
- Mobile-first approach
- Flexible grid layouts
- Adaptive images
- Touch-friendly navigation

### Glassmorphism Effects
- Semi-transparent backgrounds
- Backdrop blur effects
- Layered depth
- Premium appearance

### Interactive Elements
- Hover animations on menu items
- Smooth page transitions
- Form validation
- Dynamic content updates

### Performance Optimized
- No external dependencies
- Minimal JavaScript
- Optimized images
- Fast loading times

---

## 📱 Responsive Breakpoints

| Device | Width | Optimizations |
|--------|-------|---|
| **Mobile** | < 768px | Single column, touch-friendly |
| **Tablet** | 768px - 1024px | Two columns, adjusted spacing |
| **Desktop** | > 1024px | Full layout, multi-column |

---

## 🔧 Customization

### Change Brand Colors

Edit `styles/global.css`:
```css
:root {
  --primary-color: #8B4513;      /* Saddle Brown */
  --accent-color: #D2691E;       /* Chocolate */
  --bg-color: #FFF8E7;           /* Cosmic Latte */
  --text-color: #2C2C2C;         /* Dark Gray */
}
```

### Add Menu Items

Edit `Menu.html` and follow the existing structure:
```html
<div class="menu-item">
  <h3>Dish Name</h3>
  <p class="description">Item description</p>
  <p class="price">$XX.XX</p>
</div>
```

### Update Contact Information

Edit `ContactUs.html` with your actual:
- Restaurant address
- Phone number
- Email address
- Social media links

---

## 📊 Browser Support

- ✅ Chrome 90+
- ✅ Firefox 88+
- ✅ Safari 14+
- ✅ Edge 90+
- ✅ Mobile browsers

---

## 🚀 Deployment

### GitHub Pages

1. Push repository to GitHub
2. Go to Settings → Pages
3. Set source to `main` branch
4. Your site will be available at `username.github.io/Taste-Trove`

### Other Hosting

- **Netlify** - Connect GitHub repo, auto-deploys
- **Vercel** - Similar to Netlify, excellent performance
- **Traditional Hosting** - Upload files via FTP

---

## 💡 Best Practices

- Images are optimized for web
- Semantic HTML structure
- CSS variables for easy theming
- Mobile-first responsive design
- Accessible color contrasts
- Fast loading and rendering

---

## 📈 Future Enhancements

- [ ] Online ordering system
- [ ] Reservation booking
- [ ] Menu filtering and search
- [ ] Dark mode toggle
- [ ] Multi-language support
- [ ] Analytics integration
- [ ] Newsletter subscription
- [ ] Chef special updates

---

## 📜 License

This project is licensed under the **MIT License** - see [LICENSE](LICENSE) file for details.

---

## 🤝 Contributing

Contributions are welcome! Feel free to:
1. Fork the repository
2. Create a feature branch
3. Submit a pull request

---

## 💬 Feedback

Have suggestions or found an issue? Please feel free to:
- Open an issue on GitHub
- Create a pull request
- Contact via the website contact form

---

<div align="center">

**Crafted with ❤️ by Muhammad Hammad**

[⬆ back to top](#-taste-trove)

</div>
