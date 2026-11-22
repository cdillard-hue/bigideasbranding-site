# Big Ideas Branding

Marketing site for Big Ideas Branding — social media strategy, branding and website services for small businesses, plus work from Wild Bear Safari and Hoonah Off Ship.

## Structure

- `index.html` — the home page
- `case-studies/` — full case study pages, linked from the home page
- `assets/` — logo and photos (`assets/case-studies/<client>/` for case study images)

## Local preview

Open `index.html` directly in a browser, or serve the folder:

```
python3 -m http.server 8000
```

## Deploy

Static site, no build step. On Netlify: new site from Git, connect this repo, leave the build command blank, publish directory `/`.

## Editing

- Contact form email: search `CONTACT_EMAIL` near the bottom of `index.html` and update the address.
- Service copy, case studies and results numbers are plain HTML in the matching `<section>` blocks (`#services`, `#work`, `#results`).
- Metabolism Mastered case study (`case-studies/metabolism-mastered.html`): HTML comments mark where to drop in the before/after screenshots, the two program logos, the Meet Bex video and a quote from Bex.
