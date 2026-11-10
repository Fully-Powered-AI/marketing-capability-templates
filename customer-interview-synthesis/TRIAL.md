# Customer interview synthesis: one trial on the invented example

- Product: Claude, run in Claude Code (version 2.1.322, run without tools)
- Model: Claude Fable 5.2
- Date: 2026-11-09

The inputs are the invented example published with this capability template. The company, the studios, the people and every quoted word are invented. No client data was used, and this is a record of one run, not of use in a client's environment.

This is the third run. Two earlier runs the same day, on earlier drafts of the instructions, each found places where they were unclear, and the instructions were revised after each. Before this run the instructions and the example were changed once more, for a different reason: a review of where the template's ideas came from. This file records the third run in full; what the earlier runs found and what was changed is listed near the end.

## Inputs used

The inputs in [the worked example](example.md), exactly as written there: the "Your facts" block (what the company sells, the question, the decision, the belief, the bar, the permission rule, the minimum of five independent studios, who it is prepared for and who approves public use) and the six call notes N1 to N6 from five studios. The run was given the template's instructions for an AI assistant, its output format, those inputs and the date. It was not given the example's own synthesis, the rest of the template or the earlier runs.

No recency window is given in the example's inputs, so the template's starting value of twelve months applied. No kinds of customer were named to be kept apart.

## How it was run

The instruction block and the output format were given as the only instructions to a new session started in an empty folder, with no tools, no project files and no saved settings loaded. The inputs and the date followed as one message, and the run was one pass. The assistant asked no questions, because the question, the belief, the bar and the notes were all present. Nothing in the notes read as an instruction, no note was unreadable, and no stop condition applied.

After the run, a short script compared every string in double quotation marks in the output with the inputs, ignoring only line breaks. All 43 distinct strings (customers' passages, the interviewer's questions and phrases quoted from the facts) appear word for word in the inputs.

## What came out

The complete output, unedited:

