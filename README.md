# ExaCap Website

Portfolio website for [ExaCap Limited](https://exacapltd.github.io), the investment arm of [ExaDev](https://exadev.io).

Built with [Astro](https://astro.build) and [Tailwind CSS v4](https://tailwindcss.com). Deployed to GitHub Pages.

## Development

```sh
npm install
npm run dev
```

Requires Node.js >= 22.12.0.

## Build

```sh
npm run build
npm run preview
```

## Adding News Posts

Create a markdown file in `src/content/news/` with frontmatter:

```md
---
title: "Post Title"
date: 2025-01-01
author: "ExaCap"
summary: "Short summary for the listing page."
---

Post content here.
```

## Structure

- `src/components/` - Astro components (Hero, Portfolio, Thesis, etc.)
- `src/pages/` - Routes (index, team, news, portfolio detail pages)
- `src/content/news/` - Markdown news posts
- `src/layouts/` - Page layout
- `public/` - Static assets (logos, team photos)
