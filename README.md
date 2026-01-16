# My Blog

This repository contains the static build of my blog.

**Auto-deployed from [blogs](https://github.com/Anudorannador/blogs) repository.**

## Setup

This site is automatically built and deployed via GitHub Actions whenever changes are pushed to the `blogs` repository.

### How it works

1. The source code lives in the private `blogs` repository
2. On push to `main`, GitHub Actions builds the site with `VITE_PRIVATE_MODE=false`
3. The built static files are pushed to this repository
4. GitHub Pages serves the content

## Local Preview

To preview locally, simply serve the files with any static server:

```bash
npx serve .
```

---

*This is an auto-generated deployment. Do not edit files directly.*
