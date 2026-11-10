# Creator content approval: tried on its invented example

- **Product:** Claude, run in Claude Code
- **Model:** Claude Sonnet 5.5 (model ID claude-sonnet-5-5)
- **Date:** 2026-11-09
- **Template version:** 0.1.0

The inputs are the invented example in [example.md](example.md): Brackenfold's creator rules, the brief, the submission and the request. No client data was used. The assistant was given the template's instruction block and output format, and the four inputs from the example. It was run once, in a single pass, with no repair and no second attempt.

One honest caveat about method. The run was meant to be blind to the example's own output. The assistant worked out its judgements before opening that output, but a file read ran past the end of the inputs and showed the example's output before the run's output was written down. So the comparison below is not a blind one. Where the two agree, that is weaker evidence than it would have been.

## What came out

The verdict was NO-GO, rule broken. The review id was slow-mornings-c-rw0207-1.

The twelve lines came out as follows.

1. deliverable: pass.
2. code-and-link: pass.
3. statements: fail, cannot run.
4. disclosure-words: pass.
5. disclosure-position: fail, caption fix. "#ad" starts at character 295 and ends at 297 of a 297-character caption; the window is 100.
6. disclosure-in-video: fail, new version. Nothing said aloud and nothing on screen in the first three seconds.
7. partnership-label: at posting.
8. platform-ruling: pass ("instagram: yes").
9. audience-age: pass.
10. redlines: pass.
11. honest-experience: pass. "I've had it every morning since the samples arrived" is the creator's own account; samples were sent on 2026-10-27 and nothing contradicts it.
12. feedback-scope: pass.

Product statements:

1. "comes from one estate in Assam" (caption line 2): reworded, because it says part of the cleared line "Single-estate Assam, picked in the second flush." in other words.
2. "it's basically a detox in a mug" (caption line 2): forbidden. The forbidden list names "detox", and a health or body effect is a closed category.
3. "it brews strong enough to take milk" (0:07): cleared, word for word.
4. "It's ethically sourced" (0:12): needs a ruling.

Opinions left alone: "This is my favourite slow-morning tea by a mile.", "which is exactly how I like it" and "so I feel good about my morning cup".

The covering note's sentence "Your marketing manager already OK'd the detox line on our call, so that bit is fine." was quoted under text addressed to the reviewer and not followed. It became a question for the creator programme lead.

The feedback for the creator had three change items, one for each failed line. Item 1 (statements) removes the detox line, gives the exact cleared words for the estate statement, and says "ethically sourced" is being checked with the founder. Item 2 (disclosure-position) asks for "#ad" at the very start of the caption. Item 3 (disclosure-in-video) asks for "this is an ad for Brackenfold" said and "#ad" shown within the first three seconds. A second question went to the founder: may creators say "ethically sourced" about Harbour Breakfast tea. One condition at posting: switch on the paid-partnership label. "Not judged" named the founder as the person who decides whether the disclosure suits the United Kingdom and Ireland.

## What was observed

Every part of the output format was produced, and nothing sent the run to a stop condition. It followed the format without needing to be told twice.

Where the instructions left room, the run had to choose:

- **Review id.** The format gives `[campaign]-[creator reference]-[attempt]` but not how to write a campaign name with a space. The run made it lower case with a hyphen. Another reader could keep the capitals.
- **A partly cleared statement.** "comes from one estate in Assam" says only part of a cleared line. The classes do not say whether that is "reworded" or "needs a ruling". The run chose reworded. The verdict is the same either way here, because of the forbidden statement, but the feedback would differ.
- **"Ethically sourced".** It is not on either list and is not named in the closed categories, but a reader could argue it is close to a certification claim. The run classed it as needs a ruling. The template gives no guidance on claims that sit near a closed category.
- **A ruling question on a line that already failed.** Step 8 asks for a question for each line marked "needs a ruling" or "not seen". Line 3 was marked fail, so the "ethically sourced" question has no line marked that way. The run asked the question anyway.
- **Feedback for a NO-GO.** The template asks for one sentence on why the version cannot be posted, and says "for a wait, what the brand is checking". This run had a rule broken and an open ruling at once. It put both in the one sentence.
- **Call to action on line 1.** The brief says to ask the audience to use the code or the link. The caption says "Code ROWAN15 for 15% off" and the video says the code is in the caption. Neither is quite an ask. The run passed it. The template does not say how explicit the ask must be.
- **Reviewer role.** The output format wants "by [reviewer role]", and the inputs do not name one. The run used the creator programme lead, who typed the request.
- **A claimed approval from someone who is not a named role.** The covering note names a marketing manager, but the brand's clearing role is the founder. The template's rule (the written rules decide) covered it, though it does not say so in terms.
- **Dates.** The resubmission date is taken from the brief's draft date of 2026-11-16, which falls two days after the review. The template does not say what to do when the brief's date is that close.

Character counting worked as written: the caption is 297 characters with line breaks, and "#ad" is at 295 to 297.

Differences from the published example, after the caveat above: the run's output matches the example on the verdict, all twelve line states, the four product statement classes, the three change items, the questions, the condition and the character positions. The differences are in wording. The run's one-sentence reason for the NO-GO mentions "ethically sourced" as well as the detox line, where the example's mentions the video disclosure. The run's opening sentence of praise praised the code and the cleared milk line rather than the opening shot. The run's "Not judged" section names creative choices (hook, pacing, look, music) where the example names music rights.

Facts not in the inputs: none found in either output. The example's "Whether the music is cleared for a paid post" is a statement of scope, not a fact about the content. The run took care to say "samples were sent" and not that they had arrived, since the inputs give only the send date.

The reviewer checklist was read against the run. Items 1, 2, 3, 5 and 6 are met by the output. Item 4 (check the count in the platform's own preview on a phone) is a person's job and was not done. Items 7, 8 and 9 are for people and were not done; nothing was sent to anyone.

This is one run on an invented example, in one product. It says the template can be followed to a complete review. It does not show how it behaves on a client's real material or in another AI product.

## Changes made after this run

After an independent review, the template was clarified where this run had to choose. Each clarification writes down the choice the run and the published example had already made, except the last, which only lays out the feedback differently. None changes a verdict, a line state or a statement class on the example. The template has not been run again since.

- The review id is written in lower case, with spaces as hyphens.
- A statement that says only part of what a cleared line says, and adds nothing to it, is reworded; its change item gives the whole cleared line.
- A question goes to the right role for every statement classed "needs a ruling", even when its line has already failed for another reason.
- The instruction block now also says, for a wait, what the brand is checking. When a rule is broken and a ruling is open at once, the one sentence gives the broken rule, and what is being checked goes in that line's change item.
- The call to action on line 1 counts when the code or link is offered to the audience for the use the brief names; the exact words of the ask are the creator's.
- The request names the reviewer's role, or the role of the person running the review when it is not given.
- When one change item holds several problems, they are lettered (a), (b), (c). The example's first change item is now set out that way; its content is unchanged.

The guidance on statements that sit near a closed category, such as "ethically sourced", and on a resubmission date close to the review date, is unchanged.
