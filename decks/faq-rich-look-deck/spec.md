# FAQ Rich Look Deck

Style Swipe · Smart Upkeep · Made Nov 13, 2026

## Ask

Machan, Nov 13, 7:39–7:40 PM ICT: the public FAQ is black and white and plain, with wasted space, the same problem as À La Carte. No carousel and no tabs. Keep the accordion and its motion. Use the member app FAQ style as the baseline. Variants: warmth, icons, accent on open answers, density, and an intro or contact panel to use the empty space. Every option shown closed and open, with a short open and close clip.

## Lede

Five cards on the Home FAQ section. The baseline is the member Help And FAQ look, adapted to the public one-screen section: cream ground, a 16px white card, member type, the 8px corner chevron at 200ms, and terracotta for the Emergency question. The six category chips and the one-screen budget stay, so all 32 questions still fit. Every option shows the list closed and open, plus a short clip of the existing open and close. Pick one per card, or tap Machan Decides, and use Notes for anything to tweak.

## Cards

### 1. Member-Style Port

Should the Home FAQ keep today's look, or use the member FAQ style?

- **A. Today's Look** — The live white section, charcoal chips, 12px list and SVG chevron.
- **B. Member Style** — Cream ground, 16px card, member type, corner chevron, chips and one-screen budget kept.

A is today's live Home FAQ: white section, charcoal chips, 12px list, 16px SVG chevron. B ports the member Help And FAQ look onto that same section: cream #FCF9F4 ground, 16px-radius white card, #ECE5DA hairlines, Hind 600/15px questions and 500/14.5px answers in #3a352e, the 8px corner chevron (200ms ease), and terracotta #A8431F on the Emergency question when that chip is selected. The six chips and the saFit one-screen budget stay, so all 32 items still fit. account-shared.css is not loaded on Home. The clip uses the existing one-open accordion; only the chevron animates.

### 2. Row Density

How tight should the member-style rows be?

- **A. Roomy** — A little more padding in the card and rows, still on one screen.
- **B. Tight** — Tighter rows, so more of the group fits in the same one-screen budget.

Both sit on the member-style port, with chips kept. Roomy uses a little more padding in the card and rows. Tight tightens the rows so more of the group sits in the same one-screen budget. The open and close motion is unchanged.

### 3. Topic Icons

Where should the small topic icons sit?

- **A. On The Chips** — The live topic icon sits on each category chip.
- **B. On Each Question** — The same topic icon sits in a small terracotta tile beside every question.

Both sit on the member-style port, with chips kept. On The Chips adds the live SUIcon for that topic on each chip (furnace, shield, gutter, clipboard, van, tag). On Each Question puts that same icon in a small terracotta tile beside every question in the open group. No icons were invented.

### 4. Open Answer Accent

How should an open answer be marked?

- **A. Lagoon Edge** — A 3px lagoon bar on the open item.
- **B. Warm Tint** — The open item fills with a light terracotta tint.

Both sit on the member-style port, with chips kept. Lagoon Edge puts a 3px #05668D bar on the open item. Warm Tint fills the open item with member terracotta-tint #F7EBE5. Closed rows stay the same. The clip uses the existing accordion motion.

### 5. Using The Empty Space

How should leftover space in a short group be used?

- **A. Intro Line** — The real line Frequently Asked Questions sits under the FAQ title.
- **B. Contact Panel** — A cream panel under the list uses the live line Give Us A Call Or Send A Message In The App.

Both sit on the member-style port, with chips kept, and use leftover space in the short first group. Intro Line adds the real /faq/ page title, Frequently Asked Questions, under FAQ. Contact Panel adds a cream card under the list with the live FAQ sentence, in Title Case: Give Us A Call Or Send A Message In The App. No phone number was added, because the public page does not list one.

## Provenance

Frames are a local render of a git archive of smart-upkeep PR #111 head 409c69a6c83819f2b67169e1f3b411312a963d54 (branch onboarding-header-1113), pagelock check exit 0, unlocked only in a local QA copy and served on 127.0.0.1 with outside traffic blocked and fonts served locally. Nothing was submitted, paid, finished or sent. Nothing was pushed to smart-upkeep. The live FAQ Look deck was not edited. Variants inject CSS and DOM only; account-shared.css is not loaded on Home. Chips and saFit stay. The 8px corner chevron, 16px card, #ECE5DA hairlines, Hind/Khand type, terracotta Emergency, cream #FCF9F4 ground, and white fade follow the member /member/help/ FAQ style map. Motion is the existing one-open accordion; only the chevron animates (200ms ease). Question wording is the live public FAQ copy. Crop QA at 390×844 and 360×640. The header is the PR #111 centered logo, with Share top left and the menu top right, and is not the question on this deck. Photos were redone Nov 13, 2026 after the first frames showed the old left-aligned logo.

## Member FAQ style, for Develop

Canonical map: `/workspace/handoff/member-faq-style-map.md`. Do not load `account-shared.css` on Home. Keep chips and `saFit`.

### Files

- `member/help/index.html` — inline `#su-help-fq` CSS (card, fade, groups, accordion, jumps) and one-open JS. Fonts: Hind 400/500/600, Khand 600/700.
- `member/account-shared.css` — tokens and generic `.faq` rules (the live control is the more specific help-page chevron, not the `+`).
- `member/index.html` — the same FAQ look in the Help sheet (`#su-review-css`, `bindHelpFaq`). Does not link `account-shared.css`.
- Public target: `app.js` (`FAQ_ALL`, `saTabsHtml`, `bindSaRows`, `saFit`, `saFade`, `saIntoBox`) and `styles.css` (`.sa-tab`, `.sa-list`, `.sa-q`, `.sa-a`, `#hs-faq` one-screen rules).

### Selectors (member)

- `.help-faq-wrap` > `.help-faq-box.card.faq`
- `details.help-fq.help-emerg` > `summary`; `h3.help-grp-h`; `details.help-fq` > `summary`, `p`, `a.faq-jump`, `p.help-disc`

### CSS to reuse on `#hs-faq` (do not import the member file)

- Card: `#fff`; border `1px solid #ECE5DA`; radius **16px**; padding `2px 14px 10px`; no box-shadow.
- Fade: 28px `linear-gradient(180deg, rgba(255,255,255,0), #fff 70%)` at the bottom of the scrolling box.
- Question: Hind 600 / 15px / 1.3, `#3a352e`, padding `10px 0`. Emergency summary `#A8431F`.
- Answer: Hind 500 / 14.5px / 1.45, `#3a352e`.
- Chevron: hide `.sa-chev`. `::after` 8×8px, `border-right/bottom: 2px solid #6B6B6B`; closed `rotate(45deg)`; open `rotate(225deg)`; `transition: transform 200ms ease`.
- Ground: cream `#FCF9F4` on `#hs-faq` only. Header stays as the public band (no green header).
- Keep `.sa-tabs` / `.sa-tab` and `saFit` so all 32 items still fit one screen.
