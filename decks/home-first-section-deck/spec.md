# Home First Section Deck

Style Swipe · Smart Upkeep · Made Nov 13, 2026

Seven questions about the top of Home and the first screen after Get Started. Today is the live site from this morning's picks. The À La Carte card also stands for the FAQ section: one pick covers both. The expanded plan-list grouping card will follow once Develop pushes the final section names on PR #105. Pick one per card, or tap Machan Decides, and use Notes for anything to tweak.

## Request
Short deck on how the first section of Home looks, plus the first sign-up screen. Today is live main e8df4a21 (PR104). Cards: video pace (today vs about 0.75x), text sizing (eyebrow, headline, price), badge carousel, Get Started bar, À La Carte and FAQ layout (grouped vs inner scroll), Did You Know on step 1, and address-and-size as one screen or split. Notes and Machan Decides on every card. The expanded And More grouping card waits for PR #105.

## Cards

### Card 1 — Video Pace
Should the Home top loop stay at today's speed, or run a little slower?
- A · Today's Speed: The live 4-scene filling-bucket loop, playing at 1x in the real phone crop.
- B · About 0.75× Speed: The same loop, retimed to about three-quarters speed. Same crop, seamless.

Notes: The loops play in the deck. Today is the live 4-scene filling-bucket r2 loop at 1x (6.3s). The slower option is the same loop retimed with ffmpeg setpts to about 0.75x (8.4s), same crop, seamless. A 0.6x option was retimed but not added as a second card; the stills from 0.75x and 0.6x did not read clearly different enough.

Machan Decides sits on the card.

### Card 2 — Text Sizing
How should the eyebrow, headline, and price line size up on Home?
- A · Today's Sizing: Preventive Home Maintenance at 30px, Starting At $139/mo at 22px, and Home Care, On Schedule at 16px (390). At 360 it is 26 / 21 / 16.
- B · Rebalanced Hierarchy: The headline is the dominant line (32px at 390, 28px at 360). The eyebrow stays clearly above the quieter price (20/16 at 390, 18/15 at 360). Still fits one screen with the dock.

Notes: Today at 390 is eyebrow 30px, price 22px, headline 16px; at 360x640 it is 26 / 21 / 16. The rebalanced set makes the headline ('Home Care, On Schedule') the dominant line, keeps the eyebrow clearly above the price, and quiets the price line. At 390: headline 32, eyebrow 20, price 16. At 360x640: 28 / 18 / 15. Both still fit one screen with the dock; See Plans keeps a 12px gap.

Machan Decides sits on the card.

### Card 3 — Badge Carousel
Should the trust badges keep today's pace and size, or run slower with slightly larger pills?
- A · Today's Marquee: The live 32-second loop with 8px gaps and today's pill size.
- B · Slower, Larger Pills: A 52-second loop with slightly larger pills and a 5px gap. It still pauses on hover and touch, and holds still under reduced motion.

Notes: Today's marquee runs in 32s with 8px gaps. The variant is slower (52s) with slightly larger pills and a 5px gap, so the stills stay unique. Under reduced motion the row stays a still, swipeable strip.

Machan Decides sits on the card.

### Card 4 — Get Started Look
Should Get Started stay the large 52px pill, or go slimmer?
- A · Today's 52px Pill: The live stacked Get Started, 52px tall, same width as the section pill, in Plus terracotta.
- B · Slimmer 44px With Arrow: The same terracotta, same width, 44px tall, a softer shadow, and a small inline arrow. The arrow guard and the 12px See Plans gap still hold.

Notes: Today is the 52px stacked Get Started pill in the Plus terracotta #A8431F. The variant is a slimmer 44px pill of the same width, a softer shadow, and an inline arrow. The PR90 arrow guard is unchanged. See Plans keeps at least a 12px gap (20px with the slimmer pill).

Machan Decides sits on the card.

