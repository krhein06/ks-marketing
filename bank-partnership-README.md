# Konectd Bank Partnership Landing Page

## Files

- `konectd-bank-partnership-section.html` — paste this into your CMS template, page builder HTML block, or site partial.
- `konectd-bank-partnership.css` — standalone namespaced stylesheet for this section.
- `konectd-bank-partnership-preview.html` — full preview page for local testing.

## Basic integration

1. Commit `konectd-bank-partnership.css` into your site stylesheet folder.
2. Load the stylesheet in the page or template:

```html
<link rel="stylesheet" href="/assets/css/konectd-bank-partnership.css" />
```

3. Paste the contents of `konectd-bank-partnership-section.html` where the landing page content should render.
4. Update the form action:

```html
<form class="kp-bank-form" action="/bank-partnership-lead" method="post">
```

Replace `/bank-partnership-lead` with your CRM endpoint, form handler, HubSpot form embed, Webflow form action, or WordPress handler.

## Notes

- All classes are prefixed with `kp-bank-` to minimize collisions with your existing CSS.
- The form includes a hidden `source_page` field you can use for attribution.
- If your site already handles global fonts, keep this stylesheet as-is.
- If you want the buttons to use your house button styles, map `.kp-bank-btn`, `.kp-bank-btn-primary`, and `.kp-bank-btn-secondary` to your theme tokens.
