# Plan Tile Edge: spec

**Question:** Should the lagoon left edge go on every plan tile, or on the Plus tile only? This is the Your Plan sheet in the Smart Upkeep member app.

**Source:** real 390px renders of the live member Your Plan sheet. The live /member/ files are at smart-upkeep 69f48980; `member/index.html` sha256 starts 83eb53a1 and matches the live files byte for byte.
- I rendered a local unlocked worktree in headless Chromium at 390×844 css px, dsf2, opening Your Plan from the Home plan tile.
- The standard member is Elena on Plus at `/member/`. The Complete member is Brett at `/member/brett/`.
- There was no login, no password files were read, and nothing was pushed to smart-upkeep.

## Card 1: Plan Tile Edge
Both options show the same two tiles in the same order and layout. The only change is the Complete tile's left edge.

- **A · Every Plan Tile**
  - The lagoon (#05668D) 4px left edge sits on every plan tier, as it is live now.
  - Shown: Elena's Plus tile with the edge, and Brett's Complete tile with the edge.
  - Code: no change to `.ps-hero:before`.
- **B · Plus Only**
  - The Plus tile keeps the lagoon edge. Brett's Complete tile has no colored edge: a plain white tile with the same layout.
  - Shown by injecting `#sheet .ps-hero:before{display:none}` on the Complete tile only.
  - In code this would be the Plus tile keeping `:before` and other tiers hiding it, for example `.ps-hero:not(.is-plus):before{display:none}` (or the tier class Develop uses).

## Tile color note (F2)
F2 (white cards inside sheets) is **not live yet** at 69f48980: `.ps-hero` is still #FAF6EE cream on the #FCF9F4 sheet. So the colour doesn't distract from the edge question, every tile in both options is rendered **white (#FFF)** per the white-card rule, with the injected `#sheet .ps-hero{background:#fff}`. Everything else on the tiles is live and unchanged: names, prices ($209/mo Plus; $436/mo Complete incl. extras), care lines, chips and Tailor Your Plan.

## Labels
- Each render has an A/B tag and a title.
- Each tile has a caption: "Plus · Standard Member" or "Complete · Brett".
- Each tile has an edge tag: "Lagoon edge" or "No colored edge".
- The captions are part of the deck image only, not the app.
