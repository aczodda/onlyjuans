# OnlyJuans

Funny bilingual **coming soon** page for a parody job board for “Juans” — regular Latino-coded guys with regular jobs (landscaping, HVAC, warehouse, construction, delivery, food service).

**Not adult content.** Dark, self-deprecating, meme-y, PG-13. Tagline energy: *Subscribe to the grind* / *Suscríbete al jale* / *Real Juans. Real jobs.* / *Not that site. The job one.*

Domain context: **theonlyjuans.com**

## Open locally

1. Open the folder `/workspace/onlyjuans/` (or wherever you cloned/copied this).
2. Double-click `index.html`, **or** from a terminal:

```bash
# macOS
open index.html

# Linux
xdg-open index.html

# Or serve statically (any of these)
python3 -m http.server 8080
# then visit http://localhost:8080
```

No build step. No npm. One self-contained HTML file (inline CSS + JS for EN/ES toggle and waitlist toast).

## What’s in the box

| File         | Purpose                                      |
|--------------|----------------------------------------------|
| `index.html` | Coming soon page (hero, waitlist, EN/ES, footer)|
| `README.md`  | This file                                    |
| `netlify.toml` | Static publish + basic headers             |

## Host later

Drop `index.html` on any static host:

- **Netlify / Vercel / Cloudflare Pages** — drag-and-drop the folder or connect a repo; set publish directory to the folder containing `index.html`.
- **GitHub Pages** — push the folder and enable Pages on `main` / root (or `/docs`).
- **Any VPS / S3 / nginx** — serve `index.html` as the site root for `theonlyjuans.com`.

Point DNS for `theonlyjuans.com` at your host. Mailto CTAs use `hello@theonlyjuans.com` — set up that inbox (or change the addresses) when you’re live. The waitlist form is front-end only (toast, no backend).

## Brand rules (keep these)

- Do **not** copy OnlyFans logos, wordmarks, fonts, exact SVG marks, or trademarked assets.
- Visual system evokes that *palette feel* only: near-black backgrounds, sky-cyan accents (~`#00b4e6` / `#00AFF0` family), white type. Original wordmark (cyan “Only” + white “Juans” + a simple “J” tile — not their mark).
- Keep the job-board framing obvious so nobody mistakes it for adult content. “Subscribe” is the joke; the product is hourly gigs.
- Footer disclaimer stays: *Not affiliated with any adult platform. Just jobs for Juans.*

## Joke in one line

OnlyFans energy, but the “subscription” is an hourly landscaping / HVAC / warehouse paycheck for guys named Juan.
