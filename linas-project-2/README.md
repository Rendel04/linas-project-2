# Linas Project 2 — Kabankalan Catholic College Landing Page

A KCC-specific single-page landing page based on the free **Mentor** Bootstrap education template. The page keeps the Mentor asset organization, local Bootstrap/vendor files, stylesheet, script, and responsive component foundations, then adapts the content and visual treatment for Kabankalan Catholic College, Inc. The hero, editorial sections, color palette, imagery, and calls to action are original to this KCC landing page and differ from the official KCC homepage.

## Folder map

- `index.html` — customized, accessible one-page site and Bootstrap grid structure.
- `assets/css/main.css` — the Mentor stylesheet followed by KCC brand and responsive overrides.
- `assets/js/main.js` — Mentor navigation, animation, and scroll behavior.
- `assets/js/kcc.js` — KCC-specific navigation accessibility state and current-year text.
- `assets/vendor/` — local Bootstrap 5, Bootstrap Icons, AOS, GLightbox, PureCounter, and Swiper assets from the Mentor archive.
- `assets/img/` — official KCC seal and campus/student imagery.
- `manus-routes.json` — declaration for the single-page route.

## Local preview

From the repository root:

```sh
python3 -m http.server 3000 --bind 0.0.0.0 --directory linas-project-2
```

Open `http://localhost:3000/`.

## GitHub Pages

The repository-root workflow in `.github/workflows/pages.yml` publishes the contents of this folder. Set **Settings → Pages → Build and deployment → Source** to **GitHub Actions**. The page uses relative paths and the local vendor assets so it works at the repository's Pages subpath without a package build step.

## Content and attribution

Institutional details, the mission, founding year, education levels, campus-life references, address, phone, email, and KCC seal are adapted from [the official KCC website](https://kcc.edu.ph/#hom). Campus and student photos are official KCC imagery. Enrollment links point to [the KCC enrollment portal](https://kcc.wela.ph).

The base page, stylesheet, and script are from [Mentor by BootstrapMade](https://bootstrapmade.com/mentor-free-education-bootstrap-theme/). The required free-license credit is retained in the site footer: **Designed by BootstrapMade**. See the [BootstrapMade license](https://bootstrapmade.com/license/).
