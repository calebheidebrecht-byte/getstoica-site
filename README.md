# Stoica brand site (getstoica.com)

Static brand site for Stoica (GRIT, SHIFT, FLOW). No cart, no checkout, no accounts: every "Buy" button links to TikTok Shop, where orders, payments, customers and fulfillment are handled.

## Files
- index.html - home, product cards, how it works, FAQ
- about.html - mission, vision, team
- research.html - placebo research, articles, books, talks
- policies.html - legal disclaimer, shipping, returns, privacy, terms
- style.css - shared styles
- assets/ - product images (see below)

## TODO before pointing getstoica.com at this site
1. Add product images to assets/: grit.png, shift.png, flow.png (transparent front-of-bottle shots). Pages hide a missing image, so the site works without them.
2. Replace the generic TikTok profile link (https://www.tiktok.com/@getstoica) on each product card in index.html with that product's own TikTok Shop link (copy from Seller Center or the TikTok app).
3. Have the policy text reviewed (policies.html was rewritten for a TikTok-checkout site; the old Shopify terms/privacy text was not carried over).
4. Confirm TikTok does not depend on Shopify for inventory/fulfillment, then cut over DNS.

## Hosting
GitHub Pages, deploy from branch main, root folder. Custom domain: add a file named CNAME containing getstoica.com, and point DNS to GitHub Pages (A records 185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153; keep the existing MX/TXT records for Google Workspace email).

## Notes
- Prices are intentionally not shown; TikTok Shop is the source of truth for price.
- Original Shopify content (pages, policies) was captured on 2 Nov 2026 before the Shopify store is cancelled.
