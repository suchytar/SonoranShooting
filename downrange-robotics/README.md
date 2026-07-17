# Downrange Robotics — Landing Page

Initial landing page for Downrange Robotics. Single self-contained `index.html` (no build step, no dependencies) — ready to host on GitHub Pages.

## Deploying to a new repository

This session's GitHub access couldn't create a new repo, so to move this into its own `Downrange-Robotics` repo:

1. Create the repo at https://github.com/new (name: `Downrange-Robotics`, public).
2. Copy `index.html` (and this README) into it and commit to `main`.
3. In the repo: **Settings → Pages → Source: Deploy from a branch → main / (root) → Save**.

## Linking a Porkbun domain to GitHub Pages

See the instructions in the pull request / chat, or in short:

1. **Porkbun** → your domain → DNS: delete Porkbun's default ALIAS/CNAME parking records, then add:
   - `A` records on the root (leave host blank) pointing to `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`
   - `CNAME` record, host `www`, answer `suchytar.github.io`
2. **GitHub** → repo → Settings → Pages → Custom domain: enter your domain, save, and check **Enforce HTTPS** once the certificate is issued (can take up to ~24h for DNS to propagate, usually much faster).
