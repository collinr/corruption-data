# PRISMA Framework: Quick Reference Card
## Multi-Source Corruption Data Mapping Study

---

## PRIMARY CITATIONS (Copy-Paste Ready)

### For your proposal reference list:

```
Moher, D., Liberati, A., Tetzlaff, J., Altman, D. G., & PRISMA Group. 
(2009). Preferred reporting standards for systematic reviews and 
meta-analyses: The PRISMA statement. PLoS Medicine, 6(7), e1000097. 
https://doi.org/10.1371/journal.pmed.1000097

Page, M. J., McKenzie, J. E., Bossuyt, P. M., Boutron, I., Hoffmann, T. C., 
Mulrow, C. D., ... & Moher, D. (2021). The PRISMA 2020 statement: An updated 
guideline for reporting systematic reviews. BMJ, 372, n71. 
https://doi.org/10.1136/bmj.n71

Tricco, A. C., Lillie, E., Zarin, W., O'Brien, K. K., Colquhoun, H., 
Levac, D., ... & Munn, Z. (2018). PRISMA extension for scoping reviews 
(PRISMA-ScR): Checklist and explanation. Annals of Internal Medicine, 169(7), 
467–473. https://doi.org/10.7326/M18-0850
```

---

## IN-TEXT CITATION EXAMPLES

**Option 1 (General):**
"This systematic mapping study follows PRISMA 2020 guidelines (Page et al., 2021) 
adapted for data source identification and appraisal."

**Option 2 (Scoping Focus - RECOMMENDED):**
"To ensure methodological transparency and reproducibility, this multi-source 
corruption data mapping was conducted according to PRISMA-ScR guidelines for 
scoping reviews (Tricco et al., 2018), which are appropriate for systematically 
identifying and mapping sources rather than aggregating findings."

**Option 3 (Full Attribution):**
"This study employs the Preferred Reporting Items for Systematic Reviews and 
Meta-Analyses (PRISMA) framework (Moher et al., 2009; Page et al., 2021), 
specifically the PRISMA-ScR extension for scoping reviews (Tricco et al., 2018), 
to systematically identify, screen, and appraise publicly available corruption 
data sources in South Africa."

---

## FIVE-PHASE WORKFLOW AT A GLANCE

| Phase | Activity | Output | Tools |
|-------|----------|--------|-------|
| **1. IDENTIFICATION** | Define protocol → Search systematically | List of potential sources (n=?) | Search log, Keywords spreadsheet |
| **2. SCREENING** | Two-stage: title/abstract → full-text | Eligible sources (n=?) | Screening form, Screening log |
| **3. QUALITY APPRAISAL** | Score on 7 dimensions (1–5) | Ranked sources (composite score) | Quality assessment form (Table 4) |
| **4. DATA EXTRACTION** | Extract metadata + corruption cases | Extracted dataset | Extraction template, Audit trail |
| **5. SYNTHESIS** | Triangulate across sources; identify gaps | Integrated landscape map | Triangulation matrix, Gap analysis table |

---

## INCLUSION/EXCLUSION CRITERIA (At a Glance)

### INCLUDE if:
✓ Publicly accessible (or accessible via ethics approval)  
✓ Produced by legitimate institution (government/NGO/CSO)  
✓ Contains quantitative or structured qualitative corruption data  
✓ South Africa-focused (national/provincial/municipal)  
✓ Documented scope & methodology  
✓ Covers ≥3 years of data

### EXCLUDE if:
✗ Anecdotal only (no institutional data)  
✗ Permanently restricted/classified  
✗ Opinion without evidence  
✗ Duplicate source  
✗ Non-SA focused  
✗ Inactive archive (no updates >3 years)

---

## SEVEN-DIMENSION QUALITY SCORING (1–5 Scale)

| Dimension | 5 = Excellent | 3 = Moderate | 1 = Poor |
|-----------|---|---|---|
| **Credibility** | Independent audit, legislated mandate | Mixed credentials | Unverified, no backing |
| **Completeness** | Comprehensive coverage | Selective coverage | Anecdotal fragments |
| **Consistency** | Standardised definitions, aligned years | Moderate variation | Inconsistent framework |
| **Timeliness** | Real-time or <3 mo lag | 6–12 mo lag | >2 years lag |
| **Accessibility** | Open download, API, no paywalls | Semi-public, some friction | Restricted/blocked |
| **Granularity** | Case-level, person-level, linkable IDs | Sector/institutional level | Country-level only |
| **Bias Risk** | Low, representative | Moderate, acknowledged | High, distorted |

