# Asset Templates — Ready-to-Adapt, Per Channel × Language

The strategy and SEO modes decide *what video to make and where the link goes*; this file decides *what gets said and written*. These are scaffolds, not paste-and-ship copy. Every one is built around the same non-negotiables:

- **The view is earned, not bought.** Each template assumes real content that genuinely helps the viewer. A video that exists only as a doorway to a link is off-platform-diversion spam and gets removed — earn the watch, then offer the click.
- **Faceless-first.** Every script here works with no on-camera presenter: screen recording, data-viz/slideshow, or text-on-b-roll. None of them says "film yourself."
- **YouTube links are nofollow — traffic, not SEO equity.** These templates drive clicks-to-site, installs and brand recall. They do **not** build link equity; actual link-building is a separate discipline.
- **Carry your affiliate/referral parameter.** If you track conversions/installs with one, every link that needs attribution carries it consistently — a bare link forfeits referral attribution.
- **Disclosure where paid or sponsored.** Any paid placement (incl. promoting an owned commercial asset where the relationship isn't obvious) gets YouTube's paid-promotion toggle **and** an FTC-style spoken/written line. See `ethics-policy.md`.

> **Run the prose through a humanization pass before publishing (AI-detection-safe).** This appears under each template as a one-line reminder. A humanization pass owns the doctrine for making text read human and pass AI detectors — this file does not duplicate it. Adapt the template, localize it, *then* humanize, *then* publish. Verbatim AI-flavored scripts and descriptions are exactly the "mass-produced / inauthentic" pattern YouTube's spam policy targets.

Placeholders use `{{double-braces}}`. Anything in `[square brackets]` is an authoring note — delete it before publishing.

**Channel mapping:** dev/tech channel → a tools/product site + products (EN primary). Data/retail channel → an international BI site (EN) and a local-language store (e.g. FR). Keep distinct niches separate; resolve language-split per `channel-strategy.md`.

---

## 1. Faceless dev demo script (screen recording)

**When:** a long-form screen-recorded demo or tutorial — the strongest faceless format and the one that maps to search-intent traffic. Structure: **hook → problem → demo → CTA**. The hook earns the first 15–30s (where most drop-off happens); the demo delivers the promised value in full; the CTA is offered only after the value lands. This is EN-primary (dev channel).

### EN

```
[Faceless screen recording + voiceover. No face on camera. Keep the screen the star.]

— HOOK (0:00–0:15) — say the payoff first, show the end result on screen —
{{One sentence naming the exact outcome the viewer searched for: "Here's how to get clean {{X}} data without writing your own scraper."}}
[On screen: the finished result / the structured output, before you explain anything.]

— PROBLEM (0:15–0:45) — name the pain, briefly, so the demo feels necessary —
{{1–2 sentences on why the obvious approach is painful: e.g. "Most people reach for a headless browser and end up babysitting proxies and broken selectors."}}
[Optional: show the broken/slow way for 3–5s as contrast. Don't dwell — momentum.]

— DEMO (0:45–~end) — deliver the full method on screen, step by step —
{{Step 1 — concrete, narrated as you do it on screen.}}
{{Step 2 — the actual technique; give away the real method, don't tease it.}}
{{Step 3 — the result; show the clean output again, now that they understand it.}}
[Pacing: a visual change every ~15–30s — cut, zoom, highlight, on-screen label — to hold retention.]

— CTA (last 20–30s) — value-tied, single, non-pushy —
{{Verbal + on-screen: "If you'd rather not maintain the session and proxy layer yourself, I left a link to the tool that does exactly this in the description."}}
[On screen end-card: the destination. Card mid-video only if a link is genuinely relevant at that moment.]
```

Filled (product demo, dev channel):

```
HOOK: "Here's how to pull every merchant price into a clean spreadsheet — no headless browser, no proxy headaches." [Show the finished CSV.]

PROBLEM: "Most tutorials spin up a headless browser and then spend a week fighting rate limits and rotating tokens. You don't need a browser for this at all."

DEMO: [Show the internal JSON endpoint in DevTools → replay with the region's query param → structured rows. Then show the maintained tool doing the same hands-off.]

CTA: "The DevTools route above is free and I'd start there. If you'd rather not maintain the proxy and session logic, the tool in the description does it for you — link below."
[Description link → https://apify.com/your-username/price-scraper?your-referral-param]
```

> Run the prose through a humanization pass before publishing (AI-detection-safe).

### FR

```
[Capture d'écran + voix off. Pas de visage à l'écran. L'écran est la vedette.]

— ACCROCHE (0:00–0:15) — annoncer le résultat d'abord, le montrer à l'écran —
{{Une phrase nommant le résultat exact recherché : « Voici comment récupérer des données {{X}} propres sans coder son propre scraper. »}}
[À l'écran : le résultat final / la sortie structurée, avant toute explication.]

— PROBLÈME (0:15–0:45) — nommer la douleur, brièvement —
{{1–2 phrases : pourquoi l'approche évidente est pénible.}}

— DÉMO (0:45–~fin) — livrer toute la méthode à l'écran, étape par étape —
{{Étape 1 — concrète, narrée pendant qu'on la fait.}}
{{Étape 2 — la vraie technique ; donner la méthode, ne pas la teaser.}}
{{Étape 3 — le résultat ; remontrer la sortie propre.}}
[Rythme : un changement visuel toutes les ~15–30s pour tenir la rétention.]

— CTA (20–30 dernières s) — lié à la valeur, unique, sans forcer —
{{Voix + texte à l'écran : « Si tu préfères ne pas maintenir tout ça toi-même, le lien est en description. »}}
```

> Faire relire la prose par une passe d'humanisation avant publication (sûr face à la détection IA).

---

## 2. Faceless data explainer script (data-viz / slideshow)

**When:** a narrated deck / data-viz / ranking video — charts, list videos, market explainers built on real data. Faceless by nature: slides + voiceover. The spoken keywords feed the auto-caption and the search context, so narrate the topic plainly. **Local language for the store; EN for the international BI site.** Same hook→problem→payoff→CTA spine, slower and more editorial than the dev demo.

### EN (international BI site)

```
[Slideshow / data-viz + voiceover. No presenter. Each slide = one idea.]

— HOOK (0:00–0:15) — the surprising data point first —
{{One striking, true number on screen: "Secondary-market prices moved {{X}}% in {{period}} — here's what the data actually shows."}}

— SETUP (0:15–0:45) — why a single data point misleads —
{{1–2 sentences: a single retailer's price is a snapshot; aggregated market data gives the real curve.}}

— PAYOFF (0:45–~end) — walk the charts, one insight per slide —
{{Chart 1 — the trend, narrated.}}
{{Chart 2 — the comparison / ranking that makes it concrete.}}
{{Chart 3 — the takeaway a buyer can act on.}}
[Cite the data source on screen — accuracy is non-negotiable; no inflated claims.]

— CTA (last 20–30s) — value-tied —
{{"If you want the full pricing breakdown behind these charts, it's linked in the description."}}
[Destination = the relevant page, not the homepage.]
```

> Run the prose through a humanization pass before publishing (AI-detection-safe).

### FR (local-language store)

```
[Diaporama / data-viz + voix off. Pas de présentateur. Une slide = une idée.]

— ACCROCHE (0:00–0:15) — le chiffre qui surprend, d'abord —
{{Un chiffre vrai et marquant à l'écran : « Le prix moyen d'un {{produit}} a bougé de {{X}}% en {{période}} — voici ce que disent vraiment les données. »}}

— MISE EN PLACE (0:15–0:45) — pourquoi un prix isolé trompe —
{{1–2 phrases : un prix isolé est un instantané ; les données marché donnent la vraie courbe.}}

— LE FOND (0:45–~fin) — dérouler les graphes, une idée par slide —
{{Graphe 1 — la tendance, narrée.}}
{{Graphe 2 — la comparaison / le classement qui rend ça concret.}}
{{Graphe 3 — le conseil actionnable pour l'amateur ou l'acheteur.}}
[Citer la source des données à l'écran — l'exactitude est non négociable, aucun chiffre gonflé.]

— CTA (20–30 dernières s) — lié à la valeur —
{{« Si tu veux le détail derrière ces graphes, le lien est en description. »}}
[Destination = la page pertinente, pas la home.]
```

> Faire relire la prose par une passe d'humanisation avant publication (sûr face à la détection IA).

---

## 3. Short script (<60s, hook-first)

**When:** a vertical Short — top-of-funnel reach to *new* viewers, the cheapest discovery surface. One idea, hook in the first 1–2 seconds, no slow intro. Faceless: screen-capture clip, b-roll + text, or a single data snippet. Treat the Short as a teaser that funnels to the long-form or the channel — not as the conversion step itself (links in Shorts descriptions convert weakly).

### EN

```
[Vertical 9:16. Faceless. Hook in frame 1 — no logo intro, no "hey guys".]

— HOOK (0:00–0:02) — the question or payoff, on screen as text too —
{{"You don't need a headless browser to scrape {{site}}."  /  "{{Item}} just did something weird in the data."}}

— PAYOFF (0:02–0:50) — deliver the one idea, fast —
{{The single insight or the one-step trick. On-screen text mirrors the voiceover. One visual beat ~every 5–10s.}}

— LOOP / CTA (0:50–0:60) — point to the long-form, not a hard link —
{{"Full breakdown on the channel."  /  "Long version's pinned in the comments."}}
[Shorts CTA = watch the long-form or subscribe; save the off-platform click for where it converts.]
```

> Run the prose through a humanization pass before publishing (AI-detection-safe).

### FR

```
[Vertical 9:16. Sans visage. Accroche dès l'image 1 — pas d'intro logo, pas de « salut à tous ».]

— ACCROCHE (0:00–0:02) — la question ou le résultat, aussi en texte à l'écran —
{{« Pas besoin de navigateur headless pour scraper {{site}}. »  /  « Ce {{produit}} a fait un truc bizarre dans les données. »}}

— LE FOND (0:02–0:50) — livrer l'idée unique, vite —
{{L'insight unique ou l'astuce en une étape. Le texte à l'écran double la voix off. Un temps visuel toutes les ~5–10s.}}

— BOUCLE / CTA (0:50–0:60) — renvoyer vers le long format, pas un lien dur —
{{« Version complète sur la chaîne. »  /  « Le long format est épinglé en commentaire. »}}
```

> Faire relire la prose par une passe d'humanisation avant publication (sûr face à la détection IA).

---

## 4. Title templates (search-intent + curiosity)

**When:** every video. Two families — **search-intent** (matches what someone types; wins on Search, the highest-converting traffic) and **curiosity** (wins the click on Home/Suggested). Pick by where you expect the video to surface. Titles must be **accurate** — deceptive/clickbait titles that don't deliver are an enforceable spam violation and can get the video removed. No ALL CAPS, no `!!!!!`.

### EN

```
SEARCH-INTENT (lead with the keyword/query):
- How to {{outcome}} without {{the painful obvious way}}
- {{Task}} in {{N}} steps — {{tool/method}}
- {{Site}} data: the {{free/fast}} way to {{outcome}}

CURIOSITY (true, not bait):
- Why {{common approach}} is the wrong way to {{task}}
- I {{did X}} so you don't have to — here's what the data showed
- The {{adjective}} thing nobody tells you about {{topic}}
```

Filled: `How to scrape product prices without a headless browser` · `Prices moved 14% this quarter — here's what the data shows`

### FR

```
INTENTION DE RECHERCHE (mot-clé en tête) :
- Comment {{résultat}} sans {{la méthode pénible évidente}}
- {{Tâche}} en {{N}} étapes — {{outil/méthode}}
- Données {{site}} : la méthode {{gratuite/rapide}} pour {{résultat}}

CURIOSITÉ (vraie, pas appât) :
- Pourquoi {{approche courante}} est la mauvaise façon de {{tâche}}
- {{Produit}} : ce que les données disent vraiment des prix
- Le détail que personne ne dit sur {{sujet}}
```

> Run the prose through a humanization pass before publishing (AI-detection-safe). / Faire relire par une passe d'humanisation.

---

## 5. Description template (above-the-fold link + value + timestamps)

**When:** every video. Structure: **one-line value hook → the link (above the fold, before "...more") → fuller value → timestamps → secondary links**. Lead with a value line, not a raw URL as the literal first token (that reads promotional and costs on-platform CTR). The above-the-fold link is for clicks-to-site; it is nofollow — traffic, not equity.

### EN

```
{{One-line value hook restating what the viewer gets.}}

👉 {{What the link gives them}}: {{funnel URL — carry your affiliate/referral parameter if you track attribution}}

{{2–4 lines of genuine context: what the video covers, who it's for, the method.}}

Timestamps:
0:00 {{Hook}}
0:15 {{Problem}}
0:45 {{Demo / payoff}}
{{mm:ss}} {{CTA}}

{{Secondary link(s): channel, related video, lead magnet — relevant page, not homepage.}}
[If this video contains paid promotion: state it here in plain language AND toggle YouTube's paid-promotion box. See ethics-policy.md.]
```

Filled above-the-fold link: `👉 The tool that does this hands-off: https://apify.com/your-username/price-scraper?your-referral-param`

### FR

```
{{Une ligne d'accroche valeur qui redit ce que le viewer obtient.}}

👉 {{Ce que le lien apporte}} : {{URL de funnel — porte ton paramètre d'affiliation/referral si tu traces l'attribution}}

{{2–4 lignes de contexte sincère : ce que couvre la vidéo, pour qui, la méthode.}}

Chapitres :
0:00 {{Accroche}}
0:15 {{Problème}}
0:45 {{Démo / le fond}}
{{mm:ss}} {{CTA}}

{{Lien(s) secondaire(s) : chaîne, vidéo liée, lead magnet — page pertinente, pas la home.}}
[Si la vidéo contient une promotion payée : le dire ici en clair ET cocher la case promotion payée de YouTube. Voir ethics-policy.md.]
```

> Run the prose through a humanization pass before publishing (AI-detection-safe). / Faire relire par une passe d'humanisation.

---

## 6. Pinned comment template

**When:** every video, posted by the channel and pinned. Reinforces the link with *added* value (not a bare repeat of the description). Cheap, visible, editable after publish. This is your own comment on your own video — legitimate, unlike dropping links on others' videos.

### EN

```
{{One genuinely useful addition: a caveat, a follow-up tip, or the answer to the question this video predictably raises.}}
{{What/why the link}}: {{funnel URL — your affiliate/referral parameter on links that need attribution}}
[Optional: invite a real question — "What would you want covered next?"]
```

Filled: `Heads-up: set your region's query param or you'll get mixed currencies. Hands-off version: https://apify.com/your-username/price-scraper?your-referral-param — what site should I cover next?`

### FR

```
{{Un ajout réellement utile : un bémol, une astuce de suivi, ou la réponse à la question que la vidéo soulève.}}
{{Quoi/pourquoi le lien}} : {{URL de funnel — ton paramètre d'affiliation/referral sur les liens à tracer}}
[Optionnel : inviter une vraie question — « Quoi traiter ensuite ? »]
```

> Run the prose through a humanization pass before publishing (AI-detection-safe). / Faire relire par une passe d'humanisation.

---

## 7. External comment template (value-first + disclosure)

**When:** commenting on *another creator's* video where you have something genuinely useful to add. **Value-first, relevant, disclosed — never a link drop.** Lead with a complete, helpful comment that stands on its own; mention your asset only if it's the genuine best answer, and disclose your affiliation. High-volume / repetitive "check out my channel" comments across videos are enforceable comment spam — that tactic is banned (see `ethics-policy.md`). Most of the time the right external comment has **no link at all** — it builds recognition, and the curious click your profile.

### EN

```
[Comment on a video where your input genuinely helps. Read the video first.]

{{Specific, useful reaction or addition that stands alone — show you watched, add real value, 1–3 sentences.}}

[Only if your asset is genuinely the best answer AND it fits naturally:]
(Full disclosure: I build {{property}}.) {{One sentence on how it solves the exact thing discussed}} — {{funnel URL, affiliate/referral parameter on links that need attribution}}. The manual way works fine too.
```

Filled: `Good walkthrough. One thing that saved me a ton of time: this site serves prices from an internal JSON endpoint, so you can skip the browser entirely. (Full disclosure: I build scraping tools.) If you'd rather not maintain the session layer: https://apify.com/your-username/price-scraper?your-referral-param — but the DevTools route is free.`

### FR

```
[Commenter une vidéo où ton apport aide vraiment. Regarder la vidéo d'abord.]

{{Réaction ou ajout précis et utile qui tient seul — montrer qu'on a regardé, apporter de la valeur, 1–3 phrases.}}

[Seulement si ton asset est vraiment la meilleure réponse ET que ça vient naturellement :]
(Transparence : je développe {{propriété}}.) {{Une phrase sur comment ça résout exactement le sujet}} — {{URL de funnel, paramètre d'affiliation/referral sur les liens à tracer}}. La méthode manuelle marche aussi.
```

> Run the prose through a humanization pass before publishing (AI-detection-safe). / Faire relire par une passe d'humanisation.

---

## Localizing to other markets

These are EN + FR starters. A site can be multilingual (EN/FR/ES/PT/DE/AR/HI) and a niche itself can span languages — but a canned translation posted verbatim reads as inauthentic and underperforms. To extend a market: keep the structure, rewrite idiomatically in the target language (the actual word a native uses), match the channel's language to its audience, then run the result through a humanization pass. All non-negotiables hold in every language: earned views, faceless, nofollow-traffic framing, consistent affiliate/referral parameter where used, paid promo disclosed.

---

## Quick adaptation checklist (run before publishing any asset)

1. **Earned?** Real content that helps the viewer even if you strip the link out. If it's a doorway to a link, it's spam — rebuild.
2. **Faceless?** No on-camera presenter. Screen-rec / data-viz / text-on-b-roll only.
3. **Channel right?** Distinct niches separate; language matches the channel's audience and landing page.
4. **Title accurate?** Delivers what it promises. No clickbait, no ALL CAPS, no `!!!!!`.
5. **Link placed, not buried?** Above the fold after a value line; relevant page, not homepage.
6. **Attribution?** Affiliate/referral parameter carried consistently on links that need it. No bare link that forfeits attribution.
7. **nofollow understood?** This is traffic/brand, not link equity. Link-building is a separate discipline.
8. **Paid?** Sponsored or promoting an owned asset where the relationship isn't obvious → YouTube paid-promotion toggle + FTC-style line. See `ethics-policy.md`.
9. **Humanized?** Prose run through a humanization pass (AI-detection-safe) as the last step before publishing.
