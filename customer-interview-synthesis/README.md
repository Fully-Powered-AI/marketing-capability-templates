# Customer interview synthesis

Turn a stack of customer call notes into the answer to one question, in your customers’ own words. Every quotation is cited to the note it came from, every theme shows its confidence and the evidence against it, and nothing is claimed that the notes do not say.

*Capability template · Marketing and content · version 0.1.0 · [Capabilities Directory](https://fullypowered.ai/capabilities/customer-interview-synthesis/)*

## The outcome

You finish a round of customer calls and, the same afternoon, hold a synthesis you can defend line by line. It opens with the question you asked and the answer the notes give. Under it sit the themes, each written as a claim a customer could dispute, each carried by exact quotations with the note, the date, the speaker’s role and whether the words came unprompted.

It is built to prove you wrong when you are wrong. You write down what you believe, and what would change your mind, before the notes are read. The synthesis then reports the evidence against each theme beside the evidence for it. A founder, a marketer and a product lead can read the same page and argue about the decision, because the evidence is settled.

## Who starts the work, and when

A founder, marketer or product lead who holds the notes starts it: after a round of customer or prospect calls, before a positioning or messaging change, or before committing to a new product or service line. Someone who was on the calls checks the quotations against the notes. The person who owns the decision reads the synthesis and decides.

The capability reads what you already have. It contacts no customer, books no call and sends nothing.

## What they supply

- **The question.** One sentence your customers’ words could answer or overturn, and the decision it informs.
- **Your facts.** A few lines: what you sell, who the customers are, what you believe they would say today, and the bar for calling that belief wrong.
- **The notes.** Call notes or transcripts, each labelled with its date, the speaker’s role, the kind of business and which notes come from the same business.
- **Permission.** For each speaker: may be named, may be quoted without a name, or not for use. Anyone who was not asked counts as not for use. Not for use means not outside the company; inside this document such words are quoted and marked.

## What comes out

One internal document in a fixed order:

1.  **The question, the belief and the bar,** as you wrote them before the notes were read.
2.  **In short.** The answer in one sentence with its confidence, whether the bar for calling the belief wrong was reached, condition by condition, and whether the belief is supported, disputed or not settled.
3.  **Coverage.** How many notes were supplied and read, how many independent sources they amount to, and anything that could not be read.
4.  **Themes.** Each with the customers’ exact words and their citations, the evidence against it, and a confidence level with the rule that set it.
5.  **Their words.** The phrases customers use for the problem and for what they want, ready for whoever writes next, each with its permission.
6.  **What else they tried, leads and what is still unknown.** A lead is a theme too thin to be a finding, kept apart and labelled.

Good looks like this: anyone can pick a sentence, open the cited note and find the words there, unchanged.

See the worked example with invented data in [EXAMPLE.md](EXAMPLE.md).

## Where it fits

- [Marketing and content](https://fullypowered.ai/functions/marketing-and-content/): positioning and copy start from what customers say, in the words they use.
- [Product management](https://fullypowered.ai/functions/product-management/): a product bet is checked against customers’ accounts of the last time the problem happened.
- [Software technology](https://fullypowered.ai/industries/software-technology/): discovery calls, win and loss calls and customer conversations pile up faster than anyone reads them.
- [Professional services](https://fullypowered.ai/industries/professional-services/): client conversations show how buyers describe the work they need before a new service is named.
- [Consumer brands](https://fullypowered.ai/industries/consumer-brands/): customer conversations give the brand its customers’ vocabulary.
- [Marketing and advertising](https://fullypowered.ai/industries/marketing-and-advertising/): an agency brings a client evidence with a citation on every line.
- [New business lines](https://fullypowered.ai/situations/new-business-lines/): before you build a new line, find out whether customers describe the problem it solves.

## What has to change for your company

- **How notes are labelled.** A date, a role, a kind of business and a business reference on every note, and quotation marks around a customer’s exact words.
- **Your permission question.** The sentence you ask at the close of a call, and where the answers are recorded.
- **Your minimum.** How many independent sources a customer group needs before a theme counts as a finding. The template starts at five.
- **Who approves public use.** The role that confirms a customer’s permission before any of their words appear outside the company.
- **Your platform.** It runs in ChatGPT, Claude, Copilot or Gemini. Decide which notes the assistant may read and where the synthesis is kept.

## What has been checked

Fully Powered AI wrote this capability template. It was editorially reviewed on 9 November 2026. It has not yet been tested in a client environment. It has not yet been tested as a packaged version in ChatGPT, Claude, Copilot or Gemini.

Testing in your environment means running it on a round of notes someone on your team already knows well, plus hard cases written in advance: notes with no exact words, two speakers from one business, a belief the notes contradict. The person who was on the calls checks every quotation against its note. [Pilot acceptance-test preparation](https://fullypowered.ai/capabilities/pilot-acceptance-test-preparation/) sets those cases up, and [what we test before we call an AI workflow ready](https://fullypowered.ai/insights/what-we-test-before-a-workflow-is-ready/) describes the record we keep.

- Written by Fully Powered AI.
- Sources and rights reviewed.
- Editorially reviewed on 9 November 2026.
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

- [SOP exception capture](https://fullypowered.ai/capabilities/sop-exception-capture/)
- [Sales proposal preparation](https://fullypowered.ai/capabilities/sales-proposal-preparation/)
- [Pilot acceptance-test preparation](https://fullypowered.ai/capabilities/pilot-acceptance-test-preparation/)

## Make it yours

This is the starting version. Fully Powered AI adapts capabilities to how your company works, proves them on real work and rolls them out to the roles that use them. [Talk with us](https://fullypowered.ai/contact/).
