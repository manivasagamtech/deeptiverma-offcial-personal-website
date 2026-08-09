# Dr. Deepti Verma — Official Personal Website

Elegant, multi-page personal website for **Dr. Deepti Verma** — award-winning nutritionist,
life coach and corporate leadership trainer; Director of MasterMind Body Global.

**Live domain (target):** https://www.drdeeptiverma.world

## Pages

| URL | Page |
|---|---|
| `/` | Home |
| `/about/` | About — biography, career timeline, at-a-glance infobox |
| `/services/` | What She Does — individual coaching & corporate training |
| `/awards/` | Awards & Recognition |
| `/speaking/` | Speaking & Media |
| `/connect/` | Connect — all official social platforms & contact |

## Tech

- Pure static HTML/CSS/JS — no build step, no dependencies. Deploys directly to GitHub Pages.
- Fully responsive (mobile + desktop), accessible markup, SEO meta + JSON-LD Person schema,
  `sitemap.xml` and `robots.txt`.
- All internal links are **relative**, so the site works both at
  `https://<user>.github.io/<repo>/` and at the root of the custom domain.

## Deploying to GitHub Pages

1. Push to the `main` branch.
2. In the repo: **Settings → Pages → Source: Deploy from a branch → `main` / root**.
3. The site is live at `https://<user>.github.io/<repo>/`.

## Connecting the custom domain (www.drdeeptiverma.world)

1. In **Settings → Pages → Custom domain**, enter `www.drdeeptiverma.world` (this creates a
   `CNAME` file in the repo).
2. At the domain registrar, add a DNS record:
   - `CNAME` record: `www` → `<user>.github.io`
   - Optionally, apex `drdeeptiverma.world` → `A` records `185.199.108.153`,
     `185.199.109.153`, `185.199.110.153`, `185.199.111.153`
3. Back in GitHub Pages settings, tick **Enforce HTTPS** once the certificate is issued.

## Content source

All facts, services, links and award details were researched and compiled in
[CLIENT-BRIEF.md](CLIENT-BRIEF.md).
