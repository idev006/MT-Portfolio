# Word Production Specification — หนังสือประเมิน ๒๕๖๙
สถานะ: DRAFT SPEC v1.0 สำหรับใช้สร้าง **ไฟล์ใหม่** เท่านั้น (2026-10-17)

## 1. File and governance
- Output: editable .docx; PDF export only after quality review. File naming: MT-Portfolio-FullBook-2569_vNN_DRAFT.docx; FINAL only with owner approval.
- Source documents and photos on original Google Drive are **READ ONLY**. Never move, edit, rename, overwrite or replace them.
- New exports/images go to **GPT-WORK** https://drive.google.com/drive/folders/1fPDeHSReEJEl0S2nbrZQGBlgpytFYR8e as newly named files; test upload of binary DOCX before promising save completion.
- GitHub is the versioned SSOT of editorial/structure/claim/evidence control. Never commit unredacted private identifiers or unauthorized source images.

## 2. Page / typography
- ISO A4 portrait 210 × 297 mm, body primary Thai-compatible font **TH Sarabun New**, fallback **Sarabun** (must verify installed environment/render).
- Baseline: normal body 16 pt, chapter heading 22–24 pt, level-2 18–20 pt, level-3 16–18 pt; captions 13–14 pt. Explicitly test print legibility and pagination, revise as needed.
- Page margins baseline: top/bottom 20–22 mm, left/right 22–25 mm, binding margin if print shop requires.
- Body line spacing around 1.05–1.15; paragraph after 4–6 pt. Avoid widow/orphan lines, split captions, lone headings and clipped tables.
- Consistent page numbering (front matter optional Thai-number roman-equivalent policy to confirm, body Arabic/Thai per official style); headers/footers unobtrusive; no unverified agency insignia.

## 3. Semantic structure (editable Word)
- Use Heading 1 for **mandatory headings ๑–๑๓**; “การเข้าร่วมกิจกรรม” is an additional unnumbered *section divider*, not a replacement of headings ๑๐–๑๒.
- Section title ๑๓ **is separate** from activities.
- Use Heading 2/3 for subheads. Automatic TOC derived from real Word heading styles, do not type fake page numbers.
- Use Word paragraph/table objects for text and data. Do not flatten textual pages to full-page images.
- One-page/three-page summaries may be inserted as designed pages but must not replace mandatory chapters or cause duplicate full narratives.

## 4. Visual design
- Colors: Navy #122944 / Gold #B28B48 / Silver #A7B0BA / White; accent sparingly. Main content white for readable institutional book.
- Template page families: cover, front matter, major-section divider, chapter opener, evidence-led case study, duty page, activity photo page, certificate index, appendix/evidence page.
- Major claims in text + source ID; graphics explain, not pretend to be evidence. Distinguish screenshot of real tool, edited crop, illustrative diagram.
- Photos: retain aspect ratio; use consistent 2-column or editorial compositions, readable caption: activity/role/date/source when confirmed.
- Personal data in screenshots should be redacted on **new working copies**, never on originals. Must disclose substantive modifications to evidence images when relevant.

## 5. Data schema for assembling each chapter
```yaml
chapter_id: "05"
mandatory_heading_verbatim: "..."
key_message: "..."
priority_items:
  - work_id: "PERF-01"
    claim_ids: ["CLM-001"]
    evidence_ids: ["EVD-001"]
    status: "OWNER_CONFIRMED_PENDING_EVIDENCE"
images:
  - asset_id: "IMG-001"
    src: "read_only_drive_url"
    caption: "..."
    figure_type: "real_screenshot|real_photo|illustration"
    verified: false
```
Each work has exactly one canonical detail chapter; other mentions cross-reference work ID. Images sourced by exact file ID after inspection, not just folder name.

## 6. Quality gates before delivery
1. Validate mandatory headings coverage (๑–๑๓), grouping ๑๐–๑๒ and separation of ๑๓.
2. Check evidence IDs, statuses and the role of owner versus team.
3. Export DOCX, **render every page to images** using the installed DOCX skill renderer, inspect all pages and iterate.
4. Check Thai glyphs, tables/captions, broken lines, TOC, page numbers, embedded image quality, no personal data leakage, editable body text.
5. Only deliver as draft until owner confirms factual and stylistic accuracy; save newly named file to GPT-WORK after successful actual upload check.

## 7. No-go
- No invented metrics, awards, dates, faces, screens or deployment.
- No claimed official alignment with later policy for earlier work.
- No book release without independent proofread and owner review.
