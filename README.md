# helenamew.github.io

Personal website for Helena Ward, built with [Hugo](https://gohugo.io/) (custom templates, no theme) and hosted on GitHub Pages.

## Adding a post

Create a Markdown file in `content/writing/` with a header like this:

```markdown
---
title: My post title
date: 2026-09-28
tags: [privacy, ethics]
draft: false
---

Post text goes here.
```

Push to `main` and the site rebuilds automatically (see `.github/workflows/hugo.yaml`).

## Other things to edit

- Homepage bio: `content/_index.md`
- Research / CV pages: `content/research.md`, `content/cv.md`
- Page colour (title and line): add `colour: "#e27e35"` to a page's header; posts use their section's colour (set in `content/writing/_index.md`)
- Email address and homepage buttons (labels, links, colours): `hugo.yaml`
- Profile photo: `static/images/helena.jpg` (square)
- Fonts and the font picker: `fonts` and `fontSwitcher` in `hugo.yaml`
- Favicon: `static/favicon.svg` (plus `favicon-32.png` and `apple-touch-icon.png`)
- Design: `layouts/` (page templates) and `static/css/site.css` (styles)

## Local preview

```sh
git clone <repo-url>
hugo server -D   # then open http://localhost:1313
```

CI builds with Hugo v0.124.1 (extended) to match the local version; bump `HUGO_VERSION` in the workflow after testing locally with a newer release.
