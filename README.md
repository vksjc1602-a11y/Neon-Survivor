# Neon Survivor

A responsive, single-page HTML5 Canvas arcade game. Dodge falling meteors, collect energy shards, protect your hull and beat your best score.

**Live game:** https://neon-survivor-rocket.netlify.app  
**Repository:** https://github.com/vksjc1602-a11y/Neon-Survivor

## Features

- HTML5 Canvas gameplay with no framework or build step
- Keyboard controls and touch controls for phones
- Pause, resume and restart
- Three lives, falling meteors and energy pickups
- Local high-score saving in the browser
- Responsive layout
- About and starter privacy pages
- Netlify-ready static configuration

## Run locally

No dependencies or installation are required. Open `index.html` in a modern browser, or run a local static server:

```bash
python3 -m http.server 8000
```

Then visit http://localhost:8000.

## Controls

| Action | Control |
| --- | --- |
| Move | `←` / `→` or `A` / `D` |
| Pause / resume | `Space` or Pause button |
| Mobile movement | Hold the left/right on-screen controls |

Your best score is stored locally in your browser on that device.

## Deploy to Netlify

1. In Netlify, choose **Add new project → Import an existing project**.
2. Connect this GitHub repository.
3. No build command is required. Use `.` as the publish directory.
4. Deploy and test on desktop and mobile.

## Advertising and AdSense

Advertising is **not enabled** in this project. There is no publisher ID or active ad code.

Before applying for Google AdSense:

1. Publish original, useful content and make sure all navigation works.
2. Replace generic contact wording on `about.html` and `privacy.html` with accurate details and a real contact method.
3. Review the privacy policy against the services and cookies actually used on the site. The included policy is a starter, not legal advice.
4. Apply through your own AdSense account and wait for Google's site review.
5. Only after approval, add the exact site and ad-unit code supplied by Google. Keep ads clearly labelled and away from gameplay controls.
6. Add `ads.txt` only as instructed by AdSense.

A published game does not guarantee AdSense approval or income. Earnings depend on genuine traffic, eligible impressions, audience, advertiser demand and policy compliance. Never click your own ads, ask visitors to click ads, or use bot traffic or click exchanges.

## Project structure

```text
neon-survivor/
├── index.html
├── about.html
├── privacy.html
├── netlify.toml
├── .gitignore
└── README.md
```

This is a static website; it does not require a backend, database, build step or API key. Review the About and Privacy pages before using the website for monetization.
