# 🎓 Web Development Coursework & Portfolio

**Student Name:** Satvik  
**Institution:** Scaler School of Technology (2026–2030)  
**Degree:** B.Sc. (Hons) Computer Science & Artificial Intelligence, BITS Pilani (2026–2030)  
**Course:** Web Development — Builders Day & Lab Series  

---

## 📌 Evaluator Quick-Start

| # | Deliverable | Open This File | What You Will See |
|:-:|:---|:---|:---|
| **01** | **Portfolio** (Main Project) | [`index.html`](index.html) | Personal portfolio — CSS Grid, kinetic marquee, editorial theme |
| **02** | **Assignment 01** — Student Portal | [`assignment_01/index.html`](assignment_01/index.html) | Academic portal — pure HTML5 + basic CSS, no Flex/Grid |
| **03** | **Assignment 02** — Flexbox Quest | [`assignment_02/index.html`](assignment_02/index.html) | Mini game UI — CSS Flexbox only, responsive |

All three pages are linked to each other via navigation banners at the top — you can jump between them with one click.

---

## 📂 Repository Structure

```
project/
│
├── index.html              ← 🌟 Portfolio home (main entry point)
├── style.css               ← 🎨 Portfolio stylesheet (CSS Grid, marquee animations)
├── README.md               ← 📖 This guide
├── project.md              ← 📄 Course specification document
│
├── assignment_01/          ← 📁 Assignment 01: Student Portal
│   ├── index.html          ←    Main file (open this to view)
│   ├── style.css           ←    Stylesheet (introductory CSS, no Flex/Grid)
│   └── README.md           ←    Assignment notes & rubric checklist
│
└── assignment_02/          ← 📁 Assignment 02: Flexbox Quest
    ├── index.html          ←    Main file (open this to view)
    ├── style.css           ←    Stylesheet (CSS Flexbox only + media query)
    └── README.md           ←    Assignment notes & rubric checklist
```

---

## 🔗 How the Pages Link Together

```
Portfolio (index.html)
    ├──→ Assignment 01 (assignment_01/index.html)
    └──→ Assignment 02 (assignment_02/index.html)

Assignment 01 ←──→ Assignment 02  (bidirectional nav banner)
```

All links use **relative anchor tags** (`<a href="...">`), so they work both:
- **Locally** — double-click `index.html` in any browser
- **Online** — on GitHub Pages with zero extra configuration

---

## 🛠️ Deliverable Details

### 1. Portfolio — Builders Day Project (`index.html`)
- High-contrast editorial / avant-garde design
- CSS Grid (bento layout), CSS Flexbox (nav, footer), `@keyframes` animations
- Animated marquee: `▪▪ SCALER SCHOOL OF TECHNOLOGY ▪▪ BITS PILANI ▪▪`
- Sticky navigation with smooth scroll to `#about`, `#work`, `#education`, `#contact`

### 2. Assignment 01 — Student Portal (`assignment_01/`)
**Rules strictly followed:** Pure HTML5 + introductory CSS. **No Flexbox, No Grid, No JavaScript.**
- Semantic structure: `<header>`, `<nav>`, `<main>`, `<section>`, `<table>`, `<form>`, `<footer>`
- Student profile table with `<th>` headings
- CSS selectors: element (`body`, `h1`), class (`.highlight`, `.badge`), ID (`#student-name`)
- Course registration form: text, email, dropdown, radio, checkbox, submit & reset

### 3. Assignment 02 — Flexbox Quest (`assignment_02/`)
**Rules strictly followed:** Layout built **exclusively with CSS Flexbox**. **No Grid, No absolute/fixed positioning, No JavaScript.**
- Game header: `justify-content: space-between` with lives, coins, level
- 3-panel row: D-pad controls, flex-wrap inventory, quest tracker — each `flex: 1`
- `display: flex/block/inline/inline-block` educational showcase
- Responsive: `@media (max-width: 768px)` collapses panels to single column

---

## 🖥️ How to Run Locally

1. Download / clone this repository
2. Double-click **`index.html`** — it opens in your default browser
3. Use the navigation banners to visit each assignment

## 🌐 GitHub Pages Deployment

1. Go to **Settings → Pages** in the repository
2. Source: **Branch: `main`**, Folder: **`/ (root)`**
3. Click **Save** — your pages will be live at:
   - Portfolio: `https://<username>.github.io/<repo>/`
   - Assignment 01: `https://<username>.github.io/<repo>/assignment_01/`
   - Assignment 02: `https://<username>.github.io/<repo>/assignment_02/`

---

*Built with ❤️ by Satvik — Scaler School of Technology & BITS Pilani (2026–2030)*
