# Badge Press Studio

A single-page tool for making round pin-badge prints. Design badges (place, scale and rotate images over the cut line, fold zone and visible face), then lay out copies on A4 or US Letter and download or print a PDF at true millimetre scale.

**Live:** https://oldstarchy.github.io/badge-press-studio/

- Defaults: 44 mm cut circle, 32 mm visible face, 1.5 mm visible fold. All configurable.
- Everything runs in the browser. Designs are saved in that browser's local storage (IndexedDB); nothing is uploaded.
- Print the PDF at 100% / Actual size, not "Fit to page". Check the 50 mm scale bar.

The whole app is `index.html`. Pushing to `main` deploys it to GitHub Pages via `.github/workflows/pages.yml`.
