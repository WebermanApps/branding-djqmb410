# Home Accents Deck: spec

**Question:** Two small colored accents on the Smart Upkeep member Home. Should each one stay (as it is live now) or go?

**Source:** real 390px renders of the live member Home at smart-upkeep **30dd16fd** (PR #39).
- `member/index.html` sha256 starts 1442dccb and matches live smartupkeep.ai/member/ byte for byte.
- I rendered a local unlocked worktree in headless Chromium at 390×844 css px, dsf2, as the standard member (Elena, Plus, `/member/`).
- There was no login, no password files were read, and nothing was pushed to smart-upkeep.

**Push toast hidden:** Home shows a simulated "Push: Fall Visit report is ready" toast when it loads, and it covers the plan tile. I hid it in every render with injected `#toast{display:none}`. The app itself is unchanged.

**Framing:**
- Each option shows a framed 390px crop of Home plus a zoom of the dashed area. The frame and zoom are identical on both sides of a card.
- The only difference between A and B is one CSS rule, injected on the live page.

## Card 1: Next Visit Bar
Frame: Home scrolled 300px, showing the Your Plan tile and the Next Visit tile. Zoom: the left edge of the Next Visit tile.
- **A · Keep The Bar:** the lagoon (#05668D) 4px bar on the left of the Next Visit tile (`.nv::before`), as it is live now.
- **B · No Bar:** `.nv::before{display:none}`.
- Note: the Your Plan tile's lagoon plan edge and the Next Visit tile's thin countdown line along its bottom stay the same in both options. They aren't part of this question.

## Card 2: Header Line
Frame: the top of Home (header plus hero photo). Zoom: the header's bottom edge under the logo.
- **A · Keep The Line:** the 3px terracotta (#C1502E) `border-bottom` on `#mhTop`, as it is live now.
- **B · No Line:** `#mhTop{border-bottom:0}`.
