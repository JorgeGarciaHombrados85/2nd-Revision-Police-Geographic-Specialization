# Manuscript Changes & Clarifications
## Final Version Tracking Document

**Date Started:** June 24, 2026  
**Document:** Boots in the Beat: Effects of Beat Policing on Victimization and Crime Perception

---

## Changes Log - Organized by Section

### FRONT MATTER

#### 3. JEL Codes and Keywords Missing
**Location:** Manuscript front matter  
**Page:** 1  
**Issue:** JEL classification codes and keywords are missing from the document  
**Status:** ⚠ Needs Review

---

### ABSTRACT

#### 1. Arrests Reporting Clarification
**Location:** Edited sections/00_abstract.tex  
**Page:** 1  
**Paragraph:** 1  
**Original Note:** `\todo{Check whether this is arrests per crime or number of arrests. I would prefer to report the second in the abstract.}`  
**Change:** Clarified that the figure reports **number of arrests** (not arrests per crime)  
**Status:** ⚠ Resolved but needs review  
**Details:** The 8 percentage points (22%) increase refers to the rate of arrests per crime recorded, which represents the number of arrests relative to recorded crimes.

#### 2. Crime/Arrests Reporting Metric
**Location:** Edited sections/00_abstract.tex  
**Page:** 1  
**Paragraph:** 1  
**Issue:** Current reporting gives the impression of absolute numbers rather than rates  
**Status:** ⏳ Pending review and implementation

---

### INTRODUCTION (Section 1)
*No changes in this section currently*

---

### DESIGN AND IMPLEMENTATION (Section 2: Plan Cuadrante)

#### 5. Removed Unnecessary Subsection Heading
**Location:** Edited sections/02_institutions.tex, Opening  
**Page:** 2  
**Paragraph:** 1  
**Issue:** Section had a single subsection heading "2. Carabineros de Chile and the Plan Cuadrante Reform" which was unnecessary since there is only one subsection and the section already has a title in the main document  
**Change:** Removed the manual subsection heading; content now flows directly as part of Section 2  
**Status:** ✓ Resolved

#### 4. Terminology Inconsistency: "Crime Perception" vs "Insecurity Perception"
**Location:** Edited sections/02_institutions.tex  
**Page:** 2–4  
**Paragraph:** Throughout section  
**Issue:** Text consistently refers to "insecurity perception" or "perception of insecurity," but figures still label this as "crime perception." Consider standardizing terminology to "insecurity perception" in figures to match the text (question measures whether respondent thinks crime has increased over the last 12 months)  
**Status:** ⏳ Pending review and implementation

#### 6. Sample Specification in Comisaría Statistics
**Location:** Edited sections/02_institutions.tex  
**Page:** 2  
**Paragraph:** 3  
**Issue:** The statistics in the paragraph "All municipalities that adopted Plan Cuadrante during our study period had at least one comisar´ıa. With the exception of 10 municipalities, each had a single comisar´ıa covering the full municipal territory. On average, a comisar´ıa in our sample covered 1,608 square kilometers and served 57,642 inhabitants. Of these, 17 had no subordinate units, whereas the remaining 79 had between one and nine." currently refer to the 96 treated municipalities of the administrative/SPD sample. Could alternatively specify the same statistics for the 46-municipalities ENUSC sample instead.  
**Status:** ⏳ Pending decision on which sample to prioritize in this descriptive section

#### 7. Quadrant Share of Comisaría Territory (filled in the "x%" placeholder)
**Location:** Edited sections/02_institutions.tex  
**Page:** 3  
**Paragraph:** Quadrant-structure paragraph (immediately after Figure 1)  
**Original:** "Quadrants represented approximately x\% of the original comisaría territory." (placeholder `x`)  
**Change:** Filled in **14%**.  
**Estimation:** Computed as the number of comisarías in **2005** (the first period available in the stations panel) divided by the number of quadrants: **146 comisarías ÷ 1,071 quadrants = 13.6% ≈ 14%**. This is mathematically equivalent to (average quadrant area ÷ average comisaría territory) and to 1 ÷ (quadrants per comisaría); each comisaría territory was subdivided into ~7 quadrants. (At 2013 the same ratio is ~16%.)  
**Status:** ⚠ Needs discussion
**Discussion Points:**
1. Confirm that this ratio (comisarías ÷ quadrants) is what we intend by "% of the original comisaría territory."
**Alternative Suggestions:**
- Option A: "On average, each quadrant covered approximately 14% of the original comisaría territory" (shorter, direct)
- Option B: "Each comisaría's previously undifferentiated jurisdiction was thus partitioned into about seven quadrants, each representing approximately 14% of the original comisaría territory, with officers permanently assigned to their designated sub-area."

