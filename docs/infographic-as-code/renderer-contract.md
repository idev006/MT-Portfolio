# Renderer Contract — AI / Designer / Software

## Inputs
1. `content-lock.json` — text and item IDs. Text is **not final approved yet**.
2. `design-contract.json` — layout, typography, assets and export contract.
3. `evidence-register.md` — source provenance and verification.
4. Approved local asset manifest containing filenames, hashes, allowed uses and captions.

## Non-negotiable separation
- **Content owner** approves factual copy and claim scope.
- **Renderer** chooses spacing, icons, card treatment and image cropping within contract.
- Renderer **must not** alter factual claims, units, dates, metrics, attribution or award wording.
- Missing authentic evidence must not be replaced with AI-generated evidence. Owner-approved AI illustrations are allowed for decorative or conceptual roles, visibly distinct from proof; absence of authentic proof remains a verification issue.
- Render all Thai as editable typeset text, never as generative image text.

## Algorithm
1. Load and validate structured inputs.
2. Stop with review report if content approval or evidence gates are incomplete; optional watermarked preview is allowed.
3. Resolve user-approved images and verify file hashes/provenance.
4. Layout three A4 pages using wireframe v1 and text-first hierarchy.
5. Preserve approved wording exactly; if it does not fit, revise layout, not the claims.
6. Run QA checklist and create manifest with versions, hashes and unresolved issues.
7. Export separate PNG, PDF and editable source.
8. Mark FINAL only after proofread, compliance review and owner approval.

## Minimal release manifest
```json
{
  "status": "DRAFT",
  "content_spec": "docs/infographic-as-code/content-lock.json",
  "design_spec": "docs/infographic-as-code/design-contract.json",
  "content_approved": false,
  "evidence_verified": false,
  "outputs": [],
  "issues": ["Pending original evidence and owner content lock approval"]
}
```

## Reusable AI instruction
Read the project's SSOT, the three-page narrative, and all files in `docs/infographic-as-code/`. Do not write new factual copy. Treat the content lock as **pending** until explicitly approved. Generate only an accurately labeled draft preview if evidence or approvals are outstanding. Use document-first typography, three A4 portrait pages, Thai digits, approved assets, compact headers, icon headings, official portrait placeholder and dashed logo placeholders. Return a QA report listing every unresolved claim.

## Approved strategic content and restrained illustrations (v1.1)
- The three pages summarize **ผลการปฏิบัติราชการ**, not a technical portfolio or personal CV.
- Preserve the five thematic groups and their key messages from `design-contract.json`; show each case as ภารกิจ/ปัญหา → บทบาท/การปฏิบัติ → ผลที่เกิดขึ้น → ประโยชน์ต่อราชการ.
- Use one purposeful visual per case by default; at most two where genuine evidence requires it. Prefer verified actual screenshots/photos, then verified process diagrams, then understated line icons.
- Balance whitespace, text and visuals by significance; do not force equal-sized grids or overdecorate. AI decorative/conceptual illustrations inspired by user references are permitted; never imply an AI scene, award or screenshot is an authentic record.
- Never shrink or alter locked factual text just to make room for an illustration. If no authentic asset is available, use an understated icon, clearly identified AI conceptual illustration, or labeled placeholder in DRAFT.
- Repeated cases across pages must be consolidated to avoid wasted space. Ethics awards are not technology achievements; prototypes must be visibly labeled.
- These strategy/layout instructions are approved by the owner; factual content approval and evidence gates remain pending.

## Owner approval: AI illustration policy (2026-10-17)
- The owner authorizes AI-created visual illustrations inspired by supplied references; exact likeness is not required.
- This does **not** authorize fabricated proof, official portrait, award document, or real-system screenshot.
- Use source-of-truth text typesetting independent from AI-generated image pixels.
- Final review must detect Thai tofu/missing glyph squares; the previous draft exhibited font rendering defects.
- Page 1 must visibly contain rank/name/position, an empty 4:3 vertical portrait slot, and a thin dashed empty square for the unit logo.
