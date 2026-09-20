# Funnel Anatomy Guide

A single-page, editorial-style breakdown of the classic **webinar-registration funnel** pattern — the six recurring stages, what job each one does, and why the order matters. Built as a reference hub, not a template to relaunch as-is.

**Live structure:** one scrollable page (`index.html`), no build step, no dependencies.

## What's inside

- `index.html` — the site's HTML, CSS, and JS in one file
- `images/` — the six stage photos referenced by `index.html`
- Standing features on every load: a light/dark theme toggle (defaults to light) and a font-size selector, both remembered via `localStorage`
- Fully responsive from 320px phones up through large desktop, full-bleed sections with a readable text column
- No external JS libraries; only Google Fonts (Fraunces + Public Sans) are loaded remotely

## Run it locally

No build tools needed — just open the file:

```bash
open index.html        # macOS
# or
python3 -m http.server # then visit http://localhost:8000
```

## Deploy

### GitHub

```bash
git init
git add .
git commit -m "Initial commit: funnel anatomy guide"
git branch -M main
git remote add origin https://github.com/<your-username>/<repo-name>.git
git push -u origin main
```

### Vercel

1. Go to [vercel.com/new](https://vercel.com/new) and import the GitHub repo you just pushed.
2. Framework preset: **Other** (this is a static site — no build command, no output directory needed).
3. Click **Deploy**. Vercel will serve `index.html` as-is.

Alternatively, from the CLI:

```bash
npm i -g vercel
vercel        # first deploy, follow the prompts
vercel --prod # promote to production
```

## Using this as a starting point

This hub is intentionally generic — it teaches the *pattern*, not any single company's copy, imagery, or brand. If you want your own version of a page like this built out for your business (your offer, your copy, your brand), reach out:

- Email: [ai.agent.lamar@gmail.com](mailto:ai.agent.lamar@gmail.com)
- LinkedIn: [lamar-myers-ai](https://linkedin.com/in/lamar-myers-ai)
- X: [@myers_lama86860](https://x.com/myers_lama86860)
- Instagram: [@aiagentlamar](https://instagram.com/aiagentlamar)

## License

Content and code © Lamar Myers. The funnel pattern described is a general industry structure, not proprietary to any one company — free to learn from; please don't redistribute this specific write-up/design as your own without permission.
