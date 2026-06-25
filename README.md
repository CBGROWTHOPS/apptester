# App Tester (apptester.online)

Pre-lander funnel for the Nielsen Pulse offer (MaxBounty campaign 32298).

## Flow

1. `/` — landing page (Nielsen-aesthetic dark/purple/cyan, "Check Eligibility" CTA)
2. `/start` — 5-question quiz funnel + matching screen + final "Get Started" button
3. Button → `https://trk.ssaff.link/mb-32298/{cmc_vid}/ato` (CM smart link with brand-attribution path-suffix)

## Brand slug
- `ato` = App Tester Online (used as [s2] for per-brand attribution in the rotator)

## Deploy
Auto-deploys on push to `main` via Vercel (no build step — static HTML).

## Local preview
Open `index.html` in browser, or run any static file server in this directory.
