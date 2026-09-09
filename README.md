# Beatriz Vizcaino — Portfolio

A single-page portfolio site built with plain HTML, CSS, and JavaScript — no build step, no framework, no dependencies beyond a Google Fonts stylesheet.

## Structure

```
.
├── index.html      # the entire site: markup, styles, and behavior
├── images/         # project screenshots and hero background, referenced by index.html
└── README.md
```

## Running locally

No build step is required. Either:

- Open `index.html` directly in a browser, or
- Serve the folder locally, e.g. `python3 -m http.server` from this directory, then visit `http://localhost:8000`

## Deploying with GitHub Pages

1. Push this folder to a GitHub repository.
2. In the repo settings, under **Pages**, set the source to the `main` branch (root).
3. GitHub will publish `index.html` at `https://<username>.github.io/<repo>/`.

## Notes

- All project images live in `images/` and are referenced with relative paths — keep that folder alongside `index.html` if you move or rename anything.
- The hero headline's rotating word, the "Say Hi" cursor behavior, and the entrance animations are all handled by vanilla JavaScript at the bottom of `index.html`.
- Contact links point to `beatryev@gmail.com`.
