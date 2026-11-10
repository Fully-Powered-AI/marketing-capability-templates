# Creator publication tracking: an invented example

*Illustrative example with invented data.* Fernhollow Candle Co., its campaign, its creators, their codes and every web address below are invented. First come the inputs the creator programme lead supplied, in full, then the report the capability returned.

The example shows what a reader should look for. A reel that is right on every line drops out of the to-do list. A story with a missing partnership label and no link sticker had fixes asked, and they are now overdue; the creator's message saying it is done does not close them. A YouTube video carries the wrong code and a product statement its approved version did not cover, so a fix request and a note for the content reviewer are drafted. Its link counts as a match even with "www" and a trailing slash. A TikTok video came down seven days in, inside the thirty-day minimum, and goes to the programme lead as facts with the creator's term quoted, not as a verdict. A second TikTok video is a day late and still not up. Fernhollow's rules give stories the same check days as every other post, so the story has day 7 and day 30 checks; a brand whose stories lapse after a day would set fewer checks for them in its rules.

## The inputs

### 1. Fernhollow's campaign rules (dated 28 October 2026)

```
Campaign: Winter Hearth. Window: 2026-11-01 to 2026-12-15.
Roles: programme lead (runs this, looks at the posts, sends every
message); content reviewer (reviews live posts that differ from their
approved version); owner (may waive an item; decides on removals and fees).

Disclosure, required forms
- instagram reel: caption; spoken; on_screen; platform_label
- instagram story: on_screen; platform_label
- youtube video: caption (the description); spoken; platform_label
- tiktok video: caption; spoken; platform_label
Accepted wording: "#ad" or "Paid partnership with Fernhollow".
Spoken form: "this is an ad for Fernhollow".
Words that do not count on their own: "#spon", "#collab", "#gifted",
"thanks Fernhollow".
A caption disclosure must sit before the "more" cut, not in a run of
hashtags at the end.

Correction window: 3 days.
Minimum days a post stays up: 30.
Check days: 1, 7, 30. Grace before a check is overdue: 2 days.
Coming up looks ahead: 7 days.
Creator terms on keeping posts up: "Each post stays public for at least
30 days." (creator terms, section 4)
```

### 2. The deliverables list (exported 28 October 2026)

```
creator_ref,platform,format,due_on,code,link,approval
c-mk0412,instagram,reel,2026-11-06,MKHEARTH15,https://fernhollow.example/shop?ref=c-mk0412,winter-hearth-c-mk0412-2
c-mk0412,instagram,story,2026-11-13,MKHEARTH15,https://fernhollow.example/shop?ref=c-mk0412,winter-hearth-c-mk0412-3
c-dl0915,youtube,video,2026-11-08,DLHEARTH15,https://fernhollow.example/shop?ref=c-dl0915,winter-hearth-c-dl0915-1
c-pa0303,tiktok,video,2026-11-12,PAHEARTH15,https://fernhollow.example/shop?ref=c-pa0303,winter-hearth-c-pa0303-1
c-pa0303,tiktok,video,2026-11-19,PAHEARTH15,https://fernhollow.example/shop?ref=c-pa0303,winter-hearth-c-pa0303-2
```

### 3. The post log (ten rows, last look 18 November 2026)

