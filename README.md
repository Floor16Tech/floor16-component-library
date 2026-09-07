# Floor 16 Component Library

Everything a client document is made of, in one place — 163 techniques across 22 families,
18 grounds, and a guided build that turns a set of choices into a finished scrolling report,
a Word mirror or a 16:9 deck.

**Live:** https://floor16tech.github.io/floor16-component-library/

## What it is

A single self-contained HTML page. Not a chart catalogue: every entry names the mechanism it
is built from, explains how that mechanism works, and says what it unlocks — what you can now
show that you could not before.

| | |
|---|---|
| Techniques | 163 |
| Families | 22 |
| Grounds | 18 |
| Typefaces | 2 (Montserrat, Aptos) |
| Dependencies | 0 |

## The three views

- **Home** — the entry point, and the "Build a document" wizard.
- **Browse** — every component in a filterable bento grid, by family and category. Each card
  renders on the white surface and flips to the Ink (dark) ground, because a component that
  only works on one of them is half finished.
- **Improve** — request a change to a component, suggest a new one, or ask for a restyle;
  pick the target visually rather than from a list of titles.

## Running it

No build step, no dependencies. Open `index.html` in a browser, or serve the folder:

```bash
python -m http.server 8000
```

Everything is plain HTML, SVG and CSS on the Floor 16 design tokens. The only network request
is the Montserrat webfont from Google Fonts.

## Structure

- `index.html` — the entire library (markup, tokens, components and app shell in one file).

---

Floor 16 · internal design system reference.
