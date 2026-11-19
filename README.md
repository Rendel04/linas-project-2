# Linas Project 2 — Kabankalan Catholic College Landing Page

A responsive, single-page landing page for Kabankalan Catholic College, Inc. It uses KCC-specific content and official campus imagery in a custom editorial layout that differs from the centered dark hero on the source site.

## Project structure

- `linas-project-2/index.html` contains the page content and section structure.
- `linas-project-2/assets/css/main.css` contains the KCC visual system and responsive overrides.
- `linas-project-2/assets/js/main.js` provides the mobile navigation, current year, and reduced-motion-aware section reveals.
- `linas-project-2/assets/vendor/bootstrap.min.css` bundles Bootstrap 5.3.8 locally; its MIT license is beside it.
- `linas-project-2/assets/img/` contains the KCC seal and official campus/student photographs.
- `linas-project-2/manus-routes.json` declares the landing-page route.
- `.github/workflows/pages.yml` uploads `linas-project-2/` and deploys it with GitHub Pages.

The supplied assignment names a Bootstrap landing-page template, but its template source files were not present in the repository snapshot. This implementation uses locally bundled Bootstrap 5.3.8 as its responsive foundation and an original KCC-specific layout.

## Run locally

From the repository root:

```sh
python3 -m http.server 3000 --bind 0.0.0.0 --directory linas-project-2
```

Then open `http://localhost:3000/`.

## GitHub Pages

The repository workflow publishes the contents of `linas-project-2/` whenever `main` is updated. Set the repository's Pages source to **GitHub Actions** in **Settings → Pages**. Internal asset paths are relative, so the page also works at the repository's Pages subpath.

## Content and image sources

Institutional identity, mission, founding year, program categories, enrollment destination, address, phone, email, and KCC seal are adapted from [Kabankalan Catholic College, Inc.](https://kcc.edu.ph/). Campus and student photographs are official KCC campus-life imagery. The landing page is an independent project and is not an official replacement for the college website.
