# Creator roster

The programme owner keeps one record of every creator the brand works with: where each relationship stands, what each creator still owes the brand, what the brand still owes each creator, and when rights and exclusivity end. It is built from the files the owner supplies; nothing is sent or paid.

*Workflow template · Marketing and content · version 0.1.0 · [Workflows Directory](https://fullypowered.ai/workflows/creator-roster/)*

## The outcome

Every creator your brand has found, approached, signed or turned down lives in one place, under a reference that never changes even when a handle does. Each row says where the relationship stands and why, in dated notes that only ever grow.

Beside it sits the other half of every relationship: what is owed. Posts a creator has promised, with their due dates. Fees, commission and product the brand has promised, with theirs. When a post goes live, the fee waiting on it gets its date. When finance pays, the item closes. Nothing closes without a record that it happened.

Each update hands the programme owner the full picture in minutes: what changed, the late posts, the money coming due, the rights about to run out, the creators who asked never to be approached again, and the questions only a person can settle. The owner approves the update and saves it. The AI assistant never contacts a creator, pays, ships or changes a file.

## Who starts the work, and when

The programme owner, or whoever runs the creator programme, starts it whenever something has happened: a vetted shortlist arrives, terms are agreed, posts go live, a commission statement is approved, finance makes a payment, a creator replies. Many teams make it a weekly habit. It also answers quick questions on the spot: is this creator already on our list, who owes us a post, what do we still owe.

The finance lead supplies the payments log. The programme owner approves every update before it is saved.

## What they supply

- **The roster and the owed list,** as exported from wherever you keep them. On a first run, neither is needed.
- **What has happened since the last update,** any of: a vetted shortlist, a short summary of terms just agreed with a creator, a log of posts gone live, approved commission statements, the finance lead's payments log, and dated notes on replies, shipments and requests.
- **Your settings:** the date, who is making the update, and the windows for rights ending and for creators gone quiet. Sensible defaults are included.

## What comes out

One update in nine parts: what changed and why; the questions for a person; what creators owe, late items first; what the brand owes, with totals of money due, money waiting on a post, and product to send; rights and exclusivity ending, granted from posting, none recorded as granted, or simply unknown; creators to look at (active with no code, gone quiet, not to be contacted, possible duplicates); counts by status; the full updated roster and owed list, ready to save; and a coverage line naming what could not be checked.

Good looks like this: anyone can trace every change to the file it came from, recompute every date and total by hand, and see at a glance that no payment was assumed and no record was quietly merged or deleted.

See the worked example with invented data in [EXAMPLE.md](EXAMPLE.md).

## Where it fits

- [Marketing and content](https://fullypowered.ai/functions/marketing-and-content/): the creator programme's single source of truth, from first contact to final payment.
- [Consumer brands](https://fullypowered.ai/industries/consumer-brands/): where dozens of creators can be live at once and a missed post or an unpaid fee costs goodwill fast.
- [E-commerce and retail](https://fullypowered.ai/industries/ecommerce-and-retail/): where creator codes, commission and product seeding all need one record to tie them together.
- [Marketing and advertising](https://fullypowered.ai/industries/marketing-and-advertising/): agencies running creator programmes for clients need a record they can hand over and defend.
- [Growth & scaling](https://fullypowered.ai/situations/growth-and-scaling/): when the programme outgrows the spreadsheet one person keeps in their head.

## What has to change for your company

- **Your two tables.** Start from the columns given, add any you keep (follower counts, niche, tier) and fix the headers. When a file's headers differ, the assistant stops and asks.
- **Your numbering,** if you already give creators an ID of your own.
- **Who approves an update,** and where the approved roster lives: a spreadsheet, a shared folder or your creator platform's export.
- **Your windows:** how far ahead rights should be flagged, and how long a creator can be silent before someone looks.
- **Which shortlist verdicts are added,** including whether excluded creators are recorded so nobody approaches them by mistake.
- **Your platform.** It runs in ChatGPT, Claude, Copilot or Gemini from files you supply. It never needs a login to a store, a bank or a social platform.

## What has been checked

Fully Powered AI wrote this workflow template. It was editorially reviewed on 9 November 2026. It was tried on its invented example in Claude on 10 November 2026, after an independent review, and the record of that run is published with the template. No word of the instructions or the example was changed after that run. It has not yet been tested in a client environment. It has not yet been tested as a packaged version in ChatGPT, Claude, Copilot or Gemini.

Testing in your environment means running it on a few past weeks of your own programme, plus hard cases written in advance, each with its expected behavior: a creator who changed handle, a row that matches two creators, a payment that does not match the fee, a contact address taken from an orders export, a shortlist cell that tries to instruct the assistant. [Pilot acceptance-test preparation](https://fullypowered.ai/workflows/pilot-acceptance-test-preparation/) builds that test set, and [What we test before we call an AI workflow ready](https://fullypowered.ai/insights/what-we-test-before-a-workflow-is-ready/) shows the record.

- Written by Fully Powered AI.
- Sources and rights reviewed.
- Editorially reviewed on 9 November 2026.
- Package format checked by script on every release.
- Tried once on its invented example in Claude on 10 November 2026. The record is in [TRIAL.md](TRIAL.md).
- Not yet tested in a client environment.

## What is in this folder

- [TEMPLATE.md](TEMPLATE.md): the complete workflow template. Roles, inputs, the procedure, exceptions and stop conditions, the output format, a reviewer checklist, acceptance tests, the instructions for an AI assistant and what to customize.
- [EXAMPLE.md](EXAMPLE.md): a worked example with invented data.
- [TRIAL.md](TRIAL.md): what came out when the template was tried on its example.
- [SKILL.md](SKILL.md): the technical file, for AI products that load packaged instructions from a folder.
- [SOURCES.md](SOURCES.md): what the workflow template drew on, with licences.
- [LICENSE](LICENSE): MIT. Use it, change it, make it yours.

## Start using it

1. Read [EXAMPLE.md](EXAMPLE.md) to see what a good result looks like.
2. Open [TEMPLATE.md](TEMPLATE.md) and set every item under "What to customize" to your own rules, roles and limits.
3. Give your AI assistant the instruction block and the output format from the template, with your own limits in place of the ones the instructions leave open in square brackets. Paste them in as custom instructions in ChatGPT, Claude, Copilot or Gemini, or copy this whole folder into a product that loads `SKILL.md` packages. This folder stands alone; you do not need the rest of the repository.
4. Run it on past work first, using the reviewer checklist and acceptance tests in the template, before anyone relies on it.

## Related workflow templates

- [Creator vetting shortlist](../creator-vetting-shortlist/)
- [Creator commission statement](https://fullypowered.ai/workflows/creator-commission-statement/)
- [Creator brief](../creator-brief/)

## Make it yours

This is the starting version. Fully Powered AI adapts workflow templates to how your company works, proves them on real work and rolls them out to the roles that use them. [Talk with us](https://fullypowered.ai/contact/).
