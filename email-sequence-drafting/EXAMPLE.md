# Email sequence drafting: an invented example

*Illustrative example with invented data.* The shop, the owner, the customer named in her note, the guide, the prices and every fact below are invented, and the links use the reserved example.com address. Shop M is an invented online shop selling indoor plant supplies; Ines, its owner, is invented too. First come the inputs Ines supplied, in full, then the sequence the workflow template returned.

## The inputs

```
YOUR FACTS (supplied by Ines)

Who we are: Shop M, an online shop selling indoor plant care supplies:
  potting mixes, plant food, pots and tools.
For whom: people who keep houseplants at home, most in their first year
  or two of doing it.
Proof we can support:
  1. We mix our potting soils ourselves, in small batches, in our own
     workshop.
  2. Every order ships within two working days.
  3. Ines, the owner, answers every email to the shop herself.
Offers and terms true today:
  - Free shipping within the US on orders over $40. No end date.
  - Returns: unopened items within 30 days.
What we never say:
  - No discounts or codes. We do not run them.
  - No customer quotations. We have no permissions on record.
  - Nothing about a plant's health that sounds like a promise.
Signs as: "Ines" on its own line, then "Shop M".

THE STARTING EVENT
People download our free guide, "Your first 30 days with a new
houseplant" (a PDF, eight pages), from the guide page. The sign-up box
says: "Get the guide by email, plus a few emails over the next two weeks
to help your plant settle in. Unsubscribe any time."

KIND AND GOAL
Welcome. Goal: a first order. Done when: the person places an order.

READERS
People who have just bought or been given a houseplant and looked for
help. They know nothing of Shop M beyond the guide page.

WHAT WE HAVE TO GIVE
  - The guide. Link: https://example.com/guide-30-days (exists).
    What it says, in short: in week one, leave the plant where you put
    it and do not repot it yet. Before each watering, push a finger into
    the top two inches of soil and water only when that soil is dry.
    Repot when roots circle the inside of the pot or come out of the
    drainage holes; if you see neither, leave it in its pot.
  - Help page, "Repotting: when and how". Link:
    https://example.com/help/repotting (exists).
  - Starter set: a pot, our all-purpose potting mix and a bottle of plant
    food, $44. Its page is still being built; no link yet.
  - A watering chart. Planned, not made yet.

OTHER EMAILS THESE PEOPLE RECEIVE
The Friday newsletter, weekly, to everyone on the list.

SETTINGS
Four emails over about two weeks. No word limit set. Our sending tool
writes merge fields like {{first_name}}.

A NOTE FROM INES
Could email 4 carry a 15% off code to push the first order? And maybe
quote the review from Sam, who said our mix saved her fiddle-leaf fig.

VOICE SAMPLE (a reply Ines sent to a customer)
Hi Jo,
Thanks for the photo. Yellow lower leaves usually mean too much water,
not too little. Let the top two inches dry out before the next drink and
send me another photo in a week.
Ines
```

## The output

