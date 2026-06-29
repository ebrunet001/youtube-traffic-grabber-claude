# Measurement — What to Track, Where to Read It, What to Optimize

YouTube hands you a wall of numbers, and most of them are vanity. This skill exists to drive **referral traffic and conversions to your own assets** — so the measurement plan is built backwards from that, not from "more subscribers." The metrics sit in three layers, each answering a different question, in funnel order:

1. **Discovery** — *is the right person seeing the video?* (impressions, CTR)
2. **Engagement** — *do they actually watch it?* (average view duration, retention %) — the dominant on-platform signal
3. **Traffic & conversion** — *do they leave YouTube for the asset, and do they convert?* (clicks-to-site, installs / sign-ups attributable via your affiliate/referral parameter) — **the layer that matters most here**

A video can win the first two layers and still be worthless to the business if nobody clicks through. The whole point is layer 3; layers 1 and 2 are the means.

> Reminder on what YouTube measurement *cannot* tell you: YouTube outbound links are **nofollow** — they pass referral traffic and brand exposure, **not** SEO equity. So there is no "link value" to measure here. Measure clicks, visits, installs, and brand lift. Actual link-building belongs to a separate discipline.

---

## Layer 1 — Discovery (is the right person seeing it?)

**Metrics:** impressions, **impressions click-through rate (CTR)**, traffic-source breakdown (Search vs Suggested vs Browse vs Shorts feed vs External).

**What they mean.** Impressions = how often the thumbnail was shown. CTR = the share of those that became a click. The two levers a creator controls at this layer are the **thumbnail and title** — they win (or lose) the click. CTR has no universal "good" number; judge it *relative to your own other videos* and against the moment it stabilizes (early CTR is inflated by your own subscribers).

**Search vs the rest.** Prioritize **traffic from Search** — those viewers arrived with a query/problem, which is the highest-converting traffic for an off-platform CTA. Browse/Suggested is volume; Search is intent. A video with modest views but heavy Search traffic is often a better business asset than a high-view Browse hit.

**Where to read it.** YouTube Studio → **Analytics → Reach** tab: impressions, impressions CTR, traffic source types, and "Traffic source: YouTube search" (the actual search terms). Also the per-video Reach view to see how a single video is found.

**Optimize when weak:**
- **Low impressions** → a discovery problem, not a packaging problem. The video isn't matching queries or isn't being suggested. Fix title/description keyword match to real search intent; consider a Short to feed new-viewer reach; check the video is genuinely on-niche (channel focus drives suggestion). Do **not** "buy views to seed it" — artificial views are stripped and risk termination (see `ethics-policy.md`).
- **High impressions, low CTR** → people see it and don't click. The thumbnail/title isn't earning the click. Rework packaging — but keep it **accurate** (deceptive thumbnails/titles are removable spam, and clickbait that doesn't deliver tanks retention anyway). Don't churn the packaging on a video that's already working.

---

## Layer 2 — Engagement (do they actually watch it?)

**Metrics:** **average view duration (AVD)** and **audience retention %** — the dominant signal. Secondary: average percentage viewed, likes/comments/shares (weak signals), the retention curve shape.

**What they mean.** YouTube's system mainly learns from *whether viewers choose to watch and how much*. Retention is the closest proxy you control after the click. Rule of thumb from YouTube: **relative watch time matters more for short videos, absolute watch time more for long videos** — so judge a Short on % retained and a long tutorial on minutes held. Likes/comments are "somewhat" signals; don't optimize for them directly.

**The retention curve is the real tool.** A cliff in the first 15–30s = the hook failed. Mid-video sag = pacing problem at that timestamp. A bump = something worked (replays/shares) — study and repeat it.

**Where to read it.** YouTube Studio → **Analytics → Engagement** tab: average view duration, average percentage viewed, top videos by watch time. Per-video → **Audience-retention report**: the curve, plus "key moments for audience retention" (intro, top/recurring moments, dips).

**Optimize when weak:**
- **Early cliff (first 15–30s)** → rewrite the hook: state the payoff in the first sentence and show the end result on screen before explaining (see the scripts in `asset-templates.md`). For faceless, "authentic" = clear narration + clean screen capture, since there's no face building rapport.
- **Mid-video sag** → tighten pacing at that exact timestamp: cut dead air, add a visual change every ~15–30s, remove the tangent the curve is reacting to.
- **Good retention but few clicks** → not an engagement problem; jump to Layer 3. The video earned the watch but the CTA/destination failed.

---

## Layer 3 — Traffic & conversion (THE one that matters here)

This is the layer the skill is built for. Discovery and engagement are upstream means; **clicks-to-site and conversions are the goal.**

**Metrics:**
- **Clicks to the site** — how many viewers actually left YouTube for the asset, and from which placement (description vs card vs end screen vs pinned comment).
- **Conversions** — the business outcome on the destination: **product installs / runs / sign-ups attributable via your affiliate/referral parameter**, site leads/sales, email opt-ins, lead-magnet downloads.
- **Brand lift (indirect)** — branded searches, direct visits, and natural mentions that grow *because* people discovered the brand on YouTube. This is the real SEO-adjacent benefit — earned downstream, never the nofollow YouTube link itself.

**Where to read it.**
- **On YouTube:** Studio → **Analytics → Audience** and the traffic/CTA reports. End-screen and card performance (clicks, click rate, "Cards/End screens" report) tell you *which placement* converts. Note: YouTube reports on-platform card/end-screen clicks well, but the off-platform landing is best measured on your own side.
- **Off YouTube (the source of truth for conversion):** **UTM-tag every YouTube link** and read it in **GA4** with YouTube as a distinct referral source — clicks, sessions, and the conversion events. Tag per placement (`utm_content=description` / `card` / `endscreen` / `pinned`) so you can compare them.
- **Platform attribution:** an **affiliate/referral parameter** on every product link is how installs/sign-ups get attributed to this channel. No parameter = the install happened but you can't prove it came from your video. (Stack UTM *and* the platform's affiliate/referral parameter on product links — UTM for GA4, the affiliate param for platform attribution.)

