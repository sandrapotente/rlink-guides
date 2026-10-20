# rlink-guides

Static R-Link guides and process boards, served at https://guide.r-link.com.

- Each guide is its own folder with an `index.html` → `guide.r-link.com/<folder-name>`.
- No build step. Every push to `main` deploys on Vercel.
- The root page is intentionally blank, and nothing lists the guides.
- `vercel.json` sends `X-Robots-Tag: noindex, nofollow` on every response; `robots.txt` disallows all crawlers.