### Card 5 — À La Carte And FAQ Layout
How should every À La Carte item (and the FAQ) show in place on Home?
- A · Grouped: Always-visible section headers, rows of name plus price, tap to expand. This is the default sent to Develop. The FAQ follows the same pick. Layout choice only. Section names and which items go where follow Develop's final build.
- B · Inner Scroll: The same rows and headers, in a fixed-height box that scrolls inside the section, with a fade at the bottom. Layout choice only. Section names and which items go where follow Develop's final build.

Notes: Both options show every À La Carte item in place, with no Shop À La Carte link out, and a row expands on tap. Grouped is the default already sent to Develop. The FAQ section follows this same pick: every question in place, no See All FAQs link, one open at a time. Section names used here are Develop's working names and may shift slightly when PR #105 lands: Heating And Cooling, Water And Plumbing, Roof And Outside (Drone), Inside The Home, and Records And Perks (Records And Perks has no À La Carte items today, so it is hidden). Items and prices are from the live e8df4a21 catalogs, deduped by label. PR #105 did not yet include the À La Carte build when this was rendered (head still f6a011da). Layout choice only. Section names and which items go where follow Develop's final build.

Machan Decides sits on the card.

### Card 6 — Did You Know On Step 1
Should the simplified first sign-up screen keep Did You Know off, or show the tip?
- A · Off: The simplified Where's Your Home screen with no Did You Know. This is the default sent to Develop.
- B · With The Tip: The same simplified screen, plus the live Your Home line: Every visit ends with a written report saved to your Home Record.

Notes: Both options use the simplified first screen: Share top left, logo center, Home top right; Step 1 Of 10 with a thin bar and no eyebrow; Start Over under Next; title with no icon tile and no subtitle; Street Address full width, ZIP half width with the live service-area helper; Home Size chips in a 2x3 grid with no box; a plain Stories stepper; and the live line 'Size and stories are both priced into your plan.' Spacing is 24/8. Off is the default sent to Develop. The Did You Know line is the live Your Home tip.

Machan Decides sits on the card.

### Card 7 — Address And Size
Should address, home size, and stories stay on one screen, or split into two steps?
- A · One Screen: Address, ZIP, Home Size chips, and Stories all on Step 1 Of 10. This is the default sent to Develop. At 360 the one-screen option scrolls in this mock. Develop's PR #106 fits at 360 by tightening the gaps.
- B · Split Into Two Steps: This screen is Step 1 Of 11 and only asks for the address. Home Size and Stories follow on the next step.

Notes: A is the same simplified one-screen layout as Did You Know Off (the default). B moves Home Size and Stories to a following step, so this screen is Step 1 Of 11 and only asks for the address. At 360 the one-screen option scrolls in this mock. Develop's PR #106 fits at 360 by tightening the gaps. PR #106 is Develop's build of this simplified step and was not used as the A still (this mock was captured from e8df4a21).

Machan Decides sits on the card.

## Type sizes
Today at 390: eyebrow 30px, price 22px, headline 16px. Today at 360x640: 26 / 21 / 16.
Rebalanced at 390: headline 32px, eyebrow 20px, price 16px. At 360x640: 28 / 18 / 15.
See Plans to dock gap stays 12px on both. The slimmer Get Started pill measures 44px, and the gap becomes 20px.

## Provenance
Rendered from a local unlocked archive of smart-upkeep e8df4a21, served on 127.0.0.1 with outside traffic blocked. Variants injected as CSS or overlays. Video loops retimed with ffmpeg setpts (no fps drop) from the live 4-scene filling-bucket r2 loop (video/teaser-v7-phone-4svc-fill-3x4.mp4). À La Carte rows and prices come from the live catalogs (monthlyAddonCatalog + onceAddonCatalog). Section names for that card are Develop's working names (Heating And Cooling, Water And Plumbing, Roof And Outside (Drone), Inside The Home, Records And Perks) and may shift when PR #105 lands. Step 1 mocks use live labels, the live service-area helper, and the live priced line 'Size and stories are both priced into your plan.' Crop QA at 390x844 and 360x640. Nothing submitted, paid, finished or sent.

