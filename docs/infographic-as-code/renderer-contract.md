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
- Missing evidence or approved asset is a blocking issue; do not substitute stock or AI-generated evidence.
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
