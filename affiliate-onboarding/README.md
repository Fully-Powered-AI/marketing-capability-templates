# Affiliate onboarding

A programme owner brings a new affiliate or creator in: the code and link the store gave are checked against the programme rules and a test at checkout, then a welcome pack and a dated first-weeks checklist are prepared. A person sends, creates and pays.

*Capability template · Marketing and content · version 0.1.0 · [Capabilities Directory](https://fullypowered.ai/capabilities/affiliate-onboarding/)*

## The outcome

A creator who has just agreed terms gets one clear welcome pack: their own code and link, what their audience gets, what they earn and when they are paid, exactly how to label a paid post on their platform, and the dates of their first draft and first post. Every figure in it is copied from where it is written down (the brand's own programme rules, the creator's record, the code as the store made it), and the programme owner sees each one listed with where it came from.

Nothing reaches the creator until the basics are proven. The terms are in writing, the platform is one the brand allows, the code clashes with no other code (old ones included), the link names the creator, and someone has tried the code at checkout and seen the right discount. If any of that fails, the pack is not drafted and the programme owner sees what to fix and who fixes it.

The programme owner also gets the first weeks on one dated list, with an owner on every line: the pack goes out, the payout set-up is confirmed well before the first payout run, the draft comes in and gets a reply on time, the first post is checked on its first day, early orders on the code are looked at, and a review is held at day 30.

## Who starts the work, and when

The programme owner or the marketing lead who runs the creator programme starts it for each new creator, once the terms are agreed in writing, the code and link have been made in the store or affiliate tool, and someone has tried the code at checkout. It runs again if a code has to change or a programme rule is settled before the pack goes out. The programme owner approves the pack and sends it with the creator brief.

## What they supply

- **The programme rules:** the discount, whether codes combine with other discounts, commission basis, holdback and what a refund or cancellation does to a sale, payout schedule and set-up, attribution and self-referral rules, allowed platforms, disclosure wording, and roles.
- **The creator's record:** the deal, the agreed rate, the date the terms were agreed in writing, and the first campaign dates.
- **The code and link as made,** copied from the store or tool, with the code's dates and limits.
- **The checkout test result,** as the person who ran it wrote it down.
- **The codes already in use,** exported from the roster or the store.
- **The remaining dates:** when the pack goes out, when any product gift ships.

## What comes out

A readiness section showing each check passed or what stopped it. Then the welcome pack, ready for the programme owner to send; the first-weeks checklist with dates, owners and where each date came from, and the earliest payout run with its arithmetic; the roster entry for a person to make, with any test order marked so it never earns commission; every figure in the pack with its source; and the open items. The pack makes no statements about the products: what a creator may say lives in the brief.

See the worked example with invented data in [EXAMPLE.md](EXAMPLE.md).

## Where it fits

- [Marketing and content](https://fullypowered.ai/functions/marketing-and-content/), which runs the creator programme and owns every word that goes to a creator.
- [Consumer brands](https://fullypowered.ai/industries/consumer-brands/), where creators are a main route to new buyers and each new partner should start on exactly the same terms as the last.
- [Ecommerce and retail](https://fullypowered.ai/industries/ecommerce-and-retail/), where a code entered at checkout is the clearest record of which creator brought a sale.
- [Marketing and advertising](https://fullypowered.ai/industries/marketing-and-advertising/), where an agency runs a client's creator programme and needs every onboarding to be consistent and checkable.
- [Growth and scaling](https://fullypowered.ai/situations/growth-and-scaling/), when new creators arrive faster than one person can onboard them carefully by hand.
- [New business lines](https://fullypowered.ai/situations/new-business-lines/), when a brand opens creators as a channel and the first partners set the pattern.

## What has to change for your company

Write your programme rules first; this capability reads them and sets none of its own. The [creator programme setup](https://fullypowered.ai/capabilities/creator-programme-setup/) capability prepares them with your owner. Name who makes codes and runs the checkout test, who sends the pack, who keeps the roster and who pays. Write the fixed sentences of the pack once in your own voice. Set the timing of the first-weeks checks. Keep the brief separate: the [creator brief](https://fullypowered.ai/capabilities/creator-brief/) carries what a creator may say about your products, and the [creator commission statement](https://fullypowered.ai/capabilities/creator-commission-statement/) works out what they are owed later. Your adviser handles the creator agreement itself. It runs in ChatGPT, Claude, Copilot or Gemini from files and notes you supply, with no access to your store, your affiliate tool or your bank.

## What has been checked

Fully Powered AI wrote this capability template in its own words, from the affiliate onboarding work in its own Influencer Marketing set. It was editorially reviewed on 10 November 2026. It was tried on its invented example on 9 November 2026 in two runs, the second after the first review's changes; the record of the second is published with it, and lists the small edit made afterward that has not been run again. It has not yet been tested in a client environment. It has not yet been tested as a packaged version in ChatGPT, Claude, Copilot or Gemini.

Testing in your environment means running it on past onboardings your programme owner remembers, plus hard cases written in advance: a code that matches an old ended one, a link with nothing that names the creator, a checkout that showed the wrong discount, a codes export with renamed columns, a request to add a product claim. Your programme owner checks every figure against the rules before a pack goes out. [Pilot acceptance-test preparation](https://fullypowered.ai/capabilities/pilot-acceptance-test-preparation/) builds that test set, and [what we test before we call an AI workflow ready](https://fullypowered.ai/insights/what-we-test-before-a-workflow-is-ready/) describes the record we keep.

- Written by Fully Powered AI.
- Sources and rights reviewed.
- Editorially reviewed on 10 November 2026.
- Package format checked by script on every release.
- Tried once on its invented example in Claude on 9 November 2026. The record is in [TRIAL.md](TRIAL.md).
- Not yet tested in a client environment.

## What is in this folder

- [TEMPLATE.md](TEMPLATE.md): the complete capability template. Roles, inputs, the procedure, exceptions and stop conditions, the output format, a reviewer checklist, acceptance tests, the instructions for an AI assistant and what to customize.
- [EXAMPLE.md](EXAMPLE.md): a worked example with invented data.
- [TRIAL.md](TRIAL.md): what came out when the template was tried on its example.
- [SKILL.md](SKILL.md): the technical file, for AI products that load packaged instructions from a folder.
- [SOURCES.md](SOURCES.md): what the capability drew on, with licences.
- [LICENSE](LICENSE): MIT. Use it, change it, make it yours.

## Start using it

1. Read [EXAMPLE.md](EXAMPLE.md) to see what a good result looks like.
2. Open [TEMPLATE.md](TEMPLATE.md) and set every item under "What to customize" to your own rules, roles and limits.
3. Give your AI assistant the instruction block and the output format from the template, with your own limits in place of the ones the instructions leave open in square brackets. Paste them in as custom instructions in ChatGPT, Claude, Copilot or Gemini, or copy this whole folder into a product that loads `SKILL.md` packages. This folder stands alone; you do not need the rest of the repository.
4. Run it on past work first, using the reviewer checklist and acceptance tests in the template, before anyone relies on it.

## Related capabilities

- [Creator programme setup](../creator-programme-setup/)
- [Creator roster](../creator-roster/)
- [Creator brief](../creator-brief/)
- [Creator commission statement](https://fullypowered.ai/capabilities/creator-commission-statement/)

## Make it yours

This is the starting version. Fully Powered AI adapts capabilities to how your company works, proves them on real work and rolls them out to the roles that use them. [Talk with us](https://fullypowered.ai/contact/).
