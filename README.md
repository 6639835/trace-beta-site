# Trace beta site

Four static pages built with HTML and Simple.css.

Live site: https://trace-beta-site.6639835.workers.dev

- `public/index.html`: Beta overview
- `public/review.html`: App review information
- `public/testing.html`: What to test
- `public/eula.html`: End user license agreement

## Deploy to Cloudflare Workers

Connect this repository in Workers Builds. Leave the build command empty and use `npx wrangler deploy` as the deploy command.

The TestFlight URL is currently a placeholder (`TRACE000`). Replace it in the four HTML files when an invitation is available.

Simple.css is included locally under `public/assets/` and is licensed under the MIT license.
