# The People-Pleasing Interrupt

Sales page, checkout, and legal pages for The People-Pleasing Interrupt by Ari Hale.

Live at: https://ariellehale.github.io/people-pleaser-interrupt/

## Files

- `index.html` — Sales page (Hook/Story/Offer framework, Kit commerce checkout)
- `thank-you.html` — Post-purchase page (product delivery link, onboarding steps, ascension offers)
- `disclaimer.html` — General disclaimer (Hale Yeah! Marketing, LLC)
- `earnings-disclaimer.html` — Earnings disclaimer
- `cookie-policy.html` — Cookie policy
- `terms.html` — Terms of service (covers all programs, products, and content)

## Tracking

- Google Analytics: G-548VKLG1E8 (on all pages)
- Meta Pixel: 3013518292267783 (on all pages)

## Checkout

All CTA buttons trigger the Kit commerce overlay via `data-commerce` attribute. Commerce script loads from `arielle-hale.kit.com/commerce.js`.

## Post-Purchase Flow

Kit redirects buyers to `thank-you.html` after checkout. That page links directly to the Notion product and seeds the Substack and 90-Minute Precision Session.

## Hosting

Published via GitHub Pages. All internal links use the full base URL: `https://ariellehale.github.io/people-pleaser-interrupt/`
