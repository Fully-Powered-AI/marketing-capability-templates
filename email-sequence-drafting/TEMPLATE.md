# Email sequence drafting

Capability template, version 0.1.0.

## Purpose

Draft one short email sequence for people who asked to hear from you: a welcome after a sign-up or a requested download, a nurture sequence that leads people who asked for something toward one next step, or the onboarding emails of a new customer's first weeks. Each email has a single job, gives the reader something before it asks for anything, and makes one ask at most. Every statement about the company rests on the sender's own short page of facts, and every sequence states what starts it, what it is for, what ends it and how a reader stops it. The pack also lists what each claim rests on and the slots only the sender can fill. The sender reads, edits, loads and sends; the assistant sends nothing, schedules nothing, touches no list and invents no result, customer, offer or deadline.

## When to use it and when not to

Use it when people have signed up, downloaded, registered or bought and nothing follows yet; when an existing sequence no longer matches what you sell or what people were told they would receive; or when a new guide, offer or onboarding step needs the emails that go with it.

Do not use it:

- for people who never asked to hear from you. Writing to strangers is cold outreach, a separate piece of work with stricter rules, covered by the cold outreach sequence drafting capability;
- for a list that was bought, rented, scraped or borrowed. Holding an address is not a request;
- for a single newsletter issue, an announcement to the whole list or a promotions calendar;
- for receipts, password resets, payment failures and the other system messages your software sends;
- to set up sending: the sending tool, the automation, the list, delivery or tracking. A person does that;
- to plan tests or predict open, click or conversion rates. This capability states no rates and no benchmarks.

## Roles

- **Runs it:** the marketer or owner responsible for the emails. They supply the inputs, read every line and fill the slots.
- **Loads and sends:** `[your sending role]`, in the sending tool the company already uses, once the drafts are approved.
- **Confirms what may be claimed:** `[the role that owns your facts page]`, such as the owner or the marketing lead.
- **Confirms a customer may be quoted or named:** `[the role that holds customer permissions]`.
- **The AI assistant:** drafts and checks. It never sends, schedules, loads anything into a sending tool, connects to a mailbox, adds anyone to a list or removes anyone from one, or looks anyone up.

## Inputs

1. **Your facts.** A short page the sender supplies: what you sell and to whom; the proof you can support, with the permission on record for any customer quoted or named; the offers and terms true today (prices, trial length, shipping, returns) and until when; what you never say; who signs the emails and how. If it is missing, stop and ask for it. Nothing about the company is written without it.
2. **The starting event.** What the people did (signed up for, downloaded, registered for, bought) and the words they saw when they did it: what they were told they would receive, and how often. If those words are missing, ask once; if they are still missing, write "promise not supplied" and keep every email to the subject of what was asked for. If the event shows that the people did not ask (an imported, bought or borrowed list, or addresses gathered with no request), stop.
3. **The kind of sequence and its goal.** Welcome, nurture or onboarding; the one next step the sequence leads toward; and the action that means it can stop because it worked, such as a first order, a booked call or a finished setup step. If the kind is missing, take it from the starting event and say so. If the goal is missing, propose one and mark it "proposed".
4. **The readers.** Who they are, by role or kind, and what they already know of the company. No names or addresses are needed: the drafts carry merge-field slots in `[your sending tool's merge-field format]`. If a list of people is supplied anyway, it is not used and nothing from it is repeated.
5. **What you have to give.** The guide, checklist, setup steps, help pages or booking page the emails may offer, each with its link, whether it exists today, and a few lines on what it says if an email is to pass on its advice. Something not yet made is not offered. Something that exists but whose page or link is not ready is offered, with a slot for the link, and that email cannot go until the slot is filled.
6. **Other emails these people receive.** A newsletter, product news or another sequence, and when it goes. If missing, write "not supplied" and put the question under Read before sending.
7. **Settings.** The number of emails and the days between them; otherwise up to `[your maximum emails]` (five if unset) with the timing proposed. `[your word limit]` for each email's body (150 words if unset). Optionally, one or two emails the sender really wrote, for the voice.

## The procedure

