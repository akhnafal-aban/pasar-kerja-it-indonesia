# 15 — Verification & Synthesis: Reconciliation, Quality Gate, Curated Dashboard Dataset

Research date: 2026-11-09. Author: verification/synthesis unit. Inputs: files 01–05, 07–10, 12, 13 (files 06, 11, 14 did not exist at synthesis time). Fresh primary verifications performed this session: (a) full text of MDPI Sustainability 15(1):754 (BRIN oversupply paper), (b) GoTo audited FY2025 consolidated financial statements (employee-count note).

---

## 1. Reconciliation Findings

### C1. Talent-gap narratives (9M vs 12M vs 456k/yr vs 600k/yr vs ~151k oversupply)

**What each figure actually measures:**

| Figure | What it measures | Origin & lineage | Quality |
|---|---|---|---|
| **9M by 2030** (~600k/yr) | Cumulative 2015–2030 net shortfall of **skilled AND semi-skilled ICT workers** (training interventions needed, not jobs) | Tan & Tang, *New Skills at Work ASEAN-5* (J.P. Morgan/McKinsey, 2016, non-public model) → carried verbatim by World Bank 2018 *Preparing ICT Skills for Digital Economy* — a **3-month desk review, not original research**. Misattributed by officials to "McKinsey 2018", "World Bank", and "WEF 2015" (no WEF source exists) — evidence nobody tracked the primary source | Weak citation chain; rhetoric. NOT a market-demand estimate |
| **12M by 2030** (IMDI 2024; gap 3M after ~9M university supply; ~500k/yr) | "Digital talents" incl. basic-to-advanced digital skills — **a demand projection, not a vacancy count** | Kominfo's own IMDI model, built on **BPS + Kemendikbudristek data** (BPS lineage flag); inputs not public, not independently verifiable | Official planning model |
| **456k/yr** (BPSDM 2025; drifted 450k→453k→456k→458k→600k/yr across statements) | Annual digital-talent demand, internal BPSDM modeling on BPS data; officials call it "more precise than WB/McKinsey" — the ministry **quietly halved the pace** while keeping the "shortage" frame | BPS lineage; internal model, inputs unpublished | Current official planning number |
| **600k/yr (Kominfo)** | Arithmetic restatement of 9M ÷ 15 years | Parrots the 2016/2018 chain | Rhetoric |
| **Oversupply ~151,495** (BRIN/MDPI, 2021–2025) | **Graduate flow vs broad ICT occupation growth**: Bayesian forecast of supply 3,372,392 digital-skilled graduates (SMK+polytechnic+university, STEM/communication/informatics) vs demand 3,220,897 ICT occupations (~600k/yr growth, derived from **Sakernas** ICT-occupation growth + ILO Rapid Assessment proportions) → surplus 151,495 (~30.3k/yr); paper also reports a 392,219 **deficit over 2016–2020** actuals | Gayatri, Jaya & Ramadhan, *Sustainability* 15(1):754 (Dec 2022), BRIN researchers, **funded by Kominfo**; verified against full text this session | Academic flow model; demand side is itself BPS-derived and broad (semi-skilled included) |

**Verdict:** *None of these is a true market-demand estimate for professional IT labor.* The 9M narrative is political rhetoric on a thin citation chain (2016 consultancy model → 2018 desk review → three-way misattribution). The 456k/yr figure is the current official planning number (BPS-lineage, unverifiable). The MDPI oversupply finding is a legitimate *graduate-flow* model showing mild aggregate surplus of entry-level supply — it does **not** contradict senior-level shortage. File 12's tightness evidence (senior advertised pay +20.8% vs entry +11.1%; fresh grads facing hardest job search on record; counter-offer wars) supports the reconciliation: **the real condition is skill/seniority MISMATCH — entry-level oversupply coexisting with experienced-professional shortage.** Dashboard must show all five as *distinct concepts* with honesty labels, never as one comparable "gap" number. Korn Ferry's 600K–1.2M TMT deficit (2018) sits an order of magnitude below 9M purely because of definitional scope — a useful illustration of definitional inflation.

### C2. IT professional workforce size

See model in §2. Preliminary verdict: candidate anchors measure different things —
- **KBLI category J ≈ 1.25M (BPS Feb 2025)**: employment in *Informasi & Komunikasi* (KBLI 58–63) — includes telecom, publishing, broadcasting; usable-with-caveats (file 10), national-only, province cuts unstable.
- **Kominfo "1.09M digital workers" (2023)**: government claim, methodology never published; happens to ≈ category-J level; and suspiciously the same figure family as IMDI's "1.09M (0.75% of labor force)".
- **File-10 triangulation 900k–1.5M**: plausible for "people earning their living from IT incl. freelancers/contractors."
- **SlashData-derived ~0.8M coders (2022)**: derived (32% of rest-of-East-Asia share × global model); "people actively coding" — includes non-professional; grown to maybe 1.0–1.5M by 2025.
- **LinkedIn ~236K profiles (2023)**: keyword-search floor; LinkedIn coverage of Indonesian workforce is low (Stanford HAI flags this explicitly) → floor, not estimate.
- **GitHub 4.37M accounts (2025; 5.27M Q1 2026)**: accounts, not people-coding-for-pay; aspirational funnel top.
- **"Low hundreds of thousands" professional core (file 5)**: directionally right for *strictly employed software engineers at professional caliber*.

### C3. DTS 2021 realisasi: 131,204 vs 123,772

- **131,204** — Menkominfo via Setkab (29 Dec 2021) press statement (file 01, conf 4).
- **123,772** — DPR RI PA3KN policy brief, based on **audited LKj BPSDM Kominfo** data; target 62,764 (197.2% realization); Bappenas control report separately states **123,412** (different snapshot) (file 03, conf 5).
- **Verdict:** Prefer the audited-basis **123,772** as the canonical 2021 figure; the ~7.4k gap vs the ministry's press number is unexplained, and the DPR/BPK audit explicitly found participant/attendance data unreliable ("attendance lists could not be reconciled"), so *all* DTS counts are soft-realized. Dashboard: 2021 = 123,772 (audited), footnote 131,204 (ministerial press).
- Internal consistency of the cumulative: composition **sums exactly** — 28,713 + 20,579 + 6,192 + 13,480 = 68,964 core; 68,964 + 503,108 = 572,072. ✓ Use headline 572,072 (through 3 Oct 2025) but **always decomposed**: 88% is low-intensity Microskill; core academies total only ~69k for the entire 2018–2025 program — that is the supply-relevant number.

### C4. MSIB cumulative: >120k (batches 1–5) vs >150k (through batch 7)

Reconciled batch series (all official): **B1 2021: 13,272** · B2–B4: not individually published (>93k cumulative through B4) · **B5 2023: 36,719 placed** (98k applicants; deck says 36,728 — trivial variant, use 36,719 placed) · ">120k through B5" (Antara, Nov 2023) · **B6 2024: 47,984** (>150k applicants) · **B7 2024/25: 30,228** (final batch; 839 universities, 379 partners).

**Arithmetic:** >120k + 47,984 + 30,228 ≈ **>198k through batch 7** — so ">150k" (Kemdiktisaintek/Undana statement) is a true-but-stale lower bound, most plausibly uttered after batch 6 (~168k) and before batch 7 completed. **Verdict:** both statements true at their respective dates; best cumulative estimate through B7 ≈ **195–200k** (all fields, not IT-specific), with ">150k" as the citable official floor and batches 2–4 the residual uncertainty (~70k implied sum). Dashboard: show the batch series + est. cumulative ~198k labeled "sum of official batch counts; batches 2–4 bounded only".

### C5. Salary level mismatch: Michael Page 20–30jt averages vs Glints 6–11jt advertised medians

