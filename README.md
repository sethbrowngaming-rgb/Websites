# Websites

Personal collection of websites — one project per folder as this repo grows.

**Live site:** https://sethbrowngaming-rgb.github.io/Websites/

## portfolio (this folder, repo root)

`index.html` — single-file personal portfolio site: shipped/in-development games, web
projects (Zebonastic), side ventures (PixelBeadCo), toolkit, education, and contact.
No build step; it's plain HTML/CSS/JS.

`ads.txt` — AdSense publisher declaration (pub-3358856676053073).

GitHub Pages is already enabled (deploys from `main`, root folder) — the repo has to
stay **public** for that to keep working on GitHub's free tier. Every push to `main`
redeploys automatically within a minute or two.

To update the content later, edit `index.html` directly (or ask Claude to) and push.

## Adding more sites later

Once there's a second project, we can either move each site into its own subfolder
(and deploy each with something like Netlify/Vercel, since GitHub Pages only serves
one site per repo by default) or split them into separate repos. No need to decide
that now — the portfolio works fine at the root as-is.