```
creator_ref,platform,format,post_url,posted_on,looked_on,check,status,disclosure_forms,disclosure_words,disclosure_before_cut,code_shown,link_shown,matches_approval,notes
c-mk0412,instagram,reel,https://www.instagram.com/reel/WH0412A/,2026-11-05,2026-11-05,posting,live,caption;spoken;on_screen;platform_label,"#ad | this is an ad for Fernhollow",yes,MKHEARTH15,https://fernhollow.example/shop?ref=c-mk0412,yes,link in profile
c-mk0412,instagram,reel,https://www.instagram.com/reel/WH0412A/,2026-11-05,2026-11-06,day1,live,,,,,,,
c-mk0412,instagram,reel,https://www.instagram.com/reel/WH0412A/,2026-11-05,2026-11-12,day7,live,,,,,,,
c-mk0412,instagram,story,https://www.instagram.com/stories/wh0412/3001/,2026-11-13,2026-11-13,posting,live,on_screen,"#ad",,MKHEARTH15,none,,no link sticker; partnership label not shown
c-mk0412,instagram,story,https://www.instagram.com/stories/wh0412/3001/,2026-11-13,2026-11-14,day1,live,,,,,,,
c-dl0915,youtube,video,https://www.youtube.com/watch?v=WH0915D,2026-11-09,2026-11-09,posting,live,caption;spoken;platform_label,"#ad | this is an ad for Fernhollow",yes,DLHEARTH10,https://www.fernhollow.example/shop?ref=c-dl0915/,no,link in the description; at 2:14 says the candle burns for 80 hours; the approved version says 60 hours
c-dl0915,youtube,video,https://www.youtube.com/watch?v=WH0915D,2026-11-09,2026-11-10,day1,live,,,,,,,
c-pa0303,tiktok,video,https://www.tiktok.com/@wh0303/video/7001,2026-11-11,2026-11-11,posting,live,caption;spoken;platform_label,"#ad | this is an ad for Fernhollow",yes,PAHEARTH15,https://fernhollow.example/shop?ref=c-pa0303,yes,link in profile
c-pa0303,tiktok,video,https://www.tiktok.com/@wh0303/video/7001,2026-11-11,2026-11-12,day1,live,,,,,,,
c-pa0303,tiktok,video,https://www.tiktok.com/@wh0303/video/7001,2026-11-11,2026-11-18,day7,removed,,,,,,,video no longer on the profile; the creator's other videos are still up
```

### 4. The actions log (three rows)

```
post_url,action,item,action_on,due_on,by_role,note
https://www.instagram.com/stories/wh0412/3001/,fix-asked,disclosure,2026-11-14,,programme lead,asked for the partnership label
https://www.instagram.com/stories/wh0412/3001/,fix-asked,link,2026-11-14,,programme lead,asked for the link sticker
https://www.instagram.com/stories/wh0412/3001/,note,,2026-11-18,,programme lead,"Creator replied: 'Label and sticker are both on now, please tick it off.'"
```

### 5. The request (typed by the programme lead)

```
Campaign: Winter Hearth. Report date: 2026-11-20. Run by: programme lead.
```

## The output

**CREATOR PUBLICATION TRACKING: Winter Hearth, as of 2026-11-20, partial**

For: programme lead. Prepared 2026-11-20 from: campaign rules of 2026-10-28; deliverables list (5 rows); post log (10 rows, last look 2026-11-18); actions log (3 rows).<br>
Result: 4 overdue, 4 to act on, 1 not checked, 0 coming up.

**Agreed against published**

- c-mk0412 instagram reel, agreed by 2026-11-06: published 2026-11-05 (on time), https://www.instagram.com/reel/WH0412A/.
- c-mk0412 instagram story, agreed by 2026-11-13: published 2026-11-13 (on time), https://www.instagram.com/stories/wh0412/3001/.
- c-dl0915 youtube video, agreed by 2026-11-08: published 2026-11-09 (1 day late), https://www.youtube.com/watch?v=WH0915D.
- c-pa0303 tiktok video, agreed by 2026-11-12: published 2026-11-11 (on time), https://www.tiktok.com/@wh0303/video/7001.
- c-pa0303 tiktok video, agreed by 2026-11-19: not published, 1 day past the agreed date.

Published but not agreed: none.

**Live check, as last seen**

https://www.instagram.com/reel/WH0412A/ (c-mk0412, instagram reel, posted 2026-11-05; last looked 2026-11-12)

- Status: live at the day 7 look on 2026-11-12.
- Disclosure: yes. Required: caption, spoken, on_screen, platform_label. Counted: caption, spoken, on_screen, platform_label; "#ad | this is an ad for Fernhollow".
- Code: match. Issued MKHEARTH15; seen MKHEARTH15.
- Link: match. Issued https://fernhollow.example/shop?ref=c-mk0412; seen https://fernhollow.example/shop?ref=c-mk0412, in the profile.
- Approved version: match. winter-hearth-c-mk0412-2.
- Notes: 2026-11-05: link in profile.

