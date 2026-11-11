# InvoiceHub landing

Static landing page: plain HTML, no build step. Fonts (Google Fonts) and GSAP (cdnjs) load from CDNs.

## Files

| Path | What it is |
|---|---|
| `index.html` | The landing page |
| `terms.html`, `privacy.html`, `cookies.html` | Placeholder legal pages (replace the text before launch) |
| `404.html` | Not-found page (GitHub Pages serves it automatically) |
| `assets/og-image.png` | Open Graph / social preview, 1200×630 |
| `favicon.ico`, `assets/favicon.svg`, `favicon-16.png`, `favicon-32.png` | Favicons |
| `assets/apple-touch-icon.png` | iOS home-screen icon, 180×180 |
| `assets/icon-192.png`, `icon-512.png` + `site.webmanifest` | Android / PWA icons |
| `robots.txt`, `.nojekyll` | Crawling rules; tells GitHub Pages not to run Jekyll |

## Publish on GitHub Pages

1. Create a repository and push the contents of this folder to the `main` branch (the files at the repository root, not inside a sub-folder).
2. In the repository: **Settings → Pages → Build and deployment → Source: Deploy from a branch**, branch `main`, folder `/ (root)`. Save.
3. After a minute the site is live at `https://<user>.github.io/<repo>/`.
4. Custom domain (optional): add it in **Settings → Pages → Custom domain**; GitHub creates the `CNAME` file. Point the domain's DNS to GitHub Pages and turn on **Enforce HTTPS**.

## Before launch

- **Social preview:** og:image, og:url and canonical already point to https://invoicehub-lyart.vercel.app.
- **Legal pages:** `terms.html`, `privacy.html` and `cookies.html` contain placeholder text.
- **API:** "Get API key" opens an email to support@invoicehub.com; "Read the docs" is marked Coming soon.
