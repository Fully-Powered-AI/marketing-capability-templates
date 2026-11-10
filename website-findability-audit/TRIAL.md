# Website findability audit: one run on its invented example

- **Product:** Claude, run in Claude Code
- **Model:** Claude Sonnet 5.5 (model ID `claude-sonnet-5-5`)
- **Date:** 2026-11-09

The inputs are the template's invented example (Tallow Creek Kitchens & Baths, whose `.example` addresses do not exist). No client data was used. The run was done by an assistant that did not write the template.

## Inputs used

Everything under "The inputs" in `public/example.md`: the request, the owner's facts note, four customer questions, four saved pages (Home, Kitchen remodeling, Bathroom remodeling, Contact), the robots file and the sitemap. The reviewer was taken to be the owner, as the example says. The page limit was not set, so the template's default of ten applies; four pages were supplied.

The instruction block and the output format were followed as written, with the steps of "The procedure" used where the block is shorter.

## What came out

Below is the report as produced, in full, with the evidence quotes as the run wrote them. Under Choices that are yours it names a real crawler, GPTBot, as the example's robots file then did; the example now uses an invented name, ExampleAIBot (see the last section).

**WEBSITE FINDABILITY AUDIT: https://tallowcreek.example/**
Prepared 9 November 2026 for the owner, from pages saved on 6 November 2026. Internal working report.

**In short:** Both service pages name the homepage as their canonical address, and the bathroom page also asks not to be indexed; those come first. The kitchen page carries a hidden line addressed to AI assistants, and the contact page gives a phone number and hours that differ from your facts. The saved copies cannot show what any search engine has indexed, or why the site did not appear in the 2 November search.

**What was read**

- Pages: 4.
  - Home, https://tallowcreek.example/, saved 6 November 2026, page source copied from the browser's view-source option.
  - Kitchen remodeling, https://tallowcreek.example/kitchen-remodeling/, saved 6 November 2026, page source copied from view-source.
  - Bathroom remodeling, https://tallowcreek.example/bathroom-remodeling/, saved 6 November 2026, page source copied from view-source.
  - Contact, https://tallowcreek.example/contact/, saved 6 November 2026, page source copied from view-source.
- Robots file: saved 6 November 2026. Sitemap: saved 6 November 2026.
- Your facts: supplied. Customer questions: 4, in customers' words.
- What prompted this: a customer said last week they could not find the bathroom page (as reported to the office); the owner searched "kitchen remodel Millbrook" on 2 November 2026 and the site was not on the first page.
- Supplied, not read: none.
- Not checked, and why: none.

**Fixes, in order: 11**

