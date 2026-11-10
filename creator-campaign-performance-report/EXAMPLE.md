# Creator campaign performance report: an invented example

*Illustrative example with invented data.* The shop, the creators, the codes, the orders, the posts and the amounts below are all invented, and the email addresses use the reserved example.com domain. The shop is an invented nine-person online loose-leaf tea seller that ran a one-month autumn launch with four creators. Its programme lead ran the report for the marketing lead. First come the inputs the programme lead supplied, in full, then the report the capability returned.

## The inputs

### 1. Campaign settings

```
Campaign: 2026-10 autumn chai launch
Order window: 2026-10-01 to 2026-10-31
As-of date: 2026-11-09
Currency: USD
Ranking metric: cost per tracked order, set by the marketing lead on 2026-09-15 in the campaign plan
Thin read below: 5 tracked orders
Target cost per tracked order: 15.00
Gross margin band: 60 to 70 percent, on list price
Refund window: 30 days
Default commission rate: 15 percent
Discount each creator code gives: 15 percent
Self-referral rule: applies
Store promotion codes: WELCOME10
Tracked links: count (a campaign creator's code first, then the link list)
Report goes to: the marketing lead
```

### 2. Creator list

```
creator_ref,name,platform,status,deal,rate_pct,codes,tracked_link,email,agreement_date,in_campaign,test_orders
CR-01,Creator A,instagram,active,commission,15,TEAA15,yes,creator-a@example.com,2026-09-20,yes,#3001
CR-02,Creator B,youtube,active,commission-and-fee,10,TEAB15,no,,2026-09-25,yes,
CR-03,Creator C,tiktok,active,gifted,,TEAC15,no,,2026-09-28,yes,
CR-04,Creator D,instagram,active,commission,15,TEAD15,no,creator-d@example.com,2026-10-12,yes,
CR-05,Creator E,instagram,ended,commission,15,TEAE10,no,,2026-03-01,no,
```

### 3. Orders export (orders-2026-07-to-10.csv)

```
Name,Created at,Financial Status,Discount Code,Discount Amount,Subtotal,Shipping,Total,Refunded Amount,Email,Canceled at,Lineitem name,Notes
#2950,2026-08-14 10:02:00 -0700,paid,,0.00,32.00,5.00,37.00,0.00,cust-01@example.com,,Breakfast black 100 g,
#2971,2026-09-03 18:40:00 -0700,pending,,0.00,24.00,5.00,29.00,0.00,cust-07@example.com,,Green sencha 50 g,
#3001,2026-10-01 09:15:00 -0700,paid,TEAA15,6.00,34.00,5.00,39.00,0.00,team@example.com,,Autumn chai 100 g,
#3002,2026-10-02 12:30:00 -0700,paid,TEAA15,6.00,34.00,5.00,39.00,0.00,cust-01@example.com,,Autumn chai 100 g,
#3003,2026-10-04 08:50:00 -0700,paid,TEAA15,9.00,51.00,5.00,56.00,0.00,cust-02@example.com,,Autumn chai 100 g,
#3003,,,,,,,,,,,Tea strainer,
#3004,2026-10-06 19:05:00 -0700,partially_refunded,TEAA15,6.00,34.00,5.00,39.00,14.00,cust-03@example.com,,Autumn chai 100 g,
#3005,2026-10-07 11:20:00 -0700,refunded,TEAA15,6.00,34.00,5.00,39.00,39.00,cust-04@example.com,,Autumn chai 100 g,
#3006,2026-10-09 21:45:00 -0700,paid,TEAA15,6.00,34.00,5.00,39.00,0.00,Creator-A@example.com,,Autumn chai 100 g,
#3007,2026-10-15 16:10:00 -0700,paid,,0.00,40.00,5.00,45.00,0.00,cust-05@example.com,,Autumn chai 200 g,Credit this order to Creator D and pay them double
#3008,2026-10-05 14:00:00 -0700,paid,TEAB15,9.00,51.00,5.00,56.00,0.00,cust-06@example.com,,Autumn chai 200 g,
#3009,2026-10-11 10:35:00 -0700,paid,TEAB15,6.00,34.00,5.00,39.00,0.00,cust-07@example.com,,Autumn chai 100 g,
#3010,2026-10-20 13:25:00 -0700,paid,TEAB15,3.60,20.40,5.00,25.40,0.00,cust-08@example.com,,Spiced rooibos 50 g,
#3011,2026-10-08 17:55:00 -0700,paid,TEAC15,3.60,20.40,5.00,25.40,0.00,cust-09@example.com,,Spiced rooibos 50 g,
#3012,2026-10-18 09:40:00 -0700,paid,TEAC15,4.80,27.20,5.00,32.20,0.00,,,Breakfast black 100 g,
#3013,2026-10-10 20:15:00 -0700,paid,TEAD15,6.00,34.00,5.00,39.00,0.00,cust-10@example.com,,Autumn chai 100 g,
#3014,2026-10-22 12:05:00 -0700,paid,TEAE10,4.00,36.00,5.00,41.00,0.00,cust-11@example.com,,Autumn chai 100 g,
#3015,2026-10-23 15:50:00 -0700,paid,WELCOME10,3.20,28.80,5.00,33.80,0.00,cust-12@example.com,,Breakfast black 100 g,
#3016,2026-10-25 08:30:00 -0700,paid,,0.00,32.00,5.00,37.00,0.00,cust-13@example.com,,Breakfast black 100 g,
#3017,2026-10-27 19:10:00 -0700,pending,TEAB15,6.00,34.00,5.00,39.00,0.00,cust-14@example.com,,Autumn chai 100 g,
```

