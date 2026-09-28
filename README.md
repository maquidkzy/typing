# type.

> A minimal, distraction-free typing canvas. Just you and text.

Live at **[type.honinbo.de](https://type.honinbo.de)**

## Features

- **3 themes × light/dark** — Ink, Sepia, Navy
- **Auto-save** — text persists in `localStorage` across sessions
- **Adjustable font size** — `Ctrl +` / `Ctrl −` or `Ctrl + scroll`
- **Copy all** — one-click clipboard copy
- **Fullscreen** — distraction-free mode
- **Auto-hiding toolbar** — hover the bottom edge to reveal options

## Deploy (Cloudflare Pages)

1. Push this repo to GitHub
2. Cloudflare Dashboard → **Workers & Pages** → **Create** → **Pages** → **Connect to Git**
3. Select repo — no build command needed, output directory = `/`
4. **Custom Domains** → add `type.honinbo.de` (auto-creates CNAME since domain is already on Cloudflare)

## Files

```
index.html   ← entire app (HTML + CSS + JS, zero dependencies)
_headers     ← Cloudflare Pages security headers
README.md
```
