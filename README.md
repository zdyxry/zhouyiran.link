# zhouyiran.link

Personal landing page with bento-grid layout. Built with [Astro](https://astro.build) + [Tailwind CSS](https://tailwindcss.com), deployed on [Cloudflare Pages](https://pages.cloudflare.com).

## Development

```bash
npm install
npm run dev      # Start dev server at localhost:4321
npm run build    # Build static site to dist/
npm run preview  # Preview production build
```

## Deploy to Cloudflare Pages

1. Connect this repo in the [Cloudflare Pages dashboard](https://dash.cloudflare.com/?to=/:account/pages)
2. Set build settings:
   - **Build command**: `npm run build`
   - **Build output directory**: `dist`
3. Deploy

## Customization

Edit links in `src/pages/index.astro` — the `links` array at the top of the file.
