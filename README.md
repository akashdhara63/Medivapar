# ASR Technologies Website

Static website (HTML, CSS, JavaScript). No build step or server code needed.

## Structure
- `index.html` - the page
- `css/style.css` - styling (light/dark mode)
- `js/config.js` - **set DOWNLOAD_URL here**
- `js/main.js` - menu, free-trial form (WhatsApp), registration + download flow
- `downloads/` - optional place for the installer

## Run locally
Double-click `index.html`.

## Put it online
Upload the whole folder to any static host: Netlify (drag and drop), GitHub Pages, Cloudflare Pages, Vercel, or normal cPanel hosting (`public_html`).

## Things to know
- Contact number: search `9341858573` / `919341858573` in `index.html` and `js/main.js` to change it.
- Registrations are saved only in the visitor's own browser. To collect them yourself, a backend or form service (e.g. Formspree, Google Sheets) is needed.
