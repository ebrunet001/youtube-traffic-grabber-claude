# Traffic Conversion — Turning Views Into Off-Platform Clicks and Installs

This page owns the **conversion half** of the YouTube funnel. `youtube-traffic-doctrine.md` and `youtube-seo.md` get the right viewer to watch the video (discovery); this page turns that watcher into someone who leaves YouTube and lands on your asset — a product install, a site visit, a lead captured. Discovery without conversion is vanity; conversion without discovery is a CTA nobody sees. You need both, and they're owned by different files.

The directing principle, stated once: **the video earns the click; the CTA only collects it.** A viewer clicks through to your site because the video was genuinely useful and the next step is obviously valuable to *them* — not because you asked harder or placed the link in more spots. Every placement below is a way of making an already-earned click easy and obvious. None of them manufactures a click that the content didn't earn. When a placement starts trying to do the content's job ("link in bio, link in description, link in comments, link link link"), it stops converting and starts repelling — and it edges toward the off-platform-diversion and over-promotion patterns that depress retention and, at the extreme, draw spam enforcement (`ethics-policy.md`).

Two rules apply to **every** placement on this page, no exceptions:

1. **If you track conversions with an affiliate/referral parameter, every relevant link carries it.** For example, a product URL might be `https://apify.com/your-username/<slug>?your-referral-param` — never a bare link that forfeits referral attribution. Use the same parameter everywhere so attribution stays consistent.
2. **All CTA prose gets a humanization pass** before it's published — descriptions, pinned comments, verbal CTA scripts, end-screen text. This file specifies *what to say and where*; the humanization pass makes it read human.

And one frame inherited from the doctrine: **YouTube's outbound links are `nofollow`.** Every click you win here is *traffic and brand*, not link equity. You are optimizing clicks-to-site and installs, never "links." Actual link-building for SEO authority is a different job.

---

## The two-thing model: placement × destination

Practitioners obsess over placements (where the link goes) and underweight the destination (what the click lands on). Both decide conversion, and the destination usually decides more:

- **Placement** is *visibility* — how likely the right viewer is to see and use the link. The placements below are ranked by visibility and warmth.
- **Destination** is *motivation* — the reason the viewer clicks at all. A perfectly placed link to a generic homepage converts worse than a buried link to a free dataset the video just demonstrated.

The conversion multiplier is the **lead magnet / bridge offer**: a specific, relevant, valuable destination that matches what the video was about. Placements move clicks only when there's a compelling reason to click. This is why the lead-magnet section below is the most important on the page, not the placement catalog.

---

## Placement 1 — the description link, above the fold

This is the workhorse. On both desktop and mobile, YouTube shows only the **first 2–3 lines of the description** before the **"...more"** truncation. Anything below that is invisible until the viewer expands — and most never do. So the link, or a one-line hook plus the link, must live **above the fold**, in those first lines.

**The structure that converts:**

```
[One-line value hook tied to the video topic.]
👉 [The link — with your affiliate/referral parameter if you track attribution]

────────
[Everything else: longer description, timestamps/chapters,
 secondary links, channel boilerplate, social handles.]
```

The hook earns the expansion-or-click; the link collects it. Do **not** make the raw URL the literal first token of every video by default — that reads as a billboard, can get pulled into search snippets as ugly noise, and (per `youtube-seo.md`) the top of the description is prime keyword real estate you don't want to waste on a naked URL. Lead with one line of value, then the link.

**Calibration (this is a real effectiveness trade-off, not a policy rule):**
- Lead with a value hook, then the link — don't bury it, don't make it robotic.
- **Don't push the site in every single video.** A channel where every description screams "VISIT MY SITE" trains viewers to ignore the CTA and signals over-promotion. Vary it; let some videos be pure value with a soft, lower-placed link. This caution is correct.
- Put **one primary CTA above the fold.** Multiple competing links above the fold split the click and dilute the ask. Secondary links go below the "...more" line.

**Worked examples:**

> *Product demo video (dev channel):*
> `Scrape product prices at scale — no proxies to manage, no anti-bot headaches.`
> `👉 Try the tool (free tier): https://apify.com/your-username/price-scraper?your-referral-param`

> *Data video (data/retail channel):*
> `The 50 most-searched items this month — data updated weekly.`
> `👉 The full ranking: https://your-store.example/...`  *(or `https://your-bi-site.example/...` for the international/trade audience)*

Match the destination to the video and to the channel's property (the dev channel points at products / the tools site; the data/retail channel at the store / the BI site — see `channel-strategy.md` for the property→channel mapping).

---

