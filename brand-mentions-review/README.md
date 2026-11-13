# Brand mentions and conversations review

Your social media manager gets a dated digest of the week's collected mentions: customer questions, other talk about the brand, competitor references, category talk and irrelevant matches, each kept apart, with the mentions that need a reply listed oldest first and an owner beside each. It posts and replies to nothing.

*Workflow template · Marketing and content · version 0.1.0 · [Workflows Directory](https://fullypowered.ai/workflows/brand-mentions-review/)*

## The outcome

The pile of mentions your listening tool or saved searches collected becomes one page you can act on. Every mention is read and lands in exactly one place, so nothing is lost and nothing is counted twice. Posts that need a person today, such as someone saying the product hurt them or a scam using your name, sit at the top with who decides.

Below that is the reply list: every customer question and every open "which one should I buy?" thread in your category, oldest first, with its age, its link and a suggested owner. Replies left open last week come forward until someone marks them done. Competitor references are grouped by competitor and category talk by topic, with the questions several people asked kept as research questions.

Namesakes, spam and the brand's own posts are set aside with their reasons. Each mention is shown in its author's own words, with no sentiment score and no share-of-voice figure, because the digest covers only what was collected.

## Who starts the work, and when

The social media manager or community manager runs it once a week, after a launch or campaign, or whenever mentions have piled up. They supply the export and the brand's terms. The social media manager or the brand manager reads the digest and decides what is answered and by whom. Problems with an order go to the support lead; the brand manager decides whether to join an open category thread and handles anything that needs a person now.

## What they supply

- **The mention export.** One row per mention from your listening tool or saved searches, with an ID, the date, the platform, the author, the link and the text. The template lists the default column headers; a header that does not match stops the work until someone says what the column holds.
- **Your brand terms.** Brand and product names, short forms, misspellings and your accounts, plus any namesakes and the words that give them away.
- **The competitor list** and **the topic scope:** the category topics you want to hear about and the ones you do not.
- **The settings:** the period, who reads the digest, your reply window and who owns each kind of reply.
- **Last week's digest and the handled list,** so finished replies drop off and open ones come forward.

## What comes out

One digest in a fixed order:

1. **Needs a person now,** with the matter and who decides.
2. **Needs a reply,** oldest first, with the kind of reply, the suggested owner and the age, then what is already handled.
3. **Customer questions** and **other brand talk.**
4. **Competitor references** by competitor, and **category talk** by topic, with the questions asked by two or more people.
5. **Irrelevant** matches with their reason, and **not placed** mentions with the question that would settle each.
6. **Set aside:** posts outside the period, your own posts and repeats.
7. **A count line that adds up** and a coverage line saying what the digest does not cover.

Good looks like this: you can find every row of the export on the page exactly once, and you know before lunch which replies are overdue and whose they are.

See the worked example with invented data in [EXAMPLE.md](EXAMPLE.md).

## Where it fits

- [Marketing and content](https://fullypowered.ai/functions/marketing-and-content/), where the social team needs to know which conversations deserve attention this week.
- [Consumer brands](https://fullypowered.ai/industries/consumer-brands/), where buyers ask about products, orders and spare parts in public, and a namesake can swamp a saved search.
- [Software technology](https://fullypowered.ai/industries/software-technology/), where setup questions and comparisons with rival tools turn up in forums before they reach support.
- [Hospitality](https://fullypowered.ai/industries/hospitality/), where a question about a booking or a stay can sit unanswered on a public page.
- [Marketing and advertising](https://fullypowered.ai/industries/marketing-and-advertising/), where an agency hands each client one dated digest of the client's own mentions.
- [Growth & scaling](https://fullypowered.ai/situations/growth-and-scaling/), when mentions arrive faster than one person can read them.

## What has to change for your company

- **Your terms.** Brand and product names, misspellings, accounts and namesakes; the better this list, the fewer mentions end up unsure.
- **Your topics and competitors,** including the topics you do not want to hear about.
- **Your reply window** and who owns each kind of reply: product questions, order problems, open category threads.
- **What needs a person now,** and who decides each matter, such as whoever handles product safety or press.
- **Your columns.** Any export works if you say which column is which.
- **Your platform.** It runs in ChatGPT, Claude, Copilot or Gemini, from the files you paste or attach; it needs no connection to your social accounts or listening tool.

## What has been checked

Fully Powered AI wrote this workflow template from its own published map of marketing work. It was editorially reviewed on 11 November 2026. It was tried once on its invented example in Claude on 11 November 2026, and the record is published with it; wording clarifications made after that trial were not re-run. It has not yet been tested in a client environment, and has not yet been tested as a packaged version in ChatGPT, Claude, Copilot or Gemini.

Testing in your environment means running it on a past week your social media manager remembers well, plus hard cases written in advance: an export whose columns have other names, a namesake, a post that could mean either, the same post twice, a report of an injury. The social media manager checks every count and every age before relying on the digest. [Pilot acceptance-test preparation](https://fullypowered.ai/workflows/pilot-acceptance-test-preparation/) sets those cases up, and [what we test before we call an AI workflow ready](https://fullypowered.ai/insights/what-we-test-before-a-workflow-is-ready/) describes the record we keep.

- Written by Fully Powered AI.
- Sources and rights reviewed.
- Editorially reviewed on 11 November 2026.
- Package format checked by script on every release.
- Tried once on its invented example in Claude on 11 November 2026. The record is in [TRIAL.md](TRIAL.md).
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

- [Competitor profile from public pages](../competitor-profile-from-public-pages/)
- [Customer feedback themes](https://fullypowered.ai/workflows/customer-feedback-themes/)
- [Customer reply drafting](https://fullypowered.ai/workflows/customer-reply-drafting/)

## Make it yours

This is the starting version. Fully Powered AI adapts workflow templates to how your company works, proves them on real work and rolls them out to the roles that use them. [Talk with us](https://fullypowered.ai/contact/).
