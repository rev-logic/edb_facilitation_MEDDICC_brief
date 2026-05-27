# Fonts

## Roboto
Loaded from Google Fonts via `@import` in `colors_and_type.css`. Weights: 100 / 300 / 400 / 500 / 700 / 900. Open source (Apache 2.0).

## Neue Haas Grotesk Display Pro
**Commercial face — files not shipped.** Licensable from Monotype (https://www.monotype.com/fonts/neue-haas-grotesk).

Until the licensed files are added, the design system falls back to:
1. `Helvetica Neue` (macOS system)
2. `Helvetica` / `Arial`
3. `system-ui`

To install:
1. Drop the `.woff2` files into `fonts/neue-haas-grotesk-display/`
2. Uncomment the `@font-face` block at the top of `colors_and_type.css`

**Recommended weights to license:** 45 Light, 55 Roman, 65 Medium, 75 Bold, 85 Black.

**Substitution flagged to the user** — please confirm whether the licensed font is available so we can swap it in.
