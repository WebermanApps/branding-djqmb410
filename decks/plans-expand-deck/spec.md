# Plans Expand Deck

Style Swipe · Smart Upkeep · Made Nov 13, 2026

Four cards on the Home Plans section: how much of Plus peeks beside Essentials, how the And More sheet opens, how it closes, and how many lines show on the closed Essentials tile. Every option shows the tile closed and the full-screen sheet open, plus a short clip of the open and close. Pick one per card, or tap Machan Decides, and use Notes for anything to tweak.

## Requested
Machan, Nov 13, 7:38 PM ICT: in the deck that they are preparing I want to see both what it looks like unexpanded and expanded. Build a short Plans Expand Deck from Develop’s Plans PR: Essentials first with Plus peeking, his new 8-line Essentials order, and gutter cleaning plus fridge filters now in Essentials. For each option, show both the unexpanded tile and the full-screen expanded And More state, plus a short clip of the open and close.

## Provenance
Frames are a local render of smart-upkeep branch plans-expand-1113, head de99a1958704bd2f7bb45e5996372dd3a4221728 (cache h99u), from a git archive into a mode-700 folder. Pagelock check exited 0 on the locked tree. Unlock was used only on the local QA copy, served on 127.0.0.1 with outside traffic blocked. Crop QA at 390×844 and 360×640. Motion loops are 20fps sequences encoded to muted, playsinline, looping MP4 under 1.5MB, with a 780×1688 poster. Preview URL toggles only; content is fixed. And More and close were used in the local copy; Get Started, Finish, and Send my picks were never pressed. Nothing was pushed to smart-upkeep. Built Nov 13, 2026.

## Cards

### Card 1 — Plus Peek
How much of Plus should peek beside Essentials?
- A · 22% Peek: About 22% of the Plus tile shows at the right edge at 390, with Essentials first and fully on screen.
- B · 32% Peek: About 32% of the Plus tile shows at the right edge at 390, so more of Plus is in view.

Notes: Plan copy is fixed, not a pick: Essentials uses Machan’s eight lines in this order — Furnace/AC Tune-Up, Water Heater Flush/Descale, Appliance Filter Cleaning/Changes, Gutter Cleaning, Mold And Moisture Scan, Roof Inspections, Dryer Vent Cleaning, and Sump Pump Test — then And More. Gutter cleaning and fridge filters are in Essentials. Plus reads 4 Seasonal Visits A Year, Roof Drone Inspection Twice A Year, Garage Door Tune-Up, and Salt in Water Softener. Prices are unchanged. Every option shows the unexpanded tile, the full-screen And More sheet, and a short looping clip of the open and close. A is the default when there is no preview param.

Machan Decides sits on the card.

### Card 2 — How The Sheet Opens
Should the And More sheet grow out of the tile, or rise from the bottom?
- A · Grow From The Tile: The full-screen sheet grows out of the Essentials tile (a 340ms FLIP clip-path) and collapses back into it.
- B · Rise From The Bottom: The same full-screen sheet rises from the bottom of the phone, and slides back down to close.

Notes: Plan copy is fixed, not a pick: Essentials uses Machan’s eight lines in this order — Furnace/AC Tune-Up, Water Heater Flush/Descale, Appliance Filter Cleaning/Changes, Gutter Cleaning, Mold And Moisture Scan, Roof Inspections, Dryer Vent Cleaning, and Sump Pump Test — then And More. Gutter cleaning and fridge filters are in Essentials. Plus reads 4 Seasonal Visits A Year, Roof Drone Inspection Twice A Year, Garage Door Tune-Up, and Salt in Water Softener. Prices are unchanged. Every option shows the unexpanded tile, the full-screen And More sheet, and a short looping clip of the open and close. A is the default when there is no preview param. The clip and the Opening still are the difference; the closed tile and the settled sheet match.

Machan Decides sits on the card.

### Card 3 — How To Close
Should close be an X at the top right only, or an X plus a Close pill at the bottom?
- A · X At The Top Right: The sheet closes with the X at the top right only.
- B · X And Close Pill: The same X at the top right, plus a gloss Close pill under Get Started With Essentials.

Notes: Plan copy is fixed, not a pick: Essentials uses Machan’s eight lines in this order — Furnace/AC Tune-Up, Water Heater Flush/Descale, Appliance Filter Cleaning/Changes, Gutter Cleaning, Mold And Moisture Scan, Roof Inspections, Dryer Vent Cleaning, and Sump Pump Test — then And More. Gutter cleaning and fridge filters are in Essentials. Plus reads 4 Seasonal Visits A Year, Roof Drone Inspection Twice A Year, Garage Door Tune-Up, and Salt in Water Softener. Prices are unchanged. Every option shows the unexpanded tile, the full-screen And More sheet, and a short looping clip of the open and close. A is the default when there is no preview param.

Machan Decides sits on the card.

### Card 4 — Collapsed Lines
How many Essentials lines should show on the closed tile?
- A · 6 Lines: The closed Essentials tile shows six lines, then And More. This count holds on one screen at both 390 and 360.
- B · 8 Lines — Trims At 360: Eight lines hold on one screen at 390, including Sump Pump Test. At 360 the list is trimmed to seven so the section stays on one screen. Marked because eight lines are not valid at 360.

Notes: Plan copy is fixed, not a pick: Essentials uses Machan’s eight lines in this order — Furnace/AC Tune-Up, Water Heater Flush/Descale, Appliance Filter Cleaning/Changes, Gutter Cleaning, Mold And Moisture Scan, Roof Inspections, Dryer Vent Cleaning, and Sump Pump Test — then And More. Gutter cleaning and fridge filters are in Essentials. Plus reads 4 Seasonal Visits A Year, Roof Drone Inspection Twice A Year, Garage Door Tune-Up, and Salt in Water Softener. Prices are unchanged. Every option shows the unexpanded tile, the full-screen And More sheet, and a short looping clip of the open and close. A is the default when there is no preview param. Marked: lines=8 is valid only if it still fits one screen at 360. In this build it does not — the tile is trimmed from eight lines to seven (Sump Pump Test drops) so the section stays on one screen. Six lines hold at both sizes. The 360 unexpanded frame is shown on B so you can see the trim.

Machan Decides sits on the card.

## QA Notes For This Head
Head de99a195, cache h99u. No clipping at 360 or 390 on the closed Plans section. Peek measured 22.3% vs 32.1% at 390, and 22.5% vs 32.3% at 360. Open and close completed; no console errors and no outside requests. Motion (340ms) looked smooth in the 20fps loops. lines=8 shows eight lines on one screen at 390, but at 360 the build trims the list to seven so the section stays on one screen. The expanded sheet list scrolls under Also Included; the footer stays put. Get Started was never pressed.

