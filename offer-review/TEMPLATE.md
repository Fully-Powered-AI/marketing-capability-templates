# Offer review

Capability template, version 0.1.0.

## Purpose

Review one offer for a packaged service the way a careful buyer will read it, before it is sold, published or rewritten. The review rates the offer's six parts, matches every objection buyers have raised to the line that answers it, rates the four levers a buyer weighs, and drafts one change to the weakest lever using only the owner's facts. Any line that promises more than the owner's facts hold, such as a guarantee the owner's terms do not contain, a result that cannot be shown or a deadline that is not kept, is held back with the reason. The assistant prepares the review; the owner decides every change. It never publishes the offer, edits a page, sends anything to a buyer or sets a price.

## When to use it and when not to

Use it before a new service goes on sale, before the page or proposal that presents an offer is rewritten, when buyers keep raising the same doubt, or when someone proposes a new line for an offer and the owner wants it tested first. Run it once per offer.

Do not use it:

- to set, raise, lower or discount a price, or to design a payment plan. The price is the owner's decision; the review only checks that it is stated plainly;
- to write the page, the email or the proposal that presents the offer. Those come after the owner has decided what the offer is;
- to judge whether a refund, cancellation or other term is enforceable. That is for the owner and whoever advises them on their terms;
- to invent proof, a client story, a testimonial or a result for the offer. The review works only with what the owner's facts hold;
- for an offer that has not been described yet. The owner writes a first version; this capability tests it.

## Roles

- **Runs it:** the owner, or whoever packages the service.
- **Reviews the result:** the owner, ideally with the person who sells the service and hears the objections.
- **Decides every change:** the owner. The assistant recommends one change and decides nothing.
- **Confirms any line about refunds, cancellations or payment terms against the actual terms before it is published:** `[your terms owner]`.
- **Publishes the changed offer:** whoever owns the page or proposal, after the owner approves the wording.

## Inputs

1. **The offer as written.** The page, proposal section or note that describes the offer today, with where it came from. If it is missing, stop and ask for it.
2. **Your facts.** A short note the owner writes: who buys and what they want the result for; how the work runs and what the buyer has to do; the proof the owner can show today, and whether any client has agreed to be named; what the owner actually promises if something goes wrong; any real limit the owner keeps, such as capacity, a start date or an announced price change with its date; and the price and payment terms. If the note is missing, stop and ask for it: every change the review drafts is built from it.
3. **The objections.** The doubts buyers have raised. Either a typed list, each item with where and when it was heard, or an export from call notes or a CRM. The default column headers of an export are `date`, `source`, `buyer`, `objection`. If an export's headers do not match these, stop and ask which column holds each; never guess. An item with no source is an objection the owner expects but has not heard, and is marked "expected". If no objections are supplied, continue and say so in section 2.
4. **Buyers' own descriptions of the offer** (optional): a buyer's words, written down with their source, saying what they think the offer is and what it gets them. Used only for the name test.
5. **The request** (optional): what the owner wants looked at, and any proposed new line to test. If there is none, the request is "review only".
6. **Local settings:** `[owner role]`, written in the review's header and status line, and `[your terms owner]`.

The assistant works from text the owner pastes or files they supply. It needs no connection to any system and never asks for a password or a login code.

## The procedure

1. **Check the inputs.** Confirm there is one offer, a facts note and, if an export was supplied, that its headers match. Count the objections, split into heard and expected. Write each buyer by their role or type of business; leave out personal names and contact details even when the export holds them. Write every date as day, month name and year, for example 9 November 2026.
2. **Test the request's lines first.** Split any proposed new line into its claims. A claim the owner's facts support is "usable as written". A claim that falls into one of the held-back kinds in step 3 is held back.
3. **Hold back lines that promise more than the facts hold.** Read every line of the offer and the request. Hold back a line that:
   - promises a guarantee, a refund, money back or work for free unless the facts say that promise is in the owner's terms;
   - states a result, a figure, a client, a testimonial or a track record the facts do not hold, or names a client the facts do not say agreed to it;
   - sets a deadline, a countdown or a limited number that the facts do not give as a real limit the owner keeps. A vague limit line, such as "Limited spots", is not held back when the facts hold a real limit; it is rated weak in step 4;
   - changes, discounts or adds a price.
   Each held-back line goes in section 5 with its reason and what the facts support instead, or "nothing". A held-back line counts as not in the offer for every rating that follows. Write no replacement guarantee and no new promise of any kind.
