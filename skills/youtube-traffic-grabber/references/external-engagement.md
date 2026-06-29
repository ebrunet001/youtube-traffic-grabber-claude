# External Engagement — Authentic Participation on Other Creators' Videos

`traffic-conversion.md` collects clicks on **your own** videos, where self-promotion is expected. This page is the opposite situation: engaging on **other people's** videos and across the wider community, where you are a guest and self-promotion is *not* the default. The whole discipline of this page is knowing the difference.

This is the **direct YouTube analogue of value-first Q&A / forum doctrine** — Reddit, Quora, Stack Exchange answers — and it follows the same one-line rule, transplanted to YouTube comments and community surfaces:

> **You comment only where you genuinely add value, on relevant videos, and the link is a footnote to a complete, helpful contribution — never the point of it.**

In forum/Q&A link building the link is nofollow/UGC and the value is *referral traffic and brand*. On YouTube it's identical: **every comment link is nofollow** — you do this for traffic, brand recall, and discovery in the right audience, never for SEO equity. The mechanism that makes it work is the same too: a comment a creator and their audience are glad to see, that happens to point somewhere useful, earns clicks and goodwill; a comment that exists to plant a link is **spam** — it gets removed, can get your account flagged, and actively damages the brand it was meant to promote. (Same boundary as any Q&A channel: low risk if genuinely helpful; high if self-promotional.)

The two standing rules apply here as everywhere: any link you include carries your affiliate/referral parameter if you track attribution, and any comment/post prose gets a humanization pass before posting. But note the volume reality up front: external engagement is **hand-crafted, one comment at a time, never automated and never bulk** — so "humanize the prose" here means a handful of genuine comments, not a generated batch. Automation of engagement is exactly the line in `ethics-policy.md` that gets channels terminated.

---

## Why this is traffic & brand, not link-building

State it plainly so the agent never confuses the two channels:

- **YouTube comment links are `nofollow`/UGC.** A link in your comment on someone else's video passes **no ranking credit** to your site. Anyone who tells you to "comment on big videos for backlinks" is selling the same myth that gets debunked for Reddit/Quora.
- **The real value is qualified referral traffic and brand recall.** A genuinely helpful comment on a relevant video, seen by the right audience, drives clicks and plants your name with people who have the exact problem your asset solves. That's worth a lot — valued honestly, as traffic/brand.
- **Actual SEO link equity is a different job.** If the goal is off-page authority, that's a dedicated link-building workflow, not this page. YouTube engagement is never the link-building tactic; it's the audience-and-trust tactic.

---

## The value-first comment — anatomy

A comment that earns clicks and survives moderation has a specific shape. Copy the structure, not a script (scripts read as spam; a humanization pass owns the phrasing):

1. **Lead with genuine value.** React to the actual content — answer a question raised, add a missing nuance, correct a real error kindly, share relevant experience, extend the creator's point. The comment must stand on its own as a useful contribution *with the link removed*. If deleting the link guts the comment, it was a link drop.
2. **Disclose affiliation when you mention your own thing.** "Full disclosure, I built this —" / "Je précise, c'est l'outil que je développe —". Honesty is both an ethics requirement and a trust builder; undisclosed self-promotion is the fastest way to be read as a shill.
3. **The link is the footnote, not the headline.** It appears once, at the end, as the natural "if you want to go deeper" pointer — and only when it's *genuinely* the best next step for that viewer. Carry your affiliate/referral parameter on links that need attribution.
4. **Match the audience.** Dev/scraping/automation comments go on dev/tech videos pointing at your tools or tools site; data/retail comments go on relevant videos pointing at the store or BI site. An off-niche comment is noise even if it's polite — relevance gates value here exactly as it gates link value in link building.

**The test (same as the "three questions" used in link building):** would the *creator* be glad you posted this comment, even knowing you have a product? If yes, it's participation. If the comment only works because the creator doesn't realize you're there to promote, it's spam.

> *Dev example (on a "best web-scraping tools" video):*
> A substantive note on when a managed tool beats rolling your own (proxies, anti-bot maintenance, the real cost of self-hosting) — then, disclosed: "I maintain a price scraper on a hosting platform if it's useful — `https://apify.com/your-username/price-scraper?your-referral-param`. Either way, the proxy-rotation point above is the thing that bites people."

> *Data/retail example (on a market-analysis video, FR):*
> Une remarque concrète sur la lecture des données de marché pour estimer une valeur — puis, divulgué : "On publie des classements mensuels là-dessus sur le site si ça intéresse." Le commentaire tient debout sans le lien.

---

## Finding relevant videos (no local scraping)

Discovery is a data pull, and the data rule is absolute: **use the YouTube Data API or managed tools — never local scraping.** Local HTTP to youtube.com from your machine is forbidden by the standing no-local-scraping rule; to fetch at scale, run it through a hosted platform or a managed API, never a local `requests`/Playwright session.

What to look for:

- **Topical relevance first.** Videos where your asset is a *genuine* answer to a question the video or its commenters raise — "how do I scrape X without getting blocked," "where do I get this data," "is this a good investment." Use the YouTube Data API `search` endpoint on your niche keywords (the same intent keywords from `youtube-seo.md`).
- **Active comment sections.** A video with real, recent discussion is where a helpful comment gets seen. A dead comment section is wasted effort.
- **Right-sized, right-audience.** A mid-size video with a focused, on-niche audience converts better than a viral video whose audience is too broad to care.
- **Recency.** Comments on fresh uploads surface higher and reach the creator while they're still engaged.

Use the API to *find and prioritize*; do the actual commenting **manually, as yourself**. Discovery can be tooled; engagement cannot.

