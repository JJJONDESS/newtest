# Melt9 AR Menu - dome capsule version (v29)

Test version, based on the clean v23 (glass box).
Your v23 glass-box version is still saved separately as the
Promotion Food final - this v29 does NOT replace it.

## The dome capsule
- Clear glass dome over the pizza, like the futuristic
  food machine in your picture (half a sphere, top half
  only, opacity 0.08 so the pizza stays clear).
- Silver metal ring where the dome meets the base.
- Yellow glow ring around the dome base, and a small
  glow ring inside the top of the dome, in Melt9 yellow
  #FFC20F. Change #FFC20F to #00e5ff in index.html if
  you want the glow blue like the picture.
- Solid dark metal base under the dome, with a black
  MELT9 logo plate on the front.
- Pizza sits on the base (centre z=-0.15), not floating
  in the middle. Shadow on the base under the pizza.
- No robot arms / machinery inside the dome - we do not
  have a 3D model of that machine, and it would hide
  the pizza. The dome is clean: dome + base + glow.
- Fixed AR label, Add to cart + Photo in AR, 1-second
  flash, auto-spin - all as in v23, in Melt9 colours.

## How it works - iOS and Android
- iPhone: "View in your space" = Apple Quick Look.
- Android: "Scan the menu photo" = camera AR, A-Frame +
  MindAR from `libs/` (self-hosted, no CDN).
- Pizza size: `dishes.js`, `scale:` - change all 3 numbers.
- Dome size / glow: `index.html`, search "DOME CAPSULE".
