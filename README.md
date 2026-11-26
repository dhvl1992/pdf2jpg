# PDF to JPG

Turn every page of a PDF into a JPG, right in the browser. Part of [My Apps](https://dhvl1992.github.io/).

Live: https://dhvl1992.github.io/pdf2jpg/

- The file never leaves your device: no upload, no server.
- DPI: 150 / 200 / 300 (default 300, same as the old Colab script). JPG quality 95%.
- 1 page → one JPG. More pages → one ZIP.
- Pages are converted one at a time, so it stays light on phone memory.

## Files
- `index.html` — the whole app (plain HTML/CSS/JS, no build step). Uses `/theme.css` from the hub.
- `lib/` — copies of [pdf.js](https://github.com/mozilla/pdf.js) 6.2.108 and [JSZip](https://stuk.github.io/jszip/) 3.10.1, so nothing loads from a CDN.

## Turn on
Settings → Pages → Branch `main` / root.
