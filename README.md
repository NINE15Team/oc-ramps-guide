# QA theme guide

Open `index.html` locally. The guide is a static site with no build step and no secrets.

The guide is committed on the private theme repository’s `QA` branch at `docs/qa-guide/`. An isolated `gh-pages` branch containing only this guide has also been pushed. GitHub rejected enabling Pages on the private repository because its current plan does not support Pages for private repositories (HTTP 422).

To publish without exposing the full private theme repository, create an approved public documentation repository (or upgrade the private repository’s Pages eligibility), then push only the guide files and enable Pages. Do not use `QA` branch `/docs` as a Pages source: that directory also contains internal audit files.

Before release, the store owner should verify Admin-only values: live/QA theme IDs, app owners, payment configuration, DNS/registrar, staff roles, backup app, and technical escalation contacts. Keep that record private.
