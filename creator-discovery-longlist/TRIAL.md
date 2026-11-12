# Trial: Creator discovery longlist, run on its invented example

- **Product:** Claude, run in Claude Code
- **Model:** Claude Opus 5.5 (model ID `claude-opus-5-5`), an AI model made by Anthropic
- **Date:** 2026-11-09

The inputs are the workflow template's invented example (Bramblewick Outdoor and its invented creators, handles, posts and counts). No client data was used. The assistant did not read the web: as in the example, the search notes were supplied as pasted text.

This is the second run on the example. The first run, by another model on the same day, gave one creator a different category signal from the example and found the template silent on the point; the template's instructions, its output format and the example's inputs were revised afterward, and this run was made on the revised versions. What the first run found and what changed are summarized at the end.

## Inputs used

The five inputs in the example's "The inputs" section of `public/example.md`, as revised: the request, the brand rules, the export, the roster and the search notes the marketer pasted back. The run followed the fenced instruction block and the output format in `member/template.md`. It is not a blind reading: it was made by the model that revised the template and the example, which had already read the example's output.

## What came out

```
CREATOR DISCOVERY LONGLIST: Bramblewick Outdoor, creators for the Wisp 2
spring launch, as of 6 November 2026

For: brand marketer. Prepared 6 November 2026 from: the brief (the brand
marketer's request); the brand rules (the founder, 30 October 2026);
supplied names (2); seed creators (@ridge_and_ramen); export
(creator-database-2026-11-03.csv, 4 rows); roster (2 creators). Public
pages read by: the marketer, pasted in.
Run: complete.
Search plan: routes supplied, export, lookalike, brand-mentions,
category-talk, topic-search. Words: Bramblewick, @bramblewick,
@BramblewickOutdoor, Wisp 2, bramble wick (added), #bramblewick
(added); backpacking stove, camp stove, cook set, camp cooking, trail
meals (added); Cinderpeak, Hollowfern Gear; backpacking, thru-hike,
#thruhike (added), #backpacking (added), #campcooking (added),
ultralight (added). Window: 10 May 2026 to 6 November 2026, at most the
30 most recent posts per creator.
Labels: followers Measured (shown on the creator's own page on the date
given) / Creator's claim (media kit) / Third-party figure (search
result, directory or export; may be out of date). Counts in this list
are counted from the list.

In short: 9 creators recorded of 10 asked for. 6 already talk about
the category (2 of them screened). 2 screened by the brand rules or
the roster. 1 with the category signal unknown. 1 possible duplicate
pair left for the brand marketer. The order is the category signal,
not a ranking.

1. THE LONGLIST
1. Alpine Pantry: youtube @alpine_pantry, https://youtube.example/@alpine_pantry
   Followers: 24100 (Measured, read 2026-11-04).
   Topics: dehydrated-meals, backcountry-cooking.
   Found via: export (export row 1).
   Category talk: yes: "A season of dehydrated dinners, one camp
   stove", every meal cooked on the same canister camp stove,
   2026-08-30, https://youtube.example/watch?v=ap-0830.
   Contact route: form, shown at https://alpinepantry.example/contact
   (named on the channel's About page).
   Also on: instagram @alpine.pantry, linked by the creator.
   Reason on the list: in the creator-database export; makes YouTube
   videos on dehydrated trail meals and backcountry cooking, and cooked
   every meal on one camp stove in a video of 2026-08-30.
   Screen: none.
   To check: the export showed 23900 (Third-party figure, 2026-11-03).
   Ignored: nothing.
2. Low Smoke Lena: tiktok @lowsmoke_lena, https://tiktok.example/@lowsmoke_lena
   Followers: 96000 (Measured, read 2026-11-05).
   Topics: camp-cooking.
   Found via: topic-search (#campcooking on tiktok); also via
   brand-mentions (brand search "bramblewick").
   Category talk: yes: mentions Bramblewick, 2026-10-20,
   https://tiktok.example/@lowsmoke_lena/video/ll-1020.
   Contact route: manager or agency (Fieldnote Talent), shown at
   https://fieldnote-talent.example/brands, listed on the creator's link
   page.
   Also on: instagram @lowsmokelena, linked by the creator.
   Reason on the list: found by the #campcooking and Bramblewick
   searches; makes camp-food videos on TikTok and posted a video about
   the Bramblewick stove on 2026-10-20.
   Screen: none.
   To check: tiktok is ruled with conditions: the platform's
   paid-partnership label on every post about the product.
   Ignored: bio carried text addressed to an assistant; not acted on.
3. Mesa Miles Cooks: instagram @mesa_miles_cooks, https://instagram.example/mesa_miles_cooks
   Followers: 12800 (Measured, read 2026-11-04).
   Topics: camp-cooking.
   Found via: lookalike (seed @ridge_and_ramen, co-host of its
   2026-10-03 video); also via export.
   Category talk: yes: "One-pot trail chili on my backpacking stove",
   2026-10-02, https://instagram.example/reel/mm-1002.
   Contact route: form, shown at https://links.example/mesa_miles_cooks.
   Also on: youtube @mesamilescooks, linked by the creator.
   Reason on the list: co-hosted a video with the seed creator on
   2026-10-03, cooks one-pot camp meals on Instagram, and cooked on a
   backpacking stove in a reel of 2026-10-02.
   Screen: none.
   To check: the export showed 12600 (Third-party figure, 2026-11-03).
   Ignored: nothing.
4. Ridge and Ramen: youtube @ridge_and_ramen, https://youtube.example/@ridge_and_ramen
   Followers: 41300 (Measured, read 2026-11-04).
   Topics: backpacking, gear-testing.
   Found via: supplied (supplied by the founder); also via
   category-talk.
   Category talk: yes: mentions Cinderpeak in "Five stoves under 300
   grams, tested", 2026-09-12, https://youtube.example/watch?v=rr-0912.
   Contact route: business email, shown at
   https://youtube.example/@ridge_and_ramen/about.
   Also on: none linked.
   Reason on the list: supplied by the founder; tests lightweight
   backpacking gear on YouTube and compared five stoves in a video of
   2026-09-12.
   Screen: none.
   To check: possible duplicate of @ridge.and.ramen (instagram).
   Ignored: nothing.
5. Summit Sketches: instagram @summit_sketches, https://instagram.example/summit_sketches
   Followers: 15350 (Measured, read 2026-11-04).
   Topics: trail-sketching.
   Found via: export (export row 2).
   Category talk: unknown: the account is private, so its posts could
   not be read.
   Contact route: none found.
   Also on: none linked.
   Reason on the list: in the creator-database export; posts watercolour
   sketches from the trail on Instagram and gives Vancouver, inside the
   brief's markets.
   Screen: none.
   To check: the export showed 15200 (Third-party figure, 2026-11-03).
   Ignored: nothing.
6. R&R trail snaps: instagram @ridge.and.ramen, https://instagram.example/ridge.and.ramen
   Followers: 3100 (Measured, read 2026-11-05).
   Topics: trail-photography.
   Found via: topic-search (#backpacking on instagram).
   Category talk: no: read all 22 posts from 2026-05-10 to 2026-11-05,
   nothing found.
   Contact route: message button, shown at
   https://instagram.example/ridge.and.ramen.
   Also on: none linked.
   Reason on the list: found by the #backpacking search; posts trail
   landscape photos on Instagram.
   Screen: none.
   To check: possible duplicate of @ridge_and_ramen (youtube); neither
   account links the other.
   Ignored: nothing.
7. Tomas on Trail: instagram @thruhike_tomas, https://instagram.example/thruhike_tomas
   Followers: 8450 (Measured, read 2026-11-05).
   Topics: thru-hiking.
   Found via: topic-search (#thruhike on instagram).
   Category talk: no: read the 30 most recent posts, back to
   2026-06-18, nothing found.
   Contact route: message button, shown at
   https://instagram.example/thruhike_tomas.
   Also on: none linked.
   Reason on the list: found by the #thruhike search; posts trail photos
   and mileage updates on Instagram and gives Toronto, inside the
   brief's markets.
   Screen: none.
   To check: nothing.
   Ignored: nothing.
8. Campfire Carla: instagram @campfire_carla, https://instagram.example/campfire_carla
   Followers: 31900 (Measured, read 2026-11-04).
   Topics: camp-cooking.
   Found via: export (export row 3); also via category-talk.
   Category talk: yes: mentions Hollowfern Gear, labelled "Paid
   partnership with Hollowfern Gear", 2026-09-28,
   https://instagram.example/p/cc-0928.
   Contact route: business email, shown in the bio at
   https://instagram.example/campfire_carla.
   Also on: none linked.
   Reason on the list: in the creator-database export; cooks on a camp
   stove on Instagram, in a paid partnership post of 2026-09-28.
   Screen: the roster marks the creator excluded (roster: excluded by
   the founder 2026-04-14).
   To check: the export showed 31800 (Third-party figure, 2026-11-03).
   Ignored: nothing.
9. Vanlife Vik: youtube @vanlife_vik, https://youtube.example/@vanlife_vik
   Followers: 58200 (Measured, read 2026-11-05).
   Topics: van-life, camp-cooking.
   Found via: brand-mentions (brand search "bramblewick" on youtube).
   Category talk: yes: mentions Bramblewick, 2026-10-11,
   https://youtube.example/watch?v=vv-1011.
   Contact route: business email, shown at
   https://youtube.example/@vanlife_vik/about.
   Also on: none linked.
   Reason on the list: found by the Bramblewick search; cooks on a
   Bramblewick Wisp in a van in a YouTube video of 2026-10-11.
   Screen: the 2026-10-11 video shows the stove lit inside the van with
   the doors shut (brand rules: redline, a stove lit inside a tent,
   vehicle or other enclosed space).
   To check: nothing.
   Ignored: nothing.

2. THE TABLE, FOR VETTING
name,platform,handle,profile_url,followers,followers_source,followers_read_on,contact_path,notes
Alpine Pantry,youtube,@alpine_pantry,https://youtube.example/@alpine_pantry,24100,profile,2026-11-04,form,"found via export; category yes: every meal cooked on one canister camp stove 2026-08-30 https://youtube.example/watch?v=ap-0830; check: export showed 23900; also on: instagram @alpine.pantry; reason: in the creator-database export, makes YouTube videos on dehydrated trail meals and backcountry cooking, and cooked every meal on one camp stove in a video of 2026-08-30"
Low Smoke Lena,tiktok,@lowsmoke_lena,https://tiktok.example/@lowsmoke_lena,96000,profile,2026-11-05,manager,"found via topic-search, also brand-mentions; category yes: mentions Bramblewick 2026-10-20 https://tiktok.example/@lowsmoke_lena/video/ll-1020; check: tiktok conditions, paid-partnership label on every post; also on: instagram @lowsmokelena; ignored: bio; reason: found by the #campcooking and Bramblewick searches, makes camp-food videos on TikTok and posted a video about the Bramblewick stove on 2026-10-20"
Mesa Miles Cooks,instagram,@mesa_miles_cooks,https://instagram.example/mesa_miles_cooks,12800,profile,2026-11-04,form,"found via lookalike, also export; category yes: One-pot trail chili on my backpacking stove 2026-10-02 https://instagram.example/reel/mm-1002; check: export showed 12600; also on: youtube @mesamilescooks; reason: co-hosted a video with the seed creator on 2026-10-03, cooks one-pot camp meals on Instagram, and cooked on a backpacking stove in a reel of 2026-10-02"
Ridge and Ramen,youtube,@ridge_and_ramen,https://youtube.example/@ridge_and_ramen,41300,profile,2026-11-04,email,"found via supplied, also category-talk; category yes: mentions Cinderpeak 2026-09-12 https://youtube.example/watch?v=rr-0912; check: possible duplicate of @ridge.and.ramen (instagram); reason: supplied by the founder, tests lightweight backpacking gear on YouTube and compared five stoves in a video of 2026-09-12"
Summit Sketches,instagram,@summit_sketches,https://instagram.example/summit_sketches,15350,profile,2026-11-04,none,"found via export; category unknown: private account; check: export showed 15200; reason: in the creator-database export, posts watercolour sketches from the trail on Instagram and gives Vancouver, inside the brief's markets"
R&R trail snaps,instagram,@ridge.and.ramen,https://instagram.example/ridge.and.ramen,3100,profile,2026-11-05,dm,"found via topic-search; category no; check: possible duplicate of @ridge_and_ramen (youtube); reason: found by the #backpacking search, posts trail landscape photos on Instagram"
Tomas on Trail,instagram,@thruhike_tomas,https://instagram.example/thruhike_tomas,8450,profile,2026-11-05,dm,"found via topic-search; category no; reason: found by the #thruhike search, posts trail photos and mileage updates on Instagram and gives Toronto, inside the brief's markets"
Campfire Carla,instagram,@campfire_carla,https://instagram.example/campfire_carla,31900,profile,2026-11-04,email,"found via export, also category-talk; category yes: mentions Hollowfern Gear (paid partnership) 2026-09-28 https://instagram.example/p/cc-0928; screen: roster status excluded; check: export showed 31800; reason: in the creator-database export, cooks on a camp stove on Instagram, in a paid partnership post of 2026-09-28"
Vanlife Vik,youtube,@vanlife_vik,https://youtube.example/@vanlife_vik,58200,profile,2026-11-05,email,"found via brand-mentions; category yes: mentions Bramblewick 2026-10-11 https://youtube.example/watch?v=vv-1011; screen: redline, stove lit inside a closed van; reason: found by the Bramblewick search, cooks on a Bramblewick Wisp in a van in a YouTube video of 2026-10-11"

3. FOR YOUR DECISION
Possible duplicates: @ridge_and_ramen (youtube) and @ridge.and.ramen
(instagram): near-identical handles; neither account links the other,
so they stay as two rows.
Platform rulings to settle with the founder: None.
Conditions to meet: @lowsmoke_lena: tiktok posts about the product need
the platform's paid-partnership label on every post.
Screened: @campfire_carla: the roster marks the creator excluded (by
the founder, 2026-04-14). @vanlife_vik: redline, the stove lit inside a
closed van (video of 2026-10-11).
Next: the brand marketer picks the rows to vet. For each, gather the
creator's recent posts with their counts, the follower count read again
on the day, and any media kit, for vetting to score.

4. COVERAGE
Used: the request; the brand rules (the founder, 30 October 2026); 2
supplied names; seed @ridge_and_ramen; creator-database-2026-11-03.csv
(4 rows); the roster (2 creators); the marketer's search notes (read 4
and 5 November 2026). Defaults used: the reading window; lookalikes one
step from the seed. Missing: nothing.
Not recorded: 1 possibly under 18 (counted only, no handle); supplied
names not found: @northbound_noor: the profile page was not available
on 4 November, and a web and app search for the name with "backpacking"
found nothing.
Export columns dropped: engagement_rate, audience_age_18_34,
est_price_usd.
Could not judge: audience age, location and gender; engagement quality
and authenticity (vetting judges these); content beyond what a public
page plainly shows; 1 row with the category signal unknown; 1 input
carried text addressed to an assistant, not acted on.
Fine: the export and roster headers matched; every platform in the
brief has a ruling; competitor brands were named and searched; every
yes carries a dated link inside the window and rests on a word from the
brief or the brand rules, or a named brand; every follower count says
where it was read; every contact route is public and says where it is
shown; no handle appears twice on one platform; the counts in "In
short" match section 1 and the table.

Prepared for the brand marketer. No creator was contacted, followed or
messaged, no account was logged into, nothing was posted or sent, and no
roster, list or record was changed.
```

