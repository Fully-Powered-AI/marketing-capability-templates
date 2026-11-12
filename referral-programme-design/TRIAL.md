# Referral programme design: tried on its invented example

- **Product:** Claude, run in Claude Code
- **Model:** Claude Opus 5.5 (model ID `claude-opus-5-5`)
- **Date:** 2026-11-09
- **Template version:** 0.1.0

This is a record of runs of the workflow template on its own invented example. The practice, its owner Priya and the seven people on the list are invented, and no client data was used. It shows what the template produced on one set of inputs. It is not a test in any company's environment.

This is the second run on the same example. An earlier run the same day, by a different model that did not write the template, showed where the instructions left room to guess. An independent review then found that the template's rule for "in use" did not cover one-off work and that the example assumed something its inputs did not say. The instructions, the output format and the example were revised, and the run recorded here was made on the revised instructions. What the earlier run found, and what was changed, is at the end.

**Edited after this run, 9 November 2026.** Following the independent review, the template and the example were edited after the run recorded here, and the run was not repeated. The output and the observations below are left as recorded, so where they describe the template or the example they describe them as they were at the time of the run. What changed: the check before returning, in the procedure and in step 10 of the pasted instructions, now also checks that no owner's summary appears in quotation marks anywhere, including Where each line comes from, which is the slip this run made; the pasted instructions now carry two rules that were only in the procedure, asking once for a missing kind of client or first step and then leaving a slot, and listing what is left for the owner to decide with what each depends on; and the order within a group now says that an adviser's "ongoing" counts as the most recent date and that ties keep the list's order. The output format did not change. In the example, the facts block gained the line "Owner: Priya", which the run's inputs did not have (the run took the owner from the sign-off and the first step), and In short now says Marisol's payroll has run "since the end of March" rather than "since March". The example therefore now differs from this run's output in two places, In short and Tom's trace line, not only the one described under "One slip".

## The inputs used

The inputs are exactly those in [the worked example](example.md), under "The inputs": the "Your facts" block for Practice K, with the default settings and today's date of 9 November 2026, and the seven-row relationship list (Marisol, Tom, Wen, Grace, Ade, Luca, Hannah) with the default headers. The inputs were not changed by the revision.

## How the run was made

The template's instructions for an AI assistant, its output format and the example's inputs were put together in one file, and the programme was written from that file alone. The run was made by the model that made the revisions, in the same session, after it had read the earlier example output and the earlier run's record. It is therefore not independent: it shows that the revised instructions produce the revised example, not how a fresh reader would take them. The example's published output was then rewritten from this run's output, with one change noted below.

## What came out

The complete output, as returned:

