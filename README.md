# Personal webpage

A static, single-page personal academic homepage: About, Research, Publications,
Teaching, CV, and Contact. Content is drawn from the CV, research statement,
research plan, and teaching concept under `bonn/`, generalized so nothing here
is tied to any specific job application (no institution names, excellence
clusters, or named external collaborators tied to a specific opportunity).

## Files

- `index.html` — all page content and structure
- `styles.css` — theming (light/dark, both via `prefers-color-scheme` and a
  manual toggle) and layout
- `script.js` — mobile nav toggle and the dark/light mode toggle
  (persisted in `localStorage`)

## Updating

Edit `index.html` directly — there's no build step. Open the file in a browser
to preview.

The Publications section links out to live searches/profile:
- ADS: search on surname "Forero-Romero", refereed only
- arXiv: author search on surname "Forero-Romero"
- Google Scholar: direct profile link

Bibliometric figures (citation counts, h-index) are a snapshot from the CV;
refresh them from ADS/Scholar periodically.

## Deploying

Any static host works (GitHub Pages, Netlify, a plain web server) — just
serve this folder's contents.
