# helenamew.github.io

Personal website for Helena Ward, built with [Hugo](https://gohugo.io/) (custom templates, no theme) and hosted on GitHub Pages.

## Adding writing

Each piece is a Markdown file in `content/writing/`; the file name becomes its address (`onion-axiom.md` → `/writing/onion-axiom/`). The Writing page lists them newest first, showing the month and year.

**Linked piece** (most writing; no page on this site, the title and venue link straight to the original):

```markdown
---
title: The Onion Axiom for Artificial Intelligence
date: 2025-06-12
venue: Institute for Ethics in AI
authors: with Imogen Rivers   # optional
original: https://link-to-the-original-post
---
```

Use `pdf: https://link-to-the.pdf` instead of `original:` for a piece published as a PDF (it also gets a PDF tag).

**Paywalled piece** (gets its own page with the author version; the venue still links to the original): same header, plus the text below it:

```markdown
---
title: Accountability Gaps in Generative AI
date: 2024-04-17
venue: The EI Network
original: https://link-to-the-paywalled-post
---

The author version goes here.
```

Push to `main` and the site rebuilds automatically (see `.github/workflows/hugo.yaml`).

## Other things to edit

- Homepage bio: `content/_index.md`
- Research page: `content/research.md`
- Publications and papers under review (cards on the Research page): `data/publications.yaml`
- CV: replace the PDF in `static/` and update the CV button's `url` in `hugo.yaml`
- Page colour (title and line): add `colour: "#e27e35"` to a page's header; posts use their section's colour (set in `content/writing/_index.md`)
- Email address and homepage buttons (labels, links, colours): `hugo.yaml`
- Profile photo: `static/images/helena.jpg` (square)
- Font: Syne, self-hosted in `static/fonts/` and set as `--font` at the top of `static/css/site.css`
- Favicon: `static/favicon.svg` (plus `favicon-32.png` and `apple-touch-icon.png`)
- Design: `layouts/` (page templates) and `static/css/site.css` (styles)

## Local preview

```sh
git clone <repo-url>
hugo server -D   # then open http://localhost:1313
```

CI builds with Hugo v0.124.1 (extended) to match the local version; bump `HUGO_VERSION` in the workflow after testing locally with a newer release.
