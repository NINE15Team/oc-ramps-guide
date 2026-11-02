# OC Ramps theme docs

This repository publishes the OC Ramps theme documentation at [GitHub Pages](https://nine15team.github.io/oc-ramps-guide/). Everything is in one file, `index.html` (styles and scripts included), so there is no build step. Open it locally to preview it.

The docs are behind a simple password gate. To change the password, open the page, run `cyrb53('new password')` in the browser console, and put the result in `PASSWORD_HASH` in `index.html`. The gate keeps casual visitors out; it is not real security, so never put credentials, keys or private account details in this repository.

To add or edit a page, copy an `<article class="doc">` block, give it a unique `id` and a `data-group`. The sidebar, search, "On this page" list and previous/next links are built from those articles automatically.

The theme source is `NINE15Team/OC-Ramps`. The live theme (OC-Ramps/QA) is connected to the `QA` branch. After a theme change, update the relevant page here, check links and search, then push to `main`. GitHub Pages publishes from `main` at the repository root.
