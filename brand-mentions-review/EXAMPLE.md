# Brand mentions and conversations review: an invented example

*Illustrative example with invented data.* Quillfern is an invented 30-person maker of home coffee grinders; its competitors appear as Maker A and Maker B, the platforms are named only by type, and every handle, post and address below was written for this example. No real company or person is described. On Monday 9 November 2026 the social media manager supplies last week's mentions, in full below, and the workflow template returns the digest that follows.

## The inputs

### 1. The mention export (mentions-2026-11-02-to-08.csv)

```
ID,Date,Platform,Author,Link,Text
M201,2026-10-30,Microblog,@unbox_daily,https://microblog.example/p/201,"Quillfern Mill unboxing tonight, finally."
M202,2026-11-02,Forum,@bean_ratio,https://forum.example/t/202,"Does the Quillfern Mill fit a 58mm dosing cup, or do I need an adapter?"
M203,2026-11-02,Photo app,@quillfern,https://photos.example/p/203,"New burr set now shipping."
M204,2026-11-03,Microblog,@dawn_pourover,https://microblog.example/p/204,"Ordered a QF Mill on 20 Oct and the tracking hasn't moved in nine days. @quillfern_help anyone there?"
M205,2026-11-03,Forum,@greenfrond,https://forum.example/t/205,"Repotted my quillfern today and the fronds are finally coming back."
M206,2026-11-04,Microblog,@kettle_and_crema,https://microblog.example/p/206,"Maker A's new grinder is louder than my old Quillfern Mill but grinds finer."
M207,2026-11-04,Forum,@first_shot_sam,https://forum.example/t/207,"First espresso setup, budget about $300. Which grinder should I get?"
M208,2026-11-05,Review site,@slowmorningcup,https://reviews.example/r/208,"The handle on my Quillfern Mill snapped after a week and cut my hand."
M209,2026-11-05,Microblog,@dawn_pourover,https://microblog.example/p/209,"Ordered a QF Mill on 20 Oct and the tracking hasn't moved in nine days. @quillfern_help anyone there?"
M210,2026-11-06,Forum,@grindnerd,https://forum.example/t/210,"Conical or flat burrs for light roasts? Has anyone compared them side by side?"
M211,2026-11-06,Photo app,@latte_lines,https://photos.example/p/211,"Morning ritual with the Quilfern. Best thing I bought this year."
M212,2026-11-07,Microblog,@deal_hunter_77,https://microblog.example/p/212,"QUILLFERN MILL 90% OFF TODAY ONLY, order here: bit.example/qf"
M213,2026-11-07,Forum,@cupping_carla,https://forum.example/t/213,"Flat or conical burrs for filter coffee? I keep reading opposite advice."
M214,2026-11-08,Microblog,@roastlog,https://microblog.example/p/214,"Maker B grinder arrived with a cracked hopper. Second one this month."
M215,2026-11-08,Forum,@portafilter_pete,https://forum.example/t/215,"Does Quillfern sell replacement burrs for the original Mill, and what do they cost?"
M216,2026-11-08,Microblog,@hollow_pine,https://microblog.example/p/216,"Quillfern restock finally happened!"
M217,2026-11-08,Microblog,@cafe_crawl,https://microblog.example/p/217,"Back to the daily grind tomorrow. Flat white from the corner café first."
```

### 2. The brand terms

```
Brand names: Quillfern, Quilfern (common misspelling)
Product names: Quillfern Mill, QF Mill
Our accounts: @quillfern, @quillfern_help
Namesake: quillfern (also "quill fern"), a garden fern. Words that give
  it away: fern, frond, repot, pot, soil, plant, nursery.
```

### 3. The competitor list

```
Maker A (also "MakerA")
Maker B
```

### 4. The topic scope

```
In scope:
- Grinder recommendations: people choosing a home grinder
- Burrs: burr types, wear and replacement
- Grind size: dialling in for espresso or filter
Out of scope:
- Cafés and coffee shops
- Bean prices
```

### 5. The settings

```
Brand: Quillfern
Period: 2 November 2026 to 8 November 2026
Date prepared: 9 November 2026
Reader: Social media manager
Own accounts: @quillfern, @quillfern_help
Reply window: 2 days
Reply owners: the defaults
Matters that need a person now: the defaults; the brand manager decides each
```

### 6. Last digest (prepared 2 November 2026), its "Needs a reply" section

```
2. Needs a reply: 1
M188, 2026-10-29, Forum, @brewfirst, https://forum.example/t/188:
"Does the Quillfern Mill come with a warranty outside the US?" Kind:
question. Suggested owner: Social media manager. Age: 4 days, past the
reply window.
```

### 7. The handled list

```
M202: answered on the forum by the social media manager, 3 November.
```

## The output

**BRAND MENTIONS DIGEST: Quillfern, 2 November 2026 to 8 November 2026**

