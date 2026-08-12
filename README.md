# The Closer's Framework — landing page + funnel

Static site for a free sales-training masterclass, with a one-time-offer
upgrade after registration. No build step, no dependencies.

```
index.html   → registers for the free masterclass (Tally popup)
                    │ on submit
                    ▼
offer.html   → $27 VIP upgrade, one-time
                    ├── Yes  → checkout (Stripe Payment Link or similar)
                    └── No   → thanks.html
                                    │
thanks.html  → confirmation + add-to-calendar + what to do before Thursday
```

`styles.css` holds the shared design system (colors, type, buttons, cards,
FAQ accordion, badge, ledger, tickets) used by all three pages. Each page
adds only its own layout in a small inline `<style>` block.

## Two things to connect

**1. The Tally registration form** — already connected (`TALLY_FORM_ID` in
`index.html`). To point it at a different form:

1. Build your form at [tally.so](https://tally.so), copy its URL —
   `https://tally.so/r/wAbCdE`.
2. In `index.html`, set `TALLY_FORM_ID` to the part after `/r/`.
3. In the Tally dashboard, under **Form → Settings → Redirect on
   completion**, set the redirect to `offer.html` — this covers anyone who
   opens the Tally link directly instead of through the popup.

Every "Save my free seat" button opens the form as a popup and redirects to
`offer.html` on submit (`data-tally-on-submit`). None of them scroll or
navigate on their own.

**2. Checkout** — not yet connected. In `offer.html`, set `CHECKOUT_URL` to
wherever "Yes — upgrade me to VIP" should send people (a Stripe Payment
Link is the simplest option). Until it's set, clicking shows a toast
instead of dead-ending.

## Local preview

From the parent folder:

```
powershell -NoProfile -ExecutionPolicy Bypass -File serve.ps1 -Port 8129
```

Then open <http://localhost:8129/closers-framework-site/>.

## Deploying

Netlify builds from this repo root. `netlify.toml` sets the publish
directory, security headers, and no-cache on every HTML page so a deploy
is never served stale. There is no build command.

## Note on content

All names, testimonials, statistics, prices, and results on these pages
are illustrative placeholders for a design demo — not claims about any
real person, company, or product.
