# Onboarding Map Crop Deck

Style Swipe · Smart Upkeep · Made Nov 14, 2026

## Ask

Machan, Nov 14 2026, 9:16 AM ICT: “for the step 1, the map photo is why too small, i feel like we could almost double the size, we can show more of michigan”. Draft PR #128 doubled the map band to 240px and drew the whole state, which made Wayne, Oakland and Macomb tiny and dropped their labels. Machan's standing rule: any crop question goes to him as a swipe deck. Map B Line-Art With Pin Dots stays; Wayne, Oakland and Macomb only, labeled.

## Lede

Three quick cards on how to crop the bigger Step 1 map in onboarding. Each card puts two of the three crops side by side: Southeast Michigan, the Lower Peninsula, and the Whole State With An Inset. All three keep Map B Line-Art With Pin Dots, the 240px map band from PR #128, and Wayne, Oakland and Macomb labeled. Pick one per card, or tap Machan Decides, and use Notes for anything to tweak.

## Options

- **A. Southeast Michigan**: Metro Detroit and the counties around it, with county lines. The three counties are about 2.5 times today's size.
- **B. Lower Peninsula**: The whole Lower Peninsula, with labels on short lines. The three counties are about 1.5 times today's size.
- **C. Whole State With An Inset**: All of Michigan like today, plus a close-up box of the three counties with their labels.

## Cards

- c1: Southeast Michigan vs Lower Peninsula
- c2: Southeast Michigan vs Whole State With An Inset
- c3: Lower Peninsula vs Whole State With An Inset

Images are reused across cards on purpose (three crops, three pairs); reused sides are marked `reuses` for the gate.

## Provenance

Frames are a local render of smart-upkeep draft PR #128 head 6c5c8d15b57f80f226aef8b1e80d62a27298386d (cache h9k6), from a git archive that passed the pagelock check, unlocked only in a local copy, served on 127.0.0.1 with outside traffic blocked and fonts served locally. Step 1 (Where's Your Home?) at 390×844, 2×, full frame, no crop. Only the MAP drawing in onboarding-house.js was swapped per option, plus Develop's r2 top-alignment of the address step on every frame so the form sits under the title. Map shapes are US Census cartographic boundaries cb_2023 500k (Michigan state and counties), drawn in the PR's Map B line-art style. Develop's map-options renders were not on disk when this deck was built, so these were rendered fresh. Nothing was pushed to smart-upkeep, and nothing was submitted or sent.
