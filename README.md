# Scrubin Detailing — website

Single-page site for Scrubin Detailing. Mobile auto, marine and offroad detailing
serving Temecula, Murrieta, Menifee and French Valley, CA. (951) 391-3669

## Files

| File | What it is |
|---|---|
| `index.html` | The entire site — HTML, CSS and JS all in one file |
| `assets/` | Logo, favicons, hero images (WebP with JPEG fallbacks) |
| `netlify.toml` | Netlify caching and security headers |
| `robots.txt` / `sitemap.xml` | Search engine basics |

No build step, no dependencies. Edit `index.html`, commit, and Netlify redeploys automatically.

## Common edits

- **Prices** — search `class="prices"` in `index.html`. Update the same numbers in the
  JSON-LD block near the bottom so search engines stay in sync.
- **Phone number** — appears as `+19513913669` (links) and `(951) 391-3669` (display).
- **Quote form** — the `action` on `<form class="q">` needs a form endpoint. See SETUP.md.
