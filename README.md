# Websites

Personal collection of websites — one folder per project, named for the site it holds.

**Portfolio:** https://sethbrowngaming-rgb.github.io/Websites/portfolio/
**Los Amigos Mexican Restaurant:** https://sethbrowngaming-rgb.github.io/Websites/los-amigos/

## Layout

- `index.html` (repo root) — a small landing page linking to each project below. Also
  carries the AdSense verification snippet (see note on the separate root repo below).
- `portfolio/` — the personal portfolio site. `portfolio/index.html` is a single-file
  HTML/CSS/JS build (no dependencies, no build step): shipped/in-development games,
  web projects (Zebonastic), side ventures (PixelBeadCo), toolkit, education, and
  contact/social links. `portfolio/ads.txt` is its AdSense publisher declaration
  (pub-3358856676053073).
- `los-amigos/` — menu site for Los Amigos Mexican Restaurant. Browsing only, no
  online ordering. Menu content was transcribed from photographed menu pages — a
  handful of prices/descriptions were partly obscured by glare or cropping and are
  flagged inline on the page itself (search "check menu" / marked with `*`) — worth
  confirming against the physical menu before treating this as final. The About
  section also has a placeholder for a restaurant story blurb; address, phone, and
  hours are filled in from Google's listing. `los-amigos/ads.txt` carries the same
  AdSense publisher id as `portfolio/`.

## A second, separate repo: `sethbrowngaming-rgb.github.io`

GitHub Pages treats a repo named exactly `<username>.github.io` specially — it's the
only thing that can serve the bare domain root (`https://sethbrowngaming-rgb.github.io/`,
no path after it). This `Websites` repo can only ever serve under `/Websites/...`, no
matter what's pushed to its root — the two are separate GitHub Pages sites.

That repo exists solely so AdSense's site-ownership verification (which checks the bare
domain root) has something to find — it holds a copy of the same small landing page.
There's no real content duplication concern since it's just a links page, but if this
repo's root `index.html` changes meaningfully, it's worth mirroring the change there too.

## Deploying

GitHub Pages is enabled on both repos (deploys from `main`, repo root) — both need to
stay **public** for that to work on GitHub's free tier. Every push to `main` redeploys
automatically within a minute or two. Since Pages serves the whole repo tree, each
project folder here is reachable at `.../Websites/<folder>/` as soon as it's pushed —
no extra Pages configuration needed per project.

## Adding more sites

Give each new project its own folder at the repo root, named for that site, same
pattern as `portfolio/` — self-contained, its own `index.html`. Add a link to it from
the root `index.html` too.
