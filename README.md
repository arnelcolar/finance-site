# Finance Site

A four-page consumer finance comparison hub: credit cards, bank accounts,
insurance and retirement. Static HTML with Tailwind from a CDN, no build step.

- `index.html` — the hub
- `best-banks.html`, `best-cards.html` — comparison tables
- `retirement.html` — longevity and distribution schedules
- `REPORT.md` — the accessibility pass: contrast pairs measured, headings,
  labels, table scopes, skip link

## Known issue

All 56 photographs point at `lh3.googleusercontent.com/aida/...` URLs that now
return 403. They were generated through Google's image service and are no
longer served, so the pages render with empty image frames until they are
replaced.