1. **Check the inputs.** Confirm that your facts are present and that the starting event shows the people asked. Stop if either fails. List anything else that is missing and the default used in its place.
2. **Write the frame before any email.** What starts the sequence; who reads it and what they already know; what they were told they would receive; the goal and the action that ends it; and what stops it. The stops always include: the goal action; a request to stop or an unsubscribe, honoured at once and for good; any reply, which pauses the remaining emails for that person until the sender has answered and decided whether they continue; and the start of another sequence for the same person, so that two sequences never run into one inbox at the same time. Add any stop the sender names.
3. **Plan the emails.** Start from the shape for the kind of sequence, below. Remove any email that has no job of its own for these readers, and add none that lacks one. For each email write its job, what it gives, its one ask or "none", when it goes relative to the starting event with the reason, and any condition on who receives it. Stay inside what the people were told they would receive: a guide download does not become a weekly promotion. Every sequence has a last email; none runs on.
   - **Welcome:** the first email goes when the request arrives, carries what was asked for and tells the reader how many more emails will follow and what they cover. Each email after it gives one useful thing tied to what was asked for. The last makes the one next step, plainly and once.
   - **Nurture:** the first email carries the resource. Each one after it takes one part of the reader's problem further. The ask moves from using what was given toward the next step only in the last one or two emails.
   - **Onboarding:** the first email confirms what was bought and names the first step. Each one after it helps with one step or first use, in the order the steps happen. One email asks how it is going and names a person to reply to. The sequence ends when the goal action happens or at its last email.
4. **Set the timing.** Use the timing supplied. Otherwise propose it: the first email on the day of the starting event, later gaps growing longer, and every proposed day marked "proposed". Never give an open rate, a benchmark or a test result.
5. **Draft each email.** Plain text, the body at most `[your word limit]` words.
   - **Subject:** plain words naming what is inside. Someone who reads nothing but the subject should still know what the email holds. No reply or forward marker, no bait, no emoji, and no urgency your facts do not hold.
   - **Preview:** one short line, no longer than a short sentence, that carries the thought on from the subject in new words, never a restatement of it.
   - **Body:** begin by saying why this email has come (what they asked for, or where they are in setup); give the useful thing; make the ask; stop. Short paragraphs that read well on a phone. At most one link, and only to what the ask names; an email whose ask is "none" carries no link.
   - Personal details appear only as merge-field slots, and each merge field needs a fallback the sender sets for when the value is blank; list each one under Read before sending.
   - Count the words in each body, from the greeting to the line before the sign-off, and keep within the limit.
   - Sign as your facts say. End every email with the slot `[needs: your identification and unsubscribe lines]` unless the sender supplied those lines.
6. **Match the voice.** From the sample, take the greeting, the sign-off, the sentence length and how direct the sender is. Carry nothing about the sample's recipient into the drafts. With no sample, write plainly and say so.
7. **Remove the wording that marks an email as mass-produced:** a stock opening about the reader's wellbeing or about checking in; a filler closing line that offers help in general terms (an invitation to reply about something specific, which your facts support, is allowed, and is then that email's one ask); a sentence that denies one thing only to announce another; a run of three things that are absent; a question the email answers in its next breath; a heading-like word followed by a colon and a reveal; words such as unlock, transform, seamless and game-changing.
8. **Ground every claim.** Each statement about the company, its products, prices or terms points to a line of your facts or to the material in input 5. Each statement about the reader points to the starting event or the readers input. Where your facts are not numbered, cite the heading and quote the words. A statement that points nowhere is cut, never softened. Results, figures, customer quotations and names, discounts, deadlines, low-stock warnings and guarantees appear only when your facts hold them.
9. **Mark the slots.** Every missing fact or link is a slot, `[needs: <what is missing>]`. Never guess one.
10. **Return the pack** in the output format, with Read before sending. The sender edits, loads and sends, or discards.

## Exceptions and stop conditions

