# AmeChan

A Codex-compatible v2 animated pet inspired by a red rabbit-hoodie, bat-wing character.

## Contents

- `pet.json`: Codex pet metadata.
- `spritesheet.webp`: 8-column × 11-row v2 spritesheet, with 192 × 208 pixel cells.
- `contact-sheet-extended.png`: static overview of every animation and direction frame.
- `gifs/`: preview GIFs for all nine standard actions plus the two look rows and complete 16-direction loop.
- `qa/`: sanitized validation and visual QA reports.

## Action GIFs

`idle`, `running-right`, `running-left`, `waving`, `jumping`, `failed`, `waiting`, `running`, and `review` each have a dedicated GIF. `look-row-9.gif`, `look-row-10.gif`, and `look-loop.gif` preview the direction system.

## Compatibility

The pet uses `spriteVersionNumber: 2`, with a 1536 × 2288 WebP spritesheet and transparent background. It passed structural validation and final visual QA.

## Publishing

No machine-specific paths, source-image history, or local generation records are included in this folder. Add your chosen open-source license before publishing.
