# blog

Personal blog built with [Jekyll](https://jekyllrb.com/) and the
[Minimal Mistakes](https://github.com/mmistakes/minimal-mistakes) theme,
hosted on GitHub Pages at **https://RitteAnnti818.github.io/blog/**.

Separate from the main homepage repo (`RitteAnnti818.github.io`).

## Add a post

Create `_posts/YYYY-MM-DD-title.md`:

```markdown
---
title: "Your title"
date: 2026-06-29
categories:
  - Research   # or Notes, or a new category name
tags:
  - some-tag
---

Content in Markdown.
```

Commit and push to `main`; GitHub Pages rebuilds automatically. New categories
appear on the `/categories/` page automatically — no config change needed.

## Structure

- `_config.yml` — theme + site settings (skin, author sidebar, archives)
- `_posts/` — blog posts
- `_pages/` — Categories and Tags archive pages
- `_data/navigation.yml` — top nav bar
- `about.md` — About page
