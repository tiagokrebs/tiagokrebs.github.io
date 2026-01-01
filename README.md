# tiagokrebs.com

Personal website built with [Hugo](https://gohugo.io) and deployed to [GitHub Pages](https://pages.github.com).

## Setup

Clone with submodules (themes):
```bash
git clone --recurse-submodules https://github.com/tiagokrebs/tiagokrebs.com.git
```

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

Site deploys automatically via GitHub Actions when you push to `main` branch.

### Initial Setup (one-time)

1. Rename repository to `tiagokrebs.github.io`
2. Go to repository Settings → Pages
3. Under "Build and deployment", set Source to "GitHub Actions"
4. Push to `main` branch to trigger deployment

Site will be available at `https://tiagokrebs.github.io`

