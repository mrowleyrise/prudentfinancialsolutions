# Prudent Financial Solutions

Single-page static site for prudentfinancialsolutions.com, hosted on Cloudflare Workers (static assets).

- `public/index.html`: the page
- `public/styles.css`: styles
- `public/img/`: logo, icons, hero image
- `wrangler.jsonc`: Cloudflare config

## Adding the form

Paste the form's embed code inside `<div class="form-embed">` in `public/index.html` (look for `FORM EMBED`).

## Local preview

```bash
npx wrangler dev
```

## Deploy

```bash
npx wrangler deploy
```

Or connect this repo in the Cloudflare dashboard (Workers & Pages → Create → Import a repository) so every push to `main` deploys automatically.
