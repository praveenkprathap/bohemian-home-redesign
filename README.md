# A home, soulful — Bohemian + Neo-Ethnic home redesign

A static, responsive HTML gallery for five supplied interiors: living, dining, kitchen, bedroom and upper living area. Each room has Original/Bohemian/Neo-Ethnic controls and a global style switch, a full-size image link, design notes and implementation considerations.

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
- `app.js`: room content and Original/Bohemian/Neo-Ethnic controls and a global style switch
- `assets/*-before.jpg`: supplied room images
- `assets/*-after.jpg`: generated Bohemian concept images
- `assets/*-neo.jpg`: generated Neo-Ethnic concept images

This project includes personal source imagery supplied for this redesign. No general license to reuse those images is granted.

Neo-Ethnic follows the second supplied moodboard: Indian modern geometry, dark teak/walnut, brass, botanical art and restrained heritage motifs. The original photographs remain the starting point for both styles.

## Tropical Modern — alternative furniture layouts

A third design direction adds five new concept images (`assets/*-tropical.jpg`) using teak, cream linen, muted green and simple stone accents. The living room uses a rear-wall sofa and separate chair; dining uses a round table; the kitchen has a compact round breakfast arrangement; the bedroom tests a rotated freestanding bed; the upper lounge uses two chairs. The gallery opens in Tropical Modern and retains both earlier styles and original photographs.

These are photographic layout studies, not measured fit checks. Architectural openings, stairs, fixed cabinetry and services are intended to remain in place. Verify actual clearances before implementing, especially the rotated bed and chair pull-out areas.

## Soft Art Deco — clarified living-room partition

Five additional concepts (`assets/*-deco.jpg`) use ivory, walnut, muted teal, brass and curved furniture. This is the default gallery view. The main living room now interprets the TV feature as a slim open divider, with sightlines and passage into the adjoining space; it is not treated as a full enclosing structural wall. Existing columns, beams, other walls and all openings remain part of the retained shell. Earlier living-room visuals are marked as predating this clarification.

The exact partition design is conceptual and must be measured on site. Check TV mounting, divider stability and wiring with the installer. No structural demolition is proposed.
