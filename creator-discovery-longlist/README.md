# Creator discovery longlist

Before anyone scores or contacts a creator, the brand marketer gets a dated longlist from public pages and the names the team supplied: where each creator posts, how they were found, where their follower count came from, whether they already talk about your category, and why they are on the list.

*Workflow template · Marketing and content · version 0.1.0 · [Workflows Directory](https://fullypowered.ai/workflow templates/creator-discovery-longlist/)*

## The outcome

Creator work starts from a list with its reasoning written down, instead of from whoever happened to surface in a quick search. Each creator on it says which search or which colleague found them, the follower count with the page and the day it was read, the public way to reach them, and one plain sentence on why they belong in this campaign.

Creators who already post about your product category, or already mention your brand, sit at the top, each with the dated post that shows it. "We could not see their posts" is never written as "they never post about it". Anyone your brand rules already rule out stays on the list, marked with the rule, so nobody has to rediscover the reason next quarter.

The longlist judges no one's quality. It is the list your vetting step scores, and the marketer chooses which names go forward. The AI assistant contacts no creator, logs in nowhere and adds no one to any list.

## Who starts the work, and when

The brand marketer, or whoever runs your creator partnerships, starts it when a campaign or program needs fresh names: a launch, a new market, "more like this creator", or an export from a creator database that needs sorting and sourcing. It is rerun on a new date for each campaign rather than reused, because follower counts, bios and handles drift.

The brand's owner answers any question about the brand rules. The marketer reads the list and picks the rows that go on to vetting.

## What they supply

- **The brief.** How many creators, which platforms, the topics they should cover, the markets and languages, and any creator to find more like.
- **Your brand rules.** Where creators may post about the product, your content policy, your redlines, and the competitor brands worth noting, decided by the owner.
- **Names you already have.** Creators someone on the team already follows, and an export from a creator database or a platform's creator marketplace if you have one.
- **Your roster,** if you keep one, so creators you already work with or have ruled out are recognised.
- **What is on public pages.** Where your AI product can read public web pages and you allow it, the assistant reads them. Otherwise it hands you the searches, you run them in your own browser or app, and paste back what you see.

## What comes out

One longlist in four parts:

1. **The longlist,** one block per creator: platform and handle, follower count with its label and date, topics, how they were found, whether they already talk about your category and the post that shows it, the public contact route, other accounts they link themselves, the reason they are on the list, any screen and anything to check.
2. **A table** in the column layout the vetting step reads, so nothing is retyped.
3. **For your decision:** possible duplicates, platform questions for the owner, platform conditions to meet, and who was screened and why.
4. **Coverage:** what was used, what could not be judged, names that could not be found, and export columns that were set aside.

Good looks like this: every follower count says where it came from, every "already talks about it" has a link a person can open, and the counts at the top match the rows below.

See the worked example with invented data in [EXAMPLE.md](EXAMPLE.md).

## Where it fits

- [Marketing and content](https://fullypowered.ai/functions/marketing-and-content/): finding the creators who can carry the brand to people it does not reach yet.
- [Consumer brands](https://fullypowered.ai/industries/consumer-brands/): where the right creator can introduce a product to an audience that already trusts them.
- [E-commerce and retail](https://fullypowered.ai/industries/ecommerce-and-retail/): online stores launching products that creators can show in use.
- [Marketing and advertising](https://fullypowered.ai/industries/marketing-and-advertising/): agencies sourcing creators for several brands want each list built and documented the same way.
- [Growth & scaling](https://fullypowered.ai/situations/growth-and-scaling/): when the creator program outgrows the handful of names the founder already follows.
- [Startups & new ventures](https://fullypowered.ai/situations/startups-and-new-ventures/): a young brand building its first creator list from nothing but public pages.

## What has to change for your company

- **Your brand rules.** Decide who writes them and how a platform ruling is recorded. The longlist applies them as written and asks the owner when they are silent.
- **Your word list.** Add your brand's common misspellings, your product names, your competitors, and the terms your creators really use. Review it every quarter.
- **Your defaults.** Set how many names to aim for and how far back to read each creator's posts.
- **Your export.** Agree the columns your creator database exports. When the columns differ, the assistant stops and asks.
- **Who decides.** Name who picks the rows for vetting and who answers questions about the brand rules.
- **Your platform.** It is written for ChatGPT, Claude, Copilot or Gemini, and works from public pages and the files you supply. It never needs a login to any platform.

## What has been checked

Fully Powered AI wrote this workflow template. It was editorially reviewed on 9 November 2026. It was tried on its invented example on 9 November 2026 in Claude, in two runs; the record of the second is published with it, and summarizes the first and the changes made after it, chiefly a plain rule for when a creator counts as already talking about your category, the change that let the example's counts reproduce. It also lists the small edits made after the second run and after an independent review, which have not been run again. It has not yet been tested in a client environment. It has not yet been tested as a packaged version in ChatGPT, Claude, Copilot or Gemini.

Testing in your environment means running it on a past campaign whose creators your team already found by hand, plus hard cases written in advance, each with its expected behavior: a private account, an export whose follower figure differs from the profile, two similar handles that may be one person, a post that crosses one of your redlines, a creator who may be under 18, a bio that tries to instruct the assistant. [Pilot acceptance-test preparation](https://fullypowered.ai/workflows/pilot-acceptance-test-preparation/) builds that test set, and [What we test before we call an AI workflow ready](https://fullypowered.ai/insights/what-we-test-before-a-workflow-is-ready/) shows the record.

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

- [Creator vetting shortlist](../creator-vetting-shortlist/)
- [Creator brief](../creator-brief/)
- [Competitor profile from public pages](../competitor-profile-from-public-pages/)

## Make it yours

This is the starting version. Fully Powered AI adapts workflow templates to how your company works, proves them on real work and rolls them out to the roles that use them. [Talk with us](https://fullypowered.ai/contact/).
