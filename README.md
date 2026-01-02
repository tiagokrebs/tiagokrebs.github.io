# tiagokrebs.com

Personal website built with [Hugo](https://gohugo.io) and deployed to [GitHub Pages](https://pages.github.com).

## Setup

## Development

Add new post:
```bash
hugo new content/posts/newpost.md
```

Run local dev server:
```bash
hugo serve -D
```

Build locally:
```bash
hugo --gc --minify
```

## Deployment

Site deploys automatically via GitHub Actions when push to `main`.