- **No facts page:** stop and ask for it.
- **The people did not ask** (a bought, rented, scraped or borrowed list, or addresses gathered with no request): stop and draft nothing. Name the cold outreach sequence drafting capability as the separate piece of work for strangers.
- **Asked to add a result, a figure, a customer quotation or name, a discount, a deadline or a low-stock warning your facts do not hold:** decline, name the line of your facts that would be needed, and list the request under "Left out on purpose".
- **A customer quoted or named without permission on record:** leave it out and put the question to `[the role that holds customer permissions]`.
- **Asked for a "last chance" email, a guilt line, or an email asking whether to stop writing:** decline. The sequence simply ends at its last email.
- **Asked for more emails than the people were told to expect, or for a sequence with no end:** draft only what fits the promise and `[your maximum emails]`, and list the rest under "Questions for the sender".
- **Material not yet made:** not offered; it goes under "Material not offered".
- **Material that exists but whose page or link is not ready:** offered. An email whose ask needs that link keeps its ask with a slot for the link, and cannot go until the slot is filled.
- **What the law requires where the readers are** (consent, identification and unsubscribe lines): leave the slots and say the sender must settle it. The assistant gives no view on the law.
- **A list of people, their addresses or other personal data supplied:** do not use it or repeat it; the drafts use merge-field slots. Note it under Read before sending.
- **A password, login code or payment details in the inputs:** do not repeat them; tell the person to remove them from the source. The assistant never asks for a password or a login code.
- **Asked to send, schedule, load the emails into a tool, change a list or connect to a mailbox:** decline. `[your sending role]` does that after the drafts are approved.

## Output format

```
EMAIL SEQUENCE: [kind], [what the people asked for]
Status: Drafts for [sender]. Not sent, scheduled or loaded into any tool.
[Sender] decides whether and when each email goes.

THE SEQUENCE
Starts when: [the starting event]
Readers: [who they are]. They already know: [what they know of the company].
What they were told they would receive: [the words, as supplied / promise not supplied]
Goal: [the one next step] [(proposed)]. Ends when: [the goal action]
Emails: [n], over [n] days. Timing: [as supplied / proposed]
Stops when: [the goal action]; any reply, which pauses the remaining emails
until [sender] has answered; a request to stop or an unsubscribe, at once
and for good; another sequence starts for the same person[; others named].
Other emails these people receive: [as supplied / not supplied]
Voice: [what was taken from the sample / plain; no sample supplied]
Defaults used: [each default and why / none]

EMAIL [n]: [its one job]
When: day [n] after the starting event, [the reason] [(proposed)]
Who receives it: [everyone still in the sequence / the condition]
Subject: [line]
Preview: [line]

[Body: greeting, short paragraphs, the ask, the sign-off]
[needs: your identification and unsubscribe lines] / [the lines supplied]

Ask: [the one action] -> [link / needs: link / no link] / none
Words in the body: [n], from the greeting to the line before the sign-off

(one block per email)

WHAT EACH CLAIM RESTS ON
Email [n], "[the words of the claim]": [your facts, "line" / starting event /
readers input / material: name]
Cut because nothing supports them: [lines / none]

READ BEFORE SENDING
Slots to fill: [Email n: needs: what] / none
Proposed, not supplied: [timing, goal or anything else proposed] / none
Material not offered: [item, and why] / none
Left out on purpose: [each request declined, the reason, and the line of
your facts that would allow it] / none
Inputs not used: [a list of people or other data supplied and set aside] / none
Merge-field fallbacks to set: [each merge field, and the emails it is in] / none
Questions for [sender]: [n]. [question] / none

Drafts only. Nothing has been sent, scheduled, loaded into a sending tool
or added to a list.
```

## Reviewer checklist

1. Every statement about the company, its products, prices and terms appears in your facts or in the material supplied. (The role that owns your facts page)
2. No result, figure, customer quotation or name, discount, deadline or guarantee appears that your facts do not hold. (The role that owns your facts page)
3. The sequence stays within what the people were told they would receive when they signed up, and it has a last email. (Runs it)
4. Each email has one job, one ask at most and one link at most, and its body is within the word limit. (Runs it)
5. The stops include a request to stop, the pause on any reply and the start of another sequence for the same person. (Runs it)
6. The subject alone says what is inside; the preview adds to it and does not repeat it. (Runs it)
7. Every slot is filled, every merge field has a fallback, and the identification and unsubscribe lines are the company's own, before anything is loaded. (`[your sending role]`)
8. Every timing marked proposed has been accepted or changed. (Runs it)

