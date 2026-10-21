# Taxable

Bilingual (ES/EN) prototype of Taxable, a tax and finance app for Panama: tax calculators, calendar, ITBMS, payroll, municipal taxes, transfer pricing, defense file, bank statements, partner portal and more.

The whole app is a single static file, `index.html`. Nothing is stored on a server: data stays in the browser and is lost on reload.

## Publishing at abaxgrid.com/taxableapp

1. **Settings → Pages → Build and deployment:** Source "Deploy from a branch", branch `main`, folder `/ (root)`.
2. The app is then served at `https://dannysimgames.github.io/taxableapp/`.
3. It appears at `https://abaxgrid.com/taxableapp/` only if `abaxgrid.com` is set as the custom domain of the account's user site (the `dannysimgames.github.io` repository). Project sites inherit that domain as a path.

`.nojekyll` tells GitHub Pages to serve the file as is.

## Updating

Replace `index.html` with the new version and push to `main`. Pages redeploys in a minute or two.

## Status

Prototype. No login, no backend, simulated submissions. Items marked [POR VERIFICAR] in the app still need legal or tax review. The page carries a `noindex` tag until it goes public.