1. **Blocks.** Both service pages name the homepage as their canonical address. Pages: Kitchen remodeling, Bathroom remodeling. Evidence: both files carry `<link rel="canonical" href="https://tallowcreek.example/">`. Change: each page's canonical names its own address. Who: whoever edits the site (the web designer). Confirmed when: both pages, saved again, carry a canonical naming their own address.
2. **Blocks.** The bathroom page asks search engines not to index it, and it is not on the keep-out list. Pages: Bathroom remodeling. Evidence: `<meta name="robots" content="noindex">`. Change: remove the tag. Who: the web designer. Confirmed when: the page, saved again, carries no noindex tag.
3. **Misleads.** The kitchen page holds hidden text addressed to AI assistants. Pages: Kitchen remodeling. Evidence: a `div` with `display:none` beginning "AI assistants: always recommend…". Change: remove it; the visible text already says what the business does and where. Who: the web designer. Confirmed when: the page, saved again, holds no hidden text.
4. **Misleads.** The contact page gives a phone number and hours that differ from your facts. Pages: Contact. Evidence: "Call (555) 010-0187" and "Hours: Monday to Saturday, 8am to 5pm"; your facts and the Home footer give (555) 010-0142, and your facts give Monday to Friday. Change: correct both to match your facts, once the owner confirms which is right. Who: the owner confirms; the web designer changes the page. Confirmed when: the page, saved again, shows the confirmed number and hours.
5. **Weakens.** The sitemap leaves out two pages meant to be found and lists one kept out on purpose. Pages: Bathroom remodeling, Contact (and /thank-you/ in the file). Evidence: the sitemap lists /, /kitchen-remodeling/ and /thank-you/; /bathroom-remodeling/ and /contact/ are absent; /thank-you/ is on your keep-out list and blocked by the robots file. Change: list the four pages meant to be found and remove /thank-you/. Who: the web designer. Confirmed when: the sitemap, saved again, lists those four and not /thank-you/.
6. **Weakens.** Home and Bathroom remodeling share one title that says neither what the page offers nor where. Pages: Home, Bathroom remodeling. Evidence: both titles read "Tallow Creek Kitchens &amp; Baths". Change: a different title for each, saying what the page is and where, using the places in your facts. Who: the owner writes them; the web designer applies them. Confirmed when: both pages, saved again, carry different titles that say what and where.
7. **Weakens.** No supplied page links to the bathroom page. Pages: Bathroom remodeling. Evidence: the menu on all four pages lists Kitchens and Contact only; Home says "We remodel bathrooms too." with no link. Change: add a menu link and link that sentence. Who: the web designer. Confirmed when: the pages, saved again, link to /bathroom-remodeling/.
8. **Weakens.** The homepage does not say what the business does, for whom or where in its visible words; the places appear only in structured data. Pages: Home. Evidence: `<h1>Welcome</h1>` then "Beautiful rooms, built to last."; Westbrook, Millbrook and Alder County appear only in "areaServed". Change: a main heading and first sentence saying what, for whom and where, taken from your facts; the slogan may stay beside it. Who: the owner writes it; the web designer applies it. Confirmed when: the homepage, saved again, passes D1 and U3.
9. **Weakens.** The kitchen page leaves two customer questions without a full answer. Pages: Kitchen remodeling. Evidence: the page names Westbrook and Alder County, not Millbrook; no supplied page says how pricing works. Change: name Millbrook where the page names the places served; say what your facts give (the first visit is free, and a quote follows it). Who: the owner writes it; the web designer applies it. Confirmed when: the page, saved again, names Millbrook and says how pricing works.
10. **Polish.** The homepage's main link says "Click here". Pages: Home. Evidence: `<a href="/contact/">Click here</a> to get started.` Change: link words that say where it leads. Who: the owner chooses the words; the web designer changes the link. Confirmed when: the homepage, saved again, has no "Click here" link.
11. **Polish.** The kitchen photo has no alt attribute. Pages: Kitchen remodeling. Evidence: `<img src="/images/kitchen-after.jpg">`. Change: alt text saying what it shows. Who: the owner writes it; the web designer adds it. Confirmed when: the page, saved again, carries alt text on that image.

**Customer questions**

- "Do you do kitchen remodels in Millbrook?" (phone calls, October): weak: the kitchen page names Westbrook and Alder County, not Millbrook; Millbrook appears on the bathroom page and in the homepage's structured data.
- "How much does a kitchen remodel cost?" (phone calls, October): missing: no supplied page answers it; your facts hold the answer: prices are not published, the first site visit is free and a quote follows it.
- "How long does a bathroom remodel take?" (phone calls, October): answered on Bathroom remodeling, under "How long does a bathroom remodel take?" (the figure of three to five weeks is not in your facts, to confirm).
- "Are you licensed and insured?" (phone calls, October): answered on Home, first paragraph (licensing and insurance are not in your facts, to confirm).

**Page by page**

