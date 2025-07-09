# From Docs to Delivery

A developer‑native, Markdown‑first portfolio site built with [MkDocs](https://www.mkdocs.org/) and the [Material for MkDocs](https://squidfunk.github.io/mkdocs-material/) theme, deployed via GitHub Actions to GitHub Pages.

---

## 🚀 Overview

This repository contains the source for my personal portfolio site, showcasing cloud automation, DevOps projects, SaaS integrations, and custom tooling utilities. Instead of a traditional CMS or static HTML, this site is built on:

- **Markdown** for all content  
- **Git** for version control, review, and rollbacks  
- **CI/CD** via GitHub Actions for zero-touch builds and deploys  
- **Static-site architecture** for speed, security, and scalability

---

## 🔧 Tech Stack

- **Site generator:** MkDocs 1.6.1  
- **Theme:** Material for MkDocs 9.x  
- **Authoring:** VS Code + GitHub Copilot + ChatGPT  
- **CI/CD:** GitHub Actions (`mkdocs build` → `gh-pages` publish)  
- **Hosting:** GitHub Pages (custom domain via Porkbun)

---

## 🔌 Plugins & Extensions

**MkDocs Plugins**  
- `search` – full-text content search with custom tokenization  
- `mkdocs-awesome-nav` – simplified YAML-based sidebar navigation  
- `social` – automatic Open Graph card previews for social media  
- `minify` – compresses HTML/CSS/JS for faster delivery  
- `git-revision-date-localized` – displays last Git-modified timestamps  
- `redirects` – supports clean URL redirects for renamed/moved pages  

**Markdown Extensions**  
- `admonition` – formatted callout blocks  
- `pymdown-extensions` – tabs, tooltips, emojis, improved syntax highlighting  
- `codehilite` – advanced code block rendering  
- `mdx_math` – LaTeX and KaTeX math support  
- `toc` – automatic table of contents with anchor links  
- `footnotes` – inline and grouped references

---

## 🌈 Material Theme Features

Material for MkDocs offers a refined, responsive UI out of the box:

- 🔍 **Search** with intelligent highlighting  
- 🌗 **Light/dark mode** toggle  
- 📑 **Tabs** for code/content organization  
- 📋 **Copy-to-clipboard** on code blocks  
- 📌 **Sticky navigation** with active section tracking  
- ⬆️ **Back-to-top** buttons  
- 📣 **Announcement bar** for user alerts  
- ⚡ **Instant loading** and link prefetching  

All features are configured via `mkdocs.yml` and extensible with Markdown and CSS overrides.

---

## 📥 Getting Started

1. **Clone this repo**  
   ```bash
   git clone https://github.com/rogerleecormier/portfolio-site.git
   cd portfolio-site
