# AmeChan

[简体中文](README.md)

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

## Usage

1. Keep `pet.json` and `spritesheet.webp` in the same pet directory.
2. Place that directory in Codex's custom-pet location, or add it through Codex's pet-import flow.
3. Restart Codex, or switch away from the pet and then select `AmeChan` again in the pet picker.
4. Once selected, AmeChan provides nine state animations and 16 look directions.

## License Notice

You may freely use, modify, create derivative works from, and redistribute this project for non-commercial purposes only. Commercial use of this project or its derivatives is prohibited.
