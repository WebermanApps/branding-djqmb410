# Tailor Your Plan Look Deck

Style Swipe · Smart Upkeep · Made Nov 14, 2026

## Ask

Machan, Nov 14 2026 ICT, in UpKeep Develop's chat. 9:13 AM: “for tailor your plan we could get rid of the black and white pills and just have a carousel that has one card per section”; “i think in FAQ we could do that too, carousel cards for questions”; “basically plans, tailor your plan, and faq will all be similar style”; 9:14 AM: “it doesn't ahve to share the exact same style”, “i'm just saying that plans are carousel right now”. 9:13 AM: “when you are on "tailor your plan" you can still see FAQ header”. 9:28 AM: “lets try to shorten answers when possible”. 9:28–9:36 AM: FAQ categories in order: Plans And Visits (6), Our Team And Coverage, Billing, Cancel And Moving, and Heating, Cooling And Furnace Filters; the other categories stay as they are. 9:44 AM: “i made some suggestions on how the faq should look and how the tailor your plan should look” / “do you want to make decks based on my suggestions”.

## Lede

Five cards on the new Tailor Your Plan carousel from draft PR #126: the black and white pills are gone, with one card for each section. The section fills the space down to the bar, so the FAQ header no longer shows. Each pair changes one thing: row spacing, how prices show, section icons, how plan add-ons and one-time add-ons are told apart, and the section header. Pick one per card, or tap Machan Decides, and use Notes for anything to tweak.

## Cards

### 1. Row Spacing

How roomy should the service rows be?

- **A. Compact Rows**: Name, add-on type and price on tight rows that are still easy to tap.
- **B. Roomy Rows With A Line**: Each row adds its one-line description from the live price list.

Shown on Inside The Home: Radon Test $100, Bath Fans Clean And Check $95, Video Doorbell Install Quote, Appliance Deep Clean Quote. Compact rows are at least 44px tall. The descriptions in Roomy are the live catalog lines, word for word. The draft's rows were very loose with neither, and a short section left a big empty area at the bottom of the card.

### 2. Price Style

How should prices show?

- **A. Price Pills**: Terracotta pills, with outlined Quote pills, as in the draft.
- **B. Right-Aligned Price**: Plain price text on the right in Khand, with Quote in terracotta.

Shown on Heating And Cooling: Chimney Sweep $255/yr Plan Add-On, Furnace Tune-Up Quote, AC Tune-Up Quote, Chimney Sweep $255 One-Time Add-On, Smart Thermostat Install $175. Chimney Sweep shows twice because it is in both the plan add-on list and the one-time list. That was already true before this PR, and it is left as is here. Generator Annual Service in Seasonal Equipment shows twice for the same reason.

### 3. Section Icons

Should each section card have an icon?

- **A. Section Icon**: The live line icon sits beside the section name, as in the draft.
- **B. No Icon**: Just the section name in the header.

Shown on Seasonal Equipment, the last of five sections, so the card before it peeks in from the left. The icons are the live terracotta line icons the draft already uses for each section. No new icons were drawn.

### 4. Add-On Labels

How should plan add-ons and one-time add-ons be told apart?

- **A. Tag On Each Row**: Plan Add-On or One-Time Add-On under every name, as in the draft.
- **B. Two Sub-Headers**: Plan Add-Ons first, then One-Time Add-Ons, with no tag on each row.

Shown on Water And Plumbing: Irrigation System +$19/mo is the plan add-on, and the other five are one-time add-ons. The sub-headers use the same wording as the tags, in terracotta Khand. Both options keep the same rows and prices.

### 5. Section Header

Which section header style should the cards use?

- **A. Header Band**: The section name and icon in a light cream band at the top of the card, as in the draft.
- **B. Title With A Rule**: A larger section name on the card with a thin terracotta line under it.

Shown on Roof And Outside. Neither header is green, and the band is cream #FCF9F4 with a light hairline. Prices and labels are unchanged: Flat Roof Inspection And Clean Quote, Exterior Window Washing Needs A Site Visit, Extra Gutter Cleaning $180–$360.

## Provenance

Frames are a local render of smart-upkeep draft PR #126 head 496c08865b4c9b90d7d5844dd9d06f8e708582d8 (cache h9m2), off main e1b76db3, from a git archive that passed the pagelock check and was unlocked only in a local copy, served on 127.0.0.1 with outside traffic blocked and fonts served locally. 390×844 at 2×, full frame, no crop. Variants only add CSS and small DOM changes in that local copy. Nothing was pushed to smart-upkeep, and nothing was submitted, paid or sent. The header is the PR's centered logo with Share top left and the menu top right. The Get Started button under the four tabs is shown on every frame, as Machan asked at 9:12 AM. Prices come from the PR's pricing-config.js through the live catalog code, so no price was typed by hand. In the FAQ frames, the Home-only short answers and titles in the draft were switched off, so every question and answer is the FAQ_ALL text word for word. Legal is still reviewing the short answers. The seven cards the PR holds back for Machan and Legal stay hidden. The only text cut off at an edge is the peeking card next to the one in view, which is how the carousel works.
