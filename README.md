# JS Asthetic Ways

A single-page streetwear e-commerce landing site for **JS Asthetic Ways**, founded by JimmAT.

This is a **plain static website** — just HTML, CSS, and JavaScript. There is no build step, no framework, and no dependencies to install.

## Project Structure

```
.
├── index.html          # The entire site (markup, styles, and scripts in one file)
└── assets/              # Product photos and logo
    ├── logo.png
    ├── product-1.png
    ├── product-2.png
    ├── ...
    └── product-11.png
```

`index.html` references images using relative paths like `assets/product-1.png`, so the `assets` folder **must stay in the same directory** as `index.html`, with those exact file names.

## Running Locally

No installation needed. Just open `index.html` directly in a browser, or serve it with any static server, e.g.:

```bash
npx serve .
```

## Deploying on Vercel

Since this is a static site (not Next.js, React, etc.), configure the Vercel project like this:

1. **Framework Preset:** `Other`
2. **Root Directory:** leave as `.` (only change this if `index.html` lives in a subfolder)
3. **Build Command:** leave empty
4. **Output Directory:** leave empty

If the Framework Preset is left on something like "Next.js" by default, Vercel will try to run a build that doesn't exist for this project, which results in a blank deployed page.

## Deploying on Netlify (alternative)

Drag and drop this whole folder (including `assets/`) onto [Netlify Drop](https://app.netlify.com/drop) — no configuration required, and you get a live link instantly.

## Features

- Responsive streetwear storefront (hero, featured collection, about section, footer)
- Product grid with Add to Cart / wishlist interactions
- "Collections" modal that opens with an animated product showcase
- Scroll-triggered fade-in animations throughout
