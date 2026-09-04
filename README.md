# Websites

Personal collection of websites — one folder per project, named for the site it holds.

**Portfolio:** https://sethbrowngaming-rgb.github.io/Websites/portfolio/

## Layout

- `portfolio/` — the personal portfolio site. `portfolio/index.html` is a single-file
  HTML/CSS/JS build (no dependencies, no build step): shipped/in-development games,
  web projects (Zebonastic), side ventures (PixelBeadCo), toolkit, education, and
  contact/social links. `portfolio/ads.txt` is its AdSense publisher declaration
  (pub-3358856676053073).

No files live loose at the repo root — just this README and one folder per site, so
`/` stays a clean list of projects as more get added.

## Deploying

GitHub Pages is enabled (deploys from `main`, repo root) — the repo needs to stay
**public** for that to work on GitHub's free tier. Every push to `main` redeploys
automatically within a minute or two. Since Pages serves the whole repo tree, each
project folder is reachable at `.../Websites/<folder>/` as soon as it's pushed — no
extra Pages configuration needed per project.

Note: the bare root URL (`https://sethbrowngaming-rgb.github.io/Websites/`) has no
`index.html` to serve, so it 404s on purpose — go straight to a project's own folder
instead (e.g. `/portfolio/`). If a root landing page linking to every project is
wanted later, that's a small addition once there's more than one site to list.

## Adding more sites

Give each new project its own folder at the repo root, named for that site, same
pattern as `portfolio/` — self-contained, its own `index.html`.