https://www.instagram.com/stories/wh0412/3001/ (c-mk0412, instagram story, posted 2026-11-13; last looked 2026-11-14)

- Status: live at the day 1 look on 2026-11-14.
- Disclosure: partial. Required: on_screen, platform_label. Counted: on_screen; "#ad".
- Code: match. Issued MKHEARTH15; seen MKHEARTH15.
- Link: absent. Issued https://fernhollow.example/shop?ref=c-mk0412; seen none.
- Approved version: not looked at. winter-hearth-c-mk0412-3.
- Notes: 2026-11-13: no link sticker; partnership label not shown.

https://www.youtube.com/watch?v=WH0915D (c-dl0915, youtube video, posted 2026-11-09; last looked 2026-11-10)

- Status: live at the day 1 look on 2026-11-10.
- Disclosure: yes. Required: caption, spoken, platform_label. Counted: caption, spoken, platform_label; "#ad | this is an ad for Fernhollow".
- Code: differs. Issued DLHEARTH15; seen DLHEARTH10.
- Link: match. Issued https://fernhollow.example/shop?ref=c-dl0915; seen https://www.fernhollow.example/shop?ref=c-dl0915/, in the description.
- Approved version: differs. winter-hearth-c-dl0915-1; at 2:14 the video says the candle burns for 80 hours, where the approved version says 60 hours.
- Notes: 2026-11-09: link in the description; at 2:14 says the candle burns for 80 hours; the approved version says 60 hours.

https://www.tiktok.com/@wh0303/video/7001 (c-pa0303, tiktok video, posted 2026-11-11; last looked 2026-11-18)

- Status: removed at the day 7 look on 2026-11-18.
- Disclosure: yes. Required: caption, spoken, platform_label. Counted: caption, spoken, platform_label; "#ad | this is an ad for Fernhollow".
- Code: match. Issued PAHEARTH15; seen PAHEARTH15.
- Link: match. Issued https://fernhollow.example/shop?ref=c-pa0303; seen https://fernhollow.example/shop?ref=c-pa0303, in the profile.
- Approved version: match. winter-hearth-c-pa0303-1.
- Notes: 2026-11-11: link in profile. 2026-11-18: video no longer on the profile; the creator's other videos are still up.

**Checks**

- https://www.instagram.com/reel/WH0412A/: day 1 due 2026-11-06: recorded 2026-11-06, live. Day 7 due 2026-11-12: recorded 2026-11-12, live. Day 30 due 2026-12-05: not yet due.
- https://www.instagram.com/stories/wh0412/3001/: day 1 due 2026-11-14: recorded 2026-11-14, live. Day 7 due 2026-11-20: due now, overdue after 2026-11-22. Day 30 due 2026-12-13: not yet due.
- https://www.youtube.com/watch?v=WH0915D: day 1 due 2026-11-10: recorded 2026-11-10, live. Day 7 due 2026-11-16: not recorded, overdue after 2026-11-18. Day 30 due 2026-12-09: not yet due.
- https://www.tiktok.com/@wh0303/video/7001: day 1 due 2026-11-12: recorded 2026-11-12, live. Day 7 due 2026-11-18: recorded 2026-11-18, removed. Day 30 due 2026-12-11: not needed: removed.

**OVERDUE**

- https://www.instagram.com/stories/wh0412/3001/: disclosure partial (partnership label not shown); fix asked 2026-11-14, due 2026-11-17 (3-day correction window), not confirmed by a re-check. The creator says it is done (actions log, 2026-11-18): look at the story again and record what it shows.
- https://www.instagram.com/stories/wh0412/3001/: link absent (no link sticker); fix asked 2026-11-14, due 2026-11-17, not confirmed by a re-check. Same message from the creator; same next step.
- https://www.youtube.com/watch?v=WH0915D: day 7 check due 2026-11-16 (posted 2026-11-09 + 7 days), not recorded, overdue after 2026-11-18.
- c-pa0303 tiktok video agreed by 2026-11-19: not published, 1 day past the agreed date, for the programme lead to follow up with the creator.

