# ishaan-site

Personal site for Ishaan Gulati. Single static `index.html`, no build step, deploy on Vercel with zero config.

Includes `robots.txt`, `sitemap.xml`, and `llms.txt` for search and LLM-retrieval indexing, plus JSON-LD Person markup in the page head.

## Deploy to Vercel
1. Push this repo to GitHub.
2. Go to [vercel.com/new](https://vercel.com/new), import the repo.
3. No build settings needed (framework preset: **Other**). Hit Deploy.
4. Enable Vercel Web Analytics for the project (the site already includes the tracking script).

## Run locally
Just open `index.html` in a browser.

## TODO before shipping
Search `index.html` for `PASTE_` to find placeholder links that still need real URLs:
- LinkedIn
- Pulse App Store link
- Fern.ai Devpost/GitHub link
- Felix Devpost/GitHub link
- Instagram (@investingwithishaan)

Once those are set, add the matching `sameAs` array to the JSON-LD block in `<head>`.
