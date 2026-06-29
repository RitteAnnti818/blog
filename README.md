# blog

Personal blog built with [Jekyll](https://jekyllrb.com/) (minima theme),
hosted on GitHub Pages at **https://RitteAnnti818.github.io/blog/**.

This repo is separate from the main homepage repo
(`RitteAnnti818.github.io`) so the two never interfere.

## Add a post

Posts are organized into sidebar categories by folder:

- `_research/` → **Research** section
- `_notes/` → **Notes** section

Create `_research/YYYY-MM-DD-title.md` (or `_notes/...`):

```markdown
---
title: "Your title"
date: 2026-06-29
category: Research
---

Content in Markdown.
```

Commit and push to `main`; GitHub Pages rebuilds automatically.

To add a new category: create a `_name/` folder, then register it under
`collections:` and `ordered_collections:` in `_config.yml`.
