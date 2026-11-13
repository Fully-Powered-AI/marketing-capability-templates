# Promotional send plan: an invented example

*Illustrative example with invented data.* The company, the people, the contacts, the link (on the reserved .example domain), the dates and the counts below are all invented. Shop W is an invented online kitchenware shop with about thirty staff. Its marketing lead is planning a five-day autumn sale by email and text, with the marketing coordinator, who keeps the contact records and sends the emails, the e-commerce manager, who owns the offer and the sale page, and the operations manager, whom the company names as the owner of its sending rules. A content writer will write the copy once the plan is approved. First come the inputs the marketing lead supplied, in full, then the plan the workflow template returned.

## The inputs

### 1. Promotion brief

```
Promotion: Autumn kitchen sale, November 2026
Brand name: Shop W
Sale name: the Autumn Kitchen Sale
Offer (approved wording): 20% off all cookware and bakeware
Code: AUTUMN20, entered at checkout
Dates: Thursday 19 November 2026, 08:00, to Monday 23 November 2026, 23:59
Exclusions: gift cards and items already marked down
Standing term: free shipping on orders over $75
Link: https://shop-w.example/autumn-sale
Audience segments: past_buyers, newsletter
Proposed sends:
  1. Email, Thu 19 Nov, 08:00, past_buyers and newsletter. Sale opens.
  2. Text, Thu 19 Nov, 12:00, past_buyers. Sale opens, for customers who
     prefer texts.
  3. Email, Sun 22 Nov, 10:00, past_buyers and newsletter. Only people who
     have not bought since the sale opened. Reminder: the sale ends Monday.
  4. Text, Mon 23 Nov, 18:30, past_buyers. Only people who have not bought
     since the sale opened. Last day.
Time zone: Pacific (all customers are on the US West Coast)
Exports taken: Thursday 12 November 2026
Copy written by: content writer
Plan goes to: marketing lead
Note from the e-commerce manager: can we say we only have a few cast-iron
  pans left?
```

### 2. Shop W sending rules for promotions (the company's own document; owner: operations manager)

```
Email: promotional email goes only to email_consent "subscribed".
  "unsubscribed" excludes a person.
Text: promotional texts go only to text_consent "opted_in".
  "opted_out" and "never" exclude a person.
Texts go out between 10:00 and 18:00 in the customer's local time.
Start every send at least an hour before its window closes.
At most 1 promotional send per person per day, email and text together.
At most 3 promotional sends per person in one promotion.
No-send dates: none.
Suppression lists:
  email_unsubscribe: email only; records unsubscribes.
  hard_bounce: email only.
  text_optout: text only; records opt-outs.
  do_not_market: email and text (open complaints and refund disputes).
  staff_test: email and text.
Texts start with "Shop W:" and end with "Reply STOP to opt out".
Our email tool adds the company address and the unsubscribe link to
  every email.
Tracking: add ?src= then the channel and the send number, such as
  ?src=email-s1.
"Not bought since the sale opened": the marketing coordinator applies the
  store's buyers list on the morning of the send.
Email is loaded and sent by the marketing coordinator.
Before every send, the marketing coordinator sends a test to the
  staff_test list and opens the link.
```

### 3. Contact export (contacts.csv)

```
contact_id,segment,email_on_file,mobile_on_file,email_consent,text_consent
C01,past_buyers,yes,yes,subscribed,opted_in
C02,past_buyers,yes,yes,subscribed,opted_in
C03,past_buyers,yes,no,subscribed,
C04,past_buyers,yes,yes,subscribed,opted_out
C05,past_buyers,yes,yes,unsubscribed,opted_in
C06,past_buyers,yes,yes,subscribed,opted_in
C07,past_buyers,yes,yes,subscribed,imported
C08,newsletter,yes,no,subscribed,
C09,newsletter,yes,no,pending,
C10,newsletter,yes,no,subscribed,
C11,newsletter,yes,yes,subscribed,opted_in
C12,newsletter,yes,no,subscribed,
C13,wholesale,yes,yes,subscribed,opted_in
C14,past_buyers,no,yes,,opted_in
```

### 4. Suppression lists (suppressions.csv)

```
contact_id,list,added_on
C06,text_optout,2026-10-30
C10,hard_bounce,2026-08-14
C11,do_not_market,2026-11-03
C12,staff_test,2025-01-06
C14,vip_hold,2026-11-10
C21,email_unsubscribe,2026-09-02
```

## The plan the workflow template returned

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
- Files show: suppressions, row 5: C14 on vip_hold, added 2026-11-10. The rules do not mention vip_hold, so it is applied to email and text, and C14 receives nothing in this plan.
- Other reasons: no email address on file and a blank email consent (contacts, row 14)
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
