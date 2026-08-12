# The Closer's Framework — landing page

Single-file static landing page for a free sales-training masterclass.
No build step, no dependencies. `index.html` is the entire site.

## Connecting the Tally registration form

The form is wired up but not yet pointed at a real Tally form.

1. Build your form at [tally.so](https://tally.so).
2. Copy its URL — it looks like `https://tally.so/r/wAbCdE`.
3. Open `index.html`, find `TALLY_FORM_ID` near the bottom, and replace
   `"REPLACE_ME"` with the part after `/r/` (here, `wAbCdE`).
4. Commit and push — Netlify redeploys automatically.

Until that value is set, the registration section shows a placeholder
instead of the form. Every "Save my free seat" button on the page links to
`#register`, so they all scroll to the form once it is connected.

## Local preview

From the parent folder:

```
powershell -NoProfile -ExecutionPolicy Bypass -File serve.ps1 -Port 8129
```

Then open <http://localhost:8129/closers-framework-site/>.

## Deploying

Netlify builds from this repo root. `netlify.toml` sets the publish
directory and security headers; there is no build command.

## Note on content

All names, testimonials, statistics, and results on the page are
illustrative placeholders for a design demo — not claims about any real
person, company, or product.
