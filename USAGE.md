# Contentrain Next SaaS Dashboard on Netlify

[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https%3A%2F%2Fgithub.com%2FContentrain%2Fcontentrain-starter-next-saas-dashboard)

## Quick start

```bash
pnpm install
pnpm build
```

## Deploy with Netlify CLI

From the repository root:

```bash
pnpm dlx netlify-cli init
```

If the repository is already connected to a Netlify project:

```bash
pnpm dlx netlify-cli link
```

## Build contract

- Build command: `pnpm deploy:netlify`
- Publish directory: `framework-managed`
- Node version: `22`

## Demo routes

- `/`
- `/settings`
- `/billing`
- `/operations`
- `/architecture`

## Contentrain references

- Docs, CLI and SDK: https://ai.contentrain.io
- Next.js guide: https://ai.contentrain.io/guides/frameworks#next-js-app-router
- Studio: https://contentrain.io/studio
