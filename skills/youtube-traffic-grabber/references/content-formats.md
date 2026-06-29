# Content Formats — The Faceless Playbook

Assume **faceless content only** — no on-camera presenter, ever. This is not a limitation to work around; it is the operating constraint that every format here respects. Everything in the discovery doctrine (`youtube-traffic-doctrine.md`) and SEO (`youtube-seo.md`) still applies; the only thing removed is the talking head.

There are three faceless formats, mapped to the channel niches:

| Format | Channel | Best for |
|---|---|---|
| Screen-recorded dev tutorial / demo | dev (a tools/product site + its tools) | search-intent how-tos: scraping, MCP, automation |
| Data-viz / slideshow + voiceover | data/retail (a content/BI site + an e-commerce store) | explainers, rankings, market data |
| Vertical Shorts | both | top-of-funnel reach, teasing long-form |

**No on-camera formats appear here by design.** If a request asks to "film yourself" or "do a talking-head intro," redirect to one of these.

---

## The non-negotiable guardrail: genuine value, not mass-produced AI content

Before any format: faceless is fine; **faceless content farms are not.** YouTube's spam policy explicitly prohibits "automated or synthetic mass-production" — high volumes of near-identical content (the same background music + repetitive AI imagery + AI-read scripts across many videos) — and "scraped content" (re-posting others' material with no transformative value). Enforcement runs to monetization suspension and channel termination.

The line is **transformation and genuine usefulness**, not "did a machine touch it." A tool-assisted workflow is fine; a slop factory is not. Concretely:

- **Each video must teach or reveal something real** you actually know — a working technique, real market data, a genuine comparison. The tutorials come from real scraping/automation/tooling expertise; the data explainers from real, sourced data.
- **No batch-cloned videos.** Don't produce 50 near-identical "top 10" videos off a template with swapped stock footage and an AI voice. That is exactly what the policy targets.
- **Voiceover and scripts read as human.** All script/voiceover prose gets a humanization pass — this is both an authenticity and an AI-detection-risk safeguard. A script that reads as mass-generated is a liability.
- **"Faceless authentic" = clear narration + clean, original screen capture/visuals**, since there's no face to build rapport. The rapport comes from genuinely helping.

This guardrail sits above every format below. A format used to mass-produce slop violates it regardless of how the framework is followed.

---

## Format 1 — Screen-recorded dev tutorial / demo

**The strongest faceless format**, and the best practitioner-evidenced one for traffic-to-site: screen-share tutorials map perfectly to search-intent traffic (someone searched the exact problem) and to relevant-landing-page CTAs (the tool that automates the thing you just demoed). This is the dev channel's backbone.

### When to use

- The topic is a *doable* technique with a visible result: finding a hidden API, building an MCP server, configuring a tool, debugging a 403.
- There's a matching asset (a product, a tool, a solution page) the tutorial naturally leads to.
- The query is problem/how-to intent (highest conversion — see `youtube-seo.md`).

### Scripting framework

```
1. HOOK (0:00–0:15)   The problem, stated as the viewer feels it + the payoff.
                      "You're about to scrape HTML for data the site already
                       serves as clean JSON. Here's how to find it in 5 minutes."
2. PROMISE/MAP        One line on what they'll have by the end. Optional 5s.
3. DO IT (the body)   The actual walkthrough on screen, step by step, narrated.
                      Show the result early; don't save all payoff for the end.
4. PAYOFF + SCALE     It works. Then: "doing this by hand for 10k pages is the
                      slow part — the tool that does it at scale is linked below."
                      (Native bridge to the asset — value first, link second.)
5. CTA + NEXT         Verbal + on-screen CTA to the asset/landing page; point to
                      the next relevant video.
```

Often these can be **lightly scripted or unscripted** when you know the material cold (the strongest practitioner case study works this way) — bullet outline, record the screen, narrate live, then cut pauses. Don't over-engineer.

### Hook patterns (first 15s — the retention gate)

- **The expensive-mistake hook:** "Most people fight anti-bot for hours to scrape data the site hands out for free. Don't."
- **The result-first hook:** show the finished output in the first 3 seconds, then "here's exactly how."
- **The specific-promise hook:** "In the next 4 minutes you'll have a working MCP server."

### Retention notes

Show the working result early. Cut dead air and "um, let me find the…" fumbling. Add on-screen callouts at the key steps. Keep length matched to substance — a 6-minute technique shouldn't be padded to 12.

---

