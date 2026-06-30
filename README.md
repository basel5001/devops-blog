# XOps Blog

DevOps, Cloud, and Platform Engineering blog built with MkDocs Material and auto-deployed to GitHub Pages.

## Live Site

https://basel5001.github.io/devops-blog

## Local Preview

```bash
# Install dependencies
pip install -r requirements.txt

# Serve locally
mkdocs serve

# Open http://localhost:8000
```

## Adding a Post

1. Create a new `.md` file in `docs/posts/`
2. Add front matter:

```yaml
---
date: 2026-07-01
categories:
  - DevOps
tags:
  - relevant-tag
---
```

3. Write your article in Markdown
4. Push to `main` -- the blog deploys automatically

## Tech Stack

- [MkDocs Material](https://squidfunk.github.io/mkdocs-material/)
- GitHub Actions for deployment
- GitHub Pages for hosting

## License

MIT
