# jessie-portfolio

A terminal-style personal website for Jessie Zhou.

## Features
- Linux terminal aesthetic with typewriter intro animation
- Interactive commands: `cd about`, `cd experience`, `cd projects`, `cd contact`
- Command history (↑ / ↓ arrow keys)
- Tab autocomplete for `cd` commands
- Zero dependencies — pure HTML, CSS, and vanilla JS

## Local Development

Just open `index.html` in your browser — no build step needed.

```bash
open index.html
```

## Deploy to Vercel

### Option 1 — Vercel CLI
```bash
npm i -g vercel
vercel
```

### Option 2 — Vercel Dashboard (recommended)
1. Push this repo to GitHub
2. Go to [vercel.com](https://vercel.com) → **Add New Project**
3. Import your GitHub repo
4. Framework Preset: **Other**
5. Click **Deploy** — that's it!

Vercel will auto-deploy on every push to `main`.

## Customising Content

All content lives in the `SECTIONS` object inside `index.html`.  
Update the text under `about`, `experience`, `projects`, and `contact` to make it yours.
