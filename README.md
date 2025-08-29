# Telemed Astro Starter

A tiny Astro starter with tokens for colors/typography, a base layout, and sample pages.

## Quick Start
1) Install Node 18+ from nodejs.org (or use nvm).
2) In a terminal:
```bash
npm install
npm run dev
```
3) Open http://localhost:4321

## Customize
- **Colors & spacing**: edit `src/styles/theme.css` (CSS variables).
- **Fonts**: update `<link>`s in `src/layouts/BaseLayout.astro` (Google Fonts) or drop font files in `public/fonts` and reference in `theme.css`.
- **Logo**: put your SVG/PNG in `public/img/logo.svg` (or .png) and the header will render it automatically.
- **Pages**: edit files in `src/pages/` (index, services, telehealth, contact). Add new pages by creating new `.astro` files.
- **Images**: drop into `public/img/` and reference like `/img/yourfile.jpg`.

## Deploy
- Static output in `dist/` after `npm run build`.
- Works on Cloudflare Pages, Netlify, Vercel, GitHub Pages.
  - Build command: `npm run build`
  - Output dir: `dist`

## Redirects
- Add rules in `public/_redirects` (Netlify/Cloudflare compatible).