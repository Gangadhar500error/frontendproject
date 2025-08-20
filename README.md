# Tailwind CSS Basic Setup

A clean, modern HTML template with Tailwind CSS featuring a responsive header, hero section, and footer.

## Features

- ✅ **Responsive Design** - Works on all screen sizes
- ✅ **Modern UI** - Clean and professional design
- ✅ **Tailwind CSS** - Utility-first CSS framework
- ✅ **Hero Section** - Eye-catching landing area
- ✅ **Navigation Header** - Mobile-friendly navigation
- ✅ **Feature Cards** - Showcase your services
- ✅ **Footer** - Complete with social links and contact info

## Quick Start

1. **Open the HTML file**
   ```bash
   # Simply open index.html in your browser
   # Or use a local server for development
   ```

2. **Using a Local Server (Recommended)**
   ```bash
   # Using Python 3
   python -m http.server 8000
   
   # Using Node.js (if you have http-server installed)
   npx http-server
   
   # Using PHP
   php -S localhost:8000
   ```

3. **View in Browser**
   - Navigate to `http://localhost:8000` (or your chosen port)
   - The page should load with all Tailwind CSS styles applied

## File Structure

```
tailwind-html/
├── index.html          # Main HTML file with all components
├── README.md           # This file
├── package.json        # Node.js dependencies (if any)
└── node_modules/       # Node.js modules (if any)
```

## Components Included

### Header
- Responsive navigation menu
- Mobile hamburger menu button
- Company logo area
- Clean, modern design

### Hero Section
- Gradient background
- Call-to-action buttons
- Responsive layout
- Hero illustration placeholder

### Main Content
- Feature cards with icons
- Responsive grid layout
- Clean typography

### Footer
- Company information
- Quick links
- Contact details
- Social media icons
- Copyright notice

## Customization

### Colors
The template uses a custom color scheme defined in the Tailwind config:

```javascript
tailwind.config = {
    theme: {
        extend: {
            colors: {
                primary: '#3B82F6',    // Blue
                secondary: '#1F2937',  // Dark gray
            }
        }
    }
}
```

### Content
- Replace "Logo" with your company name
- Update hero section text and buttons
- Modify feature cards with your services
- Update footer contact information
- Replace social media links

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## Dependencies

- **Tailwind CSS** - Loaded via CDN for simplicity
- **No other dependencies required**

## Development

For production use, consider:

1. **Installing Tailwind CSS locally** for better performance
2. **Building a custom CSS file** to reduce file size
3. **Adding JavaScript** for mobile menu functionality
4. **Optimizing images** and assets

## License

This template is free to use for personal and commercial projects.

---

**Happy coding! 🚀**
