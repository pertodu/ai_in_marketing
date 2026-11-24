# Final Submission Logistics Guide — *Journal of Business Research* (*JBR*)

> **Author-only checklist — do NOT upload this file to the journal or public repository.**  
> Follow these four steps once your Task 1 expert-rater numbers are plugged in and all red notes have been removed from the manuscript.

---

## Step 1: Complete Your Personal Metadata in `Title_Page_v8.docx` and `JBR_Cover_Letter.md`

### A. Edit `E:\AI_research\03_working_paper\submission_v8\Title_Page_v8.docx`
Open `Title_Page_v8.docx` in Microsoft Word and replace every bracketed placeholder (and delete the red `[AUTHOR NOTE]` callout box once done):

1. **Corresponding Author Email:** Replace `[Insert Institutional Email]` with your Keene State College email address (e.g., `kli@keene.edu` or your official address).
2. **ORCID iD:** Replace `[Insert ORCID]` with your 16-digit ORCID URL (e.g., `https://orcid.org/0000-000X-XXXX-XXXX`). If you don't have one yet, register free in 2 minutes at [https://orcid.org/register](https://orcid.org/register).
3. **Funding Statement:** Replace `[Insert funding statement...]` with the standard Elsevier phrasing if unfunded:
   > *"This research did not receive any specific grant from funding agencies in the public, commercial, or not-for-profit sectors."*
   *(Or list any Keene State / USNH internal faculty development grant if applicable.)*
4. **Acknowledgments:** Replace `[Insert acknowledgments...]` with optional named thanks to any expert raters who opted in during Task 1 (e.g., *"The author thanks [Names] for serving as independent domain experts during construct validation."*), or delete the Acknowledgments line if all raters preferred anonymity.
5. **Confirm Highlights Length (*JBR* rule):** Check the 5 bullet points under `# Research Highlights` — Elsevier enforces **3–5 bullets, maximum 85 characters (including spaces) per bullet**. All 5 bullets currently in `Title_Page_v8.docx` already meet the $\le 85$-character limit.
6. **Save** `Title_Page_v8.docx`.

### B. Edit `E:\AI_research\03_working_paper\submission_v8\JBR_Cover_Letter.md`
Replace these four placeholders (then copy-paste into Editorial Manager or export to PDF/Word):
- `[Insert Submission Date]`
- `[Insert Institutional Email]` and `[Insert ORCID]`
- `[Insert Anonymized Figshare / ResearchBox URL]` (from Step 2 below)
- `[Insert Phone, optional]`

---

## Step 2: Upload `Replication_Package_Blind.zip` and Generate a Double-Blind Reviewer Link

> **Note:** Open Science Framework (OSF) permanently disabled new OSF Project creation on November 16, 2026. Use **Option A (Figshare)**, **Option B (ResearchBox)**, or **Option C (Direct Elsevier Upload)** below. All 30+ files inside `E:\AI_research\03_working_paper\submission_v8\Replication_Package_Blind.zip` have already been verified **PII-free** (`0` author names, `0` institutional references, `0` hardcoded paths, `0` API keys).  
> *(Reminder: After Task 1 finishes, we will add `expert_rater_adjudication_table.csv` into `04_validation/` and refresh `Replication_Package_Blind.zip` before you upload.)*

