# Instructions

All pages are stored in [src/pages](src/pages) as Markdown pages. You should be able to edit this in any text editor.

## Making and Editing New Pages

If you want to add more pages, make a new markdown file with this template:

```
---
title:
description:
layout: /src/components/main.astro
order: 0 #set to 0 to hide
---

Lorem ipsum...
```

The `title` of the page is what appears in the navigation bar. The `description` is the SEO description (this is important to set!).

Don't change `layout` (this is what gives the page it's style).

If you want to hide a page without deleting it, add an underscore before the filename, so `about.md` would go to `_about.md` to be hidden from the site.

### Home Page

The home page is [src/pages/index.md](src/pages/index.md). It's the same basic format as the other pages.

## Changing the Style

The basic layout is defined by [src/components/main.astro](src/components/main.astro). Astro is a file format that is mostly HTML. The CSS style is in this file: [src/styles.css](src/styles.css).


## Development Commands

All commands are run from the root of the project, from a terminal:

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Installs dependencies                            |
| `npm run dev`             | Starts local dev server at `localhost:4321`      |
| `npm run build`           | Build your production site to `./dist/`          |
| `npm run preview`         | Preview your build locally, before deploying     |
| `npm run astro ...`       | Run CLI commands like `astro add`, `astro check` |
| `npm run astro -- --help` | Get help using the Astro CLI                     |