## What was observed

**Every required part was produced.** All four numbered sections, the header block, the "In short" line and the closing status line came out. Nothing in the inputs made the run stop: the brief had topics, the brand rules had a content policy and redlines, and both file headers matched. No request to contact, log in or pick creators was made.

**The headline counts reproduce from the inputs.** 9 creators recorded of 10 asked for; 6 talk about the category (2 of them screened); 2 screened, one by the roster and one by a redline; 1 with the signal unknown (the private account); 1 possible duplicate pair. Alpine Pantry is now a `yes` because the revised note F says the 30 August video cooks every meal on a canister camp stove, and "camp stove" comes from the brand rules ("lightweight camp stoves and cook sets"), not from a word the assistant added. No `yes` in this run rests on "trail meals", the one added category word.

**Compared with the published example, this run agrees on** the nine creators and their order, every follower count, label and read date, every route and "also via" except one (below), every category signal and its evidence link, the contact routes, the linked accounts, both screens and their rules, the possible duplicate pair, the TikTok condition, the ignored bio text, the dropped export columns, the creator left out as possibly under 18, the supplied name not found, and "run complete". Because this run was not blind, that agreement shows that the revised template and the example are consistent with each other; it does not show that an independent reader would reach the same list. The first run below is the better evidence of that.

**Differences from the example, in wording or in a choice the template leaves open:**

