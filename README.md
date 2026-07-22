# The From Scratch Series — site

A single-page site for S. A. Cooper's *From Scratch* series, ready to publish with GitHub Pages.

## Files

```
index.html
images/
  assumed-flatness.png
  expanding-universe.png
  sound-horizon.png
```

## Publish it on GitHub Pages

1. Create a new repository on GitHub (public), e.g. `from-scratch-series`.
2. Add these files to the repo, keeping `images/` alongside `index.html`.
3. Commit and push to the `main` branch.
4. In the repo, go to **Settings → Pages**.
5. Under **Build and deployment**, set **Source** to `Deploy from a branch`, branch `main`, folder `/ (root)`. Save.
6. GitHub will publish the site at `https://<your-username>.github.io/from-scratch-series/` within a minute or two.

## Editing later

- Book copy and Amazon links live in the `<article class="book">` blocks in `index.html`.
- Swap a cover image by replacing the file in `images/` with the same filename, or update the `src` attribute.
- Colors and type are set as CSS custom properties at the top of the `<style>` block in `index.html`.
