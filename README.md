# Portfolio Website

A modern, responsive, and animated portfolio website for Basappa Mallappa Baluragi.

## Features

- ✨ **Fully Responsive** - Works perfectly on desktop, tablet, and mobile devices
- 🎨 **Modern Design** - Clean and professional UI with smooth animations
- 🚀 **Smooth Animations** - Scroll-triggered animations and interactive elements
- 📱 **Mobile-Friendly Navigation** - Hamburger menu for mobile devices
- 🎯 **Smooth Scrolling** - Seamless navigation between sections
- 💫 **Interactive Elements** - Hover effects, card tilts, and more

## Setup Instructions

1. **Add Your Photo**
   - Place your photo file in the portfolio folder
   - Name it `photo.jpg` (or update the filename in `index.html` line 30)
   - Recommended size: 300x300px or larger (square format works best)

2. **Open the Website**
   - Simply open `index.html` in your web browser
   - Or use a local server for better performance:
     ```bash
     # Using Python
     python -m http.server 8000
     
     # Using Node.js (http-server)
     npx http-server
     ```

3. **Customize**
   - Edit `index.html` to update content
   - Modify `styles.css` to change colors, fonts, or styling
   - Update `script.js` to add more interactivity

## File Structure

```
portfolio/
├── index.html      # Main HTML file
├── styles.css      # CSS styles and animations
├── script.js       # JavaScript for interactivity
├── photo.jpg       # Your profile photo (add this)
└── README.md       # This file
```

## Sections

1. **Hero Section** - Introduction with photo and social links
2. **About** - Objective and key statistics
3. **Skills** - Technical skills organized by category
4. **Projects** - Showcase of your projects
5. **Education** - Educational background timeline
6. **Certificates** - Certifications and achievements
7. **Achievements & Interests** - Your accomplishments
8. **Contact** - Contact information

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## Technologies Used

- HTML5
- CSS3 (with animations and transitions)
- JavaScript (ES6+)
- Font Awesome (for icons)

## Customization

### Changing Colors

Edit the CSS variables in `styles.css`:

```css
:root {
    --primary-color: #2563eb;    /* Main brand color */
    --secondary-color: #1e40af;  /* Secondary color */
    --accent-color: #3b82f6;     /* Accent color */
    /* ... more variables */
}
```

### Adding More Sections

1. Add HTML structure in `index.html`
2. Add corresponding styles in `styles.css`
3. Update navigation menu if needed

## Notes

- Make sure to add your `photo.jpg` file before opening the website
- Update social media links in the HTML if needed
- The website uses Font Awesome CDN for icons (requires internet connection)

## License

Free to use and modify for personal portfolios.

