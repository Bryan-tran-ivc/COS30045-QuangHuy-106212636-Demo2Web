# COS30045 Visual Atlas

A self-contained static website combining four exercises: SVG house, TV brand bars, three D3 charts, and an interactive TV explorer. The four source repositories under `../github-repositories/` remain unchanged.

## Deploy to Mercury

Upload **the contents of this folder** to your Mercury web root, keeping `index.html`, `site.css`, and the `house/`, `brands/`, `charts/`, `explorer/` folders together. Open the uploaded `index.html` through the Mercury HTTP URL. No build step or backend is needed. If uploading this folder as a subfolder, open its `index.html` URL instead. D3 v7 loads from `https://d3js.org/d3.v7.min.js`, so viewers need access to that CDN.

For local testing, run `python3 -m http.server 8000` from this folder and open `http://localhost:8000/`. Do not open the HTML with a `file://` URL: browsers block CSV fetches there. Each chart page reads its own relative `data/` folder. Values are practice data, not verified measurements.
