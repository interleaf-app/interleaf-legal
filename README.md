# Interleaf · 读迹

Official product, privacy and support pages for the Interleaf reading journal.

- [Home](https://interleaf-app.github.io/interleaf-legal/)
- [Privacy policy](https://interleaf-app.github.io/interleaf-legal/privacy/)
- [Support](https://interleaf-app.github.io/interleaf-legal/support/)
- [English](https://interleaf-app.github.io/interleaf-legal/en/)

## Maintenance

Plain static HTML and CSS; no package manager or build step. Edit the Chinese and English pages together. Screenshots use sample data. The app is available on the App Store: https://apps.apple.com/app/id6832427117. The homepage labels screenshots from the 1.2.2 development build as previews, since the current store version may differ.

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

## Product refresh · 2026-11-13

- Refreshed Chinese and English homepages with actual light-mode captures from the app repository’s `codex/1.2.2` checkout (`c05d348` plus the local build-number change to build 13). These are runtime screenshots, not design prototypes.
- Seven screens per language: Today, Shelf, reading form, note editor, text-scanning review, monthly Stats and yearly Stats. Display assets are JPEGs in `assets/screens/`, sized 804 × 1748, approximately 2.3 MB in total. The full-resolution PNG originals stay in the app’s ignored `screenshots/website-1.2.2/` folder. Older image assets are kept for historical compatibility but no longer referenced by the homepages.
- Preserved simulator library contents. Used existing sample books, temporary seeded reading drafts and the built-in OCR demonstration; no real camera capture, saved new entries, database reset or app uninstall. The language-specific UI is real; existing sample book titles remain Chinese in both languages.
- Updated support and privacy facts for formatted notes, local OCR, attachments and `.dujibackup` packages, including old JSON import compatibility. No analytics, third-party scripts, forms, remote fonts or new network services were added.
- Website changes are independent of the app’s frozen review branch and do not change App Store release status.
