# Alison Avery Personal Website

A modern, responsive personal portfolio website built with vanilla HTML5, CSS3, and ES6+ JavaScript. Features a stunning purple and teal color scheme with smooth animations and interactive elements.

## Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- A text editor (VS Code, Sublime Text, etc.)
- Basic understanding of HTML, CSS, and JavaScript

### Installation

1. **Clone or download** this repository to your local machine

2. **Navigate** to the project directory

3. **Open** `index.html` in your web browser
   - Double-click the file, or
   - Right-click and select "Open with" your preferred browser, or
   - Use a local development server (recommended)

### Using a Local Server (Recommended)

For the best experience, use a local development server:

**Option 1: Python**

```bash
# Python 3
python -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000
```

**Option 2: Node.js (http-server)**

```bash
npx http-server
```

**Option 3: VS Code Live Server Extension**

- Install the "Live Server" extension
- Right-click on `index.html`
- Select "Open with Live Server"

Then navigate to `http://localhost:8000` (or the port shown)

## Files

- `index.html`: The main HTML file, homepage
- `styles.css`: Shared CSS stylesheet for consistent styling
- `main.js`: The JavaScript code for smooth scrolling and animations
- `about.html`': About page with personal story and interests
- `work.html`': Work page with experience, projects, awards, and certifications

## Features

- Prettier for code styling
- ESLint for code quality
- **Modern Design**: Beautiful gradient backgrounds with purple and teal color scheme
- **Fully Responsive**: Works seamlessly on desktop, tablet, and mobile devices
- **Smooth Animations**: Fade-in effects, hover transitions, and scroll animations
- **Interactive Elements**: Glowing buttons, animated cards, and dynamic navigation
- **Clean Code**: Organized file structure with separated concerns (HTML, CSS, JS)
- **No Dependencies**: Built entirely with vanilla JavaScript - no frameworks or libraries required
- **ES6+ JavaScript**: Modern JavaScript features including modules, arrow functions, and Intersection Observer API

## 🛠️ Technical Details

### Technologies Used

- **HTML5**: Semantic markup and structure
- **CSS3**: Modern styling with flexbox, grid, gradients, and animations
- **JavaScript ES6+**: Modules, arrow functions, Intersection Observer API
- **No frameworks or libraries**: Pure vanilla implementation

### Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

### Key Features Implementation

**Smooth Scrolling**
- Uses native `scrollIntoView()` with smooth behavior
- Handled in `main.js`

**Scroll Animations**
- Intersection Observer API for performance
- Fade-in effects as elements come into view

**Responsive Design**
- CSS Grid and Flexbox for layouts
- Mobile-first approach with media queries
- Breakpoint at 768px for mobile devices

## 📝 Code Quality

- **Clean Separation**: HTML, CSS, and JavaScript in separate files
- **Semantic HTML**: Proper use of semantic elements
- **CSS Organization**: Logical grouping with clear comments
- **Modern JavaScript**: ES6+ features and best practices
- **No Inline Styles**: All styling in external CSS file
- **Accessible**: Proper alt text, semantic markup, and keyboard navigation


## License

This project is open source and available for personal and commercial use.

## Contributing

Feel free to fork this project and customize it for your own portfolio!

## Contact

- **Email**: john@example.com
- **LinkedIn**: [Your LinkedIn](https://linkedin.com)
- **GitHub**: [Your GitHub](https://github.com)
- **Portfolio**: [Your Website](https://yourwebsite.com)

## 🙏 Acknowledgments

- Design inspiration from modern web trends
- Color palette: Purple and Teal gradient theme
- Icons: Unicode emoji characters
- Fonts: System fonts for optimal performance

---

**Built with 💜 and vanilla JavaScript**