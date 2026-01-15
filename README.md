# Nay Myo Htet - Developer Portfolio

A clean and modern developer portfolio showcasing the N2 Kanji app, built with HTML, CSS, and JavaScript.

## Features

- **Responsive Design**: Works seamlessly on desktop, tablet, and mobile devices
- **N2 Kanji Theme Colors**: Uses the official app color palette
  - Primary: `#4F6D7A`
  - Secondary: `#A14A4A`
  - Accent: `#33CCAF`
- **Interactive Elements**:
  - Smooth scrolling navigation
  - Animated sections on scroll
  - Interactive carousel for app screenshots
  - Hover effects on buttons and cards
- **Privacy Policy**: Comprehensive privacy policy page for N2 Kanji app

## Files

- `index.html` - Main portfolio page
- `portfolio.css` - Styling with N2 Kanji theme colors
- `portfolio.js` - Interactive features and animations
- `privacy-n2kanji.html` - Privacy policy for N2 Kanji app
- `README.md` - This file

## Setup

1. Open `index.html` in a web browser to view the portfolio
2. No build process or dependencies required
3. Uses Feather Icons CDN for icons

## Customization

### Adding Screenshots

Replace the placeholder in the carousel section with actual app screenshots:

```html
<div class="carousel-track" id="n2kanji-carousel">
    <img src="screenshots/screen1.png" alt="N2 Kanji screenshot 1" />
    <img src="screenshots/screen2.png" alt="N2 Kanji screenshot 2" />
    <!-- Add more screenshots -->
</div>
```

### Adding Profile Picture

Replace the placeholder in the About section:

```html
<div class="about-image">
    <img src="profile.jpg" alt="Nay Myo Htet" />
</div>
```

### Updating Contact Information

Edit the contact links in the Contact section of `index.html`:

```html
<a href="mailto:your-email@example.com" class="contact-link">
    <i data-feather="mail"></i>
    <span>Email</span>
</a>
```

## Deployment

### GitHub Pages

1. Push the portfolio folder contents to a GitHub repository
2. Go to repository Settings → Pages
3. Select the branch and folder
4. Your portfolio will be live at `https://yourusername.github.io/repository-name`

### Netlify

1. Drag and drop the portfolio folder to Netlify
2. Your site will be deployed instantly

## Privacy Policy

The privacy policy (`privacy-n2kanji.html`) includes:

- Information collection practices
- Third-party services (AdMob, Google Play Services)
- Data retention and security
- User rights and opt-out options
- Contact information

Update the privacy policy as needed when adding new features or services to the app.

## Credits

- Design inspired by modern portfolio best practices
- Icons by [Feather Icons](https://feathericons.com/)
- Color scheme from N2 Kanji app

## License

© 2025 Nay Myo Htet. All rights reserved.
