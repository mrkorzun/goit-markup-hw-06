# WebStudio — Responsive Landing Page

A multi-section marketing landing page for a fictional digital agency, **WebStudio**. This was my **first complete landing page** built from scratch as part of the GoIT Markup course (final homework, HW-06), focused on delivering a pixel-accurate, fully responsive implementation of a real-world Figma design.

🔗 **Live demo:** [mrkorzun.github.io/goit-markup-hw-06](https://mrkorzun.github.io/goit-markup-hw-06/)

---

## 📋 Project Overview

The project reproduces a complete corporate landing page based on a provided Figma mockup. It consists of a single page (`index.html`) with multiple semantic sections — Hero, Advantages, Team, Portfolio — plus a footer with a newsletter subscription form and a modal contact form.

The main goal of this assignment was to demonstrate a solid command of **HTML5**, **CSS3**, **responsive design**, and **mobile-first methodology** — without using any frameworks, preprocessors, or JavaScript libraries.

---

## ✨ Key Features

- **Fully responsive layout** built with a **mobile-first** approach, supporting three breakpoints:
  - Mobile (up to 767px)
  - Tablet (768px – 1157px)
  - Desktop (1158px and above)
- **Adaptive images** served at the appropriate resolution per breakpoint, including **2x retina versions** via `srcset`.
- **Mobile navigation menu** with a slide-in panel and hamburger toggle.
- **Modal window** for the contact form, with overlay, smooth open/close transitions, and an accessible close button.
- **Custom-styled form elements** — text inputs with icons, a textarea, and a styled checkbox with an SVG check mark.
- **Newsletter subscription form** in the footer.
- **Hover and focus states** on all interactive elements (buttons, links, social icons, portfolio cards).
- **Animated portfolio overlay** — a translateY transition reveals project descriptions on hover.
- **SVG icon system** powered by an external sprite for crisp, scalable iconography.
- **Cross-browser CSS reset** via `modern-normalize`.

---

## 🛠 Tech Stack & Skills Demonstrated

### Languages & Markup

- **HTML5** — semantic tags (`<header>`, `<main>`, `<section>`, `<footer>`, `<address>`, `<nav>`), proper heading hierarchy, accessible form labels, ARIA-friendly attributes.
- **CSS3** — Flexbox, CSS Grid, custom properties, transitions, transforms, pseudo-classes, and pseudo-elements.

### Responsive & Adaptive Design

- Mobile-first methodology with progressively layered media queries.
- Adaptive imagery using `<picture>`, `srcset`, and `media` attributes.
- Retina-ready assets (`@1x` and `@2x`).

### UI/UX Implementation

- Pixel-perfect implementation from a Figma design.
- Smooth CSS transitions and keyframe-free animations.
- Modal dialogs and slide-in mobile menu without external JavaScript libraries.
- Custom-styled checkboxes and form controls.

### Tooling & Workflow

- **Git & GitHub** — version control with a clean commit history (18 incremental commits across the course).
- **GitHub Pages** — continuous deployment of the live demo.
- **VS Code** — primary editor.
- **Figma** — reading and translating design specs into code.

---

## 📁 Project Structure

```
goit-markup-hw-06/
├── css/
│   └── styles.css          # All styles, organized by section, mobile-first
├── images/
│   ├── hero/               # Hero background images (mob/tab/desk, @1x/@2x)
│   ├── team/               # Team member photos
│   ├── portfolio/          # Portfolio thumbnails
│   └── icons.svg           # SVG sprite for icons
├── index.html              # Single-page markup
└── README.md
```

---

## 🚀 Running Locally

No build step is required — the project is plain HTML and CSS.

```bash
git clone https://github.com/mrkorzun/goit-markup-hw-06.git
cd goit-markup-hw-06
# Open index.html in your browser, or serve with any static server:
npx serve .
```

---

## 🎯 What I Learned

This was the capstone project of the GoIT Markup course. Across the six homework assignments leading up to it, I gradually built up the page — from a basic desktop-only layout in HW-01 to a fully responsive, interactive experience here. Specific takeaways:

- How to structure CSS in a maintainable way for a real production-style page.
- The value of a mobile-first mindset and how it simplifies media queries.
- Practical use of Flexbox vs. Grid depending on the layout problem.
- Accessibility basics: focus management in modals, semantic HTML, label-input associations.
- Optimizing images for performance and high-DPI displays.
- Using Git as a daily workflow tool rather than just a backup.

---

## 📌 Notes for Reviewers

- **No JavaScript frameworks** were used; the modal and mobile menu logic relies on minimal vanilla JS (or pure CSS where possible).
- **No CSS preprocessors** — all styles are written in vanilla CSS to demonstrate fundamentals.
- This was an **educational project**; the design and content belong to the GoIT curriculum.

---

## 👤 Author

**Andrii Korzun**

- GitHub: [@mrkorzun](https://github.com/mrkorzun)
