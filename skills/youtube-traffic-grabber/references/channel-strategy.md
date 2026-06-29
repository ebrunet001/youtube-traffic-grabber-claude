# Channel Strategy — Greenfield Architecture & Property Mapping

This is the strategist's file. Before you script a single video, decide *which channels exist,
what each one is for, and which property it feeds*. Get this wrong and every downstream
asset — titles, Shorts, CTAs, external comments — is pointed at the wrong audience.

The whole plan rests on one principle the research makes non-negotiable: **YouTube rewards
focus, and focus fragments on two axes at once — niche AND language.** The algorithm ranks
per-video and per-audience; it builds a model of "who is satisfied by this channel's videos."
A channel that mixes, say, software tutorials with hobby/retail explainers, or French and
English in the same feed, gives the system an incoherent audience signal and a viewer base
that churns. One channel = one niche = one language is the spine.

Two more frames that govern everything here:

- **YouTube is a traffic/brand/discovery channel, not an SEO-equity channel.** Its outbound
  links are nofollow. We map channels to properties to drive *qualified clicks and installs*,
  never to build links — link-building is a separate discipline.
- **Greenfield.** No channel exists yet. This file covers launch-from-zero, not optimizing an
  established channel. The 0→100-subs motion is part of the plan, not an afterthought.

Property→channel mapping lives here because the channel architecture *is* the mapping —
the YouTube analogue of a property-profiles map.

---

## 1. Channel architecture = property mapping

Suppose a portfolio splits into two unrelated niches. Each niche gets its own channel family.
The niches **never** share a channel — they share no audience, no search intent, and no
satisfaction profile, so co-hosting them would poison the algorithm's audience model for both.
The worked example below uses a **software/tooling** niche and a **hobby/retail** niche; map
the pattern to your own portfolio.

| Niche | Properties it feeds | Audience | YouTube intent surface |
|---|---|---|---|
| **dev / tech** | a developer-tools site (e.g. `mr-bridge.com` + its `/scrapers`, `/mcp-servers`, `/ai-workflows`, `/studies`, `/articles`) and any tools/products it publishes (scraping, MCP servers, data tooling) | Developers, data engineers, SEO/growth people, automation & no-code builders evaluating tools | **High-intent search** — viewers arrive with a problem ("scrape X", "MCP server for Y"); the highest-converting traffic for a tool CTA |
| **hobby / retail** | a content/BI site for an international audience and an e-commerce store for a local-language market | Enthusiasts, collectors, buyers, gift shoppers, trade/importers | Mixed — some search ("best X 2020", "is rating-site Y accurate"), more browse/suggested; data-explainer content earns suggested reach |

This is a posture distinction worth keeping: the **dev channel maps to tool/product pages**
(lower stakes, install-and-traffic objective, can push harder on volume of uploads), the
**hobby/retail channels map to money sites** (they earn revenue — the channel is
brand-and-trust-building, the CTA is softer, the destination is a genuine landing page not a
hard sell).

---

## 2. The niche × language decision (resolved)

A common complication: **a niche is not always one audience.** Suppose the hobby/retail niche
spans a local-language market (an e-commerce store) and an international market (a content/BI
site). "Two channels, one per niche" is the *starting heuristic*, not the answer. You then have
to decide whether that niche runs as one bilingual channel or as language-split channels — and
the same focus principle that separates niches **applies to language too**.

### The principle, applied to language

YouTube's audience model and recommendation system fragment on language exactly the way they
fragment on topic. A bilingual channel tells the system two contradictory things: half its
viewers are satisfied by content in language A, half by language B. Suggested/Home placement
degrades for both because the "similar viewers who were satisfied" signal is split down the
middle. Auto-captions, spoken-keyword search context, and titles/thumbnails all key off
one language per video — a mixed feed dilutes every one of them. The viewer experience is also
worse: a viewer scrolling a half-foreign-language channel sees half the catalog as noise, and bounces.

