# Hero Look Deck

Style Swipe · Smart Upkeep · Made Nov 13, 2026

Six cards on the Home hero: the one screen between the Warm White header and the flush bottom bar. Every option keeps the video, Preventive Home Maintenance, Starting At $139/mo, the badges, See Plans, and Home Care, On Schedule. Pick one per card, or tap Machan Decides, and use Notes for anything to tweak.

## Requested
Machan, Nov 13, 2026: I just don't 100% love the way this looks and I'm open to any ideas. I want to sell as much info as I can on this slide but it MUST MUST MUST look crisp clean. Must keep a video, Preventive Home Maintenance, Starting At $139/mo, the badges, the See Plans down arrow, and almost certainly Home Care, On Schedule. Try taglines built into the video, moving the tagline, little check marks inside the graphic (real plan service lines only), and other layout and hierarchy options. If any option has an expanding part, show it unexpanded and expanded, plus a short clip of the open and close.

## Provenance
Frames are a local render of smart-upkeep main 08c9fa56690eb99ba4f1d5debfef2b951ebf0c74 (PR #108 merge, live on smartupkeep.ai), from a git archive whose pagelock check exited 0, unlocked only in a mode-700 QA copy, served on 127.0.0.1 with outside traffic blocked and Khand and Hind served locally. The header in every frame is a preview of the coming Home header (Machan, Nov 13, 7:46 PM ICT): the logo stays centered at all times, Share is top left, and the menu is top right, at the same size and band height. The band is Warm White with the brand-color logo; green stays off the band. Stills freeze a real frame of teaser-v7-phone-4svc-fill-3x4.mp4 (the live phone loop). Clips are frame-stepped at 20 fps, muted, looping, playsinline, under 1.5MB, with a poster. Service lines are the seven Essentials lines from live app.js ESSENTIALS_LINES (Machan Nov 13 9:07 AM); nothing was invented. Tagline-in-video and service checks are page overlays on the live loop, not a baked re-render. Crop QA at 390×844 and 360×640. One phone screen. Nothing submitted, finished or sent. Nothing pushed to smart-upkeep.

## Cards

### Card 1 — Type Hierarchy
Should the tagline stay the big line, or should the eyebrow lead?
- A · Tagline Leads (Live): The live scale: Home Care, On Schedule at 32px Khand, Preventive Home Maintenance at 20px, and Starting At $139/mo at 16px in terracotta.
- B · Eyebrow Leads: Preventive Home Maintenance at 30px Khand, Starting At $139/mo at 22px, and Home Care, On Schedule at 16px Hind — a quieter tagline and a stronger price.

Notes: This is the one type-scale question. Everything stays in the same place. The live scale was the Home First Section pick; this is a fresh look at it.

Machan Decides sits on the card.

### Card 2 — Tagline Placement
Where should Home Care, On Schedule sit?
- A · Under The Price (Live): The tagline stays in the type stack, directly under Starting At $139/mo, at the live 32px size.
- B · Above See Plans: The same tagline, at the same size, moves under the badges and sits just above the See Plans arrow.

Notes: Placement only; the type scale stays the live one. At 360 the video shortens a little so See Plans and Get Started still fit on one screen.

Machan Decides sits on the card.

### Card 3 — Tagline In The Video
Should the tagline stay typeset on the page, or be built into the video?
- A · Typeset On The Page (Live): Home Care, On Schedule stays in the type stack under the price, as it is live.
- B · Built Into The Video: The tagline sits in the upper empty field of the loop. The page stack is Preventive Home Maintenance and Starting At $139/mo. A short clip plays the loop with the tagline in place.

Notes: B is a mock: Home Care, On Schedule is typeset over the upper empty field of the live loop, in Khand Bold, charcoal #1A1A1A. The page stack keeps Preventive Home Maintenance and Starting At $139/mo; the tagline is no longer under the price. Re-render for Video & Photo, if this wins: paint Home Care, On Schedule in Khand Bold, charcoal #1A1A1A, into the upper empty field of teaser-v7-phone-4svc-fill-3x4.mp4, on every scene, with no other copy and no logo, and leave the lower empty floor clear for the page type fade.

Machan Decides sits on the card.

### Card 4 — Service Checks
Should the video show always-on service checks, or a list that opens?
- A · Always-On Checks: Three real Essentials lines stay on a cream plate in the video: Water Heater Flush, Furnace/AC Tune-Up, Dryer Vent Cleaning. A short clip plays the loop with the checks in place.
- B · Opening List: Two Essentials lines plus And More, opening to all seven Essentials lines. The card shows the unexpanded state, the expanded state, and a short open-and-close clip.

Notes: A keeps three always-on checks on a cream plate in the upper left of the video, under the play badge: Water Heater Flush, Furnace/AC Tune-Up, Dryer Vent Cleaning. Those are real Essentials lines. B starts with Furnace/AC Tune-Up and Water Heater Flush plus And More, then opens to all seven Essentials lines: Furnace/AC Tune-Up, Water Heater Flush, Furnace Filter Check And Change, Roof Drone Inspection, Mold And Moisture Scan, Dryer Vent Cleaning, Sump Pump Test. Unexpanded and expanded stills sit on the card, and a short clip shows the open and close. B should stay a page overlay so it can open; do not bake it into the loop. If A wins, Video & Photo can optionally bake those three checks, Essentials green ticks, cream plate, clear of the play badge, into the same loop.

Machan Decides sits on the card.

### Card 5 — Badge Layout
Should the badges keep scrolling, or should all six sit in a wrap?
- A · Scrolling Row (Live): The live one-row carousel, with the edge fade. A short clip shows the badges moving.
- B · All Six Wrapped: All six badges wrap in place, with no edge fade and no motion, so every label is fully visible.

Notes: The badge words are unchanged. The wrap sits under the type stack and still leaves room for See Plans at 360 and 390.

Machan Decides sits on the card.

### Card 6 — Type And Video
Should the type sit on the video fade, or fully below the video?
- A · On The Video Floor (Live): The live treatment: the type starts on the empty floor of the video, with a short fade.
- B · Below The Video: The type sits fully below a slightly shorter video, on the page, with no fade over the loop.

Notes: All of the same lines stay; only the overlap changes. The shorter video keeps See Plans and the bar on one screen at 360 and 390.

Machan Decides sits on the card.

## Re-render Spec (Video & Photo)
Only if the matching option wins. These deck frames are overlays on the live loop, not a baked re-render.

### Tagline In The Video (card 3 B)
Paint Home Care, On Schedule in Khand Bold, charcoal #1A1A1A, into the upper empty field of teaser-v7-phone-4svc-fill-3x4.mp4, on every scene. No other copy, no logo. Leave the lower empty floor clear for the page type fade.

### Always-On Checks (card 4 A, optional)
Bake these three real Essentials lines, with Essentials green #0B6E4F ticks, on a soft cream plate, into the upper left of the same loop, clear of the play badge: Water Heater Flush, Furnace/AC Tune-Up, Dryer Vent Cleaning.

### Opening List (card 4 B)
Do not bake this into the loop. It must stay a page overlay so it can open and close. The seven Essentials lines are: Furnace/AC Tune-Up, Water Heater Flush, Furnace Filter Check And Change, Roof Drone Inspection, Mold And Moisture Scan, Dryer Vent Cleaning, Sump Pump Test.