---

## Collaboration & cross-promotion with aligned creators

The highest-value external play isn't commenting — it's **genuine collaboration** with creators whose audience overlaps yours but who aren't direct competitors. This is the YouTube equivalent of earned editorial links: a real relationship that produces real exposure.

- **Who to approach:** creators in adjacent niches — for the dev channel, data/automation/no-code/SEO-tooling creators; for the data/retail channel, educators and enthusiasts in the same vertical, non-competing offer.
- **Formats that work faceless:** a guest data segment (you supply the analysis/dataset, they present), a tool walkthrough they feature, a co-produced explainer, a shout-out exchange grounded in genuinely recommending each other's work, cross-links in descriptions where it's honestly relevant.
- **The exchange must be real, not a scheme.** Mutual promotion between creators who genuinely value each other's work is legitimate. A mechanical "you plug me, I plug you" ring with no real endorsement is the engagement-manipulation pattern `ethics-policy.md` rules out — the YouTube cousin of reciprocal-link schemes.
- **Sponsored collaboration → disclose it.** If money or free product changes hands, it's a paid promotion: the **YouTube paid-promotion toggle** must be checked (Studio → Content → video → "contains paid promotion") *and* an FTC/ASA/DGCCRF-style disclosure given. The toggle satisfies YouTube; the law is separate. Full mechanics in `ethics-policy.md`.

---

## Community-tab usage

The **Community tab** (available once eligibility is met) is your channel's own owned surface for between-upload engagement — posts, polls, images, links to your subscribers. Because it's *your* surface speaking to people who already opted in, the self-promotion rules are looser than commenting on others' videos (closer to your own pinned comment than to a guest comment):

- Use it to **tease lead magnets and new uploads** (poll your audience on the next study topic; share a chart from a dataset with a link to the full thing — carry your affiliate/referral parameter on links that need it).
- Use it to **deepen the relationship**, not just broadcast links — questions, behind-the-data notes, polls that genuinely shape what you make next.
- It still isn't a place to **spam links every post**; over-promotion on your own Community tab trains subscribers to mute you, same dynamic as over-promotion in descriptions (`traffic-conversion.md`).

It's an owned channel — treat it like your pinned comment's bigger sibling, not like other creators' comment sections.

---

## WHAT GETS YOUR COMMENTS REMOVED / FLAGGED AS SPAM

Drawing the line explicitly. These behaviors get comments deleted, accounts flagged, and the brand damaged — and several are enforceable spam-policy violations (`ethics-policy.md`). The skill does not do, recommend, or generate any of them:

- **Bulk / repetitive link drops.** Posting the same (or near-same) "check out my tool/site → link" across many videos. This is the textbook **comment-spam** violation — high-volume, repetitive, deceptive comments to drive traffic — and it's exactly the YouTube version of forum-signature spam. Removed automatically, fast.
- **Link-first comments with no real value.** "Great video! Here's my channel/site: <link>." A comment that's a pretext for a link, that wouldn't exist without the link, gets read (by humans and filters) as spam.
- **Off-topic / off-niche link drops.** A scraping-tool link on a cooking video, a retail link on a gaming video. Irrelevance marks it as spam regardless of politeness.
- **Undisclosed self-promotion / shilling.** Pretending to be a neutral commenter while pushing your own product. Both a trust killer and, for paid relationships, a disclosure violation.
- **Automated / bot commenting.** Any tool that posts comments at scale. Engagement is done by hand, as yourself — automation here is the engagement-manipulation / fake-engagement line that gets *channels terminated*, not just comments removed.
- **Engagement bait & coercion.** "Sub to me and I'll sub back," "comment your link below and I'll check it out," sub4sub solicitation in comments. Named spam; also poisons the well.
- **Misleading / scammy comments.** Fake "I made $X with this" testimonials, fake urgency, impersonating the creator, phishing-style links. Severe — fast removal and account risk.
- **Hijacking a creator's audience disrespectfully.** Telling viewers to "leave this channel and come to mine." Even if not auto-removed, it burns the relationship and the brand.

The recovery cost is asymmetric: a spam comment is fast to post and slow to undo — deleted links, a flagged account, and a creator who now distrusts you. The genuine comment that took two minutes longer is the one that's still there next year sending clicks. When a request lands in this territory ("just blast our link across the top 50 scraping videos"), the response is to name the boundary, explain the spam-enforcement and brand cost, and propose the value-first variant that reaches the same audience without the risk.

---

## Cross-references

- **The Q&A/forum doctrine this page mirrors (Reddit/Quora/SE, value-first, nofollow, anti-spam)** → a dedicated link-building / off-page workflow
- **Penalty asymmetry, disclosure, "what we won't do" line (link-building side)** → a dedicated link-building / off-page workflow
- **YouTube ToS / spam policy, fake-engagement red line, paid-promotion toggle + FTC disclosure** → `ethics-policy.md`
- **CTAs on your *own* videos (the internal counterpart to this page)** → `traffic-conversion.md`
- **Property→channel mapping; which property a comment should point at; local/international split** → `channel-strategy.md`
- **Intent keywords for finding relevant videos** → `youtube-seo.md`
- **Faceless collaboration formats (guest data segment, co-produced explainer)** → `content-formats.md`
- **Ready-to-adapt external-comment skeletons, EN+FR** → `asset-templates.md`
- **Data pulls via YouTube Data API / managed tools — never local scraping** → a scraper-engineering workflow
- **Making every comment/post read human (not a generated batch)** → a prose-humanization pass
- **Acquiring SEO link equity (not what YouTube comments do)** → a dedicated link-building workflow
