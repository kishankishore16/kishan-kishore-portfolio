# Kishan Kishore — Portfolio Website

A modern, dark-themed personal portfolio for a Data Scientist & ML Engineer.

## 📁 Project Structure

```
kishan-portfolio/
├── index.html          # Main HTML — all sections & markup
├── css/
│   └── style.css       # All styles, tokens, animations, responsive
├── js/
│   └── main.js         # Scroll-reveal via IntersectionObserver
├── assets/
│   └── profile.jpg     # Profile photo
└── README.md
```

## 🚀 Getting Started

No build step required — it's plain HTML/CSS/JS.

```bash
# Clone / download the folder, then open in browser:
open index.html

# Or serve locally with Python:
python3 -m http.server 8080
# Visit http://localhost:8080
```

## ✏️ Customisation Checklist

| What to change | Where |
|---|---|
| LinkedIn URL | `index.html` → contact section |
| GitHub URL | `index.html` → contact section |
| Project GitHub links | `index.html` → each `.project-card` href |
| Profile photo | Replace `assets/profile.jpg` |
| Accent colour | `css/style.css` → `--accent` token |

## 🛠 Tech Stack

- **HTML5** — semantic markup
- **CSS3** — custom properties, Grid, Flexbox, keyframe animations
- **Vanilla JS** — IntersectionObserver for scroll reveals
- **Google Fonts** — Syne · DM Mono · DM Sans

## 📄 Sections

1. **Hero** — Name, role, profile photo, animated skill bars, stats
2. **Projects** — Dog Breed Identifier · AI Study Optimizer · Dynamic Pricing Model
3. **Skills** — Programming · Data Science & ML · Data Analysis · Tools
4. **Achievements** — HackerRank 150+ DSA problems
5. **Education** — Alliance University B.Tech CS 2026
6. **Contact** — Email · LinkedIn · GitHub · Phone
