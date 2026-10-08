# Majesty's Pleasure — static GitHub Pages

Two static pages: `/` and `/flatiron/`. No Webflow assets, JavaScript, or branding. Google Analytics uses measurement ID `G-HC3DVVEXPE` and reports page_location using the main website URLs. The real hosting remains GitHub Pages.

Upload `index.html`, `flatiron/` and `.nojekyll` into the root of the GitHub repository. Enable Pages with `main` and `/(root)`.

**Important:** This package deliberately does not include the original GTM container (`GTM-PZ37ZR2`), to avoid unexpected additional tags. If the main site relies on GTM for conversion tracking, review this before replacing the old implementation. Also test GA4 Realtime and events after deployment; reporting a virtual page_location does not merge user identities across domains.
