# valenx-members

Static member pages for Valenx Press, served by GitHub Pages. Pages carry `noindex` and are not in any sitemap.

- Interview Pass member page: `pass/<slug>/index.html`
- Weekly drop content: edit `pass/<slug>/drops.json` (current drop with daily links, next drop, released drops, billing portal link). The page reads it on load. New drop every Monday; update the static Week block in index.html too so it shows without JavaScript.
