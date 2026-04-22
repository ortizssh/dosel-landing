# Dosel — Landing

Coming-soon landing page for **Dosel Audio** — HiFi speakers designed and assembled in Chile.

## Stack

- Static HTML · no framework
- Google Fonts: Space Grotesk + Inter
- Vector logo (SVG) from the official brand system
- Ready to deploy on Vercel

## Local preview

```sh
open index.html
```

Or run any static server pointing to this directory.

## Deploy

```sh
vercel --prod
```

`vercel.json` is already configured with long-cache headers for SVG assets.

## Structure

```
index.html       — the page
isotype.svg      — Dosel isotype (white, for favicon + top bar)
logo.svg         — Dosel full lockup (white)
vercel.json      — deploy config
```

## Email capture

The signup form currently stores emails in `localStorage` for demo purposes.
Wire `form#signup-form` to a real endpoint (Formspree, Mailchimp, Shopify
Customer API, or a simple Vercel serverless function) before launch.

## Brand

See the full brand system in `/Documents/Dosel/BrandGuide/`.
