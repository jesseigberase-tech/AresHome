# ARES Industrial Corp — Business Package Demo ($599)

A static, 4-page example website built at the "Business" package tier —
a scoped-down companion to the Premium demo, so a prospect can see the
difference between the two package levels side by side.

## What's here

- `index.html` — Home (includes one static client testimonial)
- `about.html` — About
- `services.html` — Services
- `contact.html` — Contact form + Google Maps embed
- `styles.css` — Shared design system (same red/white brand as the Premium demo)
- `script.js` — Mobile nav toggle, form handling, scroll reveal, back-to-top

No build step, no dependencies, no backend.

## What's intentionally left out vs. the Premium tier

Per the Business package scope:
- No Gallery/Portfolio page
- No Blog section
- No interactive testimonial selector (just one static quote)
- No FAQ page
- Basic SEO only (meta title/description) — no JSON-LD schema markup

Business-tier features that *are* included: mobile responsive, contact
form, social links, basic SEO, Google Maps integration, and a
lightweight/fast build.

## Note on content

Company name, services, and contact info are placeholder / representative
copy — swap in real client details before this goes live.

## Deploying with GitHub Pages

1. Push this repo to GitHub.
2. Settings → Pages → Source: `Deploy from a branch`, branch `main`, folder `/ (root)`.
3. Live at `https://<username>.github.io/<repo-name>/` within a minute or two.
