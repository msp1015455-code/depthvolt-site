# DepthVolt

Marketing site for **depthvolt.tech** — DepthVolt's bladeless subsea current turbines.

## Hosting

- Served by GitHub Pages from branch `main`, folder root.
- Custom domain is set in `CNAME` (depthvolt.tech). HTTPS is enforced in Settings → Pages.
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

## Enquiry form

The contact form posts to Formspree (form ID `mnpnqyvz`). Submissions are emailed to
**info@depthvolt.com** and stored in the Formspree dashboard. The endpoint is set in
`index.html` in the constant `FORMSPREE_ID`.

## Contact

info@depthvolt.com
