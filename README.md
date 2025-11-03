# SnackboxNM Static Site

This repo is ready for **Netlify continuous deployment** (no build step).

## Structure
- `index.html` — landing page
- `thank-you.html` — Netlify form success page
- `styles.css` — minimal styling
- `assets/logo.svg` — vector logo (bite‑box, red)
- `assets/favicon.svg` — favicon
- `netlify.toml` — static publish config and headers

## Deploy
1. Create a new GitHub repo and push these files.
2. In Netlify, click **Add new site → Import from Git** and connect the repo.
3. Keep **Build command** empty and **Publish directory** as `.` (root).
4. Optional: Set your custom domain to `snackboxnm.com`.

## Manual upload (if needed)
You can also upload the ZIP below directly in Netlify **Deploys → Upload deploy**.
