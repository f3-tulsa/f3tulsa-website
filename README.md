# F3 T-Town Website

This repo contains a simple Astro site for F3 T-Town. It is intended to be deployed to Cloudflare Workers.

## Quick Start for Devs

```bash
npm install
npm run dev
```

Then open `http://localhost:4321`.

## Where To Edit Content

### Home page

Edit `src/pages/index.astro`.

This file controls the content and layout for the `/` route (the main landing page). If you want to change text, sections, images, or links on the homepage, this is the file to edit.

### 404 page

Edit `src/pages/404.astro`.

This file controls the not-found page shown when someone visits an invalid URL. Update the messaging, links back to the homepage, or any styling here.

## Project Structure (Short Version)

- `src/pages/` contains page routes. Each `.astro` file becomes a route.
- `public/` contains static assets like images or icons.

## Common Commands

| Command         | Action                                      |
| :-------------- | :------------------------------------------ |
| `npm run dev`   | Start local dev server at `localhost:4321`  |
| `npm run build` | Build the production site to `./dist/`      |
| `npm run preview` | Preview the production build locally      |
