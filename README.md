# limit0ventures.com

Static single-page site for **Limit 0 Ventures** — a name-swapped clone of the
`limit0labs.com` landing page (`~/code/websites/limit0labs.com/index.html`).

- Everything lives in `index.html` (self-contained; only external dep is Google Fonts).
- Deployed to Vercel as a static site (no build step).
- Redeploy: `cd ~/code/websites/limit0ventures.com && vercel --prod`

## Known carry-overs from the source page
The source page ships unfilled social placeholders; they were copied verbatim:
`YOUR_LINKEDIN_URL` and `YOUR_TWITTER_URL` (2 occurrences each).
