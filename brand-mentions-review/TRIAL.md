# Trial: Brand mentions and conversations review, run on its invented example

- **Product:** Claude, run in Claude Code

Model: Claude Sonnet 5.5 (model ID claude-sonnet-5-5). The assistant that ran this trial did not write the template.

Date: 2026-11-11

The inputs are the invented example in `public/example.md` (Quillfern, a made-up maker of home coffee grinders, with made-up handles and posts). No client data was used.

## Inputs used

All seven inputs from the "The inputs" section of `public/example.md`: the 17-row mention export, the brand terms and namesake, the competitor list, the topic scope, the settings, the last digest's "Needs a reply" section and the handled list. The example's own digest was not read until after the output below was produced. No stop condition was triggered: the headers matched the defaults, no ID repeated and nothing required was missing.

## What came out

The instruction block and output format were followed as written. The digest, in substance:

```
BRAND MENTIONS DIGEST: Quillfern, 2 November 2026 to 8 November 2026

For: Social media manager. Prepared 9 November 2026 from mentions-2026-11-02-to-08.csv, 17 rows; platforms: Microblog, Forum, Photo app, Review site. Brand terms: Quillfern, Quilfern, Quillfern Mill, QF Mill, @quillfern, @quillfern_help. Competitors: Maker A (MakerA), Maker B. Topics: Grinder recommendations, Burrs, Grind size. Reply window: 2 days. Last digest: 2 November 2026. Handled list: supplied.
Mentions read: 17. Outside the period: 1. Own posts: 1. Repeats: 1. Placed: 14 (Needs a person now 2 · Customer questions 3 · Other brand talk 1 · Competitor references 2 · Category talk 3 · Irrelevant 2 · Not placed 1).

1. Needs a person now: 2
M208 (2026-11-05, Review site, @slowmorningcup): "The handle on my Quillfern Mill snapped after a week and cut my hand." Matter: injury linked to the product. Decides: brand manager.
M212 (2026-11-07, Microblog, @deal_hunter_77): "QUILLFERN MILL 90% OFF TODAY ONLY, order here: bit.example/qf". Matter: possible scam using the brand's name. Decides: brand manager.

2. Needs a reply: 4
M188 (2026-10-29, Forum, @brewfirst): "Does the Quillfern Mill come with a warranty outside the US?" Kind: question. Owner: social media manager. Age: 11 days, past the reply window. Carried from 2 November 2026.
M204 (2026-11-03, Microblog, @dawn_pourover): "Ordered a QF Mill on 20 Oct and the tracking hasn't moved in nine days." Kind: own problem. Owner: support lead. Age: 6 days, past the reply window.
M207 (2026-11-04, Forum, @first_shot_sam): "Which grinder should I get?" Kind: open category question. Owner: brand manager. Age: 5 days, past the reply window.
M215 (2026-11-08, Forum, @portafilter_pete): "Does Quillfern sell replacement burrs for the original Mill, and what do they cost?" Kind: question. Owner: social media manager. Age: 1 day.
Already handled: M202, by the social media manager, 3 November.

3. Customer questions: 3   (M202, M204, M215; see 2)
4. Other brand talk: 1     (M211: "Morning ritual with the Quilfern. Best thing I bought this year.")
5. Competitor references: 2
Maker A: 1. M206: "Maker A's new grinder is louder than my old Quillfern Mill but grinds finer.", also names us.
Maker B: 1. M214: "Maker B grinder arrived with a cracked hopper. Second one this month."
6. Category talk: 3
Grinder recommendations: 1. M207 (open category question, see 2).
Burrs: 2. M210, M213. Grind size: 0.
Asked by two or more authors: conical or flat burrs, M210 and M213.
7. Irrelevant: 2
M205: namesake, "Repotted my quillfern" and "fronds".
M217: out-of-scope topic, "Flat white from the corner café".
8. Not placed: 1
M216: "Quillfern restock finally happened!" Question for the social media manager: does this mean the Mill or the quillfern plant?
9. Set aside
Outside the period: M201, 2026-10-30. Own posts: M203. Repeats: M209, repeat of M204.

Coverage and draft lines as in the format (17 mentions, no sentiment score, nothing posted, replied to, liked, reported or sent).
```

The full run printed every section in the format, with every quotation, link and "None this period." rule applied; this record keeps the substance.

## What was observed

- Every required part of the format was produced, and both sums in the count line held: 1 + 1 + 1 + 14 = 17, and 2 + 3 + 1 + 2 + 3 + 2 + 1 = 14.
- Compared with the published example, every placement, count, owner, age, the carried item and the handled item came out the same. The differences were wording only: which part of a long post to quote (as the example stood at the time of the run, it trimmed M204 and M215 and dropped the link and handle from some lines), the brand terms and competitor list in the header, and that this run did not print the example's closing "arithmetic for the reviewer" note, which is not part of the output format.
- No fact appeared in either output that is not in the inputs. The ages and the 11-day carried age are computed from the dates given.
- Shortcomings in the template (the assistant had to judge in each case):
  1. Scam against spam. "Spam" is an allowed reason under Irrelevant, and "possible scam using the brand's name" is a matter that needs a person. M212 could be either; only the order of the placement rules (matter first) settles it, and the template does not say so. The same rule would lift every ordinary spam post that uses the brand's name.
  2. Unsure against brand talk. For M216 the template says "could fairly read either way" is unsure. Treating a restock post as possibly the plant is a judgment, not something the words decide.
  3. Handled customer question. M202 is a customer question that is handled. Section 3 says "See 2", but section 2 lists it only under "Already handled". The format has no line saying so.
  4. Counts in section 2. The section 2 count includes the carried item, which is not in "Placed". Step 7 says this, but the format does not, and a reader checking the count line against the lists could think one is missing.
  5. Topic and "same question". No rule picks one topic when a post fits two (M210 could be Burrs or Grind size), and "the same question asked by two or more authors" is not defined; M210 and M213 are worded differently.
  6. Quotation length. Step 9 asks for a "short quotation" but the format shows one slot, so whether to trim or quote in full is left open.
  7. Leftover placeholder. Step 6 and the settings input write "[your reply window]" in the procedure text, as if it were a fill-in; the instruction block uses "the window".
  8. The version notes still said the template was not tried on its example, and the acceptance tests are marked "none has been run"; this trial did not change that file.
  9. Acceptance test 9 refers to "the burr question", which is not in the example's inputs.

## After the trial

The template was edited after this run, in response to the shortcomings above. Nothing in the record above was changed.

- Defects 3, 4, 5, 6 and 9 were fixed by wording: the format now says "See 2, already handled", section 2 reads "(includes [n] carried)", a mention is filed under the first matching topic in the scope's order, "the same question" means the same in substance, quotations are given in full (cut only past about 40 words), and acceptance test 9 names M215.
- Defect 1 was answered by a test that tells a possible scam (sells the product, speaks for the brand, or asks readers to follow a link to pay or sign in) from ordinary spam that is only irrelevant. M212 is still a possible scam.
- Defect 2 is a judgment the template leaves to the reader; defect 7 is the house placeholder style and was left; defect 8 is fixed in the version notes and the public pages.
- The example's published output was changed to match (full quotations, "See 2, already handled", the section 2 count note, a note on M210's topic). Its placements and counts did not change. These edits were not run again: this record is of the first run only.