## Placement 2 — the pinned comment

A **pinned comment sits at the top of the comment section**, above all others, and is editable after publish. It's the cheapest reinforcement of the description link and catches viewers who scroll to comments before (or instead of) expanding the description.

Make it *additive*, not a copy-paste of the description:

- Restate the value in the viewer's words ("A few people asked where to get the dataset — here it is 👇"), then the link (with your affiliate/referral parameter if you track attribution).
- Use it to answer the predictable top question the video raises, and attach the link as the answer's natural endpoint.
- Because it's editable, update it when the offer changes (new product version, refreshed dataset, fixed link) without re-uploading the video.

A pinned comment that's just "LINK: <url>" converts worse than one that gives a reason. The comment is a tiny piece of helpful content with the link as its footnote — the same shape as a good external comment (`external-engagement.md`), just on your own video where self-promotion is expected and welcome.

---

## Placement 3 — end screens

**End screens** occupy the **last 5–30 seconds** of a video and carry clickable elements. For conversion they're prime real estate: the viewer who reached the end is your **warmest** — they consumed the whole thing and are primed for a next step.

- For channels eligible to link to an external site (Associated Website / verified site link), an end-screen element can point **off-platform** to a landing page. Otherwise, end screens link to **another video, a playlist, or subscribe** — which keeps the warm viewer on a path that *eventually* converts (a related video whose description carries the off-site CTA).
- Design the last 20–30s of the script to *set up* the end screen: don't let the value end and then bolt on a card grid. Narrate the next step ("if you want the full dataset, it's linked — and this next video shows the related version").
- Don't cram. One or two end-screen elements with a clear hierarchy beat a wall of thumbnails.

Faceless note: end screens work without a presenter — a clean outro frame with on-screen text and the clickable elements is enough. (Format mechanics live in `content-formats.md`.)

---

## Placement 4 — cards

**Cards** are clickable elements that appear **mid-video**, timed to the exact moment the link is most relevant. Use them when the value of clicking peaks *during* the content, not just at the end:

- In a product demo, drop a card to the product page at the moment you show the result it produces.
- In a data explainer, card the full ranking/landing page right as you reference "the complete list."
- Timing beats frequency. A card fired at the relevant second converts; a card grid scattered through the video distracts and depresses retention (which hurts discovery — see `youtube-seo.md`).

Don't overload. Too many cards turn the video into a billboard and pull attention away from the content that's earning the click.

---

## Placement 5 — the verbal CTA (+ on-screen text)

Often the **single biggest driver**, because it lives *inside the content* where attention already is, not in chrome the viewer might skip. Say it and show it:

- **Name the value of clicking, not the act of clicking.** "The full dataset is linked in the description" beats "link in the description, go check it out." State *what they get* and *why now*.
- Tie it to the moment of peak relevance — right after you've demonstrated the result the link delivers.
- Reinforce with **on-screen text** (a lower-third / caption): "Full tool → description." Faceless content leans on this because there's no face to direct attention; the on-screen text *is* the pointer.
- Keep it once or twice, placed where it's earned. A video that verbally hawks the link every 30 seconds reads as a sales pitch and loses the room.

The phrasing rule across all verbal CTAs: **value-first, native, never a hard sell.** "Here's the complete guide on the blog" converts; "SMASH that link and BUY NOW" repels. Over-promotion depresses both clicks and retention — the doctrine's central conversion principle.

---

## Always-on placements — channel chrome

These aren't per-video; they run 24/7 and catch viewers who arrive at the channel from any video:

- **Channel banner link** — point it at a specific high-value offer (a flagship product, the studies hub), not a bare homepage.
- **About-section links** — the full set of property links; for the dev channel, include the product/Store links (with your affiliate/referral parameter) and the tools site; for the data/retail channel, the BI site and the store.

Treat these as the always-available pathway, not the primary converter. They support the per-video CTAs; they don't replace them.

---

## The lead magnet — the conversion multiplier (most important section)

A perfectly placed link to a weak destination converts badly. A buried link to a *great* destination still converts. The destination is the lever, and the highest-converting destination is a **lead magnet / bridge offer**: something genuinely valuable, free, and **topically matched to the video**, that the viewer wants enough to leave YouTube for.

**The rule: link to a relevant page, never the homepage.** Send the click to the thing the video was about, not the front door. A viewer who watched "how to scrape product prices" wants the *scraper*, not your company homepage.

**Lead-magnet types, ranked by fit:**

