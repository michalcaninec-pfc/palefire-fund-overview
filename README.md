# Pale Fire Capital — Partner One-Pager

Static one-page brochure ("Investment Strategy & Acquisition Criteria") for M&A / acquisition-financing partners. Self-contained `index.html` (inline CSS + JS) + `assets/` (logos, OG image). No backend, no build.

- **Live URL:** https://partners.palefire.com (GitHub Pages + custom domain)
- **noindex:** `<meta name="robots" content="noindex, nofollow">` + `robots.txt` disallow — distributed by link, not search-indexed. Not password-protected (meant for free forwarding to partners).
- **Source of the content:** originally published via the PFC publish-sites system at `reporting.palefire.com/ai-workflows/sites/palefire-fund-overview/`; moved to GitHub Pages 2026-06-11 to get a clean shareable hostname with auto-provisioned HTTPS.

## Updating

Edit `index.html` / `assets/`, commit, and push to `main`. GitHub Pages redeploys automatically (~1 min). Keep the `CNAME` file (contains `partners.palefire.com`) — deleting it drops the custom domain.

## DNS

`partners.palefire.com` is a `CNAME` → `palefire-capital.github.io` (managed by the PFC DNS admin). GitHub provisions the Let's Encrypt cert automatically once that record resolves.
