# Deliverables Relationship Map & Submission Action Guide (v8)

**Manuscript:** *Tool Presence Is Not Capability: AI Marketing Technology Signals and Customer-Facing Performance Across the Firm-Size Spectrum*  
**Author:** Ke Li (Associate Professor, Department of Business and Administration, Keene State College; ORCID: `https://orcid.org/0009-0002-9744-3547`)  
**Target Journal Ladder:** *Journal of Business Research (JBR)* → *Psychology & Marketing* → *Journal of Retailing and Consumer Services (JRCS)*  
**Last Updated:** November 23, 2026

---

## 1. How All Deliverables Relate to Each Other

Every deliverable flows from **one master source folder** (`E:\AI_research\03_working_paper\chapters_v8\`) into **four distinct destinations**, separated strictly by audience so you never accidentally break double-blind peer review:

```text
E:\AI_research\03_working_paper\chapters_v8\*.md   (Single source of truth)
   │
   ├──► [DESTINATION A: Journal Submission Portal — Elsevier Editorial Manager / JBR]
   │       • submission_v8\JBR_Cover_Letter.md                 (Editor only)
   │       • submission_v8\Title_Page_v8.docx                  (Editor only — with name & ORCID)
   │       • submission_v8\Manuscript_Blinded_v8.docx          (Reviewers + Editor — 0 PII)
   │       • submission_v8\Web_Appendix_v8.docx                (Reviewers + Editor — 0 PII, Tables W1–W7)
   │       • submission_v8\Figure_1_Conceptual_Model_300dpi.png (Standalone 300-DPI artwork)
   │       • Research Highlights (5 bullets <= 85 chars from chapters_v8\00_front_matter.md)
   │
   ├──► [DESTINATION B: Blind Data Repository — Figshare / ResearchBox / Editorial Manager]
   │       • submission_v8\Replication_Package_Blind.zip       (Zipped copy of 07_osf_replication_package\, 34 files, 0 PII)
   │
   ├──► [DESTINATION C: Email to 3–5 Marketing Faculty Raters — Task 1 (Before Submission)]
   │       • submission_v8\Expert_Rater_Recruitment_Email.md          (Copy/paste email templates)
   │       • 07_osf_replication_package\04_validation\Rater_Instructions.docx
   │       • 07_osf_replication_package\04_validation\Rater_Response_Form.xlsx
   │       • submission_v8\Executive_Benchmark_Brief_Practitioners.docx (Optional 1-page thank-you / practitioner brief)
   │
   └──► [DESTINATION D: Local Computer / Personal Archive — DO NOT UPLOAD TO JOURNAL]
           • 03_working_paper\AI_Marketing_Paper_v8.docx       (Full non-blinded master — SSRN / dossier / colleagues)
           • 03_working_paper\AI_Marketing_Paper_v8_full.md    (Full assembled markdown)
           • 03_working_paper\AI_Marketing_Paper_v7.*          (Untouched v7 backup)
           • submission_v8\run_browser_audit_50_firms.mjs & raw audit helpers/screenshots
```

---

## 2. Where to Put Each File (Exact Destination Tables)

### Destination A — Upload to the Journal Submission Portal (*JBR* / Elsevier Editorial Manager)

Double-blind peer review requires splitting author-identifying files (visible to the editor only) from anonymized files (sent to reviewers). Upload each file into its matching portal slot:

| File Path | Portal Slot ("Item Type") | Who Sees It | Pre-Upload Action Needed |
| --- | --- | --- | --- |
| `submission_v8\JBR_Cover_Letter.md` | **Cover Letter** (copy/paste into portal box or save as `.docx`) | Editor only | Replace `[Insert Institutional Email]` and date; verify 5 suggested reviewers |
| `submission_v8\Title_Page_v8.docx` | **Title Page (with Author Details)** | Editor only | Fill in `[Insert Institutional Email]`, funding statement, and acknowledgments |
| `submission_v8\Manuscript_Blinded_v8.docx` | **Manuscript (without Author Details)** | Reviewers + Editor | Update once Task 1 rater statistics are inserted (0 PII verified) |
| `submission_v8\Web_Appendix_v8.docx` | **e-Component / Supplementary Material** | Reviewers + Editor | Update once Task 1 rater statistics are inserted (0 PII verified; Tables W1–W7) |
| `submission_v8\Figure_1_Conceptual_Model_300dpi.png` | **Figure** *(only if portal asks for separate figure files; already embedded in manuscript)* | Reviewers + Editor | Ready as-is (300 DPI) |
| 5 bullets from `chapters_v8\00_front_matter.md` | **Highlights** (Elsevier separate `.docx` or portal form) | Reviewers + Editor | Ready as-is (all 5 verified $\le 85$ characters: 83, 85, 85, 84, 84) |

> **Double-Blind Safety Rule:** Never upload `AI_Marketing_Paper_v8.docx` into the blinded manuscript slot—it contains your name, affiliation, and ORCID on Page 1.

---

### Destination B — Upload to a Blind Repository (Figshare, ResearchBox, or Editorial Manager)

*(Note: OSF permanently disabled creation of new OSF Projects on November 16, 2026; use Figshare, ResearchBox, or Elsevier Editorial Manager supplementary files instead.)*

| File Path | Where to Put It | Purpose & Follow-Up |
| --- | --- | --- |
| `submission_v8\Replication_Package_Blind.zip` | Upload to **Figshare** (generate a *Private Link* for double-blind peer review), **ResearchBox**, or upload directly as a supplementary `.zip` in **Elsevier Editorial Manager** | Contains all 34 anonymized replication files: datasets (`01_data/`), Python + Node econometric scripts `step1`–`step5` (`02_code/`), SmartPLS 4 Excel reports + logs (`03_outputs_and_smartpls/`), and 50-firm live-browser audit + rater forms (`04_validation/`). After uploading, paste the blind view-only URL into Section 3.4 of the manuscript. |

*(Detailed upload walkthroughs are in `submission_v8\Final_Submission_Logistics_Guide.md` and `submission_v8\OSF_Upload_Guide.md`.)*

---

### Destination C — Email to 3–5 Marketing Faculty Raters (Task 1 — *Do Before Final Submission*)

| File Path | How to Use It | Purpose |
| --- | --- | --- |
| `submission_v8\Expert_Rater_Recruitment_Email.md` | Copy/paste into your email client | Contains 5 ready-to-send templates (warm short invite, formal colleague invite, follow-up reminder, thank-you email, and incentive menu) |
| `07_osf_replication_package\04_validation\Rater_Instructions.docx` | Email attachment #1 | 1-page taxonomy & scoring rubric for the 26 detected tools |
| `07_osf_replication_package\04_validation\Rater_Response_Form.xlsx` | Email attachment #2 | Protected dropdown spreadsheet (~10 minutes to complete) that raters email back |
| `submission_v8\Executive_Benchmark_Brief_Practitioners.docx` | Email attachment #3 *(or send as a thank-you after completion; also ideal for LinkedIn / conference handouts)* | 1-page visual executive benchmark brief summarizing the paper's key empirical insights |

---

### Destination D — Keep Locally on Your Computer (Do **NOT** Upload to the Journal)

- **Complete Non-Blinded Master Manuscript:** `03_working_paper\AI_Marketing_Paper_v8.docx`
  - Keep for your personal reference, promotion/tenure dossier, sharing with friendly reviewers, or posting as a working paper on **SSRN / ResearchGate** (Elsevier/*JBR* permits preprints prior to acceptance).
- **Editable Source Markdown & Vector Graphics:**
  - `03_working_paper\chapters_v8\*.md` (chapter-by-chapter sources)
  - `03_working_paper\AI_Marketing_Paper_v8_full.md` (assembled markdown)
  - `submission_v8\Web_Appendix_v8.md` and `submission_v8\Executive_Benchmark_Brief_Practitioners.md`
  - `submission_v8\Figure_1_Conceptual_Model.svg` (scalable source artwork)
- **50-Firm Live-Browser Validation Audit Working Files (Already Summarized in Manuscript & Replication ZIP):**
  - `submission_v8\run_browser_audit_50_firms.mjs`
  - `submission_v8\Manual_Audit_50_Firms_COMPLETED.csv`, `Manual_Audit_50_Firms.xlsx`
  - `submission_v8\Launch_Audit_Batch.ps1`, `Audit_Helper_50_Firms.html`
  - `submission_v8\audit_screenshots\` (visual verification screenshots)
  - *(Clean reconciled summary files `browser_audit_50_firms_reconciliation.csv` and `browser_audit_50_firms_summary.txt` are already copied inside `Replication_Package_Blind.zip`.)*
- **Untouched Previous Version Backup:**
  - `03_working_paper\AI_Marketing_Paper_v7.docx` and `AI_Marketing_Paper_v7_full.md`

---

## 3. Recommended Step-by-Step Action Sequence

### Step 1: Complete Task 1 — Expert Rater Panel (Highest Value Pre-Submission Step)
1. Use `submission_v8\Expert_Rater_Recruitment_Email.md` to email **3–5 marketing or information systems faculty** with `Rater_Instructions.docx` and `Rater_Response_Form.xlsx` attached.
2. When 3–5 completed `.xlsx` spreadsheets come back, place them in a folder inside `E:\AI_research\` (e.g., `E:\AI_research\08_rater_responses\`).
3. Compute Fleiss's $\kappa$, Krippendorff's $\alpha$, and the strict AI-only robustness regression, then update the final `[PENDING]` cells in `03_method.md`, `04_results.md`, and `Web_Appendix_v8.md`, and rebuild all `.docx` files and `Replication_Package_Blind.zip`.
   - *Why do this before submitting?* Reviewers at *JBR* and *Psychology & Marketing* will immediately inspect whether Google Tag Manager / Google Analytics belong in an "AI marketing technology" index. Having both (a) our already-completed **Option 2-Hybrid** GTM decomposition (Table 6 & Table W7) and (b) independent expert-panel inter-rater agreement removes the #1 construct-validity objection before Desk Review.

### Step 2: Upload the Final Blind Replication Package
1. After Step 1 updates `Replication_Package_Blind.zip`, upload the `.zip` (or extracted contents of `07_osf_replication_package\`) to **Figshare** (using a *Private Link* for peer review) or **ResearchBox**.
2. Paste the blind view-only URL into Section 3.4 of the manuscript (and re-export `Manuscript_Blinded_v8.docx` and `AI_Marketing_Paper_v8.docx`).

### Step 3: Fill In Remaining Author Placeholders
1. Open `submission_v8\Title_Page_v8.docx` and fill in:
   - Your institutional email address
   - Your funding statement (e.g., *"This research did not receive any specific grant from funding agencies in the public, commercial, or not-for-profit sectors."*)
   - Acknowledgments (optionally thanking your expert raters)
2. Open `submission_v8\JBR_Cover_Letter.md` (save as `.docx` or paste directly into the portal), insert your institutional email and submission date, and double-check the 5 suggested reviewers.

### Step 4: Submit to *Journal of Business Research* (Elsevier Editorial Manager)
Upload the **5 portal files** from Destination A:
1. Cover Letter (`JBR_Cover_Letter`)
2. Title Page (`Title_Page_v8.docx`)
3. Blinded Manuscript (`Manuscript_Blinded_v8.docx`)
4. Blinded Web Appendix (`Web_Appendix_v8.docx`)
5. Standalone Figure (`Figure_1_Conceptual_Model_300dpi.png`, if requested) + 5 Research Highlights

### Step 5: Optional Post-Submission Visibility & Backup Plan
- **Preprint (Optional):** Once submitted, you may post the non-blinded `AI_Marketing_Paper_v8.docx` on SSRN or ResearchGate to establish priority and gather feedback (check Elsevier's preprint wording during submission—*JBR* allows non-commercial working-paper preprints).
- **Practitioner Sharing:** Share `Executive_Benchmark_Brief_Practitioners.docx` with your raters, practitioner contacts, or on LinkedIn to build engagement around the paper.
- **If Desk-Rejected at *JBR*:** Pivot immediately to ***Psychology & Marketing*** (second target on ladder) or ***Journal of Retailing and Consumer Services (JRCS)*** (third target)—the Option 2-Hybrid econometric rigor (`M2a`/`M2b`, `M4a`/`M4b`, Table W7), 50-firm live-browser audit, and 65 verified references transfer directly with only a brief cover-letter re-tailoring.
