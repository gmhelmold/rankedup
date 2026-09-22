# RankedUP — exact approved-image assets

This package preserves the approved RankedUP sheet exactly as rendered. It is intentionally **not** a vector redesign.

## What “exact” means here

- `reference/RankedUP_Approved_Asset_Sheet.png` is the approved 1448 × 1086 source board, copied without modification.
- Every PNG under `png/` is a direct, unscaled pixel crop from that board.
- No image generation, recolouring, re-drawing, masking, alpha extraction, retouching, or resampling was applied to those PNGs.
- `CROP_MAP.json` records the exact source rectangle for each asset; `SHA256SUMS.txt` provides provenance hashes.

The Light and Dark app icons are the only app-icon variants included, exactly as approved. The original metal, pearl-white lettering, contained ember treatment, fine badge edge, proportions, and finishes are all preserved from the board pixels.

## Use

- Use `png/light/` on light surfaces.
- Use `png/dark/` on dark/black surfaces.
- Use `png/shared/` for the standalone mark, UP badge, and approved palette.
- The intended background is baked into each source-extracted crop so it remains visually identical to the approved sheet.

## Important boundary

These are exact visual source extracts. An editable SVG that is also pixel-identical cannot be produced without the original vector master; recreating one would again become an approximation. The previous vector reconstruction is therefore not part of this exact package.
