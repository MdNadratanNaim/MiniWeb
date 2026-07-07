# mini-web

A collection of small, useful web-based tools. This project serves as a central hub for various single-purpose utilities built as standalone webpages.

## 📌 Table of Contents
- [Tools](#-tools)
  - [Markdown Reader](#markdown-reader)
- [How to Use](#-how-to-use)

## 🚀 Tools

### Markdown Reader
[**Launch Tool**](./mdreader/)

A client-side Markdown viewer with advanced features:
- **Local & Remote Loading**: Upload `.md` files directly or load them via GitHub/URL.
- **Custom Parser**: Hand-written Markdown parser with support for tables, blockquotes, and more.
- **LaTeX Support**: Render mathematical formulas using KaTeX.
- **Smart Resolution**: Automatically resolves relative image and link paths for remote files.
- **Deep Linking**: Share specific documents using the `?view=` query parameter.

**Tech Stack:**
- HTML, CSS, JavaScript (Vanilla)
- KaTeX (via CDN) for LaTeX rendering

## 📖 How to Use

Since this is a static site, you can run it in several ways:

1. **Local File**: Simply open `index.html` in your preferred web browser.
2. **Local Server**: Use any static file server (e.g., `npx serve .` or Python's `http.server`).
3. **Hosting**: Can be easily deployed to GitHub Pages, Vercel, or Netlify.
