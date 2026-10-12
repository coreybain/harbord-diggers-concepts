# Harbord Diggers — homepage and Christmas concepts

Ten static design concepts (plain HTML, CSS and JS, no build step).

- `site/index.html` — index of all concepts
- `site/v1`–`v3` — Harbord Diggers homepage variants
- `site/v4`–`v6` — variants based on mounties.com.au
- `site/v7`–`v10` — Christmas advent calendar page (v9 and v10 follow the Mounties Group brand style guide)

Event details on the Christmas pages are placeholders. Photos and logos belong to Mounties Group / Harbord Diggers and are used here for concept purposes only.

## Run locally

```sh
python3 -m http.server 8765 --directory site
```

## Deploy to Cloudflare

```sh
npx wrangler deploy
```
