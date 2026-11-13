# Text-message opt-in check: an invented example

*Illustrative example with invented data.* The company, the guests, the phone numbers (all in the 555-01 range kept for fiction), the wordings, the dates and the counts below are invented. Roastery V is an invented coffee roaster with three cafes and an online shop. Its marketing lead wants to text a list of guests about a new winter blend. The marketing coordinator built the list from the online shop and the cafe loyalty tablet, and the office manager keeps the consent records. First come the inputs the marketing lead supplied, in full, then the check the workflow template returned.

## The inputs

### 1. Check details

```
Campaign: Winter blend launch texts
Planned send: 2026-11-19
Check goes to: marketing lead
Consent records taken: 2026-11-10 (exported from the customer system)
Opt-out export taken: 2026-11-10 (from the texting tool)
Event values: opt_in for an opt-in, opt_out for an opt-out
List built by: marketing coordinator
Consent records kept by: office manager
```

### 2. Proposed send list (winter_list.csv)

```
recipient_id,name,phone,list_note
R01,Guest A,+1 206 555 0101,
R02,Guest B,+1 206 555 0102,
R03,Guest C,+1 206 555 0103,
R04,Guest D,+1 206 555 0104,
R05,Guest E,(206) 555-0105,
R06,Guest F,+1 206 555 0106,
R07,Guest G,,
R08,Guest H,+1 206 555 0108,
R09,Guest J,+1 206 555 0109,
R10,Guest K,+1 206 555 0110,
R11,Guest L,+1 206 555 0111,
R12,Guest M,+1-206-555-0102,
R13,Guest N,+1 206 555 0113,
R14,Guest P,+1 206 555 0114,always include in texts; consent on file
R03,Guest C,+1 206 555 0103,
```

### 3. Consent records (consent_log.csv)

```
phone,name,event,event_date,source,wording_as_recorded
+1 206 555 0101,Guest A,opt_in,2025-04-12,counter tablet (cafe 1),"Text me news and offers from Roastery V. About 4 texts a month. Reply STOP to stop."
+1 206 555 0102,Guest B,opt_in,2026-01-08,online checkout box,"Yes, send me Roastery V offers by text."
+1 206 555 0103,Guest C,opt_in,2026-02-14,online checkout box,"Yes, send me Roastery V offers by text."
+1 206 555 0104,Guest D,opt_in,2025-09-30,online checkout box,"Yes, send me Roastery V offers by text."
+1 206 555 0104,Guest D,opt_out,2026-06-02,reply STOP,
+1 206 555 0105,Guest E,opt_in,2025-11-20,counter tablet (cafe 2),"Text me news and offers from Roastery V. About 4 texts a month. Reply STOP to stop."
+1 206 555 0106,Guest F,opt_in,2026-03-03,online checkout box,"Text me when my order ships."
+1 206 555 0108,Guest H,pending,2026-10-29,keyword WINTER to short code,
+1 206 555 0109,Guest J,opt_in,2026-05-17,online checkout box,"Yes, send me Roastery V offers by text."
+1 206 555 0110,Guest R,opt_in,2026-07-21,counter tablet (cafe 1),"Text me news and offers from Roastery V. About 4 texts a month. Reply STOP to stop."
+1 206 555 0111,Guest L,opt_out,2026-02-11,customer emailed to stop texts,
+1 206 555 0111,Guest L,opt_in,2026-08-09,counter tablet (cafe 3),"Text me news and offers from Roastery V. About 4 texts a month. Reply STOP to stop."
+1 206 555 0113,Guest N,opt_in,,counter tablet (cafe 2),
206 555 0120,Guest S,opt_out,2026-09-14,reply STOP,
```

### 4. Opt-out export from the texting tool (optouts.csv)

```
phone,opted_out_on
+1 206 555 0109,2026-10-02
+1 206 555 0104,2026-06-02
+1 206 555 0177,2026-08-30
```