**Conclusion: language is a second segmentation axis, co-equal with niche.** Split a multi-market
niche by language rather than running one bilingual channel.

### The resolved structure (three channels at launch, one axis parked)

| Channel | Niche | Language | Maps to | Objective |
|---|---|---|---|---|
| **Dev channel** | dev / tech | **EN-primary** | the dev-tools site + its tools/products | Installs + qualified dev traffic. EN is the lingua franca of the developer/data audience; the products and docs are EN; the site is EN-primary. One language, no split needed at launch. |
| **Local-language retail channel** | hobby / retail | **local language (e.g. FR)** | the e-commerce store | Local-language referral traffic + brand for the e-commerce money site. Local audience, local search intent, local-language packaging. |
| **International channel** | hobby / retail | **EN** | the international content/BI site | International-trade/BI traffic + brand. English-language data-explainer content for an intl audience. |

Rationale, point by point:

- **A separate local-language retail channel and a separate international channel, NOT one
  bilingual channel.** The two properties already have different languages, different markets,
  and different business models (local retail vs. intl BI/trade) — they were never one audience.
  Splitting them aligns the channel with the property *and* with the language. Each gets a
  coherent audience signal, clean auto-captions, on-language search context, and a feed that
  doesn't read as half-noise.
- **The dev channel stays EN-primary, single-channel.** Its audience is natively English across
  markets; there's rarely a non-EN dev audience large or distinct enough to justify a second dev
  channel at launch. If non-EN dev demand proves out later (many dev-tools sites are
  multilingual), a language-split dev channel becomes a *future* axis, decided the same way (own
  channel per language, never bilingual). Not built now.

### Trade-offs (stated honestly)

- **Three channels = roughly triple the production and consistency burden.** This is the real
  cost. It's defensible only because the alternative — bilingual/mixed channels — caps the
  ceiling of each via a fragmented audience signal, and because faceless formats (§4) and
  repurposing keep per-channel cost low. **Sequence the launches** rather than opening all three
  cold (see §3): lead with the one channel whose property most needs traffic now, prove the
  motion, then open the next. Three channels does not mean three simultaneous zero-to-launch fronts.
- **Slower individual growth vs. one pooled channel.** A single mega-channel would accumulate
  subscribers faster on paper — but those subs would be a blurred mix that converts poorly and
  whose feed placement suffers. Focused channels grow slower in raw subs and convert far better,
  which is the actual objective (traffic/installs, not a vanity sub count).
- **No cross-pollination between the two language markets.** A local-language viewer won't be
  suggested the EN channel and vice-versa. Acceptable: they're different markets. Cross-promote
  *manually* where genuinely relevant (an end-screen or pinned-comment pointer for a genuinely
  bilingual viewer), never by merging feeds.

### A third-language axis — named, deferred, not dropped

If a property serves a real *additional-language export market* (it's an audience, not a slot),
that third language is a **third axis in the niche**, and by the same focus principle that
audience deserves its **own localized channel / track**, not videos in a third language bolted
onto an existing channel.

**Decision pattern: park it, don't build it now.** Treat it as an explicit *deferred axis* — a
future dedicated channel or localized track, opened only once an existing channel's motion is
proven and there's production capacity in that language (localization routes through a
humanization pass). Record it so it is **never silently dropped**: the moment that export market
becomes a YouTube priority, the answer is a dedicated channel, decided on the same
one-niche-one-language logic — not a section of an existing channel in the wrong language.

> **Summary of the resolution:** niche splits the two families (2 channel families); language
> splits a multi-market niche into local + international (a 3rd channel); any further export
> language is a known 4th axis, deferred. The dev channel stays EN-primary, single-channel, with
> its own future language-split deferred too. The rule that produced all of this is one line:
> **one channel = one niche = one language.**

---

## 3. Greenfield launch-from-zero playbook (per channel)

