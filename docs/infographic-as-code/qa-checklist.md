# QA & Release Gates — Three-page Infographic

## Gate A: Source and content (mandatory)
- [ ] All content IDs in `content-lock.json` reviewed; no unapproved substantive rewriting
- [ ] Official spelling of name/position checked
- [ ] Quantitative claims supported by original evidence or documented owner confirmation
- [ ] Original ethics and ITA award wording verified
- [ ] Prior-unit attribution and prototype labels visible
- [ ] No claim of radio database or disposal
- [ ] No invented efficiencies, savings, precision, adoption or system deployment

## Gate B: Visual (mandatory)
- [ ] Exactly ๓ separate A4 portrait pages
- [ ] Header reduced; content remains visually dominant
- [ ] Thai digits throughout rendered visible copy (exclude URLs/file metadata)
- [ ] Headings use icons, not numbering
- [ ] Official portrait placeholder height:width ๔:๓
- [ ] No unit logo and no logo placeholder, per owner's latest instruction (2026-10-17)
- [ ] Statue/building: original user photos or owner-approved AI conceptual illustrations inspired by them; label illustrations appropriately
- [ ] AI illustrations are not misrepresented as authentic documentary evidence
- [ ] Legible at ๑๐๐% A4 print size; no clipping or overflow
- [ ] Navy/gold/silver/white coherent across pages
- [ ] Room for any required official signatures/certification

## Gate B2: Strategic narrative and illustrations (mandatory)
- [ ] All five agreed thematic groups represented across the three pages with their page-level key messages
- [ ] Every highlighted case explains the task/problem, actual role/action, actual result and benefit to government service
- [ ] Real operational outcomes take priority over a list of skills, software, courses or speculative future work
- [ ] No unnecessary duplicate case between pages
- [ ] Each case has a restrained purposeful visual (normally one; no more than two), or a simple icon when verified visual evidence is unavailable
- [ ] Genuine evidence images have a provenance record and caption; icons/diagrams cannot be mistaken for evidence
- [ ] No oversized decorative images, cluttered photo grids, fabricated screenshots, or AI-created incident imagery
- [ ] Text remains readable with whitespace; visuals never displace required factual copy

## Gate C: Production (mandatory)
- [ ] Text is typeset with actual Thai font; not AI-painted; no missing-glyph squares/tofu in name, rank, position, titles, or body
- [ ] Exact text comparison against approved content-lock
- [ ] Raster dimensions checked for all ๓ files
- [ ] PDF pages counted and inspected visually
- [ ] Editable source retained
- [ ] Manifest contains source revision, image provenance, output hashes
- [ ] Independent human proofreading and owner sign-off

**Release decision:** Any unchecked mandatory item → **DRAFT / NEEDS REVIEW**. Do not mark FINAL.

## Regression tests (recommended)
- Validate JSON schema/required IDs, page count and duplicate IDs.
- Scan visible text for ASCII digits and forbidden claims; flag, do not auto-correct factual text.
- Compare rendered text extraction against approved strings.
- Verify image references and aspect ratios; detect missing files.
- Generate a review report with pass/fail/unknown and evidence references.

## Owner-approved illustration and identity gates (2026-10-17)
- [ ] AI conceptual imagery may follow the uploaded reference composition without exact matching; do not treat it as a genuine evidence photo.
- [ ] Page 1 displays exact name/rank/position with independently proofread Thai glyphs.
- [ ] Page 1 has an unfilled vertical portrait placeholder (height:width = 4:3).
- [ ] No logo or logo placeholder anywhere on the three pages.
- [ ] No missing-glyph squares or corrupted Thai text anywhere; block FINAL on any occurrence.

## Superseding owner instructions (2026-10-17)
- [ ] Use user-supplied `1000020850.png`, `1000020857.png`, `1000020742.jpg`, `1000020739.jpg` as appropriate for understated background/header/footer visuals.
- [ ] Do not insert unit logos, emblem approximations or logo placeholders.
- [ ] Export three separate A4 portrait files, not a horizontally combined triptych.
- [ ] Main title is exactly `สรุปผลการปฏิบัติราชการ`, not `ผลงานที่ภาคภูมิใจ`.
- [ ] Do not invent an official portrait, certificates, application screenshots, or unapproved quantified percentages.

## Owner correction: prohibited screenshot examples (2026-10-17)
- [ ] Do not use any building, conference hall, statue, monument or landmark appearing in the latest screenshot `1000021045.jpg`; the screenshot is a negative example, not reference art.
- [ ] Do not use unrelated internet image search results as substitutes for the owner's actual locations.
- [ ] No unit logo or logo placeholder.
- [ ] Any actual place-related imagery must have explicit owner approval for the selected source; otherwise use abstract, non-location imagery.

## Art-direction release gate (2026-10-17 revision)
- [ ] Creative composition is bespoke to each page, not repeated equal-size cards or fixed-layout renderer.
- [ ] Page 1 uses editorial metric hierarchy; Page 2 uses differentiated case mosaic with grounded diagrams; Page 3 visually distinguishes actual actions, management concepts, prototypes and honours.
- [ ] Actual photographic assets have bytes/hash and source verification; do not treat `1000020850.png` and `1000020857.png` as identical to old `.jpg` names without comparing.
- [ ] Code-based output is allowed only if visual art direction and page-specific editorial layout pass independent review; no requirement to use Python for layout.
- [ ] Rendered text compared with approved content IDs, without truncation or AI-painted Thai text.
- [ ] Release remains PRODUCTION CANDIDATE until original evidence, independent proofreading and owner art approval pass.


## Mandatory hard-stop: Owner communication strategy and actual case descriptions (2026-10-17)
- [ ] SSOT §12 read and checked; don't start from program names or graphics.
- [ ] Each featured outcome uses **problem/need → owner action → evidence-qualified result → benefit to the unit**; if problem/benefit is undocumented, mark it as pending and do not invent it.
- [ ] Cooperative receipt case: hundreds of member receipts need logo + cooperative manager signature + text, formerly applied individually; batch document-marking utility saves time; >๒๐๐ pages within ≤๑ minute as owner-confirmed. Never classify it as data analytics.
- [ ] Exact “ตำรวจภูธรภาค 6”; owner rank/name/position; main topic + subtopics; compact header/footer; majority area for content; readable to senior assessors in under one minute.
- [ ] No actual unit logo; use only an empty thin dashed placeholder IF a logo area is reserved per latest owner instruction. No fake portrait; keep required empty 4:3 portrait space on P1.
- [ ] Check approved case grouping/priority against content lock and latest owner corrections; no extra unverified claims.
- [ ] Don't call an image complete if any of these checks fails. Correct copy/wireframe before production.