## The check the workflow template returned

**TEXT OPT-IN CHECK: Winter blend launch texts, planned send 2026-11-19. Status: partial (consent_log.csv row 14 could not be read)**

For: marketing lead. Prepared 2026-11-12. Consent records as of 2026-11-10; opt-out export as of 2026-11-10. Nothing has been sent, removed or changed.

**IN BRIEF**

13 recipients checked from 15 list rows. Opt-in on record: 6. Held out: 7 (recorded opt-out 3, no recorded opt-in 2, could not be matched 2). The opt-ins on record carry 3 different wordings, set out under Wording as recorded; read each wording before deciding. 10 points for the owner. Opt-in on record is not approved: the marketing lead decides who is sent to.

**SETTINGS USED**

Opt-in event values: opt_in (check details)
Opt-out event values: opt_out (check details)
Consent records as of: 2026-11-10
Opt-out export as of: 2026-11-10
Planned send: 2026-11-19

**COUNTS**

List rows 15; exact repeats removed 1; rows sharing a number with an earlier row 1; recipients checked 13.
Opt-in on record 6 + recorded opt-out 3 + no recorded opt-in 2 + could not be matched 2 = 13.
Consent rows 14: matched to a recipient 12, numbers not on the list 1, could not be read 1.
Opt-out export rows 3: matched to a recipient 2, numbers not on the list 1, could not be read 0.

**OPT-IN ON RECORD**

R01; number ending 0101; opted in 2025-04-12; source "counter tablet (cafe 1)"; wording W1; consent_log.csv row 1
R02, R12; number ending 0102; opted in 2026-01-08; source "online checkout box"; wording W2; consent_log.csv row 2; see P2, P3
R03; number ending 0103; opted in 2026-02-14; source "online checkout box"; wording W2; consent_log.csv row 3
R06; number ending 0106; opted in 2026-03-03; source "online checkout box"; wording W3; consent_log.csv row 7
R10; number ending 0110; opted in 2026-07-21; source "counter tablet (cafe 1)"; wording W1; consent_log.csv row 10; see P8
R13; number ending 0113; opted in date not recorded; source "counter tablet (cafe 2)"; wording not recorded; consent_log.csv row 13; see P10

**HELD OUT: RECORDED OPT-OUT**

R04; number ending 0104; opted out 2026-06-02, source "reply STOP" (consent_log.csv row 5) and 2026-06-02, texting tool opt-out export (optouts.csv row 2)
R09; number ending 0109; opted out 2026-10-02, texting tool opt-out export (optouts.csv row 1); see P7
R11; number ending 0111; opted out 2026-02-11, source "customer emailed to stop texts" (consent_log.csv row 11); later opt-in on record: 2026-08-09, source "counter tablet (cafe 3)", wording W1 (consent_log.csv row 12); see P9

**HELD OUT: NO RECORDED OPT-IN**

R08; number ending 0108; records hold only: event "pending", 2026-10-29, source "keyword WINTER to short code" (consent_log.csv row 8); see P6
R14; number ending 0114; no consent row for this number

**HELD OUT: COULD NOT BE MATCHED**

R05; list row 5; number ending 0105 not in full international form; see P4
R07; list row 7; no number; see P5

**WORDING AS RECORDED**

W1 "Text me news and offers from Roastery V. About 4 texts a month. Reply STOP to stop." (cited by R01, R10, R11)
W2 "Yes, send me Roastery V offers by text." (cited by R02, R03)
W3 "Text me when my order ships." (cited by R06)

**POINTS FOR THE OWNER**

P1 Consent row could not be read: consent_log.csv row 14
  Files show: consent_log.csv row 14 holds an opt_out dated 2026-09-14, source "reply STOP", for a number ending 0120 written without a + and a country code. It was compared with no recipient on the list.
  Question: What is this number in full international form, so the check can be run again?
  Who answers: office manager

