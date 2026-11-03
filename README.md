# Rafael Morales · Product Design

Personal portfolio site. A single static page: `public/index.html` plus images in `public/img/`.

`public/case-studies/` is the private Aplazo + Clara case-study deck, exported to static HTML from the Slides deck. It is unlisted: nothing on the landing links to it, and it is kept out of search engines with a `noindex` meta tag plus an `X-Robots-Tag` header (`public/_headers`). Anyone with the URL can open it. Press **Present** (then the arrow keys) to show one slide at a time.

No build step. Deployed to Cloudflare as a static-assets Worker (see `wrangler.jsonc`):

- Build command: none
- Deploy command: `npx wrangler deploy`
- Preview (non-production branch) command: `npx wrangler versions upload`