## Acceptance tests

Proposed tests. None has been run.

1. **Complete welcome inputs.** Facts, a guide download with its sign-up wording, four emails over two weeks, two help pages. Expected: the frame, four emails each with one job, what each claim rests on, and the slots.
2. **No facts page.** Expected: stops and asks for it; drafts nothing.
3. **A bought list.** The starting event is "a list of 2,000 addresses we purchased". Expected: stops, drafts nothing, names cold outreach as separate work.
4. **A discount the facts do not hold.** The sender's note asks for a 15% code; the facts say no discounts. Expected: no code in any email; listed under "Left out on purpose" with the facts line.
5. **A customer quotation with no permission.** Expected: left out; the question goes to the role that holds customer permissions.
6. **A missing link.** The final email's ask needs a page whose link is not supplied. Expected: the ask stays, with `[needs: link]`, and the slot is listed.
7. **A "last chance" email requested.** Expected: declined; the sequence ends at its last email.
8. **Onboarding with a goal action.** Expected: the goal action among the stops; emails in the order the setup steps happen; one email names a person to reply to.
9. **Overlap with a newsletter.** The people also receive a weekly newsletter. Expected: a question about the overlap under Read before sending.
10. **Asked to load the emails into the sending tool.** Expected: declines and names the sending role.
11. **A list of people with addresses supplied.** Expected: not used and not repeated; noted under "Inputs not used".
12. **More emails than promised.** The sign-up promised three emails; the sender asks for six. Expected: three drafted; the rest listed as a question for the sender.

## Instructions for the AI assistant

Paste this block as custom instructions, followed by the output format above.

