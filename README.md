# 🔐 HackerG Portfolio

[![Live Demo](https://img.shields.io/badge/Live-Demo-00d9ff?style=for-the-badge&logo=github-pages)](https://hackerg3121.github.io)
[![License: MIT](https://img.shields.io/badge/License-MIT-cyan.svg?style=for-the-badge)](LICENSE)
[![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

> **Cybersecurity Researcher & Ethical Hacker Portfolio**  
> A modern, interactive portfolio website featuring Matrix-style animations, dynamic content, and a cyberpunk aesthetic.

## 🌟 Features

- **🎨 Matrix Rain Animation** - Iconic Matrix-style falling characters background
- **📱 Fully Responsive** - Seamless experience across desktop, tablet, and mobile devices
- **🎯 Interactive UI** - Smooth animations and hover effects throughout
- **🔒 Security-Themed Design** - Cyberpunk aesthetic with cyan/dark color scheme
- **⚡ Performance Optimized** - Lightweight and fast-loading
- **♿ Accessible** - ARIA labels and semantic HTML structure

## 📋 Sections

1. **Home/Hero** - Introduction with social links and floating tech icons
2. **About** - Background, skills, and expertise overview
3. **Services** - Cybersecurity services offered
4. **Events** - Workshops, conferences, and talks
5. **Projects** - Portfolio showcase with project highlights
6. **Contact** - Get in touch section

## 🛠️ Technologies Used

- **HTML5** - Semantic markup structure
- **CSS3** - Custom styling with animations and transitions
- **Vanilla JavaScript** - Interactive features and Matrix canvas animation
- **Font Awesome 6.5.0** - Icon library for UI elements
- **Canvas API** - Matrix rain effect rendering

## 🚀 Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- Basic understanding of HTML/CSS/JS (for customization)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/HackerG3121/hackerg3121.github.io.git
   ```

2. **Navigate to the project directory**
   ```bash
   cd hackerg3121.github.io
   ```

3. **Open in your browser**
   ```bash
   # Simply open index.html in your browser
   # Or use a local server:
   python -m http.server 8000
   # Then visit http://localhost:8000
   ```

### Deployment

This site is designed to work with **GitHub Pages**:

1. Push your changes to the `main` branch
2. Go to repository Settings → Pages
3. Select `main` branch as source
4. Your site will be live at `https://yourusername.github.io`

## 📁 Project Structure

```
hackerg3121.github.io/
│
├── index.html              # Main HTML file
├── styles_v1.4.css        # Stylesheet with cyberpunk theme
├── script_v1.4.js         # JavaScript for interactions & Matrix effect
│
├── logo.png               # Main logo image
├── brand_name.png         # Brand name image
├── giri_a.jpeg           # Profile picture
│
├── PROJECTshowcase/      # Project screenshots
│   ├── project1.png
│   ├── project2.png
│   └── project3.png
│
├── .hintrc               # Webhint configuration
├── README.md             # Project documentation (this file)
└── LICENSE               # MIT License
```

## 🎨 Customization

### Changing Colors

Edit the CSS variables in `styles_v1.4.css`:

```css
:root {
    --primary-cyan: #00d9ff;
    --dark-bg: #0a0e27;
    --text-light: #e0e0e0;
    /* Add your custom colors here */
}
```

### Updating Content

1. **Personal Information** - Edit the hero section in `index.html`
2. **Projects** - Update project images in `PROJECTshowcase/` folder
3. **Social Links** - Modify links in the social-icons section
4. **About Section** - Customize your bio and skills

### Matrix Animation Settings

Adjust Matrix rain speed and density in `script_v1.4.js`:

```javascript
// Look for these variables:
fontSize = 16;  // Character size
speed = 1;      // Animation speed
```

## 📊 Performance

- ✅ Lightweight (~50KB total CSS + JS)
- ✅ Optimized Canvas animations
- ✅ Lazy-loaded images
- ✅ Minimal external dependencies

## 🔒 Security Features Showcase

This portfolio highlights expertise in:
- Ethical Hacking
- Penetration Testing
- Network Security
- Vulnerability Assessment
- Security Research

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](https://github.com/HackerG3121/hackerg3121.github.io/issues).

### How to Contribute

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

## 👤 Author

**Giri A**

- GitHub: [@HackerG4544](https://github.com/HackerG4544)
- LinkedIn: [giri-a](https://www.linkedin.com/in/giri-a-0457a4394)
- Twitter: [@Giri3121A](https://twitter.com/Giri3121A)
- Email: giriarumugam3121@gmail.com

## 🙏 Acknowledgments

- Matrix effect inspiration from the iconic movie franchise
- Font Awesome for the comprehensive icon library
- The cybersecurity community for continuous inspiration

## 📈 Future Enhancements

- [ ] Add blog section for security writeups
- [ ] Integrate dark/light theme toggle
- [ ] Add project filtering by category
- [ ] Include CTF scoreboard section
- [ ] Add contact form with backend integration
- [ ] Implement SEO optimizations
- [ ] Add accessibility improvements (WCAG 2.1 AAA)

## 🐛 Known Issues

No known issues at this time. Please report any bugs you find!

---

<div align="center">

**⭐ Star this repo if you find it useful! ⭐**

Made with 💙 and ☕ by Giri A

</div>
