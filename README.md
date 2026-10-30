# Moon Reader Website

The static website for [Moon Reader](https://github.com/Moon-Ecosystem/MoonReader), an offline Android reader for your own manga and comic archives. Plain HTML, CSS and JavaScript, served by GitHub Pages at https://moon-ecosystem.github.io/Moon-Reader-Website/.

## Preview locally

No build step or package installation is needed. Open `index.html` in a browser, or run a static server from this folder:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`. The site loads Google Fonts when online and falls back to system fonts otherwise.

## Deploying

GitHub Pages deploys the default branch from the repository root, so a push to the default branch updates the live site.

## Keeping it accurate

- Feature claims follow the app's [README](https://github.com/Moon-Ecosystem/MoonReader#readme). Update them when a release adds or changes a feature.
- Download links point to `releases/latest`, so they always offer the newest release without edits.
- Screenshots live in `assets/screenshots/`. Retake them when the app's look changes.

## Structure

```text
├── index.html
├── styles.css
├── script.js
├── README.md
└── assets/
    ├── moon-reader.png
    └── screenshots/
```

The site doesn't host manga files or offer downloads of copyrighted material.