```
You draft one short email sequence for people who asked to hear from a
company: a welcome, a nurture sequence or a new customer's onboarding.
You draft; people decide. You never send, schedule or load an email into
any tool, never connect to a mailbox, never add anyone to a list or
remove anyone from one, never look anyone up, and never change any
record. You never ask for a password or a login code.

The user will supply: your facts (what the company sells and to whom,
proof it can support with customer permissions, offers and terms true
today, what it never says, who signs); the starting event (what the
people did and the words they saw about what they would receive); the
kind of sequence, its goal and the action that ends it; who the readers
are and what they know; what the company has to give, with links and
whether each exists; other emails these people receive; and settings
(number of emails and timing, word limit, default 150; maximum emails,
default five; an optional voice sample).

1. If your facts are missing, stop and ask for them. If the starting
   event shows the people did not ask (a bought, rented, scraped or
   borrowed list, or addresses gathered with no request), stop, draft
   nothing, and say that writing to strangers is cold outreach, a
   separate piece of work. If the words the people saw are missing, ask
   once; if still missing, write "promise not supplied" and keep every
   email to the subject of what was asked for. If the kind is missing,
   take it from the starting event and say so. If the goal is missing,
   propose one and mark it "proposed". List every other missing input
   and the default used.
2. Write the frame first: what starts the sequence; the readers and what
   they know; what they were told they would receive; the goal and the
   action that ends it; and the stops. The stops always include the goal
   action; a request to stop or an unsubscribe, honoured at once and for
   good; any reply, which pauses the remaining emails until the sender
   has answered; and another sequence starting for the same person.
3. Plan the emails from the shape for the kind. Welcome: the first email
   carries what was asked for and says how many emails follow and what
   they cover; each later email gives one useful thing tied to the
   request; the last makes the one next step once. Nurture: the first
   carries the resource; each later email takes one part of the reader's
   problem further; the next step is asked for only in the last one or
   two. Onboarding: the first confirms what was bought and the first
   step; each later email helps with one step, in order; one asks how it
   is going and names a person to reply to. Remove any email with no job
   of its own. Stay inside what the people were told they would receive
   and within the maximum; list anything beyond it as a question. Every
   sequence has a last email.
4. Use the timing supplied. Otherwise propose it: the first email on the
   day of the starting event, later gaps longer, each marked "proposed".
   Never give an open rate, a benchmark or a test result.
5. Draft each email in plain text, the body within the word limit.
   Subject: plain words naming what is inside, clear to someone who reads
   nothing else; no reply or forward marker, no bait, no emoji, no
   urgency the facts do not hold. Preview: one short line, no longer
   than a short sentence, carrying the thought on from the subject in
   new words; never repeats it. Body: begin by saying why this email
   has come, give the useful thing, make one ask or none, stop. Short
   paragraphs. At most one link, only to what the ask names; an email
   whose ask is "none" carries no link. Personal details only as
   merge-field slots; the sender sets a fallback for each, so list each
   one under "Merge-field fallbacks to set". Sign as the facts say. End each email with "[needs: your
   identification and unsubscribe lines]" unless those lines were
   supplied. Count the words in each body, from the greeting to the line
   before the sign-off.
6. Match the voice sample's greeting, sign-off, sentence length and
   directness, and carry nothing about its recipient. With no sample,
   write plainly and say so.
7. Remove: stock openings about the reader's wellbeing or checking in;
   filler closing lines offering help in general terms (an invitation
   to reply about something specific, which the facts support, is
   allowed and is then the email's one ask); sentences
   that deny one thing to announce another; runs of three absent things;
   questions the email answers itself; a word, a colon and a reveal;
   words such as unlock, transform, seamless and game-changing.
8. Ground every claim. Each statement about the company, its products,
   prices or terms must point to a line of the facts or to supplied
   material; each statement about the reader to the starting event or
   the readers input. Where the facts are not numbered, cite the heading
   and quote the words. Cut, never soften, what points nowhere. Never
   write a result, figure, customer quotation or name, discount,
   deadline, low-stock warning or guarantee the facts do not hold;
   decline such a request, say which line of the facts would be needed,
   and list it under "Left out on purpose". A customer named without
   permission on record goes to the role that holds permissions. Never
   write a "last chance" email, a guilt line or an email asking whether
   to stop writing.
9. Do not offer material not yet made; list it under "Material not
   offered". Material that exists but whose page or link is not ready is
   offered, with a slot for the link; that email cannot go until the
   slot is filled. Every missing fact or link is a slot, "[needs: what
   is missing]"; never guess one.
10. If a list of people or other personal data is supplied, do not use
    or repeat it; note it under "Inputs not used". If the inputs hold a
    password, login code or payment details, do not repeat them and tell
    the user to remove them. On what the law requires where the readers
    are, leave the slots and say the sender must settle it; give no view
    on the law.
11. Use the output format exactly, every section present; write "none"
    where a section is empty. End with the line that says nothing has
    been sent, scheduled, loaded or added to a list.

If asked to send, schedule, load the emails, change a list or connect to
a mailbox, decline and say that the sending role does it after the
drafts are approved.
```

## What to customize

- `[your maximum emails]` and `[your word limit]`, and the timing you prefer for each kind of sequence.
- The shapes for welcome, nurture and onboarding, if your customers' first weeks run in a different order.
- `[your sending role]`, `[the role that owns your facts page]` and `[the role that holds customer permissions]`.
- `[your sending tool's merge-field format]`, and the fallback for each merge field.
- Your identification and unsubscribe lines, once the sender has settled what the readers' countries require. Supply them and the slot disappears.
- Your facts page: keep the offers and terms current, with their end dates, so no email states one that has lapsed.
- Which files the assistant may read in ChatGPT, Claude, Copilot or Gemini, and where the approved drafts are kept.

## Version notes

- 0.1.0, 9 November 2026. Written by Fully Powered AI from its own email drafting guide. Two openly licensed packages contributed ideas; each is credited in the sources with what it contributed, and no text of theirs is reused. Editorially reviewed. Tried on its invented example on 9 November 2026 in one run, recorded with it. Small edits made to the pasted instructions and the reviewer checklist after the recorded run have not been run again; the trial record lists them. Not yet tested in a client environment, and not yet tested as a packaged version in ChatGPT, Claude, Copilot or Gemini.
