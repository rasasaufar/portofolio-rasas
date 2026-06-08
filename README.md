# 🎨 Portofolio Rasas

> My first portfolio project — built from scratch while learning web development with HTML, Tailwind CSS, and vanilla JavaScript.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

## 📖 About

A simple, responsive portfolio website showcasing projects, client work, and certifications. Built as a learning project to understand HTML structure, Tailwind CSS utility classes, and DOM manipulation with vanilla JS.

## ✨ Features

- **Responsive Design** — mobile-first layout with hamburger menu
- **Dark Mode** — toggle with localStorage persistence
- **Navbar Fixed** — sticky navigation on scroll
- **Portfolio Showcase** — display projects with screenshots
- **Client Logos** — Gojek, Google, Tokopedia, Traveloka
- **Certificates Gallery** — showcase earned certifications
- **Back to Top** — smooth scroll button
- **Smooth Scrolling** — anchor-based navigation

## 🛠️ Tech Stack

| Layer | Technology |
|-------|------------|
| Markup | HTML5 |
| Styling | Tailwind CSS v3 |
| Scripting | Vanilla JavaScript |
| Dark Mode | Class-based toggle (`localStorage`) |
| Build | Tailwind CLI |

## 📁 Project Structure

portofolio-rasas/
├── index.html
├── package.json
├── tailwind.config.js
├── src/
│   └── input.css
├── dist/
│   ├── css/
│   │   └── final.css
│   ├── js/
│   │   └── script.js
│   └── img/
│       ├── logo.png
│       ├── rasas.png
│       ├── portfolio/
│       ├── clients/
│       └── sertifikat/
└── .gitignore
| Path | Description |
|------|-------------|
| `index.html` | Main page |
| `src/input.css` | Source CSS |
| `dist/css/final.css` | Compiled CSS |
| `dist/js/script.js` | Navbar, hamburger, dark mode |
| `dist/img/portfolio/` | Project screenshots |
| `dist/img/clients/` | Client logos (SVG) |
| `dist/img/sertifikat/` | Certificates (1-8.png) |

## 🚀 Getting Started
sh
Clone the repository
git clone https://github.com/rasasaufar/portofolio-rasas.git
cd portofolio-rasas

Install dependencies
npm install

Build CSS
npx tailwindcss -i src/input.css -o dist/css/final.css --watch

Open index.html in browser
## 📄 License

MIT

---

*Built with ❤️ by [rasasaufar](https://github.com/rasasaufar) — my first step into web development.*
