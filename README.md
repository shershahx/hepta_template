# Hepta - Travel Website Template

A modern, responsive travel website template built with HTML, CSS, and JavaScript. Perfect for travel agencies, tour operators, or travel bloggers.

## Features

- **Responsive Design**: Fully responsive layout that works on all devices
- **Modern UI**: Clean and attractive user interface with smooth animations
- **Multiple Pages**: Home, Destinations, About, and Contact pages
- **Interactive Elements**: Mobile navigation, form validation, and smooth scrolling
- **No Dependencies**: Pure HTML, CSS, and JavaScript (only uses Font Awesome for icons via CDN)
- **Easy to Customize**: Well-organized code structure and CSS variables for easy theming

## Pages

### Home (index.html)
- Hero section with call-to-action
- Features showcase
- Popular destinations preview
- Customer testimonials
- Call-to-action section

### Destinations (destinations.html)
- Comprehensive list of travel destinations
- Destination cards with images, descriptions, and pricing
- Hover effects and interactive elements

### About (about.html)
- Company information
- Mission and vision statements
- Core values
- Team statistics
- Team member profiles

### Contact (contact.html)
- Contact form with validation
- Contact information
- Office location details
- Social media links
- Map placeholder

## Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Modern styling with CSS Grid and Flexbox
- **JavaScript**: Interactive features and form validation
- **Font Awesome**: Icon library (via CDN)

## Getting Started

1. Clone or download this repository
2. Open `index.html` in your web browser
3. No build process or dependencies required!

## Customization

### Colors
Edit the CSS variables in `css/style.css`:

```css
:root {
    --primary-color: #4a90e2;
    --secondary-color: #26a69a;
    --accent-color: #ff6b6b;
    --dark-color: #2c3e50;
    --light-color: #ecf0f1;
}
```

### Images
Add your own images to the `images/` directory. The template uses placeholder SVG images that will be replaced when actual images are available. See `images/README.md` for the list of image filenames.

### Content
Update the text content directly in the HTML files. All content is clearly structured with semantic HTML.

## File Structure

```
hepta_template/
├── index.html           # Home page
├── destinations.html    # Destinations listing
├── about.html          # About page
├── contact.html        # Contact page
├── css/
│   └── style.css       # Main stylesheet
├── js/
│   └── script.js       # JavaScript functionality
├── images/
│   └── README.md       # Image requirements
└── README.md           # This file
```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## Features Breakdown

### Navigation
- Sticky header that stays at the top while scrolling
- Mobile-responsive hamburger menu
- Active page highlighting
- Smooth scroll to anchor links

### Animations
- Fade-in animations on scroll
- Hover effects on cards and buttons
- Smooth transitions throughout

### Forms
- Client-side validation
- User-friendly error messages
- Success feedback

## Future Enhancements

Potential features that could be added:
- Backend integration for contact form
- Booking system
- Blog section
- Image gallery/lightbox
- Search functionality
- Multi-language support
- Dark mode

## License

This template is free to use for personal and commercial projects.

## Credits

Created as a modern travel website template. Uses Font Awesome for icons.

## Support

For issues or questions, please open an issue in the repository.