# Live Blood Cell Analysis in Oxford, MI — Landing Page

Single content page targeting the keyword **"Live Blood Cell Analysis in Oxford, MI"**, with one contextual link to `https://beingwellnhn.com/live-blood-cell-analysis-in-oxford-mi/` using the anchor text **"live blood analysis benefits"**, placed once, in the second paragraph of the article, as requested.

## Files

| File | Purpose |
|---|---|
| `index.html` | The full page: SEO meta tags, `Article` JSON-LD, 1000+ word semantically-structured article (H1 → H2/H3, ordered steps, FAQ using `<details>`), and responsive design. |
| `robots.txt` | Allows all crawlers, points to `sitemap.xml`. |
| `sitemap.xml` | Single-URL sitemap entry for the page. |
| `README.md` | This file. |

## Before you publish — replace these placeholders

The page currently uses placeholder values since no real domain/brand was provided. Update:

1. **Domain** — replace `https://www.oxfordwellnessdigest.com/` in:
   - `index.html` (`<link rel="canonical">`, JSON-LD `mainEntityOfPage`)
   - `robots.txt` (`Sitemap:` line)
   - `sitemap.xml` (`<loc>`)
2. **Site name** — "Oxford Wellness Digest" appears in the header, footer, and JSON-LD `author`/`publisher`. Swap for your actual site/brand name.
3. **Images** — hero and in-article images currently use `picsum.photos` placeholder images (free-to-use placeholder service, safe for a live site) so the design isn't blocked on real photography. Swap the `src` values for your own licensed photos before launch.
4. **Publish date** — `datePublished` in the JSON-LD is set to today; update at publish time.

## Design notes

- Palette: deep teal (`#1B4B43`) + amber (`#C8963E`) on a cool off-white background — a clinical-but-warm feel distinct from the target site's own branding, since this page is a separate content piece linking out to it.
- Type: Fraunces (display serif) + Inter (body) + IBM Plex Mono (labels/data), loaded from Google Fonts.
- No JavaScript required — the FAQ uses native `<details>/<summary>`, and the hero cell motif is a lightweight animated inline SVG (respects `prefers-reduced-motion`).
- Fully responsive; sticky reference sidebar collapses to a single column on mobile.

## Link placement (per your instructions)

The `beingwellnhn.com` link appears **exactly once**, wrapped around the anchor text "live blood analysis benefits," inside the second `<p>` of the article. No other links to that domain exist anywhere else on the page.
