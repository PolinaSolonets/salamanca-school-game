# Wie gut kennst du die Schule von Salamanca? / How well do you know the School of Salamanca? / ¿Cuánto sabes de la Escuela de Salamanca?

A trilingual (German/English/Spanish) quiz about the School of Salamanca, linked to the
[Digital Collection of Sources](https://www.salamanca.school).

## Features

- Three levels (Einsteiger/Beginner, Fortgeschritten/Intermediate, Profi/Expert), ten questions each
- Short explanation and reading tip after every answer
- Links to the primary sources in the digital collection
- A map for each question and, at the end, the School of Salamanca as a global network
- "Share my result" button (share menu on phones, copy to clipboard on desktop)

## Editing questions

All questions are in the `LEVELS` object near the top of the script in `index.html` (German and English);
the Spanish versions are in the `ES` object directly below it, in the same order.
In every question the **first option is the correct one**; options are shuffled when displayed.
Optional fields: `src` (work ID in the digital collection and link text), `lit` (reading tip),
`dict` (entry in the Dictionary of the School of Salamanca), `more` (additional link,
e.g. a blog post) and `place` (location shown on the map).
