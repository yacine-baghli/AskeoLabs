# Askeo Labs

The Askeo Labs website: a single static page, no build step.

- `index.html`, `styles.css`, `main.js`: the page.
- `media/`: the logo, the mark and the favicon.
- `tools/build-art.mjs`: draws the logo and the three hero figures and writes them into
  `index.html` and `media/`. After changing a drawing, run `node tools/build-art.mjs`.

To preview, open `index.html` in a browser. The site is deployed on Vercel from this folder.
