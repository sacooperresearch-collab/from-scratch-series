# The From Scratch Series — site

A single-page site for S. A. Cooper's *From Scratch* series, ready to publish with GitHub Pages.

## Files

Everything sits flat, in one folder, no subfolders:

```
index.html
assumed-flatness.png
expanding-universe.png
sound-horizon.png
```

## Publish it on GitHub Pages

1. In your repo, use **Add file → Upload files**.
2. Drag in all four files above at once, directly into the repo root (not into a subfolder).
3. Commit to `main`.
4. Go to **Settings → Pages**.
5. Set **Source** to `Deploy from a branch`, branch `main`, folder `/ (root)`. Save.
6. The site publishes at `https://<your-username>.github.io/<repo-name>/` within a minute or two.

## If the cover images don't show up

This is almost always a path mismatch. To check:

1. Open the repo's main page on GitHub and confirm you actually see `assumed-flatness.png`, `expanding-universe.png`, and `sound-horizon.png` listed as files — not inside a folder.
2. Filenames are case-sensitive on GitHub Pages, even though they may not be on your own computer. `Assumed-Flatness.PNG` will not match `assumed-flatness.png` in the code.
3. If GitHub renamed a file on upload (adding `(1)` or similar), rename it back to match exactly what's in `index.html`, or edit the `src=` attribute in `index.html` to match the actual filename.

## Editing later

- Book copy and Amazon links live in the `<article class="book">` blocks in `index.html`.
- Swap a cover image by replacing the file with the same filename, or update the `src` attribute.
- Colors and type are set as CSS custom properties at the top of the `<style>` block in `index.html`.
- Add a new book by copying one `<article class="book">...</article>` block and editing its contents — the layout isn't capped at three.
