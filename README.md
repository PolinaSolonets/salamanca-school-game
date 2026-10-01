# Wie gut kennst du die Schule von Salamanca? / How well do you know the School of Salamanca?

A bilingual (German/English) quiz about the School of Salamanca, linked to the
[Digital Collection of Sources](https://www.salamanca.school).

## Features

- Three levels (Einsteiger/Beginner, Fortgeschritten/Intermediate, Profi/Expert), ten questions each
- Short explanation and reading tip after every answer
- Links to the primary sources in the digital collection
- A map for each question and, at the end, the School of Salamanca as a global network
- "Share my result" button (share menu on phones, copy to clipboard on desktop)

## Publishing with GitHub Pages

1. Create a new repository and upload `index.html` (and this README).
2. Go to **Settings → Pages**, choose **Deploy from a branch**, branch `main`, folder `/ (root)`.
3. After a minute the quiz is live at `https://<username>.github.io/<repository>/`.

The quiz is a single self-contained file. It only loads the fonts from Google Fonts;
the maps are embedded (land outlines from Natural Earth via world-atlas, public domain).

## Editing questions

All questions are in the `LEVELS` object near the top of the script in `index.html`.
In every question the **first option is the correct one**; options are shuffled when displayed.
Optional fields: `src` (work ID in the digital collection and link text), `lit` (reading tip),
`more` (additional link, e.g. a blog post) and `place` (location shown on the map).
