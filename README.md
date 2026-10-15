# MangaReader Website

A responsive, static promotional website for the MangaReader Android app. Built with plain HTML, CSS, and JavaScript so it can be tested locally and deployed using GitHub Pages.

## Preview locally

No build step or package installation is required.

1. Download and extract this folder.
2. Open `index.html` in a browser, or run a local static server from this directory:

   ```bash
   python -m http.server 8000
   ```

3. Visit `http://localhost:8000`.

The site uses Google Fonts when internet access is available; system fallbacks are defined.

## Before publishing

Search the project for placeholder content and replace it:

- `Developer One`, `Developer Two`, `Developer Three`
- `DEVELOPER / ROLE` and each short team bio
- Placeholder GitHub profile URLs and `hello@example.com`
- Add a real app download/release link when one exists.
- Add a privacy policy page/link that accurately describes the app's data practices.
- Verify all feature claims against the current Android app and README before public launch.
- Update repository links if the repository URL changes.

The current repository links point to `https://github.com/Varun-666/MangaReader`.

## Deploy on GitHub Pages

### Option A: Same repository as the Android app

1. Create a folder such as `website/` in the root of the Android repository.
2. Copy the website files into that folder.
3. In GitHub, open **Settings → Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**.
5. Select the default branch and the `/docs` folder, or move/copy the website contents to `/docs`.
6. Save and wait for the Pages deployment to finish.

GitHub Pages serves a selected root folder (or `/docs`) from a branch. It will not publish a nested `/website` directory directly as the site root with the usual branch-based setup. For the simplest same-repo setup, use `/docs`.

### Option B: Separate website repository

1. Create a repository such as `MangaReader-Website`.
2. Put `index.html`, `styles.css`, `script.js`, `assets/`, and this README at the repository root.
3. Open **Settings → Pages**.
4. Select **Deploy from a branch**, your default branch, and `/(root)`.
5. Save and use the generated Pages URL.

A separate repository keeps website changes and deployment independent from Android app releases.

## Structure

```text
mangareader-website/
├── index.html
├── styles.css
├── script.js
├── README.md
└── assets/
    └── moon-reader.svg
```

## Notes

- This is a static website; it does not require a backend.
- The mobile navigation, FAQ accordions, and current-year footer are implemented in JavaScript/HTML.
- The page is designed in a monochrome black, white, and grey theme inspired by the Moon Reader logo.
- The website does not host manga files or provide copyrighted manga downloads.