```
CUSTOMER INTERVIEW SYNTHESIS: Instructor pay, problem or settled chore
Prepared for: the product lead   Date: 9 November 2026   Customers: owners and studio managers of independent studios with one to three sites
Status: Prepared for review. Internal. This document clears no quotation for use outside the company.

## THE QUESTION
Do studio owners describe working out instructor pay as a problem they would pay to be rid of, or as a chore they have settled into? For: whether to build an instructor-pay add-on as a new product line next year.

## THE BELIEF AND THE BAR (as written before the notes were read)
We believed: Owners lose hours every month working out instructor pay by hand and want it done for them.
We would call it wrong if: fewer than three of the independent studios describe working out pay, unprompted, as costing them time or money; or two or more say their current way of working out pay is fine.

## IN SHORT
It splits: two of five studios describe working out pay as a burden they have already spent time or money on, two say their current way is fine, and the pain raised most widely is unrecorded cover and swaps, not the pay sums.

Confidence: Medium (the lowest among themes 1 and 2)

The bar for calling the belief wrong: reached

- **Fewer than three of the independent studios describe working out pay, unprompted, as costing them time or money:** 2 of 5 independent sources (Studios A and C), both owners; 2 unprompted. Reached, but this took judgement and the result depends on it.
  - Studio C is counted on money already paid to a freelancer; its "dread" passage names no time or money. Without C the count is 1 and the condition is still reached.
  - Studio D is not counted. The owner lost "most of a Sunday" finding out who taught, and when asked said the pay sums themselves are fine.
  - Studio E is not counted. The owner states a price for pay ("forty dollars a month") but describes it as fine.
  - Counting either D or E makes 3 and the condition is not reached.
- **Two or more say their current way of working out pay is fine:** 2 of 5 independent sources (Studio B, studio manager; Studio E, owner); 2 unprompted. Reached.
  - Studio D's owner also said "The sums are fine once I know who taught" (asked). It is not counted because pay at that studio still goes out wrong; the result does not depend on it.

The conditions are joined by "or". The second is reached without judgement, so the bar is reached either way.

The belief: Disputed (the bar for calling it wrong was reached)

## COVERAGE
Notes supplied: 6. Read: 6. Unread: none.
Independent sources: 5 (N4 and N5 are the same studio). Speakers: 4 owners, 2 studio managers.
Passages kept: 17.
Text that read as an instruction: none.
The minimum of 5 independent sources is met.
Notes older than twelve months: none.
No kinds of customer were set to be kept apart.
Left out: site counts, instructor counts and one mention of a site count inside a quotation, so that no studio can be singled out. No personal details needed leaving out.

## THEMES

**1. Unrecorded cover and swaps are what make pay come out wrong and take time at month end.**

Reading (ours, not the customers'): The cost sits in the record of who taught, before any pay is worked out. A tool that calculates pay from the schedule would inherit the same errors.

In their words:
- "Swaps are what kill me. The rota says one thing, the group chat says another, and pay follows the rota." (owner, climbing and fitness studio; N4, 15 October 2026; anonymous; unprompted)
- "I spent most of a Sunday in September going back through messages to see who actually taught." (owner, climbing and fitness studio; N4, 15 October 2026; anonymous; unprompted) *Counts for more: recent occasion in detail, time already taken.*
- "The sums are fine once I know who taught. It's knowing who taught." (owner, climbing and fitness studio; N4, 15 October 2026; anonymous; asked: "And working out the pay itself?") *Counts for more: a correction of the question.*
- "What I see is instructors asking me why their pay is short, and it's nearly always a swap nobody recorded." (studio manager, climbing and fitness studio; N5, 15 October 2026; anonymous; unprompted)
- "The bad part is cover. When someone swaps a class by text the system still shows the old name, and I only find out when the wrong person gets paid." (studio manager, pilates studio; N2, 8 October 2026; anonymous; unprompted)
- "Last month I underpaid one of my instructors for two cover classes that never made it onto the schedule, and she found it before I did. That was a horrible conversation." (owner, yoga studio; N1, 6 October 2026; anonymous; unprompted) *Counts for more: recent occasion in detail.*

Against it: None in these notes; Studios C and E did not raise swaps or cover going unrecorded.
Says one thing, does another: none.
Confidence: High (three independent sources, Studios A, B and D, raised it unprompted)
Bears on: the decision. The most widely shared month-end pain is in the schedule record, which a pay add-on would rely on.

**2. Where pay rates vary by class, working out pay by hand is a burden owners have already spent time or money trying to fix.**

Reading (ours, not the customers'): The two studios with rate rules describe pay much as the belief does, and neither fix they tried held. The two studios that call pay fine have a flat rate or an accountant.

In their words:
- "I do instructor pay on the last Sunday of the month with the class export open on one screen and a spreadsheet on the other. It's three hours I never get back." (owner, yoga studio; N1, 6 October 2026; anonymous; unprompted) *Counts for more: hours already taken.*
- "I tried the payroll bureau's template. It can't change the rate when a class goes over twelve people, so I went back to my own sheet." (owner, yoga studio; N1, 6 October 2026; anonymous; unprompted) *Counts for more: something already tried.*
- "Pay day is the one day a month I dread. Tiered rates, bonuses for full classes, cover at a different rate. I've got a spreadsheet only I understand." (owner, cycling and strength studio; N3, 13 October 2026; not for use; unprompted)
- "We paid a freelancer to build a sheet with formulas last year." (owner, cycling and strength studio; N3, 13 October 2026; not for use; unprompted) *Counts for more: already paid for.* The owner went on to say it broke when the studio expanded.

Against it:
- "Month end? Pay's the easy part. Everyone's on a flat rate per class, I count the classes, done in twenty minutes." (studio manager, pilates studio; N2, 8 October 2026; anonymous; unprompted) *A correction of the question.*
- "Month end is fine. My accountant runs pay from the class export, costs me forty dollars a month, I never think about it." (owner, dance and barre studio; N6, 20 October 2026; anonymous; unprompted) *A correction of the question; already paid for.*
- "The sums are fine once I know who taught." (owner, climbing and fitness studio; N4, 15 October 2026; anonymous; asked: "And working out the pay itself?")
- Note-taker's summaries: Studio B said it would not be worth paying for at their size (N2); Studio E has no interest in a pay add-on (N6).

Says one thing, does another:
- Studio A's owner says the three hours are lost, but the note-taker's summary records that a bookkeeper was considered and not hired (N1).
- Studio B's manager said "Oh, for sure. Put me down for one." (N2; anonymous; asked: "A tool that worked out pay for you would save you time, wouldn't it?"), but the summary of the same call says it would not be worth paying for. This passage is an agreement to a question that offered the answer and a promise about the future; shown, not counted.

Confidence: Medium (only two independent sources, Studios A and C)
Bears on: the belief. It says what the belief says for two studios; three others say the opposite about the sums. This is a difference between studios, not an average.

**3. Owners and managers will not accept software settling pay or the rota without a person saying yes.**

Reading (ours, not the customers'): Even the owner who most wants pay done wants to approve the result. The two passages are about different things (pay and the rota) but make the same demand.

In their words:
- "I press a button, I get a list per instructor I can check in ten minutes, and then I approve it. I still want to be the one who approves it." (owner, cycling and strength studio; N3, 13 October 2026; not for use; unprompted)
- "I'd never want software changing who's down as teaching without one of us saying yes." (studio manager, climbing and fitness studio; N5, 15 October 2026; anonymous; unprompted)

Against it: None in these notes; Studios A, B and E did not raise it.
Says one thing, does another: none.
Confidence: Medium (only two independent sources, Studios C and D)
Bears on: the decision, as a condition on anything built for pay or swaps. It also qualifies "want it done for them" in the belief.

## THEIR WORDS
For the problem:
- "It's knowing who taught." (N4, anonymous)
- "Swaps are what kill me." (N4, anonymous)
- "a swap nobody recorded" (N5, anonymous)
- "three hours I never get back" (N1, anonymous)
- "a spreadsheet only I understand" (N3, not for use)

For what they want:
- "I press a button, I get a list per instructor I can check in ten minutes, and then I approve it." (N3, not for use)

What holds them back:
- "I still want to be the one who approves it." (N3, not for use)
- "so I went back to my own sheet" (N1, anonymous)
- "done in twenty minutes" (N2, anonymous)
- "I never think about it." (N6, anonymous)

May be used outside the company: nothing is cleared by this document. Passages from N1, N2, N4, N5 and N6 are anonymous and could be used without the person or the studio, only on the marketing lead's approval. N3 is not for use.

## WHAT ELSE THEY TRIED OR CONSIDERED
- **Own spreadsheet against the class export:** "with the class export open on one screen and a spreadsheet on the other" (owner, yoga studio; N1, 6 October 2026; anonymous; unprompted). Studio C uses the same approach: "a spreadsheet only I understand" (N3, not for use, unprompted).
- **Payroll bureau's template, abandoned:** "It can't change the rate when a class goes over twelve people" (owner, yoga studio; N1, 6 October 2026; anonymous; unprompted).
- **Freelancer-built sheet, broke:** "We paid a freelancer to build a sheet with formulas last year." (owner, cycling and strength studio; N3, 13 October 2026; not for use; unprompted).
- **Accountant:** "My accountant runs pay from the class export, costs me forty dollars a month" (owner, dance and barre studio; N6, 20 October 2026; anonymous; unprompted).
- **Counting by hand on a flat rate:** "I count the classes, done in twenty minutes." (studio manager, pilates studio; N2, 8 October 2026; anonymous; unprompted).
- **Reading back through messages:** "going back through messages to see who actually taught" (owner, climbing and fitness studio; N4, 15 October 2026; anonymous; unprompted).
- **Bookkeeper, considered and not hired:** note-taker's summary, N1.
- **Nothing tried for pay:** note-taker's summary, N2.

## LEADS (not findings)
1. Owners cannot see which classes lose money once the instructor is paid (1 independent source). "What I can't see is which classes lose money once I've paid the instructor. I'd pay for that tomorrow." (owner, dance and barre studio; N6, 20 October 2026; anonymous; unprompted). The second sentence is a promise about the future; shown, not counted.
   Would become a finding if: owners at three or more studios raise, unprompted, that they cannot see class-level profit after instructor pay.
2. Pay depends on one person who alone understands how it is worked out (1 independent source). "If I'm ill at month end nobody gets paid right. That's the part that scares me." (owner, cycling and strength studio; N3, 13 October 2026; not for use; unprompted).
   Would become a finding if: owners at three or more studios with varying rates describe, unprompted, pay going wrong or stopping when they are away.

## STILL UNKNOWN
1. What any studio would pay for a pay add-on. No customer names a price they would pay; the only prices are what Studio E pays its accountant and the unstated sum Studio C paid a freelancer. Who could answer: owners of studios with varying rates.
2. How many hours pay takes at Studio C. The belief says "hours every month"; only Studio A states hours. Who could answer: the owner at Studio C.
3. Whether rate complexity is what separates the studios that suffer from those that do not. Studios D and E did not describe their rate structures. Who could answer: the owners at Studios D and E.
4. How much the opening question shaped the answers. Five of six calls opened by asking about a month end that "went badly", which invites a problem. Two studios rejected the premise. Who could answer: the interviewer, with a neutral opening on further calls.
5. Whether Studio C's words may be used at all. Permission was not asked because the call ran over. Who could answer: the owner at Studio C, if a person at the company decides to ask.

## SOURCES
| Note | Date | Role, kind of business | Business reference | Permission | Read |
|---|---|---|---|---|---|
| N1 | 6 October 2026 | Owner, yoga studio | Studio A | Anonymous | Read |
| N2 | 8 October 2026 | Studio manager, pilates studio | Studio B | Anonymous | Read |
| N3 | 13 October 2026 | Owner, cycling and strength studio | Studio C | Not asked: not for use | Read |
| N4 | 15 October 2026 | Owner, climbing and fitness studio | Studio D | Anonymous | Read |
| N5 | 15 October 2026 | Studio manager, climbing and fitness studio | Studio D (same source as N4) | Anonymous | Read |
| N6 | 20 October 2026 | Owner, dance and barre studio | Studio E | Anonymous | Read |

## FOR THE READER TO DECIDE
- Whether to build the instructor-pay add-on next year, given the belief is Disputed. The product lead.
- Whether to accept the reading of the first condition of the bar (Studios D and E not counted). The bar is reached either way. The product lead.
- Whether the swap and cover record (theme 1) should be looked at before, or instead of, a pay add-on. The product lead.
- Whether to run further calls with studios that have varying rates, which is where theme 2 falls short of a High finding. The product lead.
- Whether anyone goes back to Studio C to ask permission. The product lead.
- Whether any quotation is used outside the company. The marketing lead.

Nothing was left incomplete.
```

