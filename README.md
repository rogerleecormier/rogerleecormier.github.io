# From Docs to Delivery

A developer‑native, Markdown‑first portfolio site built with [MkDocs](https://www.mkdocs.org/) and the [Material for MkDocs](https://squidfunk.github.io/mkdocs-material/) theme, deployed via GitHub Actions to GitHub Pages.

---

## 🚀 Overview

This repository contains the source for my portfolio site, showcasing cloud automation, DevOps projects, and custom tooling utilities. Instead of a traditional CMS or hand‑coded HTML, the site leverages:

- **Markdown** for all content  
- **Git** for versioning, review, and collaboration  
- **CI/CD** for zero‑touch builds & deploys  

---

## 🔧 Tech Stack

- **Site generator:** MkDocs 1.6.1  
- **Theme:** Material for MkDocs 9.x  
- **Authoring:** VS Code + GitHub Copilot, ChatGPT for content drafting & polishing  
- **CI/CD:** GitHub Actions (`mkdocs build` → `gh-pages` publish)  
- **Hosting:** GitHub Pages (custom domain via Porkbun)  

---

## 🔌 Plugins & Extensions

**Core MkDocs Plugins**  
- `search` – full‑text site search with custom tokenization  
- `mkdocs-awesome-nav` – YAML‑driven sidebar navigation via `nav.yml`  
- `mkdocs-get-deps` – dynamically include external Markdown snippets  
- `git-revision-date-localized` – shows “Last updated” dates using Git  
- `optimize` – minifies HTML/CSS/JS for faster page loads  
- `social` – auto‑generates Open Graph/social preview cards

**Markdown Extensions**  
- `admonition` & `pymdown-extensions` – callouts, tabs, syntax highlights, emojis  
- `codehilite` – enhanced code block highlighting  
- `mdx_math` – LaTeX/KaTeX math support  
- `toc` – automatic table‑of‑contents with permalinks  

---

## 🌈 Material Theme Features

Material for MkDocs enables a rich, enterprise‑grade UI without custom code:

- **Built‑in search** with highlighted results  
- **Light/dark mode toggle**  
- **Tabbed content** & **navigation tabs**  
- **Copy‑to‑clipboard** buttons on code blocks  
- **Inline code annotations**  
- **Instant loading** & **prefetching**  
- **Sticky sidebar** with section dividers  
- **“Back to top”** button and scroll‑spy  
- **Dismissible announcement bar**  

These features ensure fast, accessible, and intuitive navigation across the site.

---

## 📥 Getting Started

1. **Clone**  
   ```bash
   git clone https://github.com/rogerleecormier/portfolio-site.git
   cd portfolio-site