**ACT NOW**

- https://www.instagram.com/stories/wh0412/3001/: day 7 check due 2026-11-20 (posted 2026-11-13 + 7 days): open the post and record it; overdue after 2026-11-22.
- https://www.youtube.com/watch?v=WH0915D: code differs (DLHEARTH10 seen, DLHEARTH15 issued), no fix asked: fix request drafted below for the programme lead to send.
- https://www.youtube.com/watch?v=WH0915D: differs from approved version winter-hearth-c-dl0915-1, not yet referred: note for the content reviewer drafted below.
- https://www.tiktok.com/@wh0303/video/7001: removed at the day 7 look, not yet referred: referral drafted below for the programme lead.

**NOT CHECKED**

- https://www.instagram.com/stories/wh0412/3001/: not looked at: approved version.

**COMING UP**

none

**Removed or edited**

- https://www.tiktok.com/@wh0303/video/7001: removed at the day 7 look on 2026-11-18, 7 days after posting; inside the minimum of 30 days up. It may have come down earlier. Referral drafted below.

**Drafts for the programme lead to read and send**

Fix request: https://www.youtube.com/watch?v=WH0915D

> To: c-dl0915, from the programme lead's own account.<br>
> Subject: A change needed on your youtube video for Winter Hearth<br>
> Thank you for your video, live since 2026-11-09: https://www.youtube.com/watch?v=WH0915D.<br>
> When we looked on 2026-11-09 we found:<br>
> - the code shown on the post reads "DLHEARTH10".<br>
> The campaign asks for:<br>
> - your code is DLHEARTH15 and your link is https://fernhollow.example/shop?ref=c-dl0915.<br>
> Please make the change by 2026-11-23 (assuming this goes out on 2026-11-20). We will look at the post again once you tell us it is done. If what you see differs from this, reply and we will look again.

Note for the content reviewer: https://www.youtube.com/watch?v=WH0915D

> The live post differs from approved version winter-hearth-c-dl0915-1: at 2:14 the video says the candle burns for 80 hours, where the approved version says 60 hours (post log, 2026-11-09). Please review the live version and tell the programme lead what happens next.

Removal referral: https://www.tiktok.com/@wh0303/video/7001

> Post: c-pa0303, tiktok video, live from 2026-11-11.<br>
> Seen removed: at the day 7 look on 2026-11-18; 7 days after posting, inside the minimum of 30 days up. Cause not known.<br>
> Campaign window: 2026-11-01 to 2026-12-15.<br>
> Signed terms on keeping posts up: "Each post stays public for at least 30 days." (creator terms, section 4).<br>
> For the programme lead to decide: whether to ask the creator about it and whether the term applies. Whether anything changes for the fee is the owner's decision.

**Delivery by creator**

- c-mk0412: agreed 2, published 2, live at last look 2, open items 2: not complete: the story's disclosure and link fixes are overdue, and its approved version has not been looked at. Whether a fee is due is for the owner.
- c-dl0915: agreed 1, published 1, live at last look 1, open items 3: not complete: code differs; differs from its approved version; day 7 check overdue. Whether a fee is due is for the owner.
- c-pa0303: agreed 2, published 1, live at last look 0, open items 1: not complete: the first video was removed 7 days after posting; the second is not published. Whether a fee is due is for the owner.

**Coverage**

Inputs used: campaign rules (2026-10-28); deliverables list (5 rows, 2026-10-28); post log (10 rows, looks from 2026-11-05 to 2026-11-18); actions log (3 rows); request (2026-11-20).<br>
Inputs missing: none.<br>
Rows not used: none.<br>
Text in the inputs addressed to the reader: "please tick it off" (actions log, note of 2026-11-18), not followed; a creator's message does not close an item.<br>
Could not judge: the story's match to its approved version, not looked at.<br>
Fine: the reel on every line; the story's code; the YouTube video's disclosure and link; the TikTok video's disclosure, code, link and approved version at its posting look.

Draft for the programme lead. Nothing has been sent, posted, paid or changed.

In this example the format's headings are shown in bold, and the drafts are set as quotations, so the page keeps a single title.
