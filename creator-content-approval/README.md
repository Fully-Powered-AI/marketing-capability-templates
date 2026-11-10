# Creator content approval

A brand marketer gets a written go or no-go on a creator's draft before it goes live: every product statement checked against the brand's cleared list, the disclosure against the brand's own rules, and feedback the creator can act on without losing their voice. A person sends it.

*Capability template · Marketing and content · version 0.1.0 · [Capabilities Directory](https://fullypowered.ai/capabilities/creator-content-approval/)*

## The outcome

Every creator draft gets the same careful read, and the answer is on one page. The verdict comes first: go, go with changes, or no-go with the reason. Below it sit twelve checks in a fixed order, each with what was seen and where: the brief, the code and link, every statement about the product, the disclosure in the caption and in the video, the platform's own partnership label, the platform ruling, the audience, the redlines, and whether what the creator says happened to them holds up.

The creator gets feedback they can use straight away. Each change names the place, quotes what is there, says what is needed and why, and gives exact words only where the brand's own rules supply them. Their jokes, opinions, hook and look are left alone, because the brand sets guardrails and the creator makes the content.

Nothing slips through on a guess. A statement nobody has cleared goes to the person who clears statements as a question. Anything nobody could see, such as a video without a transcript, holds the verdict until someone supplies it. A forbidden statement is a no-go every time, never softened to a quick fix.

## Who starts the work, and when

The brand marketer, the content reviewer or the creator programme lead starts it when a creator sends a draft caption, video, audio or image post, and again when a revised version comes back. It also runs before a payment that depends on approved content, where the review is evidence for the person who decides the payment. The programme lead reads the review, settles the open questions with the right people and sends the feedback from the brand's own account.

## What they supply

- **Your creator rules:** the statements you have cleared, each marked with who cleared it and when; the forbidden statements with their reasons; the subjects where only cleared words may be used; your ruling on each platform; your disclosure wording, placement and spoken form for each platform, with the words that do not count on their own; your audience rule and redlines; and who clears statements, who sets the disclosure and who sends feedback.
- **The brief as sent** to this creator, with the product, deliverables, dates, code and link.
- **The draft exactly as the creator sent it:** the caption, a transcript for video or audio, and the file or notes from someone who watched it in full, with any covering note.
- **The request:** the campaign, creator, platform, format, product, who is running the review, the occasion and which attempt this is.

## What comes out

A review in a fixed order: the verdict and its reason, what was reviewed, the caption quoted in full, the twelve checks, every product statement with its class (cleared, reworded, forbidden or needs a ruling), the opinions left alone, and the reasons behind the verdict. Then the feedback for the creator, the questions for the people who clear statements and fetch inputs, the conditions to meet when posting, what was not judged, and a coverage list of what was used and what was missing. A revision gets the next attempt number and a check of every change asked for last time.

See the worked example with invented data in [EXAMPLE.md](EXAMPLE.md).

## Where it fits

- [Marketing and content](https://fullypowered.ai/functions/marketing-and-content/), which runs the creator programme and owns what the brand says in public.
- [Compliance, risk and privacy](https://fullypowered.ai/functions/compliance-risk-and-privacy/), which wants paid posts disclosed the brand's way and product statements kept to what has been cleared, with the decisions on each country's rules left to a person.
- [Consumer brands](https://fullypowered.ai/industries/consumer-brands/), where creators carry the product to new buyers and one loose health or product statement can travel a long way.
- [Growth & scaling](https://fullypowered.ai/situations/growth-and-scaling/), when drafts arrive faster than one person can read them all with the same care.

## What has to change for your company

Write down your cleared and forbidden statements and name the person who clears them; the capability adds none of its own. Decide the subjects where only cleared words will do, such as health effects or certifications. Set your disclosure wording, placement and spoken form for each platform, and how early in the caption it must appear. Disclosure rules differ from country to country, so a person at your company decides whether your wording fits each country your creators reach, taking advice where needed. Decide whether a caption-only fix may go live without a second review. Name who sends the feedback. It runs in ChatGPT, Claude, Copilot or Gemini from the text and files you supply, with no access to your social accounts or your store.

## What has been checked

Fully Powered AI wrote this capability template in its own words, from the content approval capability in its own Influencer Marketing set. It was editorially reviewed on 9 November 2026. It was tried on its invented example in Claude on 9 November 2026, and the record of that run is published with it. The run was not blind: the example's output had been seen before the run's own output was written. Small clarifications made after the run, listed in the record, have not been run again. It has not yet been tested in a client environment. It has not yet been tested as a packaged version in ChatGPT, Claude, Copilot or Gemini.

Testing in your environment means running it on past creator drafts your team remembers well, with hard cases written in advance: a forbidden statement tucked into a good post, a paraphrase of a cleared line, a disclosure at the end of the caption, a video with no transcript, a covering note that claims someone already approved it. The programme lead checks every verdict against the cleared list before any feedback is sent. [Pilot acceptance-test preparation](https://fullypowered.ai/capabilities/pilot-acceptance-test-preparation/) builds that test set, and [what we test before we call an AI workflow ready](https://fullypowered.ai/insights/what-we-test-before-a-workflow-is-ready/) describes the record we keep.

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

- [Creator brief](../creator-brief/)
- [Creator vetting shortlist](../creator-vetting-shortlist/)
- [Copy edit with a change list](../copy-edit-with-a-change-list/)

## Make it yours

This is the starting version. Fully Powered AI adapts capabilities to how your company works, proves them on real work and rolls them out to the roles that use them. [Talk with us](https://fullypowered.ai/contact/).