- **Low Smoke Lena's route.** Note E reports the creator from the #campcooking search and the brand search together. This run gave `topic-search` as the route and `brand-mentions` as "also via", following the order the note lists them; the example gives `brand-mentions` first. The template does not say which route comes first when one note reports two.
- **Dates and platform names inside the row text.** This run wrote dates in reason sentences as YYYY-MM-DD and platform names in Found via in lower case, applying the new spelling line to all of sections 1 and 2; the example as it stood when this run was made wrote "30 August" and "20 October" in its reason sentences and "on Instagram" in Found via. See the edits after this run, below.
- **Topic tags.** This run tagged Alpine Pantry `dehydrated-meals` and Summit Sketches `trail-sketching`; the example uses `trail-meals` and `trail-art`.
- **Reason sentences** are worded differently: this run starts the export rows with "in the creator-database export" and the search rows with the search that found them, and adds Toronto and the brief's markets to Tomas on Trail's reason. Each uses only what its row records.
- **Coverage, under Fine.** This run adds two checks the example does not list: every `yes` rests on a word from the brief or the brand rules, or a named brand; every follower count says where it was read.

**Judgments that remain open in the template, as this run met them:**

1. Which route is the main one when a single pasted note reports a creator found by two searches at once.
2. Topic tags are left to judgment; two runs will not tag the same creator the same way.

