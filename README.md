# Intuitive Heart — Astro site

This project is an Astro website built from the original HTML landing page.
It includes:

- A homepage with sessions, events, corporate wellness, NLP, pricing, shop, testimonials, and contact sections.
- A blog collection powered by Markdown files in `src/content/blog/`.
- A responsive mobile menu, smooth page transitions, and WhatsApp contact flow.

## Run locally

1. Install dependencies:
   ```bash
   npm install
   ```
2. Start the dev server:
   ```bash
   npm run dev
   ```
3. Open the local URL shown in the terminal.

## Add a new blog post

Create a new Markdown file in `src/content/blog/`.
Use the filename as the URL slug, for example `inner-work-notes.md`.

Example frontmatter:

```markdown
---
title: "A gentle guide to intuitive inner work"
pubDate: "2026-05-09"
description: "Small practices for staying grounded, curious, and clear."
category: "Tarot"
heroEmoji: "✦"
---

Your post content goes here.
```

Then visit `/blog` to see the new post.

## Non-technical blog updates

If you want, I can also help add a simple CMS integration later so your friend can post without editing files directly.
