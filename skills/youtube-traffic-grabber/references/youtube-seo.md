# YouTube SEO — Search and Discovery Optimization

YouTube SEO is the discovery half of the funnel (`youtube-traffic-doctrine.md`): getting the right viewer to watch. It is not about "links" — YouTube's outbound links are nofollow and carry no SEO equity. It is about ranking a *video* on YouTube's search/suggested/browse surfaces (and, as a bonus, inside Google), so that an interested human finds it and watches.

Everything here is anchored on YouTube's own performance/discovery FAQ. Where popular advice contradicts the FAQ — most notably on tags — this page corrects it rather than repeating the folklore.

The order of this page reflects the actual order of importance: **retention/AVD first, then CTR (title + thumbnail), then search-intent matching (title/description/spoken content), then tags last (minor).** Most blogs invert this. Don't.

---

## First principle: rank per-video, per-audience, on performance

YouTube ranks individual videos for individual viewers based on **performance and relevance** — not channel reputation, not raw view count, not how long you've uploaded. Two consequences shape all optimization:

- **There is nothing to "trick."** The system mostly learns from whether viewers chose to watch and how satisfied they were. You optimize by genuinely satisfying the viewer who searched, not by stuffing metadata.
- **Optimization is per-video.** Each video earns its own ranking for its own query/audience. A single great video can carry a young channel; a weak one isn't rescued by channel age.

---

## Keyword and search-intent research

The tutorial and data-explainer formats live or die on **matching a real search intent**. A viewer who searched "how to find a site's hidden API" and lands on your exact tutorial is the warmest possible traffic for the matching tool CTA.

### How to pull the data — never local scraping

Keyword and competitor research means hitting YouTube data, and the hard rule applies: **no scraping from your local machine.** Pull research data through:

- **The YouTube Data API v3** — the official, documented REST API. `search.list` (find videos/channels for a query), `videos.list` (stats/metadata on specific videos), `captions` (transcript availability). This is an official API, not scraping. Mind the daily quota (search is expensive); cache results.
- **Managed keyword tools** — TubeBuddy, vidIQ, Ahrefs' YouTube keyword tool, Keywords Everywhere. These are SaaS that do the data collection server-side.
- **YouTube's own autosuggest** — typing a seed term into the YouTube search box surfaces real queries people make. Read it manually in a browser; do not script it from local. For volume at scale, route through the Data API or a managed tool.
- **A hosted scraping platform** — if a bespoke pull is needed, run it on a hosted platform/cloud Actor, never a local crawler.

If a request turns into "build me a YouTube scraper," that is a scraper-engineering job (tool ladder, managed APIs, anti-bot) — hand it off. This page only specifies *what* to research, not how to engineer the pull.

### What to research

1. **Seed → expand.** Start from the asset's value proposition ("scrape prices from site X", "tool A vs tool B", "build an MCP server"). Expand with autosuggest and a keyword tool into the real phrasings people search.
2. **Intent classification.** Sort candidates into *problem/how-to* (highest conversion — the viewer wants a solution your asset provides), *comparison* (warm — "X vs Y"), and *informational/explainer* (top-of-funnel, brand). Weight the catalog toward problem/how-to for traffic-to-site.
3. **Competition read.** For a target query, look at what already ranks: are the top results strong and recent, or stale and thin? A query with weak incumbents and clear intent is a slot. Use `search.list` + `videos.list` to read titles, view-to-recency, and engagement.
4. **Demand vs. winnability.** A lower-volume query you can rank #1 for, with sharp intent, beats a high-volume query buried on page 3. Niche queries are exactly this — modest volume, sharp intent, weak competition.

---

## Retention / AVD — the dominant signal

The single most important thing YouTube SEO can influence is **whether viewers watch, and how much.** The system uses both **absolute and relative watch time**, with the rule of thumb: relative watch time matters more for short videos, absolute for long videos. Likes, dislikes, and "not interested" contribute only "somewhat"; watch is the heavyweight.

This makes retention an SEO concern, not just a production one. Levers:

- **The first 15 seconds decide the video.** A weak open craters average-view-duration (AVD) and tanks the ranking before the content even starts. Hook patterns are in `content-formats.md`.
- **Pacing and pattern interrupts.** Cut dead air; change the visual every so often (new screen, new chart, on-screen callout). The commonly cited "interrupt every 60–90s" is blog folklore, not YouTube doctrine — but the underlying point (keep the viewer from drifting) is consistent with the FAQ's retention emphasis. Read your **audience-retention report**: the dips show exactly where viewers leave. Fix those moments.
- **Deliver the promise fast.** If the title promises "find a hidden API in 5 minutes," show it working early. Front-loading payoff lifts retention and avoids the malicious-clickbait line (title must match content).
- **Match length to substance.** Don't pad a 6-minute tutorial to 12 for "watch time" — bloat kills AVD. Absolute watch time helps long videos *only when the length is earned*.

Retention is also where faceless content has to work harder: with no face to build rapport, clear narration and clean screen capture carry the engagement (see `content-formats.md`).

---

## CTR — title and thumbnail win the click

Title + thumbnail are the packaging that earns the click from an impression. They drive CTR, the second discovery lever after retention. Changing them *can* re-rank a video — but only because viewers then interact differently with the new packaging, not because the edit pings the algorithm. So: optimize them up front, and **don't churn the packaging on a video that's already working.**

