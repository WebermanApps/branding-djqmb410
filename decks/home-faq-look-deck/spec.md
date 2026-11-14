# Home FAQ Look Deck

Style Swipe · Smart Upkeep · Made Nov 14, 2026

## Ask

Machan, Nov 14 2026 ICT, in UpKeep Develop's chat. 9:13 AM: “for tailor your plan we could get rid of the black and white pills and just have a carousel that has one card per section”; “i think in FAQ we could do that too, carousel cards for questions”; “basically plans, tailor your plan, and faq will all be similar style”; 9:14 AM: “it doesn't ahve to share the exact same style”, “i'm just saying that plans are carousel right now”. 9:13 AM: “when you are on "tailor your plan" you can still see FAQ header”. 9:28 AM: “lets try to shorten answers when possible”. 9:28–9:36 AM: FAQ categories in order: Plans And Visits (6), Our Team And Coverage, Billing, Cancel And Moving, and Heating, Cooling And Furnace Filters; the other categories stay as they are. 9:44 AM: “i made some suggestions on how the faq should look and how the tailor your plan should look” / “do you want to make decks based on my suggestions”.

## Lede

Six cards on the new Home FAQ carousel from draft PR #126: one card per question, in your new category order. Each pair changes one thing: card height, where the category shows, the pager, how much of the next card peeks in, how a card starts, and card color. Every frame keeps the cards top-aligned, so the next card's top lines up with the one in view, and the questions and answers are the FAQ text word for word. Pick one per card, or tap Machan Decides, and use Notes for anything to tweak.

## Cards

### 1. Card Height

How tall should each FAQ card be?

- **A. Fits Its Answer**: The card hugs its answer and the counter sits right under it. Leftover room sits below, above the bar.
- **B. One Height For All**: Every card fills the panel, so cards never change size. Short answers leave room inside the card.

Shown on a short answer, Is Smart Upkeep a Home Warranty or Insurance?, card 6 of 33. In the draft the card was centered with a big gap above and below, and the next card sat lower. Both options fix that by lining the cards up at the top. Fits Its Answer moves the empty room below the counter. One Height For All keeps it inside the card, and a long answer like What Should I Do In An Emergency? scrolls inside its card. The other five cards in this deck use Fits Its Answer.

### 2. Category

Where should the category name show?

- **A. Chip On The Card**: A small terracotta chip with the topic icon sits on top of every card.
- **B. Header Above The Cards**: The category name and the place in it, like 2 / 3, sit above the carousel and change as you swipe.

Shown on Where Do You Work?, in Our Team And Coverage. The chip uses the warm tint #F7EBE5 with terracotta #A8431F text. Header Above The Cards takes the category off each card and drops the duplicate category line under the card, so the card starts with the question. Tabs across the top were left out, because seven category names don't fit across 390px without cutting the last one off.

### 3. Pager

How should the FAQ show where you are?

- **A. Counter**: The category name and a count like 19 / 33 sit under the card, as in the draft.
- **B. Category Progress**: One short bar for each category. The current bar fills as you swipe, with Billing, Cancel And Moving · 5 / 5 under it.

Shown on Is There a Cancellation Right in Michigan?, the last of five in Billing, Cancel And Moving. The draft's first build had a row of 32 dots that ran off the edge, and the counter replaced it. A dot row capped at about 7 is another way to do it, if neither of these is right. Bars that are done turn a light terracotta, and the current one fills terracotta. Gold is not used.

### 4. Peek

How much of the next card should peek in?

- **A. Slim Peek**: About 10% of the next card shows, so the answer gets more width and fewer lines.
- **B. Wide Peek**: About 22% of the next card shows, as in the draft, so it is clearer that you can swipe.

Shown on a long answer, What Do You Do on a Visit?, card 2 of 33. Slim Peek makes the card 331px wide and Wide Peek makes it 298px. The answer is the FAQ text word for word, and it fits without scrolling on both.

### 5. Card Top

How should each card start?

- **A. Question First**: The category chip, then the question in Khand, with no icon beside it.
- **B. Icon And Question**: The live topic icon sits in a small warm tile beside the question.

Shown on How Often Should I Change My Furnace Filter?, in Heating, Cooling And Furnace Filters. Icon And Question uses the section's live furnace icon from the site icon set, in a 40px tile tinted #F7EBE5. No new icons were drawn.

### 6. Card Color

Which card color should the FAQ use?

- **A. White Card**: A white card with a light hairline on the cream section.
- **B. Warm Tint Card**: The whole card uses the warm tint you already approved for open answers on the FAQ.

Shown on Who Sees Photos From My Visits?. Warm Tint Card uses #F7EBE5, the open-answer tint from your FAQ Rich Look Deck pick, with a white category chip so the chip still stands out. The other cards in this deck use the draft's light cream #FFF8EE.

## Provenance

Frames are a local render of smart-upkeep draft PR #126 head 496c08865b4c9b90d7d5844dd9d06f8e708582d8 (cache h9m2), off main e1b76db3, from a git archive that passed the pagelock check and was unlocked only in a local copy, served on 127.0.0.1 with outside traffic blocked and fonts served locally. 390×844 at 2×, full frame, no crop. Variants only add CSS and small DOM changes in that local copy. Nothing was pushed to smart-upkeep, and nothing was submitted, paid or sent. The header is the PR's centered logo with Share top left and the menu top right. The Get Started button under the four tabs is shown on every frame, as Machan asked at 9:12 AM. Prices come from the PR's pricing-config.js through the live catalog code, so no price was typed by hand. In the FAQ frames, the Home-only short answers and titles in the draft were switched off, so every question and answer is the FAQ_ALL text word for word. Legal is still reviewing the short answers. The seven cards the PR holds back for Machan and Legal stay hidden. The only text cut off at an edge is the peeking card next to the one in view, which is how the carousel works.
