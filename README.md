# luxeo-site

One-page static site for [luxeo.ai](https://luxeo.ai).

## Stack
- Plain HTML + CSS (no build step)
- Hosted on GitHub Pages
- Custom domain via `CNAME` file + DNS records at Namecheap

## Local preview
```bash
python3 -m http.server 8080
# then open http://localhost:8080
```

## Deploy
Push to `main`. GitHub Pages auto-deploys.

## Brand notes
- Wordmark in `assets/logo.svg` is a placeholder using Inter Bold. The agency (Project.Done) holds the original vector with the custom diamond-X glyph. Drop the original SVG in `assets/logo.svg` to replace.
- Diamond accent in `assets/diamond.svg` is a clean SVG approximation of the brand mark with the pink-to-magenta gradient.