#### 8. Figure 1 — Panels Switched and Panel (b) Redrawn
**Location:** Figures/figure01_implementation.tex (Figure \ref{fig:figure01}, input in Edited sections/02_institutions.tex at line 14); panels described in §2 (¶6 for panel (a), ¶8 for panel (b))
**Change:** Switched the order of the two panels, and redrew **Panel (b)** to match what Andrés was describing.
**Note:** I'm not sure Panel (b) is exactly what Andrés had in mind — needs his confirmation that this is what he meant.
**Status:** ⏳ Needs revision

---

### DATA AND EMPIRICAL STRATEGY (Section 3)

#### 1. ENUSC Sample Population Representation Correction
**Location:** Edited sections/03_data.tex, Line 7  
**Original Text:** "These areas represent 35% of Chile's population"  
**Corrected Text:** "These areas represent 27% of Chile's population"  
**Status:** ✓ Resolved  
**Details:** The 46 ENUSC communes (plus one never-treated) in the analytical sample represent:
- **27%** of Chile's total population
- **30%** of Chile's urban population  
- **30%** of the population under Plan Cuadrante implementation

#### 2. Inconsistency in Sample Composition Reporting
**Location:** Edited sections/03_data.tex, Last paragraph  
**Issue:** Inconsistent sample composition information between Introduction and Data sections  
**Status:** ⏳ Pending  
**Details:** 
- **SPD Sample:** Numbers reported in Introduction but NOT in Data section
- **ENUSC Sample:** Numbers reported in Data section but NOT in Introduction
- **Suggested Addition to Data Section:** Clarify that the SPD analysis includes **292 municipalities total** (96 treated, 196 never-treated)

#### 3. Administrative Data Time Period Specification
**Location:** Edited sections/03_data.tex, Empirical Strategy section (Line ~15)
**Original Text:** "those relying on administrative data use variation from 2004-2013 adoptions."
**Corrected Text:** "those relying on administrative data use variation from 2003-2013 adoptions."
**Status:** ✓ Resolved in main text
**Details:** 
- **Reported Crimes:** 2003-2013 (includes two municipalities—Temuco and Padre de las Casas—that adopted PC in 2003, with baseline data available for 2002)
- **Arrests:** 2005-2013 (limited to this period due to data availability for arrest records)
**Recommendation:** Consider adding a note in footnote 6 (the robustness check footnote) specifying that the 2005-2013 variation applies to arrests analyses to clarify this distinction

---

### RESULTS (Section 4)

#### 1. De-duplicated Spillovers Narrative (§4.2) vs. Appendix B.4
**Location:** Edited sections/04_02_spillovers.tex (¶5) and Edited sections/B_robustness_checks.tex (subsection "Testing for Spatial Spillovers", label `spillovers`)
**Issue:** Section 4.2 and Appendix B.4 told essentially the same spillovers story; in addition, §4.2 ¶5 described the ENUSC *survey-outcome* spillover exercise but mis-referenced the *administrative-neighbors* figure.
**Change:** Reworked so the two sections complement rather than repeat each other, following Jorge's response-to-reviewers text on the spillovers comment:
- **§4.2** now carries the *narrative* of the five exercises. ¶5 was split into the two distinct ENUSC complements with corrected refs — administrative outcomes for neighbors of the 46 ENUSC municipalities → Figure `fig:figure_46ENUSC_spillovers_admin` (B8); ENUSC survey outcomes (early- to late-adopters) → Figure `fig:figure_results_spillovers_enusc` (B9). Also restored the municipality-size stat ("101,000 inhabitants and 2,000 square kilometers" `\citep{SINIM}`) in ¶1, and added the number-of-treated-neighbors figure ref (`fig:figure_count_spillovers`) alongside the share figure in ¶3.
- **Appendix B.4** reframed as the *technical companion* ("details the specifications behind the spillover tests summarized in Section~\ref{sec:spillovers}"): equations (2)–(3), estimator choices (Callaway for the binary/admin baseline; de Chaisemartin for the continuous-intensity test and the 1,000-permutation randomization-inference exercise, justified by the prohibitive cost of re-estimating Callaway over a thousand permutations), and the six focal ENUSC late-adopters each paired with its earliest-adopting neighbor and adoption year. The three previously orphaned figures (treatment-intensity, permutations, ENUSC-sample spillovers) are now input here, and `figure03_spillovers` is input once (no longer duplicated from §4.2).
**Status:** ⚠ Needs Review

#### 2. Footnote 7 — Pre-Trends Test Mislabeled
**Location:** Edited sections/04_results.tex (¶1 pre-trends footnote, Footnote 7)
**Issue:** The previous version labeled the reported figures as the **joint significance test** of the pre-treatment coefficients, but the values actually came from the test that the **average pre-treatment effect equals zero**. The two tests were conflated.
**Change:** Corrected and now reports **both** tests explicitly:
- *Average pre-treatment effect = 0:* victimization 0.833, reported crime 0.204, security perception 0.178, security measures 0.066.
- *Joint significance of pre-treatment coefficients:* 0.101, 0.049, 0.076, 0.109, respectively.
Added a sentence noting the only marginal case is the joint test for reported crime (0.049), where the pre-treatment coefficients are slightly positive and therefore conservative with respect to the negative estimated effect.
**Open question (author decision):** The joint-test p-values are less reassuring than the previously (mis)reported numbers — in particular reported crime is marginally significant at 5%. **Decide whether to report both tests, only the average-effect test, or keep both with the conservative-bias caveat.**
**Status:** ⏳ Pending decision