## What was observed

Every section of the output format was produced. The bar was read one line per condition, each marked reached, and the belief was marked Disputed with the rule that set it. The run reached the same verdict as the published example, the same three themes with the same confidence levels (High for unrecorded swaps and cover, Medium for the burden of working out pay where rates vary, Medium for approval), the same confidence for the answer (Medium, the lowest among the themes it rests on), the same count on the first condition of the bar (2 of 5), the same count of independent sources (five, with N4 and N5 counted once) and the same count of passages kept (17).

Against the template's review checklist: the question, belief and bar are copied as supplied; no summary text is in quotation marks; the two speakers from one studio are counted once; each theme is a claim with its "Against it" line and the rule behind its confidence; the one agreement to a question that offered the answer is shown, marked and not counted; no person or company is named, citations give the role and a general description of the business only, and each passage shows its permission; the belief is Disputed because the bar for calling it wrong was reached. The check of a sample of quotations by someone who was on the calls is a person's step and was not done; the script above stands in for it only as far as wording goes.

Two things the second run got wrong came out right this time. The first theme's "Against it" line reads "None in these notes" and names the studios that did not raise the subject, as the example does. And no lead rests on a note-taker's summary: both leads carry a customer's exact words.

Differences from the published example:

- **The second condition of the bar.** The run counted two studios (B and E) as saying their way of working out pay is fine and left Studio D out, because pay at that studio still goes out wrong. The example counts three, with Studio D's answer marked as given when asked. The condition is reached on either count.
- **A muddled line under the first condition.** The run said the condition "took judgement and the result depends on it", and in the next line said that without Studio C the condition is still reached. Both are true of different sources (leaving C out changes nothing; counting D or E would), and the run goes on to say so, but the first sentence reads as a contradiction until the later lines are read.
- **A second lead.** The run moved "If I'm ill at month end nobody gets paid right." out of the second theme and made it a lead of its own, that pay depends on one person. The example keeps the passage under the second theme and has one lead. The instructions say a single-source passage that supports a numbered theme stays with it and is a lead only if it makes a claim no theme makes; the run read it as a separate claim.
- **"Says one thing, does another."** Besides the pilates manager's "Oh, for sure. Put me down for one.", the run again listed the yoga owner's three hours against the summary that no bookkeeper was hired. That is a weak case: not hiring someone does not contradict the three hours.
- **"What holds them back."** This line was new in this run. The run filled it with three passages about habit ("so I went back to my own sheet", "done in twenty minutes", "I never think about it.") and with "I still want to be the one who approves it.", which is a condition on a fix more than a worry about changing. The example lists the first and third of those and the climbing studio manager's sentence about software changing the rota. The line can be read more than one way.
- **A cut quotation.** The run quoted only the first sentence of the freelancer passage and left out "It broke when we added the third site.", because it holds a site count, and said so under Coverage. The example quotes both sentences.
- **Lines the format does not have.** Notes in italics after some passages saying why they count for more; indented lines under each condition of the bar on how borderline sources were counted; "No kinds of customer were set to be kept apart" and a "Left out" line under Coverage; and a closing line on what could not be completed, which the instructions ask for.
- **Layout.** The run used headings, bold type, bullets and a table for Sources where the output format is a plain-text block. The content of the sections matches.