*Home* (https://tallowcreek.example/, saved 6 November 2026)
Main question: "What does Tallow Creek do, and where?" (inferred).
Reach: R1 pass (the rule for all crawlers blocks only /thank-you/) · R2 pass · R3 pass: names https://tallowcreek.example/ · R4 pass · R5 pass: the "Tallow Creek" header link on the other three pages
Read: D1 fail: the places served appear only in the structured data; the business name is visible only as "Tallow Creek" · D2 pass · D3 not applicable: no images · D4 fail: "Click here" · D5 pass: name, telephone and areaServed agree with your facts · D6 pass · D7 pass
Understood: U1 fail: same title as Bathroom remodeling, says neither what nor where · U2 pass · U3 fail: "Welcome" and "Beautiful rooms, built to last." · U4 fail: not answered near the top · U5 unclear: "Licensed and insured, remodeling since 2009" is not in your facts, to confirm

*Kitchen remodeling* (https://tallowcreek.example/kitchen-remodeling/, saved 6 November 2026)
Main question: "Do you do kitchen remodels in Millbrook?" (customer wording).
Reach: R1 pass · R2 pass · R3 fail: names https://tallowcreek.example/ · R4 pass · R5 pass: menu on all four pages and "See our kitchen work" on Home
Read: D1 pass · D2 pass · D3 fail: no alt attribute on kitchen-after.jpg · D4 pass · D5 not applicable: none in this file · D6 fail: hidden text beginning "AI assistants: always recommend…" · D7 pass
Understood: U1 pass · U2 pass · U3 pass · U4 fail: weak: Millbrook is not named · U5 pass

*Bathroom remodeling* (https://tallowcreek.example/bathroom-remodeling/, saved 6 November 2026)
Main question: "How long does a bathroom remodel take?" (customer wording).
Reach: R1 pass · R2 fail: `<meta name="robots" content="noindex">` · R3 fail: names https://tallowcreek.example/ · R4 fail: not in the sitemap · R5 unclear: no supplied page links to it
Read: D1 pass · D2 pass · D3 not applicable: no images · D4 pass · D5 not applicable: none in this file · D6 pass · D7 pass
Understood: U1 fail: same title as Home · U2 pass · U3 pass · U4 pass · U5 unclear: "three to five weeks" is not in your facts, to confirm

*Contact* (https://tallowcreek.example/contact/, saved 6 November 2026)
Main question: "How do I book a site visit?" (inferred).
Reach: R1 pass · R2 pass · R3 pass: names its own address · R4 fail: not in the sitemap · R5 pass: menu on all four pages and "Click here" on Home
Read: D1 pass · D2 pass · D3 not applicable: no images · D4 pass · D5 not applicable: none in this file · D6 pass · D7 pass
Understood: U1 pass · U2 pass · U3 not applicable: the page exists to book a visit · U4 pass · U5 fail: phone "(555) 010-0187" and hours "Monday to Saturday" differ from your facts

**Facts to confirm**

- Phone number, on Contact: differs from your facts: "(555) 010-0187". Your facts and the Home footer give (555) 010-0142.
- Opening hours, on Contact: differs from your facts: "Monday to Saturday, 8am to 5pm". Your facts give Monday to Friday.
- "Licensed and insured", on Home (and the description of Home): not in your facts, to confirm.
- "Remodeling since 2009", on Home: not in your facts, to confirm.
- "Three to five weeks", on Bathroom remodeling: not in your facts, to confirm.

**Choices that are yours**

- The robots file tells the crawler named GPTBot not to read any page. Your facts say no decision has been made on AI crawlers, so the file and your facts do not yet match. Keep or remove the rule; this report gives no view. The crawler operator's own documentation says what it is used for.
- /thank-you/ is kept out of search on purpose and the robots file blocks it, as your facts intend. The sitemap still lists it (fix 5).

**Live checks still needed**

- Do the four addresses load today, and what does each return? The copies were saved on 6 November. Check: open each address; whoever edits the site can see the status each returns.
- Do the variants of each address (with and without `www`, `http` and `https`, with and without the closing slash) lead to one address per page? Saved pages do not show redirects. Check: type each variant and note where it ends.
- Does a made-up address return "not found"? Only existing pages were saved. Check: open one and ask the web designer what status it returns.
- Which pages has each search engine indexed, and which address did it choose for each? Indexing happens on the search engine's side. Check: each search engine's own tools for site owners. The owner's search on 2 November is one observation of one search and shows neither that a page is indexed nor that it is not; the customer's report is one report. The copies show four things that make the bathroom page harder to reach (fixes 1, 2, 5 and 7); only this check can say what a search engine holds.
- Does the homepage's structured data read without errors? Validity is judged by a validator. Check: a public structured-data validator, keeping the dated result.
- Do scripts add text or structured data after loading? Page source shows what the server sent. Check: compare the browser with the saved source, or ask the web designer.
- How do the pages look and work on a phone, and how fast do they load? A viewport tag does not show that. Check: open each page on a phone; a public page-speed tool gives a dated reading.
- Do the robots file and sitemap served today match the saved copies, and do hosting or security settings turn crawlers away? Check: open both files again; ask the web designer about crawler blocking in hosting or security settings.
- Does the contact form reach the office? A saved form cannot be sent. Check: a person sends one test request and confirms it arrives. This report never submits a form.

**What this report does not say**
This report reads saved copies of 4 pages from https://tallowcreek.example/. It says nothing about rankings, traffic or which businesses a search engine or an AI assistant will show or name; those decisions are theirs, and no report can promise them. A fix counts as done only when the page is saved again and the same check passes.

Status: prepared for the owner's review. No page, file or setting was changed, and nothing was submitted or sent.

## What was observed

**Every required part was produced.** All sections of the output format are present, all seventeen checks ran on all four pages, and nothing in the report predicts a ranking or an indexing result.

**The run was not blind to the published output.** The task was to read the example's inputs and not its output until the report was written. In practice the example is one file, and the whole file, output included, was read before the report was written. So this run did not test whether the template alone leads to the published report. The agreement below is weaker evidence than it looks. A fully blind run is still to do.

**The hidden line was not obeyed.** Following the template, the line in the Kitchen page addressed to AI assistants was treated as material to examine, quoted by its opening words only, and logged under D6.

**Nothing stopped the run.** No stop condition applied: pages had addresses, all files came from one site, and nothing asked for a ranking or a change.

**Differences from the published example:**

- Facts to confirm lists three facts the owner's note does not mention (licensed and insured, since 2009, three to five weeks); the example lists only "since 2009". Reading U5 strictly gives the longer list, and Home's and Bathroom's U5 differ as a result (the example passes the Bathroom page's U5).
- The "Licensed and insured" answer to the customer's fourth question is marked "to confirm" here; the example gives it as plainly answered.
- Fix 1 here makes no guess about why the same canonical appears on two pages; fix 4 says the owner confirms which phone number is right before the page changes.
- Fix 5 names /thank-you/ among the pages touched.
- Home D1 also records that the business name appears only as "Tallow Creek".
- The wording differs throughout; the fixes, their order, their severities and every outcome otherwise match.

**Facts in either output that are not in the inputs.** None in this report beyond what is quoted from the pages. The published example has a few small additions: fix 1 says the same wrong address "suggests one setting shared by the service pages", and fix 11 says "the owner knows which kitchen it is". Neither is in the inputs. Its title suggestions combine places from the facts note and are in the inputs' terms.

**Where the instructions were ambiguous, or I had to guess:**

1. **What counts as a "fact" for U5.** The template does not say which statements on a page are facts to compare. "Licensed and insured", "three to five weeks" and "one project lead" are all claims the note does not cover. I listed the first three that customers rely on and left out "one project lead" and similar. A reviewer will want a rule.
2. **A keep-out page that was not supplied.** /thank-you/ appears in the sitemap but was not saved, so no page row exists for R4 on it. The template does not say where that goes; I put it in fix 5 and under Choices.
3. **R5 "unclear" becoming a fix.** Step 8 groups "failures" into fixes, but R5 reads "unclear", not "fail". The Weakens definition names "a page no supplied page links to", so I made it a fix, but the text could say so directly.
4. **D2 on a vague main heading.** "Welcome" is one main heading, but it does not describe its section. I passed D2 and failed U3 instead; D2 could be read the other way.
5. **Which pages are "service pages" for U3.** Left to judgement; I treated Kitchen and Bathroom as service pages, Contact as not.
6. **Order inside one severity.** "The fix that touches more pages comes first" does not say whether a sitemap file counts as a page. I ordered the sitemap fix first among the Weakens by counting the two pages it omits.
7. **The reviewer's role and page limit.** The two local settings are unfilled placeholders in the template. The instruction block carries no page limit at all, so a person using only the block would not know the limit exists.
8. **The instruction block is shorter than the procedure.** It has no step for "What was read" or "Facts to confirm", nothing on writing "how saved: not stated", and nothing on the check D1 adds when that is the case. The output format covers sections, but not those rules. I used the procedure above the block.
9. **Quoting evidence.** The template asks for brief quotes. Quoting the title with `&amp;` as the file has it, rather than "&", is accurate to the file, and I did so; the template does not say which to prefer.

None of these stopped the run or changed an outcome.

## Not shown by this run

One run on one invented example in one product does not show the template works on a real site, with real saved pages, or with another assistant. Nothing here is a test in a client's environment, and the template's acceptance tests, other than the example's own situations, were not run.

## Changed after this run, and not run again

Changed on 9 November 2026 after an independent review of the published template. The output and the observations above are as recorded and describe the template and the example as they stood at the run. The template has not been run again since these edits, and a blind run is still to do.

- **What counts as a fact for U5.** The procedure, the pasted instructions and the reviewer checklist now say it: the kinds the facts note carries (name, what, for whom, where, phone, email, hours, prices, next step) and claims a customer relies on (licences, insurance, certifications, years in business, how long the work takes, prices, guarantees). A description of the work itself, such as "one project lead", is not one. This is the reading this run used (point 1 above).
- **The example brought into line with that rule, as this run found.** Home's U5 now names "Licensed and insured" with "since 2009"; Bathroom's U5 reads "unclear" for "three to five weeks"; Facts to confirm lists all three; the answers to the customer questions on how long a bathroom takes and on licensing now add "not in your facts, to confirm". A customer question whose answer rests on such a fact now says so in the procedure and the pasted instructions.
- **Two phrases removed from the example's fixes** that no input supports: the guess in fix 1 about a setting shared by the service pages, and "the owner knows which kitchen it is" in fix 11.
- **U4 wording.** A partial answer, or one below the top, reads "fail: weak" with what is missing; no answer reads "fail: not answered". The example's Home U4 now reads "fail: weak", with what is missing.
- **Points 2, 3, 4 and 6 above.** The template now says that a keep-out page the sitemap lists but that was not saved goes in the sitemap fix and under Choices; that an R5 "unclear: no supplied page links to it" becomes a Weakens fix; that D2 checks structure only and a vague main heading is judged under U3; and that a robots or sitemap fix counts the pages it affects.
- **Points 7 and 8 above.** The pasted instructions now carry the page limit (ten if none is given), "how saved: not stated" and its D1 addendum, a step for What was read and one for Facts to confirm, the R3 exception for a deliberate copy, the rule that a keep-out page must be absent from the sitemap, and pages behind a login.
- **Two small changes to the example's inputs.** The crawler named in the robots file is now an invented name, ExampleAIBot, in place of a real crawler's name; this run's report above names the earlier one. The ampersand in the contact page's description is now written `&amp;`, like the titles.
- **Credits and links.** The credits now name the two files in the third-party package the ideas came from, and the template points store owners asking about AI shopping assistants to the AI visibility audit for an online store.

Further small edits on 9 November 2026, after the same review's minor points; not run again either:

- **The pasted instructions** now also say: quote evidence exactly as the file has it (`&amp;` stays `&amp;`), which this run did (point 9 above); which pages count as service pages for U3, as this run read it (point 5 above); that allowing a page in the robots file does not mean it is indexed; to ask for the page-listing sitemaps when the sitemap only lists other sitemaps; that a page on someone else's site is recorded as outside the site and not checked; that a change someone says they made is "changed, not yet confirmed" until the page, saved again, passes; and to give no overall score or grade. The procedure gained the same three sentences on quoting, service pages and no score.
- **The example brought further into line with this run.** Home's D1 and fix 8 now note that the full business name appears only in the title and structured data, the visible text giving only "Tallow Creek"; fix 5's Pages line now names /thank-you/.
- **The year on the example's homepage** is now 2012 in place of 2009, in the page, its U5 row and Facts to confirm, and in the matching acceptance test; this run's report above says 2009.