For: Social media manager. Prepared 9 November 2026 from mentions-2026-11-02-to-08.csv, 17 rows; platforms: Forum, Microblog, Photo app, Review site. Brand terms: Quillfern, Quilfern, Quillfern Mill, QF Mill, @quillfern, @quillfern_help. Competitors: Maker A, Maker B. Topics: Grinder recommendations, Burrs, Grind size. Reply window: 2 days. Last digest: 2 November 2026. Handled list: supplied.
Mentions read: 17. Outside the period: 1. Own posts: 1. Repeats: 1. Placed: 14 (Needs a person now 2 · Customer questions 3 · Other brand talk 1 · Competitor references 2 · Category talk 3 · Irrelevant 2 · Not placed 1).

**1. Needs a person now: 2**

- M208, 2026-11-05, Review site, @slowmorningcup, https://reviews.example/r/208: "The handle on my Quillfern Mill snapped after a week and cut my hand." Matter: injury linked to the product. Decides: Brand manager.
- M212, 2026-11-07, Microblog, @deal_hunter_77, https://microblog.example/p/212: "QUILLFERN MILL 90% OFF TODAY ONLY, order here: bit.example/qf". Matter: possible scam using the brand's name. Decides: Brand manager.

**2. Needs a reply: 4 (includes 1 carried)**

- M188, 2026-10-29, Forum, @brewfirst, https://forum.example/t/188: "Does the Quillfern Mill come with a warranty outside the US?" Kind: question. Suggested owner: Social media manager. Age: 11 days, past the reply window. Carried from 2 November 2026.
- M204, 2026-11-03, Microblog, @dawn_pourover, https://microblog.example/p/204: "Ordered a QF Mill on 20 Oct and the tracking hasn't moved in nine days. @quillfern_help anyone there?" Kind: own problem. Suggested owner: Support lead. Age: 6 days, past the reply window.
- M207, 2026-11-04, Forum, @first_shot_sam, https://forum.example/t/207: "First espresso setup, budget about $300. Which grinder should I get?" Kind: open category question. Suggested owner: Brand manager. Age: 5 days, past the reply window.
- M215, 2026-11-08, Forum, @portafilter_pete, https://forum.example/t/215: "Does Quillfern sell replacement burrs for the original Mill, and what do they cost?" Kind: question. Suggested owner: Social media manager. Age: 1 day.

Already handled: M202, by the social media manager, 3 November.

**3. Customer questions: 3**

- M202: "Does the Quillfern Mill fit a 58mm dosing cup, or do I need an adapter?" See 2, already handled.
- M204: "Ordered a QF Mill on 20 Oct and the tracking hasn't moved in nine days. @quillfern_help anyone there?" See 2.
- M215: "Does Quillfern sell replacement burrs for the original Mill, and what do they cost?" See 2.

**4. Other brand talk: 1**

- M211: "Morning ritual with the Quilfern. Best thing I bought this year."

**5. Competitor references: 2**

- Maker A: 1. M206: "Maker A's new grinder is louder than my old Quillfern Mill but grinds finer.", also names us.
- Maker B: 1. M214: "Maker B grinder arrived with a cracked hopper. Second one this month."

**6. Category talk: 3**

- Grinder recommendations: 1. M207: "First espresso setup, budget about $300. Which grinder should I get?", open category question, see 2.
- Burrs: 2. M210: "Conical or flat burrs for light roasts? Has anyone compared them side by side?" M213: "Flat or conical burrs for filter coffee? I keep reading opposite advice."
- Grind size: 0.

Asked by two or more authors: flat or conical burrs (the same question in substance), M210 and M213. M210 also touches grind size and is filed under Burrs, the first matching topic in the scope's order.

**7. Irrelevant: 2**

- M205: namesake, "Repotted my quillfern today and the fronds are finally coming back." The words fern and fronds give it away.
- M217: out-of-scope topic, "Back to the daily grind tomorrow. Flat white from the corner café first."

**8. Not placed: 1**

- M216: "Quillfern restock finally happened!" Question for the social media manager: does this post mean the Mill or the quillfern plant? Nothing in its words says which.

**9. Set aside**

Outside the period: M201, 2026-10-30. Own posts: M203. Repeats: M209, repeat of M204.

Coverage: these are the 17 mentions read from the export, for 2 November 2026 to 8 November 2026, from Forum, Microblog, Photo app and Review site. They are not every conversation about Quillfern or its category. No sentiment score, share of voice or reach is given.
Draft for the social media manager. Nothing has been posted, replied to, liked, reported or sent.

**Note outside the digest, for the reviewer: the arithmetic.** 1 outside the period + 1 own post + 1 repeat + 14 placed = 17 read. 2 + 3 + 1 + 2 + 3 + 2 + 1 = 14 placed. Ages are counted from 9 November: 29 October is 11 days, 3 November 6, 4 November 5, 8 November 1; the window is 2 days.