#### 3. Missing Reference for Officer-Reassignment Claim (`SOURCE_ON_REASSIGNMENT`)
**Location:** Edited sections/04_02_spillovers.tex (§4.2, end of ¶1) — `\citep{SOURCE_ON_REASSIGNMENT}`
**Issue:** The sentence stating that "existing Carabineros regulations assign officers to *comisarías* … for fixed periods, making rapid reallocation of police officers across jurisdictions difficult" was supported by a **placeholder citation** (`SOURCE_ON_REASSIGNMENT`). The placeholder entry was removed from `Bibliography.bib`, so the cite now compiles as an unresolved **(?)** reference (page 17).
**Resolution:** Not a bibliography citation but a footnote pointing to the Transfer Manual for Carabineros de Chile Personnel (`https://www.carabineros.cl/transparencia/og/pdf/OG_2707_13112019.pdf`). Added in `04_02_spillovers.tex` and to the matching unsupported claim in `response/Parts/r1_01.tex` (officer-transfer regulatory constraints).
**Status:** ✅ Resolved

---

### CONCLUSIONS (Section 5)
*No changes in this section currently*

---

### ONLINE APPENDIX A - Implementation Details

#### 1. Appendix A Coherence Review Recommendation
**Location:** Edited sections/A_implementation_details.tex  
**Issue:** Appendix A needs to be reviewed for coherence given new information and material added to Introduction (Section 1) and Design & Implementation (Section 2)  
**Status:** ⏳ Pending review
**Details:** 
- **Recommendation 1:** Review whether all content in Appendix A still makes sense and complements (rather than duplicates) the expanded material now in Introduction and Section 2 (Plan Cuadrante overview, comisaría statistics, quadrant structure, etc.)
- **Recommendation 2:** Consider including rollout maps at country and region levels in Appendix A to provide visual representation of Plan Cuadrante's geographic expansion and timing of adoption across municipalities

#### 2. Tables A1, A2, and A3 Reformatted
**Location:** Edited sections/A_implementation_details.tex (Appendix A summary-statistics tables)
**Change:** Tables A1, A2, and A3 were reformatted.
**Note:** Check Table A3 in particular — previously the division of the table into the two samples was not well defined.
**Status:** ⏳ Pending revision


---

### ONLINE APPENDIX C - Additional Results

#### 1. New Table C1 (Security Measures by Type and SES) + Figure C1 Refresh
**Location:** Edited sections/C_additional_results.tex (§C.2); Tables/Measures_bytype.tex (new file); Graphs/results_typeofcrimes_{ENUSC,SPD}.pdf (Figure C1)
**Do-files:** reg_typesmeasures.do (table) and reg_typesofcrime.do (Figure C1), both using the capped event-study horizon (year $\le$ PCSP+6) as in reg_mainresults.do
**Issue:** Table \ref{tab:hhprotectionmeasurestype} was referenced in the text but never created — the `\input` was commented out (`% File not yet created`), leaving an undefined reference — and the draft export reported neither Municipalities nor a properly formatted N / Y mean. Figure C1 in the manuscript used stale (pre-cap) graphs.
**Change:**
- Rewrote the table export in `reg_typesmeasures.do` to mirror Table B1 (`Results_SPD_N47`): ATT with significance stars, SE in parentheses, and the rows **N**, **Municipalities**, and **Y mean** (pre-treatment outcome mean among treated municipalities). Columns are grouped by measure type (cheap / expensive) and, within each, by SES (All / Higher / Lower). Estimates are the horizon-capped (t+6) ATT from `csdid` + `estat simple`. Created `Tables/Measures_bytype.tex` and uncommented the `\input` in §C.2, resolving the previously undefined `tab:hhprotectionmeasurestype` reference.
- Refreshed Figure C1 (type-of-crime effects) with the capped graphs regenerated by `reg_typesofcrime.do`.
**Results (Table C1):** Cheap −0.072*** / Cheap–Higher SES −0.090*** / Cheap–Lower SES −0.058*** / Expensive −0.015*** / Expensive–Higher SES −0.028*** / Expensive–Lower SES −0.004 (n.s.). N = 93,041 (all) / 40,377 (higher SES) / 52,664 (lower SES); 47 municipalities throughout.
**Status:** ⚠ Needs Review

---

## To Be Added
Add your next changes here...

---

**Notes:**
- Each change references the specific file location, page number, and paragraph number
- Include what was changed and why
- Mark status as: ✓ Resolved / ⏳ Pending / ✗ Removed / ⚠ Needs Review
