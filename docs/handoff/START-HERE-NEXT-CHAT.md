# MT-Portfolio — START HERE / AI Handoff (2026-10-17)

**Repository:** https://github.com/idev006/MT-Portfolio  
**Current objective:** Produce three **separate, genuine production-grade** Thai executive editorial infographics (A4 portrait) for the police promotion dossier, ๒๕๖๙. Owner has rejected the earlier output as **DRAFT**, not production. Do not call it FINAL until explicit owner visual approval, proofread and evidence gates.

## First actions in a fresh chat
1. Read this file, then `docs/infographic-as-code/CREATIVE-PRODUCTION-WORKFLOW-V2.md`, `README.md`, `docs/SSOT.md`, `docs/infographic-as-code/content-lock.json`, `docs/infographic-as-code/design-contract.json`, `docs/infographic-as-code/qa-checklist.md`, `docs/infographic-as-code/evidence-register.md`, and `docs/handoff/PRODUCTION-LESSONS-AND-RELEASE-GATES.md`.
2. Treat the **latest owner's corrections in content-lock** as authoritative over older narrative drafts or contradictory legacy production guides. Do not silently revert them.
3. Reconfirm available real photo/evidence files and provenance; repository paths are not proof the files are accessible in the new chat. Ask for re-upload only for actually missing critical assets.
4. Plan an art-directed, visually rich but **factually conservative** editorial layout; typeset all Thai text with actual font and proofread.
5. Generate **three independent A4 portrait PNG files** and show the images **inline in the chat**; optionally provide PDF/editable source, after inspecting exports.
6. If user requests production, do the work rather than return only a prompt, status, triptych or old files.

## Fixed content
- Main title: **สรุปผลการปฏิบัติราชการ**
- Subtitle: **ประกอบการพิจารณาแต่งตั้งข้าราชการตำรวจให้ดำรงตำแหน่งสูงขึ้น วาระประจำปี ๒๕๖๙**
- Exact organization heading: **ตำรวจภูธรภาค 6** (exception to Thai numerals)
- Person and position: use exact text in content-lock; verify against official record before formal release. No invented portrait.
- Page 1: **พัฒนาระบบงานและลดงานซ้ำ**. Owner-confirmed: Report ๑๙๑ preparation approx ๑ hour to no more than ๑ minute; cooperative documents/receipts more than ๒๐๐ pages in no more than ๑ minute. These are **owner-confirmed, supporting artifacts pending**.
- Page 2: **ใช้ข้อมูลสนับสนุนการกำกับ วางแผน และตัดสินใจ**. Cases: ฉลามบก (prior unit), IPB (prior unit), Dashboard ๑๙๑, reporting from existing radio-equipment data, and support missions. **No claim of radio database development or equipment disposal**. Dashboard ๑๙๑ belongs on P2; P1 is the report processor, not dashboard.
- Page 3: **พัฒนาคน พัฒนางาน และพัฒนาตนเองอย่างต่อเนื่อง**. Owner **explicitly confirmed ACTUAL** (a) teaching/coaching and knowledge transfer to personnel, (b) discipline supervision and enforcement of subordinates. Owner identifies **as MANAGEMENT CONCEPT** (not proven achieved outcome) goal clarification, task allocation and ability to cover each other's work. Other cases: MTSecurity / AI CCTV / Computer Vision as **ศึกษา/ต้นแบบ**; learning; ITA ๒๕๖๗; ethics recognition from police headquarters ๒๕๖๙. Check exact award text against genuine originals.
- Never invent percent savings, AI accuracy, extra honors, deployment, system screenshots, police events, personnel photos, award certificates, or achievements.