**Composite Score = Average of seven dimensions**

**Decision:**
- **≥3.5** → Primary analysis (reliable)
- **2.5–3.4** → Secondary analysis (supplementary, acknowledge limitations)
- **<2.5** → Mention in limitations section only

---

## SEARCH STRATEGY TEMPLATE

**Document before searching:**

| Field | Your Entry |
|-------|---|
| **Search Term Examples** | "corruption South Africa," "irregular expenditure," "fraud," "audit findings," "state capture," "procurement irregularities" |
| **Databases/Portals** | Vulekamali, AGSA, Parliament Hansard, SIU, Public Protector, Corruption Watch, Google Scholar, News24, [your additions] |
| **Date Limits** | 2010–2025 (or justify different range) |
| **Language** | English |
| **Source Types** | PDF reports, Excel files, API endpoints, web databases |
| **Search Log** | [Keep table: Database, Query, Date Searched, Results Found, Sources Identified] |

---

## SCREENING LOG TEMPLATE

Maintain this for each source reviewed:

```
Source Name: _____________________
Identified from: _____________________
Date screened: _____________________

STAGE 1 (Title/Description): Include? YES / NO
Reason: ________________________________

STAGE 2 (Full-Text): Include? YES / NO
Reason: ________________________________

Exclusion reason (if applicable):
[ ] Not SA-focused
[ ] Anecdotal only
[ ] Opinion without data
[ ] Permanently restricted
[ ] Duplicate
[ ] Other: ________________
```

---

## DATA EXTRACTION TEMPLATE (Condensed)

```
SOURCE METADATA:
- Institution: __________________
- Data source name: __________________
- URL: __________________
- Timeline: ____ to ____
- Format: __________________
- Machine-readable?: Yes / No
- Quality score: ____/5.0

CORRUPTION CASE (repeat for each):
- Case ID: __________________
- Type (fraud/waste/irregular/state capture): __________________
- Sector: __________________
- Jurisdiction: __________________
- Date of incident: __________________
- Rand value: R__________________
- Outcome: __________________
- Reported by (other sources?): __________________
```

---

## TRIANGULATION RULE

For credibility assessment:

| Reported by # Sources | Credibility Level | Interpretation |
|---|---|---|
| **5+ sources** | Very High | Multiple independent corroboration |
| **3–4 sources** | High | Cross-verified finding |
| **2 sources** | Moderate | Some corroboration |
| **1 source** | Low | Isolated report; flag for follow-up |

---

## PRISMA CHECKLIST (Core Items for Your Proposal)

- [ ] **Title:** Includes "systematic," "mapping," "data sources," "South Africa"
- [ ] **Abstract:** Objective, methods (PRISMA), # sources screened, # included, key findings
- [ ] **Methods - Protocol:** Registered a priori (OSF link provided)
- [ ] **Methods - Eligibility:** Explicit inclusion/exclusion criteria
- [ ] **Methods - Search:** Document keywords, databases, date ranges, filters
- [ ] **Methods - Study Selection:** Two-stage process described
- [ ] **Methods - Data Extraction:** Standardised template, variables defined
- [ ] **Methods - Quality Assessment:** Seven-dimension framework (1–5 scores)
- [ ] **Results - Flow Diagram:** Shows screening process (identified → screened → eligible → included)
- [ ] **Results - Characteristics Table:** Data source inventory with metadata
- [ ] **Results - Quality Scores:** Table showing all scores across dimensions
- [ ] **Results - Synthesis:** Triangulation findings, gap analysis
- [ ] **Discussion - Interpretation:** What does the map reveal?
- [ ] **Discussion - Limitations:** Screening bias, publication bias, access barriers
- [ ] **Discussion - Implications:** For policy, practice, future research

---

## INTEGRATION WITH YOUR FRAMEWORKS

