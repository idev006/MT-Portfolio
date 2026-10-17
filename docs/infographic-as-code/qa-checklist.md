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
- [ ] Logo placeholder thin dashed; no logo generated
- [ ] Statue/building from approved user attachments only
- [ ] No synthetic evidence imagery
- [ ] Legible at ๑๐๐% A4 print size; no clipping or overflow
- [ ] Navy/gold/silver/white coherent across pages
- [ ] Room for any required official signatures/certification

## Gate C: Production (mandatory)
- [ ] Text is typeset with actual Thai font; not AI-painted
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
