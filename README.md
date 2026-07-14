# Sonoran Shooting Industries — Website

Static site for sonoranshooting.com. Plain HTML/CSS/JS, no build step.

## Pages
- `index.html` — Home
- `coupler.html` — Gen 12 Magazine Coupler
- `belt-clip.html` — Gen 12 Belt Clip
- `engraving.html` — Laser Engraving
- `contact.html` — Contact (Formspree form)

## Deploying via GitHub Pages
1. Push/upload all files in this folder to the repo root (or a `docs/` folder — adjust the Pages source setting to match).
2. Repo → Settings → Pages → Source: deploy from `main` branch, root folder.
3. GitHub publishes at `https://<username>.github.io/SonoranShooting/`. To use sonoranshooting.com instead: add a `CNAME` file (already included) containing `sonoranshooting.com`, and point the domain's DNS at GitHub Pages per GitHub's custom-domain docs.

## Notes
- Contact form posts to Formspree (form ID `xwvgkevd`).
- GunTab checkout links use a fixed checkout UUID for SSI purchases.
- Video backgrounds: `home-bg-video.mp4` (home hero). Keep file sizes reasonable for page load.
