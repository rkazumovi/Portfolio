# 👨‍💻 Personal Portfolio Website

<p align="center">
  <img width="480" height="480" alt="Portfolio preview" src="https://github.com/user-attachments/assets/ce01000b-4261-4f02-b456-799e8c5e684f" />
</p>

A modern, responsive personal portfolio website showcasing my background, skills, and services as a Software Engineer, built with vanilla HTML, CSS, and JavaScript — no frameworks, no build step.

🌐 **Live Demo:** [my-tech-portfolio.netlify.app](https://my-tech-portfolio.netlify.app/)
📂 **Repository:** [github.com/rkazumovi/Portfolio](https://github.com/rkazumovi/Portfolio)

![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)
![Netlify](https://img.shields.io/badge/Deployed%20on-Netlify-00C7B7?logo=netlify&logoColor=white)

---

## Overview

This single-page portfolio presents a professional introduction, an "About Me" section, a services showcase, and a contact section — all built as a lightweight, dependency-free static site. The layout emphasizes clean design, smooth scroll-based navigation, and full responsiveness across devices.

## ✨ Features

- 👋 Hero section with a professional introduction and a CSS-only animated typewriter effect cycling through role titles
- 📄 Dedicated "About Me" section
- 💼 Services showcase covering Web Development, Frontend Development, Backend Development, and Software Development
- 📬 Contact section with a name/email/phone/subject/message form
- 🔗 Social links (Instagram, LinkedIn, GitHub, GitLab)
- 🧭 Scroll-aware navigation bar that highlights the active section as you scroll
- 📱 Responsive mobile menu with toggle icon
- 🎨 Custom CSS theming via CSS variables (color palette, backgrounds)
- ⚡ Zero-dependency static site — no build step, no bundler required

## 🏗️ Sections

| Section | Description |
|---|---|
| **Home** | Hero introduction with name, animated role titles, and social links |
| **About** | Overview of background and experience |
| **Services** | Web Development, Frontend Development, Backend Development, Software Development |
| **Contact** | Contact form (name, email, phone, subject, message) |

## 🛠️ Built With

**Languages**
- HTML5 — semantic page structure and markup
- CSS3 — styling, responsive layout, and CSS-variable-based theming; includes a hand-built CSS keyframe typewriter animation (no JS animation library)
- JavaScript (Vanilla) — scroll-based active-nav-link tracking and mobile menu toggle

**Libraries**
- [Boxicons](https://boxicons.com/) — icon set, loaded via CDN

**Tools & Deployment**
- [Git](https://git-scm.com/) — version control
- [GitHub](https://github.com/) — source hosting
- [Netlify](https://www.netlify.com/) — static site hosting and deployment

## 🚀 Getting Started

### Prerequisites

- A modern web browser
- [Git](https://git-scm.com/)

### Installation

1. Clone the repository
   ```bash
   git clone https://github.com/rkazumovi/Portfolio.git
   cd Portfolio
   ```

2. Open `index.html` directly in your browser, or serve the folder with any static file server (e.g. VS Code Live Server) for the best local experience.

No package manager, build step, or dependencies are required — this is a pure static site.

## 📁 Project Structure

```
Portfolio/
├── index.html            # Main page markup and all sections
├── style.css              # All styling, layout, and animations
├── script.js               # Scroll-based nav highlighting and mobile menu toggle
├── main-image.png          # Profile/hero image
└── portfolio-icon.png      # Favicon
```

## 📱 Responsive Design

The layout adapts across desktop, tablet, and mobile breakpoints, including a collapsible mobile navigation menu.

## 📦 Deployment

The site is deployed with **Netlify** and is live at:
👉 [my-tech-portfolio.netlify.app](https://my-tech-portfolio.netlify.app/)

## 🤝 Contributing

Contributions and suggestions are always welcome.

1. Fork the repository
2. Create your feature branch
   ```bash
   git checkout -b feature/new-feature
   ```
3. Commit your changes
   ```bash
   git commit -m "Add new feature"
   ```
4. Push to the branch
   ```bash
   git push origin feature/new-feature
   ```
5. Open a Pull Request

---

<p align="center">⭐ If you found this project interesting, consider giving it a star on GitHub!</p>