## Format 2 — Data-viz / slideshow + voiceover

Narrated decks, charts, ranking/list videos, explainer animations. The data/retail channel's backbone: data is inherently visual and authoritative — ratings, price movements, regional comparisons, rankings — and it explains itself well over a clean slide with a voiceover. The auto-captioned voiceover also feeds search context (`youtube-seo.md`).

### When to use

- The value is **information/insight**, not a live procedure: "the 10 best-value items right now," "what this index actually tracks," "is this overpriced?"
- You have real, sourced data to show (pulled via the Data API / managed tools / a hosted platform — never local scraping).
- Informational or comparison intent — top-of-funnel and warm, building brand for the data/retail properties.

### Scripting framework

```
1. HOOK (0:00–0:15)   A provocative number, claim, or question on screen.
                      "This product outscores items 4x its price. Here's the data."
2. STAKES             Why the viewer should care for ~5–10s. The question the
                      data answers.
3. THE DATA (body)    Slide by slide / chart by chart, narrated. One idea per
                      slide. Build the argument; reveal the ranking progressively
                      to hold attention (countdowns retain well).
4. THE TAKEAWAY       The insight, stated plainly. What to do with it.
5. CTA + NEXT         "The full ranking / the live data is on the site
                       — linked below." Verbal + on-screen. Next video pointer.
```

All voiceover prose gets a humanization pass (in the channel's language — language segmentation is a real axis, not just niche).

### Hook patterns

- **The counterintuitive-number hook:** "90% of this category is overpriced. These three aren't."
- **The question hook:** "What does this index actually measure — and why should you care?"
- **The ranking-tease hook:** "Number 1 surprised me. Let's count down."

### Retention notes

One idea per slide; change the visual frequently (static slides for 60 seconds kill AVD). Reveal rankings progressively rather than dumping the list. Keep charts legible on mobile. Don't narrate the slide text verbatim — the voiceover adds the *insight*, the slide shows the *data*.

### Authenticity note (this format's specific risk)

Slideshow + AI-voiceover is the exact recipe the spam policy's "mass-production" clause targets. The safeguard is real, sourced data + genuine analysis you stand behind + humanized narration — not a template churning out interchangeable list videos. If a plan starts to look like "50 ranking videos off one template," it has crossed the line.

---

## Format 3 — Vertical Shorts

Faceless Shorts: screen-capture clips, b-roll + on-screen text, data snippets, teasers of the long-form. The **cheapest way to reach new viewers**, on both channels.

### When to use

- To **tease** a long-form video or drive new-viewer reach (top-of-funnel — *not* the conversion step; the CTA lives on the long-form / channel).
- To repurpose: a 30-second highlight of a tutorial, a single chart from a data explainer, one sharp tip.
- To test a hook or topic cheaply before committing to a full video.

### Scripting framework

```
1. HOOK (0:00–0:02)   Instant. The single most surprising frame/claim first.
                      No intro, no logo, no "hey guys."
2. PAYOFF (body)      One idea, delivered fast. A single tip, stat, or reveal.
3. LOOP/END           End so it loops cleanly (re-watches boost reach) or lands
                      a one-line "full tutorial on the channel."
```

### Hook patterns (first 1–2 seconds — even tighter than long-form)

- Open on the result/the surprising number, on screen, immediately.
- "Stop doing X." / "This one setting…" stated in the first second.
- A bold on-screen text overlay that states the payoff before the voiceover even starts.

### Retention notes

Shorts are swiped in a second — the first frame and the clean loop drive reach more than anything else. Keep it to one idea. Don't try to fit a CTA-to-site into a Short; its job is reach, funneling to the long-form/channel where the real CTA lives.

---

## Cross-format rules

- **Faceless only.** Every framework above works with zero on-camera presence. No format here, and none added later, may require filming a person.
- **Genuine value over volume.** The mass-production guardrail governs all three. Cadence is *not* a growth lever (see the myth bust in `youtube-traffic-doctrine.md`) — quality earns the watch, not quantity.
- **Humanize the prose.** Every hook, script, and voiceover — EN and FR — gets a humanization pass.
- **Each format earns the view before the link.** The CTA system (placement, any affiliate/referral parameter, lead magnets) is in `traffic-conversion.md`; the destination must be a relevant page, not the bare homepage.
- **Repurpose, don't mass-clone.** One tutorial → a Short + a blog post + a newsletter item is healthy reuse. Fifty templated near-duplicates is the policy violation.