Launching from zero is its own discipline. A channel with no audience has no Home/Suggested
reach to inherit — the system has no "similar satisfied viewers" model yet. Early growth comes
from **search intent** and **Shorts reach**, not from recommendations. Plan accordingly.

**Account setup (prerequisite).** Create each channel as a **Brand Account under one Google
account** (ideally an address on the brand's own domain, e.g. `hello@your-domain.com`, the same
as the website). One Google account can own multiple Brand-Account channels, which is exactly how
the three channels above (dev, local retail, international) coexist without separate logins.
Using Brand Accounts means ownership can be delegated later without handing over the personal
Google login.

### 3a. Sequence the launches (don't open three cold fronts)

Pick the channel whose property most needs traffic and whose content you can sustain, launch it,
prove the 0→100 motion, *then* open the next. A defensible default order: **dev channel first**
(richest search-intent demand, clearest install funnel, lowest content-sourcing cost since the
products and docs already exist), then the retail channel tied to whichever property is the
current priority. This is a recommendation, not a rule — your current business priority overrides it.

### 3b. First content pillars (the launch slate)

Open each channel with **3–4 pillars**, not a grab-bag. Pillars give the algorithm a coherent
topic signal and give the channel an identity. Each pillar maps to a property funnel (§5).

- **Dev channel** (EN): (1) *Tool how-tos* — "do task X with tool Y", problem-led, search-intent.
  (2) *Product walkthroughs* — set up / use a tool, screen-recorded. (3) *Data tooling / workflows*
  — "turn raw data into X", connects to the site's studies. (4) *Concept explainers* — "what is an
  MCP server", top-of-funnel reach.
- **Local-language retail channel** (e.g. FR): (1) *Selections / buying guides* — by category,
  budget. (2) *Data decoded* — rating data explained (faceless data-viz). (3) *Pairings &
  occasions* — gift, event, use-case. (4) *Behind the scenes* — selection, advice, faceless.
- **International channel** (EN): (1) *Market data explainers* — market trends as narrated
  data-viz. (2) *Is X accurate?* — rating-data literacy. (3) *Investment & trade angle* — market
  reads for the intl/trade audience. (4) *Region/category deep-dives* — slideshow + voiceover.

Pillars are the launch identity; you can prune the weakest after the first ~15–20 videos based on
which earns retention and CTR.

### 3c. The 0 → first-100-subs motion

The first 100 subscribers don't come from the recommendation engine — they come from **answering
specific questions people are already searching** and from **Shorts reach**:

1. **Lead with search-intent long-form.** Target low-competition, specific queries you can rank
   for from zero (a problem-led "how to do X" tutorial beats a broad "topic 101"). Search is the
   surface a zero-audience channel can win, because it ranks on title/description/content match +
   engagement-for-that-query, not channel reputation.
2. **Seed reach with Shorts** (§3e) — the cheapest way to put a brand-new channel in front of new
   viewers, since Shorts surface in their own feed independent of subscriber count.
3. **Borrow audiences via genuine external engagement** — value-first comments on relevant
   creators' videos draw their viewers to your channel. This is owned by the external-engagement
   reference (`external-engagement.md`); it is **value-first and disclosed, never link-drop spam**.
   It is a real 0→100 lever, used cleanly.
4. **Convert your existing properties' traffic.** Site visitors and any newsletter/social
   following are warm — point them at the new channel. (This is earning *real* early views via
   legit cross-promotion — explicitly fine — and is the sharp line away from buying/seeding views,
   which is a ToS violation.)
5. **Earn the subscribe, never coerce it.** Asking viewers to subscribe is legitimate; sub4sub,
   bought subs, and "subscribe to unlock" coercion are not (`ethics-policy.md`).

### 3d. Posting cadence — consistency and quality, NOT volume

**Critical, research-anchored:** upload cadence is **not correlated with growth.** YouTube
explicitly says you do *not* need to upload daily or weekly; many channels win on **quality over
quantity**; breaks don't structurally damage a channel; and best-posting-*time* doesn't materially
affect long-term performance for evergreen content (which is what faceless tutorials and
data-explainers are).

