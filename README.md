# sainmore.com

Static website for **sAInmore** (super AI & more), served by GitHub Pages.

- Plain HTML + CSS, no JavaScript, no cookies, no external requests.
- `index.html`: home page. `privacy.html`: privacy notice (site + app).
- Facts on the pages must match the app's published release notes (`RELEASE-<version>.md` in the app project). The facts used are listed in a comment at the top of `index.html`.
- Fonts: Atkinson Hyperlegible Next and Audiowide, both under the SIL Open Font License (`fonts/OFL-*.txt`).
- `CNAME` holds the custom domain. `.nojekyll` tells GitHub Pages to serve the files as they are.
- `_from-app/` is where the app chat drops screenshots; it and `LAUNCH.md` (launch checklist) are in `.gitignore`, so they are never published.
- `404.html`, `robots.txt` and `sitemap.xml` are standard GitHub Pages extras.

Preview locally: open `index.html` in a browser, or run `python -m http.server` in this folder and visit http://localhost:8000.
