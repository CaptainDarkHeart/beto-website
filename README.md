# Beto Ruiz Alonso — Website

Rebuild of [betoruizalonso.com](https://www.betoruizalonso.com/), a Berlin-based portrait, fashion, and event photographer's portfolio site.

Built with [Astro](https://astro.build), styled after a minimal, single-image gallery viewer (à la Jack Davison's portfolio site): one photo on screen at a time, a slide-in index panel for site navigation, and a full-screen thumbnail lightbox.

## Structure

- `src/pages/` — routes: Home, Events, Portraits, Actors, About
- `src/components/Gallery.astro` — single-image viewer (click left/right to navigate, Thumbs lightbox, Index toggle)
- `src/components/SiteIndex.astro` — slide-in side panel listing site sections (Works / Info)
- `src/components/IntroOverlay.astro` — homepage intro: name and tagline fade sequence
- `src/layouts/Layout.astro` — shared page shell
- `src/styles/global.css` — fonts, color tokens

Events gallery uses real client photos. Portraits and Actors galleries are still placeholders ([picsum.photos](https://picsum.photos)) pending real photo assets from the client.

## Deployment

Pushes to `main` auto-deploy to Cloudflare Pages via GitHub Actions (`.github/workflows/`).

## Development

```sh
npm install
npm run dev
```

## Commands

| Command           | Action                                      |
| :----------------- | :------------------------------------------- |
| `npm install`       | Install dependencies                        |
| `npm run dev`       | Start local dev server at `localhost:4321`  |
| `npm run build`      | Build production site to `./dist/`          |
| `npm run preview`     | Preview the build locally                    |
