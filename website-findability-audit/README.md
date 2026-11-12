# Website findability audit

An owner or marketer asking why the website is not found gets a plain report from saved copies of their own pages: what stops each page being reached, read or understood, the fixes in order, and the checks only a live look can settle. No ranking is promised.

*Workflow template · Marketing and content · version 0.1.0 · [Workflows Directory](https://fullypowered.ai/workflow templates/website-findability-audit/)*

## The outcome

You stop guessing about your website and start fixing the right things first. The report goes through each page you saved and asks three questions: can a search engine reach it, can a search engine or an AI assistant read it, and does a customer who arrives on it learn what you do, for whom and where. Every answer points to the exact tag or line in the file it came from, so your web designer can go straight to it.

What fails becomes a short list of fixes in order of consequence, with the ones that keep pages out of search at the top. A problem shared by several pages is one fix, not five. Each fix says who makes it and what you will see when it is done.

The report is honest about its edges. Anything the saved copies cannot settle, such as what a search engine has actually indexed or how the site behaves on a phone, sits in its own list with how to check it. It never states a ranking, a traffic figure or what an assistant will say about you: those decisions belong to the search engines and assistants, and no report can promise them.

## Who starts the work, and when

The owner, the marketing lead or whoever looks after the website starts it: when someone asks why the business does not show up, before a new site or a redesign goes live, after a change that may have broken something, or as a regular look at the pages that bring in customers.

That person saves the pages, writes a short note of the facts and reviews the report. The owner decides which fixes to make and settles every choice the report hands back, such as which crawlers the site lets in. The assistant reads what it is given and changes nothing.

## What they supply

- **Saved copies of your pages.** The homepage, your main service or product pages, the about page and the contact page, each with its address and the date you saved it. Viewing the page source in your browser and saving it as a text file is enough.
- **Two site files,** saved the same way: the robots file and the sitemap.
- **Your facts.** A short note in your own words: what you do, for whom and where, how to reach you, your hours, how pricing works, the next step you want a visitor to take, and any pages you keep out of search on purpose.
- **The questions customers ask,** in their words, from calls, emails or the contact form.
- **What prompted this,** if anything: a search you tried, or something a customer said, with the date.

## What comes out

One dated report, in a fixed order:

1. **In short,** in plain sentences, and a list of exactly what was read.
2. **Fixes, in order,** each with its severity, the pages, the evidence, the change, who makes it and how you will know it worked.
3. **Customer questions,** each marked answered, weak or missing, with where your facts already hold the answer.
4. **Page by page,** seventeen checks on each page, every one with its outcome.
5. **Facts to confirm,** where a page disagrees with your note or with another page, or states something customers rely on, such as a licence or how long the work takes, that your note does not mention.
6. **Choices that are yours,** such as a rule turning a named crawler away.
7. **Live checks still needed,** each with how a person checks it.

Good looks like this: your web designer can check any line against the saved file it names, and nothing in the report claims more than those files show.

See the worked example with invented data in [EXAMPLE.md](EXAMPLE.md).

## Where it fits

- [Marketing and content](https://fullypowered.ai/functions/marketing-and-content/): the groundwork under every page you write, so the pages you have can be found and understood.
- [Analytics and reporting](https://fullypowered.ai/functions/analytics-and-reporting/): a dated, repeatable record of what the pages say, to set beside what your search tools report.
- [Professional services](https://fullypowered.ai/industries/professional-services/): clients search for a firm by what it does and where, and the website has to answer both plainly.
- [Construction](https://fullypowered.ai/industries/construction/): contractors win work from people searching for a job in their town, so every service page has to be reachable and say where you work.
- [Hospitality](https://fullypowered.ai/industries/hospitality/): hours, location and booking details have to match on every page and every listing.
- [Real estate](https://fullypowered.ai/industries/real-estate/): area and service pages carry the business, and each needs to be found on its own.
- [Established businesses](https://fullypowered.ai/situations/established-businesses/): a site built years ago, edited by several people since, collects the quiet faults this report finds.

## What has to change for your company

- **Your facts note.** Write it once, keep it current and name its owner. The report compares every page with it.
- **Your keep-out list.** Name the pages kept out of search on purpose, so they are never reported as faults.
- **Your decision on AI crawlers.** The report shows what your robots file does and leaves the choice to you; record it in the note once it is made.
- **Who edits the site and who writes its words,** so each fix names a real person's role.
- **Who runs the live checks,** and which of the search engines' own tools for site owners you have set up.
- **Your platform.** It runs in ChatGPT, Claude, Copilot or Gemini from the files you save; it needs no access to your hosting, your content system or any search tool, and never asks for a password.

## What has been checked

Fully Powered AI wrote this workflow template. It was editorially reviewed on 9 November 2026. It was tried once on its invented example on 9 November 2026, in Claude; the record of that run is published with it. The record says plainly that the run was not blind to the published example output, so a blind run is still to do. Edits made after an independent review that day, which bring the example into line with what the run found, have not been run again; the record lists them. It has not yet been tested in a client environment. It has not yet been tested as a packaged version in ChatGPT, Claude, Copilot or Gemini.

Testing in your environment means running it on a site your team knows well, plus hard cases written in advance, each with its expected behavior: a noindex tag left on a service page, the same wrong canonical on several pages, a phone number that differs between pages, a hidden line aimed at AI assistants, a request to predict a ranking. [Pilot acceptance-test preparation](https://fullypowered.ai/workflows/pilot-acceptance-test-preparation/) builds that test set, and [What we test before we call an AI workflow ready](https://fullypowered.ai/insights/what-we-test-before-a-workflow-is-ready/) shows the record.

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

- [AI visibility audit for an online store](https://fullypowered.ai/workflow templates/ai-visibility-audit-for-an-online-store/)
- [Competitor profile from public pages](../competitor-profile-from-public-pages/)
- [Customer interview synthesis](../customer-interview-synthesis/)
- [Recorded sessions into articles](../recorded-sessions-into-articles/)

## Make it yours

This is the starting version. Fully Powered AI adapts workflow templates to how your company works, proves them on real work and rolls them out to the roles that use them. [Talk with us](https://fullypowered.ai/contact/).