What this means for the plan:

- **Pick a cadence you can sustain indefinitely, then hold it.** Consistency builds *audience
  habit* and protects against burnout — it is not itself a ranking input. A sustainable
  every-1–2-weeks beats a 3×/week sprint that collapses in a month.
- **Never trade quality for volume to "feed the algorithm."** There is no algorithm to feed on
  cadence; there is only viewer satisfaction per video. A mass-produced upload cadence also edges
  toward the automated/synthetic-mass-production line — the opposite of what we want.
- **Don't obsess over upload time.** For evergreen faceless content, post-time optimization is
  wasted effort. Reserve timing care for any Live/Premiere only.
- **Sequencing across channels** (§3a) is how you keep three channels consistent without
  three burnout fronts — stagger, don't stack.

### 3e. How Shorts seed a new channel

Shorts are the launch accelerant, not the conversion step. For a zero-audience channel they're
the cheapest reach because they surface in the Shorts feed independent of subs.

- **Faceless Shorts per channel:** dev → a 30-second screen-capture of a tool solving a task, or
  one data snippet; retail → one chart/ranking reveal or a single fact as data-viz + text.
- **Use Shorts as top-of-funnel, funnel to long-form.** A Short teases the full tutorial /
  full data explainer; the long-form is where retention and the site CTA live. Don't put the hard
  site CTA in the Short — Shorts viewers are low-intent; route them to the long-form first.
- **Shorts subscribers convert weakly to long-form watchers** — treat Short-driven subs as reach,
  not as qualified audience, and measure them separately (`measurement.md`).
- **Keep them genuinely informative.** A flood of near-identical AI Shorts is the content-farm
  pattern the spam policy punishes. Faceless ≠ slop (§4).

---

## 4. Faceless format mix (per channel)

Assume **faceless content only** — no on-camera presenter, ever. Every format below works without
a face. The discovery and conversion doctrine applies unchanged; the constraint only removes
talking-head.

**Faceless ≠ mass AI slop.** This is the load-bearing caveat. YouTube's spam policy prohibits
automated/synthetic mass-production — high volumes of near-identical AI videos (same stock music +
repetitive AI imagery + AI-read scripts) and scraped/re-posted content. Good faceless content is
the opposite: genuinely informative, original, transformative. With no face to build rapport,
"authentic" means **clear narration + clean screen capture/data-viz + real expertise** — the
value carries the video. (Format scripting frameworks and hooks live in `content-formats.md`;
prose gets a humanization pass.)

| Channel | Primary faceless formats | Why it fits |
|---|---|---|
| **Dev** | **Screen-recorded demos & tutorials** (the strongest faceless format — maps directly to search-intent traffic); product/UI demonstrations; concept explainers as narrated screen + diagrams | The work is inherently on-screen (terminal, product UI, client). Show, narrate, link the relevant landing page. |
| **Local retail** | **Data-viz / slideshow + voiceover** (ratings, category/price data); narrated guides; list/ranking videos | No on-camera presence needed; the data and the selection *are* the content. Voiceover transcript auto-captions → feeds local-language search context. |
| **International** | **Data-viz / slideshow + voiceover** on market data; narrated market explainers; ranking/explainer animations | Market-data storytelling is natively faceless and natively shareable into suggested. |
| **All three** | **Faceless Shorts** (screen-capture clips, b-roll + text, single data snippet, long-form teaser) | Cheapest new-audience reach; §3e. |

Production-sustainability: pick formats you can sustain (unscripted screen-share tutorials when
you know the material cold; templated data-viz decks), outsource/automate *editing* (not
creation), repurpose one asset across long-form + Short + blog + newsletter. Sustainable faceless
production is what makes the three-channel architecture (§2) affordable.

---

## 5. Content pillars → property funnels

