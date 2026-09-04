# Websites

Personal collection of websites — one folder per project as this repo grows.

**Live site:** https://sethbrowngaming-rgb.github.io/Websites/ (redirects to the portfolio below)

## Layout

- `index.html` (repo root) — a redirect stub that forwards `/` to `/portfolio/`. Once
  there's a second project, this becomes a real landing page linking to each one.
- `ads.txt` (repo root) — AdSense publisher declaration (pub-3358856676053073). Stays
  at the repo root on purpose, since ad-crawlers look for it as close to the site root
  as possible.
- `portfolio/` — the personal portfolio site. `portfolio/index.html` is a single-file
  HTML/CSS/JS build (no dependencies, no build step): shipped/in-development games,
  web projects (Zebonastic), side ventures (PixelBeadCo), toolkit, education, and
  contact/social links. Live directly at
  https://sethbrowngaming-rgb.github.io/Websites/portfolio/

## Deploying

GitHub Pages is already enabled (deploys from `main`, repo root) — the repo needs to
stay **public** for that to work on GitHub's free tier. Every push to `main` redeploys
automatically within a minute or two. Since Pages serves the whole repo tree, any new
project folder is reachable at `.../Websites/<folder>/` the moment it's pushed — no
extra Pages configuration needed per project.

## Adding more sites

Give each new project its own folder next to `portfolio/` (same pattern: its own
`index.html`, self-contained). Then add a link to it from the root `index.html` so
`/` becomes a real landing page instead of a straight redirect.
