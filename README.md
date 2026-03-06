## Good Words

This is a small, single-page site of comforting lines and public-domain quotes.

## Live site

If this repo is named `good-words`, it will be available at:

`https://kryptr003.github.io/good-words/`

## What’s inside

- **`index.html`**: The main page markup and copy (hero text, sections for comfort, classics, and small notes).
- **`styles.css`**: Layout, colors, typography, animations, and theme styling.
- **`script.js`**: Theme toggle, subtle scroll/tilt effects, safety for external links, and the rotating quote card content.

## Editing content

- **Hero + section copy**: Edit the text directly in `index.html`.
- **Rotating quotes**: Update the `quotes` array in `script.js` (each entry has `text`, `from`, and `tag`).
- **Public-domain classics**: The three classic quote cards live in the “Classic lines (public domain)” section of `index.html`.
- **Small notes**: The three “Small notes to keep” cards are also in `index.html`.

## Run locally

You can open `index.html` directly in your browser.

For a simple local server (helpful for caching and JS), from this folder:

```bash
python3 -m http.server 5173
```

Then visit `http://localhost:5173`.
