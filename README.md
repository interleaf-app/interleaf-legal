# Interleaf · 读迹

Official product, privacy and support pages for the Interleaf reading journal.

- [Home](https://interleaf-app.github.io/interleaf-legal/)
- [Privacy policy](https://interleaf-app.github.io/interleaf-legal/privacy/)
- [Support](https://interleaf-app.github.io/interleaf-legal/support/)
- [English](https://interleaf-app.github.io/interleaf-legal/en/)

## Maintenance

Plain static HTML and CSS; no package manager or build step. Edit the Chinese and English pages together. Screenshots use sample data. The app is preparing for release; add an App Store link only after its listing is available.

Preview: `python3 -m http.server 8080` from this directory.

GitHub Pages publishes the `main` branch from `/` with `.nojekyll`. Relative links support the project URL above. No analytics, external fonts or scripts. Local fonts retain their OFL license files in `assets/fonts/`.

Contact: krystal.11381@outlook.com

## Brand assets

- Product name: **读迹 / Interleaf**. Marginalia is the app’s internal project name.
- `assets/app-icon.png`: 180 × 180 default **Natural White / 自然白** icon, exported from the app’s Icon Composer document. The neutral white background and three books match the current default app icon.
- Source: `designs/app-icons/previews/natural-white-default.png` in [the app repository](https://github.com/summer-521/Marginalia), generated from `Resources/AppIcon.icon`. Copy the current export and resize it to 180 × 180 when refreshing this asset.
- All six Chinese and English content pages use the same asset for the header, favicon and Apple touch icon; the 404 page also uses it for both browser icons. Update the icon query version on every page when replacing it so returning visitors receive the new icon.

## Icon refresh · 2026-11-11

Updated the default Natural White icon and the icon cache version on all seven HTML pages. Product screenshots are deliberately unchanged; refresh those after version 1.2.0 is live on the App Store.
