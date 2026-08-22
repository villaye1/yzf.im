# yzf.im

Personal blog hosted at [yzf.im](https://yzf.im).

## Setup

1. Enable GitHub Pages in repository Settings → Pages.
2. Source: Deploy from a branch → `main` / root (or `/docs`).
3. Add custom domain `yzf.im` and enable "Enforce HTTPS".
4. Configure DNS at your domain registrar:

**For apex domain (yzf.im):**

| Type | Host | Value |
|------|------|-------|
| A | @ | 185.199.108.153 |
| A | @ | 185.199.109.153 |
| A | @ | 185.199.110.153 |
| A | @ | 185.199.111.153 |
| CNAME | www | villaye1.github.io |

After DNS propagates, the site will be available at https://yzf.im.

## Development

This is currently a static HTML starter. You can replace it with Jekyll, Hugo, Hexo, Astro, or any static site generator that outputs to the root or `docs` folder.
