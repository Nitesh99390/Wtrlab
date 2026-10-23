# Wtrlab

Archived static snapshot of `wtr-lab.com` (saved site assets).

## Structure

- `wtr-lab.com/` – main site pages, `_next/` static chunks, images
- `img.wtr-lab.com/` – CDN images
- `fonts.googleapis.com/`, `fonts.gstatic.com/` – web fonts
- `_DataURI/` – inline data URIs extracted by the archiver
- Other domains – third-party scripts captured with the page

## Serve locally

```bash
python3 -m http.server 8000
# open http://localhost:8000/wtr-lab.com/
```