**Optimize when weak:**
- **Good views/retention, low clicks** → the CTA or the destination is the problem, not the content. Move the link **above the fold** in the description (after a one-line value hook), add/strengthen a **verbal + on-screen CTA tied to the value**, add a **pinned comment**, use an **end screen** (the viewer who reached the end is your warmest). Point the link at the **relevant page/lead magnet**, not the homepage — a compelling destination is the conversion multiplier.
- **Clicks but no conversions** → the destination doesn't match the promise. Align the landing page to the video's specific topic; verify the offer is real and matches what the CTA promised.
- **Installs happening but unattributed** → an affiliate-param / UTM hygiene failure. Audit every link in the description, pinned comment, and end screen.
- **Tempted to inflate any of this** → don't. Bought/botted clicks and fake installs are fraud-adjacent and a ToS violation; they also poison your own data so you can't tell what actually works.

---

## Deprioritize — vanity metrics

These feel like progress and mostly aren't, for *this* goal:

- **Raw subscriber count.** Subs are a habit/loyalty signal, not a traffic or conversion metric. A small channel with high Search traffic and strong click-through beats a big channel of off-target subscribers. (And buying subs is a ToS violation that gets them stripped — see `ethics-policy.md`.)
- **Total views across off-target videos.** Views on videos that don't reach prospects or carry a relevant CTA are noise. Optimize views *on the videos that convert*, not the channel total.
- **Likes/comments as a target.** Real engagement is welcome and YouTube weighs it "somewhat" — but it's a weak signal and a bad optimization target. Never solicit or trade engagement (no engagement-bait, no like-for-like).
- **Tags.** Near-worthless for ranking (YouTube: "How important are Tags? Not important" — mainly for spelling variants). Fill them if you like; never treat them as a growth lever.
- **Upload cadence / post-time as a KPI.** Growth is not correlated with time-between-uploads, and publish time doesn't drive long-term performance for evergreen faceless tutorials. Consistency builds audience habit; it is not a ranking input. Don't optimize the calendar at the expense of the video.

---

## The one-line scorecard per video

For each video, the question is not "how many views" but: **Search-led discovery → strong retention → clicks-to-site → attributable conversions (affiliate/referral parameter / GA4).** Read Reach for layer 1, Engagement + the retention curve for layer 2, and GA4 + the platform attribution parameter for layer 3 — and fix the *first* layer that's weak before touching the others.
