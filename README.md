> Source of truth: this starter is exported from the `contentrain-starters` monorepo.
> Internal starter id: `next-saas-dashboard`.
# Contentrain Next SaaS Dashboard

Product-surface starter for teams that want Contentrain to own dashboard UI copy, settings surfaces, billing plans, and operational messaging instead of scattering strings across components.

## Start

```bash
pnpm install
pnpm dev
```

## Commands

```bash
pnpm check
pnpm build
pnpm start
pnpm deploy:netlify
```

## Demo routes

- `/`
- `/settings`
- `/billing`
- `/operations`
- `/architecture`

## Why this starter exists

- UI strings are managed through a Contentrain dictionary model instead of hardcoded JSX text
- Settings, billing, queue items, notices, and audit rows are typed content models
- The starter demonstrates product-surface governance, not only marketing pages

Official references:

- [SDK](https://ai.contentrain.io/packages/sdk.html)
- [Docs](https://docs.contentrain.io/)
- [Studio](https://studio.contentrain.io/)

## Deploy

- Netlify build command: `pnpm deploy:netlify`
- Netlify publish directory: framework-managed
- Keep the publish directory empty in the Netlify UI and let the Next.js runtime be detected automatically
