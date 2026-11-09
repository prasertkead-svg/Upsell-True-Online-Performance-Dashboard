# Upsell True Online Performance Dashboard

Single-page dashboard (`index.html`) that reads an encrypted dataset (`data.json`).
Data is AES-GCM encrypted in the browser; passcodes are not stored in this repo.

Tabs: Over All · By Area · By Shop · By Staff · Campaign · Insight · (Admin, owner only).
Views: month selector, Revenue / QTY toggle, export to Excel/CSV.

Serve locally: `python3 -m http.server` then open http://localhost:8000
Hosting: enable GitHub Pages (Settings → Pages → main / root).
