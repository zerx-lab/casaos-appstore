# FluxDown CasaOS / ZimaOS App Store

A third-party [CasaOS](https://casaos.io) / ZimaOS app store hosting **FluxDown**,
a Rust-powered multi-protocol download manager.

## Add this store

In ZimaOS: **App Store → Sources → Add**, then enter:

```
https://cdn.jsdelivr.net/gh/zerx-lab/casaos-appstore@gh-pages
```

Then install **FluxDown** from the store.

- App: https://github.com/zerx-lab/FluxDown
- Website: https://fluxdown.zerx.dev
- Image: `ghcr.io/zerx-lab/fluxdown-server`

## Build (CI)

Pushing to `main` triggers `.github/workflows/deploy.yml`, which runs the official
`build_appstore.py` and publishes the static store to the `gh-pages` branch.
