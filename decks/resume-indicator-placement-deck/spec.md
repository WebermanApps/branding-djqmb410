# Resume Indicator Placement Deck

Style Swipe · Smart Upkeep · Made Nov 13, 2026

Four quick questions about where the Continue Sign-Up prompt should sit once the new green header ships. Each card puts one new spot against today's Pick Up Where You Left Off strip on the bottom bar. If you like more than one new spot, say which wins in Notes. Pick one per card, or tap Machan Decides, and use Notes for anything to tweak.

## Request
Machan, Nov 13 4:22 PM ICT: the Pick Up Where You Left Off prompt on Home is better than before but still a little awkward; consider a small indicator in the new large header. Short A/B deck, one meaning per card, each new placement against today's placement as the control: header pill (beside the icons, and under the logo), a dot on the menu icon that opens Continue Sign-Up, and a slim line at the top of the content card. Real frames, new header preview, light only, Title Case, 44px or more tap targets. Notes and Machan Decides on every card.

## Cards

### Card 1 — Header Pill Beside The Icons
Should the resume prompt move up into the header, as a small pill beside Share and the menu?
- A · Today: Bottom Bar Strip: Preview Context: the new green header and the flush bottom bar are a preview built on top of the real Home render, not live yet. Today's placement: the real Pick Up Where You Left Off · Step 3 strip sits on top of the bottom bar tabs, with an × that clears saved progress.
- B · Pill Beside The Icons: Preview Context: the new green header and the flush bottom bar are a preview built on top of the real Home render, not live yet. A small cream Continue Sign-Up pill in the green band, just left of Share and the menu. The bottom bar strip goes away.

Notes: Preview Context. A small cream pill in the band, left of Share and menu. Khand 13px in Essentials green with a clock glyph, 28px tall with a 44px tap area. Tap goes straight back to the saved step. The bottom bar loses its strip and goes back to tabs plus Get Started. No × on the pill; Start Over inside sign-up still clears progress. Fits at 360 with room to spare.

Machan Decides sits on the card.

### Card 2 — Header Pill Under The Logo
Or should the header pill sit on its own row under the logo, with the step number?
- A · Today: Bottom Bar Strip: Preview Context: the new green header and the flush bottom bar are a preview built on top of the real Home render, not live yet. Today's placement: the real Pick Up Where You Left Off · Step 3 strip sits on top of the bottom bar tabs, with an × that clears saved progress.
- B · Pill Under The Logo: Preview Context: the new green header and the flush bottom bar are a preview built on top of the real Home render, not live yet. Continue Sign-Up · Step 3 as a cream pill under the logo. The band is 16px taller only while there is progress to resume.

Notes: Preview Context. The same pill on its own row under the logo, with the step number (· Step 3). To fit without touching the logo, the band grows 16px (88 to 104) only while there is progress to resume; the card still overlaps by 24px. 26px tall with a 44px tap area.

Machan Decides sits on the card.

### Card 3 — Dot On The Menu
Should the header just show a small dot on the menu, with Continue Sign-Up as the menu's top row?
- A · Today: Bottom Bar Strip: Preview Context: the new green header and the flush bottom bar are a preview built on top of the real Home render, not live yet. Today's placement: the real Pick Up Where You Left Off · Step 3 strip sits on top of the bottom bar tabs, with an × that clears saved progress.
- B · Menu Dot, Then Continue Row: Preview Context: the new green header and the flush bottom bar are a preview built on top of the real Home render, not live yet. A small cream dot on the menu icon. Tap the menu and Continue Sign-Up · Step 3 is the top row, above Log In and Sign Up. The clip loops the tap and open.

Notes: Preview Context. A small cream dot on the menu icon. The clip shows a tap, then the menu opening: Continue Sign-Up · Step 3 is the top row (green on a pale green row), above Log In and Sign Up. Rows are 48px. Open is 220ms ease-out, close 180ms. Quietest option on Home: nothing extra shows until the menu is opened.

Machan Decides sits on the card.

### Card 4 — Slim Line On The Card
Should the prompt be a slim line across the top of the white card instead?
- A · Today: Bottom Bar Strip: Preview Context: the new green header and the flush bottom bar are a preview built on top of the real Home render, not live yet. Today's placement: the real Pick Up Where You Left Off · Step 3 strip sits on top of the bottom bar tabs, with an × that clears saved progress.
- B · Slim Line At Card Top: Preview Context: the new green header and the flush bottom bar are a preview built on top of the real Home render, not live yet. A slim cream Continue Sign-Up · Step 3 Of 11 row at the top of the white card, with a thin green progress line, a chevron and an ×.

Notes: Preview Context. A 44px cream row at the very top of the white card, with a thin green progress line along its top edge (3 of 11 filled). Continue Sign-Up · Step 3 Of 11, a chevron, and an × to clear progress, like today. The hero moves down 44px while it shows.

Machan Decides sits on the card.

## Provenance
Every frame is rendered from a git archive of smart-upkeep main 79f5d57beddea154e471c14821fd401767a72d40 (PR #107 merge, cache h99q), pagelock check exit 0, unlocked only in a local QA copy and served on 127.0.0.1 with all outside traffic blocked and fonts served locally. The real resume prompt comes from the app's own saved state (localStorage smartUpkeep.v1 with resume set to the Systems step), so the control strip reads the live text: Pick Up Where You Left Off · Step 3. Preview Context (injected on top of the real render, not live yet): a #0B6E4F brand band 88px plus the safe area, the real logo in white at 26px on the left, Share and menu as 48px tap targets with 22px white line glyphs, a white content card with a 20px top radius overlapping the band by 24px, and the bottom bar made full width and flush to the bottom edge. The badge strip shuffles on every load, so the capture seeds the shuffle to show the same badge order on every frame. Captured at 390x844 (2x); crop QA at 360x640. The menu clip is frame-stepped at 24fps (tap 250ms, open 220ms ease-out, hold 1.8s, close 180ms), muted, looping, playsinline, with a poster. Nothing submitted, finished or sent. Nothing pushed to smart-upkeep.

