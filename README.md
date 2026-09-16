# Agama Design Collective website

An Astro website for Agama Design Collective. The project is designed as a static, photography-led portfolio that can be maintained through Git by a developer or coding agent.

## Local development

Use Node.js 22 or later and pnpm:

```sh
pnpm install
pnpm dev
```

Create a production build with `pnpm build`.

## Structure

- `src/pages/` contains the routes.
- `src/components/` contains reusable interface components.
- `src/layouts/` contains the shared page shell.
- `src/assets/` contains source images that Astro optimizes at build time.
- `public/brand/` contains brand assets copied directly to the final site.
- `projects/` and `studio/` contain the original client material. Preserve these files.

## Design rules

- No text smaller than 14px.
- Normal text must meet a minimum 4.5:1 contrast ratio.
- Use `#1c1c18` for primary text and `#4d4b43` for secondary text on `#f4f0e8`.
- Instrument Sans is used throughout, with weight and width variation creating hierarchy.
- Motion must respect `prefers-reduced-motion`.
- Keep the homepage restrained and no-scroll on standard desktop viewports.
- Use real project photography and preserve its natural proportions.

## Current milestone

The homepage and the first Geethalayam project page establish the visual system. Projects, Studio and Contact routes currently provide the initial structure for the remaining content.