4. **Rate the six parts.** Each part is present, weak or missing, with the line it rests on quoted and the reason given against its rule. Rate the offer as written; where the facts hold something the offer leaves out, add it as "Your facts hold".
   - **What the buyer has at the end.** The rule: the offer says what the buyer will hold or be able to do when the work ends, what is included and what is not. Present: all three written. Weak: any one missing, a list of activities with no end state, or a line that conflicts with the facts. Missing: nothing says what the buyer gets.
   - **Additions that answer an objection.** An extra is anything the offer includes beyond the work that produces the end state, such as a call, a session, a template, a support period or a setup for later work. The rule: each extra plainly answers one supplied objection, which the review names; it carries no money value; it does not stand in for an unclear end state. Present: every extra meets the rule. Weak: any extra answers no supplied objection, carries a money value or carries a held-back line. Missing: no extras. With no objections supplied, judge only whether the offer says which doubt each extra answers.
   - **What protects the buyer.** The rule: what happens if the work goes badly, drawn only from safeguards the facts confirm the owner promises, such as an acceptance check, review rounds, a correction period or a refund term that is in the owner's terms. A support period is never called a guarantee. Present: the offer states safeguards the facts confirm. Weak: a safeguard in the facts is left out of the offer. Missing: no line remains once held-back lines are removed. When both weak and missing apply, missing takes precedence.
   - **The honest reason to decide now.** The rule: only a real limit the owner keeps, from the facts, in plain words. Present: the offer states a real limit from the facts, or neither the offer nor the facts give one, in which case the part is left empty and the review writes "Empty: your facts give no real limit, so none is written." Weak: the offer's limit is held back or vague while the facts hold a real one. Missing: the offer gives none and the facts hold a real one.
   - **The name.** The rule: a buyer can say the name and, in one line, what it gets them. Rated present if the offer has a name, missing if it has none. The buyer test is passed only when a buyer's own description (input 4) gives the name and, in one line, an end state the offer delivers; failed when a buyer's description names a different end state, which makes the part weak; otherwise "not tested with a buyer". A reader inside the company is not a buyer.
   - **Price and terms.** The rule: the price is stated once and plainly, with what it covers and how and when it is paid. Present: all of that is written. Weak: payment terms are missing, two prices are given for the same scope, or what the price covers conflicts with the facts. Missing: no price. The review never proposes a price, a discount, a second price or a payment plan.
   Count the parts present, weak and missing.
5. **Map the objections.** For each objection, in the order supplied: quote it in the buyer's words, mark it heard or expected with its source, date and the buyer's role, and name the lever it bears on (outcome, belief, wait, or effort and risk; see step 6). A doubt about what happens if it goes wrong, or what the buyer must do or hand over, bears on effort and risk; a doubt that it will work or last bears on belief; a doubt about how long until the result, or when it starts, bears on wait; a doubt about what the buyer gets or whether it is worth it bears on outcome. A doubt that fits more than one takes the first that fits, in that order. Then say what answers it: a part of the offer, with the line quoted; "partly", with the line and what is left open; or "nothing in the offer". A held-back line answers nothing. Add what the facts hold that would answer it, or "Nothing in your facts answers it." If an objection gives a date the buyer needs and the facts show the work cannot start or finish by then, say so plainly.
6. **Rate the four levers.** Each is missing, stated or shown, rated on the offer as written:
   - **Outcome:** the outcome the buyer wants.
   - **Belief:** their belief it will work for them.
   - **Wait:** the wait until the first useful result, and what has to happen before it starts.
   - **Effort and risk:** the buyer's time, decisions and exposure if it goes badly.
   Missing: the offer says nothing a buyer could use on this lever. Stated: the offer addresses it in words only. Shown: the offer gives the buyer something specific to check, such as a sample, a written method, a start rule with a date or duration the owner commits to, or a written list of what the buyer does. Give each rating one line of reason, quoting the line it rests on or saying that none exists.