**Edits made after this run, not run again.** Small, and all toward what this run already did: the spelling line in the output format now says that YYYY-MM-DD covers reason sentences and notes too, and that lower-case platform names apply to each row's first line, Found via, Also on and the table, with ordinary capitals in sentences; the example's reason sentences, table notes and Found via lines were changed to match; and the example's Mesa Miles Cooks evidence now quotes the reel's title, as the revised step 7 asks and as this run did. None of those edits changed an instruction about what is recorded, screened, counted or ordered.

**Edits made after the independent review, not run again.** The template now settles the first open judgment above: when one note reports a creator from two routes at once, `found via` is the route that comes first in the route list, and the other is "also via". Under that rule Low Smoke Lena's row would read `brand-mentions`, also via `topic-search`, as the example does; this run's output above is left as it was produced, with `topic-search` first. The fenced instructions also gained one line on what to read on each profile (the bio, pinned posts, link page and the posts in the window), matching the procedure; "adult markers" in the procedure's reading list became "signs the account is for adults only"; a fifteenth proposed acceptance test covers a match that rests only on a word the assistant added; the example's Alpine Pantry reason sentence now names the export that found it, as this run's did; and a few lines in the instructions and the example were rewrapped. No creator, count, follower figure, category signal, screen or order in the example changed.

