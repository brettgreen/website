# Project: Brett Green Academic Website

## Status
Migrating from Wix to a free static site hosted on GitHub Pages.

## What's Done
- Built a new static HTML/CSS site in `new-site/` with 3 pages:
  - `index.html` (Home) - bio, photo, education, editorial positions, contact
  - `publications.html` - 17 published papers with abstracts
  - `working-papers.html` - 4 working papers with status/abstracts
  - `styles.css` - responsive academic design (blues/whites, Raleway + Avenir fonts)
  - `assets/headshot.jpg` and `assets/CV_Brett_Green.pdf`
- Nav links: Home, Publications, Working Papers, CV (PDF), Google Scholar, SSRN, Contact
- CV PDF is hosted in repo (was previously on Dropbox)

## What's Left
1. **Preview the site** - open `new-site/index.html` in a browser to review
2. **Restructure repo for deployment** - move `new-site/*` to repo root, remove old Wix files (src/, package.json, wix.config.json, wix.lock)
3. **Enable GitHub Pages** - serve from main branch root
4. **Configure custom domain** - add CNAME file for `www.brettgreen.info`, update DNS:
   - CNAME record: `www` -> `brettgreen.github.io`
   - A records for apex: 185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153
5. **Enable HTTPS** in GitHub Pages settings

## Key Details
- Domain: brettgreen.info (custom domain, user wants to keep it)
- Google Scholar: https://scholar.google.com/citations?user=3lDWe9kAAAAJ&hl=en
- SSRN: https://papers.ssrn.com/sol3/cf_dev/AbsByAuth.cfm?per_id=1010842
- Email: b.green@wustl.edu
- Affiliation: Olin Business School, Washington University in St. Louis

## Old Wix files (can be deleted)
- `src/`, `package.json`, `wix.config.json`, `wix.lock`, `.eslintrc.json`
- Saved HTML reference files: `Brett Green Academic Research*.html`, `Publications*.html`, `Working Papers*.html` and `*_files/` directory
