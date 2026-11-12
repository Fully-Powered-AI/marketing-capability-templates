# Creator vetting shortlist

Before anyone contacts a creator, the program lead sees every name on the longlist scored on six lines, each backed by what was seen and when: audience fit, engagement quality, authenticity, brand safety, sponsored track record and contactability. A person chooses who to approach.

*Workflow template · Marketing and content · version 0.1.0 · [Workflows Directory](https://fullypowered.ai/workflows/creator-vetting-shortlist/)*

## The outcome

Your longlist becomes a dated shortlist you can defend. Every creator carries six scores, and every score carries the evidence behind it: what was seen, on which page, on which day. The engagement rate is worked out from the creator's own recent posts, with the working shown, so nobody has to trust a media kit or a round number in a pitch.

Each creator ends with a verdict: engage, negotiate, skip or exclude, with the rule that decided it. A creator worth approaching but with something to settle first, such as thin evidence or a question about your brand rules, is marked negotiate with exactly what to settle. Anything your rules forbid excludes the creator outright, whatever the rest of the scores say.

The shortlist proposes; your program lead confirms every score and chooses who is approached. No creator is contacted, followed or added to any list by the AI assistant.

## Who starts the work, and when

The program lead, or whoever runs your creator partnerships, starts it once there is a longlist and before any first message is drafted. It runs again for a creator on a new date when the evidence was thin or their content has changed.

The brand's owner answers any question the shortlist raises about the brand rules. The program lead approves the shortlist.

## What they supply

- **Your brand rules.** Who the brand is for, a ruling for each platform, your content policy, your redlines and your competitor categories, written by the owner.
- **The longlist.** Each creator's handle, platform, follower count and where that count came from.
- **Recent posts.** For each creator, the likes, comments, shares and views shown on their recent public posts, and the day those counts were read.
- **Evidence notes.** What your team saw on each creator's public pages, with the date: the bio, what commenters say, three months of posts, paid partnerships and the contact route. Where your AI product can read public web pages and you allow it, the assistant can gather these itself.
- **Your settings.** The date of the run and your own starting engagement bands; the rest has sensible defaults you can change.

## What comes out

One shortlist in four parts:

1. **The shortlist,** one line per creator: verdict, total out of 30, confidence, brand-safety flag, tier and engagement rate.
2. **Creator by creator,** the six scores with their evidence, the engagement working, the confidence checks and the rule behind the verdict.
3. **For your decision:** who is proposed for approach and what to settle first, the questions for the owner, and who is not approached now and why.
4. **Coverage:** what was used, what was missing, what could not be judged, and any warnings.

Good looks like this: anyone on the team can recompute every rate from the posts listed, and every score points to something a person could go and look at.

See the worked example with invented data in [EXAMPLE.md](EXAMPLE.md).

## Where it fits

- [Marketing and content](https://fullypowered.ai/functions/marketing-and-content/): choosing the creators who carry the brand to new audiences.
- [Consumer brands](https://fullypowered.ai/industries/consumer-brands/): where creators often sell more than advertising does, and one wrong partner travels fast.
- [Marketing and advertising](https://fullypowered.ai/industries/marketing-and-advertising/): agencies vetting creators for several brands need one method they can show each client.
- [Growth & scaling](https://fullypowered.ai/situations/growth-and-scaling/): when a creator program grows past the few names the founder knows personally.

## What has to change for your company

- **Your brand rules.** Decide who writes them and how a ruling is recorded. The shortlist applies them exactly as written and asks the owner whenever they are silent.
- **Your starting bands.** Set the engagement range you expect for each size of creator, then replace it with your own figures once you have vetted enough creators.
- **Your verdict lines.** Decide the totals that mean engage and negotiate, the brand-safety score that excludes, and the authenticity floor.
- **Your exports.** Agree the columns of your longlist and posts files. When a file's columns differ, the assistant stops and asks.
- **Who confirms.** Name who confirms the scores and who approves the shortlist.
- **Your platform.** It is written for ChatGPT, Claude, Copilot or Gemini, and works from files you supply and public pages only. It never needs a login to any platform.

## What has been checked

Fully Powered AI wrote this workflow template. It was editorially reviewed on 9 November 2026. It was tried on its invented example on 9 November 2026 in two runs; the record of the second is published with it, and summarizes the first and the changes made after it. It has not yet been tested in a client environment. It has not yet been tested as a packaged version in ChatGPT, Claude, Copilot or Gemini.

Testing in your environment means running it on creators your team has already vetted by hand, plus hard cases written in advance, each with its expected behavior: a private account, a creator whose only figures come from a media kit, a post that crosses one of your redlines, the same accounts leaving the same praise on every post, a bio that tries to instruct the assistant. [Pilot acceptance-test preparation](https://fullypowered.ai/workflows/pilot-acceptance-test-preparation/) builds that test set, and [What we test before we call an AI workflow ready](https://fullypowered.ai/insights/what-we-test-before-a-workflow-is-ready/) shows the record.

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

- [Creator brief](../creator-brief/)
- [Creator commission statement](https://fullypowered.ai/workflows/creator-commission-statement/)
- [Competitor profile from public pages](../competitor-profile-from-public-pages/)
- [Brand strategy workshop](../brand-strategy-workshop/)
- [Cold outreach sequence drafting](https://fullypowered.ai/workflows/cold-outreach-sequence-drafting/)

## Make it yours

This is the starting version. Fully Powered AI adapts workflow templates to how your company works, proves them on real work and rolls them out to the roles that use them. [Talk with us](https://fullypowered.ai/contact/).
