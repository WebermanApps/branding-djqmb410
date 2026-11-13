# Onboarding Home Build Deck

Style Swipe · Smart Upkeep · Made Nov 13, 2026

Five questions about building the house through all 11 sign-up steps. Style and placement are already settled from your Sign-Up First Steps picks: a flat illustration in a band above the title, with a small caption. Step 1 is still and shows a filter change. From step 2 the house reacts with light motion, and a What's Included For A Home Like Yours hint sits under the band. The house is one illustration (never a photo of the home), in a 120px band that stays the same height on every step. It shrinks to a mini strip only when the keyboard is open. Every step fits the Safari visible area on an iPhone 14 or 15, about 390×660.  Pick one per card, or tap Machan Decides, and use Notes for anything to tweak.

## Request
Machan, 7:44 PM ICT, 13 Nov 2026: for the onboarding I love the idea of building the home with a graphic as we go; when they go to one story or two story it shows the graphic as they go, and if they add stuff it shows it on the screen, and we carry the home with them until they finish. Folded with Sign-Up First Steps picks (flat illustration, Filter Change, still on step 1, band above the title, small caption, Home That Reacts, What's Included hint, light motion). Team plan with Develop: one inline SVG, transform and opacity only, 200–300ms, no loops, no confetti, green only as a tiny plant accent, centered Warm White header with Share top left and the menu top right. 7:49–7:50 PM: every step fits the iPhone 14/15 Safari visible area of about 390×660; keep the house band consistent, tighten questions first, then drop Did You Know, and shrink the house only as a last resort.

## Cards

### Card 1 — Step 1 Scene
On Where's Your Home?, should Filter Change be its own picture, or happen inside the empty house?
- A · Its Own Picture: A still flat Filter Change illustration in the 120px band, with no house around it.
- B · Inside The Empty House: The same Filter Change, happening inside the empty house frame, so the scene can grow from step 1 to step 11.

Notes: Both are still, as the team called for step 1. A is the Filter Change as its own small picture. B puts that same filter change inside the empty house frame, so step 1 through step 11 is one continuous scene. Style and placement come from your Sign-Up First Steps picks (flat illustration, band above the title, small caption). The header is the coming Warm White band with a centered logo, Share top left and the menu top right, 88px tall. The house band is 120px on every step, including this one, and shrinks to a 48px mini strip only when the keyboard is open. Green is only the small plant accent, never a band.

Machan Decides sits on the card.

### Card 2 — How Items Appear
When a system or extra is added, how should it appear on the house?
- A · Pop: The item scales up into place with a short fade, about 240ms.
- B · Draw-In: The item slides up into place with a short fade, about 260ms.

Notes: Shown on Your Systems as the AC unit is added to a 2-story house that already has a furnace and a tank water heater. Pop scales the unit up with a fade (about 240ms). Draw-In slides it up into place with a fade (about 260ms). Both use only transform and opacity, one change per answer. The live motion is a single play, not a loop; this clip repeats so you can see it. Under reduced motion, see card 5. Style and placement come from your Sign-Up First Steps picks (flat illustration, band above the title, small caption). The header is the coming Warm White band with a centered logo, Share top left and the menu top right, 88px tall. The house band is 120px on every step, including this one, and shrinks to a 48px mini strip only when the keyboard is open. Green is only the small plant accent, never a band.

Machan Decides sits on the card.

### Card 3 — Story Change
When the number of stories changes, should the house morph, or swap?
- A · Morph: The same house eases from one story to two, about 280ms.
- B · Swap: The 1-story house crossfades with the 2-story house, about 280ms.

Notes: Shown on How Big Is Your Home? as the answer moves from 1 Story to 2 Stories. Morph eases the same house from one floor to two (about 280ms). Swap crossfades the 1-story layer with the 2-story layer. Size stays Under 2,000, and the What's Included hint stays one line under the band. The live motion is a single play; this clip repeats so you can see it. Style and placement come from your Sign-Up First Steps picks (flat illustration, band above the title, small caption). The header is the coming Warm White band with a centered logo, Share top left and the menu top right, 88px tall. The house band is 120px on every step, including this one, and shrinks to a 48px mini strip only when the keyboard is open. Green is only the small plant accent, never a band.

Machan Decides sits on the card.

### Card 4 — Finish Reveal
At the last step, how should the finished house land?
- A · Settle: The finished house eases into place with a short scale and fade. No confetti.
- B · Reveal: The finished house fades and eases in. No confetti.

Notes: Shown on Join Plus, with the finished 2-story house carried through from earlier answers. Settle is a short scale and fade into place (about 300ms). Reveal fades and eases the finished house in (about 300ms). No confetti. Legal recap copy is unchanged. The live motion is a single play; this clip repeats so you can see it. Style and placement come from your Sign-Up First Steps picks (flat illustration, band above the title, small caption). The header is the coming Warm White band with a centered logo, Share top left and the menu top right, 88px tall. The house band is 120px on every step, including this one, and shrinks to a 48px mini strip only when the keyboard is open. Green is only the small plant accent, never a band.

Machan Decides sits on the card.

### Card 5 — Reduced Motion
When a device asks for reduced motion, should items cut in, or fade?
- A · Instant Swap: The item or story cuts in at once, with no motion.
- B · A Quick Fade: The item or story fades in with opacity only, about 200ms.

Notes: Shown as the AC unit appears on Your Systems. Instant Swap cuts in with no motion. A Quick Fade uses opacity only, about 200ms, with no scale or slide. This is the prefers-reduced-motion fallback for every house change (items, stories and the finish). Style and placement come from your Sign-Up First Steps picks (flat illustration, band above the title, small caption). The header is the coming Warm White band with a centered logo, Share top left and the menu top right, 88px tall. The house band is 120px on every step, including this one, and shrinks to a 48px mini strip only when the keyboard is open. Green is only the small plant accent, never a band.

Machan Decides sits on the card.

## Provenance
Original flat SVG illustrations drawn for this deck (no AI photos, no member houses). Funnel steps and answers mapped from live smart-upkeep main 08c9fa56 (app.js and pricing-config.js). The header is a mock of the coming Warm White #FFFCF7 88px band with the logo centered at all times, Share top left and the menu top right (header PR in progress; logo size matches the live 12% larger mark). The house-build graphic is not live. One inline SVG, 10,680 bytes, with a layer group per item. Motion in the product is a one-shot 200–300ms transform or opacity change, no loops; the deck clips loop so you can see it. Mocks are the 390×660 Safari visible area (and 360×640), not the full 390×844 phone. Real prices only (Essentials $139/mo, Plus $209/mo, Complete $379/mo). Crop QA at 390×660 and 360×640. Nothing submitted, paid, finished or sent. Nothing was pushed to smart-upkeep.

