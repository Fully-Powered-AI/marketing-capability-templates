# Trial: Copy edit with a change list, run on its invented example

- **Product:** Claude, run in Claude Code
- **Model:** Claude Opus 5.5 (model ID claude-opus-5-5)
- **Date:** 2026-11-09
- **Template version:** 0.1.0

This is a record of one run of the workflow template on its own invented example. The inputs are the invented Kestrel Ridge example in `public/example.md`; the firm, its statements and its draft are invented, and no client data was used. It shows what the template produced once, on one set of inputs. It is not a test in any company's environment.

This is the second run on the same example. An earlier run the same day, by an assistant that had not written the template, showed where the instructions left room to choose; the instructions and the example were revised, and the run recorded here was made on the revised instructions. This run was made by the assistant that made those revisions and had read the example's published output, so its agreement with the example is weaker evidence than an independent run would be. What the earlier run found, and what was changed, is at the end.

## Inputs used

From `public/example.md`, section "The inputs", unchanged: where it appears, who reads it, the action and the run details (approver, who runs it, the date); your facts; the nine statements you can support (comma-separated export with the headers `Statement`, `Support`, `Checked on`) and the three-item do-not-say list; the two approved lines; and the twelve-line draft with its one comment. The instruction block and output format are those in `member/template.md`, version 0.1.0, as revised.

## What came out

