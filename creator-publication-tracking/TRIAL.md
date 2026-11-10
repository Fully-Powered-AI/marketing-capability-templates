# Creator publication tracking: tried on its invented example

- **Product:** Claude, run in Claude Code
- **Model:** Claude Sonnet 5.5 (model ID claude-sonnet-5-5)
- **Date:** 2026-11-09

The inputs are the invented example in [example.md](example.md): Fernhollow Candle Co., the Winter Hearth campaign, its creators, codes and web addresses are all made up. No client data was used. The model that ran the template did not write it.

## How it was run

The model read the template (`member/template.md`) and took only the five invented inputs from the example: the campaign rules, the deliverables list (5 rows), the post log (10 rows), the actions log (3 rows) and the request (report date 2026-11-20). It had not read the example's output. It then followed the fenced instruction block and the output format on those inputs. Only afterwards did it compare its output with the published example's output and the reviewer checklist. Nothing was sent, posted, paid or changed.

## What came out

All required parts of the output format were produced. The report, in the template's format:

```
CREATOR PUBLICATION TRACKING: Winter Hearth, as of 2026-11-20, partial

For: programme lead. Prepared 2026-11-20 from: campaign rules of 2026-10-28; deliverables list (5 rows); post log (10 rows, last look 2026-11-18); actions log (3 rows).
Result: 4 overdue, 5 to act on, 1 not checked, 0 coming up.

Agreed against published
- c-mk0412 instagram reel, agreed by 2026-11-06: published 2026-11-05 (on time), https://www.instagram.com/reel/WH0412A/.
- c-mk0412 instagram story, agreed by 2026-11-13: published 2026-11-13 (on time), https://www.instagram.com/stories/wh0412/3001/.
- c-dl0915 youtube video, agreed by 2026-11-08: published 2026-11-09 (1 day late), https://www.youtube.com/watch?v=WH0915D.
- c-pa0303 tiktok video, agreed by 2026-11-12: published 2026-11-11 (on time), https://www.tiktok.com/@wh0303/video/7001.
- c-pa0303 tiktok video, agreed by 2026-11-19: not published, 1 day past the agreed date.
Published but not agreed: none

Live check, as last seen
https://www.instagram.com/reel/WH0412A/ (c-mk0412, instagram reel, posted 2026-11-05; last looked 2026-11-12)
- Status: live at the day7 look on 2026-11-12.
- Disclosure: yes. Required: caption, spoken, on_screen, platform_label. Counted: caption, spoken, on_screen, platform_label; "#ad | this is an ad for Fernhollow".
- Code: match. Issued MKHEARTH15; seen MKHEARTH15.
- Link: match. Issued https://fernhollow.example/shop?ref=c-mk0412; seen https://fernhollow.example/shop?ref=c-mk0412, in the profile.
- Approved version: match. winter-hearth-c-mk0412-2.
- Notes: 2026-11-05: link in profile.

https://www.instagram.com/stories/wh0412/3001/ (c-mk0412, instagram story, posted 2026-11-13; last looked 2026-11-14)
- Status: live at the day1 look on 2026-11-14.
- Disclosure: partial. Required: on_screen, platform_label. Counted: on_screen; "#ad".
- Code: match. Issued MKHEARTH15; seen MKHEARTH15.
- Link: absent. Issued https://fernhollow.example/shop?ref=c-mk0412; seen none.
- Approved version: not looked at. winter-hearth-c-mk0412-3.
- Notes: 2026-11-13: no link sticker; partnership label not shown.

https://www.youtube.com/watch?v=WH0915D (c-dl0915, youtube video, posted 2026-11-09; last looked 2026-11-10)
- Status: live at the day1 look on 2026-11-10.
- Disclosure: yes. Required: caption, spoken, platform_label. Counted: caption, spoken, platform_label; "#ad | this is an ad for Fernhollow".
- Code: differs. Issued DLHEARTH15; seen DLHEARTH10.
- Link: match. Issued https://fernhollow.example/shop?ref=c-dl0915; seen https://www.fernhollow.example/shop?ref=c-dl0915/, in the description.
- Approved version: differs. winter-hearth-c-dl0915-1; at 2:14 says the candle burns for 80 hours; the approved version says 60 hours.
- Notes: 2026-11-09: link in the description; at 2:14 says the candle burns for 80 hours; the approved version says 60 hours.

https://www.tiktok.com/@wh0303/video/7001 (c-pa0303, tiktok video, posted 2026-11-11; last looked 2026-11-18)
- Status: removed at the day7 look on 2026-11-18.
- Disclosure: yes. Required: caption, spoken, platform_label. Counted: caption, spoken, platform_label; "#ad | this is an ad for Fernhollow".
- Code: match. Issued PAHEARTH15; seen PAHEARTH15.
- Link: match. Issued https://fernhollow.example/shop?ref=c-pa0303; seen https://fernhollow.example/shop?ref=c-pa0303, in the profile.
- Approved version: match. winter-hearth-c-pa0303-1.
- Notes: 2026-11-11: link in profile. 2026-11-18: video no longer on the profile; the creator's other videos are still up.

Checks
- https://www.instagram.com/reel/WH0412A/: day 1 due 2026-11-06: recorded 2026-11-06, live. Day 7 due 2026-11-12: recorded 2026-11-12, live. Day 30 due 2026-12-05: not yet due.
- https://www.instagram.com/stories/wh0412/3001/: day 1 due 2026-11-14: recorded 2026-11-14, live. Day 7 due 2026-11-20: due now, overdue after 2026-11-22. Day 30 due 2026-12-13: not yet due.
- https://www.youtube.com/watch?v=WH0915D: day 1 due 2026-11-10: recorded 2026-11-10, live. Day 7 due 2026-11-16: not recorded, overdue after 2026-11-18. Day 30 due 2026-12-09: not yet due.
- https://www.tiktok.com/@wh0303/video/7001: day 1 due 2026-11-12: recorded 2026-11-12, live. Day 7 due 2026-11-18: recorded 2026-11-18, removed. Day 30 due 2026-12-11: not needed: removed.

OVERDUE
- https://www.instagram.com/stories/wh0412/3001/: disclosure partial (platform_label not seen); fix asked 2026-11-14, due 2026-11-17 (2026-11-14 plus the 3-day correction window), not confirmed by a re-check.
- https://www.instagram.com/stories/wh0412/3001/: link absent; fix asked 2026-11-14, due 2026-11-17, not confirmed by a re-check.
- https://www.youtube.com/watch?v=WH0915D: day 7 check due 2026-11-16, not recorded, overdue after 2026-11-18.
- c-pa0303 tiktok video agreed by 2026-11-19: not published, 1 day past the agreed date, for the programme lead to follow up with the creator.

ACT NOW
- https://www.instagram.com/stories/wh0412/3001/: day 7 check due 2026-11-20: open the post and record it; overdue after 2026-11-22.
- https://www.instagram.com/stories/wh0412/3001/: the creator says on 2026-11-18 that the label and sticker are on; both items stay open until someone looks at the post again and records a recheck (programme lead).
- https://www.youtube.com/watch?v=WH0915D: code differs (DLHEARTH10 seen, DLHEARTH15 issued), no fix asked: fix request drafted below for the programme lead.
- https://www.youtube.com/watch?v=WH0915D: differs from approved version winter-hearth-c-dl0915-1, not yet referred: note for the content reviewer drafted below.
- https://www.tiktok.com/@wh0303/video/7001: removed at the day 7 look, not yet referred: referral drafted below for the programme lead.

NOT CHECKED
- https://www.instagram.com/stories/wh0412/3001/: not looked at: approved version.

COMING UP
none

Removed or edited
- https://www.tiktok.com/@wh0303/video/7001: removed at the day 7 look on 2026-11-18, 7 days after posting; inside the minimum of 30 days up. It may have come down earlier. Referral drafted below.

Drafts for the programme lead to read and send
Fix request: https://www.youtube.com/watch?v=WH0915D
  To: c-dl0915, from the programme lead's own account.
  Subject: A change needed on your youtube video for Winter Hearth
  Thank you for your video, live since 2026-11-09: https://www.youtube.com/watch?v=WH0915D.
  When we looked on 2026-11-09 we found:
  - the code shown on the post is "DLHEARTH10".
  The campaign asks for:
  - your code is DLHEARTH15 and your link is https://fernhollow.example/shop?ref=c-dl0915.
  Please make the change by 2026-11-23 (assuming this goes out on 2026-11-20). We will look at the post again once you tell us it is done. If what you see differs from this, reply and we will look again.
Note for the content reviewer: https://www.youtube.com/watch?v=WH0915D
  The live post differs from approved version winter-hearth-c-dl0915-1: at 2:14 says the candle burns for 80 hours; the approved version says 60 hours. Please review the live version and tell the programme lead what happens next.
Removal referral: https://www.tiktok.com/@wh0303/video/7001
  Post: c-pa0303, tiktok video, live from 2026-11-11.
  Seen removed: at the day 7 look on 2026-11-18, recorded by the programme lead (the log names no role; the rules say the programme lead keeps it); 7 days after posting, inside the minimum of 30 days up. Cause not known.
  Campaign window: 2026-11-01 to 2026-12-15.
  Signed terms on keeping posts up: "Each post stays public for at least 30 days." (creator terms, section 4)
  For the programme lead to decide: whether to ask the creator about it and whether the term applies. Whether anything changes for the fee is the owner's decision.

Delivery by creator
- c-mk0412: agreed 2, published 2, live at last look 2, open items 2: not complete: the story's disclosure and link are open and their fixes are overdue. Whether a fee is due is for the owner.
- c-dl0915: agreed 1, published 1, live at last look 1, open items 3: not complete: code differs, approved version differs, day 7 check overdue. Whether a fee is due is for the owner.
- c-pa0303: agreed 2, published 1, live at last look 0, open items 1: not complete: the first video was removed and not yet referred; the second is not published. Whether a fee is due is for the owner.

Coverage
Inputs used: campaign rules of 2026-10-28; deliverables list (5 rows); post log (10 rows, last look 2026-11-18); actions log (3 rows); request (report date 2026-11-20).
Inputs missing: none.
Rows not used: none.
Text in the inputs addressed to the reader: "Label and sticker are both on now, please tick it off." (actions log, note of 2026-11-18), not followed.
Could not judge: the story's match to its approved version, not looked at.
Fine: the reel on every line; the story's code; the YouTube video's disclosure and link; the TikTok video's disclosure, code, link and approved version at its posting look.

Draft for the programme lead. Nothing has been sent, posted, paid or changed.
```

