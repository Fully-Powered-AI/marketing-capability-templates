# Text-message opt-in check

Before a text campaign goes out, the marketing lead sees every number on the proposed list beside the opt-in your own records hold for it: where it was given, when, and the wording as recorded. Anyone with no recorded opt-in, or with a recorded opt-out, is held out and counted. A person decides who is sent to.

*Workflow template · Marketing and content · version 0.1.0 · [Workflows Directory](https://fullypowered.ai/workflows/text-message-opt-in-check/)*

## The outcome

A list for a text campaign usually comes from one place and the opt-ins from another: the online shop, the counter tablet, a keyword someone texted, a list that arrived with an acquired business. This check brings them together, one number at a time. Every recipient on the list sits on one line beside what your records actually say about that number: the date of the opt-in, where it was given, and the exact wording the person saw, printed as it was recorded.

Anyone the records do not support is held out in plain view, in three groups: a recorded opt-out, no recorded opt-in, or a number that could not be matched. Each group is counted, and the counts add up to the list. An opt-out recorded in the texting tool but missing from the consent records, an opt-in that came after an opt-out, a number written without its country code, a name that no longer matches: each becomes a point with the question to ask and who answers it.

The marketing lead or owner decides who is sent to. The workflow template states no legal rule and gives no view on whether any opt-in is enough for the campaign; a legal question goes to your counsel. It sends nothing, removes nobody from any tool and changes no record.

## Who starts the work, and when

The marketing lead or owner, or a marketer for them, starts it once a list for a promotional text has been put together and before it goes near the texting tool. The person who keeps the consent records answers questions about them, and the person who built the list answers questions about the list. Run it again when the list or the records change, and on the day of the send if the records were taken some days before.

## What they supply

- **Check details.** The campaign name, the planned send date, the date the consent records were taken, the words your records use for an opt-in and an opt-out, who built the list and who keeps the consent records.
- **The proposed send list,** one row per recipient, with an ID, a name and a phone number.
- **Your consent records,** one row per opt-in or opt-out, with the number, the date, the source and the wording as recorded.
- **The opt-out export from your texting tool,** if it keeps its own list of people who replied STOP.

## What comes out

One check in a fixed order: the result in brief, the settings used, the counts reconciled from the list rows to the four groups, each group line by line, every wording exactly as recorded, the numbered points for the owner, and what the check did not judge. Phone numbers appear only by their last four digits. Where a group is empty it says so. It ends with a blank line for the owner's decision.

See the worked example with invented data in [EXAMPLE.md](EXAMPLE.md).

## Where it fits

- [Marketing and content](https://fullypowered.ai/functions/marketing-and-content/), where the team planning a text campaign wants to know that every number on the list asked to hear from it.
- [E-commerce and retail](https://fullypowered.ai/industries/ecommerce-and-retail/), where a segment pulled from the store's customers is checked against the opt-ins taken at checkout and in store.
- [Hospitality](https://fullypowered.ai/industries/hospitality/), where guests who joined at the counter, at booking or by texting a keyword end up on one list.
- [Consumer brands](https://fullypowered.ai/industries/consumer-brands/), where opt-ins arrive from the online shop, events and pop-ups, each recorded in its own way.
- [Marketing and advertising](https://fullypowered.ai/industries/marketing-and-advertising/), where an agency checks a client's list against the client's own consent records before the client decides.
- [Growth & scaling](https://fullypowered.ai/situations/growth-and-scaling/), when texting grows from a few loyal customers to lists nobody has read line by line.
- [Established businesses](https://fullypowered.ai/situations/established-businesses/), when years of sign-up forms have left opt-ins with several sources and wordings.
- [Acquisitions & integration](https://fullypowered.ai/situations/acquisitions-and-integration/), when a list comes with an acquired business and its consent records sit in another system.

It does not plan the campaign or draft the messages. The [promotional text campaign plan](https://fullypowered.ai/workflows/promotional-text-campaign-plan/) does that, and it sorts the audience by the consent statuses your policy names; this check instead sets each number beside the raw opt-in records, with source, date and wording as recorded. It does not build a send plan across email and text ([promotional send plan](https://fullypowered.ai/workflows/promotional-send-plan/)), check an email audience ([campaign audience check](https://fullypowered.ai/workflows/campaign-audience-check/)) or write emails ([email sequence drafting](https://fullypowered.ai/workflows/email-sequence-drafting/)). It starts with a proposed list and ends with that list checked, number by number. It does not read a wording against the campaign: each wording is printed as recorded, and whether it fits this campaign is for the reader to read and the owner to decide.

## What has to change for your company

Write down the words your consent records use for an opt-in and an opt-out, and map the columns your shop, customer system or texting tool exports to the defaults once. Store numbers with their country code, or expect those rows to be held out until someone fixes them. Name who keeps the consent records, who builds lists, who decides who is sent to, and who removes held-out recipients and presses send. Decide where legal questions go: your in-house counsel, or the outside counsel you use.

## What has been checked

Fully Powered AI wrote this workflow template. It was editorially reviewed on 12 November 2026. It was tried on its invented example on 12 November 2026 in Claude; the record is published with it. It has not yet been tested in a client environment. It has not yet been tested as a packaged version in ChatGPT, Claude, Copilot or Gemini.

Testing in your environment means running it on a past list whose problems you already know: a number that opted out in the texting tool only, an opt-in after an opt-out, a number without its country code, a sign-up with no wording recorded. The person who keeps the consent records checks every line and recomputes every count before the check is relied on. [Pilot acceptance-test preparation](https://fullypowered.ai/workflows/pilot-acceptance-test-preparation/) builds that test set, and [What we test before we call an AI workflow ready](https://fullypowered.ai/insights/what-we-test-before-a-workflow-is-ready/) shows the record.

- Written by Fully Powered AI.
- Sources and rights reviewed.
- Editorially reviewed on 12 November 2026.
- Package format checked by script on every release.
- Tried once on its invented example in Claude on 12 November 2026. The record is in [TRIAL.md](TRIAL.md).
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

- [Promotional text campaign plan](https://fullypowered.ai/workflows/promotional-text-campaign-plan/)
- [Promotional send plan](../promotional-send-plan/)
- [Campaign audience check](https://fullypowered.ai/workflows/campaign-audience-check/)
- [Email sequence drafting](../email-sequence-drafting/)

## Make it yours

This is the starting version. Fully Powered AI adapts workflow templates to how your company works, proves them on real work and rolls them out to the roles that use them. [Talk with us](https://fullypowered.ai/contact/).