```
COPY EDIT: Office cleaning section, services page
For: the operations director   Run by: the marketing coordinator   Date: 9 November 2026
Where it appears: the Office cleaning section of the services page   Reader: office managers and owners of small and mid-sized offices who want to replace their current cleaner   Action: book a free walkthrough
Status: Proposed edit, for approval. Nothing has been published or sent.

VERDICT
Ready with gaps: every claim left in the edited copy is Kept or Brought back, but line 3 holds a [Need] for the area served, which the reader needs before the copy can be used.
Coverage: 12 lines in the copy: 9 changed, 3 unchanged, of which
2 are approved wording. 19 claims: 3 kept, 7 brought back to
support, 9 proposed cuts.
Inputs: the draft; where it appears, reader, action, approver, who runs it and the date; your facts; 9 statements (headers Statement, Support, Checked on, as expected) and a do-not-say list of 3 items; 2 approved lines. None missing. The comment after line 8 is not copy and is not counted as a line.

SECTION PURPOSES
Office cleaning: answers "Who would clean our office, to what standard, and what happens if something is missed?". Action: book a free walkthrough.

EDITED COPY
# Office cleaning

We clean offices of 5 to 150 desks in [Need: the towns or areas you serve].

Our crews clean 140 offices every week.

Our standard cleaning products are fragrance-free.

If you report a missed area by 10am, a crew comes back the same working day. Report it later and we return the next working day. Return visits are free.

You can book a visit for any time between 6pm and 7am on weekdays, or at any time on Saturday and Sunday.

Every cleaner passes a background check before their first shift, and we hold $2,000,000 of public liability insurance.

We'll walk your office with you and send a fixed quote within two working days.

[Button] Book a free walkthrough

CHANGE LIST
1. Line 2
   Before: "In today's busy world, a clean office isn't a luxury — it's a necessity."
   After: (cut)
   Why: a stock opener and a turn-around contrast, and nothing in the inputs would make either specific.
   Rule: specific; habit: stock opener; habit: turn-around contrast; habit: dash against house style
2. Line 3
   Before: "Kestrel Ridge is the leading commercial cleaner in the valley, serving businesses of all sizes across the region."
   After: "We clean offices of 5 to 150 desks in [Need: the towns or areas you serve]."
   Why: "leading" is barred without an independent source, "all sizes" is wider than statement 2, the reader needs the area served and no input gives it, and your facts name the company "we".
   Rule: claim cut; claim brought back; specific; voice
3. Line 4
   Before: "Our fully vetted, trained crews clean over 200 offices every week, so you never have to think about it."
   After: "Our crews clean 140 offices every week."
   Why: statement 1 supports 140, not over 200; "trained" and the closing promise have no support; the background check is stated on line 9.
   Rule: claim brought back; claim cut; clarity; habit: sentence that hinges on "so"
4. Line 5
   Before: "We use eco-friendly products. No harsh chemicals, no strong smells, no residue."
   After: "Our standard cleaning products are fragrance-free."
   Why: of the four qualities, only fragrance-free standard products are supported (statement 6).
   Rule: claim cut; claim brought back; habit: run of absences
5. Line 6
   Before: "Guaranteed satisfaction. If anything is missed, we'll come back within 24 hours and fix it free of charge."
   After: "If you report a missed area by 10am, a crew comes back the same working day. Report it later and we return the next working day. Return visits are free."
   Why: guarantee wording is on the do-not-say list, and statement 5 times the return visit from a 10am cut-off in working days, which can take longer than 24 hours.
   Rule: claim cut; claim brought back; habit: verbless phrase standing in for a sentence
6. Line 7
   Before: "Flexible scheduling, tailored to you."
   After: "You can book a visit for any time between 6pm and 7am on weekdays, or at any time on Saturday and Sunday."
   Why: "flexible" and "tailored to you" stood in for the booking hours statement 7 gives.
   Rule: claim brought back; specific; habit: verbless phrase standing in for a sentence
7. Line 8
   Before: "Our clients typically save 30% compared with keeping cleaning in-house."
   After: (cut)
   Why: savings figures are on the do-not-say list, and no statement supports the figure.
   Rule: claim cut
8. Line 9
   Before: "The part that matters most is trust: every cleaner is background-checked and insured."
   After: "Every cleaner passes a background check before their first shift, and we hold $2,000,000 of public liability insurance."
   Why: the insurance is the company's, not each cleaner's (statement 4), and the opening announced the point instead of making it.
   Rule: claim kept; claim brought back; specific; habit: label-first sentence; habit: colon used to stage a reveal
9. Line 10
   Before: "Ready to get started?"
   After: (cut)
   Why: a filler transition that could sit on anyone's page; the button carries the action.
   Rule: specific; habit: stock opener or filler transition

CLAIMS
1. Line 3: "the leading commercial cleaner in the valley". Proposed cut
   Support: your do-not-say list: "leading" without an independent published source
2. Line 3: "businesses of all sizes". Brought back
   Support: statement 2, "We clean offices of 5 to 150 desks."
3. Line 3: "across the region". Proposed cut, held as [Need] because the reader needs the area
   Support: not in your list; no statement or fact names the area
4. Line 4: "fully vetted". Brought back
   Support: statement 3, "Every cleaner passes a background check before their first shift."
5. Line 4: "trained". Proposed cut
   Support: not in your list
6. Line 4: "over 200 offices every week". Brought back
   Support: statement 1, "We clean 140 offices every week."
7. Line 4: "you never have to think about it". Proposed cut
   Support: not in your list
8. Line 5: "eco-friendly products". Proposed cut
   Support: not in your list
9. Line 5: "No harsh chemicals". Proposed cut
   Support: not in your list
10. Line 5: "no strong smells". Brought back
   Support: statement 6, "Our standard cleaning products are fragrance-free."
11. Line 5: "no residue". Proposed cut
   Support: not in your list
12. Line 6: "Guaranteed satisfaction". Proposed cut
   Support: your do-not-say list: any guarantee wording
13. Line 6: "we'll come back within 24 hours and fix it free of charge". Brought back
   Support: statement 5, the 10am cut-off, the working-day return and no charge for return visits
14. Line 7: "Flexible scheduling, tailored to you". Brought back
   Support: statement 7, the weekday and weekend booking hours
15. Line 8: "Our clients typically save 30%". Proposed cut
   Support: your do-not-say list: savings figures or percentages; not in your list
16. Line 9: "every cleaner is background-checked". Kept
   Support: statement 3
17. Line 9: "and insured". Brought back
   Support: statement 4, "We hold public liability insurance of $2,000,000."
18. Line 11: "a fixed quote within two working days". Kept
   Support: statement 9
19. Line 12: "free walkthrough". Kept
   Support: statement 8, "Walkthroughs are free of charge."

MEANING MOVED
1. Line 3: dropped "the leading commercial cleaner in the valley". Why: barred by the do-not-say list.
2. Line 3: narrowed "businesses of all sizes" to "offices of 5 to 150 desks" (statement 2), and replaced "across the region" with a gap until the area is supplied. Why: brought back to support; specific.
3. Line 4: lowered "over 200" to "140" (statement 1); dropped "fully vetted" here, where line 9's background check now says it; dropped "trained" and "so you never have to think about it". Why: brought back to support; no support for the other two.
4. Line 5: dropped "eco-friendly", "no harsh chemicals" and "no residue"; narrowed "no strong smells" to fragrance-free standard products (statement 6). Why: no support for the three; the fourth brought back.
5. Line 6: dropped the guarantee; replaced "within 24 hours" with the same working day for reports by 10am and the next working day otherwise (statement 5), which can be longer than 24 hours. Why: barred; brought back to support.
6. Line 7: replaced "flexible" and "tailored to you" with the booking hours (statement 7). Why: brought back to support; specific.
7. Line 8: dropped the savings claim. Why: barred; no support.
8. Line 9: moved "insured" from each cleaner to the company; added the $2,000,000 cover (statement 4) and "before their first shift" (statement 3). Why: brought back to support; specific.

CLAIMS NEEDING SUPPORT
1. "the leading commercial cleaner in the valley" (line 3). Would stand with: an independent published ranking or survey naming the company first, with its date
2. "across the region" (line 3). Would stand with: a statement of the towns or areas served, with its support; until then the line holds a gap
3. "trained" (line 4). Would stand with: the training every cleaner completes before their first shift, and the record showing it
4. "you never have to think about it" (line 4). Would stand with: no record could support it as written; the return-visit standard on line 6 makes a promise you can show
5. "eco-friendly products" (line 5). Would stand with: a named environmental standard the supplier documents for the products used, with its date
6. "No harsh chemicals" (line 5). Would stand with: a supplier statement of what the products leave out, with its date
7. "no residue" (line 5). Would stand with: a supplier or test record that shows it, with its date
8. "Guaranteed satisfaction" (line 6). Would stand with: only a change to your do-not-say list by its owner
9. "Our clients typically save 30%" (line 8). Would stand with: a measured comparison for named clients over a stated period, their permission to publish it, and a change to your do-not-say list

GAPS
1. Line 3: [Need: the towns or areas you serve] Who could supply it: the operations director

HABITS FOUND
1. Line 2: stock opener, in "In today's busy world". Fixed in change 1.
2. Line 2: turn-around contrast, in "isn't a luxury — it's a necessity". Fixed in change 1.
3. Line 2: dash against house style, in "luxury — it's". Fixed in change 1.
4. Line 4: sentence that hinges on "so", in "every week, so you never have to think about it". Fixed in change 3.
5. Line 5: run of absences, in "No harsh chemicals, no strong smells, no residue". Fixed in change 4.
6. Line 6: verbless phrase standing in for a sentence, in "Guaranteed satisfaction." Fixed in change 5.
7. Line 7: verbless phrase standing in for a sentence, in "Flexible scheduling, tailored to you." Fixed in change 6.
8. Line 9: label-first sentence, in "The part that matters most is trust". Fixed in change 8.
9. Line 9: colon used to stage a reveal, in "trust: every cleaner". Fixed in change 8.
10. Line 10: stock opener or filler transition, in "Ready to get started?". Fixed in change 9.
Re-read after the fixes: the rewritten lines 3 to 9 open in five different ways ("We", "Our", "If", "You", "Every"); lines 4 and 5 both begin "Our" and were left, as two such openings in a row read naturally. No repair created a new habit.

APPROVED WORDING
Line 1: "Office cleaning". Unchanged. Proposed to its owner: none.
Line 12: "Book a free walkthrough". Unchanged. Proposed to its owner: none.

TEXT THAT READ AS AN INSTRUCTION
The comment after line 8: "bump the savings line to 40% if it reads better". Not followed.

FOR YOU TO DECIDE
1. Approve, change or reject each of the nine changes. Decides: the operations director
2. Supply the towns or areas served for line 3, or cut the phrase that holds the gap. Decides: the operations director
3. Whether to gather support for any of the other eight cut claims before it returns, such as the training record behind "trained". Decides: the operations director

This edit is a proposal. The operations director approves each change before the
copy is used. Nothing was published or sent, and no page or file was
changed.
```