**Not contradictory — different population × metric × seniority:**
- **Glints**: median of *advertised* salary mid-points, from the subset of postings disclosing salary (≈15k tech postings/semester) — SME/startup-heavy, **junior-skewed**, i.e. "what entry/junior jobs at SMEs advertise."
- **Michael Page**: average from ~5,000 placement/client benchmark points via a recruiter — MNC/large-local, **seniority-mixed toward experienced professionals**, i.e. "what experienced people placed by headhunters earn." Their tech table spans engineer (20–30jt) to VP Engineering (108jt); averages are dominated by mid-senior roles.
- The two are consistent with Glints' own senior/entry ratio (2.7×→2.9×) and +20.8% senior vs +11.1% entry growth. Sanity: Glints senior backend (11–30jt across industries) overlaps MP backend average (25jt).
**Dashboard treatment:** plot as two clearly-labeled metrics — "advertised median (posting-level, junior-skewed)" vs "placed average (recruiter benchmark, senior-skewed)" — never on one unlabeled axis; show the seniority bridge (Glints junior→senior bands) connecting them.

### C6. GoTo headcount trajectory — verified with latest audited number

- Pre-Nov 2022 base: ~10,800–11,000 permanent (implied by company statement 1,300 = 12%) — conf 4.
- Layoffs: Nov 2022 1,300; Mar 2023 ~600 (cumulative ~1,900 early 2023).
- Revelio (profile-based): 3,888 (2023) → 3,521 (2024) → ~3,375 (mid-2026 est).
- **NEW (verified this session):** GoTo audited FY2025 consolidated financial statements (EY-audited, published 10 Mar 2026) disclose **3,553 permanent employees as of 31 Dec 2025 (31 Dec 2024: 3,352)**.
- **Verdict:** Trajectory consistent — ~70% peak-to-trough collapse 2022–2024, then **stabilization/slight regrowth in 2025 (+201, +6% YoY)**. Revelio vs company-disclosed figures agree within ~5%, validating Revelio as trend source. Caveat: Revelio counts ≈ profiles; company number = group permanent payroll (driver-partners excluded). Post-2025: Tokopedia tech-unit restructuring continues (>450 reported cut in TikTok/Tokopedia tech unit, Jul 2026; "~10% of Tokopedia staff remain" media claim, company denies) — the 2026 endpoint is still falling; track via Revelio.

---

## 2. Workforce Size Estimate Model

### Assumptions table

| # | Anchor | Value (year) | What it covers | Conf | Use in model |
|---|---|---|---|---|---|
| A1 | BPS Sakernas, category J Informasi & Komunikasi | 1.25M (Feb 2025) | Telecom + publishing + broadcast + IT (KBLI 58–63) employees | 4 (usable-with-caveats, weak-provincial) | Upper bound for formal ICT-sector employees; subtract non-IT segments |
| A2 | ADBI/ADBI WP 1258 | 894k (2018) | ICT sector incl. telecom | 4 | Lower-band historical anchor |
| A3 | Sakernas KBLI 62 share ≈ 0.4–0.6% of employed (~145M) | ~580k–870k | "Programming, computer consultancy & other computer activities" (5-digit coding weak: supervisor-coded write-ins, small-domain noise) | 3 | Central band for IT-services occupation |
| A4 | Kominfo "1.09M digital workers = 0.75% of 144M labor force" | 1.09M (2023) | Undefined "digital workers", methodology unpublished | 2–3 | Upper-bound corroboration only |
| A5 | J. Jasa Profesional +14.5% yoy to 2.53M (Feb 2025, BPS) | — | Professional-services employment (incl. outstaffed IT, IT embedded in consultancies) | 3 (weak) | Evidence significant IT headcount hides outside category J |
| A6 | SlashData-derived | ~0.8M coders (2022) → ~1.0–1.5M (2025 est) | People actively coding (incl. students/semi-pro), derived from 32% rest-of-East-Asia share | 3 (share) / 2 (absolute) | Upper band for coder population |
| A7 | LinkedIn keyword profiles | ~236K (2023) | Self-identified SWE/developer/programmer professionals on LinkedIn | 2 | Floor (LinkedIn coverage of ID workforce low) |
| A8 | Access Partnership/Google app economy | 36K direct technical app-dev jobs (2023) | Narrow app-economy direct technical roles only | 3 | Lower-bound for one segment only |
| A9 | GitHub Octoverse | 4.37M accounts (2025); 5.27M (Q1 2026) | Accounts (students, hobbyists, multi-account) | 4 for count; not a workforce measure | Funnel-top; never use as supply |
| A10 | Consultant claim | ~660K working professional SWEs (2026) | Unknown | 1 | Rejected (quality gate) |
| A11 | Komdigi "3 juta digital talents" (2025 framing) | 3M | Broader digital-skilled workforce claim (incl. non-IT digital occupations) | 2–3 | Corroboration for broader tier only |
| A12 | IT grads/yr (PDDikti bottom-up) | ~70–85k computing graduates/yr; +TI/SI new entrants 94k/yr | Annual professional-grade supply flow | 3–5 | Flow input: workforce stock must be ≥ several years of net inflow minus attrition |

