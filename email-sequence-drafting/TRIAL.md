# Email sequence drafting: a trial on its invented example

- **Product:** Claude, run in Claude Code
- **Model:** Claude Sonnet 5.5 (model ID claude-sonnet-5-5)
- **Date:** 2026-11-09

This is one run of the capability template on its invented example. The inputs are the invented ones in [the example](example.md); no client data was used. The model that ran it did not write the template, and it read only the example's inputs before producing its output. It read the example's output afterwards, to compare. Nothing was sent, scheduled or loaded anywhere.

## Inputs used

The inputs block in `public/example.md`, in full and unchanged: Ines's facts for Shop M, the guide download as the starting event with its sign-up wording, a welcome sequence with the goal of a first order, the readers, what Shop M has to give (the guide, the repotting help page, a starter set with no page yet, a watering chart not yet made), the Friday newsletter, the settings (four emails over about two weeks, no word limit, merge fields such as `{{first_name}}`), Ines's note asking for a 15% code and a customer's review, and her voice sample. The template's instruction block and output format were followed as written.

## What came out

The full output of the run:

```
EMAIL SEQUENCE: Welcome, the guide "Your first 30 days with a new houseplant"
Status: Drafts for Ines. Not sent, scheduled or loaded into any tool.
Ines decides whether and when each email goes.

THE SEQUENCE
Starts when: someone downloads the free guide from the guide page.
Readers: people who have just bought or been given a houseplant and looked
for help. They already know: nothing of Shop M beyond the guide page.
What they were told they would receive: "Get the guide by email, plus a few
emails over the next two weeks to help your plant settle in. Unsubscribe
any time."
Goal: a first order. Ends when: the person places an order.
Emails: 4, over 14 days. Timing: four emails over about two weeks as
supplied; the days are proposed.
Stops when: the person places an order; any reply, which pauses the
remaining emails until Ines has answered; a request to stop or an
unsubscribe, at once and for good; another sequence starts for the same
person.
Other emails these people receive: the Friday newsletter, weekly, to
everyone on the list.
Voice: from Ines's reply to a customer: "Hi" and the first name, short
plain sentences, signed "Ines".
Defaults used: a word limit of 150 for each body, since none was set.

EMAIL 1: deliver the guide and say what follows
When: day 0 after the download, because the email carries what was asked
for (proposed)
Who receives it: everyone who downloads the guide
Subject: Your guide to a new houseplant's first 30 days
Preview: Start with week one, which is mostly about leaving things alone

Hi {{first_name}},

Here is the guide you asked for, "Your first 30 days with a new
houseplant". It is eight pages.

If you read one part first, make it week one: leave the plant where you
put it and do not repot it yet.

Three more short emails follow over the next two weeks, one each on
watering, repotting and getting supplies for your plant.

Open the guide: https://example.com/guide-30-days

Ines
Shop M
[needs: your identification and unsubscribe lines]

Ask: open the guide -> https://example.com/guide-30-days
Words in the body: 69

EMAIL 2: how to tell when to water
When: day 3 after the download, once the plant has been home a few days
(proposed)
Who receives it: everyone still in the sequence
Subject: How to tell when your plant needs water
Preview: A finger in the soil gives the answer before each watering

Hi {{first_name}},

You downloaded the guide a few days ago, so this email is about the one
check the guide asks you to make before each watering.

Push a finger into the top two inches of soil. Water only when that soil
is dry.

Ines
Shop M
[needs: your identification and unsubscribe lines]

Ask: none -> no link
Words in the body: 44

EMAIL 3: know when to repot
When: day 8 after the download, after the guide's week-one rule against
repotting has passed (proposed)
Who receives it: everyone still in the sequence
Subject: When your plant needs a bigger pot, and when it does not
Preview: Two signs to look for at the roots, and what to do if you see neither

Hi {{first_name}},

You asked for help settling in a plant, and the guide gives two signs that
it needs a bigger pot: roots circling the inside of the pot, or roots
coming out of the drainage holes.

If you see neither, leave it in its pot.

If you see one, our repotting page covers when and how:
https://example.com/help/repotting

Ines
Shop M
[needs: your identification and unsubscribe lines]

Ask: read the repotting page -> https://example.com/help/repotting
Words in the body: 58

EMAIL 4: the one next step, the starter set
When: day 14 after the download, the last email inside the two weeks the
sign-up box promised (proposed)
Who receives it: everyone still in the sequence; anyone who has ordered
has already left it
Subject: A starter set for your plant's first repotting
Preview: A pot, potting mix and plant food, $44

Hi {{first_name}},

This is the last email that came with your guide.

When your plant is ready for a bigger pot, our starter set holds a pot,
our all-purpose potting mix and a bottle of plant food, for $44. We mix
our potting soils ourselves, in small batches, in our own workshop.

Orders over $40 ship free within the US, and every order ships within two
working days. Unopened items can be returned within 30 days.

See the starter set: [needs: link to the starter set page]

Ines
Shop M
[needs: your identification and unsubscribe lines]

Ask: see the starter set -> [needs: link to the starter set page]
Words in the body: 87

WHAT EACH CLAIM RESTS ON
Email 1, "the guide you asked for ... eight pages": starting event, "a PDF,
eight pages".
Email 1, "leave the plant where you put it and do not repot it yet": material,
the guide.
Email 1, "Three more short emails follow over the next two weeks": starting
event, "a few emails over the next two weeks"; settings, four emails.
Email 1, "watering, repotting and getting supplies": plan of this sequence
(emails 2 to 4), within "to help your plant settle in".
Email 2, "the guide asks you to make before each watering", "top two inches",
"water only when that soil is dry": material, the guide.
Email 2, "downloaded the guide a few days ago": starting event.
Email 3, the two signs and "leave it in its pot": material, the guide.
Email 3, "our repotting page covers when and how": material, help page
"Repotting: when and how".
Email 4, "a pot, our all-purpose potting mix and a bottle of plant food", "$44":
material, starter set.
Email 4, "We mix our potting soils ourselves, in small batches, in our own
workshop": your facts, proof 1.
Email 4, "Orders over $40 ship free within the US": your facts, offers and
terms, free shipping.
Email 4, "every order ships within two working days": your facts, proof 2.
Email 4, "Unopened items can be returned within 30 days": your facts, offers
and terms, returns.
Email 4, "the last email that came with your guide": starting event and
settings (four emails).
Cut because nothing supports them: none.

READ BEFORE SENDING
Slots to fill: Emails 1 to 4: needs: your identification and unsubscribe
lines. Email 4: needs: link to the starter set page.
Proposed, not supplied: the days 0, 3, 8 and 14.
Material not offered: the watering chart, because it is not made yet.
Left out on purpose:
  - The 15% off code from Ines's note. Your facts say: "No discounts or
    codes. We do not run them." A code could appear only once your facts
    name it and its terms.
  - The quoted review from a customer. Your facts say: "No customer
    quotations. We have no permissions on record." It could appear only
    with the customer's permission on record, confirmed by the role that
    holds customer permissions.
Inputs not used: none.
Merge-field fallbacks to set: {{first_name}}, in all four emails.
Questions for Ines:
  1. Can the starter set be ordered today, even though its page is still
     being built? Email 4 asks for the order and cannot go until the link
     exists.
  2. Do people who download the guide also receive the Friday newsletter
     during these two weeks? If they do, two kinds of email reach the same
     inbox in the same weeks.
  3. Are the proposed days 0, 3, 8 and 14 right?

Drafts only. Nothing has been sent, scheduled, loaded into a sending tool
or added to a list.
```

