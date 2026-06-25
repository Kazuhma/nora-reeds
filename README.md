# Nora Reeds

One-page artist website for singer-songwriter Nora Reeds, hosted on GitHub Pages.

Static site — no build step, no dependencies. Just `index.html` plus images in `assets/`.

## Local preview

Open `index.html` in a browser, or serve the folder:

```sh
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Assets

`index.html` references two images in `assets/`:

- `assets/nora-reading.jpg` — full-bleed hero photo
- `assets/album-between-the-pages.png` — album cover

Drop those files in `assets/` (exported from the Claude Design project) and the page is complete.

## Deploy (GitHub Pages)

Push to `main`, then enable Pages in repo Settings → Pages → Branch: `main` / root.