**Derivation, Tier 1 — Employed IT professionals (earning their living from IT work):**
- IT-specific core of category J: empirical weight of telecom/broadcast/publishing inside J plausibly 30–50% → **600k–900k** in formal ICT-sector IT roles (A3's KBLI-62 band 580–870k agrees).
- Embedded/in-house IT in banks,manufacturing, government, consultancies (coded under other industries; A5): conservative uplift +10–20% → **660k–1.05M**.
- Freelance/contract IT workers coded informal (a large share per file 07/03; 1000 Startup program ratio 5 informal : 1 formal): +5–15% → **700k–1.2M**.
- Cross-checks: Kominfo 1.09M just above top; ADBI 894k (2018, incl. telecom) inside band after growing 2018→2025; file-10 triangulation 900k–1.5M slightly higher (uses broader IT definition) — our band deliberately conservative at the top.

**→ (a) Employed IT professionals: 700k–1.2M (point ≈ 950k, ~2025). Confidence 2–3 (triangulated; no direct census exists).**
Sub-range: *strict professional software developers/engineers* (excl. support/ERP/network/data-adjacent): **300k–600k (point ≈ 450k)** — bounded by LinkedIn floor 236K (A7 low coverage ⇒ true number above) and consultant 660K/A6 coder population (incl. non-professional ⇒ true professional core below).

**Tier 2 — Broader digital-fluency/digital-jobs workforce** (workers using substantive digital skills incl. non-IT digital occupations — digital marketing, e-commerce ops, data-enabled office roles): anchored by Komdigi 3M claim + IMDI framework tiers: **2.5M–4M (point ≈ 3M). Confidence 2.**

**Tier 3 — Platform-economy earners** (context, not IT professionals): ~13.2M engaged in e-commerce (WB 2019); ~20M earn some income via platforms / ~4.5M exclusively / ~2.25M active ride-hail/delivery gig workers (Caribou 2022–24, conf 3).

**Funnel metrics (not workforce):** GitHub 4.37M accounts; GNLD 24.6M literacy-trained since 2017; Microsoft 2.4M AI-trained; AWS >1.3M trained; DTS 572k (69k core); registered freelance-platform profiles >1.4M vs <10K Upwork ever-earning ≥$1 (registered-vs-active gap ≥ 2 orders of magnitude).

---

## 3. Quality Gate — Rejected Numbers (builder must not use; confidence ≤2 or methodology-lost)

**Workforce size & gap claims:**
1. "9M digital talents needed by 2030 / 600k/yr" — citation-chain rhetoric; only as labeled narrative, never as data (C1).
2. IMDI "12M by 2030" — non-public BPS-lineage model; labeled government claim only.
3. AWS/Access Partnership "110M digitally-skilled workers needed" — vendor-inflated definition (includes basic digital literacy); conf 2.
4. AWS "19% of workforce are digital workers"; Erick Thohir "17.5M tech-adaptable workers" — no methodology.
5. Komdigi "1 juta talenta digital baru 2018–2024" — aggregation unclear, conf 2; use 572,072 instead.
6. "10 juta coder" Indonesia–UAE — target, not data.
7. Kemnaker SKKNI "1,979,418 ICT HR needed 2025" — BPS-derived projection, conf 2.
8. Consultant "~660K working SWEs" (LinkedIn post, conf 1); ASPIlUKI "~2M developers" (conf 2, no method); LinkedIn 236K profile count (conf 2) — floor annotation only, not a headline estimate.
9. GitHub "4.37M developers" as developers/workforce — accounts, funnel only. Same for "8.7M by 2030" projection.
10. ESA-UNGGIL Bayesian single-role projections (e.g., "257K mobile devs by 2030") — conf 2.

**BPS-specific (per file-10 verdicts):**
11. Sakernas Nov 2025 round (first-ever quarterly release; LPEM-criticized) — AVOID entirely.
12. Sakernas province-level category-J / KBLI-62 cuts (±20% swings unmatched by real cycles) — AVOID.
13. BPS "13.6M freelancers / 46.47M (2023)" — definitional mismatch (casual day labor ≠ digital freelancers); banned.
14. KBLI-62 point estimates as sole source; Feb-round provincial detail; pandemic-era (2020–21) levels.

**Program & bootcamp:**
15. RevoU "90%+ placement in 6 months" — recirculated, unverifiable origin.
16. Hacktiv8 alumni 3,100+ / RevoU 15,000+ — self-reported marketing (conf 2); display-only context, never in supply math.
17. DTS headline 572,072 used *without* Microskill decomposition — always decompose (88% is micro-credentials).
18. GNLD 24.6M as workforce/training-scale for IT — short-workshop literacy, exclude from IT supply.

**Corporate:**
19. Bank Mandiri "3,000 tech engineers" — could not be verified; rejected (verifiable proxy: MDA→ODP-IT ~600/bootcamp).
20. eFishery headcount claims — admitted financial fraud, unreliable.
21. BNI IT division "400/406" — snippet-level, unverified.
22. theorg.com Telkomsigma team sample (conf 1); Infobelpro "9,318 software companies" (conf 2 registry); "ABSI" association (unverified name); EPAM/Capgemini Indonesia headcounts (conf 1).
23. Startup totals "2,200–2,390 active" vs "<1,000" — definitional; no single number usable.

**Platforms & freelance:**
24. Sribu ">1.3 juta talenta freelancer" — marketing, all categories, registered ≠ active (conf 2); Fastwork ">150,000 jobs" (multi-country, all categories, conf 2).
25. Turing "Indonesia top-5 supplier", Arc.dev, Deel/Oyster/Remote Indonesia counts, Payoneer Indonesia rates — no published verification exists at all (conf 1).
26. E33G remote-worker KITAS take-up — no retrievable figure.
27. sikatin-type "45,000 unfilled cyber vacancies / 1,000 cyber grads/yr" — verbal tradition, no primary source (conf 1).
28. Hacktiv8/ACE blog growth claims (+200% AI postings, +45% DevOps postings) — no methodology (conf 1).
29. ChatGPT "129M Indonesian users" figure — implausible vs 204.7M internet users.

**Salaries & market:**
30. Levels.fyi Indonesia (n=289 self-reported) — conf 2; thin-sample annotation at best.
31. Indeed Indonesia SWE average Rp11.12jt — self-report + ad mix, conf 2.
32. "20–30% salary jump when switching" — blog-circulated, unverified primary.
33. Salary aggregator blogs (kantorku/baodev/whatsthesalary, PoiData 610 DIY companies, Amikom "84 digital creative companies") — SEO/scrape, conf 1–2.

**Implicit rule for the builder:** confidence 3+ enters charts; confidence 2 enters only as clearly-flagged context/floor annotations; confidence 1 never renders.

---

## 4. Curated JSON (complete dashboard dataset)

```json
{
  "meta": {
    "country": "Indonesia",
    "as_of": "2026-11-09",
    "confidence_scale": "1-5 (5=administrative census/audited; 4=official or verified method; 3=survey/vendor w/ described method; 2=weak/self-reported/derived; 1=unverifiable)",
    "freshness_legend": {"live": "snapshot 2026-11", "current": "2025-2026", "recent": "2023-2024", "stale": "2018-2022"},
    "bps_policy": "BPS figures carry file-10 verdicts; used only with caveats where verdict = usable-with-caveats"
  },

  "headline_kpis": {
    "employed_it_professionals": {
      "range_low": 700000, "range_high": 1200000, "point_estimate": 950000, "year": 2025,
      "source": "Synthesis triangulation: BPS Sakernas cat-J 1.25M; KBLI-62 band 580-870k; Kominfo 1.09M; ADBI 894k(2018); embedded-IT uplift; freelance uplift",
      "confidence": 2, "freshness": "current",
      "definition": "people earning their living from IT work, incl. freelance IT; excludes telecom/broadcast-only roles",
      "assumptions": ["category J minus 30-50% telecom/broadcast/publishing", "+10-20% in-house IT coded in other industries (outstaffing sits in Jasa Profesional, 2.53M)", "+5-15% informal IT freelancers"]
    },
    "professional_software_engineer_core": {
      "range_low": 300000, "range_high": 600000, "point_estimate": 450000, "year": 2025,
      "source": "bounded by LinkedIn ~236K profiles (floor; low LinkedIn coverage) and SlashData-derived coder population (ceiling incl. non-professionals)",
      "confidence": 2, "freshness": "current"
    },
    "broader_digital_fluency_workforce": {
      "range_low": 2500000, "range_high": 4000000, "point_estimate": 3000000, "year": 2025,
      "source": "Komdigi '3 juta digital talents' framing + IMDI framework tiers", "confidence": 2, "freshness": "current",
      "definition": "workers using substantive digital skills incl. non-IT digital occupations"
    },
    "platform_economy_earners": {
      "some_income_via_platforms": 20000000, "exclusively": 4500000, "active_gig_delivery_ridehail": 2250000,
      "year": "2022-2024", "source": "Caribou Digital/Mastercard triangulation of platform self-reports + WB surveys", "confidence": 3, "freshness": "recent",
      "note": "context tier, not IT professionals"
    },
    "github_accounts": {"value": 4370000, "year": 2025, "q1_2026": 5270000, "source": "GitHub Octoverse 2025 / Innovation Graph", "confidence": 4, "freshness": "current", "honesty_label": "ACCOUNTS NOT PROFESSIONALS - funnel-top only"},
    "talent_gap_narratives": [
      {"claim": "9M digital talents needed by 2030 (~600k/yr)", "honesty_label": "CITATION-CHAIN RHETORIC", "what_it_measures": "cumulative 2015-2030 shortfall of skilled AND semi-skilled ICT workers", "origin": "JPM/McKinsey New Skills at Work 2016 (non-public model) via World Bank 2018 desk review; misattributed 3 ways by officials", "source": "WB 'Preparing ICT Skills for Digital Economy' 2018", "year": 2018, "confidence": 3, "freshness": "stale"},
      {"claim": "12M digital talents by 2030 (gap ~3M; ~500k/yr)", "honesty_label": "GOVERNMENT PLANNING PROJECTION", "what_it_measures": "demand projection for all digital-skill levels, built on BPS + education-ministry data", "source": "Kominfo IMDI 2024", "year": 2024, "confidence": 4, "freshness": "recent", "lineage_flag": "BPS-derived"},
      {"claim": "~456k digital talents needed/year", "honesty_label": "CURRENT OFFICIAL PLANNING NUMBER (BPS-lineage, unverifiable inputs)", "note": "ministry drifted 450k->453k->456k->600k/yr across 18 months of statements", "source": "BPSDM Komdigi internal modeling on BPS data", "year": 2025, "confidence": 4, "freshness": "current"},
      {"claim": "oversupply of ~151,495 digital-skilled graduates 2021-2025 (~30.3k/yr)", "honesty_label": "ACADEMIC FLOW MODEL - entry-level graduates vs broad ICT occupation growth; Kominfo-funded; demand input BPS-derived", "detail": "supply 3,372,392 graduates vs demand 3,220,897 occupations; 2016-20 actuals were a 392,219 deficit", "source": "Gayatri et al., Sustainability 15(1):754 (BRIN), verified full text", "year": 2022, "confidence": 4, "freshness": "stale"},
      {"claim": "IMPLICATION: no genuine market-demand estimate exists; real condition = skill/seniority MISMATCH (entry oversupply + senior shortage)", "honesty_label": "SYNTHESIS VERDICT", "evidence": "senior advertised pay +20.8% vs entry +11.1% (Glints 2026); fresh grads' hardest job search on record (LPEM UI 2026); counter-offer wars (Michael Page 2025)", "confidence": 3, "freshness": "live"}
    ],
    "benchmark_anchors": {
      "bps_category_J_employment": {"value": 1250000, "year": "Feb 2025", "source": "BPS Sakernas via Databoks", "confidence": 4, "freshness": "current", "caveat": "includes telecom/publishing/broadcast; national level only"},
      "adbi_ict_sector_2018": {"value": 894000, "year": 2018, "source": "ADBI WP 1258 (Sakernas 2018)", "confidence": 4, "freshness": "stale"},
      "kominfo_digital_workers_claim": {"value": 1090000, "year": 2023, "source": "Menkominfo via Bisnis.com, methodology unpublished", "confidence": 3, "freshness": "recent"},
      "kornferry_tmt_deficit": {"range": "600k-1.2M by 2030", "year": 2018, "source": "Korn Ferry Global Talent Crunch", "confidence": 3, "freshness": "stale", "note": "order-of-magnitude comparator exposing definitional inflation of 9M"}
    }
  },

  "demand_by_role": {
    "method_note": "LinkedIn guest job-search counts, location=Indonesia, snapshot 9 Nov 2026; keyword overlap means DO NOT SUM across role families; not total market (misses non-LinkedIn boards, remote-global)",
    "live_linkedin_vacancies_2026_11_09": [
      {"role": "data analyst", "value": 2151, "source": "LinkedIn guest job search", "confidence": 4, "freshness": "live", "note": "BI 1,357; largest single IT keyword"},
      {"role": "software engineer/developer/programmer (overlapping)", "value": "[1461, 1402, 1339]", "source": "LinkedIn guest", "confidence": 4, "freshness": "live"},
      {"role": "QA engineer/tester (overlapping)", "value": "[1013, 838]", "source": "LinkedIn guest", "confidence": 4, "freshness": "live"},
      {"role": "backend developer", "value": 870, "note": "by language: java 553, python 578, golang 413, node 284, php 201", "source": "LinkedIn guest", "confidence": 4, "freshness": "live"},
      {"role": "IT support", "value": 859, "note": "sysadmin 650, network engineer 460", "source": "LinkedIn guest", "confidence": 4, "freshness": "live"},
      {"role": "AI/ML engineer (combined)", "value": 1058, "note": "AI eng 653 + ML eng 405", "source": "LinkedIn guest", "confidence": 4, "freshness": "live"},
      {"role": "data engineer", "value": 772, "source": "LinkedIn guest", "confidence": 4, "freshness": "live"},
      {"role": "devops engineer (SRE separately 750)", "value": 772, "source": "LinkedIn guest", "confidence": 4, "freshness": "live"},
      {"role": "cloud engineer", "value": 676, "source": "LinkedIn guest", "confidence": 4, "freshness": "live"},
      {"role": "web developer", "value": 608, "source": "LinkedIn guest", "confidence": 4, "freshness": "live"},
      {"role": "cybersecurity", "value": "[611, 601]", "source": "LinkedIn guest", "confidence": 4, "freshness": "live"},
      {"role": "fullstack developer", "value": 651, "source": "LinkedIn guest", "confidence": 4, "freshness": "live"},
      {"role": "frontend developer", "value": "[329, 325]", "source": "LinkedIn guest", "confidence": 4, "freshness": "live"},
      {"role": "ERP (ERP 572, SAP 378, Odoo 290)", "value": 572, "source": "LinkedIn guest", "confidence": 4, "freshness": "live"},
      {"role": "mobile developer (all)", "value": "[271, 157, 147, 103, 93]", "note": "mobile, flutter, android, ios, react native", "source": "LinkedIn guest", "confidence": 4, "freshness": "live"},
      {"role": "data scientist", "value": 804, "source": "LinkedIn guest", "confidence": 4, "freshness": "live"}
    ],
    "fastest_growing_roles": [
      {"role": "cyber security engineer", "rank": 2, "of": 15, "source": "LinkedIn Jobs on the Rise Indonesia 2025 (title growth Jan2022-Jul2024)", "year": 2025, "confidence": 4, "freshness": "recent"},
      {"role": "SOC analyst", "rank": 3, "of": 15, "source": "LinkedIn JoR 2025", "year": 2025, "confidence": 4, "freshness": "recent"},
      {"role": "project manager (IT industry prominent)", "rank": 14, "of": 15, "source": "LinkedIn JoR 2025", "year": 2025, "confidence": 4, "freshness": "recent"},
      {"role": "AI engineer (graduates only)", "rank": 1, "of": 3, "source": "LinkedIn Grad Guide 2025 (Jan 2022-Dec 2024)", "year": 2025, "confidence": 4, "freshness": "recent", "note": "AI roles NOT in overall top-15 - Indonesia's 2022-24 growth was security-led, not AI-led"}
    ],
    "skill_demand_shares_pct_of_tech_postings": {"MySQL": 17, "JavaScript": 14, "Python": 13, "PostgreSQL": 13, "Node.js": 11, "React.js": 10, "Java": 10, "SQL": 8, "DataAnalysis": 5, "ML": 4, "AI": 4, "source": "Glints skills report (Jan-Aug 2026 postings)", "year": 2026, "confidence": 3, "freshness": "live"},
    "tech_job_postings_tracker": {"active_postings": 2717, "month": "Jan 2024", "delta": "-8.9% since Oct 2023", "source": "GlobalData job-postings tracker", "confidence": 3, "freshness": "recent"}
  },

  "salaries": {
    "method_note": "Two families, never to be plotted on one unlabeled axis: [glints] = advertised medians/ranges from postings, junior-skewed, SME-heavy; [mp] = recruiter-placement averages, senior-skewed, MNC/large-local; [rw] = recruiter annual bands. IDR/month unless stated.",
    "advertised_market": [
      {"role": "computer & software (category median)", "metric": "advertised_median", "value_m": 6.0, "source": "Glints LMI", "year": "H1 2026", "confidence": 3, "freshness": "live", "note": "+9.1% vs H1 2024 (5.5M); n~15k disclosed-salary postings"},
      {"role": "backend developer (senior bucket)", "metric": "advertised_median", "value_m": 7.5, "source": "Glints LMI", "year": "H1 2026", "confidence": 3, "freshness": "live", "note": "+25% in 2 yrs"},
      {"role": "national median all roles", "value_m": 3.5, "source": "Glints", "year": "H1 2026", "confidence": 3, "freshness": "live"}
    ],
    "role_level_bands": [
      {"role": "software engineer", "level": "junior-mid (cross-industry)", "min_m": 6.0, "max_m": 14.0, "source": "Glints HR & Salary Survey 2024", "year": 2024, "confidence": 3, "freshness": "recent"},
      {"role": "software engineer", "level": "senior", "min_m": 15.0, "max_m": 35.5, "source": "Glints Survey 2024 (retail 15-20; new economy 28.5-35.5)", "year": 2024, "confidence": 3, "freshness": "recent"},
      {"role": "backend developer", "level": "junior-mid", "min_m": 7.0, "max_m": 11.0, "source": "Glints Survey 2024", "year": 2024, "confidence": 3, "freshness": "recent"},
      {"role": "backend developer", "level": "senior", "min_m": 11.0, "max_m": 30.0, "source": "Glints 2024 (tech 11-20; finance 16.7-23.3; media 20-30)", "year": 2024, "confidence": 3, "freshness": "recent"},
      {"role": "frontend developer", "level": "junior-mid", "min_m": 7.0, "max_m": 13.0, "source": "Glints 2024", "year": 2024, "confidence": 3, "freshness": "recent"},
      {"role": "frontend developer", "level": "senior", "min_m": 11.0, "max_m": 40.0, "source": "Glints 2024 (tech 11-23; finance 20-40)", "year": 2024, "confidence": 3, "freshness": "recent"},
      {"role": "fullstack developer", "level": "junior-mid", "min_m": 7.3, "max_m": 13.3, "source": "Glints 2024", "year": 2024, "confidence": 3, "freshness": "recent"},
      {"role": "fullstack developer", "level": "senior", "min_m": 13.0, "max_m": 28.0, "source": "Glints 2024 (tech 13-17; finance 15-28)", "year": 2024, "confidence": 3, "freshness": "recent"},
      {"role": "android developer", "level": "junior-mid", "min_m": 8.0, "max_m": 12.0, "source": "Glints 2024", "year": 2024, "confidence": 3, "freshness": "recent"},
      {"role": "iOS developer", "level": "junior-mid", "min_m": 10.0, "max_m": 15.0, "source": "Glints 2024", "year": 2024, "confidence": 3, "freshness": "recent"},
      {"role": "devops engineer", "level": "senior (tech)", "min_m": 18.0, "max_m": 27.0, "source": "Glints 2024", "year": 2024, "confidence": 3, "freshness": "recent"},
      {"role": "SRE", "level": "senior (property)", "min_m": 25.0, "max_m": 38.0, "source": "Glints 2024", "year": 2024, "confidence": 3, "freshness": "recent"},
      {"role": "QA automation", "level": "junior-mid", "min_m": 6.0, "max_m": 10.0, "source": "Glints 2024", "year": 2024, "confidence": 3, "freshness": "recent"},
      {"role": "QA", "level": "senior (finance)", "min_m": 15.0, "max_m": 24.0, "source": "Glints 2024", "year": 2024, "confidence": 3, "freshness": "recent"},
      {"role": "data analyst", "level": "junior (advertised)", "min_m": 4.0, "max_m": 8.0, "source": "Glints salary list 2025", "year": 2025, "confidence": 3, "freshness": "recent"},
      {"role": "data engineer", "level": "junior (advertised)", "min_m": 5.0, "max_m": 7.7, "source": "Glints 2025", "year": 2025, "confidence": 3, "freshness": "recent"},
      {"role": "data scientist", "level": "junior (advertised)", "min_m": 4.0, "max_m": 8.0, "source": "Glints 2025", "year": 2025, "confidence": 3, "freshness": "recent"},
      {"role": "solution architect", "level": "senior (finance)", "min_m": 19.0, "max_m": 34.0, "source": "Glints 2024", "year": 2024, "confidence": 3, "freshness": "recent"}
    ],
    "recruiter_placed_averages_mp2025": [
      {"role": "frontend developer", "value_m": 20}, {"role": "QA engineer", "value_m": 23},
      {"role": "backend developer", "value_m": 25}, {"role": "mobile developer", "value_m": 25},
      {"role": "fullstack developer", "value_m": 30}, {"role": "ERP functional (SME)", "value_m": 37},
      {"role": "tech lead", "value_m": 40}, {"role": "IT GRC manager", "value_m": 40},
      {"role": "IT manager", "value_m": 50}, {"role": "solution architect", "value_m": 55},
      {"role": "engineering manager", "value_m": 67}, {"role": "head of engineering", "value_m": 81},
      {"role": "head of IT", "value_m": 85}, {"role": "VP engineering", "value_m": 108},
      {"source": "Michael Page Indonesia Salary Guide 2025 (~5,000 benchmark pts)", "year": 2025, "confidence": 3, "freshness": "recent",
       "honesty_label": "AVERAGES SENIOR-SHOT: placed professionals at MNC/large locals - upper band of market"}
    ],
    "recruiter_annual_bands_rw2026": [
      {"role": "software developer", "min_pa": 440000000, "max_pa": 770000000, "source": "Robert Walters 2026", "year": 2026, "confidence": 3, "freshness": "current"},
      {"role": "data scientist", "min_pa": 450000000, "max_pa": 850000000, "source": "RW 2026", "year": 2026, "confidence": 3, "freshness": "current"},
      {"role": "head of cyber security", "min_pa": 1300000000, "max_pa": 1600000000, "source": "RW 2026", "year": 2026, "confidence": 3, "freshness": "current"},
      {"role": "CTO/CIO", "min_pa": 1900000000, "max_pa": 3200000000, "source": "RW 2026", "year": 2026, "confidence": 3, "freshness": "current"}
    ],
    "trend_signals": [
      {"metric": "senior vs entry advertised salary growth", "senior_pct": 20.8, "entry_pct": 11.1, "ratio": "2.7x -> 2.9x", "source": "Glints LMI", "year": "H1'24-H1'26", "confidence": 3, "freshness": "live"},
      {"metric": "annual increments (counter-offer culture in fin-services tech)", "value": "5-8%", "source": "Michael Page 2025", "year": 2025, "confidence": 3, "freshness": "recent"},
      {"metric": "projected salary increase 2026/2027 (Indonesia top of SEA)", "value": 5.9, "unit": "%", "source": "Aon Salary Increase Survey (Oct 2025)", "year": 2025, "confidence": 4, "freshness": "current"},
      {"metric": "tech employees earn premium vs non-tech (SEA startups)", "value": 29, "unit": "%", "source": "Glints x Monk's Hill 2024", "year": 2024, "confidence": 3, "freshness": "recent"}
    ]
  },

  "supply_pipeline": {
    "higher_education": [
      {"metric": "computing graduates/yr (all target majors, S1+D)", "est_range": "70,000-85,000", "source": "PDDikti bottom-up (TI 35,919 + SI 25,866 verified; Ilmu Komputer/RPL/TI/MI est 10-20k)", "year": "2023/24", "confidence": 3, "freshness": "recent"},
      {"metric": "Teknik Informatika graduates", "value": 35919, "source": "PDDikti via Detik/JawaPos", "year": "2023/24", "confidence": 4, "freshness": "recent"},
      {"metric": "Sistem Informasi graduates", "value": 25866, "source": "PDDikti", "year": "2023/24", "confidence": 4, "freshness": "recent"},
      {"metric": "new entrants TI", "value": 46035, "source": "Statistik Pendidikan Tinggi 2025 p.122 (PDDikti census)", "year": 2025, "confidence": 5, "freshness": "current"},
      {"metric": "new entrants SI", "value": 48335, "source": "Statistik PT 2025", "year": 2025, "confidence": 5, "freshness": "current"},
      {"metric": "enrolled TI + SI (all years)", "value": 443331, "source": "Statistik PT 2025 p.166", "year": 2025, "confidence": 5, "freshness": "current"},
      {"metric": "total HE graduates all fields", "value": 2547717, "source": "Statistik PT 2025 p.204", "year": 2025, "confidence": 5, "freshness": "current"}
    ],
    "vocational_smk": [
      {"metric": "SMK students (all fields)", "value": 4876648, "schools": 14391, "source": "Direktorat SMK dashboard (Dapodik)", "year": "2025/26", "confidence": 4, "freshness": "live"},
      {"metric": "class-12 cohort (approx annual grad flow, all fields)", "value": 1529042, "source": "Direktorat SMK dashboard", "year": "2025/26", "confidence": 4, "freshness": "live"},
      {"metric": "TIK share of SMK grads (only as top-3-field combo, TRE+BM+TIK)", "value": 80.2, "unit": "% combined", "source": "PSKP Kemendikdasmen kajian", "year": 2019, "confidence": 3, "freshness": "stale"}
    ],
    "dts_core": [
      {"year": 2020, "realized": 58116, "budget_idr_bn": 16.4, "source": "DPR RI PA3KN brief (audited LKj BPSDM)", "confidence": 5, "freshness": "stale"},
      {"year": 2021, "realized": 123772, "budget_idr_bn": 122.6, "source": "DPR RI brief (audited); Bappenas 123,412; ministry press said 131,204 - use audited", "confidence": 4, "freshness": "stale"},
      {"year": 2022, "realized_min": 200000, "source": "Kominfo via sdmdigital.id (283,906 applicants)", "confidence": 4, "freshness": "stale"},
      {"year": 2023, "graduated": 92192, "source": "Antara quoting Kabadan SDM", "confidence": 4, "freshness": "recent"},
      {"year": 2024, "note": "full-year total NOT published; only executing-center subtotals", "confidence": 2, "freshness": "recent"},
      {"metric": "cumulative graduates 2018-Oct 2025", "value": 572072, "decomposition": {"core_academies": 68964, "microskill": 503108}, "source": "Komdigi via Indonesiabaik infographic", "confidence": 3, "freshness": "current", "honesty_label": "88% is low-intensity Microskill; supply-relevant core is ~69k cumulative; BPK audit found participant data unreconcilable"}
    ],
    "msib": [
      {"batch": 1, "year": 2021, "participants": 13272, "source": "MUDIMA journal citing program data", "confidence": 3, "freshness": "stale"},
      {"batch": "1-4", "cumulative_min": 93000, "source": "Tirto citing Kemendikbudristek", "year": 2023, "confidence": 3, "freshness": "recent", "note": "batches 2-4 not individually published"},
      {"batch": 5, "year": 2023, "participants": 36719, "applicants": 98000, "source": "Medcom quoting MSIB head", "confidence": 4, "freshness": "recent"},
      {"batch": "1-5", "cumulative_min": 120000, "source": "Antara quoting official", "year": "Nov 2023", "confidence": 4, "freshness": "recent"},
      {"batch": 6, "year": 2024, "participants": 47984, "applicants": ">150,000", "source": "kemdikbud.go.id official", "confidence": 5, "freshness": "recent"},
      {"batch": 7, "year": "2024/25", "participants": 30228, "partners": 379, "universities": 839, "source": "kemdiktisaintek.go.id (final batch)", "confidence": 5, "freshness": "recent"},
      {"metric": "cumulative through batch 7 - best estimate", "value": 198000, "est_range": "195k-200k", "source": "synthesis: sum of official batch counts (batches 2-4 bounded only)", "confidence": 2, "freshness": "recent", "honesty_label": "official floor is '>150k' (stated mid-cycle); all fields, tech-share never published"}
    ],
    "bootcamps": [
      {"program": "Bangkit (Google/GOTO/Traveloka)", "cohort": "~3,000 admitted/yr; 2,250 graduated 2021", "source": "Google Cloud blog + participant accounts", "confidence": 3, "freshness": "stale"},
      {"program": "Hacktiv8 (self-reported)", "alumni": 3100, "source": "hacktiv8.com", "confidence": 2, "freshness": "current", "honesty_label": "CONTEXT-ONLY, marketing figure"},
      {"program": "RevoU (self-reported)", "alumni": 15000, "source": "revou.co", "confidence": 2, "freshness": "current", "honesty_label": "CONTEXT-ONLY, marketing figure"}
    ],
    "employer_pipeline_evidence": [
      {"metric": "BCA hires 'mainly IT' 2023", "value": 4000, "source": "BCA Annual Report 2023 p.29 (audited)", "confidence": 5, "freshness": "recent"},
      {"metric": "Bank Mandiri My Digital Academy batch-2 graduates funneled to ODP-IT", "value": 600, "applicants": 24673, "source": "official statements via viva/gadget", "confidence": 4, "freshness": "recent"}
    ],
    "absorption_gaps_note": "no credible national '% of computing grads employed in-field' figure exists; university tracers suggest 70-75% working within 1 yr, 85-93% within 2 yrs (extrapolation, conf 2)"
  },

  "formal_informal": {
    "formal_economy_context": [
      {"metric": "BPJS Ketenagakerjaan active participants", "value": 39700000, "of_which_bpu_informal": 8990000, "source": "BPJSTK", "year": "Apr 2025", "confidence": 5, "freshness": "current", "note": "no KBLI-sector cut published - formal IT employment cannot be derived from BPJS"},
      {"metric": "informal employment share (all sectors)", "value": 57.7, "unit": "%", "source": "BPS (usable-with-caveats; series break Feb 2025 - 21st ICLS redefinition)", "year": "Nov 2025", "confidence": 3, "freshness": "live-as-of-but-round-AVOID", "honesty_label": "tech freelancers/remote contractors systematically MISCLASSIFIED as informal"}
    ],
    "informal_it_evidence": [
      {"metric": "1000 Startup Digital program job outcomes (only govt formal/informal split found)", "formal_permanent": 4000, "informal_freelance": 20000, "ratio": "5:1 informal:formal", "source": "Menkominfo via Antara", "year": 2023, "confidence": 3, "freshness": "recent"},
      {"metric": "DTS PROA intake composition", "already_employed_pct": 83, "unemployed_pct": 17, "source": "bpsdm.komdigi.go.id", "year": 2024, "confidence": 4, "freshness": "recent"},
      {"metric": "Upwork: Indonesian profiles ever earning >=$1", "value": "<10,000", "above_100k_usd": 169, "source": "LSE (Permana) scrape analysis", "year": 2023, "confidence": 3, "freshness": "recent"},
      {"metric": "registered freelancer profiles across 9 platforms (2018)", "value": 171033, "active_28d": 2062, "active_pct": 1.2, "source": "Sucahyo et al. (DIODE) web scrape", "year": 2018, "confidence": 4, "freshness": "stale"},
      {"metric": "registered-vs-active structural gap (IT slice)", "value": "2+ orders of magnitude", "source": "file-07 triangulation (Sribu/Fastwork claims vs Upwork earners)", "confidence": 2, "freshness": "current", "honesty_label": "KEY MODELING ANCHOR: registrations massively overstate active workforce"},
      {"metric": "semi-formal TaaS/body-shop channel (Gigson by Devcenter)", "status": "verified existence, no volumes published", "source": "devcenter.co direct fetch", "confidence": 3, "freshness": "live"}
    ],
    "government_employment": [
      {"metric": "CPNS 2024 total formasi (all fields)", "value": 207247, "source": "Setkab/BKN", "year": 2024, "confidence": 4, "freshness": "recent"},
      {"metric": "Kominfo/Komdigi CPNS 2024 formasi", "value": 4215, "source": "Kominfo announcement", "year": 2024, "confidence": 4, "freshness": "recent"},
      {"metric": "national count of IT-role civil servants", "value": null, "note": "DATA GAP - does not exist publicly"},
      {"metric": "government IT demand runs through procurement (SPBE index 3.12, 615 institutions evaluated) not payroll", "value": 3.12, "source": "KemenPANRB (Kepmen)", "year": 2024, "confidence": 5, "freshness": "recent"}
    ],
    "freelance_remote_summary": {
      "modeling_note": "Government programs operate pre-employment (DTS 572k cumulative is training, not jobs); local-platform freelance-IT is small in earnings terms; formalized remote contracting grows via TaaS/EOR rails (Gigson) but publishes no volumes;",
      "magnitude_order": "registered supply ~1.4M+ profiles vs <10K ever earning >=$1 on Upwork: the genuinely active IT freelance/remote segment is likely in the low tens of thousands"
    }
  },

  "regional": {
    "jakarta_concentration": [
      {"metric": "LinkedIn jobs in Jakarta vs national (all roles, 1-day snapshot)", "value_pct": 55, "source": "LinkedIn jobs pages live crawl", "year": "Nov 2026", "confidence": 3, "freshness": "live"},
      {"metric": "share of national startup-ecosystem score (StartupBlink)", "value_pct": 84.8, "source": "StartupBlink 2026", "confidence": 4, "freshness": "live"},
      {"metric": "Greater Jakarta share of newest ICT postings (sample, non-random)", "value_pct": 70, "source": "JobStreet feed sample", "confidence": 2, "freshness": "live", "honesty_label": "CONTEXT-ONLY"}
    ],
    "city_salary_differentials_mid_it": [
      {"city": "Jakarta", "band": "12-20jt/mo (baseline)"},
      {"city": "Surabaya", "vs_jakarta_pct": -25}, {"city": "Bandung", "vs_jakarta_pct": -30},
      {"city": "Bali/Semarang", "vs_jakarta_pct": -38}, {"city": "Yogyakarta", "vs_jakarta_pct": -45},
      {"source": "Aniday recruiter benchmarks 2026", "year": 2026, "confidence": 3, "freshness": "live"},
      {"note": "outlier: Batam/Bintan/Kepri has HIGHEST advertised SWE average at 14jt/mo (JobStreet advertised-salary aggregation, conf 3, live); JobStreet national SWE typical band 6-9jt/mo"}
    ],
    "secondary_hubs": [
      {"city": "Bandung", "facts": {"digital_ready_grads_per_yr": 8000, "vc_value_share_pct_under": 3, "grads_leaving_to_jakarta_18m_pct": 33}, "source": "Digital Districts 2025", "confidence": 3, "freshness": "recent"},
      {"city": "Yogyakarta", "facts": {"software_companies_diy": 610, "source_conf": 2, "label": "POI-scrape, context-only"}, "confidence": 2, "freshness": "current"},
      {"city": "Surabaya", "facts": {"startup_funding_to_date_usd_m": 153}, "source": "Digital Districts 2025", "confidence": 3, "freshness": "recent"}
    ],
    "gap_note": "no BPS-free per-province IT workforce count exists; provincial split must be modeled from vacancy + graduate geography"
  },

  "emerging": {
    "ai": [
      {"metric": "relative AI-hiring growth (fastest in world)", "value_pct": 31.7, "source": "LinkedIn AI Index 2026 via Second Talent", "year": 2025, "confidence": 4, "freshness": "current"},
      {"metric": "AI-talent concentration growth 2019-25", "value_pct": 108, "source": "LinkedIn/Stanford HAI AI Index 2026", "confidence": 4, "freshness": "current"},
      {"metric": "AI talent headcount", "value": 96000, "note": "0.06% of workforce; was 28K in 2019; >70% reskilled from other professions", "source": "LinkedIn-based report via Kompas.id", "year": 2024, "confidence": 3, "freshness": "recent"},
      {"metric": "Indonesian businesses adopting AI", "value_m": 18, "growth_pct_yoy": 47, "source": "AWS Unlocking Indonesia's AI Potential (Access Partnership)", "year": 2026, "confidence": 4, "freshness": "current"},
      {"metric": "businesses citing digital-skills gap as main AI barrier", "value_pct": 57, "source": "AWS 2026", "year": 2026, "confidence": 4, "freshness": "current"},
      {"metric": "AI trained by Microsoft Elevate (2 yrs)", "value": 2400000, "credentials_issued": 1500000, "source": "Microsoft (self-reported program counts)", "year": 2026, "confidence": 3, "freshness": "current", "honesty_label": "training tickets, not employment"},
      {"metric": "AI wage premium Indonesia", "value": null, "note": "NO Indonesia-specific figure exists; global PwC barometer 56% - do not localize"},
      {"metric": "AI-app consumer revenue growth H1'24->H1'25 (highest in SEA)", "value_pct": 127, "source": "e-Conomy SEA 2025", "confidence": 4, "freshness": "current"}
    ],
    "cloud_infrastructure": [
      {"metric": "Microsoft Indonesia investment", "value_usd_b": 1.7, "period": "2024-2028", "verified": "Microsoft PR + Reuters", "confidence": 5, "freshness": "current"},
      {"metric": "AWS Jakarta region investment / modeled jobs-yr", "value_usd_b": 5, "jobs_yr": 24700, "source": "AWS Economic Impact Study", "confidence": 3, "freshness": "recent", "honesty_label": "modeled job-years incl supply chain, not payroll"},
      {"metric": "Indosat-NVIDIA Surakarta AI DC + AI-factory (train 1M by 2027 claim)", "value_usd_m": 200, "total_by_2027_usd_m": 1000, "source": "DCD reporting of company statements", "confidence": 3, "freshness": "current"},
      {"metric": "Zankore by Indosat (Ooredoo/Nokia/NVIDIA)", "value_usd_m": 800, "capacity": "200MW by H1-2027, 1GW long-term", "source": "DCD/FutureCIO", "year": 2026, "confidence": 4, "freshness": "live"},
      {"metric": "enterprise cloud adoption", "value_pct_under": 30, "source": "ADBI Policy Brief 2024-1", "confidence": 3, "freshness": "recent", "note": "lowest APAC tier - large forward hiring headroom"},
      {"metric": "public cloud services market", "value_usd_m": "~1,000 (2024F, from 538 2021)", "source": "IDC via Huawei white paper", "confidence": 3, "freshness": "recent"},
      {"metric": "APAC whole-cloud CAGR", "value_pct": 22.2, "to": 2028, "source": "IDC", "confidence": 3, "freshness": "current"}
    ],
    "cybersecurity": [
      {"metric": "orgs reporting difficulty hiring qualified cyber candidates", "value_pct": 73, "note": "3rd worst of 29 countries; only 50% see gap as risk (perception lag)", "source": "Fortinet Skills Gap 2022", "year": 2022, "confidence": 4, "freshness": "stale"},
      {"metric": "Indonesia cyber workforce gap figure", "value": null, "note": "NO credible Indonesia-specific number exists - ISC2 publishes APAC only (4.8M global gap 2024, conf 4, but no ID cut); '45,000 unfilled' is folklore (rejected)"},
      {"metric": "orgs citing lack of security skills as breach cause (global 2025)", "value_pct": 68, "source": "Fortinet 2025 Skills Gap", "confidence": 4, "freshness": "recent"},
      {"metric": "BSSN detected anomalies (threat pressure)", "value": 403990813, "year": 2023, "source": "BSSN via Kemnaker SKKNI 2025", "confidence": 3, "freshness": "recent", "note": "threat pressure well evidenced; workforce quantification is NOT a data gap the dashboard can close"}
    ]
  },

  "market_conditions": {
    "layoffs": [
      {"metric": "all-sector PHK (JKP claimants, formal-sector lower bound)", "series": {"2022": 25114, "2023": 64855, "2024": 77965, "2025": 88519, "2026_jan_oct": 72336}, "source": "Kemnaker Satudata", "confidence": 4, "freshness": "live"},
      {"metric": "tech/startup layoff events since 2020", "events": 149, "companies": 107, "headcount_floor": 8722, "est_true_range": "10,000-15,000 reported events 2022-25 (silent layoffs prevalent)", "peak": "2022 Q4 (GoTo 1,300)", "source": "ecommurz crowdsourced tracker", "confidence": 3, "freshness": "recent"},
      {"metric": "GoTo trajectory (verified)", "series": {"pre_nov2022": "~10,800-11,000", "2023": 3888, "2024_company": 3352, "2025_company": 3553, "mid_2026_revelio_est": 3375}, "source": "company layoff statements + Revelio Labs + GOTO FY2025 audited FS (verified this session)", "confidence": 4, "freshness": "live", "honesty_label": "FY2025 audited-report disclosure: 3,553 permanent employees at 31 Dec 2025 (3,352 at 31 Dec 2024) - ~70% peak-to-trough collapse 2022-24, then stabilization; Tokopedia tech-unit cuts resumed 2026"},
      {"metric": "role pattern", "value": "2022-23 cuts protected engineering partially; 2024-26 waves hit engineering directly (Tokopedia waves 2024/25/26, Accelbyte, Xendit, Populix)", "confidence": 3, "freshness": "recent"}
    ],
    "tightness": [
      {"metric": "voluntary attrition - Emerging Tech (peak-froth datapoint)", "value_pct": 15, "year": 2022, "source": "Mercer TRS 2022 (550 orgs)", "confidence": 4, "freshness": "stale"},
      {"metric": "Indonesia employers expecting more active hiring H2-2025", "value_pct": 42, "source": "JobStreet by SEEK HCB 2025", "confidence": 3, "freshness": "recent"},
      {"metric": "APAC employers struggling to fill roles (Indonesia NOT sampled - any 'Indonesia 77%' in press is APAC misattribution)", "value_pct": 77, "source": "ManpowerGroup Talent Shortage 2025 (n=40,413)", "confidence": 4, "freshness": "recent"},
      {"metric": "counter-offer war / 5-8% increments for scarce professionals", "source": "Michael Page 2025", "confidence": 3, "freshness": "recent"},
      {"metric": "BPS info-comm avg wage (employees)", "series": {"Aug2023_m": 5.13, "Aug2024_m": 4.98}, "source": "BPS (usable-with-caveats; employees only, category-J broad)", "confidence": 4, "freshness": "recent", "note": "decline during tech winter = credibility cross-check"}
    ],
    "macro_context": [
      {"metric": "digital economy GMV", "value_usd_b": 90, "year": 2024, "note": "+13%; largest in SEA; e-comm restated 65->62", "source": "e-Conomy SEA 2024", "confidence": 4, "freshness": "recent"},
      {"metric": "digital economy GMV", "value_usd_b": 99, "year": 2025, "note": "+14%; 2030 range $180-360B", "source": "e-Conomy SEA 2025", "confidence": 4, "freshness": "current"},
      {"metric": "audit-verified big-tech hiring signals", "value": "BCA ~4,000 hires 2023 'mainly IT' (AR, conf 5); Aon: IT/AI/cyber hottest 2026 roles, 42% firms with hiring challenges", "confidence": 4, "freshness": "current"},
      {"metric": "enterprise IT budgets (examples)", "value": "Mandiri IT capex Rp3T; BNI Rp1.9T; BRI ~Rp4-4.6T; BTN Rp1T; Telkom capex Rp24.5T (>50% digital conn.)", "source": "director statements via Bisnis/Kontan + audited filings", "confidence": 4, "freshness": "recent", "note": "Inpres 1/2025 efficiency cut (Rp256.1T) damped govt IT spend 2025 (Metrodata AR)"}
    ]
  },

  "source_credibility": {
    "bps_verdicts": {
      "sakernas_TPT": "USABLE_WITH_CAVEATS",
      "category_J_17cat": "USABLE_WITH_CAVEATS_national_only",
      "kbli62_5digit": "USABLE_WEAK_national_trend_only_never_point_estimate",
      "formal_informal_share": "USABLE_WITH_CAVEATS_series_break_Feb2025",
      "wages_infokom": "USABLE_WITH_CAVEATS_employees_only",
      "nov2025_round": "AVOID",
      "fabrication_assessment": "NOT SUPPORTED - weaknesses are fitness-for-purpose at granular tech detail, not fabrication; aggregates track external benchmarks"
    },
    "tier_1_sources": [
      "PDDikti/Statistik Pendidikan Tinggi 2025 (administrative census)",
      "Audited annual reports & IDX filings (Bukalapak, Blibli, Telkomsel, IOH, BCA, XL, GOTO FY2025 FS)",
      "DPR RI PA3KN policy brief (BPK-audit basis) for DTS",
      "KemenPANRB SPBE evaluations",
      "BPJS Ketenagakerjaan active-participant series",
      "Direktorat SMK Dapodik dashboard",
      "GOTO FY2025 audited financial statements (employee count, verified this session)"
    ],
    "tier_2_sources": [
      "LinkedIn Economic Graph products (JoR, AI Index) - trend/rank only, coverage bias flagged",
      "Glints salary/postings data - advertised not paid, junior-skewed, label method",
      "Michael Page/Robert Walters recruiter guides - placed-market upper band, senior-skewed",
      "e-Conomy SEA - published method, annual restatements (±5%)",
      "Kemnaker Satudata JKP series - formal-sector lower bound",
      "Fortinet/ISC2 (no Indonesia cut in ISC2)",
      "Aon/Mercer employer surveys",
      "GitHub Octoverse - account trends only"
    ],
    "banned_or_reduce": [
      "BPS: see verdicts above",
      "All government 'digital talent need' figures - planning projections with no public methodology (use only with honesty labels)",
      "Bootcamp self-reported alumni counts",
      "All conf-1 vendor blog growth claims",
      "Gig-economy registered-user counts (registered >= 100x active)"
    ]
  }
}
```

---

## 5. Remaining Uncertainties

1. **BPS KBLI-62 (6201–6209) direct series** — inside microdata/Sirusa table 101549 only; the single most valuable official cut for workforce size remains unextracted.
2. **Batches 2–4 MSIB per-batch counts** (implied sum ~70k) and **DTS 2024 full-year total** — exist in ministry datasets (data.komdigi.go.id, kampusmerdeka archives), not yet pulled.
3. **Bootcamp verified alumni totals** (Purwadhika, Impactbyte, Refactory, Skilvul, Dicoding) — none audited; class as permanently soft unless a survey is commissioned.
4. **BPJS-by-sector (KBLI) cut** — would give the only administrative count of formal IT employment; not published publicly.
5. **IT-role civil servants (PNS/PPPK IT)** — SIASN data exists internally; reconstructable only by parsing BKN CPNS lampiran (Pranata Komputer, Pengelola TIK etc.).
6. **Remote workers for foreign employers** — invisible in all official data (no question on employer location); E33G take-up unretrievable this round; Deel/Oyster gated.
7. **Fresh-grad vs senior placement rates for computing majors** — no national tracer; extrapolation band (70–75% 1-yr) is confidence 2.
8. **MSIB share that is tech-specific** — never published; partner-list classification would be an estimate.
9. **Indonesia-specific AI and cybersecurity wage premiums** — do not exist publicly; global figures (56%/28-40%) must not be localized.
10. **2026 endpoint of tech employment** — post-2025 GoTo/Tokopedia restructuring still moving; Revelio mid-2026 (~3,375) vs FY2025 audited (3,553) shows divergence resumes in 2026.
11. **Files 06 (salary deep-dive), 11 (supply), 14 (data rescue) were never produced** — salary here is built from 02/08/13 only; regional axis is vacancy-proxy only.
