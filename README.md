# Suresh Kamrushi — Personal Website

Static portfolio and blog published with GitHub Pages at [sforsuresh.in](https://sforsuresh.in).

## Pages

- `index.html` — Portfolio home page.
- `blog.html` — Blog listing with article summaries and publication dates.
- `host-static-html-page-godaddy.html` — Guide to hosting a static HTML page on a GoDaddy domain.
- `make-github-repo-private.html` — Guide to changing a GitHub repository from public to private.

The blog listing and article pages define Jekyll `permalink` values so they can be reached without `.html` extensions:

- `/blog/`
- `/host-static-html-page-godaddy/`
- `/make-github-repo-private/`

Keep the permalink front matter in place when editing these pages. Navigation links use the clean URLs.

## Site assets

- `sk.png` — PNG favicon referenced by all pages.
- `CNAME` — Custom domain configuration for GitHub Pages.
- `support.js` and `vendor/` — Runtime dependencies used by the portfolio page.

## Preview locally

From the repository root, start a local static server:

```sh
python -m http.server 8000
```

Then open `http://localhost:8000/`. The permalink routes are applied when published through GitHub Pages; a basic local static server serves the source `.html` filenames directly.

## Publish

Push changes to the GitHub Pages publishing branch. GitHub Pages will deploy the site using the repository’s configured source and process the permalink front matter. Check the Pages deployment status after pushing.
