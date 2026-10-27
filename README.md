# QuickConnex company site

Static one-page site for **quickconnex.tech**. There's no build step: open `docs/index.html` in a browser.

## Files
Everything under `docs/` is published. Everything outside it, this README included, is not.

- `docs/index.html`: single page (hero, RenoDesk, contact, footer)
- `docs/styles.css`: theme, shared with the RenoDesk landing page
- `docs/logo-mark.svg`, `docs/favicon.svg`: gear mark and favicon
- `docs/robots.txt`, `docs/sitemap.xml`: crawler files
- `docs/CNAME`: the custom domain GitHub Pages serves (`quickconnex.tech`)
- `docs/.nojekyll`: serve the files as they are, with no Jekyll build

HTML comments ship to the browser, so keep working notes out of `docs/`.

## Hosting
GitHub Pages, published from the `docs/` folder on `main`.
