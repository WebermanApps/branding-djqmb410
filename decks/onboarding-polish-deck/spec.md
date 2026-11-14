# Onboarding Polish Deck

Style Swipe · Smart Upkeep · Made Nov 14, 2026

## Ask

Machan, Nov 14 2026, 8:47 PM ICT: “most of the information we ahve now is good but aesthics is lacking, overall branding and polish is lacking, and coolness”. Keep the information and change the look, for sign-up steps 1–7. The house-build band stays the hero motif; do not replace it. Do not deck work already in flight on ob-bar-1114: the bottom bar matching Home (cream #F5EDDF, hairline, shine), step transitions (24px slide plus fade, about 320ms, Back mirrored, fade-only under reduced motion), the animated progress fill, and Step 2 as two cards (Home Size and How Many Stories?) with no default on stories and Next nudging a missing answer. Cheap first, then medium. Each card is tagged cheap or medium so Develop can ship picks in stacked small PRs. Motion is transform and opacity only, 200–400ms, ease-out, with a fade for reduced motion. Never animate height, width, or top. Each step must fit one phone screen at 360×640 with the bar. Taps 44px or larger. Text contrast 4.5:1 or better. Light mode only, Khand and Hind, Title Case, no green header band. No new prices or copy claims. New art needs a source.

## Lede

Ten cards of look-only options for sign-up steps 1–7, on top of the onboarding work already in flight. The house band stays in every frame. The cream Home-matched bar, the step fade, the progress fill, and the two-card Step 2 are already coming, so they are not in this deck. The first eight cards are cheap; the last two are medium. The typography card also restyles Did You Know as a small tip chip and redraws the system and extras icons to one line weight. Pick one per card, or tap Machan Decides, and use Notes for anything to tweak.

## Cards

### 1. Hero Accent Tint · Cheap

Should each step's hero pick up a light warm tint?

- **A. Warm Tint Per Step**: The house band and the title card take a light tint from the same family as the Tailor tiles. Shown on Your Systems in Deeper Terracotta #F3E6DF.
- **B. Keep The Cream Hero**: The live cream house band and a plain title, with no per-step tint.

Cheap. The tints stay in the light warm family already used on Tailor: terracotta wash, warm sand, soft cream. Water's light lagoon wash is in that set if a later step needs it, but it is not used as a green look. The house drawing itself does not change.

### 2. Headlines And Cards · Cheap

Should the type and cards share one system?

- **A. Bigger Khand, Shared Cards, Tip Chips**: A larger Khand headline, a one-line Hind subhead, and one radius, shadow, and padding on the cards. Did You Know becomes a small tip chip, and the system and extras icons share one line weight. Shown on Your Systems.
- **B. Keep Today's Type And Cards**: The live headline size, the current card mix, the green-tinted Did You Know box, and the current icons.

Cheap. This pick also ships the tip-chip restyle and the one-line-weight icons, so those do not take their own cards. Muted helper text on this option uses #5C534C so it meets 4.5:1; the live 11px muted gray is still under that. No new claims in the subheads: Your Systems keeps “How Many Of Each”.

### 3. Selected State · Cheap

How should a picked tile feel?

- **A. Outline, Check, And A Soft Lift**: A terracotta outline, a check badge, and a 2px lift, in the same language as a selected Plans tile. Shown on Water Softener in Do You Have Any Of These?
- **B. Keep The Soft Green Fill**: The live selected tile: a light green fill and a green check, with no lift.

Cheap. The lift is a transform only. This does not change which extras are selected or what they cost. The current green fill is the thing being compared, not a new brand color.

### 4. Your Home Strip · Cheap

Should answers collect into a strip under the progress bar?

- **A. A Running Your Home Strip**: Answer chips for the address, size, stories, and systems sit under the progress bar. The latest chip is shown slightly popped in. Shown on Your Systems.
- **B. No Summary Strip**: The live progress bar only, with the house caption still carrying the size and stories line.

Cheap. The chips only repeat answers already given. Motion is transform and opacity; the row keeps a reserved height so the layout does not jump. On a 360-wide phone the chips wrap to a second line.

### 5. Pin Drop · Cheap

After the address is entered, should a pin drop and the address snap into a card?

- **A. Pin Drop, Then An Address Card**: A terracotta pin lands on the line-art map, and the street and ZIP snap into a short card. Shown on Where's Your Home? with 123 Main St, Novi 48322.
- **B. Keep The Street And ZIP Fields**: The live street and ZIP fields, already filled, with the map pins as they are today.

Cheap: it extends the existing line-art map in onboarding-house.js. The pin move is a transform; reduced motion would fade the pin and the card in. No new map art.

### 6. Stepper Motion · Cheap

When a count changes, should the stepper tick and roll the number?

- **A. A Tick And A Number Roll**: The count rolls from 1 to 2 on Furnace, and a small terracotta tick confirms the change. Transform only, 200–400ms.
- **B. Keep The Quiet Stepper**: The live plus and minus pill, with the number swapping in place and no tick.

Cheap. Reduced motion would fade the new number and skip the roll. The tick does not change the count or any price. Plus-ones already in the live UI (the +1 tag) stay as they are.

### 7. House Reacts · Cheap

Should the house band react as systems and extras are added?

- **A. Systems Light Up, Extras Orbit**: Counted systems pick up a warm glow inside the house, and extras appear as small line icons around it. Shown on Do You Have Any Of These?
- **B. Keep Today's House Band**: The live house, which already stacks floors and pops in items, with no added glow or orbiting extras.

Cheap: it extends onboarding-house.js, the same as the pin drop. The house drawing stays; this only lights what is already counted and places extras around it. Motion is transform and opacity, and the band does not change height.

### 8. Proposal Receipt · Cheap

Should Your Home Care Proposal feel like a receipt, with the total counting up?

- **A. Itemized Receipt And A Count-Up**: The breakdown sits on a lightly textured receipt card, and Due Today is a larger terracotta total that counts up. Shown with the live Plus quote for this home.
- **B. Keep The Plain Breakdown**: The live list of plan, add-ons, payment, and Due Today, on a plain card.

Cheap. The paper texture is a light pattern, not a blur. The figures are the live catalog quote for this sample home (Plus $262/mo, Irrigation +$19/mo in the plan price, Due Today $262). The count-up is a number roll on that same total, not a new price. Reduced motion would fade the total in.

### 9. Monthly Delta Pill · Medium

On Tailor Your Plan, should a live monthly delta tick as add-ons change?

- **A. A Live Monthly Delta Pill**: A pill under the title shows the live add-on monthly total, here +$19/mo for Irrigation, and ticks when the amount changes.
- **B. Keep The Note Under The List**: The live “Your add-ons: +$19/mo” line under the list, with no pill by the title.

Medium. The amount is the live add-on total from the current catalog, not a new price. The pill only restates that figure closer to the title. The tick is a transform; reduced motion fades the new amount.

### 10. Swipeable Plan Cards · Medium

Should Your Plan use swipeable cards like the Home Plans tiles?

- **A. Swipeable Plan Cards**: Essentials, Plus, and Complete sit in a horizontal snap row, with the selected Plus card lit, outlined, and slightly lifted, and the neighbors peeking. Tap-to-expand stays on the selected card.
- **B. Keep The Stacked Plan Cards**: The live vertical stack, with the selected Plus card expanded in place and the others listed below.

Medium. This reuses the Home Plans tile language (lit, outline, lift) and existing plan names and prices. The swipe is a scroll, not a layout animation. The selected card keeps its current detail; opening it does not animate height, width, or top.

## Provenance

Frames are a local render of smart-upkeep at 6257bc6a854e20d2066dd63b850831424178ac1f, taken from a git archive of the ob-bar-1114 clone's HEAD, with that clone's then-uncommitted bar and Step 2 two-card work copied into the render tree only. The clone itself was not modified, and nothing was pushed to smart-upkeep. The archive passed a pagelock unlock in a private mode-700 folder, served on 127.0.0.1 with outside traffic blocked and fonts served locally. Art is 390×844 at 2×, full frame, no crop. Fit was checked at 360×640, 390×660 and 430×746: the step itself does not overflow, taps stay at least 44px, and a 36px leftover on the document scroll is present on the baseline too (page chrome, not the step). Variants only add CSS and a few local DOM marks in that session (the pin, the Your Home chips, the orbit icons, the delta pill, the stepper roll). Prices come from pricing-config.js through the live catalog code, so no price was typed by hand. Shown figures such as Plus $262/mo, Irrigation +$19/mo, and Due Today $262 are the live quote for this sample home (123 Main St, 48322, Under 2,000, 2 Stories, one of each system, Irrigation selected). Muted labels use #5C534C on the typography option so body text meets 4.5:1; the live 11px muted gray at 3.82 is called out on that card. No green header band. Gold is not used.
