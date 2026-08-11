# The Byte Project

Landing page for byte-project.com, served by GitHub Pages.

## Files
- `index.html` — the site. Self contained: fonts, scripts and assets are all embedded.
- `CNAME` — tells GitHub Pages which custom domain to serve. Do not delete.
- `robots.txt`, `sitemap.xml` — search engine directives.

## Editing
The page is a bundled export. To change the design, edit the original artifact and
re-export, then re-apply the meta tags in the `<head>` and in the `__bundler/template`
block near the bottom of the file.

To change only the title, description or social preview text, edit both copies of
those meta tags in `index.html`. They appear twice by design: once in the outer
`<head>` for crawlers that do not run JavaScript, once inside the template block
for the rendered page.

Email capture posts to Buttondown at `thebyteproject`.
