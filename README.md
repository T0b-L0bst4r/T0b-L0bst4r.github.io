# Folio

Built with [Swebsy](https://studio.swebsy.com/create?template=folio&ref=export). This folder is a **build
output** — a complete, self-contained static site you can upload to any host.

## Run it

Open `index.html` in a browser, or upload the whole folder to any static
host (Netlify, Cloudflare Pages, GitHub Pages, or plain FTP to a web root).
No build step, no dependencies, no server required.

```
index.html              your home page
<page>.html             one file per page
css/styles.<hash>.css   every style, in one file
js/                     scripts, only when a page needs them
assets/  fonts/         images and fonts
sitemap.xml robots.txt  search engine files
```

The `<hash>` in file names changes whenever the contents change, so browsers
never serve a stale copy. It is regenerated on every export.

## Editing

To keep an editable copy, use **Project → Export Project** in Swebsy (a
`.swebsy` backup file). This folder can't be opened in Swebsy again.

To change the design, change it in Swebsy and export again. Changes made to
these files **can never return to the editor**, and the next export replaces
the whole folder.

Start a new site from this template:

  https://studio.swebsy.com/create?template=folio&ref=export
