# Terramade — Sustainable African Furniture

A modern, premium one-page landing site for a sustainable African furniture brand that transforms discarded tyres, scrap metals, and fabrics into artistic, functional furniture pieces.

## Stack

- Static HTML (single file: `index.html`)
- Tailwind CSS via CDN with a custom design-token config
- Google Fonts (Fraunces display + Inter body)
- Lightweight IntersectionObserver reveal-on-scroll

## Local preview

Just open the file:

```bash
open index.html
```

Or serve it with any static server:

```bash
npx serve .
```

## Deploy to Vercel

This project is a static site — Vercel auto-detects it.

**Option 1 — Vercel dashboard**

1. Go to [vercel.com/new](https://vercel.com/new)
2. Import `drbinna/Degradable_9999`
3. Framework Preset: **Other** (Vercel will use the static `index.html` automatically)
4. Click **Deploy**

**Option 2 — Vercel CLI**

```bash
npm i -g vercel
vercel        # preview
vercel --prod # production
```

## Project structure

```
.
├── index.html      # the entire site
├── vercel.json     # Vercel config (headers, clean URLs)
├── .gitignore
└── README.md
```

## Customizing

- **Brand name** — find & replace `Terramade` in `index.html`
- **Email** — search for `yourbrand@email.com`
- **Product photos** — replace the 5 Unsplash URLs with your own assets
- **Color palette** — tokens defined in the `tailwind.config` block near the top of `index.html`
