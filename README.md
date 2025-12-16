<div align="center">

# 🎨 Modern Product Showcase

### *Stunning glassmorphism design meets smooth animations*

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://github.com/ridhofri/modern-product-showcase/graphs/commit-activity)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](http://makeapullrequest.com)

<p align="center">
  <a href="#-demo">Demo</a> •
  <a href="#-features">Features</a> •
  <a href="#-installation">Installation</a> •
  <a href="#-usage">Usage</a> •
  <a href="#-contributing">Contributing</a>
</p>

![Showcase Animation](https://via.placeholder.com/800x400/1a1a1a/ff4500?text=Your+Amazing+Screenshot+Here)

</div>

---

## 🌟 Highlights

> A modern, responsive product showcase website featuring **glassmorphism design**, **parallax effects**, and **buttery-smooth animations**. Built with pure vanilla JavaScript—no frameworks, no dependencies, just clean code.

### ⚡ Why This Project?

- 🎯 **Zero Dependencies** - Pure HTML, CSS, and JavaScript
- 🚀 **Blazing Fast** - Optimized performance with lazy loading
- 💎 **Premium Design** - Modern glassmorphism UI/UX
- 📱 **Mobile First** - Fully responsive on all devices
- ♿ **Accessible** - Keyboard navigation & semantic HTML
- 🎨 **Customizable** - Easy to modify colors and content

---

## ✨ Features

<table>
<tr>
<td width="50%">

### 🎨 Design
- ✅ Glassmorphism effects
- ✅ Gradient animations
- ✅ Custom scroll snap
- ✅ Parallax backgrounds
- ✅ Backdrop blur effects
- ✅ Smooth transitions

</td>
<td width="50%">

### ⚡ Functionality
- ✅ Dynamic data loading
- ✅ Auto-retry on error
- ✅ Intersection Observer
- ✅ Ripple click effects
- ✅ Loading animations
- ✅ Keyboard navigation

</td>
</tr>
</table>

---

## 🎥 Demo

### 🔗 [**Live Demo →**](https://ridhofri.github.io/modern-product-showcase/)

<div align="center">

| Desktop | Mobile |
|---------|--------|
| ![Desktop](https://via.placeholder.com/400x250/1a1a1a/ffffff?text=Desktop+View) | ![Mobile](https://via.placeholder.com/200x350/1a1a1a/ffffff?text=Mobile+View) |

</div>

---

## 🚀 Quick Start

### Prerequisites

```bash
# You only need a modern browser!
✅ Chrome 90+ / Firefox 88+ / Safari 14+ / Edge 90+
```

### Installation

```bash
# 1. Clone the repository
git clone https://github.com/ridhofri/modern-product-showcase.git

# 2. Navigate to project folder
cd modern-product-showcase

# 3. Open with Live Server or any local server
# That's it! 🎉
```

### Run Locally

<details>
<summary><b>🟢 VS Code (Recommended)</b></summary>

```bash
# Install Live Server extension
# Right-click index.html → "Open with Live Server"
```
</details>

<details>
<summary><b>🐍 Python</b></summary>

```bash
# Python 3.x
python -m http.server 8000

# Open http://localhost:8000
```
</details>

<details>
<summary><b>🟩 Node.js</b></summary>

```bash
npx http-server -p 8000

# Open http://localhost:8000
```
</details>

<details>
<summary><b>🌐 Direct Open</b></summary>

```bash
# Simply double-click index.html
# (Some features may not work without a server)
```
</details>

---

## 📂 Project Structure

```
modern-product-showcase/
│
├── 📄 index.html              # Main landing page
├── 📄 detail.html             # Product detail page
├── 📄 README.md               # You are here!
│
├── 📁 assets/
│   ├── 📁 css/
│   │   └── 🎨 style.css       # All styles & animations
│   │
│   ├── 📁 js/
│   │   └── ⚡ script.js       # Interactive features
│   │
│   ├── 📁 images/
│   │   ├── 🖼️ main-image.jpg  # Hero background
│   │   └── 🖼️ product-*.jpg   # Product images
│   │
│   └── 📋 data.json           # Product database
│
└── 📄 .gitignore              # Git ignore rules
```

---

## 🎨 Customization

### 1️⃣ **Add New Products**

Edit `assets/data.json`:

```json
{
  "id": "product-id",
  "title": "Product Name",
  "subtitle": "Amazing product description",
  "image": "assets/images/your-image.jpg",
  "color": "Midnight Black",
  "battery": "24 Hours",
  "weight": "250g",
  "latency": "40ms",
  "price": "Rp 2.500.000"
}
```

### 2️⃣ **Change Color Scheme**

In `assets/css/style.css`:

```css
/* Primary Colors */
--primary-orange: #ff4500;
--secondary-orange: #ff6347;

/* Backgrounds */
--dark-bg: #0f110f;
--glass-bg: rgba(255, 255, 255, 0.1);
```

### 3️⃣ **Modify Animations**

```css
/* Animation Duration */
.product-content {
  transition: all 0.4s ease; /* Change to 0.6s for slower */
}

/* Animation Delay */
.stat:nth-child(1) { animation-delay: 0.1s; }
.stat:nth-child(2) { animation-delay: 0.2s; }
```

---

## 🛠️ Technologies

<div align="center">

| Technology | Purpose | Version |
|------------|---------|---------|
| ![HTML5](https://img.shields.io/badge/-HTML5-E34F26?style=flat&logo=html5&logoColor=white) | Markup | 5 |
| ![CSS3](https://img.shields.io/badge/-CSS3-1572B6?style=flat&logo=css3&logoColor=white) | Styling | 3 |
| ![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black) | Logic | ES6+ |
| ![Git](https://img.shields.io/badge/-Git-F05032?style=flat&logo=git&logoColor=white) | Version Control | Latest |

</div>

### Key APIs Used

- 🔍 **Intersection Observer** - Scroll-triggered animations
- 📡 **Fetch API** - Async data loading
- 🎭 **CSS Backdrop Filter** - Glassmorphism effects
- 📜 **Scroll Snap** - Smooth section transitions

---

## 📊 Performance

<div align="center">

| Metric | Score | Status |
|--------|-------|--------|
| Performance | 95+ | 🟢 Excellent |
| Accessibility | 90+ | 🟢 Great |
| Best Practices | 95+ | 🟢 Excellent |
| SEO | 90+ | 🟢 Great |

</div>

### Optimization Features

✅ **Lazy Loading** - Images load as needed  
✅ **CSS Transforms** - GPU-accelerated animations  
✅ **Debounced Events** - Optimized scroll handlers  
✅ **Minimal DOM** - Efficient rendering  
✅ **Compressed Assets** - Fast load times  

---

## 📱 Responsive Design

```css
/* Breakpoints */
Mobile:  < 768px   → Stack layout, touch-optimized
Tablet:  768-1024px → Hybrid layout
Desktop: > 1024px  → Full parallax experience
```

<div align="center">

| Device | Experience |
|--------|-----------|
| 📱 Mobile | Touch-friendly, optimized animations |
| 📱 Tablet | Balanced layout, smooth scrolling |
| 💻 Desktop | Full parallax, all effects enabled |
| 🖥️ Large Desktop | Enhanced visuals, maximum impact |

</div>

---

## 🌐 Browser Support

<div align="center">

| Browser | Minimum Version | Status |
|---------|----------------|--------|
| ![Chrome](https://img.shields.io/badge/-Chrome-4285F4?style=flat&logo=google-chrome&logoColor=white) | 90+ | ✅ Fully Supported |
| ![Firefox](https://img.shields.io/badge/-Firefox-FF7139?style=flat&logo=firefox&logoColor=white) | 88+ | ✅ Fully Supported |
| ![Safari](https://img.shields.io/badge/-Safari-000000?style=flat&logo=safari&logoColor=white) | 14+ | ✅ Fully Supported |
| ![Edge](https://img.shields.io/badge/-Edge-0078D7?style=flat&logo=microsoft-edge&logoColor=white) | 90+ | ✅ Fully Supported |
| ![Opera](https://img.shields.io/badge/-Opera-FF1B2D?style=flat&logo=opera&logoColor=white) | 76+ | ✅ Fully Supported |

</div>

---

## 🎓 Learning Resources

Built this project and want to learn more?

- 📚 [MDN Web Docs](https://developer.mozilla.org/) - Complete web development guide
- 🎨 [CSS Tricks](https://css-tricks.com/) - CSS techniques and tricks
- ⚡ [JavaScript.info](https://javascript.info/) - Modern JavaScript tutorial
- 🎭 [Glassmorphism Generator](https://hype4.academy/tools/glassmorphism-generator) - Create glass effects

---

## 🤝 Contributing

Contributions make the open-source community amazing! Any contributions are **greatly appreciated**.

<details>
<summary><b>📝 How to Contribute</b></summary>

1. **Fork** the Project
2. **Create** your Feature Branch
   ```bash
   git checkout -b feature/AmazingFeature
   ```
3. **Commit** your Changes
   ```bash
   git commit -m "Add some AmazingFeature"
   ```
4. **Push** to the Branch
   ```bash
   git push origin feature/AmazingFeature
   ```
5. **Open** a Pull Request

</details>

### 🐛 Found a Bug?

[Report it here →](https://github.com/ridhofri/modern-product-showcase/issues)

### 💡 Have an Idea?

[Share it here →](https://github.com/ridhofri/modern-product-showcase/discussions)

---

## 📜 License

Distributed under the **MIT License**. See `LICENSE` for more information.

```
MIT License - feel free to use this project for personal or commercial purposes!
```

---

## 👨‍💻 Author

<div align="center">

### **RIDHOFIR**

[![GitHub](https://img.shields.io/badge/-GitHub-181717?style=flat&logo=github)](https://github.com/ridhofri)
[![LinkedIn](https://img.shields.io/badge/-LinkedIn-0A66C2?style=flat&logo=linkedin)](https://linkedin.com/in/yourprofile)
[![Twitter](https://img.shields.io/badge/-Twitter-1DA1F2?style=flat&logo=twitter&logoColor=white)](https://twitter.com/yourhandle)
[![Email](https://img.shields.io/badge/-fikrishodiqridhofir@gmail.com-D14836?style=flat&logo=gmail&logoColor=white)](mailto:your.fikrishodiqridhofir@gmail.com)
[![Portfolio](https://img.shields.io/badge/-Portfolio-000000?style=flat&logo=vercel&logoColor=white)](https://yourportfolio.com)

*Full-stack Developer | UI/UX Enthusiast | Open Source Contributor*

</div>

---

## 🙏 Acknowledgments

Special thanks to:

- 🎨 [Dribbble](https://dribbble.com) - Design inspiration
- 💎 [Michal Malewicz](https://hype4.academy/) - Glassmorphism concept
- 🔤 [Google Fonts](https://fonts.google.com/) - Days One font
- 🎭 [Shields.io](https://shields.io/) - Awesome badges
- 💡 The open-source community

---

## 📈 Project Stats

<div align="center">

![GitHub stars](https://img.shields.io/github/stars/ridhofri/modern-product-showcase?style=social)
![GitHub forks](https://img.shields.io/github/forks/ridhofri/modern-product-showcase?style=social)
![GitHub watchers](https://img.shields.io/github/watchers/ridhofri/modern-product-showcase?style=social)
![GitHub issues](https://img.shields.io/github/issues/ridhofri/modern-product-showcase)
![GitHub pull requests](https://img.shields.io/github/issues-pr/ridhofri/modern-product-showcase)
![GitHub last commit](https://img.shields.io/github/last-commit/ridhofri/modern-product-showcase)

</div>

---

## 💖 Support

If you found this project helpful:

- ⭐ **Star** this repository
- 🐛 **Report** bugs and issues
- 💡 **Suggest** new features
- 🤝 **Contribute** to the code
- 📢 **Share** with others

---

<div align="center">

### 🚀 Ready to Build Something Amazing?

**[⬆ Back to Top](#-modern-product-showcase)**

---

**Made with ❤️ and ☕ by [Your Name](https://github.com/ridhofri)**

*"Great design is invisible. Great code is elegant."*

---

[![Visitors](https://api.visitorbadge.io/api/visitors?path=ridhofri%2Fmodern-product-showcase&label=Visitors&countColor=%23ff4500&style=flat)](https://visitorbadge.io/status?path=ridhofri%2Fmodern-product-showcase)

</div>