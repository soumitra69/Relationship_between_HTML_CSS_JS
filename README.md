# Relationship Between HTML, CSS & JavaScript

## Project Overview

This project demonstrates the fundamental relationship and interaction between HTML, CSS, and JavaScript in modern web development. Through interactive examples and visual demonstrations, users can understand how these three core technologies work together to create dynamic web experiences.

## 🌟 Features

- Interactive body scanner demonstration
- Visual representation of HTML structure
- CSS styling examples and effects  
- JavaScript functionality integration
- Responsive design principles
- Modern web development practices

## 🚀 Live Demo

Visit the live demo: [https://soumitra69.github.io/Relationship_between_HTML_CSS_JS/](https://soumitra69.github.io/Relationship_between_HTML_CSS_JS/)

## 📋 Technologies Used

- **HTML5** - Structure and semantic markup
- **CSS3** - Styling, animations, and responsive design
- **JavaScript** - Interactive functionality and dynamic behavior
- **GitHub Pages** - Hosting and deployment

## 🛠️ Installation & Setup

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- Basic understanding of web development concepts

### Local Development

1. **Clone the repository**
   ```bash
   git clone https://github.com/soumitra69/Relationship_between_HTML_CSS_JS.git
   ```

2. **Navigate to project directory**
   ```bash
   cd Relationship_between_HTML_CSS_JS
   ```

3. **Open in browser**
   - Simply open `index.html` in your preferred web browser
   - Or use a local server:
   ```bash
   # Using Python 3
   python -m http.server 8000
   
   # Using Node.js (if you have http-server installed)
   npx http-server
   ```

4. **View the project**
   - Open your browser and navigate to `http://localhost:8000`

## 📁 Project Structure

```
Relationship_between_HTML_CSS_JS/
│
├── index.html          # Main HTML file
├── styles/
│   ├── main.css        # Primary stylesheet
│   └── responsive.css  # Responsive design styles
├── scripts/
│   ├── app.js          # Main JavaScript functionality
│   └── scanner.js      # Body scanner specific code
├── assets/
│   ├── images/         # Project images
│   └── icons/          # Icon files
├── README.md           # Project documentation
└── LICENSE            # License information
```

## 🎯 Learning Objectives

This project helps understand:

1. **HTML (Structure)**
   - Semantic markup
   - Document structure
   - Accessibility considerations

2. **CSS (Presentation)**
   - Styling and layout
   - Responsive design
   - Animations and transitions

3. **JavaScript (Behavior)**
   - DOM manipulation
   - Event handling
   - Interactive features

## 💡 Key Concepts Demonstrated

- **Separation of Concerns**: How HTML, CSS, and JS each handle different aspects
- **Progressive Enhancement**: Building from basic HTML up
- **Responsive Design**: Adapting to different screen sizes
- **Interactive Elements**: Mouse events and dynamic content
- **Modern Web Standards**: Using current best practices

## 🔧 Configuration

No special configuration required. The project works out of the box with any modern web browser.

### Browser Compatibility
- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+

## 📊 Usage Examples

### Basic HTML Structure
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>HTML CSS JS Relationship</title>
    <link rel="stylesheet" href="styles/main.css">
</head>
<body>
    <div class="scanner-container">
        <!-- Interactive content here -->
    </div>
    <script src="scripts/app.js"></script>
</body>
</html>
```

### CSS Integration
```css
.scanner-container {
    display: flex;
    justify-content: center;
    align-items: center;
    min-height: 100vh;
    background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
}
```

### JavaScript Functionality
```javascript
document.addEventListener('DOMContentLoaded', function() {
    const scanner = document.querySelector('.scanner');
    scanner.addEventListener('mouseover', handleScanEvent);
});
```

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

### How to Contribute

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author

**Soumitra69**
- GitHub: [@soumitra69](https://github.com/soumitra69)
- Project Link: [https://github.com/soumitra69/Relationship_between_HTML_CSS_JS](https://github.com/soumitra69/Relationship_between_HTML_CSS_JS)

## 🙏 Acknowledgments

- Modern web development community
- MDN Web Docs for comprehensive references
- GitHub Pages for free hosting
- All contributors who help improve this project

## 📞 Contact

If you have any questions, suggestions, or issues, please feel free to:
- Open an issue on GitHub
- Reach out via GitHub profile

---

⭐ If you found this project helpful, please give it a star on GitHub!

## 📚 Additional Resources

- [MDN Web Docs](https://developer.mozilla.org/)
- [W3Schools](https://www.w3schools.com/)
- [JavaScript.info](https://javascript.info/)
- [CSS-Tricks](https://css-tricks.com/)

---

Made with ❤️ for learning web development fundamentals