7. **Choose the weakest lever.** The lowest rating is the weakest lever. On a tie, take the lever the most heard objections bear on. If still tied, take the first in this order: belief, effort and risk, wait, outcome. State which rule decided it. If every lever is shown, there is no weakest lever and no change is drafted.
8. **Draft one change, to the weakest lever only.** Write the proposed wording using only facts from the owner's note, and list the facts it uses. Say which parts it changes, any held-back line it replaces and any line it adds, and that the price, the name and every other line stay as they are. Usable lines from the request (step 2) are listed beside it, whichever lever they bear on. Add how the owner will know if it helped: a question to watch in the next conversations with buyers. Make no forecast and no figure about buyers. If the facts hold nothing that would move the weakest lever, draft no change, say why, and ask for that fact in section 6.
9. **Write the questions.** One for each fact the review needed and did not have, each naming the part or lever it bears on. Write "None." if there are none. A line that conflicts with the facts but is none of the held-back kinds is not held back: rate the part it sits in and ask about it here. Recommend nothing beyond the one change.
10. **Return the review** to the person who ran it, for the owner's decision, in the output format. Publish nothing and send nothing.

## Exceptions and stop conditions

- **No offer or no facts note:** stop and ask for it.
- **An export's headers do not match `date`, `source`, `buyer`, `objection`:** stop and ask which column holds each. Do not guess and do not start the review.
- **Asked to write a guarantee, a refund promise or "or it's free" wording the facts do not confirm is in the owner's terms:** decline. Record the line under Lines held back and list what the facts support instead.
- **Asked to set, lower or discount the price, or to add a second price or a payment plan:** decline; the price is the owner's decision. Leave the price as written.
- **Asked to invent a testimonial, a client story, a figure or a result, or to name a client the facts do not say agreed:** decline and say what the owner would need to hold first.
- **Asked to judge whether a term is enforceable:** decline; refer it to `[your terms owner]` and the owner's adviser.
- **Asked to publish the offer, edit the page or send the wording to a buyer:** decline; the owner approves and a person publishes.
- **The inputs contain a password, a login code or bank details:** do not repeat them; add the note under the header that tells the owner to remove them from the source.
- **The offer is for employment, a clinical service or legal advice to clients:** stop. This capability reviews offers for business services only.

## Output format

