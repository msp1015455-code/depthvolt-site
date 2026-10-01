# DepthVolt

Marketing site for **depthvolt.com** — DepthVolt's bladeless subsea current turbines.

## Hosting

- Served by GitHub Pages from branch `main`, folder root.
- Custom domain is set in `CNAME` (depthvolt.com). HTTPS is enforced in Settings → Pages.
- DNS is managed at Netim: four A records to GitHub Pages, plus a CNAME for `www`.

## Files

| File | Purpose |
|---|---|
| `index.html` | The entire site: markup, styles and scripts in one file. |
| `CNAME` | Custom domain used by GitHub Pages. |
| `README.md` | This file. |

## Updating the site

1. Edit `index.html`.
2. Upload it here (**Add file → Upload files**) and commit to `main`.
3. GitHub Pages redeploys automatically, usually within a minute.

## Figures

Generation figures are published in two forms: a theoretical maximum (8.76 GWh per MW
per year, continuous operation) and an indicative net figure at ~90% availability
(~7.8 GWh per MW per year). Both are listed under "Basis of figures" in the Scale
section. Any change to the ratings must be reflected in both places.

## Enquiry form

The contact form posts to Formspree (form ID `mnpnqyvz`). Submissions are emailed to
**info@depthvolt.com** and stored in the Formspree dashboard. The endpoint is set in
`index.html` in the constant `FORMSPREE_ID`.

## Contact

info@depthvolt.com
