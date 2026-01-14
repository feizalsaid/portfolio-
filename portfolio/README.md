# Professional Portfolio

A modern, responsive portfolio website built with HTML, Tailwind CSS, and JavaScript.

## Features

- 🎨 Modern and clean design with Tailwind CSS
- 📱 Fully responsive (mobile, tablet, desktop)
- ⚡ Smooth animations and transitions
- 🧭 Smooth scrolling navigation
- 📧 Contact form
- 🎯 SEO Optimized
- ♿ Accessible design
- 🚀 Latest Tailwind CSS Version
- ✅ W3 Validated Code Structure
- 🌐 Cross Browser Compatibility
- ⚡ Optimized Performance
- 📚 Well Documented

## Sections

- **Hero Section**: Eye-catching introduction with call-to-action buttons
- **About**: Personal introduction and key statistics
- **Skills**: Showcase of technical skills and technologies
- **Projects**: Portfolio of featured projects
- **Contact**: Contact information and message form

## Getting Started

### Prerequisites

No prerequisites needed! This is a static website that runs in any modern web browser.

### Installation

1. Clone or download this repository
2. Open `index.html` in your web browser

### Local Development

For a better development experience, you can use a local server:

#### Using Python 3
```bash
python3 -m http.server 8000
```

#### Using Node.js (with http-server)
```bash
npx http-server -p 8000
```

Then open `http://localhost:8000` in your browser.

## Technology Stack

- **HTML5**: Semantic markup
- **Tailwind CSS**: Utility-first CSS framework (via CDN)
- **JavaScript**: Interactive functionality
- **Font**: Inter (Google Fonts)

## Customization

### Personal Information

1. **Hero Section** (`index.html`):
   - Update your name in the hero section
   - Modify the title/role
   - Update the description

2. **About Section**:
   - Edit the about text
   - Update statistics (projects count, years of experience, etc.)

3. **Skills Section**:
   - Add or remove skill categories
   - Update skill tags to match your expertise

4. **Projects Section**:
   - Replace placeholder projects with your actual projects
   - Update project descriptions, tags, and links

5. **Contact Section**:
   - Update email address
   - Add your GitHub profile URL
   - Configure form submission (currently shows an alert)

### Colors

The color scheme can be customized in `index.html` by modifying the Tailwind config:

```javascript
tailwind.config = {
    theme: {
        extend: {
            colors: {
                'charcoal': '#1E1E1E',
                'dark-neutral': '#2D2D2D',
                'soft-gray': '#E0E0E0',
                'vibrant-blue': '#3B82F6',
                // Add your custom colors here
            },
        }
    }
}
```

### Production Build (Optional)

For production, consider using Tailwind CLI for smaller CSS bundle:

1. Install Tailwind CSS:
```bash
npm install -D tailwindcss
```

2. Initialize Tailwind config:
```bash
npx tailwindcss init
```

3. Build CSS:
```bash
npx tailwindcss -i ./src/input.css -o ./dist/output.css --minify
```

## Contact Form

The contact form currently shows an alert on submission. To make it functional:

1. Set up a backend service (e.g., Formspree, EmailJS, or your own server)
2. Update the form submission handler in `script.js`
3. Configure the endpoint to handle form submissions

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Performance

- Uses Tailwind CSS CDN for fast loading
- Minimal custom CSS for animations only
- Optimized images and assets
- Fast page load times

## License

This project is open source and available under the MIT License.

## Credits

- **Framework**: [Tailwind CSS](https://tailwindcss.com/)
- **Font**: [Inter](https://fonts.google.com/specimen/Inter) by Google Fonts
- **Icons and graphics**: Custom CSS

---

Built with ❤️ using HTML, Tailwind CSS & JavaScript
