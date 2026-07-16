# Hub

A minimal launcher for my AI fashion ecosystem. One landing page, three apps.

## What it does

Single static page with three tiles — click one and it opens that app in a new tab. No login, no backend, no shared session. Each app handles its own auth independently.

| App | Description | Status |
|---|---|---|
| [WYA](https://dsbml6kwxecah.cloudfront.net/) | Build and organize your digital wardrobe | Live |
| [Luna](https://d34nojihupg1cl.cloudfront.net/) | AI stylist for outfits and fashion advice | Live |
| TryOn | See outfits on a 3D avatar | Coming soon |

## Live

**[ria0304.github.io/hub](https://ria0304.github.io/hub)**

## Stack

Plain HTML/CSS, no build step, no dependencies (aside from Google Fonts for Playfair Display + Inter). Deployed via GitHub Pages.

## Local development

Just open `index.html` in a browser. No install, no server needed.

## Deploy

Push to `main` — GitHub Pages serves `index.html` from the repo root automatically.

## Roadmap

- [ ] Swap TryOn's placeholder tile for a live link once that app ships
- [ ] Add a custom domain
