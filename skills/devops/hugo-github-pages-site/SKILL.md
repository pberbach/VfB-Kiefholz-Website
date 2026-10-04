---
name: hugo-github-pages-site
description: Hugo static site with multi-language (German/English) and GitHub Pages deployment for club websites.
⚠️ German is valid language for legal matters. English full translation secondary.

## Steps
1. `hugo new site dir` 2. Configure `hugo.toml` 3. Create `content/de/` + `content/en/` 4. `hugo --buildDrafts` 5. `git push origin main` 6. Enable GitHub Pages

## Pitfalls
1. Hugo may only detect 4 pages - ensure layouts exist
2. Pages build takes 1-3 min
3. German always wins for legal
4. Volleyball links to kiefholz.net
5. Basketball/Cricket are intro pages only
6. Takeactive static only
7. Add Berlin gym law note everywhere

## Enables
- Multi-language club websites
- GitHub Pages deployment
- Legal compliance (DSGVO/Impressum)
- Brand colors #FF6B35 + #0033A0