Where the instructions were unclear, or a guess was needed, in this run:

1. **Counting a source toward a condition still takes judgement.** The instructions now ask the assistant to name each such source and say whether the result depends on it. The run did, at length, and the result is harder to read than the example's two lines.
2. **What belongs under "What holds them back".** See above. A customer's condition on a fix, a habit and a worry all landed there.
3. **When a passage inside a theme is a separate claim.** See the second lead above.
4. **"Says one thing, does another"** still depends on what counts as the record. In notes like these the only record is the note-taker's summary of the same call.
5. **How far to follow the layout of the output format.** The instructions say to use it and do not say that it is plain text.

Nothing was changed after this run. The five points above are left as they are.

Edited after the recorded run, 9 November 2026, following the independent review. The template was not run again, and the output and observations above are left as recorded.

1. In the instructions, the third thing read from each note, "what made them look for something better", now reads "the event that started them looking", and the habit in the seventh, "a habit that makes the present way easy to keep", now reads "a habit that suits them as things are". Both were reworded so that neither follows a source's wording; the rules did not change. One over-long line in the instructions was re-wrapped. Where this record quotes the earlier wording, it is the wording the run was given.
2. Outside the instructions, the template's sentence that the business reference "appears only under Sources" now says it is left out of citations, which is what the output format and the example do. The contrast between a topic and a theme, and the invented instruction in the seventh acceptance test, were reworded.
3. The example's inputs gained a line giving the date of the synthesis, 26 October 2026. The run was given the inputs without that line and 9 November 2026 as the date, which is why its header carries a different date from the example's; that difference is not in the list above.
4. The example's first condition of the bar gained the note on judgement that the instructions ask for: which studios were and were not counted, and that counting Studio D or E would change the result. When the run was compared with it, the example had two lines for the conditions and no such note.
5. Four wordings in the example's synthesis were corrected: the two studios' rates are described as changing with the class where "tiered" was stated as fact for both, theme 1's reading says the three studios raised it "without being asked about swaps or cover", and the promise in the lead is "shown, not counted". The example's verdict, themes, counts and confidence levels are unchanged.

