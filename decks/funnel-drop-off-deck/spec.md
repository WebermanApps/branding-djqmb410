# Funnel Drop-Off Deck

Style Swipe · Smart Upkeep · Made Nov 12, 2026

Four questions about friction in the sign-up flow: what happens if they press Back, when Your Details checks the fields, whether the fields tell the browser to autofill, and whether Plus starts selected. Pictures are real funnel screens at 390px, on the latest stack. Pick one per card, or tap Machan Decides, and use Notes for anything to tweak.

## Request
Sign-up friction that can lose people mid-flow. Built from real post-#94 funnel screens (Your Plan, Your Details, and a mid-funnel step plus the browser chrome), on the latest Home and funnel stack (PR96 four-tab bar plus Get Started, boxless Share, no See What's Included on plan tiles, one-screen phone fit, Home Care, On Schedule; PR97 one-screen funnel). Not a 10-card Your Details redo, and not a remake of Where's Your Home or Sign-Up Fit. Validation errors are Legal-approved: “Enter a 10-digit U.S. phone number.” and “Enter an email address, like name@example.com.” Legal: the tagline is not paired with a promise of timing or a set arrival time.

## Cards

### Card 1 — Browser Back Mid-Funnel
If they press the browser Back button in the middle of sign-up, what should happen?
- A · Previous Step, Picks Kept: Browser Back goes to the previous funnel step and keeps their answers.
- B · Leave The Funnel (Today): Browser Back can leave the funnel (today: no history entries for steps).

Notes: These pictures use the latest stack: Get Started, boxless Share, no See What's Included on the plan tiles, one-screen phone fit, and Home Care, On Schedule. The tagline is not paired with a promise of timing or a set arrival time. This is not a remake of Where's Your Home or Sign-Up Fit. Option A is the previous step with their address and size picks kept. Option B is today's Home page.

Machan Decides sits on the card.

### Card 2 — Your Details Validation
When should Your Details check the name, phone, and email?
- A · Check On Blur: When a field is left, it checks in place. Email is checked for shape. A US phone is auto-formatted as (XXX) XXX-XXXX as they type, and it must be 10 digits.
- B · Check On Next, Errors At The Top: Fields are not checked until Next. Errors are listed in one block at the top of the card.

Notes: These pictures use the latest stack: Get Started, boxless Share, no See What's Included on the plan tiles, one-screen phone fit, and Home Care, On Schedule. The tagline is not paired with a promise of timing or a set arrival time. This is not a remake of Where's Your Home or Sign-Up Fit. Error lines are Legal-approved: “Enter a 10-digit U.S. phone number.” and “Enter an email address, like name@example.com.” Today's shorter lines are also approved. Field order, compact fields, the highlighted address, and Have A Code? stay as they are.

Machan Decides sits on the card.

### Card 3 — Autofill Hints
Should the sign-up fields tell the browser what to autofill?
- A · Use Autofill (Today): Autocomplete is already set to name, tel, email, postal-code, and address-line1.
- B · Plain Fields: The same fields, with autocomplete off.

Notes: These pictures use the latest stack: Get Started, boxless Share, no See What's Included on the plan tiles, one-screen phone fit, and Home Care, On Schedule. The tagline is not paired with a promise of timing or a set arrival time. This is not a remake of Where's Your Home or Sign-Up Fit. Near no-brainer; Machan Decides is enough. No new customer-facing copy. Option A shows a mock browser suggestion list so the behavior is visible.

Machan Decides sits on the card.

### Card 4 — Plan Default
When they reach Your Plan, should a plan already be picked?
- A · Plus Is Pre-Selected (Today): Plus is selected and marked Most Popular. Home uses the same recommended default.
- B · Nothing Selected: All three plans are unselected until they tap one. Next stays unready until a plan is picked.

Notes: These pictures use the latest stack: Get Started, boxless Share, no See What's Included on the plan tiles, one-screen phone fit, and Home Care, On Schedule. The tagline is not paired with a promise of timing or a set arrival time. This is not a remake of Where's Your Home or Sign-Up Fit. Plan colors, prices, key-point lines, and the Most Popular ribbon stay as they are. Only the empty vs Plus default is in question.

Machan Decides sits on the card.

## Provenance
Real funnel and Home screens from a local unlocked merge of Develop PR96 (428f746, Home section bar) and PR97 (27afbc5, one-screen funnel), served on 127.0.0.1 with every external request aborted (Google Fonts CSS answered locally with Khand and Hind; no analytics). Headless Chromium at 390x844 (deck images, dsf 2, 780x1688 JPEG q90) and 360x844 (crop QA), prefers-reduced-motion. Fictional sample person: Jordan Lee, 142 Maple Street, Novi, 48375. Nothing was submitted, paid, finished or sent.

