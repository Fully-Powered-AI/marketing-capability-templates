# Creator campaign performance report

When a creator campaign closes, the marketing lead gets one report built from the store's own orders: what each creator brought in and cost, every creator ranked under a metric set beforehand, and a proposed next step for each. Every number is labelled measured, supplied or estimated.

*Workflow template · Marketing and content · version 0.1.0 · [Workflows Directory](https://fullypowered.ai/workflows/creator-campaign-performance-report/)*

## The outcome

The question "which creators worked?" gets an answer you can check. Every creator in the campaign sits in one ranked table, including the ones with no orders, under the metric your team chose before anyone looked at the results. Beside each creator: tracked orders, net sales, new and repeat customers, what they cost once fees, gifted product and discounts are counted, and whether they pay back at your margins.

Every number says where it came from. Measured figures come from the store's orders export or from posts your team checked. Supplied figures came from a person, such as a fee, a gift or a screenshot of reach. Estimated figures were worked out, such as contribution at your margin band. Reach and likes are shown, kept apart, and never decide a ranking.

The report ends with a proposed next step for every creator, with its reason and the strongest alternative, and an empty column for the marketing lead's decision. It proposes; the marketing lead decides.

## Who starts the work, and when

The creator programme lead or a marketing coordinator starts it once a campaign's order window has closed, or once a month for an always-on programme. The marketing lead reads it and decides each creator's next step. The programme lead then records those decisions and talks to the creators.

## What they supply

- **The campaign settings.** The order window, the ranking metric and who set it, the point below which a read is too thin to judge, and, if you have them, a target cost per order and your margin band.
- **The creator list.** Each creator's deal, rate, codes, start date, and whether they were part of this campaign.
- **The orders export** from your store, covering the campaign and some earlier months, so new customers can be told from returning ones.
- **Where you have them:** the orders credited to tracked links, the fees and gifted product per creator, a log of the posts your team checked, and reach figures from creators' screenshots.

No connection to the store, the creator platform or any social account is needed, and none is asked for.

## What comes out

One report in a fixed order:

1. **The answer:** what worked, what you are asked to decide, and what limits the read.
2. **Campaign totals** and **every creator, ranked,** each figure with its label.
3. **What each creator cost,** part by part, and whether each pays back at both ends of your margin band.
4. **Excluded orders,** by rule: test orders, refunds, unpaid orders, a creator buying with their own code.
5. **Posts and disclosure,** with any removals and fixes, and **reported reach**, kept apart.
6. **The order check:** every order in the window placed exactly once, and the codes nobody on the list owns.
7. **Proposed next steps,** the **next-cycle notes** and **coverage:** what was used, what was missing, and what the report could not see.

Good looks like this: anyone on the team can recompute a creator's figures from the order numbers on the page, and nobody has to take a screenshot's word for anything.

See the worked example with invented data in [EXAMPLE.md](EXAMPLE.md).

## Where it fits

- [Marketing and content](https://fullypowered.ai/functions/marketing-and-content/), which runs the creator programme and decides who to work with again.
- [Analytics and reporting](https://fullypowered.ai/functions/analytics-and-reporting/), which wants one set of definitions behind every campaign figure.
- [Consumer brands](https://fullypowered.ai/industries/consumer-brands/), where creator programmes are a common way to reach new customers.
- [E-commerce and retail](https://fullypowered.ai/industries/ecommerce-and-retail/), where creator codes and links turn into orders a store can count.
- [Growth & scaling](https://fullypowered.ai/situations/growth-and-scaling/), when a few creators become dozens and gut feel no longer tells you who is working.

## What has to change for your company

- **Your metric.** Decide who sets the ranking metric and how it is recorded before each campaign, and the point below which a read is too thin to act on.
- **Your numbers.** Set your target cost per order, your margin band, your refund window and your default commission rate.
- **Your files.** The column names your store, creator list and logs use, if they differ from the defaults. When a file's columns do not match, the assistant stops and asks.
- **Your roles.** Who runs it, who decides each creator's next step, and who records the decision and talks to creators.
- **Your platform.** It is written for ChatGPT, Claude, Copilot or Gemini and works from files you supply. Decide which exports the assistant may read.

## What has been checked

Fully Powered AI wrote this workflow template. It was editorially reviewed on 9 November 2026. It was tried on its invented example in Claude on 9 November 2026, and the record of that run is published with the template; it lists the edits made afterward that have not been run again. It has not yet been tested in a client environment. It has not yet been tested as a packaged version in ChatGPT, Claude, Copilot or Gemini.

Testing in your environment means running it on one or two past campaigns your team has already reviewed by hand, with hard cases written in advance: a creator with no orders, a refund that cancels an order's sales, an order carrying two creators' codes, a missing costs file, a screenshot passed off as a platform figure. Your programme lead checks every figure against the export before anyone relies on it. [Pilot acceptance-test preparation](https://fullypowered.ai/workflows/pilot-acceptance-test-preparation/) sets those cases up, and [what we test before we call an AI workflow ready](https://fullypowered.ai/insights/what-we-test-before-a-workflow-is-ready/) describes the record we keep.

- Written by Fully Powered AI.
- Sources and rights reviewed.
- Editorially reviewed on 9 November 2026.
- Package format checked by script on every release.
- Tried once on its invented example in Claude on 9 November 2026. The record is in [TRIAL.md](TRIAL.md).
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

- [Creator commission statement](https://fullypowered.ai/workflows/creator-commission-statement/)
- [Creator brief](../creator-brief/)
- [Creator vetting shortlist](../creator-vetting-shortlist/)

## Make it yours

This is the starting version. Fully Powered AI adapts workflow templates to how your company works, proves them on real work and rolls them out to the roles that use them. [Talk with us](https://fullypowered.ai/contact/).