## What was observed

All required parts of the output format were produced, and nothing in the inputs made the run stop. The facts page was present and the people had asked, so neither stop condition applied. The two requests in Ines's note were declined as the template directs: the 15% code (the facts say no discounts) and the customer's review (no permission on record).

Differences from the published example:

- Days. This run proposed days 0, 3, 8 and 14; the example has 0, 3, 7 and 13. The template says only that later gaps grow longer, so both fit. This run's email 1 also says "14 days" where the example says "13 days", because the days differ.
- Email 1 previews the three later emails as watering, repotting and supplies; the example says the first week, repotting and what to have ready for repotting.
- Email 2 here has no ask and no closing offer. The example's email 2 ends with an invitation to reply if something worries the reader, and records that as its ask. That is close to the "filler closing line that offers help in general terms" the template tells the assistant to remove, so this run left it out.
- Email 4 here also states the 30-day returns line; the example leaves it out. Both are supported by the facts.
- Questions for Ines: this run asked three (adding whether the starter set can be ordered before its page exists); the example asks two.
- Layout is otherwise the same, and the counted body lengths of the example's emails (62, 71, 60 and 81 words) are correct when the greeting is counted.

Facts not in the inputs: none found in this run's output. In the example's output, one statement needs a closer look. Email 1 promises an email on "what to have ready when you do" (repot), which the sign-up promise and the inputs do not name as a topic, although it fits "to help your plant settle in". Everything else in the example output traces to the inputs.