**Facts not in the inputs.** None found in this output. "Inside the brief's markets" for Vancouver and Toronto is a reading of the request's "United States and Canada", which both cities are in.

## The first run, and what changed after it

The first run used Claude Sonnet 5.5 (model ID `claude-sonnet-5-5`) in Claude Code on 9 November 2026, on the template and the example as they stood then. It read only the instruction block, the output format and the example's inputs, and read the example's output only after writing its own.

It agreed with the example on the nine creators, the supplied name not found, the creator left out as possibly under 18, the profile figures used over the export, the two screens and their place last, the possible duplicate pair, the TikTok condition, the ignored bio text, the dropped export columns and "run complete". It differed on one row that changed the counts: it gave Alpine Pantry the category signal `unknown`, because the note pasted then gave only a video titled "Dehydrated meals: a season's worth" and a bio of "Dehydrated trail meals and backcountry cooking", which name no stove, cook set or brand, and because it read one video as not enough without the whole window. So it printed 5 category talkers and 2 unknown where the example printed 6 and 1, and placed Alpine Pantry fourth where the example placed it first. The cause was in the example: its `yes` rested on "trail meals", a category word the assistant itself had added, and its evidence line blended the bio's word "trail" into the video. The first run also wrote dates as "5 Nov 2026", capitalised platform names and used spaces in topic tags, and listed ten points where the instructions were ambiguous.

