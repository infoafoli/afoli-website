# afoli.org

Static website for the Asian Family Office Leadership Institute (AFOLI).

## Files
- `index.html` – single-page site (Mission, Our Work, Board, Get Involved, Contact)
- `styles.css` – dark blue + beige palette (tokens at the top of the file)
- `favicon.svg` – placeholder "A" monogram; swap for the final AFOLI logo
- `robots.txt`, `sitemap.xml` – SEO basics

## Before launch
- Jonathan to review all copy (mission text and focus areas are a first draft)
- Confirm board titles (currently all "Director") and whether to add bios/photos
- Match exact hex colors to Sophia's pin design if they differ
- Replace favicon with the final logo

## Deploy
Option A – Network Solutions hosting: upload all files to the web root (`htdocs`/`public_html`) via the hosting File Manager or SFTP.
Option B – GitHub Pages: repo Settings → Pages → deploy from `main`, add custom domain `www.afoli.org`, then in Network Solutions DNS add a CNAME `www` → `<username>.github.io` and A records for `@` → 185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153.
