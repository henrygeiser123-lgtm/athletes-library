# The Athlete's Library website

- `index.html`: the store site
- `guide/index.html`: the Release Kit Smart Guide (opened from the QR card)
- `release-kit-logo.svg`: logo used by both pages

All links between files are relative, so the site works the same on any domain.

## Moving to a custom domain
1. Buy the domain.
2. In this repo: Settings → Pages → Custom domain → enter it → Save. Turn on "Enforce HTTPS" once it's offered.
3. At the domain registrar, add DNS records:
   - Root domain: four A records to 185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153
   - `www`: a CNAME record to the GitHub Pages address of this account (USERNAME.github.io)
Old github.io links, including QR codes, then redirect to the new domain automatically.
