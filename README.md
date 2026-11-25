# Website

https://numerius-engineering-llc.github.io/web/

A Jekyll site for GitHub Pages.

## Web apps

Each web app is hosted on its own GitHub Pages site, built and deployed by a workflow in the app's own
repository (`.github/workflows/pages.yml`), so the hosted copy always matches the latest commit. The
Web App Portfolio page (`apps.md`) links straight to those sites, for example
`https://jwkunz.github.io/<repo>/`.

To add an app: add a Pages workflow to its repository, enable **Settings > Pages > Source: GitHub
Actions**, and add a tile to `apps.md`.

The files in `apps/` are small redirect pages from the old addresses. `gravitated.html` and
`rf_ranger.html` are the exceptions: those two repositories are private, which GitHub Pages does not
support on this plan, so full copies are kept here.