## Fixed design and delivery
- Three **individual** A4 portrait pages; minimum 2480×3508px at 300dpi, preferably 3508×4960 or higher with valid aspect ratio. Never deliver only a horizontal three-panel collage.
- Navy `#122944`, gold `#B28B48`, silver `#A7B0BA`, white and ink; elegant restrained executive style, high visual hierarchy, actual infographic storytelling rather than stacks of empty text cards.
- Thai numbers in visible content except exact organization name. Correct shaping, typography, line breaks, full text visibility; text-first rendering, not AI-generated Thai lettering.
- **NO logo AND NO logo placeholder** (supersedes outdated guides).
- Page 1 blank official portrait placeholder **height:width = 4:3**; never synthesize a person's face.
- Approved owner-supplied atmospheric photos: `1000020746.jpg`, `1000020747.jpg`, `1000020742.jpg`, `1000020739.jpg` (only if originals accessible and verified). Buildings are secondary accents, not hero; no unrelated search-result images.
- AI illustrations may be used only as **clearly conceptual/decorative** and labeled `ภาพประกอบ` where necessary. They cannot serve as evidence.
- Each real screenshot/certificate requires provenance and review for sensitive information.
- Include a real editorial visual system: large verified metrics, process/flow diagrams grounded in content, varied layout and visual weights, restrained icons, intentional typography and ample *purposeful* white space.
- Production gate: compare exported image text to locked source, inspect at A4 print scale, check actual pixels, typography, clipping, citations/provenance, security, and user approval.

## Prior failures to avoid
- Earlier 3508×4960 PNGs showed five near-identical tall empty white cards, too much blank space, weak visual storytelling, no evidence-driven graphics. Owner rejected them as DRAFT.
- A subsequent AI-generated **wide triptych** had invented 50%, 60%, 70%, 100% results, invented people/police scenes, simulated dashboards and awards, and corrupted Thai text. **REJECTED AS EVIDENCE AND NOT TO BE REUSED**. Its appearance is at most inspiration for composition/visual richness, not content, images or layout format.
- A high-resolution image is not automatically production quality. Never say “production” solely on resolution.
- Earlier assistant displayed sandbox links that did not show in user's app. When delivering, actually render/display each image in chat (e.g. using an available image display tool), plus optional verified links.

## Status
- Owner has confirmed the factual wording with subsequent P3-team corrections. `content-lock.json` is approved for textual scope, **not** independent evidence validation or final artwork.
- Genuine original award/ITA records, project screenshots and timing-test evidence may still require verification. `evidence-register.md` tracks this; any unverified claim must remain explicitly qualified.
- Next goal is a **genuinely redesigned** 3-page production candidate, not further cosmetic editing of prior drafts.

## Ready-to-paste opening prompt
> เปิด Repository `idev006/MT-Portfolio` และอ่าน `docs/handoff/START-HERE-NEXT-CHAT.md` ก่อน ตามด้วย Content Lock, Design Contract, Evidence Register และ QA Checklist จงสร้าง Infographic ระดับ Production Grade จำนวน ๓ หน้า A4 แนวตั้ง แยกเป็น ๓ ภาพ แสดงภาพจริงในแชท ใช้ข้อความล็อกตามเอกสารและคำยืนยันล่าสุดโดยไม่สร้างข้ออ้างเพิ่ม เน้น Visual Storytelling และ Editorial Design ระดับผู้บริหาร ใช้ Thai typesetting จริง ห้ามใช้ภาพ triptych เก่าหรือภาพ/ตัวเลข AI ที่แต่งขึ้น ตรวจ QC ก่อนแสดง และรายงานสิ่งที่ยังไม่ผ่านการตรวจหลักฐานอย่างตรงไปตรงมา

## Production method change — 2026-10-17
- Art-director-led hybrid workflow replaces fixed Python card-layout generation.
- Retain evidence verification, locked factual copy, actual Thai typesetting and automated preflight/export checks.
- Layout positions, image crops, negative space, and typography hierarchy are creative decisions per page; design percentages are guidance, not restrictive templates.
- Previous `make_portfolio.py` and its renderings are retained as rejected/historical drafts, never promoted to FINAL.
- Actual accessible owner-uploaded images `1000020850.png`, `1000020857.png`, `1000020742.jpg`, `1000020739.jpg` require provenance/hash verification before export. Older `.jpg` building names remain unresolved aliases.

## Owner decision — design-as-code cancelled
Do not use procedural art/layout code, Python cards or the earlier "hybrid" layout engine for any of the three pages. AI Art Direction leads creative design. Data/evidence/Thai-language validation and export QA remain mandatory; see the explicit cancellation appended to the creative workflow and current design contract.