### Titles

- **Lead with the search phrase, naturally.** The title is a primary relevance signal for search. Put the core query near the front: "Find Any Site's Hidden API (Network Tab Tutorial)" beats "A Cool Trick I Learned for APIs."
- **Promise a specific, deliverable payoff.** Specificity raises CTR and sets a retention contract you can keep.
- **Accurate, not clickbait.** The FAQ requires titles to be accurate; the spam policy makes *maliciously misleading* titles an enforceable violation (e.g. promising a full tutorial, delivering a teaser). Avoid LOUD packaging — ALL CAPS, "!!!!!", shock — which turns viewers away and can trigger removal.
- **Front-load for truncation.** Titles truncate in many surfaces; the meaningful words go first.

### Thumbnails

- **Compelling + accurate**, following the thumbnail policy. No deceptive, shocking, disgusting, gratuitously violent, indecent, or bait imagery — those cause viewer loss and can be removed under Community Guidelines.
- **Readable at small size and on mobile.** One clear idea, 3–5 words of high-contrast text max, a single focal element. For faceless dev content: the UI/result, a bold label, an arrow. For data content: the chart/ranking, the headline number.
- **Title + thumbnail are a pair, not duplicates.** The thumbnail shows; the title says. Together they make one promise the video keeps.

---

## Descriptions

The description feeds search relevance (it's matched against queries) and houses the CTA (covered in `traffic-conversion.md`). For SEO:

- **First 1–3 lines do double duty.** They show above the "...more" fold and can be pulled into search snippets — prime real estate. Lead with a natural-language sentence that includes the core search phrase and states the video's value, *then* the link. Do not robotically dump a raw URL as the literal first token of every video (an effectiveness myth, not a policy rule — it costs on-platform context and reads promotional; vary it).
- **Write a real description, not keyword soup.** A few hundred words of genuine, query-relevant context helps search understand the video. Keyword stuffing does not help and reads as spam.
- **Include the spoken/visual keywords.** What you say on the voiceover is auto-captioned and feeds search context, so the description and narration should cover the same real phrasings.
- All link prose gets a humanization pass; if you use an affiliate/referral parameter, carry it on the links that need attribution.

---

## Spoken and on-screen content is searchable

Search matches against "the video content," not just metadata. For faceless formats this is a gift: the voiceover transcript (auto-captioned) and on-screen text are read as content. Say the real query phrasings out loud naturally, label things on screen, and the video becomes findable for them — no metadata gymnastics required. Upload a clean transcript/caption file when you can; it improves both accessibility and search comprehension.

---

## Tags — minor, spelling-variants only

Honest correction of the most common YouTube-SEO myth: **tags are not an important ranking factor.** YouTube's FAQ states it directly — "How important are Tags? Not important." Their actual documented purpose is to **correct common spelling variants** of your topic (e.g. "YouTube" / "U Tube" / "You-tube", or a product name people routinely misspell).

So:

- Fill tags with the obvious spelling variants of your core term if you want — it's harmless.
- **Never treat tags as a growth or discovery lever.** Practitioner case studies that swear by tags (and several marketing blogs) contradict the authoritative source here; believe the source. Effort spent perfecting tags is effort stolen from title, thumbnail, retention, and spoken content — the things that actually rank you.
- If a tool or guide sells "tag optimization" as a core step, that's the tags myth. Don't repeat it.

---

## Shorts discovery

Shorts rank and surface differently from long-form: they live in their own vertical scroll feed and are the cheapest way to reach **new** viewers. For SEO purposes:

- **Optimize the hook and loop, not metadata.** Shorts are watched/swiped fast; the first second and the rewatch-loop drive their reach far more than tags or description.
- **A clear spoken/on-screen topic still helps search** — Shorts can appear in search and suggested too.
- **Treat Shorts as top-of-funnel reach**, funneling to long-form or the channel where the CTA lives — not as the conversion step itself. Full format guidance in `content-formats.md`.

---

## What NOT to optimize for

Time saved is time earned. The FAQ debunks these as ranking inputs — do not spend effort on them:

- **Upload cadence** — "Do I need to upload daily or weekly? No." Views are not correlated with time between uploads.
- **Posting time** — not known to affect long-term performance for evergreen content (matters only for Live/Premieres and minor early nudges).
- **Raw view count / "seeding" views** — ranking is per-video performance with real viewers; artificial views are stripped and risk termination (never buy or bot — red line).
- **Re-editing winning metadata** — don't churn the title/thumbnail on a video that's already performing.

Put that reclaimed effort into retention and into matching real search intent.

---

## SEO checklist (per video)

1. Target one real search intent (researched via Data API / managed tool, never local scraping).
2. Hook lands in the first 15s; pacing keeps AVD high; retention report reviewed after publish.
3. Title leads with the search phrase, promises a specific payoff, accurate (no clickbait/LOUD).
4. Thumbnail: one idea, readable on mobile, accurate, paired with the title.
5. Description: value + core phrase + link above the fold (not a robotic raw-URL dump); real context below; humanize the prose + carry any affiliate/referral parameter.
6. Voiceover/on-screen text says the real query phrasings; caption file uploaded.
7. Tags: spelling variants only — and not counted as a growth lever.
8. Shorts (if used): hook + loop optimized; funnels to long-form/channel.
