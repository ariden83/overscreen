# OverScreen — public pages

This repository holds the public web pages of **OverScreen**, an Android app by **ariden** that records your taps and swipes and replays them, on demand or when a chosen area of the screen appears.

The pages are published with GitHub Pages at <https://ariden83.github.io/overscreen/>. The app's source code lives in a separate, private repository.

## Pages

Every page exists in English and in French, and each one links to all the others and to its translation.

| Page | English | French |
|---|---|---|
| Privacy policy | [`/`](https://ariden83.github.io/overscreen/) (`index.md`) | [`fr.html`](https://ariden83.github.io/overscreen/fr.html) (`fr.md`) |
| Terms of use | [`terms.html`](https://ariden83.github.io/overscreen/terms.html) | [`terms-fr.html`](https://ariden83.github.io/overscreen/terms-fr.html) |
| FAQ | [`faq.html`](https://ariden83.github.io/overscreen/faq.html) | [`faq-fr.html`](https://ariden83.github.io/overscreen/faq-fr.html) |
| Legal notice | [`legal.html`](https://ariden83.github.io/overscreen/legal.html) | [`legal-fr.html`](https://ariden83.github.io/overscreen/legal-fr.html) |

## Addresses in use: do not move them

These addresses are used outside this repository, so the files must keep their names; renaming this repository changes them all, because GitHub Pages does not redirect a renamed repository:

- the **privacy policy** (`/` and `fr.html`) is the privacy policy URL of the Google Play listing, and the app opens it from its consent screen;
- the **FAQ** and the **terms of use** are opened from the guide of the app;
- the Play Store listing links to the privacy policy, the terms of use and the FAQ.

## Ready-made configs

`configs/` holds one backup file per app (`<package name>.json`), in the format of the export of OverScreen. To use one, download it and import it from the app: the import adds or replaces the items of that file only and leaves the configs of your other apps untouched. Note that the import also applies the "pause when leaving the app" setting stored in the file.

## Editing a page

1. Edit the Markdown file. Pages are plain Markdown with a short front matter (`title:`); the [Primer](https://github.com/pages-themes/primer) theme set in `_config.yml` does the layout.
2. Apply the same change to the other language, so both versions always say the same thing.
3. When the privacy policy or the terms of use change in substance, update their **effective date**, in both languages.
4. Commit and push to `main`: GitHub Pages rebuilds the site within a minute or two.

To preview locally (optional): `bundle exec jekyll serve` with the `github-pages` gem, or simply open the Markdown on GitHub.

## Keeping the pages true

These pages describe what the app actually does. When the app changes in a way they mention, update them in the same move. In particular:

- **no Internet permission and no data collected**: if the app ever gets network access, analytics or ads, the privacy policy must be updated before that version is published;
- **OverScreen Pro**: the purchase is not available yet; the FAQ and the store listing say so, and must be updated when it is switched on;
- **legal notice**: the publisher is currently an anonymous non-professional individual; once OverScreen Pro is sold, the publisher becomes a professional and the legal notice must give their real identity.

## Contact

**ariden.apps@gmail.com**

Copyright (c) 2026 ariden. All rights reserved.