```
EMAIL SEQUENCE: Welcome, the guide "Your first 30 days with a new houseplant"
Status: Drafts for Ines. Not sent, scheduled or loaded into any tool.
Ines decides whether and when each email goes.

THE SEQUENCE
Starts when: someone downloads the guide from the guide page.
Readers: people who have just bought or been given a houseplant and
looked for help. They already know: nothing of Shop M beyond the guide
page.
What they were told they would receive: "Get the guide by email, plus a
few emails over the next two weeks to help your plant settle in.
Unsubscribe any time."
Goal: a first order. Ends when: the person places an order.
Emails: 4, over 13 days. Timing: four emails over about two weeks as
supplied; the days are proposed.
Stops when: a first order; any reply, which pauses the remaining emails
until Ines has answered; a request to stop or an unsubscribe, at once
and for good; another sequence starts for the same person.
Other emails these people receive: the Friday newsletter, weekly, to
everyone on the list.
Voice: from Ines's reply to a customer: "Hi" and the first name, short
plain sentences, signed "Ines".
Defaults used: a word limit of 150 for each body, since none was set.

EMAIL 1: deliver the guide and say what follows
When: day 0 after the download, as soon as the request arrives, because
it carries what was asked for (proposed)
Who receives it: everyone who downloads the guide
Subject: Your guide to a new houseplant's first 30 days
Preview: Eight pages, and what the next three emails will cover

Hi {{first_name}},

Here is the guide you asked for, "Your first 30 days with a new
houseplant". It runs to eight pages.

Over the next two weeks I'll send three more short emails, each on one
part of helping your plant settle in: the first week, when to repot, and
what to have ready when you do.

Open the guide here: https://example.com/guide-30-days

Ines
Shop M
[needs: your identification and unsubscribe lines]

Ask: open the guide -> https://example.com/guide-30-days
Words in the body: 62

EMAIL 2: get the first week right
When: day 3 after the download, while the plant is still in its first
week (proposed)
Who receives it: everyone still in the sequence
Subject: Your plant's first week: leave it where it is
Preview: And a finger test to use before every watering

Hi {{first_name}},

Your plant is in its first week with you, so this email is about that
week. The guide says to leave your plant where you put it and not to
repot it yet.

Before each watering, push a finger into the top two inches of soil.
Water only when that soil is dry.

If something about your plant worries you, reply to this email. I
answer every one myself.

Ines
Shop M
[needs: your identification and unsubscribe lines]

Ask: reply if something worries them -> no link
Words in the body: 71

EMAIL 3: know when to repot
When: day 7 after the download, as the first week ends and the guide's
no-repotting rule lifts (proposed)
Who receives it: everyone still in the sequence
Subject: When your plant needs a bigger pot
Preview: Two signs to look for, and what to do if you see neither

Hi {{first_name}},

Your plant has had its first week to settle. The guide gives two signs
that it needs a bigger pot: roots circling the inside of the pot, or
roots coming out of the drainage holes.

If you see neither, leave it in its pot.

If you do see one, our page on repotting covers when and how:
https://example.com/help/repotting

Ines
Shop M
[needs: your identification and unsubscribe lines]

Ask: read the repotting page -> https://example.com/help/repotting
Words in the body: 60

EMAIL 4: the one next step, the starter set
When: day 13 after the download, the last email inside the two weeks the
sign-up box promised (proposed)
Who receives it: everyone still in the sequence; anyone who has placed
an order has already left it
Subject: A starter set for your plant's first repotting
Preview: A pot, our own potting mix and plant food, sent within two working days

Hi {{first_name}},

This is the last of the emails that came with your guide.

When your plant is ready for a bigger pot, our starter set holds a pot,
our all-purpose potting mix and a bottle of plant food. We mix our soils
ourselves, in small batches, in our own workshop.

The set is $44, so it ships free within the US, and every order leaves
within two working days.

See the starter set: [needs: link to the starter set page]

Ines
Shop M
[needs: your identification and unsubscribe lines]

Ask: see the starter set -> [needs: link to the starter set page]
Words in the body: 81

WHAT EACH CLAIM RESTS ON
Email 1, "the guide you asked for ... It runs to eight pages": starting
event, "a PDF, eight pages".
Email 1, "three more short emails ... over the next two weeks": starting
event, "a few emails over the next two weeks"; settings, four emails.
Email 1, "the first week, when to repot, and what to have ready when you
do": the plan of this sequence (emails 2 to 4), within "to help your
plant settle in".
Email 2, "Your plant is in its first week with you": readers input, "have
just bought or been given a houseplant"; the email goes on day 3.
Email 2, "leave your plant where you put it and not to repot it yet":
material, the guide, "in week one, leave the plant where you put it and
do not repot it yet".
Email 2, "push a finger into the top two inches of soil. Water only when
that soil is dry": material, the guide.
Email 2, "I answer every one myself": your facts, proof 3.
Email 3, "roots circling the inside of the pot, or roots coming out of
the drainage holes" and "If you see neither, leave it in its pot":
material, the guide.
Email 3, "our page on repotting covers when and how": material, help
page "Repotting: when and how".
Email 4, "a pot, our all-purpose potting mix and a bottle of plant food",
"$44": material, starter set.
Email 4, "We mix our soils ourselves, in small batches, in our own
workshop": your facts, proof 1.
Email 4, "it ships free within the US": your facts, free shipping within
the US on orders over $40; the set is $44, which is over $40.
Email 4, "every order leaves within two working days" (and the preview's
"sent within two working days"): your facts, proof 2.
Email 4, preview, "our own potting mix": your facts, proof 1.
Email 4, "This is the last of the emails that came with your guide":
starting event, "a few emails over the next two weeks"; settings, four
emails.
Cut because nothing supports them: none.

READ BEFORE SENDING
Slots to fill: Emails 1 to 4: needs: your identification and unsubscribe
lines. Email 4: needs: link to the starter set page.
Proposed, not supplied: the days 0, 3, 7 and 13.
Material not offered: the watering chart, because it is not made yet.
Left out on purpose:
  - The 15% off code from Ines's note. Your facts say: "No discounts or
    codes. We do not run them." A code could appear only once your facts
    name it and its terms.
  - The review from Sam. Your facts say: "No customer quotations. We
    have no permissions on record." It could appear only with Sam's
    permission on record, confirmed by Ines.
Inputs not used: none.
Merge-field fallbacks to set: {{first_name}}, in all four emails.
Questions for Ines:
  1. Do new guide sign-ups also get the Friday newsletter during these
     13 days? If they do, two kinds of email reach the same inbox in the
     same weeks.
  2. Are the proposed days 0, 3, 7 and 13 right?

Drafts only. Nothing has been sent, scheduled, loaded into a sending tool
or added to a list.
```
