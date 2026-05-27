# My First Website

This is a static website built with `index.html` and styled for a colorful landing page.

## Local development

```bash
npm install
npm run dev
```

Then open `http://127.0.0.1:5500` to view it locally.

## Deploy to Vercel

1. Connect this GitHub repo to Vercel.
2. Vercel will detect `vercel.json` and deploy the static site.

## Deploy to Render

1. Connect this GitHub repo to Render.
2. Use the `render.yaml` manifest or create a new Node web service.
3. Set branch to `main`.

## GitHub Packages

This repository is configured to publish an npm package to GitHub Packages using `@maomaower/my-first-website`.

- Package name: `@maomaower/my-first-website`
- Registry: `https://npm.pkg.github.com/`

Publish happens automatically on every push to `main` via GitHub Actions.