- **Free study / dataset** — a strong hook. A video that demonstrates an insight ("the 50 most-searched items this month," "what we found scraping 10k product pages") with the *full data/study* one click away is the cleanest value-for-click trade there is. The data is both the content's proof and the CTA's reward. Maps to a `/studies` hub and to market reports.
- **Free tool / free tier** — for a product, the install *is* the lead magnet. The video shows the tool working; the CTA is "run it yourself, free tier" → the product page (with your affiliate/referral parameter if you track attribution). This is the highest-intent conversion on the dev channel: the viewer is already evaluating the tool.
- **Template / checklist / config** — a ready-to-use input config, a checklist, a setup snippet. Low production cost, high perceived value, perfectly matched to a tutorial video.
- **Email course / gated guide** — captures a lead (email) rather than just a click; appropriate when the goal is nurture, not immediate install. Use sparingly — a gate adds friction that a free dataset doesn't.
- **Members-only / deeper content** — the long-form version of what the video teased.

**Why this works and isn't spam:** the lead magnet makes the CTA *value-first by construction*. You're not asking the viewer to do you a favor by clicking; you're offering them the next useful thing. That's the difference between a conversion path and a link drop. It also keeps you clear of the off-platform-diversion line in `ethics-policy.md`: the video is genuinely informative on its own, and the link leads to *more genuine value* — not a thin doorway whose only purpose is to push viewers off YouTube.

---

## Example funnels — end to end

Map the whole path so the CTA, destination, and channel align.

### Funnel A — product demo → install (dev channel)

| Stage | Content |
|---|---|
| **Video** | Faceless screen-rec: "Scrape product prices without getting blocked" — show the tool running, the data coming out. |
| **Lead magnet** | The tool itself, free tier. The install is the reward. |
| **Above-fold description** | `Scrape prices at scale — no proxy/anti-bot setup.` + `👉 https://apify.com/your-username/price-scraper?your-referral-param` |
| **Verbal CTA** | At the result reveal: "If you want to run this on your own list, the tool's linked — there's a free tier." |
| **Card** | Fired at the result reveal → product page (with referral param). |
| **End screen** | Product page (if external link eligible) or the next product-demo video whose description carries the link. |
| **Pinned comment** | "Free tier is enough to test it on a few hundred products 👇 [link with referral param]" |

### Funnel B — data video → site (data/retail channel)

| Stage | Content |
|---|---|
| **Video** | Faceless data-viz + voiceover: "Top 50 most-searched items this month" (data-derived). |
| **Lead magnet** | The full ranking / market report — the complete dataset the video sampled. |
| **Above-fold description** | `The full monthly ranking (updated data).` + `👉 https://your-store.example/...` (local) or `https://your-bi-site.example/...` (international/trade) |
| **Verbal CTA** | "I only showed the top 10 — the full 50, with prices, is on the site." |
| **Card** | Fired at "and here's the rest of the list" → the report page. |
| **End screen** | The report page (if eligible) or the next month's/related ranking video. |
| **Pinned comment** | "Full ranking + price moves here 👇 [link]" |

Pick the data/retail destination by audience: the **local-language store** for local retail/enthusiast intent, the **international BI site** for intl/trade intent (`channel-strategy.md` resolves the language/property split).

---

## Measurement hook

Conversion only improves if you can see it. UTM-tag every off-site YouTube link (treat YouTube as its own GA4 source); if your destination has its own attribution parameter, *that* is the platform-native attribution. Compare CTR across description vs. card vs. end screen separately so you optimize the placements that actually convert. The full KPI framework — clicks-to-site, installs via the attribution parameter, per-placement CTR — lives in `measurement.md`. This page produces the CTAs; that page tells you which ones worked.

---

## Cross-references

- **Discovery side (search/suggested/browse), nofollow/traffic-not-equity frame** → `youtube-traffic-doctrine.md`
- **Keyword/title/description/thumbnail optimization, retention signals** → `youtube-seo.md`
- **Property→channel mapping, local/international destination split** → `channel-strategy.md`
- **Faceless format mechanics (end-screen frames, on-screen text, screen-rec)** → `content-formats.md`
- **Ready-to-fill description / pinned-comment / CTA templates, EN+FR** → `asset-templates.md`
- **KPIs: clicks-to-site, installs via the attribution parameter, per-placement CTR** → `measurement.md`
- **Off-platform-diversion line, over-promotion, paid-promotion disclosure** → `ethics-policy.md`
- **Value-first comments on *others'* videos (conversion's external counterpart)** → `external-engagement.md`
- **Making all CTA prose read human** → a prose-humanization pass
- **Acquiring SEO link equity (not what YouTube links do)** → a dedicated link-building workflow
