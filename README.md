# wondermawgames.com

Static website for Wonder Maw Games, hosted on Cloudflare Pages.

No build step: Cloudflare serves the files in the repo root as they are.

- `index.html` is the landing page
- `styles.css` holds all styling
- `404.html` is served for missing pages

Every push to `main` redeploys the site automatically.

## Cloudflare Pages settings

- Framework preset: None
- Build command: (leave empty)
- Build output directory: `/`

## Edit locally

Open `index.html` in a browser, or run `npx serve .` and visit http://localhost:3000.
