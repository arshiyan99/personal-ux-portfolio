# Personal UX/UI Portfolio Website

A modern, high-performance, and fully responsive personal portfolio website designed explicitly for UX/UI Designers, Product Designers, and Front-End Developers. This repository contains the complete codebase, assets, and styling framework needed to spin up an interactive, personalized landing page to showcase digital work.

## 🚀 Live Demo
https://arshiyan-sayyad.netlify.app/

---

## 🎨 Features

- **Fully Responsive Architecture:** Optimized across standard desktop viewports, tablets, and smartphones.
- **Dynamic Style Switcher:** Allows visitors to customize their viewing experience interactively.
- **Multiple Visual Themes:** Pre-configured with 5 standalone custom color accents (`color-1.css` to `color-5.css`).
- **Media-Rich Portfolio Grid:** High-fidelity project item display optimized for image assets.
- **Clean Project Directory:** Well-structured separation of assets (CSS, JS, Images) for simple maintenance.

---

## 📁 Repository Structure

```text
my portfolio/
│
├── index.html                  # Main markup entry point
├── css/
│   ├── style.css               # Global core layout framework
│   ├── style-switcher.css      # Core styles for the dynamic skin toggler
│   └── skin/
│       ├── color-1.css         # Accent Theme 1
│       ├── color-2.css         # Accent Theme 2
│       ├── color-3.css         # Accent Theme 3
│       ├── color-4.css         # Accent Theme 4
│       └── color-5.css         # Accent Theme 5
│
├── js/
│   ├── script.js               # Global site interactivity behaviors
│   └── style-switcher.js       # Dynamic style-switching runtime logic
│
└── images/
    ├── me.jpeg                 # Profile banner image
    ├── icon.jpg                # Site favicon / asset logo
    └── portfolio/
        ├── port1.png           # Portfolio Showcase Project 1
        ├── port2.png           # Portfolio Showcase Project 2
        ├── port3.png           # Portfolio Showcase Project 3
        ├── port33.png          # Portfolio Showcase Project 4
        ├── port4.png           # Portfolio Showcase Project 5
        └── port5.png           # Portfolio Showcase Project 6
```

---

## 🛠️ Installation & Customization

### 1. Clone the Repository
```bash
git clone https://github.com
cd personal-ux-portfolio
```

### 2. Update Content
Open `index.html` in your favorite IDE to replace placeholders with your name, bio, case studies, and experience details.

### 3. Change Profile & Project Imagery
Drop your assets directly into the designated folders inside `images/` to swap them seamlessly:
- Replace `images/me.jpeg` with your dynamic profile headshot.
- Replace items inside `images/portfolio/` with mockups or screens of your product designs.

### 4. Switch Default Accent Theme
By default, the global core loads standard styling profiles. You can change the primary default visual accent by modifying the stylesheet link target inside the `<head>` block of your `index.html`.

---

## 💻 Tech Stack Used

- **HTML5:** Semantic markup structure.
- **CSS3:** Custom layouts, transitions, grid mapping, variables, and responsive media queries.
- **JavaScript (ES6):** Dynamic interactions, dynamic DOM manipulation, and dynamic runtime style switching.

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE). Feel free to customize and use it for your personal brand!