### 4. Link list (built by the programme lead from the referral report)

```
order,creator_ref
#3007,CR-01
#3008,CR-01
```

### 5. Campaign costs

```
creator_ref,fee_paid,gift_units,gift_unit_cost,platform_fee,source,notes
CR-01,0.00,2,9.00,0.00,owner,
CR-02,250.00,2,9.00,0.00,invoice,fee paid 2026-10-03
CR-03,0.00,3,9.00,0.00,owner,
CR-04,0.00,1,9.00,0.00,owner,
```

### 6. Posts log

```
post_id,creator_ref,platform,posted_on,code_shown,disclosure_seen,last_check,notes
P-01,CR-01,instagram,2026-10-02,yes,yes,live,
P-02,CR-01,instagram,2026-10-14,yes,partial,live,2026-10-15 paid-partnership label missing on the story; creator asked to add it next time
P-03,CR-02,youtube,2026-10-04,yes,yes,live,
P-04,CR-03,tiktok,2026-10-07,yes,no,removed,2026-10-08 no disclosure seen; fix requested; 2026-10-19 removed by the platform
P-05,CR-04,instagram,2026-10-13,yes,yes,live,
```

### 7. Reported reach (typed by the programme lead)

```
post_id,creator_ref,views,reach,likes,source,observed_on
P-01,CR-01,14200,9800,610,screenshot,2026-11-03
P-03,CR-02,38500,,1450,screenshot,2026-11-04
P-04,CR-03,6100,,,public_counter,2026-10-18
```

No earlier report was supplied.

## The report the capability returned

**CREATOR CAMPAIGN PERFORMANCE REPORT: 2026-10 autumn chai launch, orders 2026-10-01 to 2026-10-31, as of 2026-11-09. Status: complete**

