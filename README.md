# Websites

Personal collection of websites — one project per folder as this repo grows.

## portfolio (this folder, repo root)

`index.html` — single-file personal portfolio site: shipped/in-development games, web
projects (Zebonastic), side ventures (PixelBeadCo), toolkit, education, and contact.
No build step; it's plain HTML/CSS/JS.

**Deploy on GitHub Pages:**
1. Repo → Settings → Pages
2. Source: "Deploy from a branch"
3. Branch: `main`, folder: `/ (root)`
4. Save — it'll be live at `https://sethbrowngaming-rgb.github.io/Websites/` in a minute or two.

To update the content later, edit `index.html` directly (or ask Claude to) and push —
Pages redeploys automatically on every push to `main`.

## Adding more sites later

Once there's a second project, we can either move each site into its own subfolder
(and deploy each with something like Netlify/Vercel, since GitHub Pages only serves
one site per repo by default) or split them into separate repos. No need to decide
that now — the portfolio works fine at the root as-is.
