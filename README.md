# College-landing-Page
# TechNova Institute — Website

A multi-page marketing site for TechNova Institute, a fictional college for builders. Built with plain HTML, CSS, and vanilla JavaScript — no build step, no framework, no dependencies to install.

## ✨ Features

- Fully static, framework-free (HTML/CSS/JS only)
- Responsive layout with a mobile nav toggle
- Scroll-reveal animations via `IntersectionObserver`
- Animated stat counters (Alumni page)
- Filterable program/faculty cards (Academics, Faculty)
- Accessible FAQ accordion (Admissions)
- Client-side contact form validation (Contact)
- Image gallery with lightbox (Campus Life)
- Expandable news feed (News & Events)
- 🍁 Site-wide falling & swaying **momiji (maple leaf)** animation, generated in JS and rendered on every page

## 📄 Pages

| Page | File |
|---|---|
| Home | `index.html` |
| About | `about.html` |
| Academics | `academics.html` |
| Faculty | `faculty.html` |
| Campus Life | `campus-life.html` |
| News & Events | `news.html` |
| Alumni | `alumni.html` |
| Admissions | `admissions.html` |
| Contact | `contact.html` |

## 🗂 Project Structure

```
.
├── index.html
├── about.html
├── academics.html
├── admissions.html
├── alumni.html
├── campus-life.html
├── contact.html
├── faculty.html
├── news.html
├── style.css       # design tokens, layout, components, momiji leaf animation
├── main.js         # nav, reveal animations, forms, filters, lightbox, momiji leaves
└── README.md
```

## 🛠 Tech Stack

- HTML5
- CSS3 (custom properties, `clamp()` for fluid type/spacing, no preprocessor)
- Vanilla JavaScript (ES6+, no dependencies)
- Google Fonts: Space Grotesk, Inter, JetBrains Mono

## 📦 Deploying

Since this is a static site, it can be hosted anywhere that serves static files, e.g.:

- **GitHub Pages** — push to a repo, then enable Pages on the `main` branch (`/root`) in Settings → Pages
- **Netlify / Vercel** — drag-and-drop the folder or connect the repo for automatic deploys
- Any static file host / CDN

## 📝 License

All rights reserved — TechNova Institute is a fictional brand used for demo purposes. Adapt freely for your own project.
