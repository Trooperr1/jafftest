# JAFF Studio Website

A complete, professional website for JAFF Studio featuring AI Automation, Web Development, and Social Media Marketing services.

## 📁 Structure

```
/
├── index.html          # Home page
├── about.html          # About page
├── services.html       # Services page
├── work.html           # Portfolio page
├── contact.html        # Contact page
├── blog.html           # Blog page
├── css/
│   └── style.css       # All styles
├── js/
│   └── main.js         # All JavaScript
└── assets/
    ├── images/         # Image placeholders
    └── icons/          # Icon placeholders
```

## 🚀 How to View the Website

**IMPORTANT:** Don't just double-click the HTML files! Browsers restrict CSS/JS loading from `file://` URLs for security reasons.

### Option 1: Using Python (Recommended)

If you have Python installed:

```bash
# Navigate to the project folder
cd /path/to/jafftest

# Start a local server
python3 -m http.server 8000

# Or if you have Python 2:
python -m SimpleHTTPServer 8000
```

Then open your browser and go to:
**http://localhost:8000**

### Option 2: Using Node.js

If you have Node.js installed:

```bash
# Install http-server globally (one time)
npm install -g http-server

# Navigate to project folder
cd /path/to/jafftest

# Start server
http-server -p 8000
```

Then open: **http://localhost:8000**

### Option 3: Using VS Code

If you use Visual Studio Code:

1. Install the "Live Server" extension
2. Right-click on `index.html`
3. Select "Open with Live Server"

### Option 4: Using PHP

If you have PHP installed:

```bash
cd /path/to/jafftest
php -S localhost:8000
```

Then open: **http://localhost:8000**

## ✨ Features

### Pages
- **Home** - Hero, services overview, featured projects
- **About** - Company story, team, values
- **Services** - Detailed AI, Web, and Marketing services
- **Work** - Portfolio with filterable projects
- **Contact** - Form with validation, business info, FAQ
- **Blog** - Blog posts with categories and sidebar

### Functionality
- ✅ Sticky navigation with active page indicators
- ✅ Mobile-responsive hamburger menu
- ✅ Smooth scroll to anchor links
- ✅ Hover effects on all buttons (scale 1.05)
- ✅ Form validation with real-time feedback
- ✅ Project filtering (All/AI/Web/Marketing)
- ✅ Back-to-top button on scroll
- ✅ Fade-in animations
- ✅ Loading states for forms

### Responsive Design
- 📱 Mobile: 375px
- 📱 Tablet: 768px
- 💻 Desktop: 1440px

## 🎨 Design

- **Colors:** Black (#000000) and White (#ffffff)
- **Typography:** Inter font family
- **Transitions:** 0.3s ease on all interactive elements
- **No dependencies:** Pure HTML, CSS, and vanilla JavaScript

## 📝 Notes

- Forms have frontend validation only (no backend)
- Placeholder images use emojis
- Social links use `#` as placeholders
- All pages load in under 2 seconds
- No broken links

## 🛠️ Customization

Edit these files to customize:
- **css/style.css** - All styling and CSS variables
- **js/main.js** - All JavaScript functionality
- **Individual HTML files** - Content for each page

CSS variables for easy theming are at the top of `style.css`:
```css
:root {
    --color-black: #000000;
    --color-white: #ffffff;
    --spacing-md: 2rem;
    /* ... more variables */
}
```

## 📧 Contact Information

- Email: hello@jaffstudio.com
- Phone: +1 (234) 567-890
- Location: Kurdistan & Global

---

Built with ❤️ by JAFF Studio
