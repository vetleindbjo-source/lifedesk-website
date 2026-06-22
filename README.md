# lifedesk-website

Marketing landing page for **LifeDesk**, deployed on Vercel at the apex domain `lifedesk.no`.

- `index.html` — the static landing page.
- `vercel.json` — redirects `/app` → `https://www.lifedesk.no/app` (the web app, hosted on Railway).

The app, backend, and OAuth live on Railway at `www.lifedesk.no`. This repo is only the public landing page, kept separate so the bare domain `lifedesk.no` can resolve via Vercel's apex `A` record (which Railway/Domeneshop couldn't do with a CNAME).
