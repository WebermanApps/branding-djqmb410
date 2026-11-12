# Sign-Up Fit Deck

Develop’s one-screen sign-up fits every step except two. Each card shows two real ways to fit one of them on one screen, built on that update. Legal’s text stays word for word, with nothing cut, and prices are unchanged. Pick one per card, or tap Machan Decides, and use Notes for anything to tweak.

Requested: Machan, Nov 12 2026 10:07 PM ICT: on phone, "everything to fit on one screen at a time" and "avoid scrolling unless they click something". Anything that can't fit without cutting content comes to him as a deck. Develop's smart-upkeep PR97 (one-screen sign-up, head 27afbc58) fits every step except two: Start Date at 360x640 (779 vs 640 px) and Accept (about 1,690 px at every size). This two-card deck shows two real ways to fit each one, on the PR97 build. Legal's First Visit text and all consent and checkbox text stay word for word (tucked behind a tap at most, never cut). Prices unchanged.

## Cards

### Start Date On A Small Phone
On a small phone, the Start Date step runs about 140 px past the screen. Which way should it fit?
Today on a small phone (360 x 640), the month calendar and Legal’s Your First Visit box stack to about 779 px on a 640 px screen, so it scrolls. On regular phones and desktop the full month already fits and stays as it is in both options.
- A · Your First Visit Behind A Tap: The full month stays. Your First Visit becomes one row with the picked date. One tap opens Legal’s box, word for word, over the calendar.
- B · Two-Week Strip, Box Open: The calendar shows two weeks at a time, with the arrows paging. Legal’s Your First Visit box stays open under it, word for word.

### Accept Step
The Accept step is about 1,000 px too tall on every screen. Which way should it fit?
Today Accept stacks the summary, the Payments During Beta box, both consent checkboxes, the signature pad and the Payment box, about 1,690 px tall. Nothing is cut in either option, and Join Now stays off until sign-up opens.
- A · One Block Per Screen: Five short screens with Next: summary, Member Agreement, Payments During Beta, Signature, then Payment with Join Now.
- B · Tap-To-Open Boxes: One screen of rows: Due Today, Member Agreement, Payments During Beta and Signature. Each opens its full text over the page. Join Now sits in the bottom bar.

## Facts
Source: real smart-upkeep PR97 head 27afbc58fa84, unlocked git-archive copy, local serve, outside traffic blocked.
Every option fits one screen at 360x640 and 390x844, and at 1280x800. Measured page height vs screen:
- start-a@360x640: 640 of 640 px, Next visible True
- start-a@360x640-open: 640 of 640 px, Next visible True
- start-a@390x844: 844 of 844 px, Next visible True
- start-a@390x844-open: 844 of 844 px, Next visible True
- start-a@1280x800: 800 of 800 px, Next visible True
- start-a@1280x800-open: 800 of 800 px, Next visible True
- start-b@360x640: 640 of 640 px, Next visible True
- start-b@390x844: 844 of 844 px, Next visible True
- start-b@1280x800: 800 of 800 px, Next visible True
- accept-a@360x640-p1: 640 of 640 px, Next visible True
- accept-a@360x640-p2: 640 of 640 px, Next visible True
- accept-a@360x640-p3: 640 of 640 px, Next visible True
- accept-a@360x640-p4: 640 of 640 px, Next visible True
- accept-a@360x640-p5: 640 of 640 px, Next visible True
- accept-a@390x844-p1: 844 of 844 px, Next visible True
- accept-a@390x844-p2: 844 of 844 px, Next visible True
- accept-a@390x844-p3: 844 of 844 px, Next visible True
- accept-a@390x844-p4: 844 of 844 px, Next visible True
- accept-a@390x844-p5: 844 of 844 px, Next visible True
- accept-a@1280x800-p1: 800 of 800 px, Next visible True
- accept-a@1280x800-p2: 800 of 800 px, Next visible True
- accept-a@1280x800-p3: 800 of 800 px, Next visible True
- accept-a@1280x800-p4: 800 of 800 px, Next visible True
- accept-a@1280x800-p5: 800 of 800 px, Next visible True
- accept-a@360x340-kb-signature: 422 of 340 px, Next visible True, focused field visible True
- accept-a@390x500-kb-signature: 500 of 500 px, Next visible True, focused field visible True
- accept-b@360x640: 640 of 640 px, Next visible True
- accept-b@360x640-recap: 640 of 640 px, Next visible True
- accept-b@360x640-agree: 640 of 640 px, Next visible True
- accept-b@360x640-charge: 640 of 640 px, Next visible True
- accept-b@360x640-sig: 640 of 640 px, Next visible True
- accept-b@390x844: 844 of 844 px, Next visible True
- accept-b@390x844-recap: 844 of 844 px, Next visible True
- accept-b@390x844-agree: 844 of 844 px, Next visible True
- accept-b@390x844-charge: 844 of 844 px, Next visible True
- accept-b@390x844-sig: 844 of 844 px, Next visible True
- accept-b@1280x800: 800 of 800 px, Next visible True
- accept-b@1280x800-recap: 800 of 800 px, Next visible True
- accept-b@1280x800-agree: 800 of 800 px, Next visible True
- accept-b@1280x800-charge: 800 of 800 px, Next visible True
- accept-b@1280x800-sig: 800 of 800 px, Next visible True
- accept-b@360x340-kb-signature: 619 of 340 px, Next visible True, focused field visible True
- accept-b@390x500-kb-signature: 619 of 500 px, Next visible True, focused field visible True
Legal First Visit, consent, checkbox and price text verified word for word in every option (verify.json).

