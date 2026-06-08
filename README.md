# minsungmj.github.io

Personal research website of **Minsung Jang** — systems researcher across the full
AI-infrastructure stack (accelerator-aware runtimes, GPU-cluster training,
AI-datacenter networking, and cloud and secure systems).

Live: <https://minsungmj.github.io>

## Stack

A single, dependency-free static page: hand-authored semantic HTML + one CSS file,
no JavaScript, no build step. Served by GitHub Pages from `main` / root (`.nojekyll`).

```
index.html        page (source of truth for rendered content)
styles.css        styles (light + dark via prefers-color-scheme)
print.css         print stylesheet
data/site.json    structured content mirror (keep in sync with index.html)
assets/svg/*      original, hand-drawn system diagrams (no third-party figures)
assets/img/*      headshot (downscaled, EXIF-stripped), favicon, Open Graph card
assets/cv/*       CV PDF (added separately; referee-free, metadata-scrubbed)
404.html · robots.txt · sitemap.xml
```

## Editing

Update `index.html` (and `data/site.json` to match) for content changes. All claims
trace to the author's CV and verified public sources. The `assets/svg` diagrams are
original; do not paste figures from papers or slides.

## Code license

Site code is MIT (see `LICENSE`). Publication and patent metadata are factual.
Diagrams and the portrait are © Minsung Jang.
