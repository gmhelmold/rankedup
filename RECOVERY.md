# RankedUP — recovery state

Recovered on 2026-09-22 after the previous chat became unusable during the GitHub upload.

## Recovered intact

### RankedUP_Approved_Exact_Assets.zip

SHA-256: `8eca76920757d03d5763a95fb39ef92b100f0fafb84a04115690b9292e68a632`

Contains the approved-board direct crops, crop map, validation, checksums and source-board references. The nine delivery assets are direct unscaled crops from the approved 1448×1086 sheet.

### RankedUP_Brand_Assets_v2.zip

SHA-256: `568d8577ec51d54fa0965cccde12480236b2db37ca94a8261fb085067ad2b4b4`

Contains PNG/SVG/outlined SVG/editable sources, favicons, Light/Dark app icon exports, colour tokens and QA documentation.

### Approved visual source board

SHA-256: `09da599b4d4df3f6d91730709d682fe96392b86c8ba5079d0ab25bbe6f3b271c`

## Later ReadyToUse package state recovered from the interrupted session

The later derived package was named `RankedUP_ReadyToUse_Assets.zip`. Its recorded final audit reported:

- 9 transparent delivery crops plus 2 board references checked with AE=0
- 175 raster files decoded successfully
- 99 dimension checks
- 20 aspect-ratio/proportion checks
- lossless WebP, favicon and palette/tokens
- Web, iOS and Android exports
- only Light and Dark app-icon variants
- iOS outputs corrected to opaque and universal iPad slots completed
- approved native app-icon source is 138×138; larger outputs are proportional enlargements

The derived ReadyToUse ZIP itself was not found in persistent Library storage. Its authoritative approved inputs above did survive intact.

## GitHub interruption

The repository was initialized at commit `bbb4cfa9ae767c5d4b83c5a62a3a3eca6f773f5e`. The interrupted chat had created some Git blobs but did not close the tree/commit that would reference them. Unreferenced blobs are therefore not treated as recovered evidence.
