# Mohammed Addi — Portfolio

Personal portfolio website showcasing my projects, skills, and background as an AI/Computer Science student.

**Live site:** [mohammed-addi.netlify.app](https://mohammed-addi.netlify.app/)

## Tech Stack

- React (Vite)
- Tailwind CSS
- Framer Motion
- Material UI
- AOS (scroll animations)
- Lucide Icons
- SweetAlert2

## Features

- Home, About, Portfolio, and Contact sections in a single-page layout
- Project showcase with live demo links, GitHub links, and detail pages
- Certificates & awards gallery
- Responsive design, dark theme with a blue accent palette
- Contact form powered by SweetAlert2 notifications

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (LTS recommended)

### Installation

```bash
git clone https://github.com/ai-mohammed/my-portfolio.git
cd my-portfolio
npm install
```

### Development

```bash
npm run dev
```

Open the URL printed in your terminal (typically `http://localhost:5173`).

### Production Build

```bash
npm run build
```

The optimized output is generated in the `dist` folder, which is what gets deployed.

### Preview a Build Locally

```bash
npm run preview
```

## Deployment

The site is deployed on [Netlify](https://www.netlify.com/), which serves the contents of the `dist` folder committed to the `main` branch. To ship a new version:

```bash
npm run build
git add dist
git commit -m "build: update production bundle"
git push
```

## Project Structure

```
src/
├── Pages/          # Home, About, Portofolio, Contact, etc.
├── components/      # Reusable UI components (Navbar, CardProject, ...)
└── assets/          # Static assets
public/              # Static files copied as-is (images, resume, icons)
dist/                # Production build (served by Netlify)
```

## Contact

- LinkedIn / GitHub / Instagram links are available directly on the site's Contact page.

---

© 2026 Mohammed Addi. All rights reserved.