Each pillar exists to move a viewer from "watched the video" to "visited/installed the property."
The CTA mechanics (above-the-fold description link, pinned comment, end screens, cards, verbal
CTA, lead magnets) are owned by `traffic-conversion.md`; this section maps **which pillar points
at which funnel**.

**Two portfolio rules apply to every dev pillar, no exceptions** (restated because pillars place links):

1. If you track installs/conversions with an affiliate/referral parameter, every link to a product
   that needs attribution carries it consistently — never a bare link that forfeits attribution.
2. Every script, title, description, pinned comment, and external comment gets a humanization pass
   before publishing.

### Dev channel (tool/product posture — install + traffic)

| Pillar | Funnel destination | CTA flavor |
|---|---|---|
| Tool how-tos | the specific product page *or* the site's `/scrapers`-style hub | "The tool I used is linked below" → relevant landing page, not homepage |
| Product walkthroughs | the product/install page | demo-then-link; the install is the conversion |
| Data tooling / workflows | the site's `/studies` or `/articles` (the data study the video visualizes) | "Full data & method in the writeup" lead magnet |
| Concept explainers | an educational landing page (e.g. `/mcp-servers` or `/ai-workflows`) | soft, top-of-funnel — brand + recall, not hard install |

### Local retail channel (money-site posture — soft CTA, brand + traffic)

| Pillar | Funnel destination | CTA flavor |
|---|---|---|
| Selections / buying guides | the relevant store category/product page | "the selection is on the shop" — native, soft |
| Data decoded | the store (relevant selection) | data-literacy first, gentle pointer to the shop |
| Pairings & occasions | the store's gift/occasion page | "gift ideas" → relevant landing page |
| Behind the scenes | the store homepage/about | brand, not a hard sell |

### International channel (money-site posture — brand + intl trade traffic)

| Pillar | Funnel destination | CTA flavor |
|---|---|---|
| Market data explainers | the international content/BI offer | "deeper analysis on the site" — credible, soft |
| Is X accurate? (rating literacy) | the international site | trust-building; brand recall over hard CTA |
| Investment & trade angle | the trade/BI page | qualified intl/trade lead-gen |
| Region/category deep-dives | the relevant page | brand + suggested-feed reach |

Money-site CTAs are deliberately softer than the dev channel's: the retail/BI channels build trust
and brand for revenue properties, so the link is native and value-tied ("here's the full
analysis"), never a hard sell. The dev channel, mapping to lower-stakes tool/product pages, can be
more direct about the install. **Value before the link** on every channel (golden rule) — the
video earns the view; the CTA is secondary.

---

## Self-review

- **Niche × language resolved + justified:** §2 decides local + international channels (NOT one
  bilingual channel) and EN-primary single dev channel, justified by applying the
  one-niche-one-language focus principle to language, with trade-offs stated honestly. ✔
- **Third-language axis named as deferred:** §2 parks any additional export language explicitly as
  a future dedicated channel/track, recorded so it is never silently dropped. ✔
- **Greenfield / launch-from-zero:** §3 covers sequencing, launch pillars, the 0→100 motion,
  cadence (consistency/quality NOT volume), and how Shorts seed a new channel. ✔
- **Faceless-first:** §4 maps faceless formats per channel; faceless ≠ AI slop caveat stated. ✔
- **Earned engagement only:** 0→100 motion uses real early views, value-first external engagement,
  legitimate cross-promotion; bought/seeded views and sub4sub explicitly rejected (§3a). ✔
- **YouTube = traffic, not SEO equity:** stated up top; link-building is a separate discipline;
  nofollow noted. ✔
- **Niche focus per channel:** unrelated niches never share a channel; §1. ✔
- **Portfolio rules:** consistent affiliate/referral parameter on every link that needs it; all
  prose humanized; §5. ✔
- **Cross-refs:** `content-formats.md`, `traffic-conversion.md`, `external-engagement.md`,
  `measurement.md`, `ethics-policy.md`. ✔
