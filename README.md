# wondermawgames.com

Static website for Wondermaw Games, hosted on Cloudflare Pages.

No build step: Cloudflare serves the files in the repo root as they are.

- `index.html` is the landing page
- `styles.css` holds all styling
- `404.html` is served for missing pages
- `fonts/` holds the custom Wondermaw Display font (caps only, used for headings)
- `img/` holds the logo (`logo.png`) and the monster mark (`mark.png`, also the favicon)

Every push to `main` redeploys the site automatically.

## Cloudflare Pages settings

- Framework preset: None
- Build command: (leave empty)
- Build output directory: `/`

## Edit locally

Open `index.html` in a browser, or run `npx serve .` and visit http://localhost:3000.
