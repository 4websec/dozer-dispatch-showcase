# On-Page SEO Audit — Dozer Dispatch homepage

*A build-in-public self-audit. Published as part of the [Dozer Dispatch showcase](../index.html).*

**Page:** https://dozerdispatch.com/ (commercial homepage, single-page site)
**Target query (assumed):** primary `shop manual voice assistant`; secondary `heavy equipment service manual app`
**Method:** 8-dimension on-page framework, scored against the live served markup.

> ⚠️ The page names no head keyword, so the target query here is *inferred*. The title/H1 recommendations depend on it — a real keyword-research pass could shift them.

---

## Score across 8 dimensions

| # | Dimension | Score | One-line |
|---|-----------|-------|----------|
| 1 | Title tag | **Needs work** | 56 chars, unique, distinct from H1 — but zero category keyword; leads with brand + emotional wedge only |
| 2 | Meta description | **Pass** | 160 chars, unique, value-prop + soft differentiator; reads as ad copy |
| 3 | Header structure | **Pass** | Exactly 1 H1, 7 logical H2, 9 H3, no skipped levels |
| 4 | Body content | **Needs work** | Strong intent answer + proof, but the head term never appears in visible copy |
| 5 | Internal links | **N/A** | Single-page site — no other pages to link to or from |
| 6 | Images & media | **Needs work** | No in-body `<img>` (the console is CSS/SVG); OG cover loads, but there's no indexable image/alt surface |
| 7 | URL slug | **Pass** | Root `/`, clean, HTTPS, canonical set |
| 8 | On-page schema | **Pass** | SoftwareApplication + Organization + FAQPage, matches visible content |

---

## The core tension

The most recent copy refresh made the page **better for humans and worse for crawlers on the head term.** The hero — *"answers in seconds, not a YouTube video"* — is a strong *click* magnet. But click-through only pays off once you're already *ranking*, and nothing on the page tells a search engine which query to rank it for. The category noun ("service manual," "shop manual," "voice assistant") is absent from the title, the H1, and the visible body.

The fix is **not** to sacrifice the wedge. It's to **prepend the category noun** so the page states both what it *feels like* (fast) and what it *is* (a shop-manual voice assistant).

---

## Critical fix

**C1 — Seed the head keyword into the title and H1.** Every recommendation keeps the voice intact and just re-inserts the missing anchor:

- **Title:** `Shop Manual Voice Assistant — Answers in Seconds | Dozer Dispatch`
- **H1:** `Your shop manual — answered in seconds, not a YouTube video.`

Both keep the anti-YouTube hook while naming the query object. The meta description already contains "shop manual" + "service techs" — it's the one place the keyword survived, so leave it.

## Important fixes

- **I1 — First visible paragraph:** answer the primary intent in the words a searcher used. One natural mention of "shop manual / service manual," for the reader — not density stuffing.
- **I2 — One H2 should carry the category + vertical.** `One tool, every machine` (currently an H3) is close — promote that idea to an H2-level phrase that names *manual*.
- **I3 — Add one real screenshot** of the console in use, with a descriptive filename (`dozer-dispatch-service-manual-voice-console.webp`) and alt text. Opens Google Images and adds a keyword-bearing element the page currently lacks.

## Nice-to-have polish

- **N1 — Title length:** the keyword title runs ~60 chars; verify it doesn't truncate on mobile SERPs.
- **N2 — Mine the FAQ schema.** The 6-question FAQPage is rich-result eligible; adding one question that literally phrases the category captures the keyword inside structured data already shipped.
- **N3 — Single-page structure caps internal linking.** Not a defect — but the moment a second indexable page exists (a vertical page, a "how it works" page), wire descriptive-anchor internal links both ways.

---

## Takeaway

Five of eight dimensions pass; the schema and header hygiene are genuinely clean. The gap is a single, high-leverage one: the page is **optimized for the click and blind for the query.** Whether that's the right trade depends on the channel — if organic search isn't a channel you're driving yet, the current emotional-first title may be the correct bet. On-page SEO only starts paying once organic is a channel you care about.