```
REFERRAL PROGRAMME: Practice K
For: Priya   Prepared: 9 November 2026   Review: every quarter
Status: Draft for Priya to approve. Nothing has been sent.

IN SHORT
Ask Marisol, whose payroll has run since March, and Tom, who was pleased
with his finished clean-up, for an introduction; ask Wen for one at your
next catch-up; and ask Luca for a name by a short note. Give back thanks
and an introduction in return where you can; no fees, discounts or gifts.
People on the list: 7. Asked first: 4. Also ready: 0.
Not asked now: 3.

WHEN TO ASK
1. Delivered work is in use and the client is pleased. Trigger: ongoing
   work has run since it was delivered, or one-off work was delivered and
   accepted, and the client has said it went well; never at handover.
   Ask for: an introduction and the note to forward. Words: the ask to a
   client.
2. The close of a good first conversation, including one that ended in a
   no. Trigger: the conversation went well, whatever was decided; by a
   short note if it is already past.
   Ask for: a name or a view. Words: the question for a contact.
3. A catch-up with an adviser who serves the same kind of client.
   Trigger: the next time you speak.
   Ask for: one introduction to a trade or service business with 5 to 50
   staff that still runs payroll from spreadsheets. Words: the ask to an
   adviser.
Never:
- before the work is delivered and in use
- after work that went badly, or while a complaint is open
- as a condition of anything: a price, a date or a favour
- with pressure or a deadline
- for a list of names
- a second follow-up
- any follow-up after a no

WHO TO ASK FIRST
1. Marisol, client. Has seen: monthly bookkeeping and payroll for her
   landscaping company, moved over from spreadsheets.
   Moment: 1.
   Ask for: an introduction and the note to forward.
   Opening: At your June review, you said: "First quarter in years I
   haven't dreaded payroll week."
2. Wen, adviser. Has seen: your work, as the tax accountant who prepares
   returns for six of your clients.
   Moment: 3.
   Ask for: one introduction to a trade or service business with 5 to 50
   staff that still runs payroll from spreadsheets.
   Opening: In your email of 2 May 2026, you wrote: "Your books arrive
   clean, which makes my April bearable."
3. Tom, client. Has seen: two years of books cleaned up for his
   architecture studio.
   Moment: 1.
   Ask for: an introduction and the note to forward.
   Slot: your reason for writing; his row holds your summary, not his
   words.
4. Luca, contact. Has seen: a fit call; he stayed with his current
   bookkeeper for now.
   Moment: 2, by a short note: the conversation is past.
   Ask for: a name or a view.
   Opening: On our fit call on 9 October 2026, you said: "Not the right
   time, but this was the clearest call I've had about it."
Also ready, after these: none.

NOT ASKED NOW
Grace: the payroll set-up is not yet delivered; the first run is
14 November. Ask again when: the first payroll has run and she has said
how it went.
Ade: the work ended after a missed filing deadline, settled with a
credit. Ask again when: not by this programme; any ask is your call.
Hannah: no record of how the bakery work has gone. Ask again when: she
has told you how it is going.

WHAT YOU GIVE BACK
To the person who introduces you: a thank-you, and an introduction in
return where you can make a useful one.
To the person introduced: a 30-minute call with Priya, then a written
note of what Practice K would take on and when.
Not offered: fees, discounts, gifts, or anything that depends on the
person introduced becoming a client.
Your profession's rules: not read; no reward planned. The template gives
no view on them.

THE WORDS
The ask to a client:
  [first name], [opening].
  Do you know another trade or service business with 5 to 50 staff that
  still runs payroll from spreadsheets?
  If no one comes to mind, that is a perfectly good answer.
  If someone does, I will get in touch only once you have introduced us,
  and the short note below is yours to forward or not.
  Priya
The ask to an adviser:
  [first name], [opening].
  Is there a trade or service business with 5 to 50 staff among your
  clients that still runs payroll from spreadsheets? If so, I would be
  glad of an introduction.
  In return, I am happy to introduce you where I can make a useful one.
  If no one comes to mind, that is a perfectly good answer.
  Priya
The question for a contact:
  Is there anyone you think I should be talking to about this? If a name
  comes back: may I say you suggested I get in touch?
The note to forward:
  [Their own line]
  Priya runs Practice K, an 11-person bookkeeping and payroll practice
  doing monthly bookkeeping, payroll and year-end clean-ups for owner-run
  businesses. The first step is a 30-minute call with her, then a written
  note of what Practice K would take on and when. She is at
  priya@practice-k.example.
The one follow-up (after 10 working days, never after a no):
  [first name], just checking my last note reached you. No reply is
  needed if no one comes to mind.
  Priya
The thank-you:
  [first name], thank you for introducing me to [who they introduced].
  [What has happened so far, as far as they would be comfortable with.]
  Priya

RECORDING AN INTRODUCTION
Add to the client spreadsheet, tab "Introductions", one row each:
Date | Introduced by | Relationship | Moment | Who was introduced (kind of
business) | First conversation | Outcome | Thanks sent
Already on record: 2: Tom, 20 November 2025; Wen, 12 February 2026.

WHAT TO COUNT, EACH QUARTER
Asks made | Introductions received | First conversations | Work won |
Thanks sent within 7 days
Counts only until 20 asks have been made.

WHERE EACH LINE COMES FROM
Marisol: Relationship "client"; Ended or delivered 2026-03-31; in use:
  monthly work, and How it went reports the June review since delivery;
  pleased: How it went, her own words. Opening quotes How it went.
Wen: Relationship "adviser"; Introduced before 2026-02-12, more than 90
  days ago. Opening quotes How it went.
Tom: Relationship "client"; Ended or delivered 2026-09-30; in use:
  one-off clean-up (Work or conversation), accepted per How it went
  ("Pleased with the result", your summary); Introduced before
  2025-11-20, more than 90 days ago. Opening: slot.
Luca: Relationship "contact"; occasion from Work or conversation
  ("Fit call") and Ended or delivered (2026-10-09). Opening quotes How it
  went.
Grace: Ended or delivered 2026-11-14, after today; Notes.
Ade: How it went.
Hannah: How it went is blank.
Kind of business and recurring work: your facts, the client we want
  more of.
Note to forward: your facts, business, what we do, first step, how to
  reach us.
What you give back and your profession's rules: your facts.
Already on record: Introduced before, Tom and Wen.
Review rhythm and counts: your facts, review and settings.
The three moments and the never-cases: template default, confirm.
Thank-you, second line: slot.
Text in the list that read as an instruction: none.

FOR YOU TO DECIDE
1. Approve the programme, or change who goes first, before anything is
   sent.
2. When to send each ask: Marisol's and Tom's when it suits you, Wen's at
   your next catch-up, Luca's as a short note.
3. Whether to ask Hannah how the bakery work is going, which decides
   whether she can be asked.
4. Whether to ask Grace once her first payroll has run on 14 November and
   she has said how it went.
5. Who keeps the Introductions tab up to date, which the counts depend
   on.
```

