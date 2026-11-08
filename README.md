# OC Ramps theme docs

This repository publishes the OC Ramps theme documentation at [GitHub Pages](https://nine15team.github.io/oc-ramps-guide/). Everything is in one file, `index.html` (styles and scripts included), so the docs are easy to update and publish.

The docs are behind a simple password gate. To change the password, open the page, run `cyrb53('new password')` in the browser console, and put the result in `PASSWORD_HASH` in `index.html`. The gate is intentionally light and meant to prevent casual browsing.

Competitive analysis: https://nine15team.com/brands/oc-ramps/oc-ramps-competitive-analysis.html

To add or edit a page, copy an `<article class="doc">` block, give it a unique `id` and a `data-group`. The sidebar, search, "On this page" list and previous/next links are built from those article blocks.

The theme source is `NINE15Team/OC-Ramps`. The live theme (OC-Ramps/QA) is connected to the `QA` branch. After a theme change, update the relevant page here, check links and search, then push to `main` and let the GitHub Pages site rebuild.
