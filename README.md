# Rafael Morales · Product Design

Personal portfolio site. A single static page: `public/index.html` plus images in `public/img/`.

No build step. Deployed to Cloudflare as a static-assets Worker (see `wrangler.jsonc`):

- Build command: none
- Deploy command: `npx wrangler deploy`
- Preview (non-production branch) command: `npx wrangler versions upload`
