# Promotional send plan: trial on the invented example

- **Product:** Claude, run in Claude Code

Model: Claude Sonnet 5.5 (model ID claude-sonnet-5-5). Date of the runs: 2026-11-12. Two runs are recorded, the second after the template was revised because of what the first found.

## Second run, after the revision

The inputs are the invented example in `public/example.md` (Shop W's Autumn Kitchen Sale), whose brief now reads "Pacific (all customers are on the US West Coast)" where the first run's read "Pacific (all customers are in the US)". No client data was used.

This run is not independent. It was done by the session that revised the template, which had the example's plan open. It applied the revised instruction block step by step to the four inputs and set the result down; the output below is the plan published in the example. A match with the example therefore shows consistency, not a blind result. An independent re-run on the revised template has not been done. After an independent review, the published example's Q4 was edited to print an "Other reasons" line, as Q1 and Q2 do; the output recorded below is as the run produced it and is unchanged.

### What came out

**PROMOTIONAL SEND PLAN: Autumn kitchen sale, November 2026, Thu 19 Nov 2026 to Mon 23 Nov 2026. Status: draft for approval**

For: marketing lead. Prepared 2026-11-12 from the inputs listed under Coverage. Nothing has been sent, scheduled, uploaded or changed.

**THE PLAN IN BRIEF**

4 sends (2 email, 2 text) to past_buyers and newsletter, Thu 19 Nov to Mon 23 Nov 2026.
Email: of 14 contacts, 7 can receive, 4 suppressed, 0 no address on file, 1 excluded by consent, 1 held for a question, 1 outside this promotion.
Text: of 14 contacts, 3 can receive, 2 suppressed, 1 no mobile number on file, 1 excluded by consent, 1 held for a question, 6 outside this promotion.
8 people can receive at least one send; at most 20 sends in all. 7 open questions; 4 decisions for the marketing lead. Can receive is not approved.

**SETTINGS USED**

Permitted email statuses: subscribed (rules)
Excluded email statuses: unsubscribed (rules)
Permitted text statuses: opted_in (rules)
Excluded text statuses: opted_out, never (rules)
Email window: 08:00 to 20:00 Pacific (default, not from your rules; Q6)
Text window: 10:00 to 18:00 Pacific (rules)
Sending allowance: 60 minutes, so email starts by 19:00 and texts by 17:00 (rules)
Most sends per person per day: 1, email and text together (rules)
Most sends per person in this promotion: 3, email and text together (rules)
No-send dates: none (rules)
Suppression lists: email_unsubscribe, email, records unsubscribes; hard_bounce, email; text_optout, text, records opt-outs; do_not_market, email and text; staff_test, email and text (rules). vip_hold, email and text (default, not from your rules; Q4)
Text sender prefix: "Shop W:" (rules)
Text opt-out wording: "Reply STOP to opt out" (rules)
Email identification and unsubscribe lines: added by the email tool (rules)
Condition "not bought since the sale opened": the marketing coordinator applies the store's buyers list on the morning of the send (rules)
Email sent by: the marketing coordinator (rules)
Texts sent by: not supplied (Q7)
Before every send: "the marketing coordinator sends a test to the staff_test list and opens the link" (rules)
Link: https://shop-w.example/autumn-sale (brief)
Tracking pattern: ?src= then the channel and the send number (rules)
Time zones: Pacific, the only zone named (brief)
Days counted in: Pacific, the zone of the brief's send times (brief)

**OFFER FACTS**

F1 the Autumn Kitchen Sale (brief: Sale name)
F2 20% off all cookware and bakeware (brief: Offer)
F3 AUTUMN20, entered at checkout (brief: Code)
F4 Thursday 19 November 2026, 08:00, to Monday 23 November 2026, 23:59 (brief: Dates)
F5 gift cards and items already marked down (brief: Exclusions)
F6 free shipping on orders over $75 (brief: Standing term)

**AUDIENCE: EMAIL**

Contacts 14 (export rows 14; exact repeats collapsed 0).
Outside 1 + suppressed 4 + no address 0 + excluded 1 + held 1 + can receive 7 = 14.
Outside this promotion: 1 (wholesale: C13).
By segment: past_buyers: can receive 6, held 0. newsletter: can receive 1, held 1.
Suppressed: hard_bounce: 1 (C10). do_not_market: 1 (C11). staff_test: 1 (C12). vip_hold: 1 (C14, which also has no email address on file and a blank email consent).
No address on file: None.
Excluded by consent: unsubscribed: 1 (C05).
Held for a question: 1 (C09: email consent "pending" is in neither of the rules' lists, Q2).
Can receive: C01, C02, C03, C04, C06, C07, C08.

**AUDIENCE: TEXT**

Contacts 14 (export rows 14; exact repeats collapsed 0).
Outside 6 + suppressed 2 + no mobile number 1 + excluded 1 + held 1 + can receive 3 = 14.
Outside this promotion: 6 (newsletter: C08, C09, C10, C11, C12; wholesale: C13).
By segment: past_buyers: can receive 3, held 1.
Suppressed: text_optout: 1 (C06). vip_hold: 1 (C14).
No mobile number on file: 1 (C03, which also has a blank text consent).
Excluded by consent: opted_out: 1 (C04).
Held for a question: 1 (C07: text consent "imported" is in neither of the rules' lists, Q1).
Can receive: C01, C02, C05.

**RECORDS THAT DISAGREE**

C06: on text_optout since 2026-10-30 (suppressions, row 1); text consent "opted_in" (contacts, row 6). Kept suppressed. Q3.

**SEND CALENDAR**

S1 (brief 1) Email. Thu 19 Nov 2026, 08:00 Pacific.
- To: past_buyers, newsletter. Condition: none.
- Reach: 7 (C01, C02, C03, C04, C06, C07, C08).
- Purpose: Sale opens.
- Says: 1. The Autumn Kitchen Sale starts today: 20% off all cookware and bakeware, until Mon 23 Nov at 23:59 (F1, F2, F4). 2. Code AUTUMN20, entered at checkout; gift cards and items already marked down are excluded (F3, F5). 3. Free shipping on orders over $75 (F6).
- Call to action: shop the sale. Link: https://shop-w.example/autumn-sale?src=email-s1
- Required parts: the company's identification and unsubscribe lines, added by the email tool.
- Copy by: content writer. Brief only; copy not written here.

S2 (brief 2) Text. Fri 20 Nov 2026, 12:00 Pacific (brief proposed Thu 19 Nov, 12:00: C01 and C02 can also receive S1 that day, against a limit of 1 send per person per day; decision 1).
- To: past_buyers. Condition: none.
- Reach: 3 (C01, C02, C05).
- Purpose: Sale is on, for customers who prefer texts (brief: "Sale opens, for customers who prefer texts"; moved a day later, when the sale has already opened).
- Says: 1. The Autumn Kitchen Sale is on until Mon 23 Nov at 23:59: 20% off all cookware and bakeware (F1, F2, F4). 2. Code AUTUMN20, entered at checkout (F3).
- Call to action: shop the sale. Link: https://shop-w.example/autumn-sale?src=text-s2
- Required parts: sender prefix "Shop W:" first and "Reply STOP to opt out" last.
- Copy by: content writer. Brief only; copy not written here.

S3 (brief 3) Email. Sun 22 Nov 2026, 10:00 Pacific.
- To: past_buyers, newsletter. Condition: only people who have not bought since the sale opened, applied by the marketing coordinator from the store's buyers list on the morning of the send.
- Reach: at most 7 (C01, C02, C03, C04, C06, C07, C08).
- Purpose: Reminder: the sale ends Monday.
- Says: 1. The Autumn Kitchen Sale ends Mon 23 Nov at 23:59 (F1, F4). 2. 20% off all cookware and bakeware with code AUTUMN20, entered at checkout (F2, F3). 3. Gift cards and items already marked down are excluded (F5).
- Call to action: shop the sale. Link: https://shop-w.example/autumn-sale?src=email-s3
- Required parts: the company's identification and unsubscribe lines, added by the email tool.
- Copy by: content writer. Brief only; copy not written here.

S4 (brief 4) Text. Mon 23 Nov 2026, 17:00 Pacific (brief proposed 18:30: texts go out between 10:00 and 18:00 and the last send starts an hour before the close, so the latest start is 17:00; decision 2).
- To: past_buyers. Condition: only people who have not bought since the sale opened, applied by the marketing coordinator from the store's buyers list on the morning of the send.
- Reach: at most 3 (C01, C02, C05).
- Purpose: Last day.
- Says: 1. Last day of the Autumn Kitchen Sale: it ends at 23:59 (F1, F4). 2. 20% off all cookware and bakeware with code AUTUMN20 (F2, F3).
- Call to action: shop the sale. Link: https://shop-w.example/autumn-sale?src=text-s4
- Required parts: sender prefix "Shop W:" first and "Reply STOP to opt out" last.
- Copy by: content writer. Brief only; copy not written here.

**SENDS PER PERSON**

Limits: at most 1 per person per day; at most 3 per person in this promotion (rules).
On the proposed schedule: 8 people can receive at least one send.
Within the promotion limit: 6 (C03: S1, S3. C04: S1, S3. C05: S2, S4. C06: S1, S3. C07: S1, S3. C08: S1, S3).
Over the promotion limit: C01: 4 sends (S1, S2, S3, S4) against 3. C02: 4 sends (S1, S2, S3, S4) against 3. Decision 3.
More than the daily limit on one day: None on the proposed schedule; on the brief's schedule, C01 and C02 would receive S1 and S2 on Thu 19 Nov (decision 1).
Most sends that could go out: 7 + 3 + 7 + 3 = 20.

**OPEN QUESTIONS**

Q1 Held for a question, text: C07
- Files show: contacts, row 7: segment past_buyers, mobile on file yes, text consent "imported". The rules permit "opted_in" and exclude "opted_out" and "never".
- Other reasons: none
- Question: What does "imported" mean in Shop W's text consent records?
- Who answers: operations manager

Q2 Held for a question, email: C09
- Files show: contacts, row 9: segment newsletter, email on file yes, email consent "pending". The rules permit "subscribed" and exclude "unsubscribed".
- Other reasons: none
- Question: What does "pending" mean in Shop W's email consent records?
- Who answers: operations manager

Q3 Records that disagree, text: C06
- Files show: suppressions, row 1: C06 on text_optout, added 2026-10-30. Contacts, row 6: text consent "opted_in". C06 is kept off both texts.
- Other reasons: none
- Question: Which of the two records is current for C06's texts?
- Who answers: marketing coordinator

Q4 A list the rules do not name: vip_hold
- Files show: suppressions, row 5: C14 on vip_hold, added 2026-11-10. The rules do not mention vip_hold, so it is applied to email and text, and C14 receives nothing in this plan. C14 also has no email address on file and a blank email consent (contacts, row 14).
- Question: Which channels, if any, does vip_hold cover, and does it record opt-outs?
- Who answers: operations manager

Q5 Fact asked for: cast-iron stock
- Files show: the brief's note asks whether the sends can say only a few cast-iron pans are left. The brief holds no stock fact, so no send says it.
- Question: Is there a stock fact, in approved wording, that the sends may state?
- Who answers: e-commerce manager

Q6 Default used: email window
- Files show: the rules give a window for texts and none for email, so 08:00 to 20:00 Pacific was used. S1 at 08:00 sits at its opening.
- Question: What is Shop W's window for promotional email?
- Who answers: operations manager

Q7 Not supplied: who sends texts
- Files show: the rules name the marketing coordinator for email and nobody for texts.
- Question: Who loads and sends S2 and S4?
- Who answers: operations manager

**DECISIONS FOR THE MARKETING LEAD**

1. S2, brief Thu 19 Nov at 12:00. C01 and C02 can receive both S1 (email, 08:00) and S2 that day, against a limit of 1 send per person per day. Proposed Fri 20 Nov at 12:00, when no other send goes. Keep the proposal or choose another time.
2. S4, brief Mon 23 Nov at 18:30. Texts go out between 10:00 and 18:00 and the last send starts an hour before the close, so the latest start is 17:00. Proposed 17:00 the same day. Keep it or choose an earlier time.
3. C01 and C02 would receive 4 sends (S1, S2, S3, S4) against a limit of 3 per person in this promotion, because they can receive both email and text. Which send do they go without?
4. Approve this plan, or ask for changes.

**BEFORE THE FIRST SEND**

1. Offer facts F1 to F6, the code, the dates and the exclusions confirmed. Who: e-commerce manager. Done: ____________ Date: ________
2. The landing page live at https://shop-w.example/autumn-sale, stating the offer and its exclusions, and code AUTUMN20 tested at checkout. Who: e-commerce manager. Done: ____________ Date: ________
3. The copy for S1 to S4 written from their briefs and approved. Who: marketing lead. Done: ____________ Date: ________
4. The final wording of S2 and S4 starts with "Shop W:" and ends with "Reply STOP to opt out". Who: operations manager. Done: ____________ Date: ________
5. Q1 to Q7 answered, and this plan run again if an answer changes who can receive. Who: marketing lead. Done: ____________ Date: ________
6. The suppression lists refreshed from the email and texting tools on the day of each send, and the buyers list applied before S3 and S4. Who: marketing coordinator. Done: ____________ Date: ________
7. A named person loads and sends each channel; texts have nobody yet (Q7). Who: marketing lead. Done: ____________ Date: ________
8. This plan approved. Who: marketing lead. Done: ____________ Date: ________
9. From the rules: "Before every send, the marketing coordinator sends a test to the staff_test list and opens the link." Who: marketing coordinator. Done: ____________ Date: ________

**COVERAGE**

Used: the promotion brief (every line); Shop W's sending rules (every line); contacts.csv (14 data rows); suppressions.csv (6 data rows).
Missing: nothing.
Not used: none.
Suppression rows for contacts not in the export: C21 on email_unsubscribe (suppressions, row 6).
Could not judge: whether any consent is sufficient; what any law or carrier rule requires; whether the landing page states the offer and its exclusions; whether the code works; who will buy, unsubscribe or opt out after 12 November.
Ignored: none found.
Checked and fine: email 1 + 4 + 0 + 1 + 1 + 7 = 14; text 6 + 2 + 1 + 1 + 1 + 3 = 14; email segments, can receive 6 + 1 = 7 and held 0 + 1 = 1; text segment, can receive 3 and held 1; email suppressed by list 1 + 1 + 1 + 1 = 4; text suppressed by list 1 + 1 = 2; no exact repeat rows and no repeated contact_id; every send on the proposed schedule falls between the offer's start, Thu 19 Nov at 08:00, and its end, Mon 23 Nov at 23:59.

Draft for approval. Nothing has been sent, scheduled, uploaded or changed.
Approved by (marketing lead): ____________ Date: __________

### What was observed

- **The time-zone defect from the first run is dealt with in the template.** The revised block checks every send in every zone the brief names and makes an unsettled zone an open question for the marketing lead. This example names one zone and says all customers are on the West Coast, so every check is in Pacific time and no open question arises. The two-zone case (a text at 17:00 Pacific reaching Eastern customers at 20:00) is covered by a new acceptance test, number 13, which has not been run.
- **Changes from the first run's output:** the settings list names the time zones and the zone days are counted in; S2's purpose is restated for its new day, with the brief's words beside it; Q4 asks whether `vip_hold` records opt-outs as well as which channels it covers. Counts, times, decisions and the 20-send total are unchanged.
- **The first run's other ambiguities are settled in the template by wording, not by testing:** "other reasons" means every other reason that applies; "the send number" is the plan's S number; a moved send's purpose is restated; a question about a status the rules do not name goes to the messaging rules owner. The "Who answers" lines in this run name the company's person only.
- **Not shown.** Acceptance tests 13 and 14 (two zones, an unsettled zone) were not run. The instruction block is longer than before and a smaller model may still drop a step. It is one run, on one invented example, by the model that revised the template. It says nothing about client data or other products.

## First run, before the revision

Recorded as it was. The template and the example have changed since: the time-zone finding below is the reason. Its inputs were the example before the brief's zone line was reworded.

Model: Claude Sonnet 5.5 (model ID claude-sonnet-5-5). Date of the run: 2026-11-12.

The inputs are the invented example in `public/example.md` (Shop W's Autumn Kitchen Sale). No client data was used. The run was done by a session that did not write the template. It read the template and only the four invented inputs (promotion brief, sending rules, contact export, suppression lists), followed the instruction block and the output format, produced the plan, and only then read the example's published output to compare.

### Inputs used

The four inputs under "The inputs" in `public/example.md`, in full: the promotion brief (including the e-commerce manager's note about cast-iron pans), Shop W's sending rules, `contacts.csv` (14 rows) and `suppressions.csv` (6 rows).

### What came out

```
PROMOTIONAL SEND PLAN: Autumn kitchen sale, November 2026, Thu 19 Nov 2026 to Mon 23 Nov 2026. Status: draft for approval

For: marketing lead. Prepared 2026-11-12 from the inputs listed under Coverage. Nothing has been sent, scheduled, uploaded or changed.

THE PLAN IN BRIEF
4 sends (2 email, 2 text) to past_buyers and newsletter, Thu 19 Nov to Mon 23 Nov 2026.
Email: of 14 contacts, 7 can receive, 4 suppressed, 0 no address on file, 1 excluded by consent, 1 held for a question, 1 outside this promotion.
Text: of 14 contacts, 3 can receive, 2 suppressed, 1 no mobile number on file, 1 excluded by consent, 1 held for a question, 6 outside this promotion.
8 people can receive at least one send; at most 20 sends in all. 7 open questions; 4 decisions for the marketing lead. Can receive is not approved.

SETTINGS USED
Permitted email statuses: subscribed (rules)
Excluded email statuses: unsubscribed (rules)
Permitted text statuses: opted_in (rules)
Excluded text statuses: opted_out, never (rules)
Email window: 08:00 to 20:00 Pacific (default, not from your rules; Q6)
Text window: 10:00 to 18:00 Pacific (rules)
Sending allowance: 60 minutes, so email starts by 19:00 and texts by 17:00 (rules)
Most sends per person per day: 1, email and text together (rules)
Most sends per person in this promotion: 3, email and text together (rules)
No-send dates: none (rules)
Suppression lists: email_unsubscribe (email, records unsubscribes), hard_bounce (email), text_optout (text, records opt-outs), do_not_market (email and text), staff_test (email and text) (rules); vip_hold (email and text, default, not from your rules; Q4)
Text sender prefix: "Shop W:" (rules)
Text opt-out wording: "Reply STOP to opt out" (rules)
Email identification and unsubscribe lines: added by the email tool (rules)
Condition "not bought since the sale opened": applied by the marketing coordinator from the store's buyers list on the morning of the send (rules)
Email loaded and sent by: the marketing coordinator (rules)
Texts loaded and sent by: not supplied (Q7)
Before every send: "the marketing coordinator sends a test to the staff_test list and opens the link" (rules)
Link: https://shop-w.example/autumn-sale (brief)
Tracking pattern: ?src= then the channel and the send number (rules)
Time zone: Pacific (brief)

OFFER FACTS
F1 the Autumn Kitchen Sale (brief: Sale name)
F2 20% off all cookware and bakeware (brief: Offer)
F3 AUTUMN20, entered at checkout (brief: Code)
F4 Thursday 19 November 2026, 08:00, to Monday 23 November 2026, 23:59 (brief: Dates)
F5 gift cards and items already marked down (brief: Exclusions)
F6 free shipping on orders over $75 (brief: Standing term)

AUDIENCE: EMAIL
Contacts 14 (export rows 14; exact repeats collapsed 0).
Outside 1 + suppressed 4 + no address 0 + excluded 1 + held 1 + can receive 7 = 14.
Outside this promotion: 1 (wholesale: C13).
By segment: past_buyers: can receive 6, held 0. newsletter: can receive 1, held 1.
Suppressed: hard_bounce: 1 (C10). do_not_market: 1 (C11). staff_test: 1 (C12). vip_hold: 1 (C14; also no email address on file and a blank email consent).
No address on file: None.
Excluded by consent: unsubscribed: 1 (C05).
Held for a question: 1 (C09: email consent "pending", Q2).
Can receive: C01, C02, C03, C04, C06, C07, C08.

AUDIENCE: TEXT
Contacts 14 (export rows 14; exact repeats collapsed 0).
Outside 6 + suppressed 2 + no mobile number 1 + excluded 1 + held 1 + can receive 3 = 14.
Outside this promotion: 6 (newsletter: C08, C09, C10, C11, C12; wholesale: C13).
By segment: past_buyers: can receive 3, held 1.
Suppressed: text_optout: 1 (C06). vip_hold: 1 (C14).
No mobile number on file: 1 (C03; also a blank text consent).
Excluded by consent: opted_out: 1 (C04).
Held for a question: 1 (C07: text consent "imported", Q1).
Can receive: C01, C02, C05.

RECORDS THAT DISAGREE
C06: on text_optout since 2026-10-30 (suppressions, row 1); text consent "opted_in" (contacts, row 6). Kept suppressed. Q3.

SEND CALENDAR
S1 (brief 1) Email. Thu 19 Nov 2026, 08:00 Pacific.
- To: past_buyers, newsletter. Condition: none.
- Reach: 7 (C01, C02, C03, C04, C06, C07, C08).
- Purpose: Sale opens.
- Says: 1. The Autumn Kitchen Sale starts today: 20% off all cookware and bakeware, until Mon 23 Nov at 23:59 (F1, F2, F4). 2. Code AUTUMN20, entered at checkout; gift cards and items already marked down are excluded (F3, F5). 3. Free shipping on orders over $75 (F6).
- Call to action: shop the sale. Link: https://shop-w.example/autumn-sale?src=email-s1
- Required parts: the company's identification and unsubscribe lines, from the email tool.
- Copy by: content writer. Brief only; copy not written here.

S2 (brief 2) Text. Fri 20 Nov 2026, 12:00 Pacific (brief proposed Thu 19 Nov 12:00: C01 and C02 can also receive S1 that day, against a limit of 1 per day; decision 1).
- To: past_buyers. Condition: none.
- Reach: 3 (C01, C02, C05).
- Purpose: Sale opens, for customers who prefer texts.
- Says: 1. The Autumn Kitchen Sale is on until Mon 23 Nov at 23:59: 20% off all cookware and bakeware (F1, F2, F4). 2. Code AUTUMN20, entered at checkout (F3).
- Call to action: shop the sale. Link: https://shop-w.example/autumn-sale?src=text-s2
- Required parts: sender prefix "Shop W:" first and "Reply STOP to opt out" last.
- Copy by: content writer. Brief only; copy not written here.

S3 (brief 3) Email. Sun 22 Nov 2026, 10:00 Pacific.
- To: past_buyers, newsletter. Condition: only people who have not bought since the sale opened, applied by the marketing coordinator from the store's buyers list on the morning of the send.
- Reach: at most 7 (C01, C02, C03, C04, C06, C07, C08).
- Purpose: Reminder: the sale ends Monday.
- Says: 1. The Autumn Kitchen Sale ends tomorrow, Mon 23 Nov, at 23:59 (F1, F4). 2. 20% off all cookware and bakeware with code AUTUMN20, entered at checkout (F2, F3). 3. Gift cards and items already marked down are excluded (F5).
- Call to action: shop the sale. Link: https://shop-w.example/autumn-sale?src=email-s3
- Required parts: the company's identification and unsubscribe lines, from the email tool.
- Copy by: content writer. Brief only; copy not written here.

S4 (brief 4) Text. Mon 23 Nov 2026, 17:00 Pacific (brief proposed 18:30: the text window closes at 18:00 and the last send starts an hour before, so the latest start is 17:00; decision 2).
- To: past_buyers. Condition: only people who have not bought since the sale opened, applied by the marketing coordinator from the store's buyers list on the morning of the send.
- Reach: at most 3 (C01, C02, C05).
- Purpose: Last day.
- Says: 1. The last day of the Autumn Kitchen Sale: it ends at 23:59 (F1, F4). 2. 20% off all cookware and bakeware with code AUTUMN20 (F2, F3).
- Call to action: shop the sale. Link: https://shop-w.example/autumn-sale?src=text-s4
- Required parts: sender prefix "Shop W:" first and "Reply STOP to opt out" last.
- Copy by: content writer. Brief only; copy not written here.

SENDS PER PERSON
Limits: at most 1 per person per day; at most 3 per person in this promotion (rules).
On the proposed schedule: 8 people can receive at least one send.
Within the promotion limit: 6 (C03: S1, S3. C04: S1, S3. C05: S2, S4. C06: S1, S3. C07: S1, S3. C08: S1, S3).
Over the promotion limit: C01: 4 sends (S1, S2, S3, S4) against 3. C02: 4 sends (S1, S2, S3, S4) against 3. Decision 3.
More than the daily limit on one day: None on the proposed schedule; on the brief's schedule, C01 and C02 would have received S1 and S2 on Thu 19 Nov (decision 1).
Most sends that could go out: 7 + 3 + 7 + 3 = 20.

OPEN QUESTIONS
Q1 Held for a question, text: C07
- Files show: contacts, row 7: segment past_buyers, mobile on file yes, text consent "imported". The rules permit "opted_in" and exclude "opted_out" and "never".
- Other reasons: none
- Question: What does "imported" mean in Shop W's text consent records?
- Who answers: [your messaging rules owner] (operations manager)

Q2 Held for a question, email: C09
- Files show: contacts, row 9: segment newsletter, email on file yes, email consent "pending". The rules permit "subscribed" and exclude "unsubscribed".
- Other reasons: none
- Question: What does "pending" mean in Shop W's email consent records?
- Who answers: operations manager

Q3 Records that disagree, text: C06
- Files show: suppressions, row 1: C06 on text_optout, added 2026-10-30. Contacts, row 6: text consent "opted_in". C06 is kept off both texts.
- Other reasons: none
- Question: Which of the two records is current for C06's texts?
- Who answers: [your records keeper] (marketing coordinator)

Q4 A list the rules do not name: vip_hold
- Files show: suppressions, row 5: C14 on vip_hold, added 2026-11-10. The rules do not mention it, so it is applied to email and text and is not treated as an opt-out list. contacts, row 14: C14 has no email address on file and a blank email consent.
- Question: Which channels does vip_hold cover, and does it record opt-outs?
- Who answers: operations manager

Q5 Fact asked for: cast-iron stock
- Files show: the brief's note asks whether the sends can say only a few cast-iron pans are left. The brief holds no stock fact, so no send says it.
- Question: Is there a stock fact, in approved wording, that the sends may state?
- Who answers: [your offer owner] (e-commerce manager)

Q6 Default used: email window
- Files show: the rules give a window for texts and none for email, so 08:00 to 20:00 was used. S1 at 08:00 is at the opening.
- Question: What is Shop W's window for promotional email?
- Who answers: operations manager

Q7 Not supplied: who sends texts
- Files show: the rules name the marketing coordinator for email and nobody for texts.
- Question: Who loads and sends S2 and S4?
- Who answers: operations manager

DECISIONS FOR THE MARKETING LEAD
1. S2, brief Thu 19 Nov at 12:00. C01 and C02 can receive both S1 and S2 that day, against 1 per person per day. Proposed Fri 20 Nov at 12:00, when no other send goes. Keep it or choose another time.
2. S4, brief Mon 23 Nov at 18:30. The latest start is 17:00. Proposed 17:00 the same day. Keep it or choose an earlier time.
3. C01 and C02 would receive 4 sends against a limit of 3 in this promotion. Which send do they go without?
4. Approve this plan, or ask for changes.

BEFORE THE FIRST SEND
1. Offer facts F1 to F6, the code, the dates and the exclusions confirmed. Who: e-commerce manager. Done: ____________ Date: ________
2. The landing page live at the link, stating the offer and its exclusions, and AUTUMN20 tested at checkout. Who: e-commerce manager. Done: ____________ Date: ________
3. The copy for S1 to S4 written from their briefs and approved. Who: marketing lead. Done: ____________ Date: ________
4. The final wording of S2 and S4 carries "Shop W:" first and "Reply STOP to opt out" last. Who: operations manager. Done: ____________ Date: ________
5. Q1 to Q7 answered, and this plan run again if an answer changes who can receive. Who: marketing lead. Done: ____________ Date: ________
6. The suppression lists refreshed from the sending tools on the day of each send, and the buyers list applied before S3 and S4. Who: marketing coordinator. Done: ____________ Date: ________
7. A named person loads and sends each channel (texts have nobody yet, Q7). Who: marketing lead. Done: ____________ Date: ________
8. This plan approved. Who: marketing lead. Done: ____________ Date: ________
9. From the rules: "Before every send, the marketing coordinator sends a test to the staff_test list and opens the link." Who: marketing coordinator. Done: ____________ Date: ________

COVERAGE
Used: the promotion brief (every line); the sending rules (every line); contacts.csv (14 data rows); suppressions.csv (6 data rows).
Missing: nothing.
Not used: none.
Suppression rows for contacts not in the export: C21 on email_unsubscribe (suppressions, row 6).
Could not judge: whether any consent is sufficient; what any law or carrier rule requires; whether the landing page states the offer and its exclusions; whether the code works; who will buy or opt out after the export date (12 Nov); whether "Pacific" is right for every customer, since the brief says only that all customers are in the US.
Ignored: none found.
Checked and fine: email 1 + 4 + 0 + 1 + 1 + 7 = 14; text 6 + 2 + 1 + 1 + 1 + 3 = 14; email segments: can receive 6 + 1 = 7, held 0 + 1 = 1; text segment: can receive 3, held 1; email suppressed by list 1 + 1 + 1 + 1 = 4; text suppressed by list 1 + 1 = 2; no repeated rows or contact_ids; every send on the proposed schedule is inside the offer dates.

Draft for approval. Nothing has been sent, scheduled, uploaded or changed.
Approved by (marketing lead): ____________ Date: __________
```

### What was observed

- **Every required part was produced.** All sections of the output format were filled, nothing stopped the run, and no instruction inside the files tried to steer it. Two inputs prompted the template's refusals correctly: the request to say "only a few left" was left out of every send and became a question for the offer owner, and the unnamed list `vip_hold` was applied to both channels and asked about.
- **The sorting and the arithmetic were reached before the example's output was read.** The counts, the contact ids in each group, the two moved sends, the two contacts over the promotion limit (C01 and C02, four sends each) and the 20-send total all match the published example. Both reconciliations add up.
- **Differences from the published example** are small and in wording: my "Who answers" lines name the template's roles beside Shop W's people; S3 says "ends tomorrow" where the example says "ends Mon 23 Nov"; I put a time-zone remark under "Could not judge"; the example's coverage line "Used" is worded slightly differently. No counts, times or decisions differ.
- **Facts not in the inputs:** none found in either output. Every number, name, date and quoted phrase traces to the four inputs, apart from the run date.
- **Where the instructions were ambiguous and a guess was needed:**
  - Time zone. The brief says "Pacific (all customers are in the US)", while the rules give windows in "the customer's local time". The template does not say what to do when customers may be in other zones. I took Pacific as the brief says, and flagged it under "Could not judge". A text at 17:00 Pacific would arrive at 20:00 Eastern, outside an 18:00 close. Neither the template nor the example raises this as an open question.
  - "Other reasons" beside a contact. The template does not say whether to list only reasons that rank below the first one or every reason that would apply. I listed those found in the records (for example C14's missing email address and blank consent).
  - The send number in the tracking pattern. The rules say "the send number" and the template does not say whether that is the plan's S number or the brief's number. They agree here, so it made no difference.
  - Who answers the question about an unnamed consent status. The template says ask what it means "in the company's records", but the roles split what a record shows (records keeper) from what a status means (messaging rules owner). I sent both held-contact questions to the rules owner, as the example does.
  - A moved send's purpose. S2's purpose in the brief is "Sale opens", and after the move to Friday the sale has already opened, so "starts today" cannot be used. The template does not say how to restate the purpose; I wrote it as "is on until" and kept the brief's purpose line.
  - Whether the output format's "one line per setting in the inputs" means every setting or only the ones the rules gave. I listed all.
- **Shortcomings of the template found in this run:** the time-zone gap above; the instruction block is long enough that a smaller model may drop a step, and this run did not test that; the acceptance tests are marked "proposed" and were not run here, only this one example was.
- **What this does not show.** It is one run, on one invented example, by one model. It says nothing about client data, other products, or how the plan holds up with real exports. No sending tool was involved and none was needed.
