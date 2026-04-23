# Heart Financial Advisers — Website

Static site hosted on Netlify, source on GitHub.

## Files
- `index.html` — master page (embeds both parts)
- `heart-part-1.html` — nav → hero → about → services → testimonials
- `heart-part-2.html` — award → CTA → contact form → footer
- `embed-hero-info-card.html` / `embed-townsville-pill.html` — standalone component embeds (legacy Wix — kept for reference)

## Deploy
Pushing to `main` auto-deploys via Netlify.

## Contact form
`heart-part-2.html` uses Web3Forms. Replace `REPLACE_WITH_YOUR_WEB3FORMS_KEY` with a real access key from https://web3forms.com (delivers to `clientservices@heart1stop.com`).
