# Website

This repository contains a static snapshot of [dancary.com](https://dancary.com/) downloaded using HTTrack. The files can be served as a simple static website.

## Viewing locally

You can serve the site using Python's built-in HTTP server:

```bash
python3 -m http.server --directory "my website" 8000
```

Then open <http://localhost:8000> in your browser.

## GitHub Pages

If you want to host this repository with GitHub Pages, set `my website` as the website root in the repository settings ("Deploy from a folder").
