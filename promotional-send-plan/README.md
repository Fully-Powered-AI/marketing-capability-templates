# Promotional send plan

Before a promotion goes out, the marketing lead gets one send plan across email and text: who can receive it under your own consent records, every send in order with its time, what it says and links to, the suppression lists applied, and what must be approved before the first send. Nothing is sent.

*Workflow template · Marketing and content · version 0.1.0 · [Workflows Directory](https://fullypowered.ai/workflows/promotional-send-plan/)*

## The outcome

A sale runs for five days, and the customers who hear about it should hear the right amount: one email when it opens, perhaps a text, a reminder for anyone who has not bought yet, and never more in one day than your rules allow. This plan puts the whole promotion on one page before anything is built in a sending tool.

The marketing lead sees every email and text in date order, with its time, the segments it goes to, the two or three points it makes, the offer facts behind each point and its tracked link. Beside the calendar sits the audience, counted channel by channel: who can receive, who is suppressed and on which list, who is excluded by their own consent status, and who is held back because their record says something your rules do not cover. Consent comes only from the records you supply. A blank is never read as a yes, and a purchase is never read as permission to text.

The plan then checks the things that go wrong in a busy week: a text set for after your window closes, an email and a text landing on the same person on the same day, a loyal customer who would get four messages when your limit is three, a request to say "only a few left" when no stock fact exists. Each one becomes a decision for the marketing lead or a question for the person who can answer it. It ends with what must be signed off before the first send, and by whom. The workflow template sends nothing, schedules nothing, loads no list and changes no record.

## Who starts the work, and when

The marketing lead, or a marketer for them, starts it once the offer is approved and before anyone builds a send. The person who keeps the contact records answers questions about what a record shows. The person your company names to own its sending rules answers what a consent status or a list means. The offer owner, often the e-commerce manager, confirms the offer facts and the sale page. Run it again when the offer, the dates or an export changes.

## What they supply

- **The promotion brief.** The offer in its approved wording, with dates, any code and exclusions; the link; the segments; the sends you have in mind, each with its channel, day, time and purpose; the time zone, or every zone your customers are in.
- **Your sending rules.** Which consent statuses permit promotional email and which permit texts, plus your windows, how many sends one person may receive in a day and in a promotion, what each suppression list covers, and who sends each channel. Where a setting is missing, the plan uses a stated default and asks about it.
- **The contact export,** one row per contact, with segment, whether an email address and a mobile number are on file, and the email and text consent statuses. No addresses or phone numbers are needed.
- **The suppression lists:** unsubscribes, opt-outs, bounces, complaints, staff and test contacts, in one file.

## What comes out

One plan in a fixed order: the plan in brief, the settings used and where each came from, the numbered offer facts, the audience for email and for text with every count reconciled, any records that disagree, the send calendar, the sends each person would receive, the open questions with who answers each, the decisions for the marketing lead, the sign-offs needed before the first send, and what the plan could not judge. Each send carries a brief for the copywriter, not finished copy. Where a section is empty it says so. The last line is a blank approval for the marketing lead.

See the worked example with invented data in [EXAMPLE.md](EXAMPLE.md).

## Where it fits

- [Marketing and content](https://fullypowered.ai/functions/marketing-and-content/), where one promotion has to read as one plan across every email and text the team sends.
- [Advertising and lead generation](https://fullypowered.ai/functions/advertising-and-lead-generation/), where paid campaigns point at the same offer and the owned sends need the same dates and facts.
- [E-commerce and retail](https://fullypowered.ai/industries/ecommerce-and-retail/), where a sale weekend reaches past buyers and newsletter readers through two channels at once.
- [Consumer brands](https://fullypowered.ai/industries/consumer-brands/), where loyalty members, online buyers and newsletter readers each carry their own consent history.
- [Hospitality](https://fullypowered.ai/industries/hospitality/), where a seasonal menu or a midweek offer goes to guests who asked to hear about them.
- [Marketing and advertising](https://fullypowered.ai/industries/marketing-and-advertising/), where an agency lays out a client's promotion for the client to approve.
- [Growth & scaling](https://fullypowered.ai/situations/growth-and-scaling/), when promotions multiply and nobody is counting how often each customer hears from you.
- [Established businesses](https://fullypowered.ai/situations/established-businesses/), when years of sign-up forms have left consent statuses and lists in several shapes.

It does not write the copy: welcome and nurture emails are [email sequence drafting](https://fullypowered.ai/workflows/email-sequence-drafting/), and a text-only campaign drafted word by word is [promotional text campaign plan](https://fullypowered.ai/workflows/promotional-text-campaign-plan/). A full record-by-record review of a doubtful list is [campaign audience check](https://fullypowered.ai/workflows/campaign-audience-check/).

## What has to change for your company

Write your sending rules down if they are not already: which consent statuses permit promotional email and texts, which exclude a person, your sending windows, your limits per day and per promotion, what each suppression list covers, and who sends each channel. Your rules owner and your own advisers set those rules; the workflow template applies the ones you give it and takes no view on what any law or carrier requires. Map the columns your customer or sending tool exports to the defaults once. Agree who confirms the offer facts, who writes the copy from each send's brief, and who signs each item before the first send.

## What has been checked

Fully Powered AI wrote this workflow template. It was editorially reviewed on 12 November 2026. It was tried on its invented example on 12 November 2026 in Claude; the record is published with it. The template was revised after that trial, and the revised version has so far been run again only by the session that revised it, not independently. It has not yet been tested in a client environment, or as a packaged version in ChatGPT, Claude, Copilot or Gemini.

Testing in your environment means running it on a past promotion whose problems you already know: a status your rules do not name, a contact on the opt-out list whose record still says opted in, a text scheduled after your window, a customer who would hear from you too often. The person who keeps the contact records recomputes every count before the plan is relied on. [Pilot acceptance-test preparation](https://fullypowered.ai/workflows/pilot-acceptance-test-preparation/) builds that test set, and [What we test before we call an AI workflow ready](https://fullypowered.ai/insights/what-we-test-before-a-workflow-is-ready/) shows the record.

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

- [Email sequence drafting](../email-sequence-drafting/)
- [Promotional text campaign plan](https://fullypowered.ai/workflows/promotional-text-campaign-plan/)
- [Campaign audience check](https://fullypowered.ai/workflows/campaign-audience-check/)

## Make it yours

This is the starting version. Fully Powered AI adapts workflow templates to how your company works, proves them on real work and rolls them out to the roles that use them. [Talk with us](https://fullypowered.ai/contact/).