Where the template was ambiguous and this run had to choose:

- How to cite "your facts, line". The facts page is not numbered except for its three proof items, so claims were cited by quoting the heading or the item.
- Whether an email with no ask may carry a link. The rule says at most one link, "only to what the ask names", and the output format has "Ask: none". This run gave email 2 no link; email 1 treated opening the guide as its ask because the guide is what was requested.
- Whether a sequence's closing email, with a returns line and shipping terms, is one ask or several. This run kept to one ask (see the starter set) and treated the terms as supporting it.
- Whether the Friday newsletter counts as "another sequence" for the stop rule. This run treated it as a separate matter and asked the sender, since the template puts overlap under Read before sending.
- Whether to offer the starter set while its page is not built. The template says unfinished material is not offered, but also that an ask whose link is missing keeps its ask with a slot. This run kept the ask and raised the question; the instructions do not say which wins when both apply.
- Merge-field fallbacks. The sending tool's fallback format is not given, so only `{{first_name}}` is written and the fallback is listed to be set.
- The days count ("over 14 days") depends on the proposed days, which is why it differs from the example.

Shortcomings seen: the template gives no rule for how long a preview may be or for choosing between equally valid proposed days. One run on one example shows that the instructions can be followed to a complete pack; it says nothing about other inputs, other models or other products.

## Edits made after this run

The template was revised on 9 November 2026, after this run and after an independent review. These edits have not been run again. Each one either settles an ambiguity listed above in the way this run already chose, or permits something without requiring it, so the output recorded above still fits the revised instructions.

- Material that exists but whose page or link is not ready (the starter set) is offered, with a slot for the link, and that email cannot go until the slot is filled; material not yet made (the watering chart) is not offered. This run did both.
- An email whose ask is "none" carries no link. This run's email 2 has none.
- Where the facts page is not numbered, a claim cites the heading and quotes the words, as this run did.
- A preview is one short line, no longer than a short sentence. Every preview above fits.
- The closing-line rule now says that an invitation to reply about something specific, which the facts support, is allowed and is then the email's one ask. This settles the difference noted above about the example's email 2; this run's choice to leave such a line out still fits, since nothing requires one.
- The pasted instructions now carry two defaults the procedure already held: a missing kind of sequence is taken from the starting event, and a missing goal is proposed and marked "proposed". The example supplies both, so neither applied.
- The reviewer checklist's subject and preview line was reworded; it is not part of the pasted instructions.
- 9 November 2026, after a second review: step 5 of the pasted instructions now says the sender sets a fallback for each merge field, as the procedure already said. This run listed its one merge field for a fallback, so its output still fits.

The example was also edited on 9 November 2026, after this run. Proof 3 in its inputs now reads "answers every email to the shop herself" instead of "answers every customer email herself", because the readers are not yet customers; this run's output does not use proof 3. The example's list of what each claim rests on gained lines for email 1's three topics (the statement noted above), the opening of email 2 and the opening of email 4. The example's emails are unchanged.

One correction was made to this record: the note on the example's output said "two statements need a closer look" and named only one, so the count now reads one. No other recorded output or observation was changed.
