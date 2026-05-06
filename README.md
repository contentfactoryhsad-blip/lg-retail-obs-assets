# LG Retail OBS — Asset Library

Cutout graphic assets used by the LG Retail OBS Content Builder.

Served via [jsDelivr CDN](https://www.jsdelivr.com/) for global edge caching:

```
https://cdn.jsdelivr.net/gh/contentfactoryhsad-blip/lg-retail-obs-assets@main/{category}/{filename}.png
```

## Structure

- `for-dark-bg/` — graphics designed for dark background banners
- `for-light-bg/` — graphics designed for light background banners

All files are 1280×1280 transparent PNG cutouts.

## Updating

1. Add or remove PNGs in the appropriate folder
2. Commit + push to `main`
3. In the consumer repo, run `npm run assets:build` and commit the regenerated `manifest.json`
4. jsDelivr cache: changes to `@main` propagate within minutes; for instant invalidation, request `https://purge.jsdelivr.net/gh/contentfactoryhsad-blip/lg-retail-obs-assets@main/<path>`
