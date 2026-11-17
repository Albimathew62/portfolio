# Albi Mathews — Portfolio

Static site: no build step, no dependencies.

```
index.html            the whole page (HTML + CSS + a tiny clock script)
assets/
  albi-portrait.jpg   hero photo (orange glasses)
  albi-wide.jpg       full-width colour portrait
  albi-bw.jpg         small avatar in the quote + footer
  favicon.svg
  Albi_Mathews_Resume.pdf
```

## Preview locally
Open `index.html` in a browser, or run `python -m http.server` in this folder and visit http://localhost:8000.

## Deploy
Copy everything in this folder to the root of your site repo (e.g. the repo behind albimathew.online), commit and push.

## Quick edits
- Accent colour: search-and-replace `#C8FF2E` in `index.html`.
- Archive years: search for `[YEAR]`.
