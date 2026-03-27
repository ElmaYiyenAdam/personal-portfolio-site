# Personal Portfolio Website

Minimal, static personal site with two pages: Home and Academic.

## Local Development

```bash
npm install
npm run dev
```

Build and preview:

```bash
npm run build
npm run preview
```

## Cloudflare Pages Deployment

1) Push this repository to GitHub.
2) In Cloudflare Pages, click **Create a project** → **Connect to Git**.
3) Select the repo and set build settings:
   - Build command: `npm run build`
   - Output directory: `dist`
4) Deploy. Cloudflare Pages will build on every push to the default branch.
