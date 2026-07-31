# Abdias Peguero — Data Engineering Portfolio

A lightweight, modern Data Engineering portfolio built with plain HTML, CSS and JavaScript.

## Why this setup?

- Completely free and open-source
- No framework or package installation required
- Fast static site
- Easy for Codex to understand and edit
- Deployable free on GitHub Pages, Cloudflare Pages, Netlify or Vercel

## Local preview

### Option 1: Open directly

Double-click `index.html`.

### Option 2: Run a local server

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000`.

## Customize before publishing

In `index.html`, replace:

- `your-email@example.com`
- The LinkedIn placeholder URL
- The GitHub placeholder URL
- Any project claims or metrics you do not want public
- Add a résumé PDF to `assets/` and create a link to it

## Deploy free with GitHub Pages

1. Create a new public GitHub repository.
2. Upload all files from this project.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, select **GitHub Actions**.
5. The included workflow will publish the site automatically.
6. Your website will be available at:
   `https://YOUR-USERNAME.github.io/YOUR-REPOSITORY/`

## Deploy free with Cloudflare Pages

1. Push this project to GitHub.
2. In Cloudflare Pages, select **Create a project → Connect to Git**.
3. Choose the repository.
4. Framework preset: **None**.
5. Build command: leave empty.
6. Output directory: `/`.
7. Deploy.

## Codex workflow

This repository includes `AGENTS.md`, which gives Codex project-specific guidance.

Suggested first Codex prompt:

> Review this portfolio for accessibility, responsive design, performance and professional positioning. Make improvements without adding paid services or unnecessary dependencies.

## Structure

```text
.
├── .github/workflows/deploy-pages.yml
├── assets/
│   ├── script.js
│   └── styles.css
├── AGENTS.md
├── index.html
├── LICENSE
└── README.md
```