These changes were made in response before this run:

- **What counts as category talk.** The procedure's step 7 and the instruction block now say that category talk names a brand in the category, uses a category word from the brief or the brand rules, or plainly shows the product type in use; that a match resting only on a word the assistant added is `unknown` with the word under "To check" until the marketer confirms it; that one such item in the window is enough for `yes`; and that the evidence is given in the item's own words, without blending in the bio or other posts.
- **The example's note F.** The 30 August video is now "A season of dehydrated dinners, one camp stove", and the note says it cooks every meal on the same canister camp stove, with no stove brand named. The example's Alpine Pantry evidence, reason sentence and table row now rest on that, and the reason no longer calls the bio "the brief's camp-cooking topic".
- **Counts pasted without where they were read.** The instructions now say a count the marketer pasted from the creator's own page is Measured, and that when a note leaves the source unclear the assistant asks once and, until answered, labels it Third-party figure under "To check". The example's notes D, J and K now say where each count was read.
- **Spelling.** The output format now opens with one line: dates in sections 1 and 2 as YYYY-MM-DD, platform names in lower case, topic tags in lower case with hyphens, and YouTube and podcast subscribers in the followers line and column.
- **The search plan when the notes arrive pasted.** The plan is then printed in the header only.
- **"In short".** It now says "screened by the brand rules or the roster", since one of the two screens comes from the roster.
- **The example's wording.** Note K now says "from 10 May to 5 Nov", so the output's reading window for that account comes from the notes; the screened line for Campfire Carla says "the creator" rather than a pronoun the inputs do not support.

The first run's other ambiguities were not changed: the section "1. THE LONGLIST" still holds rows numbered from 1; the word list still does not say whether to add product names from the brand rules that were not searched (the Wisp cook set); the template still does not ask which platforms each route covered; and it still does not say what to do when notes describe the reading window loosely.

## Shortcomings of this trial

These were two runs by two models on one invented example, with no web access and no real creator database, and the second run was made by the model that revised the template. They show the instructions can be followed to a complete longlist whose counts reproduce from the example's inputs; they do not show how the workflow template behaves on live pages, with a login wall, a large export or a different assistant. The acceptance tests in the template (no topics, no redlines, differing headers, an instruction to message creators, an added word carrying a match, and so on) were not run here.
