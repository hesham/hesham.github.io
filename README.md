# hesham.github.io

Personal site for Hesham El-Nahhas, served via GitHub Pages at [hesham.ca](https://hesham.ca). Built with Jekyll, which GitHub Pages builds and deploys automatically on push — no CI workflow needed.

## Local development

```
bundle install
bundle exec jekyll serve
```

Then open http://localhost:4000.

## Writing a blog post

Add a new file to `_posts/` named `YYYY-MM-DD-title.md`:

```
---
layout: post
title: "Your Title"
---

Post content in Markdown.
```