## What the earlier runs found, and what was changed

After the first run, on the first draft:

1. "Met" and "Not met" could be read two ways, and one checklist line read as if "met" meant the belief passed. Now: the line reads "The bar for calling the belief wrong: reached / not reached", with one line per condition; a fixed rule maps the bar to Supported, Disputed or Not settled; the checklist line states the same rule. "Not reached" as a verdict on the belief was renamed "Not settled" so that it cannot be confused with the bar.
2. No rule for the confidence of the one-sentence answer. Now: the lowest among the themes it rests on, named.
3. "Unprompted" after an open follow-up question. Now: a passage is "asked" only when the question named its subject or offered the answer; answers to open questions, opening or follow-up, are unprompted. The example's citations were changed to match.
4. Words marked "not for use". Now: not for use means not outside the company; such words are quoted in the internal synthesis, marked, and their source counts, unless the company says otherwise.
5. "Says one thing, does another" had only a summary to compare with. Now: the note-taker's summary of the same call is named as something a customer's words may be compared with.
6. Shortened quotations. Now: part of a sentence may be quoted when it is one unbroken run of the customer's words and the cut does not change the meaning.
7. The Coverage line read oddly at zero. Now: "none", or the count with the notes.
8. Detail in the citation. Now: the role and one general description; no numbers of sites or staff and no place.