### Option A — Figshare *(Recommended: 1-Click Anonymous Private Link + Reserve DOI)*
1. Go to [https://figshare.com](https://figshare.com) and sign in (free account; you can sign in with ORCID).
2. Click **My data** → **+ Create a new item**.
3. Drag and drop `E:\AI_research\03_working_paper\submission_v8\Replication_Package_Blind.zip` into the upload area.
4. Fill in basic metadata:
   - **Title:** `Replication Package: Tool Presence Is Not Capability: AI Marketing Technology Signals and Customer-Facing Performance Across the Firm-Size Spectrum`
   - **Item type:** `Dataset`
   - **Categories:** `Marketing`, `Information Systems`
   - **Keywords:** `AI adoption`, `marketing technology`, `digital trace data`, `online reviews`, `customer satisfaction`
   - **Description:** Paste the first paragraph of `07_osf_replication_package/README.md`.
   - **License:** `CC BY 4.0` (standard for open academic data/code).
5. **Do NOT click "Publish item" yet!** (Publishing makes your name public and breaks double-blind review.)
6. Click **Save changes** (keeps the item as a **Private Draft**).
7. On the right panel (or under **Manage**), click **Generate private link** (sometimes labeled **Share with private link**):
   - Copy the generated URL (looks like `https://figshare.com/s/xxxxxxxxxxxxxxxxxxxx`).
   - *(Optional)* Also click **Reserve DOI** so you have a permanent DOI ready to activate with one click when *JBR* accepts the paper.
8. **Blind-Safety Check:** Open the private URL in an **Incognito / InPrivate browser window** (logged out of Figshare) and confirm:
   - The `.zip` downloads cleanly, and
   - Your name and Keene State College do **not** appear anywhere on the Figshare page.

### Option B — ResearchBox *(Marketing & Behavioral Science Standard)*
1. Go to [https://researchbox.org](https://researchbox.org) and sign in / create a free researcher account.
2. Click **Create a new Box** and upload the contents of `07_osf_replication_package` (or `Replication_Package_Blind.zip`) under the **Data**, **Code**, and **Materials** sections.
3. Keep the Box **Private / Under Review** and generate the **Anonymous Peer-Review Link** from the Box sharing menu.
4. Open the peer-review link in an **Incognito browser window** to confirm no author name or affiliation is visible.

### Option C — Direct Upload Inside Elsevier Editorial Manager *(Zero External Repository Needed During Review)*
1. During *JBR* submission (Step 4 below), upload `Replication_Package_Blind.zip` directly under the file type **"Supplementary Material for Review"** (or **"Research Data"**).
2. In the manuscript's Data Availability Statement, state:
   > *"Replication datasets, the website technology detection dictionary, Python econometric scripts, and supplementary SmartPLS 4 outputs are provided as anonymized Supplementary Material for peer review and will be publicly archived on Mendeley Data with a permanent DOI upon acceptance."*
3. Only **after *JBR* accepts the paper**, upload the package to [https://data.mendeley.com](https://data.mendeley.com) and publish it to obtain your permanent DOI.

---

## Step 3: Insert the Anonymized Repository URL (3 Places)

Once you have your anonymized URL from Option A or Option B (skip if using Option C), paste it into:
1. **Method Section 3.5** of `Manuscript_Blinded_v8.docx` (and `AI_Marketing_Paper_v8.docx`).
2. **Data Availability Statement** (Section 6) of `Manuscript_Blinded_v8.docx` (and `AI_Marketing_Paper_v8.docx`).
3. **Declarations section** of `JBR_Cover_Letter.md`.

*(Or paste the URL into chat here when you bring back Task 1's rater files, and I will insert it cleanly into every document and regenerate all final `.docx` files for you!)*

---

## Step 4: Upload Submission Package to *Journal of Business Research* (Elsevier Editorial Manager)

Go to the *Journal of Business Research* submission portal: [https://www.editorialmanager.com/jbr](https://www.editorialmanager.com/jbr)

### Exact File-to-Slot Mapping in Editorial Manager

| Editorial Manager Upload Slot | Exact File to Upload | Blinded? |
| --- | --- | --- |
| **Cover Letter** | `submission_v8\JBR_Cover_Letter.md` *(save/paste as `.docx` or `.pdf`)* | No (Editor only) |
| **Title Page (with Author Details)** | `submission_v8\Title_Page_v8.docx` | No (Editor only) |
| **Highlights** | Copy the 5 bullets from `Title_Page_v8.docx` (or save as a 1-page `Highlights.docx`) | Yes |
| **Manuscript (without Author Details)** | `submission_v8\Manuscript_Blinded_v8.docx` *(final red-note-free version after Task 1)* | **YES — 0 PII** |
| **Figure 1** *(if Editorial Manager requests separate high-res figures)* | `submission_v8\Figure_1_Conceptual_Model_300dpi.png` *(300 DPI)* | **YES** |
| **e-Component / Supplementary Material / Web Appendix** | `submission_v8\Web_Appendix_v8.docx` *(final version after Task 1)* | **YES — 0 PII** |
| **Supplementary Material (Optional — Option C only)** | `submission_v8\Replication_Package_Blind.zip` | **YES — 0 PII** |

### Entering Suggested Reviewers in Editorial Manager
Copy these five verified scholars directly from `JBR_Cover_Letter.md`:
1. **Patrick Mikalef** — Norwegian University of Science and Technology (NTNU) — `patrick.mikalef@ntnu.no`
2. **Božidar Vlačić** — Católica Porto Business School, Universidade Católica Portuguesa — `bvlacic@ucp.pt`
3. **Mekhail Mustak** — Hanken School of Economics — `mekhail.mustak@hanken.fi`
4. **Davide Proserpio** — Marshall School of Business, University of Southern California — `proserpi@marshall.usc.edu`
5. **Marcello M. Mariani** — University of Bologna & Henley Business School — `marcello.mariani@unibo.it`

### Final 60-Second Pre-Submit PDF Proof Check
Before clicking **Approve Submission** in Editorial Manager, open the system-generated **Merged Submission PDF** and check:
- [ ] **Zero red text** remains anywhere in `Manuscript_Blinded_v8.docx` or `Web_Appendix_v8.docx`.
- [ ] Your name (`Ke Li`) and institution (`Keene State College`) appear **only** on the Title Page and Cover Letter — **nowhere** in the Blinded Manuscript, Figure 1, or Web Appendix.
- [ ] **Figure 1** and **Tables 1–7** render cleanly without clipped columns or broken page breaks.
- [ ] **Data Availability URL** (if using Figshare/ResearchBox) opens cleanly in an Incognito window with zero author identity shown.

---

## Step 5 (Same Day You Submit): Set a 12-Month Wave 2 Calendar Reminder

On the day you submit to *JBR*, put a calendar reminder for **June 7, 2027** (12 months after Wave 1) to re-run `collect_ai_metrics_sales_size.py` on the exact same 1,000-firm frame. If reviewers ask for longitudinal or within-firm panel evidence during a Revise & Resubmit (R&R), having Wave 2 ready will be your strongest possible response.