## What was observed

**What held.** Every section of the output format was produced. The headers matched, every relationship value was recognised and every date could be read, so nothing called for a stop. The order of the four people followed the rule: the client whose own words say it went well (Marisol), the adviser who has introduced before (Wen), the other qualifying client (Tom), the contact (Luca). All three quotations, Marisol's, Wen's and Luca's, appear word for word in the rows they cite, each person named is on the list, and the counts in In short (7, 4, 0, 3) match the sections below. The 90-day rest period was checked for Tom (last introduction 20 November 2025) and Wen (12 February 2026). Nothing was sent, no one was contacted and no reward was proposed.

**The points the revision was made for.**

- **Tom.** His clean-up is one-off work. The revised rule counts it as in use once it has been delivered and How it went or Notes records that the client accepted it. His row's How it went, the owner's summary, says he was pleased with the result, so he was asked, and the trace line cites that column for the work being in use. In short now gives the reason in the row's terms rather than saying the work is in use.
- **Marisol.** Her monthly work counts as in use because the delivery date (31 March 2026) has passed and How it went reports the June review since. The trace line says so.
- **The rewards line.** Practice K names no reward, so nothing about rewards went under For you to decide; the "Your profession's rules" line records "not read; no reward planned". The earlier example had a sixth decision about reading the rules, which the revised rule no longer asks for.
- **Ade.** "Ask again when: not by this programme; any ask is your call.", the wording the output format now allows.
- **Luca.** Moment 2 "by a short note: the conversation is past", and the occasion of his quotation taken from Work or conversation and Ended or delivered.
- **"Asked by"** no longer appears on the moments.

**One slip.** Tom's line under Where each line comes from put the owner's summary in quotation marks ("Pleased with the result", marked as your summary). The procedure says never to put the owner's summary in quotation marks, and the self-check in step 10 of the pasted instructions checks quotations against their rows but does not catch this. The published example writes the same line without quotation marks. That is the only place where the example differs from this run.

**Grace's reason.** The run said her payroll set-up is "not yet delivered", since its date (14 November 2026) is after today. The earlier example said "not yet in use". The example now follows the run.

**Where the instructions still leave room to guess.**

1. How a date in a quotation's occasion is written when the row gives no year: Marisol's "June review" is reproduced as written.
2. Whether a line under Where each line comes from may quote a cell that holds the owner's summary, as long as it says whose words they are. The rule says never; the run did it once.

