# Crusader Wrestling Foundation website

This is a static website for the independent Crusader Wrestling Foundation (CWF). The homepage and inline styles are in `index.html`; `favicon.svg` uses the crest in `cwf_logo.jpg`, and `cwf_gold_out_shirt.jpg` is the fundraiser shirt preview.

## Local preview

The site has no build step or package dependencies. From this directory, start a local server with:

```powershell
python -m http.server 8000 --bind 127.0.0.1
```

Then open `http://127.0.0.1:8000/` in a browser.

## Publishing

GitHub Pages serves the repository root from the `main` branch.

## Content guardrails

- Keep CWF presented as an independent organization. Do not imply school affiliation or publish school-specific fundraising, payment, or team contact details.
- CWF is a Pennsylvania nonprofit corporation seeking IRS recognition under section 501(c)(3); do not describe tax-exempt status as approved or promise tax deductibility before an IRS determination.
- Do not publish the EIN, personal addresses, or private officer contact details without explicit approval for public use.
- Add public contact details, address or service area, domain, donation instructions, and sponsorship details only after they are confirmed and approved for public use.
