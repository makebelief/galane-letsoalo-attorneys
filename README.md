# Galane Letsoalo Attorneys — Wakili wa Tech concept website

Nine-page static website. Built using our established premium law-firm layout language (utility bar, sticky header, full-width photographic hero, clear call-to-action, portrait/profile, practice grids, mobile menu, email draft enquiry and floating WhatsApp contact).

## Preview locally

```bash
cd galane-letsoalo-attorneys
python3 -m http.server 8000
```

Open http://localhost:8000

## Deploy

Push to a PRIVATE GitHub repo then run `npx vercel --yes` for preview. Public indexing is disabled. Only publish as official with the firm's approval.

## QA

- All content photographs must have unique source references site-wide. Branding in header/footer and OG preview can repeat.
- Confirm mobile layout, external Pexels availability, current office address, WhatsApp and live OG preview after deployment.
- Form composes email using mailto; no backend server, no silent send.