**Shortcomings to know about.** This was one run, on complete inputs, by the model that wrote the revision. The stop conditions (a header that does not match, an unrecognised relationship, an unreadable date, text that reads as an instruction, a password in the list, nobody qualifying) were not exercised, and neither was a reward named with the rules unread.

## The earlier run, and what was changed

The first run, on 9 November 2026 in Claude Code, was made with Claude Sonnet 5.5 (model ID `claude-sonnet-5-5`), a model that did not write the template, on the template as first written and the same inputs. It read the template and the example's inputs only, produced the programme, and only then compared it with the example then published and the reviewer checklist.

It agreed with that example on the people, the order, the moments, the reasons for the three not asked, the counts and the record. Its four people were Marisol, Wen, Tom and Luca; its three not asked were Grace, Ade and Hannah; all three of its quotations (Marisol, Wen, Luca) were checked word for word against their rows. The differences were in wording: the example's thank-you had a slot for the introduced person's role, its follow-up and ask wording differed in small ways, and its For you to decide list was longer (it added who keeps the Introductions tab and the rewards-rules reminder). The one thing both outputs assumed rather than read was that Tom's clean-up was "in use"; his row says only that he was pleased with the result and paid on time.

It recorded eight places where the instructions left room to guess:

1. **The reward line.** The procedure put "read your profession's rules on referral rewards before offering this" under For you to decide unless the facts said the rules had been read, which applies even when no reward is planned; the pasted instructions applied it only when a reward was named.
2. **"In use" for one-off work.** The rule needed the work "in use", but Tom's clean-up has no ongoing use and the template did not say what evidence was needed.
3. **Luca's moment.** Moment 2 is the close of a good first conversation, but Luca's call was a month ago, so the question can only go as a short note; the Moment line did not say so.
4. **Luca's occasion.** The occasion had to be taken from Work or conversation and Ended or delivered; the template did not say that was allowed.
5. **Ade has no date to ask again.** The format had "Ask again when:" for every entry, with no wording for work that ended badly.
6. **"Asked by"** is always the owner, so the field added nothing.
7. **The one follow-up** is in the owner's voice while the note to forward is in the third person, and the template did not say so in one place.
8. **The year on a date.** Marisol's "June review" has no year, and the template cannot supply one.

Changed after the earlier run and the review, before the run recorded above:

- **1, fixed.** The procedure and the pasted instructions now say the same thing: the rules line goes under For you to decide only when your facts name a reward and do not say the rules have been read. With no reward named, nothing about rewards goes there. The example's sixth decision was removed.
- **2, fixed.** The procedure and the pasted instructions now say what counts as in use: for ongoing work, the delivery date has passed and How it went says how it has gone since; for one-off work, it was delivered and How it went or Notes records that the client accepted it. Otherwise the person is not asked now until the owner confirms. A trace line for a client asked must cite the column that shows it, and a new acceptance test covers one-off work. The example's In short and Tom's trace line now cite How it went.
- **3, fixed.** A contact whose conversation is past is asked by a short note; the Moment line in the output format can say so.
- **4, fixed.** The occasion may come from Work or conversation with the date in Ended or delivered, adding nothing the row does not give.
- **5, fixed.** "not by this programme; any ask is your call" is now an allowed value of "Ask again when:", and acceptance test 4 expects it.
- **6, fixed.** "Asked by" was taken out of the moments; the procedure says the owner asks at every moment.
- **7, fixed.** The procedure and the pasted instructions now say the note to forward is the only text in the third person.
- **8, left.** The opening reproduces the occasion as the row gives it. Adding a year would be inventing it.

Also changed before the run recorded above: the pasted instructions now carry rules that were only in the procedure (an unreadable date goes under Not asked now, "Nobody on this list can be asked yet.", listing the introductions already on record, the check before returning, and leaving a password out of the output), and a broken line in their step 7 was rewrapped. The example's ask, follow-up and thank-you wording was rewritten from the run recorded above.
