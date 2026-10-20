---
title: "{{ replace .File.ContentBaseName "-" " " | title }}"
date: {{ .Date }}
venue: # where it was published, e.g. Institute for Ethics in AI
authors: # optional co-authors, e.g. with Jen Semler
original: # link to where it was published
pdf: # or: link to a PDF
# Leave the body empty to link straight to `original`/`pdf` (no page on this site).
# Add the text below only for paywalled pieces, which then get their own page.
draft: true
---
