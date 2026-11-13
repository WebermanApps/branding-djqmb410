# FAQ Look Deck

Style Swipe · Smart Upkeep · Made Nov 13, 2026

Eight questions about the FAQ section on Home. The first card is the chip and row look, matched to À La Carte. The rest are short looping recordings of how a question opens and closes. The green header (logo on the left, Share and menu on the right) and the flush full-width Get Started bar are preview context for the coming Home chrome, not live yet. Pick one per card, or tap Machan Decides, and use Notes for anything to tweak.

## Request
A separate FAQ Look deck, visually consistent with the À La Carte one. Opening and closing matter most, so most cards are short looping recordings of open and close motion. Notes and Machan Decides on every card.

## Cards

### Card 1 — Chips And Rows
Should the FAQ chips and rows keep today's look, or match the À La Carte treatment?
- A · Today's Look: The live FAQ chips and divided rows on the cream page.
- B · Matched To À La Carte: The same green selected chip and soft padded rows as the À La Carte Look deck.

Notes: Today is the live FAQ chips and divided rows. Matched To À La Carte uses the same green selected chip and soft padded rows as the À La Carte Look deck. The green header (logo on the left, Share and menu on the right) and the flush full-width Get Started bar are preview context for the coming Home chrome, not live yet.

Machan Decides sits on the card.

### Card 2 — Expand Easing
Which open and close timing feels right?
- A · 200ms Ease-Out: A 200ms ease-out open and close. The loop plays in the deck.
- B · 320ms Springy Ease: A 320ms cubic-bezier(.2,.8,.2,1) open and close. The loop plays in the deck.

Notes: Both loops open and close the first question. A is 200ms ease-out. B is 320ms cubic-bezier(.2,.8,.2,1). Every option stays on one phone screen, with no jank and no layout shift outside the section. Under reduced motion, opens and closes are instant (no height, fade, or icon motion). These deck loops still play unless the device is set to reduce motion, in which case the poster frame is shown. The green header (logo on the left, Share and menu on the right) and the flush full-width Get Started bar are preview context for the coming Home chrome, not live yet.

Machan Decides sits on the card.

### Card 3 — Height Animation
How should the answer height be animated?
- A · Grid Rows: CSS grid-template-rows from 0fr to 1fr, smooth, with no jump.
- B · Measured Height: A measured pixel height that eases to the answer size, then settles, also with no jump.

Notes: Both are smooth, with no jump. Grid uses CSS grid-template-rows from 0fr to 1fr. Measured Height animates a pixel height, then settles. Both use the 320ms cubic-bezier(.2,.8,.2,1) timing. Every option stays on one phone screen, with no jank and no layout shift outside the section. Under reduced motion, opens and closes are instant (no height, fade, or icon motion). These deck loops still play unless the device is set to reduce motion, in which case the poster frame is shown. The green header (logo on the left, Share and menu on the right) and the flush full-width Get Started bar are preview context for the coming Home chrome, not live yet.

Machan Decides sits on the card.

### Card 4 — Open Icon
Should the row use a rotating chevron, or a plus that becomes a minus?
- A · Chevron Rotate: The live chevron rotates as the row opens and closes.
- B · Plus To Minus: A plus becomes a minus on the same timing.

Notes: Chevron Rotate turns the live chevron as the row opens. Plus To Minus swaps a plus for a minus on the same timing. Every option stays on one phone screen, with no jank and no layout shift outside the section. Under reduced motion, opens and closes are instant (no height, fade, or icon motion). These deck loops still play unless the device is set to reduce motion, in which case the poster frame is shown. The green header (logo on the left, Share and menu on the right) and the flush full-width Get Started bar are preview context for the coming Home chrome, not live yet.

Machan Decides sits on the card.

### Card 5 — Answer Enter
As the height opens, should the answer fade in, or also slide in a little?
- A · Fade In: The answer fades in as the height opens.
- B · Fade And Slide: The same fade, with a short upward settle as the answer arrives.

Notes: Fade brings the answer in by opacity as the height opens. Slide-In adds a short upward settle on the same fade and height. Every option stays on one phone screen, with no jank and no layout shift outside the section. Under reduced motion, opens and closes are instant (no height, fade, or icon motion). These deck loops still play unless the device is set to reduce motion, in which case the poster frame is shown. The green header (logo on the left, Share and menu on the right) and the flush full-width Get Started bar are preview context for the coming Home chrome, not live yet.

Machan Decides sits on the card.

### Card 6 — One Or Several Open
When you open a question, should the others close, or can several stay open?
- A · One Open At A Time: Opening a second question closes the first.
- B · Several Stay Open: Opening a second question leaves the first one open. It still fits one screen.

Notes: One Open At A Time closes the first question when the second is tapped. Several Stay Open keeps both answers open. The section still fits one screen. Every option stays on one phone screen, with no jank and no layout shift outside the section. Under reduced motion, opens and closes are instant (no height, fade, or icon motion). These deck loops still play unless the device is set to reduce motion, in which case the poster frame is shown. The green header (logo on the left, Share and menu on the right) and the flush full-width Get Started bar are preview context for the coming Home chrome, not live yet.

Machan Decides sits on the card.

### Card 7 — Inner Scroll Follow
When an open answer would run past the fold, should the list follow it, or stay put?
- A · Stays Put: The list does not scroll. The open answer can clip at the bottom of the box.
- B · Scroll Follows: The box uses scrollIntoView nearest so the open item stays on screen.

Notes: Shown on Plans And Visits, in a box that is shorter than the full group, so opening a lower question can run past the fold. Stays Put leaves the scroll where it was, so the answer can clip. Scroll Follows uses scrollIntoView nearest so the open item stays on screen. Every option stays on one phone screen, with no jank and no layout shift outside the section. Under reduced motion, opens and closes are instant (no height, fade, or icon motion). These deck loops still play unless the device is set to reduce motion, in which case the poster frame is shown. The green header (logo on the left, Share and menu on the right) and the flush full-width Get Started bar are preview context for the coming Home chrome, not live yet.

Machan Decides sits on the card.

### Card 8 — Tap Feedback
What should a tap on a question feel like?
- A · Subtle Press Tint: A light Essentials-green wash on the row for about 160ms.
- B · Scale .98: The row scales to 0.98 for a short press-in, on the same timing.

Notes: Subtle Press Tint flashes a light Essentials-green wash on the row. Scale .98 gives a short press-in. Both last about 160ms. Every option stays on one phone screen, with no jank and no layout shift outside the section. Under reduced motion, opens and closes are instant (no height, fade, or icon motion). These deck loops still play unless the device is set to reduce motion, in which case the poster frame is shown. The green header (logo on the left, Share and menu on the right) and the flush full-width Get Started bar are preview context for the coming Home chrome, not live yet.

Machan Decides sits on the card.

## Provenance
Same local unlocked archive of smart-upkeep 79f5d57 as the À La Carte Look deck, 127.0.0.1, outside traffic blocked. Motion loops are 20fps sequences encoded to muted, playsinline, looping MP4 under 1.5MB, with a 780×1688 poster. Question wording is the live FAQ copy. Crop QA at 390×844 and 360×640. Nothing submitted, paid, finished or sent. Nothing was pushed to smart-upkeep.