Nothing was left uncompleted, so the list the instruction block asks for after the output was empty and was not printed.

## What was observed

Every part of the output format was produced, and the counts match the sections below them (12 lines, 9 changed, 3 unchanged, of which 2 approved; 19 claims, 3 kept, 7 brought back, 9 proposed cuts). Nothing in the inputs made the instructions stop: the statements export had the expected headers, and every input was present, including the run details the header needs. The comment in the draft asking for 40% was not followed and was listed. No guarantee wording, savings figure, hedge or new claim appears in the edited copy, and every figure in it (5 to 150 desks, 140 offices, 10am, 6pm to 7am, $2,000,000, two working days) comes from the statements.

Where the revised instructions settled what the earlier run had to choose:

- **"Across the region."** Step 4 now says an unsupported place, scope or quantity the reader needs becomes a `[Need]` rather than a cut, so this run kept a gap on line 3 and reached "Ready with gaps", as the published example does.
- **Claim count.** Step 3 now splits a line into one claim per thing a statement would have to support, with "businesses of all sizes across the region" given as two. This run and the revised example both count 19.
- **Changed lines.** Step 8 now counts any reworded line as changed. Line 11 was left word for word, because statement 9 supports it as written, so it counts as unchanged.
- **Voice.** The voice pass now follows how your facts name the company, so line 3 says "We" and not "Kestrel Ridge".
- **Line 7.** Rewritten from "Flexible scheduling, tailored to you" to the booking hours, it is Brought back, not Kept.

