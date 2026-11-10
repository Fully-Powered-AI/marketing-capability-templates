# Event plan: tried on its invented example

- **Product:** Claude, run in Claude Code
- **Model:** Claude Opus 5.5 (model ID claude-opus-5-5)
- **Date:** 2026-11-09

The inputs were the invented example in [example.md](example.md): Tallowby IT, the Calderbrook Chamber of Commerce and its Harbourside Business Breakfast are all made up. No client data was used.

## The earlier run, and what was edited after it

The template was first run on the same example earlier the same day, in Claude (Claude Sonnet 5.5), blind: the model read the template and only the nine inputs, produced its plan, and then compared it with the published output. That run produced every section of the output format, with the same dates, 19 lines, 7 outward lines and 1 payment line as the published example. It also found places where the template left a choice open, and places where the published example stated things the inputs did not hold: the note to the organiser and the slides sent "from the founder's email" and owned by the founder although no role's work in the team note covered writing to the organiser; "the organiser loads them for the day" on the slides line; "about 60" given as the number the talk goes to, where the organiser said only that about 60 usually attend; and a record column for accepted meeting times that the record does not have.

After an independent review of that run, the template and the example were edited, and the run was repeated on the edited version. The edits:

1. **Owner and sender of the note to the organiser.** Line b now names its owner, the event owner. Every outward line's "From" is the address the team note gives its owner, else "not named", with a question. The example's team note now says the founder writes to the organiser from their own email.
2. **Non-working event day.** The instruction block now carries the procedure's rule that a non-working E is stated first under Questions.
3. **"Invite to the session".** The template now says a session may be the business's own talk at an organiser's event, and the note to the organiser asks whether invited guests need a ticket of their own when the terms do not say.
4. **The record's columns.** Line a now adds a column for each field of the conversation note the record lacks, and for the time agreed for a 15-minute meeting.
5. **Drafts needed.** Only drafts an outward line sends are listed; work that is itself a line, such as the talk outline, is not.
6. **The listener for the run-through.** The listener is the person the event owner names, else "listener not named", with a question.
7. **Costs paid on the day,** such as parking: the approver approves each at its amount in the E-1 approval line, with the day's material.
8. **The example's slides line** now reads "What follows: D1", and the talk line reads "count not known until the day; about 60 usually attend (organiser's email, 2 November 2026)".

## How this run was made

This run was not blind. It was made by the model that made the edits above, which had already read the earlier run's record and the published example as it stood before the edits. It read the edited template and the nine inputs of the edited example, followed the instruction block and the output format, and produced the plan below. The published example's output was then brought into line with this run's output, so the two now match line for line. Because the same model edited and ran the template, this record shows that the edited template produces a complete and consistent plan from these inputs; it is weaker evidence than a blind run.

## What came out

A full plan in the output format, with every section present.

- **Event:** Harbourside Business Breakfast, Thursday 3 December 2026, 7:30 to 9:30 am, in the chamber's meeting room. Roles: speaking and attending. Event owner and approver: the founder. Not supplied: none.
- **Goal and target:** conversations with office managers and operations leads at businesses of 20 to 100 people. Target as the founder set it on 9 November 2026: 6 conversations noted and 2 follow-up meetings booked by Thursday 17 December 2026.
- **Who attends:** the organiser's own words ("About 60 members usually attend; mostly owners and managers of local businesses", 2 November 2026), with no breakdown by role, asked in B2.
- **Opening question (proposed):** "When did your office last replace its laptops, and how did it go?" **Introduction line (proposed):** built from the facts note: offices of 10 to 150 people, and laptop refreshes for 23 local offices since 2022, unnamed.
- **People to reach:** four office managers at current clients, invited to the session by the account manager (B4); three operations leads asked for 15 minutes at the event by the founder (B5); the newsletter readers (about 900) not used because their ask is "none".
- **Checklist:** 19 lines, 7 outward, 1 payment.
  - Before, ten lines: B1 Monday 9 November, add the breakfast as a source in the Enquiries sheet and add the columns it lacks (role, situation, what matters most, tier, noted by, time agreed), office coordinator; B2 the same day, the note to the organiser asking about recording, reuse, attendees by role and whether the invited office managers and operations leads need tickets of their own, from the founder's email, owned by the founder; B3 the talk outline, Thursday 19 November; B4 the invitations and B5 the requests for 15 minutes, Monday 23 November; B6 the $35 second ticket, office coordinator, and B7 the timed run-through, both on Wednesday 25 November; B8 the slides to the organiser, Monday 30 November, from the founder's email, what follows D1; B9 the briefing, Tuesday 1 December; B10 the founder approves the slides and the parking ($24, the founder's estimate), Wednesday 2 December.
  - The day, five lines: D1 the talk, to breakfast attendees, "count not known until the day; about 60 usually attend (organiser's email, 2 November 2026)", go given in B10; D2 questions from the floor noted by the account manager; D3 the founder meets each operations lead who accepted, at the time agreed; D4 and D5 a conversation-note line each for the founder and the account manager.
  - After, four lines: A1 enter notes and questions and sort into tiers, Friday 4 December; A2 and A3 the founder's and the account manager's tier 1 and tier 2 follow-ups, each from their own email, Monday 7 December; A4 review against the target, Thursday 17 December.
- **Dates moved off closed days:** the ticket deadline (Friday 27 November, closed) moved to Wednesday 25 November, and the run-through (E-5, Saturday 28 November) moved back past the two closed days to Wednesday 25 November. Both lines say what they moved from.
- **Follow-up:** by Monday 7 December. Tier 1 a personal note confirming the step; tier 2 one short note offering the free 30-minute laptop check call once; tier 3 nothing; registered-and-did-not-attend not applicable.
- **Drafts needed:** 6: the note to the organiser, the invitation, the request for 15 minutes, the slides and the two sets of follow-up notes.
- **Cost:** the founder's figures of 9 November 2026. Ticket $35 quoted; parking $24 estimated (the founder's); handout unavailable and left out. Known money $59 ($35 quoted, $24 estimated). Hours 14 (founder 10, account manager 4).
- **Questions for the founder:** 4: the proposed opening question, the proposed introduction line, whether there is a printed handout, and who listens to the run-through in B7.
- It ended with the line that nothing has been registered, booked, paid, sent, posted or published.

