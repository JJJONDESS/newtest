# Melt9 AR Menu - crystal plate version (v24)

Same working menu as v23, with the glass box replaced by a
crystal clear plate. No other behaviour changed.
Your v23 glass-box version is saved separately as the
Promotion Food final - this v24 is a test version to compare.

## The crystal plate
- Clear glass plate under the pizza (almost invisible,
  like the "Meals of 2040" picture - the food is the hero).
- Thin yellow rim (#FFC20F) around the plate, so you can
  still see where the plate ends on a light table.
- A second, larger clear plate underneath, layered like
  the glass stands in the reference picture.
- Small black MELT9 logo seen through the glass, under
  the plate - branding without a solid yellow base.
- Shadow under the pizza, 1-second flash, fixed AR label,
  Add to cart + Photo in AR - all as before.

## How it works - iOS and Android
- Menu page: list of dishes from `dishes.js`.
- Dish page: 3D view first (model-viewer).
  - iPhone: "View in your space" = Apple Quick Look.
  - Android: "Scan the menu photo" = camera AR, A-Frame +
    MindAR from `libs/` (self-hosted, no CDN).
- Pizza size: `dishes.js`, `scale:` - change all 3 numbers.
- Plate size / rim: `index.html`, search "CRYSTAL PLATE".
- Brand colours: yellow #FFC20F, black #000000.

## Files in this zip
- `index.html`, `app.js`, `dishes.js`, `kitchen.html`
- `libs/` - A-Frame + MindAR engine. Always upload this
  folder with index.html, or the camera will fail.
- `dishes/` - only files actually used: 3 models x2
  (small + iOS), 3 target photos (.mind), 3 posters,
  `shadow.png`, `base-logo.png`.