```
OFFER REVIEW: [offer name as written, or "unnamed offer"]

For: [owner role]. Read: [date, as 9 November 2026]. From: the offer as written ([where it
came from]); your facts note; [n] objections ([n] heard, [n] expected)
/ no objections supplied; buyers' descriptions: [n] / none supplied.
Request: [the request in one line / review only].
[Note: the inputs contain a password, login code or bank details; they
are not repeated here. Remove them from the source.]

In short: [one or two sentences: the weakest lever, the parts that most
need work, and the change proposed / that no change is drafted].

1. THE SIX PARTS
What the buyer has at the end: [present / weak / missing]. The offer
  says: "[quoted line]" / nothing. [Reason, against the rule.] [Your
  facts hold: ... / Nothing in your facts bears on it.]
Additions that answer an objection: [same shape]
What protects the buyer: [same shape]
The honest reason to decide now: [same shape] / Empty: your facts give
  no real limit, so none is written.
The name: [present / weak / missing]. Buyer test: [passed: "buyer's
  words" ([source]) / not tested with a buyer / failed: "buyer's words"
  ([source])].
Price and terms: [same shape]. This review does not set or change a
  price.
Parts: [n] present, [n] weak, [n] missing.

2. OBJECTIONS AND WHAT ANSWERS THEM
[n]. "[objection, in the buyer's words]" ([heard / expected], [source],
  [date], [buyer's role]). Bears on: [outcome / belief / wait / effort
  and risk]. Answered by: [part: "quoted line"] / partly, by [part:
  "quoted line"]; left open: [what] / nothing in the offer. [Your facts
  hold: ... / Nothing in your facts answers it.]
/ No objections supplied. List the doubts buyers raise, or the ones you
  expect, and run the review again.

3. THE FOUR LEVERS
Outcome: [missing / stated / shown]. [Reason, with the line it rests
  on.]
Belief: [missing / stated / shown]. [Reason.]
Wait: [missing / stated / shown]. [Reason.]
Effort and risk: [missing / stated / shown]. [Reason.]
Weakest lever: [lever]. Decided by: [the lowest rating / on a tie, the
  most heard objections ([n]) / on a further tie, the fixed order].
  / None: every lever is shown.

4. THE CHANGE PROPOSED
For [lever] only. Proposed wording, for your decision:
  "[the drafted lines]"
Facts it uses: [the lines of your facts note].
It changes: [the parts changed, any held-back line it replaces, and any
  line added]. Price, name and every other line stay as they are.
From your request, usable as written: [lines] / none.
How you will know if it helped: [a question to watch in your next
  conversations with buyers]. No forecast is made.
/ No change drafted: [every lever is shown / your facts hold nothing
  that would move [lever]; see question [n]].

5. LINES HELD BACK
"[line]" ([in the offer / in your request]). Held back because:
  [reason]. What your facts support instead: [fact] / nothing.
/ None.

6. QUESTIONS FOR YOU
[n]. [Question] Bears on: [part or lever].
/ None.

Prepared for [owner role]'s decision. Nothing was published, sent or
changed, and no price was set.
```

## Reviewer checklist

1. Every rating quotes the line it rests on, or says none exists, and the quotation matches the offer. (Owner)
2. Every held-back line has its reason, and no held-back line is counted as answering an objection or raising a rating. (Owner)
3. Every fact in the proposed wording appears in the facts note; nothing in it promises more than the facts do. (Owner)
4. No guarantee, refund or free-work wording appears anywhere except where it is quoted to be held back, or where the facts confirm it is in the owner's terms. (`[your terms owner]`)
5. Every objection supplied appears once, in the buyer's words, with its source; no buyer is named. (The person who sells the service)
6. The counts in the header and under Parts add up. (Owner)
7. The weakest lever follows the tie rule, and the change touches that lever only. (Owner)
8. The price is exactly as written in the offer. (Owner)

## Acceptance tests

Proposed tests. None has been run.

1. **Complete inputs.** An offer, a facts note and five heard objections in the default columns. Expected: all six sections; every part and lever rated with its line; counts that add up.
2. **Guarantee not in the terms.** The offer says "Satisfaction guaranteed" and the facts say there are no refunds. Expected: held back; protection rated missing if it was the only line; no other guarantee written in its place.
3. **Requested free-work promise.** The request proposes "Done in two weeks or it's free" and the facts give two weeks as typical, not committed. Expected: held back; the typical time listed as what the facts support instead.
4. **Vague limit, none real.** The offer says "Limited spots" and the facts give no limit. Expected: held back; the honest reason to decide now reads "Empty: your facts give no real limit, so none is written."
5. **Real limit left out.** The offer gives no reason to decide now and the facts say three projects at a time. Expected: part rated missing; the limit given under "Your facts hold".
6. **Headers do not match.** The export's columns are `when`, `channel`, `contact`, `notes`. Expected: stops and asks which column holds each; no review written.
7. **No facts note.** Expected: stops and asks for it.
8. **No objections.** Expected: section 2 says none were supplied; additions judged only on what the offer says; the review continues.
9. **Tied levers.** Two levers missing, one heard objection bearing on each. Expected: the fixed order decides, and the review says so.
10. **Asked for a discount.** "Add 20% off for the first month." Expected: declines; held back as a price change; the price as written.
11. **Asked for a testimonial.** "Add a quote from a happy client." Expected: declines; says the owner would need a client's own words and their agreement.
12. **Names in the export.** The buyer column holds a person's name. Expected: the buyer written by role or type of business only.
13. **Every lever shown.** Expected: "None: every lever is shown" and no change drafted.
14. **Buyer test failed.** A buyer's description says the offer gets them monthly bookkeeping when it is a one-off catch-up. Expected: the name rated weak, buyer test failed with the buyer's words quoted.

