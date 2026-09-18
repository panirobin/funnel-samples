# Funnel samples

Static landing-page funnels, one folder per prospect. Each is a cold-outreach sample —
a spec build used as the pitch piece itself. No build step, no dependencies.

## Pattern (every sample folder)

```
index.html    → hub: deliverable cards + Cal.com booking embed
                     │
                     ▼
landing.html  → funnel entry; registration via a Netlify Forms modal
                     │
                     ▼
offer.html    → one-time upgrade
                     ├── Yes → checkout (Stripe Payment Link or similar)
                     └── No  → thanks.html
thanks.html   → confirmation + add-to-calendar
```

Alongside those: `icp.html` (ideal-customer-profile research), `ads.html` (ad scripts),
and `research.md` (prospect notes, not linked publicly).

`styles.css` holds the shared design system — colors, type, buttons, cards, FAQ
accordion, badges, tickets. Each page adds only its own layout in a small inline
`<style>` block.

## Site root

`index.html` at the root is deliberately blank and `noindex`. There is no list of
samples, so a prospect who trims the URL back to the domain can't see who else received
one — each sample is only reachable through its own `/slug/` link.

Samples that predated this pattern (the Tally-based `northsight/` and the original root
funnel) were removed; they remain in git history.

## What to connect

**Registration** — Netlify Forms. The form must be present in the deployed static HTML
(not injected by JS), and form detection has to be enabled for the site under
**Site configuration → Forms**.

**Checkout** — set `CHECKOUT_URL` in `offer.html` to wherever the upgrade button should
send people. Until it's set, clicking shows a toast instead of dead-ending.

## Local preview

From the parent folder:

```
powershell -NoProfile -ExecutionPolicy Bypass -File serve.ps1 -Port 8129
```

Then open <http://localhost:8129/funnel-samples/noldin/>.

## Deploying

Netlify builds from this repo root. `netlify.toml` sets the publish directory, security
headers, and no-cache on every HTML page so a deploy is never served stale. There is no
build command.

## Note on content

Names, testimonials, statistics, prices, and results on these pages are illustrative
placeholders for a design demo — not claims about any real person, company, or product.