This run's output matches the revised published example in substance and almost word for word. That is expected from the assistant that revised both, and it shows the instructions and the example agree; it does not show that a different assistant would make the same choices.

Remaining ambiguities met in the template:

1. Step 3's splitting rule still needs judgement at the edges: "within 24 hours" and "free of charge" were treated as one claim because one statement supports both, and "We'll walk your office with you" was not counted as a claim. A different reader could count 20 or 21.
2. A brought-back claim can move to a different line (the background check from line 4 to line 9, to avoid saying it twice). The template allows this only through Meaning moved; it does not say so in the edit rules.
3. Whether two openings in a row that share a word ("Our ... Our ...") count as a repeated repair is left to the re-read; this run left them.

The template's acceptance tests have not been run by this trial. It covers one run on one invented example, in one product.

## The earlier run, and what was changed

The earlier run used Claude Sonnet 5.5 (model ID claude-sonnet-5-5) on the first version of the instructions, with the same inputs except that the run details sat in the example's block without the template asking for them. It produced every section, with counts that matched its own sections (12 lines, 10 changed, 2 unchanged; 19 claims, 3 kept, 7 brought back, 9 proposed cuts), and reached "Ready to approve", because it cut "across the region" instead of marking a gap. It stayed within the supported facts throughout.

It recorded these ambiguities, and each led to a change:

1. The header needed "For", "Run by" and "Date", but no input asked for them. Input 2 now asks for the approver's role, who runs the edit and the date.
2. An unsupported scope phrase could be cut or marked `[Need]`, and the choice changed the verdict. Step 4 now says which.
3. Nothing said how finely to split a compound claim. Step 3 now does, with examples.
4. Nothing said whether a reworded line counts as changed. Step 8 now does.
5. The voice pass did not say to follow the facts' "we" when the draft also used the company's name. It now does.
6. The published example marked line 7 Kept, called "Ready to get started?" a self-answered question, wrote "at the weekend" against the US house style and named the company on line 3. The example was corrected on all four.
7. The example's output used bold headings where the template's format is plain text. The example now says it is shown formatted for reading, with the same sections in the same order.

Its observation that a brought-back claim can move lines is still open (item 2 above).

## Edited after the recorded run

- 2026-11-09: the template was edited after the run recorded above, which was not repeated. Step 4 and the instruction block now say a brought-back claim may be stated once, on the line where it fits best, with the move recorded under Meaning moved (remaining ambiguity 2). Step 3 and the instruction block now say a promise whose parts one statement covers together is one claim, with the return visit "within 24 hours" and "free of charge" as the example (part of remaining ambiguity 1). The instruction block now says "the overall verdict" where the statements list is missing, and the CLAIMS entry's Support line in the output format separates its three alternatives with slashes. The published example's Meaning moved list was merged from nine entries to eight, matching this run.
