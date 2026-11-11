# Affiliate onboarding: trial on the invented example

- **Product:** Claude, run in Claude Code
- **Model:** Claude Opus 5.5 (model ID claude-opus-5-5)
- **Date:** 2026-11-09

The inputs were the invented example in `public/example.md` (Quillmoor Tea Company, the creator Dana Ruiz and the codes are all made up). No client data was used.

This is the second run on the example. A first run the same day, by Claude Sonnet 5.5 in Claude Code, followed the template as written and matched the example in every figure and date, but found that the pack told the creator a sale counts once 30 days pass "without a refund or cancellation", which the programme rules did not say, and noted eight smaller ambiguities. After an editorial review, the template was changed: the holdback sentence now states only the number of days, a refund and cancellation line is read from the programme rules (and added to the example's rules), the creator's first-weeks list, working days, the live-post check and the payout set-up check are defined, the "Ready to send" line points to open items when there are any, and the instruction block now carries the commission variants, the no-export rule and the payout paragraph's limits. This run tests the changed template.

**Not an independent run.** The same session made the changes and then ran the template, and it had read the earlier example output. The output below was produced from the instruction block, the output format and the example's six inputs, and then compared with the earlier example output; the example's published output was then replaced with this run's output.

## Inputs used

The six inputs in `public/example.md`, by reference: the programme rules (now including "Refunds and cancellations: a sale refunded or cancelled within the holdback earns no commission"), the creator's record, the code and link as made, the checkout test, the codes in use (five rows, headers `code, held_by, status`), and the dates for the first weeks. The template's instruction block and output format were followed as written; the "[your payout set-up check days]" placeholder in the block was left unset.

## What came out

Every required part of the output format was produced, in order: the readiness section, the welcome pack, the first-weeks checklist, the roster entry, the figures with their sources, the open items with the coverage line, and the closing draft line. Nothing in the inputs triggered a stop.

- **Readiness:** all gates passed. Terms were agreed in writing on 4 November 2026. Instagram is allowed. The code STEEPWITHDANA15 clashes with none of the five codes (STEEPWITHDAN15, held by c-000098 and ended, is a different code: one letter shorter). The link carries `utm_content=c-000127`. The test showed "15% off", which matches the rules' 15 percent, and checkout accepted only one of two codes, which matches the rules.
- **Ready to send:** "yes, after reading the open items in section 6".
- **Welcome pack:** the code, link, 15 percent, the window (from 6 November 2026, no end date), the combining sentence ("Your code cannot be used together with another discount code at checkout."), the attribution rule, the posting rule, 12 percent of the order subtotal after discounts before shipping and tax, the self-referral rule, the payout schedule word for word, "A sale counts once 30 days have passed.", "A sale refunded or cancelled within the holdback earns you no commission.", the direct bank-transfer paragraph with the payee-form step, the Instagram disclosure wording, the pointer to the Winter Blends brief, the creator's dates and the contact.
- **The creator's first weeks:** 10 Nov sampler ships; 16 Nov finance checks the payee form; 20 Nov draft due; 24 Nov the programme lead replies; 27 Nov first post; 28 Dec review of the first 30 days.
- **First weeks for the programme lead:** 9 Nov send pack and brief; 10 Nov ship the sampler; 16 Nov payout set-up check (9 Nov plus 7 days, the number taken from the inputs); 20 Nov draft due; 24 Nov reply (20 Nov plus 2 working days); 27 Nov first post and the check of the live post that day; 4 Dec first-orders check; 28 Dec day-30 review, moved from Sunday 27 December.
- **Earliest payout run that can include a sale on this code:** Tuesday 15 December 2026 (6 November plus 30 days is 6 December, a Sunday; the next run under "monthly on the 15th" is 15 December).
- **Roster entry:** c-000127, the code, the link, made in the store admin, active, tested 6 November 2026 by the operations lead, test order #2087 left out of commission and reports.
- **Open item:** combining with the free-shipping offer over USD 40 was not tested (the test order was USD 18.00), so the pack says nothing about it. The operations lead settles it at the next test.

## What was observed

**Against the earlier example output.** Every readiness result, every checklist date, the payout-run computation, the roster entry and the open item were the same. The differences were the changes the review asked for: the Ready line now points to the open item; the holdback sentence no longer mentions refunds, and the refund line from the rules follows it; the creator's list now includes the day-30 review; the live-post check is named by the day it happens; the figures list adds the refund line and the 28 December date. Two lines were worded closer to the inputs than before: the disclosure placement ("in the first line of your caption", where the earlier output said "Begin the first line") and the reply on the draft ("replies on your draft", where the earlier output added "with a go or the changes needed", which no input says).

**Against the reviewer checklist.** All seven points could be checked and held, including point 2 as now written: no rule appears in the pack that the programme rules do not hold.

**Ambiguities and guesses.**
1. The attribution rule says an order through the link with no code is "credited second". It was copied as written. It is still not clear what "second" means, and the template still has no instruction for a rule line that is unclear rather than missing.
2. "Clash check against [n] codes" was filled with 5, the rows in the export. The two store promotion codes in the rules are also in the export and were not counted twice. The output format does not say how to count codes that appear in both.
3. The refund line keeps the rules' word "holdback", which the creator otherwise meets only in the payout schedule copied word for word. The template copies it; it does not explain it.
4. No public holidays were supplied, so 28 December was treated as a working day, as the template now says.
5. The combining sentence still covers only other discount codes, because the free-shipping case was not tested. The Ready line now tells the programme owner to read that open item first.
6. "Send your draft Reel and stories to the programme lead" names the programme lead because the rules make that role the creators' contact and the receiver of drafts is not otherwise stated.

**Facts in the output not in the inputs.** None found. The refund statement now traces to a line in the programme rules. The brand name in "Welcome to the Quillmoor Tea creator programme" comes from the rules' disclosure wording; "Winter Blends brief" comes from the dates input.

**Stops.** None. The inputs were complete and clean, so the stop conditions, the "date not set" path for an unset payout check and the missing-refund-line path were not exercised. The template's twelve acceptance tests were not run; this was one ordinary run only.

**Limits of this record.** One run, by one model, on one invented example, in one product, by the session that had just edited the template. It does not show how the template behaves on messy real inputs, in other products, or for a client.

## Changed after this run, and not run again

Changed on 10 November 2026 after a further editorial review, and not run again. The output and the observations above are as recorded and describe the template as it stood at the run:

- **The coverage line.** The instruction block's step 6 now names the three things listed as not judged (codes in the store that the export does not list; whether the store or tool will credit and pay as the rules say; whether the disclosure wording meets each country's rules). The procedure already named them, and this run and the example already wrote them; the block alone did not say so.
- **Credits.** Four files the credits already named (two from finsilabs/awesome-ecommerce-skills, one from coreyhaines31/marketingskills and one from aaron-he-zhu/aaron-marketing-skills) now have source entries, and the Apache-2.0 notice for aaron-he-zhu/aaron-marketing-skills was added. Nothing in the template or the example changed for this.
