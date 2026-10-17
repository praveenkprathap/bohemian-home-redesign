# A home, soulful — Bohemian home redesign

A static, responsive HTML gallery for five supplied interiors: living, dining, kitchen, bedroom and upper living area. Each room has original/concept controls, a full-size image link, design notes and implementation considerations.

## View locally

Open `index.html` directly in a browser, or run `python3 -m http.server 8000` in this directory and visit `http://localhost:8000`.

No build step, package installation, account or backend is required. Google Fonts are optional; local fallback fonts are included.

## Publish publicly with GitHub Pages

Upload this complete project to a new repository. In repository Settings → Pages, choose **GitHub Actions** as the source. The included workflow deploys the static files on pushes to `main`, or from its manual Run workflow control. A public GitHub Pages URL is shown after a successful deployment.

## Design basis

The supplied Bohemian moodboard informs terracotta, olive, ochre, linen and natural timber, with cane details, layered textiles and handmade ceramics. The five supplied room photographs are the source images. Generated proposals are conceptual images and may vary from the precise original geometry. No room dimensions, product prices or construction specifications are inferred.

Keep original openings and circulation. Confirm measurements, fan clearances, cabinet operation, rug placement and finish suitability on site before implementation.

## Files

- `index.html`: page structure
- `styles.css`: responsive and print styles
- `app.js`: room content and original/concept controls
- `assets/*-before.jpg`: supplied room images
- `assets/*-after.jpg`: generated Bohemian concept images

This project includes personal source imagery supplied for this redesign. No general license to reuse those images is granted.