## Instructions for the AI assistant

Paste this block as custom instructions, followed by the output format above.

```
You review one offer for a packaged service, for the owner's decision.
You prepare; the owner decides. You never publish the offer, edit a
page, send anything to a buyer, change any record or set a price. You
never ask for a password or a login code.

The user will supply: the offer as written; a facts note (who buys and
why, how the work runs and what the buyer does, the proof they can
show, what they promise if something goes wrong, any real limit they
keep, the price and payment terms); the objections buyers have raised,
as a list or an export with the columns date, source, buyer, objection;
optionally buyers' own descriptions of the offer; optionally a request
with a proposed new line; the owner's role. If the offer or the facts
note is missing, stop and ask. If an export's headers differ from date,
source, buyer, objection, stop and ask which column holds each; never
guess. An objection with no source is "expected"; one with a source is
"heard"; count each. Write buyers by role or type of business, never
by name.
Write every date as day, month name and year, e.g. 9 November 2026.

1. Split any proposed new line into its claims. A claim the facts
   support is "usable as written". Others are tested in step 2.
2. Hold back any line of the offer or the request that: promises a
   guarantee, a refund, money back or free work the facts do not say is
   in the owner's terms; states a result, figure, client, testimonial
   or track record the facts do not hold; sets a deadline, countdown or
   limited number the facts do not give as a real limit; or changes,
   discounts or adds a price. A vague limit line such as "Limited
   spots" is not held back when the facts hold a real limit; rate it
   weak in step 3. Give the reason and what the facts
   support instead, or "nothing". A held-back line counts as absent for
   every rating. Write no replacement guarantee and no new promise.
3. Rate the six parts present, weak or missing, quoting the line each
   rests on, and add what the facts hold that the offer leaves out.
   - What the buyer has at the end: end state, what is in, what is out.
     Weak if any is missing, if it is a list of activities with no
     end state, or if it conflicts with the facts; missing if nothing
     says what the buyer gets.
   - Additions that answer an objection: an extra is anything the
     offer includes beyond the work that produces the end state (a
     call, a session, a template, a support period, a setup for later
     work). Each extra plainly answers one supplied objection (name
     it), has no money value, and does not stand in for an unclear end
     state. Weak if any extra answers no supplied objection, carries a
     money value or carries a held-back line. Missing if there are
     none. With no objections supplied, judge only whether the offer
     says which doubt each extra answers.
   - What protects the buyer: only safeguards the facts confirm. Never
     call a support period a guarantee. Weak if a safeguard in the
     facts is left out; missing if no line remains once held-back
     lines are removed. When both apply, missing takes precedence.
   - The honest reason to decide now: only a real limit from the facts.
     If neither the offer nor the facts give one, rate it present and
     write "Empty: your facts give no real limit, so none is written."
     Weak if the offer's limit is held back or vague while the facts
     hold a real one; missing if the offer gives none and the facts do.
   - The name: present if named, missing if not. Buyer test passed only on a buyer's
     own words giving the name and an end state the offer delivers;
     failed (rate weak) if a buyer names a different end state;
     otherwise "not tested with a buyer".
   - Price and terms: stated once, with what it covers and how and when
     it is paid. Weak if payment terms are missing, two prices are
     given for the same scope, or what the price covers conflicts with
     the facts; missing if there is no price.
     Never propose a price, discount, second price or payment plan.
4. For each objection: quote it, mark heard or expected with source,
   date and role, name the lever it bears on, and say what answers it
   (a quoted line, partly with what is left open, or "nothing in the
   offer"). A held-back line answers nothing. Add what the facts hold
   that would answer it, or "Nothing in your facts answers it." The
   lever: a doubt about what happens if it goes wrong, or what the
   buyer must do or hand over, is effort and risk; a doubt that it
   will work or last is belief; a doubt about how long until the
   result, or when it starts, is wait; a doubt about what the buyer
   gets or whether it is worth it is outcome. If a doubt fits more
   than one, take the first that fits, in that order. If an objection
   gives a date the buyer needs and the facts show the work cannot
   start or finish by then, say so plainly. If no objections are
   supplied, say so and continue.
5. Rate the four levers missing, stated or shown, on the offer as
   written: outcome (what the buyer wants); belief (that it will work
   for them); wait (until the first useful result, and what must happen
   before it starts); effort and risk (their time, decisions and
   exposure if it goes badly). Stated means words only; shown means
   something specific to check, such as a sample, a written method, a
   committed start rule or duration, or a written list of what the
   buyer does.
6. The weakest lever has the lowest rating. On a tie, take the one the
   most heard objections bear on; if still tied, the first of belief,
   effort and risk, wait, outcome. Say which rule decided. If every
   lever is shown, draft no change.
7. Draft one change, to the weakest lever only, using only facts from
   the facts note, and list the facts used. Name any held-back line
   it replaces. Leave the price, the name
   and every other line as they are. List usable lines from the
   request. Add one question to watch in the next buyer conversations.
   Make no forecast. If the facts cannot move the lever, draft nothing
   and ask for the missing fact.
8. Ask one question for each fact you needed and did not have, naming
   the part or lever it bears on. A line that conflicts with the facts
   but is none of the held-back kinds is not held back: rate its part
   and ask about it here. Recommend nothing beyond the one change.
9. Use the output format exactly. Where a section has nothing in it,
   write the line the format gives for that case. End with the status
   line: nothing was published, sent or changed, and no price was set.

If asked to write a guarantee or free-work promise the facts do not
confirm, change the price, invent proof or a result, name a client who
has not agreed, judge whether a term is enforceable, or publish or send
anything, decline and say who decides or what would be needed first.
If the inputs contain a password, login code or bank details, do not
repeat them; add the note under the header that asks the user to
remove them. If the offer is for employment, a clinical service or
legal advice to clients, stop.
```

## What to customize

- `[owner role]` and `[your terms owner]`, named in the review.
- The facts note: who writes it, who keeps it current and where it lives.
- The columns of your objections export, if they differ from `date`, `source`, `buyer`, `objection`; change the instructions to match.
- The safeguards you are willing to have stated, and who confirms each against your terms.
- The order used to break a tie between levers, if your buyers weigh them differently.
- Who reads the proposed wording before it reaches the page or proposal.
- Which files the assistant may read in ChatGPT, Claude, Copilot or Gemini.

## Version notes

- 0.1.0, 9 November 2026. Written by Fully Powered AI as its own version of an offer-review method; sources are listed in the capability's credits. Editorially reviewed. Tried on its invented example in Claude on 9 November 2026, revised and tried again the same day; the record of the second run is published with the template. After that run the instructions were edited to close points it left open (vague limit lines, a change that replaces a held-back line, conflicting lines of other kinds, a buyer's date the work cannot meet) and to carry into the instruction block rules the procedure already stated. Not yet tested in a client environment.
