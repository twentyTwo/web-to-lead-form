# Verdek — Web-to-Lead Form

A modern, responsive Salesforce **Web-to-Lead** contact form. Submits lead data
to Salesforce and is published via GitHub Pages.

## Live site

https://twentytwo.github.io/web-to-lead-form/

## Features

- Split-screen hero layout with an emerald "Verdek" brand panel
- Floating-label inputs with focus, hover, and validation states
- Inline validation (required fields, email & phone format)
- Accessible labels, autocomplete hints, and `prefers-reduced-motion` support
- Graceful in-page success confirmation after submission
- Preserves the original Salesforce endpoint and field names exactly

## Salesforce details

| Field | Value |
| --- | --- |
| Endpoint | `https://test.salesforce.com/servlet/servlet.WebToLead` |
| Org ID (`oid`) | `00DAK000000ivoz` |
| Return URL (`retURL`) | `https://www.verdek.com/` |

> The endpoint above is the **sandbox/test** Salesforce host (`test.salesforce.com`).
> To go live, switch it to `https://webtolead.salesforce.com/...` and use a
> production org ID.

## Local preview

Just open `index.html` in a browser, or run any static server:

```bash
npx serve .
# or
python -m http.server 8000
```