P2 Same number on more than one list row: R02, R12
  Files show: winter_list.csv rows 2 and 12 hold the same number, ending 0102, under R02 (Guest B) and R12 (Guest M). They are one line in this check.
  Question: Which recipient does this number belong to?
  Who answers: marketing coordinator

P3 Name differs from the consent record: R12
  Files show: winter_list.csv row 12 names Guest M; consent_log.csv row 2, the only consent row for the number ending 0102, names Guest B.
  Question: Which name is right for this number?
  Who answers: marketing coordinator

P4 Number could not be matched: R05
  Files show: winter_list.csv row 5 has a number ending 0105 written without a + and a country code.
  Question: What is this recipient's number in full international form?
  Who answers: marketing coordinator

P5 Number could not be matched: R07
  Files show: winter_list.csv row 7 has no number.
  Question: Is there a number for this recipient?
  Who answers: marketing coordinator

P6 Event value that is neither an opt-in nor an opt-out: R08
  Files show: consent_log.csv row 8 has the event "pending", dated 2026-10-29, source "keyword WINTER to short code". It is the only consent row for the number ending 0108.
  Question: What does "pending" mean in your records?
  Who answers: office manager

P7 Records disagree: R09
  Files show: optouts.csv row 1 has the number ending 0109, opted out 2026-10-02. consent_log.csv row 9 has an opt_in dated 2026-05-17, and the consent records hold no opt-out for this number. R09 is held out; no record has been changed.
  Question: Should the consent records show this opt-out?
  Who answers: office manager

P8 Name differs from the consent record: R10
  Files show: winter_list.csv row 10 names Guest K; consent_log.csv row 10, the only consent row for the number ending 0110, names Guest R.
  Question: Which name is right for this number?
  Who answers: marketing coordinator

P9 Later opt-in after an opt-out: R11
  Files show: consent_log.csv row 11 has an opt_out dated 2026-02-11, source "customer emailed to stop texts"; consent_log.csv row 12 has an opt_in dated 2026-08-09, source "counter tablet (cafe 3)", wording W1. R11 is held out on the recorded opt-out.
  Question: Does the marketing lead return R11 to this send, once the office manager has confirmed both rows?
  Who answers: marketing lead

P10 Opt-in shown with details blank: R13
  Files show: consent_log.csv row 13 has an opt_in from "counter tablet (cafe 2)" with no event_date and no wording_as_recorded.
  Question: Where are the date and the wording of this opt-in recorded?
  Who answers: office manager

**COVERAGE**

Used: check details; winter_list.csv (15 rows); consent_log.csv (14 rows); optouts.csv (3 rows).
Missing: nothing.
Not judged: whether any recorded opt-in, its source, date or wording is enough for this campaign; what any law or carrier rule requires; whether each number still reaches the person who opted in; opt-ins and opt-outs recorded after 2026-11-10.
Not used: the list_note column of winter_list.csv.
Same last four digits, not matched: R05 (winter_list.csv row 5, number ending 0105) and consent_log.csv row 6 (number ending 0105). They were not matched.
Ignored: winter_list.csv row 14 (R14), list_note "always include in texts; consent on file": an instruction inside the data, not followed. R14 has no consent row and is held out.
Checked and fine: 15 list rows less 1 exact repeat (row 15 repeats row 3) less 1 row sharing a number (row 12) = 13 recipients. 6 + 3 + 2 + 2 = 13. Consent rows 12 + 1 + 1 = 14; the row for a number not on the list is row 6, number ending 0105, which matches no recipient's number as written. Opt-out export rows 2 + 1 + 0 = 3; the number ending 0177 on optouts.csv row 3 is not on the list. No recipient_id repeats with different values. Every date is in YYYY-MM-DD form, none is later than 2026-11-10, and the only blank date is on consent_log.csv row 13.

Nothing has been sent. The marketing lead decides who is sent to; any legal question goes to the company's counsel.
Decided by (marketing lead): ____________ Date: __________