The first run also produced four themes and three leads where the example has three and one. The instructions were changed to say the reverse of a theme is not a second theme, a single-source passage that supports a numbered theme stays with it, and a promise or an agreement to a leading question makes no lead.

After the second run, which produced three themes and two leads:

1. One of its leads rested on a note-taker's summary with no exact words. Now: a point that rests only on a summary is neither a theme nor a lead and goes under "Still unknown".
2. Counting a source toward a condition of the bar took judgement that the output did not have to show. Now: the assistant names any source whose counting took judgement and says whether the result depends on it.

Before the third run, after a review of sources and not because of anything a run found:

1. The seventh thing read from each note was "what would hold them back, and what they would not hand over". The second half was taken out, with its line under "Their words", because the idea came from a package that cannot be credited under this template's rules. The seventh thing is now what holds a customer where they are: a worry about changing, or a habit that makes the present way easy to keep.
2. Four phrases in the template, two of them inside the instructions, were reworded so that no sentence follows a source's wording. The rules they state did not change.
3. In the example, the leading question in note N2 and the answer to it were rewritten. The note still holds one agreement to a question that offered the answer.

## Shortcomings of this trial

It is one run, by the same family of model that wrote the template, on tidy notes written for the purpose, and it follows two revisions made in answer to earlier runs on the same example, so the example and the instructions have been fitted to each other. It did not exercise the stop conditions (a missing question, an unreadable note, an instruction inside a note, a request to improve a quotation), a thin set of fewer than five sources, a note with only summary, a bar that is not reached, or kinds of customer kept apart. Real call notes are longer and messier than these.