```
┌─────────────────────────────────────────────┐
│  PRISMA: Systematic identification & screening  │
│  (Phase 1–2: Find & validate sources)        │
└────────────────┬────────────────────────────┘
                 ↓
┌─────────────────────────────────────────────┐
│  YOUR MATRIX: Seven-dimension quality scoring  │
│  (Phase 3: Evaluate & rank)                   │
└────────────────┬────────────────────────────┘
                 ↓
┌─────────────────────────────────────────────┐
│  BOWEN: Document analysis & data extraction   │
│  (Phase 4: Extract from high-quality sources) │
└────────────────┬────────────────────────────┘
                 ↓
┌─────────────────────────────────────────────┐
│  TRIANGULATION: Synthesize across sources    │
│  (Phase 5: Identify convergence & gaps)      │
└─────────────────────────────────────────────┘
```

---

## BEFORE YOU START: Pre-Data Collection Checklist

- [ ] Write protocol (a priori)
- [ ] Register on OSF (link to include in proposal)
- [ ] Finalise search strategy (keywords, databases, date limits)
- [ ] Create screening form (include/exclude decisions)
- [ ] Create data extraction template
- [ ] Define quality scoring anchor descriptions (see table above)
- [ ] Populate Corruption Data Source Inventory (36 sources template)
- [ ] Plan dual screening calibration (10–20% of sources, you + supervisor)

---

## DURING DATA COLLECTION: Ongoing Checklist

- [ ] Log all searches (database, query, date, results)
- [ ] Maintain screening log with rationale for exclusions
- [ ] Double-screen first 10 sources (calibration)
- [ ] Extract using standardised template
- [ ] Document QA checks (what validation did you apply?)
- [ ] Keep audit trail (who, when, how, issues encountered)

---

## REPORTING CHECKLIST (Before Submission)

- [ ] Create PRISMA flow diagram (identified → screened → eligible → included)
- [ ] Complete all 29 items in PRISMA 2020 checklist
- [ ] Report all quality scores (table format)
- [ ] Discuss triangulation (which cases/sectors converge?)
- [ ] Address gaps (where is data sparse/absent?)
- [ ] Acknowledge limitations (bias, access barriers, screening limitations)
- [ ] Provide transparent methods section (reproducible)

---

## QUICK CITATION FOR YOUR METHODS SECTION

**Cut & paste template:**

"This systematic data source mapping was conducted following PRISMA-ScR 
guidelines (Tricco et al., 2018) for scoping reviews. [Protocol was registered 
prospectively at OSF [link] on [date].] The study systematically identified 
corruption and governance data sources across South African public sector, NGO 
development sector, and civil society organisations through systematic searching 
of government portals, NGO databases, academic repositories, and media archives 
(search strategy documented in Appendix X). Identified sources were screened 
in two stages (title/abstract, then full-text) against explicit inclusion 
criteria, and eligible sources were appraised for quality using a seven-dimension 
framework (credibility, completeness, consistency, timeliness, accessibility, 
granularity, bias risk). Data extraction and synthesis followed document analysis 
principles (Bowen, 2009), with triangulation across sources to identify 
convergence and data gaps. This methodological approach ensures transparency, 
reproducibility, and systematic appraisal of source quality."

---

## KEY REFERENCE URLS

- **PRISMA Statement:** https://www.prisma-statement.org/
- **PRISMA-ScR (Scoping Reviews):** https://osf.io/k83jd/
- **OSF (Protocol Registration):** https://osf.io/
- **Moher et al. 2009 (Open access):** https://journals.plos.org/plosmedicine/article?id=10.1371/journal.pmed.1000097
- **Page et al. 2021 (Open access):** https://www.bmj.com/content/372/bmj.n71

---

## FINAL RECOMMENDATION

**Start with PRISMA-ScR (Tricco et al., 2018)** — it is most relevant to your 
study because:
1. **Designed for scoping reviews** (mapping sources, not meta-analysis)
2. **Handles heterogeneous sources** (unlike traditional systematic reviews)
3. **Emphasizes transparency** in source selection & appraisal
4. **Explicitly covers data quality assessment** (your seven-dimension matrix)

Your combination of **PRISMA-ScR + Bowen Document Analysis + Your Quality Matrix** 
is a best-practice approach for rigorous, transparent, multi-source research.

---

**Document prepared for:** Collin Mamdoo, PhD candidate  
**Study:** Multi-Source Mapping and Descriptive Analysis of Corruption Data in South Africa  
**Date:** April 2026
