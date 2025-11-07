# create-react-app-doc

<div align="center">

<img alt="React" src="https://img.shields.io/badge/React-16.13-61DAFB?style=for-the-badge&logo=react&logoColor=000" />
<img alt="Create React App" src="https://img.shields.io/badge/CRA-3.4.3-09D3AC?style=for-the-badge&logo=create-react-app&logoColor=fff" />
<img alt="JavaScript" src="https://img.shields.io/badge/JavaScript-ES6+-F7DF1E?style=for-the-badge&logo=javascript&logoColor=000" />
<img alt="Node.js" src="https://img.shields.io/badge/Node.js-18.x-339933?style=for-the-badge&logo=node.js&logoColor=fff" />

</div>

## Overview

Single‑page documentation site built with Create React App to explore and demonstrate CRA concepts, patterns, and utilities. It organizes content into chapters with in‑app navigation and theming for quick learning and reference.

## Key Features

- Chapter‑based navigation with client‑side routing and hash links
- Theme switcher with persisted dark mode
- Search component for quick topic lookup

## Tech Stack

React 16, Create React App 3.4, JavaScript (ES6), Emotion (theming), React Router DOM 5

## Architecture

SPA using Create React App with `react-router-dom` and `react-router-hash-link` for section navigation. Styling and theming via Emotion; chapters live under `src/components/chapters`, with shared UI and layouts in `src/UI` and `src/layouts`. Global styles and theme utilities are in `src/utils`.

## Performance & Accessibility

CRA production build optimizations; client‑side routing keeps interactions fast. Uses semantic HTML in components with keyboard‑accessible navigation patterns.

## Quality

- Linting: ESLint (react-app) • Formatting: N/A
- Type safety: N/A (JavaScript)
- Tests: React Testing Library deps present; no test files committed
- CI: None

## Prerequisites

- Node.js: `18.17.0`

## Installation

```bash
git clone https://github.com/maxgalchenko/create-react-app-doc.git
cd create-react-app-doc
npm install
```

## Quick Start

```bash
npm start

# Production build
npm run build

# Tests (watch mode)
npm test
```

Open http://localhost:3000

## Available Scripts

- `npm start` – Start the development server at http://localhost:3000
- `npm run build` – Build the app for production to the `build` folder
- `npm test` – Run tests in interactive watch mode
- `npm run analyze` – Analyze bundle size of production build
- `npm run eject` – Eject CRA configuration (one‑way)

## Screenshots

![Overview](./public/screenshots/getting-started-1.png)
![Chapter view](./public/screenshots/getting-started-2.png)
![Details](./public/screenshots/getting-started-3.png)

---

<div align="center">

Built with ❤️ by [Maksym Galchenko](https://github.com/maxgalchenko)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/galchenko-max/)
[![Portfolio](https://img.shields.io/badge/Portfolio-Visit-green?style=for-the-badge&logo=web)](https://portfolio-green-six-29.vercel.app/)
[![Email](https://img.shields.io/badge/Email-Contact-red?style=for-the-badge&logo=gmail)](mailto:galchenko.maksym@gmail.com)
![License](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)

</div>
