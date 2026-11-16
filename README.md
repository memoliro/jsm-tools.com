# JSM Tools — jsm-tools.com

Free online tools that never upload your files. One page, no build step,
no server: the whole site is static HTML + CSS, served by Cloudflare Pages
from this repo.

## What's here

- `index.html` — the No-Upload Tools Hub: 22 audited tools across the JSM
  family (Image 7, Video 4, Loudness 4, Enhance in-browser 4, Options 2,
  LyricPrep 1). Only two promises are made on the page: **No Upload** and
  **No Account** — both verified per tool before listing.
- `styles.css` — shared stylesheet (same file as jsm-image.com).
- `favicon.svg`, `sitemap.xml`, `robots.txt`.

## The two rules

1. **No Upload** — every listed tool processes files in the visitor's
   browser; nothing is sent to a server. JSM Enhance's AI tools (Extend,
   Sharpen, Unblur, Remove) upload images to a server, so they are NOT
   listed — only Enhance's four in-browser tools are.
2. **No Account** — no sign-in anywhere on any listed tool.

The page deliberately does NOT claim "No Ads", "No Tracking" or "Works
Offline" — none of those holds across the family sites.

## Deploy

Cloudflare Pages project `jsm-tools` (custom domain jsm-tools.com),
Git integration on `memoliro/jsm-tools.com`, branch `main`, no build command.