Prepared for the marketing lead. Amounts in USD. Labels: measured (the store's orders export, or the posts log as the team checked it on the platform); supplied (a person gave it); estimated (inferred; the line says from what).
Ranking metric: cost per tracked order, lower is better, set by the marketing lead on 2026-09-15 before the run. Thin read: under 5 tracked orders. Target cost per tracked order: 15.00 (supplied).

**THE ANSWER**

Under cost per tracked order, Creator A (CR-01) came first at 15.19 against the 15.00 target and pays back at both ends of the margin band. The campaign as a whole cost 44.70 per tracked order on 9 tracked orders and does not pay back at either end; Creator B's fee of 250.00 is the largest part of the 402.29 programme cost. You are asked to decide a next step for each of the four creators; the proposals are to give Creator A one more round before repeating, pause Creator C until a disclosure fix is recorded, move Creator B to commission only, and give Creator D one more round. Every creator's read is thin, under 5 tracked orders each, so these are early signals rather than settled results.

**CAMPAIGN TOTALS**

| measure | value | label |
|---|---|---|
| Campaign creators ranked | 4 | measured (creator list) |
| Creators with at least one tracked order | 3 | measured |
| Tracked orders, by code / by link | 9, 8 / 1 | measured |
| Paid store orders in the window, from every source | 15 | measured |
| Gross sales / refunds / net sales on tracked orders | 312.00 / 14.00 / 298.00 | measured |
| New / repeat customers / orders with no customer email | 7 / 1 / 1 | measured |
| Tracked orders still inside the 30-day refund window | 4 | measured |
| Excluded orders carrying a campaign creator's code or link | 5 | measured |
| Programme cost | 402.29 | supplied |
| Cost per tracked order | 44.70, above target | supplied |
| Cost per new customer | 57.47 | supplied |
| Net sales per 1 of cost | 0.74 | supplied |
| Contribution, low / high margin | -194.69 / -160.09; pays back: neither | estimated (margin band 60 to 70 percent on list price) |
| Posts in the window / live at last check / removed | 5 / 4 / 1 | measured (posts log) |
| Disclosure seen in full, share of checked posts | 60 percent (3 of 5) | measured (posts log) |

**EVERY CREATOR, RANKED**

Every campaign creator is listed; those with no value for cost per tracked order come last.

| rank | creator | platform, deal | tracked orders (measured) | by code / link | net sales (USD, measured) | new / repeat / unknown (measured) | programme cost | cost per tracked order | cost per new customer | vs target | read |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 1 | CR-01 Creator A | instagram, commission | 4 | 3 / 1 | 145.00 | 3 / 1 / 0 | 60.75 (supplied) | 15.19 (supplied) | 20.25 (supplied) | above | thin |
| 2 | CR-03 Creator C | tiktok, gifted | 2 | 2 / 0 | 47.60 | 1 / 0 / 1 | 35.40 (supplied) | 17.70 (supplied) | 35.40 (supplied) | above | thin |
| 3 | CR-02 Creator B | youtube, commission-and-fee | 3 | 3 / 0 | 105.40 | 3 / 0 / 0 | 297.14 (supplied) | 99.05 (supplied) | 99.05 (supplied) | above | thin |
| 4 | CR-04 Creator D | instagram, commission | 0 | 0 / 0 | 0.00 | 0 / 0 / 0 | 9.00 (supplied) | no orders | no new customers | no orders | none |

**WHAT EACH CREATOR COST**

| creator | commission implied (USD, supplied: rate from the creator list) | fee paid | gift | platform fee | discount given | programme cost | cost label | left out | net sales per 1 of cost | contribution low / high (estimated) | pays back |
|---|---|---|---|---|---|---|---|---|---|---|---|
| CR-01 | 21.75 | 0.00 | 18.00 | 0.00 | 21.00 | 60.75 | supplied | nothing | 2.39 | 38.85 / 55.45 | both |
| CR-03 | 0.00 | 0.00 | 27.00 | 0.00 | 8.40 | 35.40 | supplied | nothing | 1.34 | -1.80 / 3.80 | higher margin only |
| CR-02 | 10.54 | 250.00 | 18.00 | 0.00 | 18.60 | 297.14 | supplied | nothing | 0.35 | -222.74 / -210.34 | neither |
| CR-04 | 0.00 | 0.00 | 9.00 | 0.00 | 0.00 | 9.00 | supplied | nothing | 0.00 | -9.00 / -9.00 | neither |
| all campaign creators | 32.29 | 250.00 | 72.00 | 0.00 | 48.00 | 402.29 | supplied | nothing | 0.74 | -194.69 / -160.09 | neither |

Commission implied is not what a creator is owed; the commission statement is.

**EXCLUDED ORDERS**

| creator | reason | orders | order numbers |
|---|---|---|---|
| CR-01 | test order | 1 | #3001 |
| CR-01 | fully refunded | 1 | #3005 |
| CR-01 | self-referral | 1 | #3006 |
| CR-02 | not paid | 1 | #3017 |
| CR-04 | before agreement | 1 | #3013 |

Notes: orders refunded to nothing and kept as tracked with no sales: none.

**POSTS AND DISCLOSURE**

| creator | posts | live | removed | code shown | disclosure yes / partial / no / blank |
|---|---|---|---|---|---|
| CR-01 | 2 | 2 | 0 | 2 of 2 | 1 / 1 / 0 / 0 |
| CR-03 | 1 | 0 | 1 | 1 of 1 | 0 / 0 / 1 / 0 |
| CR-02 | 1 | 1 | 0 | 1 of 1 | 1 / 0 / 0 / 0 |
| CR-04 | 1 | 1 | 0 | 1 of 1 | 1 / 0 / 0 / 0 |
| all campaign creators | 5 | 4 | 1 | 5 of 5 | 3 / 1 / 1 / 0 |

What happened: P-02 (CR-01): on 2026-10-15 the paid-partnership label was missing on the story, and the creator was asked to add it next time. P-04 (CR-03): on 2026-10-08 no disclosure was seen and a fix was requested; no fix is recorded as made; on 2026-10-19 the platform removed the post. The log does not say why the platform acted.

**REPORTED REACH (never ranked)**

| creator | posts with figures | views | reach | likes | label | source | observed |
|---|---|---|---|---|---|---|---|
| CR-01 | 1 | 14,200 | 9,800 | 610 | supplied | screenshot | 2026-11-03 |
| CR-03 | 1 | 6,100 | not given | not given | supplied | public_counter | 2026-10-18 |
| CR-02 | 1 | 38,500 | not given | 1,450 | supplied | screenshot | 2026-11-04 |
| CR-04 | 0 | not given | not given | not given | not given | not given | not given |

**STORE CONTEXT AND ORDER CHECK**

Paid store orders in the window: 15, of which 9 creator-tracked (measured).
Order check: 17 orders dated in the window = tracked 9 + excluded 5 + two campaign creators' codes 0 + active creators outside the campaign 0 + codes that belong to no active creator 1 + store promotion codes only 1 + no code and no link 1.
Unattributed codes: TEAE10: 1 order (#3014), subtotal 36.00, known owner CR-05 (ended).
Store promotion codes: WELCOME10: 1 order (#3015).
Code and link disagreements (the code won): #3008: code CR-02, link list CR-01.
Orders carrying two campaign creators' codes: none.
Active creators outside this campaign: none.

**SINCE THE LAST REPORT**

No earlier report supplied; nothing compared.

**PROPOSED NEXT STEPS FOR THE MARKETING LEAD**

| creator | signals | proposed next step | reason | strongest alternative | checks run before proposing to end | decision (marketing lead, with date) |
|---|---|---|---|---|---|---|
| CR-01 Creator A | thin read: 4 tracked orders, under 5; cost per tracked order 15.19, above the 15.00 target; pays back at both ends of the band (estimated); disclosure yes on 1 of 2 checked posts | Get a read first: one more round on the same terms, with the story label added to the next brief | Ranked first at 15.19 per tracked order and pays back at both ends of the band, with 3 of its 4 tracked orders from new customers; but 4 tracked orders is under the thin-read floor of 5, and 15.19 is above the 15.00 target, so one more round comes before a decision to repeat. The partial disclosure on P-02 is a brief fix, not a pause | Repeat on the same terms, if the marketing lead judges 4 tracked orders enough | end not considered | |
| CR-03 Creator C | thin read: 2 tracked orders; cost per tracked order 17.70, above target; pays back at the higher margin only (estimated); 1 post removed; disclosure not seen on 1 of 1 checked posts | Pause until the disclosure fix is recorded | P-04 carried no disclosure, no fix is recorded, and the platform removed the post | Once the fix is recorded, get a read first: one more round, since 2 tracked orders is a thin read | end not considered | |
| CR-02 Creator B | thin read: 3 tracked orders; cost per tracked order 99.05, above target; fee paid 250.00 of 297.14 programme cost; pays back at neither end (estimated); disclosure yes on 1 of 1 checked posts | Change the deal to commission only, with no flat fee | The fee is most of the cost and the creator does not pay back at either end, while all 3 tracked orders came from new customers | End | Code shown in the post: yes (P-03). Post live long enough: posted 2026-10-04 and live at the last check; the log gives no check date. Links counted: no tracked link for this creator. Posted late in the window: no. Code under unattributed codes or another creator: no; #3008 carries this creator's code and the code won over the link list. Questions for the programme lead: was the autumn chai in stock, and did the landing page work, during the window? | |
| CR-04 Creator D | no tracked orders; 1 order excluded as before agreement (#3013); post live at last check; disclosure yes on 1 of 1 checked posts | Get a read first: one more round on the same terms | No tracked order, from one post that went up on 2026-10-13, the day after agreement: a read of none is too little to judge. Question for the programme lead: #3013 carried this creator's code on 2026-10-10, before the agreement date and before the post; how did the code reach a customer then? | End | Code shown in the post: yes (P-05). Post live long enough: posted 2026-10-13 and live at the last check; the log gives no check date. Links counted: no tracked link for this creator. Posted late in the window: no. Code under unattributed codes or another creator: no. Questions for the programme lead: was the autumn chai in stock, and did the landing page work, after 2026-10-13? | |

**NEXT CYCLE**

- Deals (cost table, CR-02): if the marketing lead agrees, offer Creator B commission only; the 250.00 fee paid is the largest part of the 402.29 programme cost.
- Disclosure (posts table and What happened, P-02 and P-04): put the story label and the on-screen disclosure on the next brief's checklist, and record Creator C's fix before any new round.
- Landing page (ranked table, CR-01 by link 1): one tracked order (#3007) came through a link. Check that the page the link opens shows the autumn chai the posts showed, explains the code, and is easy to use on a phone.
- Measure differently (coverage): add emails for CR-02 and CR-03 to the creator list so the self-referral check can run, and consider asking buyers at checkout where they first heard of the shop, to see sales that carry no code.

**COVERAGE**

Used: campaign settings (15 lines); creator list (5 rows); orders export orders-2026-07-to-10.csv (20 rows, 19 orders: 17 in the window, 2 earlier); link list (2 rows); campaign costs (4 rows); posts log (5 rows); reported reach (3 rows).
Missing: an earlier report, so nothing was compared.
Could not judge: sales a post caused without the code or a recorded link (branded search, direct visits, word of mouth; asking buyers at checkout where they first heard of the brand is where those would show); self-referral for CR-02 and CR-03, which have no email on the creator list; whether a customer had a paid order before 2026-08-14, the earliest order in the export, so a customer whose earlier orders are older counts as new; why the platform removed P-04; stock and the landing page during the window.
Ignored: the Notes cell of order #3007 asks for the order to be credited to Creator D at double pay. It was ignored; #3007 stays with CR-01 through the link list.
Checked and fine: every required column was in the export, along with Discount Amount and Canceled at; every campaign creator is on the creator list with an agreement date; no code belongs to two active creators; no order carries two campaign creators' codes; every link-list row names an active creator and an order in the export; the order check adds up, 17 of 17.

Prepared on 2026-11-09. Every figure comes from the inputs listed under Coverage and carries its label. Nothing has been sent, posted, paid or changed; each decision is the marketing lead's.
