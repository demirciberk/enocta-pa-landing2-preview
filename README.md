# Enocta PA — Landing2 preview

Static, public visual preview of the **Landing2** page (the sticky "Inky" cinematic
chapter plus the capability, trust and closing sections).

## What this is

- A standalone Vite + React build of the Landing2 page only, published with GitHub Pages.
- Assets (scroll-scrubbed `world.mp4`, poster, product proof shot, mascot art, fonts) are served from this repo.

## What this is not

- **No backend and no API are included.** Anything that looks like a call to action or a
  session in the real product is inert here: no server, no profiles, no data layer.
- The repository is a visual preview, not the Enocta PA application source.

## Build

```sh
npm ci
npm run build
```

`vite.config.ts` sets `base: '/enocta-pa-landing2-preview/'` because Pages serves this
project from a sub-path. The published output is the repository root (`dist/` contents
are committed on `main`).
