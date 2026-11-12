# Member Reminders Deck

Seven calls on in-app reminders for Essentials and Plus, plus two plan facts Develop is re-asking. Reminder pictures are real /member/ dashboard screens at 390px, with Legal's exact card wording. Drone and storm-cap pictures are clean What's Included plan rows. Pick one per card, or tap Machan Decides, and use Notes for anything to tweak.

Requested: Machan, Nov 12 2026 7:37 PM ICT, via Grok and Develop: in-app filter and monthly smoke reminders on the /member/ dashboard for Essentials and Plus between visits; a Reminder Card deck for placement, actions, and an optional Add Reminders To My Calendar link (PLAN.md). Also re-ask drone frequency (one a year on every plan vs the current config) and Complete's after-storm yearly cap (2, 3 or 4). Legal's FINAL filter and reminder copy (7:39 PM, revised) is used word for word.

## Cards

### Filter Reminder Interval
How often should the in-app filter reminder come due between visits?
- A · Every 3 Months For Everyone: The reminder is set to every 3 months for every Essentials and Plus member. No in-app picker.
- B · Members Pick 1, 2 Or 3 Months: The member picks 1, 2 or 3 months in the app. The What's Included line stays Legal's exact wording.

### Calendar Reminders
Should the reminder card also offer an Add Reminders To My Calendar link?
- A · Add Reminders To My Calendar: A link on the card saves a .ics file of repeating filter and smoke times to the phone calendar, so the phone can show them when the app is closed.
- B · App Only: Reminders stay in the member app only. There is no calendar link.

### Filter Change Due Card Look
How should the Filter Change Due reminder look on the member dashboard?
- A · Due Card In The Dashboard Flow: A white due card sits in the dashboard flow under the greeting, with Legal's exact Filter Change Due title, body, buttons and footer.
- B · Slim Top Banner: A slim banner sits just under the header, with the same Legal Filter Change Due wording.

### Test Your Smoke Alarms Card Look
How should the Test Your Smoke Alarms reminder look on the member dashboard?
- A · Due Card In The Dashboard Flow: A lagoon-accent due card sits in the dashboard flow, with Legal's exact Test Your Smoke Alarms title, body, buttons and footer.
- B · Slim Top Banner: A slim lagoon banner sits just under the header, with the same Legal Test Your Smoke Alarms wording.

### Reminder Actions
Which actions should the reminder card offer?
- A · Mark Done And Remind Me Later: Both Legal buttons show. Under Remind Me Later: “This shows again the next time you open the app.” It is a next-open snooze, with no number of days.
- B · Mark Done Only: Only Mark Done shows. There is no Remind Me Later and no snooze line.

### Drone Flights
How often should each plan include a roof drone flight?
- A · One A Year On Every Plan: Essentials, Plus and Complete each include one roof drone inspection a year. Legal's line: “Roof Drone Inspection once a year. Nobody walks on your roof.”
- B · Keep The Current Setup: Keep the current plan config: Essentials once a year, Plus twice a year, Complete twice a year and after major storms. The config marks these as a default, not decided yet.

### Complete Storm-Check Yearly Cap
What yearly cap should Complete's after-storm checks have? If you want 3 a year, leave a Note.
- A · 2 A Year: Complete after-storm checks, on top of the 12 monthly visits, up to 2 a year. Includes vent and ice dam clearing.
- B · 4 A Year: Complete after-storm checks, on top of the 12 monthly visits, up to 4 a year. Includes vent and ice dam clearing. Leave a Note if you want a cap of 3 a year.

## Legal Copy (Final, 7:39 PM, Revised)
Used word for word on the reminder cards and lines:
- Tile: Furnace Filter Check and Change
- Filter title: Filter Change Due
- Filter body: Your furnace filter is due for a change. Your tech checks it and changes it at visits. Between visits, it's up to you.
- Smoke title: Test Your Smoke Alarms
- Smoke body: Press the test button on each smoke and CO alarm. If one doesn't sound, replace its battery or the alarm. Your tech also tests them at every visit.
- Buttons: Mark Done / Remind Me Later
- Under Remind Me Later: This shows again the next time you open the app.
- Footer: Reminders show here when you open the app.
- Essentials and Plus filter: We check your furnace filter every visit and change it when it's due. If a change comes due between visits, your member app shows a reminder.
- Essentials and Plus smoke: We test your smoke and CO detectors at every visit. Between visits, your member app shows a monthly reminder to press the test button.

## Facts
Source: /workspace/member-reminders/PLAN.md, /workspace/whats-included-audit/AUDIT.md and LEGAL-WHATS-INCLUDED.md (FINAL section), and pricing-config.js on smart-upkeep main c462c1b.
Reminders are in the /member/ app for Essentials and Plus, between visits. Complete has monthly visits, so it does not get these between-visit reminders.
The tech checks the furnace filter every visit and changes it when it is due. Between visits, the member changes it; the app shows a reminder.
Smoke and CO detectors are tested at every visit. Between visits, the member app shows a monthly reminder to press the test button.
Remind Me Later is a next-open snooze. It is not a number of days.
Current drone setup in the plan config (a default, not decided yet): Essentials once a year, Plus twice a year, Complete twice a year and after major storms.
Complete after-storm checks sit on top of the 12 monthly visits. The yearly cap is not in the config; the cards offer 2 or 4 a year, and a Note can ask for 3.