## What was observed

Nothing in the inputs was a stop condition, the event day was a working day and no two inputs disagreed. The assistant was not asked to send, pay or estimate anything and did none of those. The two tests the template lists that this example touches both held: the Saturday run-through after a closed Thursday and Friday moved back to the Wednesday, and the payment deadline on the closed Friday moved to the working day before, quoting the amount and its source. Dates and sums were rechecked: E-24, E-14, E-10, E-8, E-3, E+1, E+4 and E+14 fall on the dates given; $35 + $24 = $59; 10 + 4 = 14 hours.

Where a choice still had to be made:

1. **The organiser as recipient.** The inputs name the organiser as the chamber and cite "the organiser's email". This run wrote "To: the chamber's organiser, 1", reading that as one contact.
2. **Paying the ticket.** The office coordinator "books travel and tickets"; this run read that as covering the payment line for the second ticket.
3. **The talk line's count.** The template offers "count not known until the day" or a count. This run gave the first and added the organiser's own words with their source, which is not a form the template spells out.
4. **"Two working days after E".** This run did not count E: Friday 4 December is the first working day after it and Monday 7 December the second.
5. **Guests' tickets.** If the organiser answers that invited guests need tickets, the template does not say who pays or when; that waits for the next run with the answer.
6. **Who pays the parking on the day.** B10 approves the amount; the inputs do not say who pays it, and the template does not ask.

Facts in this run's output that are not in the inputs: none found beyond the proposed opening question and introduction line, which are the assistant's own wording, built from the facts note and marked "proposed". The run left the 900 newsletter readers unused, quoted no result, name or discount, and named no client.

The template's acceptance tests have still not been run as such. This record covers one example, in one product, and is not a test in a client environment.

## Edits after this run

On 10 November 2026, after a second independent review, the template was given small clarifications. The run above was not repeated for them: by reading, none changes this example's output, because the example supplies the event day and the working days, is not a webinar, has no answer yet from the organiser about guests' tickets and has no cost on the day above its amount. The run's output and the observations above are left as recorded.

1. **The instruction block** now carries three rules the procedure already had: missing working days default to Monday to Friday, said so; a missing event day means every date is written as an offset only; a cost on the day above its approved amount goes back to the approver.
2. **The instruction block's follow-up step** now adds the note to webinar registrants who did not attend, or "not applicable", as the procedure and the output format already did.
3. **The instruction block's questions step** now says "missing date or deadline", as the procedure does.
4. **The count on an outward line** may now add what the organiser says about attendance, with its source and date, beside "count not known until the day". This is the form this run used on D1 (observation 3).
5. **Guests' tickets** (observation 5): once the organiser says invited guests need a ticket of their own, the plan asks the event owner whether the business pays for them, and each ticket it pays for becomes a payment line.
6. **Costs paid on the day** (observation 6): such a cost is approved in the E-1 approval line, is not a payment line and is not counted as one, and whoever incurs it pays it within its approved amount. This is why the example's checklist counts 1 payment line although B10 approves the $24 parking.
