# IronX - Gym & Fitness Website

A modern, responsive website for IronX gym and fitness center. This project features a clean design with smooth animations, interactive elements, and a fully responsive layout that works seamlessly on desktop, tablet, and mobile devices.

## 🏋️ Project Overview

IronX is a professional gym website showcasing fitness services, pricing plans, testimonials, and contact information. The website is built with HTML5, CSS3, Bootstrap, and JavaScript, providing an excellent user experience across all devices.

## 📁 Project Structure

```
energym-master/
│
├── index.html          # Home page 
├── about.html          # About page
├── service.html        # Services page
├── contact.html        # Contact page
│
├── css/
│   ├── bootstrap.css   # Bootstrap framework styles
│   ├── style.css       # Main custom stylesheet (optimized)
│   ├── responsive.css  # Responsive design styles for mobile devices
│   ├── style.css.map   # Source map for style.css
│   └── animate.css     # WowJs css file
│
├── js/
│   ├── bootstrap.js         # Bootstrap JavaScript framework
│   ├── jquery-3.7.1.min.js  # jQuery library
│   └── wow.min.js           # WowJs js file
│   
└── images/             # All website images and assets
    ├── logo.png
    ├── slider-bg.jpg
    ├── about-img.png
    ├── result-img.jpg
    ├── s-1.jpg, s-2.jpg, s-3.jpg, s-4.jpg  # Service images
    ├── u-1.png, u-2.png, u-4.png           # Feature icons
    ├── client.png                          # Testimonial image
    └── [social media icons]
```

## ✨ Features

### 🎨 Design Features
- **Modern UI/UX**: Clean and professional design
- **Responsive Design**: Fully responsive layout for all screen sizes
- **Smooth Animations**: Hover effects and transitions on buttons and cards
- **Interactive Elements**: Hover effects on service cards, buttons, and navigation

### 🎯 Key Sections

- **Hero Slider**: Multiple slides with call-to-action buttons
- **Services**: Interactive service cards with hover effects
- **Pricing Plans**: Three pricing tiers with feature lists
- **Testimonials**: Customer reviews carousel
- **Contact Form**: Functional contact form with validation

## 🛠️ Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Custom styling with animations and transitions
- **Bootstrap 5**: Responsive grid system and components
- **JavaScript/jQuery**: Interactive functionality
- **Google Fonts**: Poppins, Dosis, Baloo Chettan fonts
- **Owl Carousel**: Slider functionality (CDN)

## 🎨 Color Scheme

- **Primary Yellow**: `#f8bc1a` - Used for buttons, accents, and highlights
- **Dark Purple**: `#3c0e78` - Used for sections and backgrounds
- **Dark Gray**: `#161616` - Used for footer and info sections
- **Light Gray**: `#f4f3f3` - Used for backgrounds
- **White**: `#ffffff` - Text and backgrounds

## 📱 Responsive Breakpoints

The website is optimized for the following screen sizes:
- **Desktop**: 1200px and above
- **Tablet**: 768px - 1199px
- **Mobile**: Below 768px
- **Small Mobile**: Below 576px

## 🚀 Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- A local web server (optional, for testing)

### Installation

1. **Clone or download** the project files
2. **Open** `index.html` in your web browser
3. **Or** use a local server:
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js (http-server)
   npx http-server
   ```

## 📝 Customization

### Changing Colors
Edit `css/style.css` and search for color values:
- Primary yellow: `#f8bc1a`
- Dark purple: `#3c0e78`
- Dark gray: `#161616`

### Modifying Content
- Edit HTML files directly to change text content
- Update images in the `images/` folder
- Modify `css/style.css` for styling changes
- Adjust `css/responsive.css` for mobile-specific styles

### Adding New Sections
1. Add HTML structure in the desired HTML file
2. Add corresponding CSS in `css/style.css`
3. Add responsive styles in `css/responsive.css` if needed

## 🎯 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 📦 Dependencies

### CDN Resources
- **Bootstrap CSS/JS**: Included locally
- **jQuery**: Included locally (`js/jquery-3.7.1.min.js`)
- **Owl Carousel**: Loaded from CDN
- **Google Fonts**: Poppins, Dosis, Baloo Chettan

### Local Files
- Bootstrap CSS: `css/bootstrap.css`
- Bootstrap JS: `js/bootstrap.js`
- Custom CSS: `css/style.css`
- Responsive CSS: `css/responsive.css`

## 🔧 CSS Optimization

The `style.css` file has been optimized:
- Removed unused CSS rules
- Consolidated duplicate styles
- Minimized code while maintaining functionality
- All styles are actively used in the HTML pages

## 🎨 Button Styles

All buttons follow a consistent design:
- **Read More Button**: Yellow background (`#f8bc1a`) with transparent hover
- **Get A Quote Button**: Light gray background with transparent hover
- **Send/Join Now Buttons**: Yellow background matching Read More button style
- All buttons have smooth 0.3s transitions

## 📱 Mobile Features

- Centered content on mobile devices
- Responsive navigation menu
- Optimized images and layouts
- Touch-friendly buttons and links
- Mobile-specific spacing and padding

## 🔄 Recent Updates

- Optimized CSS by removing unused styles
- Added smooth hover transitions to all buttons
- Centered pricing card text on all devices
- Improved mobile responsiveness
- Enhanced service card hover effects

## 🐛 Troubleshooting

### Images not loading
- Ensure the `images/` folder is in the correct location
- Check image file names match exactly (case-sensitive)

### Styles not applying
- Clear browser cache
- Check file paths in HTML `<link>` tags
- Verify CSS files are in the `css/` folder

### JavaScript not working
- Ensure jQuery is loaded before Bootstrap
- Check browser console for errors
- Verify all JS files are in the `js/` folder

## 📚 Additional Resources

- [Bootstrap Documentation](https://getbootstrap.com/docs/)
- [jQuery Documentation](https://api.jquery.com/)
- [Google Fonts](https://fonts.google.com/)
