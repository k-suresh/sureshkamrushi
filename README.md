# Suresh Kamrushi — Personal Website

Static portfolio and blog published with GitHub Pages at [sforsuresh.in](https://sforsuresh.in).

## Pages

- `index.html` — Portfolio home page.
- `blog.html` — Blog listing with article summaries and publication dates.
- `preview-html-page-locally.html` — Guide to previewing a local HTML page with Python, VS Code, or Node.js.
- `host-static-html-page-godaddy.html` — Guide to hosting a static HTML page on a GoDaddy domain.
- `make-github-repo-private.html` — Guide to changing a GitHub repository from public to private.
- `github-pages-hosting-limits.html` — Guide to GitHub Pages technical, usage, and commercial limits.
- `host-images-github-blog.html` — Guide to hosting images for a GitHub blog.
- `10-rag-architectures.html` — Practical guide to ten retrieval-augmented generation architectures.
- `ai-search-blog-visibility.html` — Guide to helping search engines and AI-powered search discover a blog.
- `cqrs-design-pattern-microservices.html` — Practical guide to CQRS design and trade-offs in microservices.
- `retrieval-augmented-generation-rag-guide.html` — Practical guide to RAG architecture, retrieval, embeddings, and chunking.
- `sql-server-insert-hang-debugging-guide.html` — Guide to diagnosing SQL Server insert hangs, blocking, and batch failures.
- `enabledisable-delete-confirmation-windows-10.html` — Guide to enabling or disabling the Windows 10 delete confirmation dialog.
- `type-namespace-name-servicecontroller-not-found.html` — Guide to resolving the missing ServiceController type or namespace in C#.
- `How-to-change-IIS-port-in-windows.html` — Guide to changing a website's HTTP binding port in IIS.
- `Generating-ERD-using-PHPMyAdmin.html` — Guide to creating and exporting an ER diagram with phpMyAdmin.

The blog listing and article pages define Jekyll `permalink` values so they can be reached without `.html` extensions:

- `/blog/`
- `/preview-html-page-locally/`
- `/host-static-html-page-godaddy/`
- `/make-github-repo-private/`
- `/github-pages-hosting-limits/`
- `/host-images-github-blog/`
- `/10-rag-architectures/`
- `/ai-search-blog-visibility/`
- `/cqrs-design-pattern-microservices/`
- `/retrieval-augmented-generation-rag-guide/`
- `/sql-server-insert-hang-debugging-guide/`
- `/enabledisable-delete-confirmation-windows-10/`
- `/type-namespace-name-servicecontroller-not-found/`
- `/change-iis-port-windows/`
- `/generating-erd-using-phpmyadmin/`

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