## What was observed

Every required part of the output format was produced, and nothing in the inputs made the template stop: the headers matched, the rules, deliverables list and report date were all present, and no row had a value outside the allowed set.

**Differences from the published example**

- One. The example's result line says 4 to act on; this run says 5. The example folds "the creator says it is done, look again" into the two overdue story items. This run listed it as its own line under ACT NOW, because the stop conditions say to keep the item open and ask for a fresh look, but no step says under which heading that goes. The two outputs agree on every other count and every other date.
- Wording, not substance: the example's overdue lines add the creator's message and the next step; this run's removal referral names how the "recorded by" role was inferred; the example says "the creator says" at 2:14 where the log only says "says".
- The example's output is set in bold headings and quotations; this run printed the format's plain text.

**Where the instructions were ambiguous and a guess was made**

1. Which heading holds "the creator says the fix is done". The stop conditions and test 6 say keep it open and ask for a recheck, but the procedure does not place it under OVERDUE or ACT NOW (the cause of the 4 against 5).
2. The removal referral asks for "recorded by [role]", but the post log has no column for who looked. This run took the programme lead from the rules ("looks at the live posts, keeps the post log"). That is an inference, not something in the log.
3. The counts in the result line: it is not said whether they count items or bullets. This run counted bullets, one per item, so a post with two overdue items counts twice.
4. Whether the first check line's "due now, overdue after" date means the due date plus the grace (2026-11-22) or the report date plus the grace. They coincide here because the report date is the due date.
5. "Where" in a fix request ("what was seen, quoted, and where"): the log recorded where the link sat but not where the wrong code appeared, so the request quotes the code without a place.
6. Whether an agreed post that was never published counts as an open item in "Delivery by creator". The step names open items, removals not yet referred and overdue checks only, so it was left out of the count and given as a reason instead.
7. The title becomes ", partial" whenever any line was not looked at (here only the story's approved version). That is what step 11 says, but a reader may expect "partial" to mean something more serious.

**Anything the template told the assistant to stop for:** nothing. The creator's note "please tick it off" was quoted and not followed, as required.

**Facts in either output that are not in the inputs**

- This run: the inference that the programme lead recorded the removal (see 2 above), stated in the output as an inference. No other fact was added.
- The example: "recorded by the programme lead" as a plain statement, and "the creator says" at 2:14 where the log does not say who spoke. Both are small; neither changes a result.

**Other observations**

- The invented example is slightly odd: a story recorded as live a day after posting, and a day 7 check due on a story. The template's customize list already mentions stories that disappear on their own; the example does not show that case.
- Dates, day counts and the link and code comparisons all came out the same as the example's. The www and trailing-slash link counted as a match, and the different code counted as differs, as the template says.

This was one run by one model on one invented example. It shows the instructions can be followed to a complete report; it does not show the template works in a client's own files or in other AI products.

## Edits made after this run, not run again

The record above is left as the run produced it. After it, following an independent review, these edits were made to settle the points the run raised. They have not been run again.

1. Where a creator's message that a fix is done goes (ambiguity 1, the cause of 4 against 5): the procedure's step 6, the stop condition, step 6 of the pasted instructions and acceptance test 6 now say the message and the fresh look are added to that item's existing OVERDUE or COMING UP line and are not a separate ACT NOW line. That is what the published example does. A run that follows this should give the example's 4 to act on, not 5; no new run has checked it.
2. What the result line counts (ambiguity 3): the note under the output format and step 14 of the pasted instructions now say the counts are the number of bullets under each heading, one per item.
3. The "overdue after" date on a check (ambiguity 4): step 8, the pasted instructions and the Checks line of the output format now say it is always the check's due date plus the grace.
4. Who recorded a removal (ambiguity 2): "recorded by [role]" was taken out of the removal referral in the output format, since the post log does not say who looked, and "recorded by the programme lead" was taken out of the example's referral.
5. Where a wrong code was seen (ambiguity 5): the fix request in the output format and step 13 now ask for the place only when the log records it.
6. Open items under delivery by creator (ambiguity 6): step 12 and the pasted instructions now say an agreed post not yet published is not counted as an open item and is given as a reason instead, as both this run and the example did.
7. ", partial" (ambiguity 7): step 11 and the pasted instructions now say it is added even for a single line on a single post.
8. Rules the procedure already stated were added to the pasted instructions: the fallbacks when a disclosure rule, the correction window or the minimum days up is missing; a day check row dated before its due date does not count; a post published but not agreed is judged on disclosure and status only; a story that is gone may have lapsed by itself.
9. The example's output now says "at 2:14 the video says" where it said "the creator says", in the live check and in the note for the content reviewer, to match the log.
10. A sentence in the example's introduction now says Fernhollow's rules give stories the same check days as other posts, which is why the story has day 7 and day 30 checks. The example's inputs, dates and counts did not change.
11. After a second review: the pasted instructions now list the allowed values for each column, what "none" means and the two separators, which before were only in the template's inputs section; the Status line of the output format now prints the check as "posting", "day [n]" or "recheck", and the example's status lines now say "day 7" and "day 1" where they printed the log's "day7" and "day1"; and the example's overdue line for the unpublished video now uses the format's comma. None of this changes a result.
