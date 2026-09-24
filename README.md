# Zouk Navigator

Static, single-file dashboard (`index.html`, data embedded). No build step.

## Deploy on Vercel (recommended: private)
1. Create a **private** GitHub repo (e.g. `zouk-navigator`) and upload these files.
2. vercel.com → Add New → Project → import the repo → Framework preset: **Other** → Deploy.
3. Project → Settings → Deployment Protection → turn on **Vercel Authentication** (team members only) or **Password Protection** (Pro plan).

## Or GitHub Pages
Repo → Settings → Pages → Deploy from branch `main` / root.
Note: GitHub Pages sites are public on free plans, even from a private repo — anyone with the link can see spend and revenue.

## Daily refresh
Replace `index.html` with the new build and commit. Vercel redeploys automatically on every push.
