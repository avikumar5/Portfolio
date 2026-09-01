# Kshitiz Kumar — Portfolio

Personal portfolio site for Kshitiz Kumar, a full-stack developer and AI engineer. Single-page site built with Astro and Tailwind CSS, featuring GSAP-driven animations, a Matter.js physics playground for the tech-stack section, and a live "now playing" widget powered by the Last.fm API.

Live at [kshitizkumar.vercel.app](https://kshitizkumar.vercel.app).

## Tech Stack

- [Astro](https://astro.build) — static site generation
- [Tailwind CSS 4](https://tailwindcss.com) — styling
- [GSAP](https://gsap.com) — scroll and load animations
- [Matter.js](https://brm.io/matter-js/) — physics-based tech-stack visualization
- [Lenis](https://lenis.darkroom.engineering/) — smooth scrolling
- Deployed on [Vercel](https://vercel.com), with Vercel Analytics and Speed Insights

## Project Structure

```
src/
├── components/     # Section components (Hero, About, Experience, Technologies, Education, Footer, ...)
├── layouts/        # Base HTML layout with SEO meta tags
├── pages/          # index.astro (single page) and 404.astro
├── styles/         # Global CSS and Tailwind theme
public/             # Static assets (favicon, resume, images)
```

## Environment Variables

Copy `env.example` to `.env` and fill in the values. See that file for what's required (e.g. `PUBLIC_LASTFM_API_KEY` for the now-playing widget).

## Commands

All commands are run from the root of the project, from a terminal:

| Command             | Action                                      |
| :------------------- | :------------------------------------------ |
| `npm install`         | Installs dependencies                       |
| `npm run dev`          | Starts local dev server at `localhost:4321` |
| `npm run build`        | Builds the production site to `./dist/`     |
| `npm run preview`      | Previews the production build locally       |
| `npm run astro ...`    | Runs Astro CLI commands (e.g. `astro check`) |
