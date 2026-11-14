# Home FAQ Section Look Deck

Style Swipe · Smart Upkeep · Made Nov 14, 2026

## Ask

Machan, Nov 14 2026 ICT, in UpKeep Develop's chat. 10:17 AM: “there was confusion on the faq look deck” / “so i submitted with one note” / “the design is supposed to be carousel by section, not question”. 9:28–9:36 AM: FAQ sections in order: Plans And Visits (6 pinned: What's Included And How Many Do I Get?, What Do You Do On A Visit?, What Does A Plan Cost?, What's In My Visit Report?, What Is The Founding 50 Offer?, Is Smart Upkeep A Home Warranty Or Insurance?), Our Team And Coverage, Billing, Cancel And Moving, and Heating, Cooling And Furnace Filters; the other sections stay as they are. 9:13 AM: “i think in FAQ we could do that too, carousel cards”; “basically plans, tailor your plan, and faq will all be similar style”. Replaces the Home FAQ Look Deck, which was built one card per question by mistake.

## Lede

Five cards on the Home FAQ the way you meant it: one carousel card per section, with that section's questions inside. Built on draft PR #126 in your section order, with your 6 Plans And Visits questions first. Each pair changes one thing: how a question opens, where the section name sits, the pager, how much of the next card peeks in, and card color. The questions and answers are the Legal-approved text word for word. Pick one per card, or tap Machan Decides, and use Notes for anything to tweak.

## Cards

### 1. Opening A Question

How should a question open inside a section card?

- **A. Opens In Place**: Tap a question and its answer opens right under it, inside the card. The questions below slide down.
- **B. Opens In A Sheet**: Tap a question and its answer slides up in a sheet above the tabs. The card keeps its full question list.

Shown on Plans And Visits, section 1 of 6, with What's Included And How Many Do I Get? open. Your 6 pinned questions lead in your order, and the other 5 Plans And Visits questions follow them. Rows that don't fit scroll inside the card, and the “+ More Questions” line marks them in the mock. Opens In Place shows 4 questions with the answer open. Opens In A Sheet keeps 8 questions in the card, 5 of them above the sheet. The sheet stops at the tabs, so Get Started stays on screen, and it closes with the X or a swipe down. The other four cards in this deck use Opens In Place.

### 2. Section Title

Where should the section name sit?

- **A. On The Card**: The section icon, name and question count sit at the top of each card.
- **B. Header Above The Cards**: The section name and count sit above the carousel and change as you swipe, so each card starts with its first question.

Shown on Our Team And Coverage, section 2 of 6, with How Are Techs Vetted And Trained? open. Header Above The Cards drops the section name under the card so it isn't shown twice, and the card starts 42px lower. The icons are the live section icons from the site icon set. No new icons were drawn.

### 3. Pager

How should the FAQ show which section you're on?

- **A. Section Counter**: The section name and a count like 3 / 6 sit under the card, like the draft's counter.
- **B. Progress Bar**: Six short bars, one per section. Done sections turn light terracotta, the current one is filled, and its name sits under the bars.

Shown on Billing, Cancel And Moving, section 3 of 6, with Can I Cancel? open. The draft has 6 sections and 37 questions: Plans And Visits 11, Our Team And Coverage 3, Billing, Cancel And Moving 6, Heating, Cooling And Furnace Filters 7, Safety Checks 4, and Water, Gutters And Michigan Winters 6. Billing runs Cancel, Refunds, Pause, Move, Is There a Cancellation Right in Michigan?, then Card Info, as in the draft. Section-name chips were left out, because six section names don't fit across 390px without cutting the last chip off. Gold is not used.

### 4. Peek

How much of the next section card should peek in?

- **A. Slim Peek**: About 39px of the next card shows, so the questions get more width and wrap less.
- **B. Wide Peek**: About 93px of the next card shows, as in the draft, so it's clearer you can swipe.

Shown on Heating, Cooling And Furnace Filters, section 4 of 6, with What Happens During A Furnace Tune-Up? open. Slim Peek makes the card 326px wide, and Wide Peek keeps the draft's 272px. With the answer open, Slim fits 4 of the 7 questions, and Wide fits 3. The other cards in this deck use Wide Peek.

### 5. Card Color

Which color should the section cards be?

- **A. White Card**: A white card with a light hairline on the cream section.
- **B. Warm Tint Card**: The whole card uses the warm tint you already approved for open answers on the FAQ.

Shown on Billing, Cancel And Moving, with What Happens If I Move? open. Warm Tint Card uses #F7EBE5, the open-answer tint from your FAQ Rich Look Deck pick, with a white icon tile so the icon still stands out. The other cards in this deck use the draft's light cream #FFF8EE.

## Provenance

Frames are a local render of smart-upkeep draft PR #126 r4 head bbc354b47d9e66f8296f05c1d8ce5dd61afc283a (cache h9m8), off main e1b76db3, from a git archive that passed the pagelock check and was unlocked only in a local copy, served on 127.0.0.1 with outside traffic blocked (0 outside requests) and fonts served locally. 390×844 at 2×, full frame, no crop. The section-card layout is a mock: in that local copy the head's 37 rendered FAQ cards are regrouped into one card per section, in the head's own order, with CSS and small DOM changes only. Nothing was pushed to smart-upkeep, and nothing was submitted, paid or sent. Every question title and answer is the text the head renders on Home (the Legal-approved Home FAQ copy at bbc354b4), copied from the page, not retyped. Employees, License and Liability stay hidden, as in the head. The “+ N More Questions” line at the bottom of a long card is a mock marker for the rows that scroll inside the card; it is not FAQ copy. The header is the PR's centered logo with Share top left and the menu top right, and the dock keeps the 48px tabs with the 44px Get Started under them on every frame. Every frame is top-aligned: the card in view and its neighbor start at the same height, the card runs down to the pager, and nothing from another section peeks in. The only text cut off at an edge is the peeking neighbor card, which is how the carousel works.
