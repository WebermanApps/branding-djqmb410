# Resume Indicator Placement Deck

Style Swipe · Smart Upkeep · Made Nov 13, 2026

Four quick questions about where the Continue Sign-Up prompt should sit on Home. Each card puts one new spot against today's Pick Up Where You Left Off strip on the bottom bar. If you like more than one new spot, say which wins in Notes. Pick one per card, or tap Machan Decides, and use Notes for anything to tweak.

## Request
Machan, Nov 13 4:22 PM ICT: the Pick Up Where You Left Off prompt on Home is better than before but still a little awkward; consider a small indicator in the new large header. Short A/B deck, one meaning per card, each new placement against today's placement as the control: header pill (beside the icons, and under the logo), a dot on the menu icon that opens Continue Sign-Up, and a slim line at the top of the content card. Real frames, new header preview, light only, Title Case, 44px or more tap targets. Notes and Machan Decides on every card.

## Cards

### Card 1 — Header Pill Beside The Icons
Should the resume prompt move up into the header, as a compact clock pill beside the menu?
- A · Today: Bottom Bar Strip: Preview Context: placements are shown on the current Warm White header — logo centered, Share top left, Menu top right. The flush bottom bar is a preview on top of the real Home render. Today's placement: the real Pick Up Where You Left Off · Step 3 strip sits on top of the bottom bar tabs, with an × that clears saved progress.
- B · Compact Clock Beside The Menu: Preview Context: placements are shown on the current Warm White header — logo centered, Share top left, Menu top right. The flush bottom bar is a preview on top of the real Home render. A compact terracotta clock pill immediately left of the menu. A full Continue Sign-Up label does not fit beside the icons once the logo is centered. The bottom bar strip goes away.

Notes: Preview Context. With the logo centered, a full Continue Sign-Up label no longer fits between the logo and the menu, so this option is a compact terracotta clock pill immediately left of the menu. 28px at 390, 24px at 360, with a 44px tap area. Tap goes straight back to the saved step. The bottom bar loses its strip and goes back to tabs plus Get Started. No × on the pill; Start Over inside sign-up still clears progress. At 360 there is a clear gap from the logo.

Machan Decides sits on the card.

### Card 2 — Header Pill Under The Logo
Or should the header pill sit on its own row under the logo, with the step number?
- A · Today: Bottom Bar Strip: Preview Context: placements are shown on the current Warm White header — logo centered, Share top left, Menu top right. The flush bottom bar is a preview on top of the real Home render. Today's placement: the real Pick Up Where You Left Off · Step 3 strip sits on top of the bottom bar tabs, with an × that clears saved progress.
- B · Pill Under The Logo: Preview Context: placements are shown on the current Warm White header — logo centered, Share top left, Menu top right. The flush bottom bar is a preview on top of the real Home render. Continue Sign-Up · Step 3 as a terracotta pill, centered under the logo. The band is taller only while there is progress to resume, so the pill is not covered by the card.

Notes: Preview Context. The same terracotta pill, centered on its own row under the logo, with the step number (· Step 3). The band grows from 88px to 124px only while there is progress to resume, so the pill sits fully under the logo and is not covered by the card; the card still overlaps by 24px. 28px tall with a 44px tap area.

Machan Decides sits on the card.

### Card 3 — Dot On The Menu
Should the header just show a small dot on the menu, with Continue Sign-Up as the menu's top row?
- A · Today: Bottom Bar Strip: Preview Context: placements are shown on the current Warm White header — logo centered, Share top left, Menu top right. The flush bottom bar is a preview on top of the real Home render. Today's placement: the real Pick Up Where You Left Off · Step 3 strip sits on top of the bottom bar tabs, with an × that clears saved progress.
- B · Menu Dot, Then Continue Row: Preview Context: placements are shown on the current Warm White header — logo centered, Share top left, Menu top right. The flush bottom bar is a preview on top of the real Home render. A small terracotta dot on the menu icon. Tap the menu and Continue Sign-Up · Step 3 is the top row, above Log In and Sign Up, with no wrapped label. The clip loops the tap and open.

Notes: Preview Context. A small terracotta dot on the menu icon. The clip shows a tap, then the menu opening: Continue Sign-Up · Step 3 is the top row (terracotta on a warm cream row, no wrapped label), above Log In and Sign Up. Rows are 48px. Open is 220ms ease-out, close 180ms. Quietest option on Home: nothing extra shows until the menu is opened.

Machan Decides sits on the card.

### Card 4 — Slim Line On The Card
Should the prompt be a slim line across the top of the white card instead?
- A · Today: Bottom Bar Strip: Preview Context: placements are shown on the current Warm White header — logo centered, Share top left, Menu top right. The flush bottom bar is a preview on top of the real Home render. Today's placement: the real Pick Up Where You Left Off · Step 3 strip sits on top of the bottom bar tabs, with an × that clears saved progress.
- B · Slim Line At Card Top: Preview Context: placements are shown on the current Warm White header — logo centered, Share top left, Menu top right. The flush bottom bar is a preview on top of the real Home render. A slim cream Continue Sign-Up · Step 3 Of 11 row at the top of the white card, with a thin terracotta progress line, a chevron and an ×.

Notes: Preview Context. A 44px cream row at the very top of the white card, with a thin terracotta progress line along its top edge (3 of 11 filled). Continue Sign-Up · Step 3 Of 11, a chevron, and an × to clear progress, like today. The hero moves down 44px while it shows.

Machan Decides sits on the card.

## Provenance
Every frame is rendered from a git archive of smart-upkeep main 79f5d57beddea154e471c14821fd401767a72d40 (PR #107 merge, cache h99q), pagelock check exit 0, unlocked only in a local QA copy and served on 127.0.0.1 with all outside traffic blocked and fonts served locally. The real resume prompt comes from the app's own saved state (localStorage smartUpkeep.v1 with resume set to the Systems step), so the control strip reads the live text: Pick Up Where You Left Off · Step 3. Preview Context (injected on top of the real render): the current Warm White header (#FFFCF7), 88px at rest (56px band plus 32px skirt), the color logo (logo-band.svg) at the PR109 size of 189×47px, centered at all times, Share top left and Menu top right as 48px charcoal tap targets with 22px glyphs, a white content card with a 20px top radius overlapping the band by 24px, and the bottom bar made full width and flush to the bottom edge. Recaptured the evening of Nov 13, 2026 after photo QA: the first publish used a retired green left-logo header preview, the menu Continue Sign-Up label wrapped, and the beside-the-icons text pill could not fit once the logo was centered. The badge strip shuffles on every load, so the capture seeds the shuffle to show the same badge order on every frame. Captured at 390x844 (2x); crop QA at 360x640, no clipped UI, no crop through the indicator, 44px or more tap targets. The menu clip is frame-stepped at 24fps (tap 250ms, open 220ms ease-out, hold 1.8s, close 180ms), muted, looping, playsinline, with a poster. Nothing submitted, finished or sent. Nothing pushed to smart-upkeep.

