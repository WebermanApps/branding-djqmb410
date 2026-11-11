# Refer Mascot Look Deck: CSS/SVG spec

Base: the live Refer A Neighbor sheet (smartupkeep.ai/member/, main 8f9438b5, member/index.html sha256 697bc775), changed with injected CSS/DOM only. Renders are 390px wide at 2x.
Mascot: the real `assets/persimmon-wink.svg`, inlined so its parts can move. The geometry is unchanged. The raised arm (the path `M178 120 Q196 104 194 84` plus the hand circle) is wrapped in `<g class="rm-arm">`. The open eye (the ellipse at cx 78, cy 112 plus its highlight) is wrapped in `<g class="rm-eye">`. No new character is drawn. The houses and heart in card 1B are simple line SVGs.

## Layout used on every card (top to bottom)
1. **Mascot hero card** `.rf-card.rm-hero`. It replaces the green reward card and takes the space the full QR used.
   - padding 18/16/16, centered, on a white card (the live `.rf-card` shadow, no border)
   - mascot `.rm-m`: width `var(--mw)`, 96px by default (card 4: 64 / 128)
   - headline `b.rm-h`: Khand 700 1.75rem/1.05, #1D1A16, "1 Free Month For Both"
   - sub `.rm-sub`: Hind 500 15px/1.4, #5A5650, "Share Your Code With A Neighbor"
   - The trigger wording (first payment vs first visit) is left out on purpose.
2. **Small QR control** `button.rm-qr-row`, the first child of `.rf-combo`.
   - min-height 48px, gap 12px, Hind 600 15px #1D1A16
   - 22px QR glyph (#2A2826), label "Show QR Code", 20px chevron (#8A847C)
   - The "Scan To Join" label and the inline 128px QR are hidden.
   - Tap opens: `aria-expanded="true"`, label "Hide QR Code", chevron `rotate(180deg)` over `.2s`, and `.rm-qr-big` shows below the row.
     - `.rm-qr-big`: flex center, padding 4/0/14, background #fff, no border; QR svg 220×220
   - Tap again closes. The QR always sits edge-free on white.
3. **Code chip and actions.** The live, settled `.rf-code-hit` tap-to-copy chip (#F6EFE3) and `.rf-acts`, with Share and Copy Link side by side. Unchanged.
4. **Empty state.** The live `.rf-status` card with "No referrals yet." Unchanged.

Sheet: `#sheet.rf-on, #sheet.rf-on #shB { background:#FCF9F4 }`, with white cards. No colored edges. Accents: terracotta #C1502E (mascot, heart, Share), jungle #0B6E4F (the live "Copied" tag).

## Keyframes (shared)
```css
@keyframes rmWave{0%,100%{transform:rotate(0)}15%{transform:rotate(-16deg)}30%{transform:rotate(8deg)}45%{transform:rotate(-16deg)}60%{transform:rotate(0)}}
@keyframes rmEnter{0%{opacity:0;transform:translateY(16px) scale(.92)}100%{opacity:1;transform:none}}
@keyframes rmBreathe{0%,100%{transform:scale(1)}50%{transform:scale(1.03)}}
@keyframes rmBlink{0%,90%,100%{transform:scaleY(1)}93%{transform:scaleY(.1)}96%{transform:scaleY(1)}}
@keyframes rmBounce{0%,100%{transform:translateY(0)}30%{transform:translateY(-10px)}55%{transform:translateY(0)}75%{transform:translateY(-4px)}}
@keyframes rmPop{0%{opacity:0;transform:translateY(0) scale(0)}30%{opacity:1;transform:translateY(-4px) scale(1.2)}60%{opacity:1;transform:translateY(-10px) scale(1)}100%{opacity:0;transform:translateY(-16px) scale(1)}}
@keyframes rmSpark{0%{opacity:0;transform:translate(0,0)}30%{opacity:1}100%{opacity:0;transform:translate(var(--dx),var(--dy))}}
@keyframes rmHeartArc{0%{transform:translate(-78px,26px) scale(.7);opacity:0}12%{opacity:1}50%{transform:translate(0,0) scale(1)}88%{opacity:1}100%{transform:translate(78px,26px) scale(.7);opacity:0}}
.rm-arm{transform-box:fill-box;transform-origin:0% 100%}   /* shoulder */
.rm-eye{transform-box:fill-box;transform-origin:50% 50%}
@media (prefers-reduced-motion: reduce){.rm-m,.rm-arm,.rm-eye,.rm-arc .rm-heart,.rm-pop,.rm-spark{animation:none!important}}
```
With reduced motion every element rests in its final pose: the mascot is visible, no wave, and the heart and pop are hidden. Copy feedback still shows the live "Copied" text tag.

## Card 1: Mascot Hero
- **A, Wave And Wink, Centered.** A 96px mascot above the headline. Wave: `.rm-arm{animation:rmWave 1.6s ease-in-out .2s 1 both}`, played once when the sheet opens (the deck preview loops it every 2.4s). The wink is already in the asset.
- **B, Between Two Houses.** `.rm-art` is a flex row with gap 14px: house (52px) · mascot (96px) · house.
  - Houses: stroke #2A2826 at 3.2 (in a 64×56 viewBox), white fill.
  - A 16px terracotta heart travels along a 200×44 arc above them: `.rm-arc .rm-heart{animation:rmHeartArc 2.4s ease-in-out infinite both}`. Shipped, this could run 2 loops and then stop.

## Card 2: Motion Level (hero layout from 1A)
- **A, One-Time Entrance.** `.rm-m{animation:rmEnter .7s cubic-bezier(.22,.61,.36,1) 0s 1 both}`, then one wave at .5s delay. Plays once per sheet open, then rests.
- **B, Subtle Idle Loop.** `.rm-m{animation:rmBreathe 3.2s ease-in-out infinite;transform-origin:50% 100%}` and `.rm-eye{animation:rmBlink 4s linear infinite}`. No wave.

## Card 3: Copy Feedback (tap on the code chip; the live `.is-copied` "Copied" tag stays)
- **A, Mascot Bounce.** On copy: `.rm-m{animation:rmBounce .6s cubic-bezier(.3,.7,.4,1) 1 both}`. The mascot hops 10px, then 4px.
- **B, Heart Pop On The Chip.** On copy: `.rm-pop` (a 16px terracotta heart placed `right:66px` in the chip, left of "Copied") runs `rmPop .7s ease-out 1 both`. Three 4px terracotta `.rm-spark` dots run `rmSpark .6s ease-out .05s` (dx/dy: -14/-12, 12/-14, 0/-18). The mascot doesn't move.
- Trigger: add the animation class on the chip's click handler (after `rfCopyText`), and remove it on `animationend` so it can replay.

## Card 4: Mascot Size (static, layout from 1A)
- **A, Small:** `--mw:64px` (hero card about 150px tall).
- **B, Medium:** `--mw:128px` (hero card about 215px tall).

## Previews in the deck
Animated WebP made from real frames at 80ms per step (12.5fps), 600px wide, looping. Frames come from headless Chromium by pausing the Web Animations and setting `currentTime`. Each option also has a static 390 frame (JPEG). The deck swaps to that frame when the viewer has Reduce Motion on.
