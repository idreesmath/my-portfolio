### Name: Muhammad Idrees
### Panaversity ID: @idrees448-77qh
#### Task: 03 (My Portfolio) Course: AI101 - P011

# My Portfolio 🌐

A clean, mobile-friendly, one-page portfolio website built with plain **HTML & CSS** — no frameworks, no build step, no dependencies.

**🔗 Live site:** [idrees.pk](https://idrees.pk/)  

**🔗 Live site on Vercel:** [my-portfolio-idrees.vercel.app](https://my-portfolio-idrees.vercel.app/)

## About

Personal portfolio of **Muhammad Idrees** — Lecturer of Mathematics at Government Boys Postgraduate College Quetta, and software developer. The site showcases my skills, projects, and contact information in a single responsive page.

## Features

- 📱 **Fully responsive** — adapts cleanly from phones to desktops using CSS grid, flexbox, and fluid typography
- 🎨 **Professional dark theme** — navy background with sky-blue accents, defined via CSS custom properties for easy re-theming
- ⚡ **Zero dependencies** — everything (markup + styles) lives in one `index.html` file; works offline and loads instantly
- 🧭 **Smooth navigation** — sticky header with smooth-scroll links to each section
- ✉️ **Actionable contact cards** — clickable `mailto:` link

## Sections

1. **Hero** — name, tagline, and call-to-action buttons
2. **About Me** — background in teaching, mathematics, and software development
3. **Skills** — HTML, CSS, JavaScript, TypeScript, Python, React, Next.js, Tailwind CSS, Node.js, Git & GitHub, REST APIs, LaTeX, Agentic AI
4. **Projects** — Snake Game, Expense Tracker Pro, Weather Dashboard, Markdown Notes App, AI Chatbot Assistant, Recipe Finder
5. **Contact** — email and location

## Project Structure

```
my-portfolio/
├── index.html       # The entire website (markup + styles)
├── requirement.md   # Content requirements the site was built from
└── README.md        # This file
```

## Running Locally

No build step needed — just open the file in a browser:

```bash
# Option 1: open directly
open index.html        # macOS
xdg-open index.html    # Linux
start index.html       # Windows

# Option 2: serve locally
npx serve .
```

## Deployment

The site is deployed to [Vercel](https://vercel.com) as a static site:

```bash
npx vercel --prod
```

## Customizing

- **Colors** — edit the CSS custom properties in the `:root` block at the top of `index.html` (`--bg`, `--accent`, etc.)
- **Content** — all text lives directly in the HTML sections; update and redeploy
- **Projects** — swap a card's "Coming soon" label for a live link as projects ship

## Contact

- 📧 [idrees@idrees.pk](mailto:idrees@idrees.pk)
- 📍 Pakistan

---

© 2026 Muhammad Idrees
