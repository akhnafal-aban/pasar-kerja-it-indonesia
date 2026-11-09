# BPS Methodology Audit — Sakernas & Tech-Workforce Statistics Verdict

Research date: 2026-11-09. Scope: Sakernas methodology, KBLI 62 series, quality evidence for/against, alternatives, verdict per series.

---

## 1. Headline Verdict

| BPS series | Verdict | Reasoning |
|---|---|---|
| Sakernas headline TPT (Tingkat Pengangguran Terbuka), national/provincial, Feb+Aug trend | **USABLE-WITH-CAVEATS** | Big sample, calibrated weights, consistent methodology 2015–2024; matches external shocks (Aug 2020 spike 5.3→7.1%). Caveat: "worked ≥1 hour in reference week" definition means low-quality/underemployment invisible in TPT; falls during 2023–24 layoff waves for definitional, not conspiratorial, reasons. |
| Employed persons by 17-category lapangan usaha, incl. "J. Informasi dan Komunikasi" (= KBLI 58–63 aggregate) | **USABLE-WITH-CAVEATS** | Aug round (~300k HH) gives stable national estimates; directionally consistent with known tech cycle (Info-Comm wages fell 2023→2024 during tech winter). Small domain → high sampling error at province level; Feb round NOT usable for provinces at this detail. |
| Sakernas KBLI 5-digit code 62 (6201–6209) employment counts | **USABLE-WEAK / avoid as sole source** | KBLI coded by field supervisors from 3 open-ended write-in questions — documented interpretive subjectivity. KBLI 62 alone ≈ 0.4–0.6% of workforce → only ~1,200–1,800 respondents even in Aug round; province-level cuts unstable. Use only as national-level, multi-year trend with confidence bands; never as a point estimate for "number of software workers in Indonesia." |
| Informal/formal employment share | **USABLE-WITH-CAVEATS** (2021–2024), **SERIES BREAK 2025** | Definition followed BPS's own binary (formal = buruh/karyawan/pegawai + berusaha dibantu buruh tetap); Feb 2025 survey re-implemented 21st ICLS informal-employment standards → pre/post-2025 figures not fully comparable. Informal share ALSO misclassifies tech freelancers/remote contractors (counted as "pekerja bebas non-agrikultur" = informal even when high-earning). |
| Sakernas wages by sector (Upah Buruh, Info & Comm) | **USABLE-WITH-CAVEATS** | Wage series only covers buruh/karyawan/pegawai (excludes self-employed/freelancers — a large share of IT workforce); broad "Informasi dan Komunikasi" category, not KBLI 62-specific; small-domain error again. But 2023→2024 Info-Comm wage decline (Rp5.13→4.98M) is exactly what the tech winter predicted — a credibility point. |
| Nov 2025 round (new quarterly Sakernas) first release | **AVOID until proven** | First-of-kind round, seasonal confound (planting season), criticized by LPEM UI for inconsistency with growth/tax/formal-sector data; union transparency complaints. No back-series to validate. |
| Anything pre-Aug 2020 to Feb 2022 for labor-market levels | **AVOID for fine comparisons; usable for direction** | ICLS-19 items suspended; pandemic phone/DOPU pivot; extracompartmental World Bank HiFy panel showed materially worse conditions than headline Sakernas captured (24% not working late May 2020 vs official TPT ~7% later — definitional differences, but pandemic-era level shifts are contaminated). |
| Susenas-based poverty series (context only) | Not asked, but relevant to "BPS careless" prior: methodology criticisms documented (CBN basket unchanged since 1998) are about outdated-but-published conventions, NOT fabrication. |

**Bottom line on "BPS asal-asalan":** Partially supportable, fully supportable only in weak form. Evidence supports: pandemic-era collection disruption, coding subjectivity at 5-digit KBLI, small-domain sampling noise, method churn 2024–2025 (CAPI switch, ICLS 19/20/21, new Nov round), and a 2026 media-reported episode of BHP/QoS criticism. Evidence does NOT support: fabrication, politically manipulted numbers, or an institution that doesn't follow standardized statistical procedure. BPS publishes its methodology, gets ILO technical assistance, and its aggregates track external benchmarks (World Bank/IMF use them). The problem for the user's purposes is FITNESS FOR PURPOSE at tech-sector granularness, not wholesale unreliability.

---

## 2. Sakernas & KBLI Methodology (detailed)

### 2.1 Sample design
- **Two rounds/year since 2015** (Feb + Aug); quarterly 2011–2014; semiannual before; a new November round was added 2025 (first: 8–30 Nov 2025; sub-sample of the Aug 2025 SLS; SLS refreshed via SUPAS 2025). Quarterly Sakernas interrupted between 2015–2024. [SOURCE :: 2025 :: https://surabayakota.bps.go.id/id/news/2025/12/09/718/sakernas-november--sakernas-triwulanan-pertama-di-dekade-ini.html :: 5]
- **Feb round: ~75,000–76,890 households** (7,500 census blocks), estimation to provincial level. [SOURCE :: 2023 :: https://boyolalikab.bps.go.id/id/news/2023/01/26/488/... :: 5] [SOURCE :: 2024 :: Keadaan Angkatan Kerja Feb 2024 PDF via sedao.pelalawankab.go.id :: 5]
- **Aug round: ~300,000–307,880 households** (30,000 BS) — estimation to kabupaten/kota. [SOURCE :: 2023 :: BPS Keadaan Angkatan Kerja Agustus 2023 publication page :: 5] [SOURCE :: 2024 :: https://www.bps.go.id/id/publication/2024/12/09/6f1fd1036968c8a28e4cfe26/... :: 5]. BPS presentation: Feb 76,800 HH / Aug 302,860 HH. [SOURCE :: 2025 :: https://2025.iec-pyc.org/wp-content/uploads/2025/08/2.-Amalia-Adininggar-Wiyasanti-BPS.pdf :: 4]
- Design: two-stage (formerly three-stage) stratified; PPS systematic selection of census blocks; 10 households/block; frame from updated SP2010 (now SUPAS 2025). Stratification: 4 industry groups × urban/rural = 8 strata (based on household-head industry from census). Weighting pipeline documented: design weight → nonresponse adjustment → trimming → calibration to population projections (age-sex). [SOURCE :: 2016 PEDOMAN PENGAWAS Sakernas :: https://catalog.ihsn.org/catalog/8550/download/90197 :: 5] [SOURCE :: ILO Sakernas methodology review 2008–2012 :: https://www.ilo.org/.../wcms_241123.pdf :: 5]

### 2.2 Questionnaire & KBLI coding — THE KEY WEAKNESS
- KBLI (5-digit, KBLI 2020) and KBJI (4-digit) are **not asked as codes**: 3 open-ended write-in answers (what is done, output, business field) are coded afterward **by field supervisors (PML)**, whose(keys) interpretive workload the BPS itself is studying replacement of with ML (IndoBERT/SVM experiments at BPS seminars). No standardized write-in phrasing protocol; coding quality depends on the supervisor. [SOURCE :: 2024 :: https://doi.org/10.34123/semnasoffstat.v2024i1.2180 :: 4]
- KBLI 62 "Pemrograman, konsultasi komputer dan kegiatan komputer lainnya" (6201–6209) is inside category J "Informasi dan Komunikasi" (KBLI 58–63: publishing, motion picture, broadcasting, telecom, IT, information services). Household-side employment-by-industry is standard Sakernas output at 17-category level; 5-digit detail available via microdata (via BPS microdata access / Sakernas tables on sirus/data.bps), not in headline publications. [SOURCE :: 2024 :: BPS Keadaan Angkatan Kerja Agustus 2024 (17 categories listed) :: 5] implied 5-digit = [SOURCE :: 2024 semnasoffstat paper, confirms 5-digit KBLI in raw Sakernas :: 4]
- KBLI 95 = repair of computers and communication equipment (not in J; in "Other services"); IT freelancers usually land in J + self-employment status. [SOURCE :: 2020 KBLI structure, inferred/confidence 3]
- ICLS framework: ICLS-13 concepts since 2016; **ICLS-19 suspended Aug 2020–Feb 2022 due to COVID, reintroduced Feb 2023**; **Feb 2024 switched PAPI→CAPI (app: FASIH)** except parts of Papua; **Feb 2025 questionnaire re-implements ICLS 19, 20, and 21** (with dual ICLS-13 estimates for series continuity); informal-employment indicators (21st ICLS) integrated Feb 2025 with ILO technical assistance. [SOURCE :: 2024 :: Sakernas Feb 2024 pencacahan manual via Scribd :: 4] [SOURCE :: 2025 :: https://unstats.un.org/UNSDWebsite/statcom/session_56/documents/written/5-Indonesia-27Feb2025.pdf :: 5] [SOURCE :: 2025 :: https://mappikab.bps.go.id/id/news/2025/01/23/4/... :: 5]
- Gig/platform work: NO direct question identifying platform workers. Studies derive gig estimates from proxy variables (self-employed in services × uses internet × marketplace app) — authors explicitly state Sakernas "cannot perfectly estimate" gig workers due to question ambiguity (a driver may not call Gojek a "marketplace"). [SOURCE :: 2022/2023 :: https://doi.org/10.12695/jmt.2022.21.3.7 + The Conversation 2023 :: 5]
- Remote workers for foreign companies: no dedicated question; should be captured as employed (if 1+ hr) under self-employed/employee status, industry coded from description — coding to KBLI 62 depends on write-in clarity; cross-border employment invisible (no question on employer location); revenue/earnings not measured beyond employee wage bracket. [Inference, confidence 3]

### 2.3 Sampling-error arithmetic for KBLI 62 (my computation)
Feb round: ~75k households ≈ ~300k persons; IT sector ~0.8% of employed → roughly 2,000–2,500 employed persons in sample for category J; KBLI 62 only maybe 600–1,000. With design effects, national CV plausibly ~5–10% on category J, worse on 62; provincial-level KBLI-62 estimates are effectively anecdote. Aug round is 4× size. [Inference from disclosed design; confidence 3]

---

## 3. BPS Series Actual Numbers (KBLI 62 / Info-Comm)

| Indicator | Value | Date |
|---|---|---|
| Employment in J. Informasi & Komunikasi | 1.09M (up 1.3% yoy) | Feb 2022 [SOURCE :: 2022 :: https://databoks.katadata.co.id/pdb/statistik/0a8b0a2abf6574a/... :: 4] |
| Employment in J. Info & Comm | fell **-20,000** yoy | Aug 2023 [SOURCE :: 2023 :: https://databoks.katadata.co.id/ketenagakerjaan/statistik/012798e3f9c7251/... :: 4] |
| Employment in J. Info & Comm | **1.25M** (+1.6% yoy) | Feb 2025 (also J. Jasa Profesional +14.5% yoy to 2.53M — likely outstaffing/IT-services-to-firms, another place tech workers hide) [SOURCE :: 2025 :: https://databoks.katadata.co.id/ketenagakerjaan/statistik/681b0f4271d3e/... :: 4] |
| ICT sector employment (Sakernas 2018 basis, incl. telecom) | 894,000 | 2018 [SOURCE :: 2020 :: ADBI WP 1258, https://www.adb.org/sites/default/files/publication/700891/adbi-wp1258.pdf :: 4] |
| Avg wage, Info & Comm (employees) | **Rp5.13M** (highest of all sectors) | Aug 2023 [SOURCE :: 2023 :: https://www.bps.go.id/id/pressrelease/2023/11/06/2002/... :: 5] |
| Avg wage, Info & Comm | **Rp4.98M** (one of only 3 sectors DECLINING yoy) | Aug 2024 [SOURCE :: 2024 :: https://ekonomi.bisnis.com/read/20241105/12/1813519/... :: 5] |
| National avg wage | Rp3.18M → Rp3.27M → Rp3.33M | Aug 2023 → Aug 2024 → Nov 2025 [SOURCE :: BPS press releases :: 5] |
| TPT (unemployment) | Aug 2020 7.10% → Feb 2021 6.26% → Aug 2022 5.86% (+/-) → Aug 2023 5.32% → Aug 2024 ~4.91% → Feb 2025 ~4.76% → Nov 2025 **4.74%** | [SOURCE :: 2020–2026 :: BPS BRS + World Bank IEP Dec 2021 (numbers for Aug 2019 5.3→Aug 2020 7.1, Feb 2021) + Kompas 2026 :: 5] |
| Total employed | 139.85M (Aug 2023) → 144.64M (Aug 2024) → **147.91M (Nov 2025)**; informal share **57.70%** | [SOURCE :: 2023–2026 :: BPS/Kompas/CNBC :: 5] |
| Formal employment | 57.18M (40.89%) Aug 2023 → 62.57M (42.30%) Nov 2025 | [SOURCE :: BPS BRS :: 5] |

Sanity check vs tech layoffs 2022–2024: Kemnaker recorded ~237k workers laid off Jan–Oct 2023 nationally (80k+ in 2025), yet TPT fell and Info-Comm headcount in Aug 2023 fell only 20k. Consistent if laid-off techies re-entered as freelancers (→ informal "pekerja bebas"), took other work (1-hr rule), or dropped out. No contradiction implies fabrication; **but BPS's categories make it impossible to verify tech-specific dynamics below the J-category level**. [SOURCE :: 2024 :: https://www.cnbcindonesia.com/research/20240731111002-128-559132/... + LPEM brief Aug 2024 :: 4]

---

## 4. Quality Evidence — AGAINST BPS reliability

1. **Pandemic break**: ICLS-19 concepts suspended Aug 2020–Feb 2022 (official BPS statement); phone interviewing as fallback ("if face-to-face cannot be done, mitigation by telephone"); households refused interviews during March 2020. [SOURCE :: 2024 :: Sakernas Feb 2024 manual quote :: 5] [SOURCE :: 2020 :: https://positium.com/blog/data-collection-under-lockdown-value-of-big-data :: 4] World Bank HiFy phone panel found 24% of recent workers not working in late May 2020 — a magnitude the subsequent official TPT never approached (partly definitional; SMERU/UNICEF report explicitly lists two explanations incl. measurement differences). [SOURCE :: 2020 :: WB IEP Jul 2020 (doi:10.1596/34123) + SMERU/UNICEF brief :: 4]
2. **ILO global COVID survey**: only 11.8% of Asia-Pacific countries introduced extra quality checks for 2020 phone-mode switch bias (Indonesia not evidenced among them). [SOURCE :: 2022 :: https://www.ilo.org/media/381221/download :: 3]
3. **Nov 2025 first quarterly release criticized**: (a) LPEM UI (Teguh Dartanto): results "less synchronized with economic growth, tax revenue, employment data," seasonal planting-season confound; (b) Sarbumusi: TPAK rise likely part-time driven; demands per-sector breakdown transparency; (c) KSPN: "BPS doesn't present layoff figures... I doubt the TPT decline." [SOURCE :: 2026-02-05 :: https://www.kompas.id/artikel/bps-jumlah-penduduk-bekerja-meningkat-upah-buruh-cenderung-stagnan :: 5] [SOURCE :: 2026-02-05 :: https://ekonomi.bisnis.com/read/20260205/12/1950520/... :: 5]
4. **KBLI/KBJI coding subjectivity** (open text → supervisor interpretation; no write-in standard; BPS research confirms codes determined by PML interpretation). [SOURCE :: 2024 :: semnasoffstat DOI above :: 4]
5. **Small-domain instability**: tech employment cuts jump around (e.g., South Sulawesi Info-Comm: 28,408 Feb 2023 → 25,450 Aug 2023 → 36,806 Feb 2024 → 31,750 Aug 2024 — a ±20% swing unmatched by any real industry cycle). [SOURCE :: 2024 :: Kemnaker/Sakernas provincial datasheet saoraja.sulselprov.go.id :: 4]
6. **One-hour employment rule** + headline-level aggregation systematically understates distress during layoff waves (TPT fell through the 2023–24 tech winter). Academic/op-ed critiques (INDEF, individual columnists). [SOURCE :: 2025–2026 :: krisna.or.id; suara.com column; Kompas :: 4]
7. **Adjacent credibility issue — poverty statistics** (not labor): materially criticized for a 2½-decade-unchanged CBN basket (Prakarsa 2025; CELIOS; Unmul academics; even BPS itself publicly admitted components "not updated since 1998" with revision plan pending). This justifies skepticism about inertia/institutional slowness, but note it's an OUTDATED-CONVENTIONS critique, not fabrication, and it's Susenas, not Sakernas. [SOURCE :: 2025 :: https://www.tempo.co.id/ekonomi/the-prakarsa-...; kalimantan.bisnis.com 2025; kompas.com 2025-07-28; celios.co.id paper :: 4]

**Political manipulation allegations: searched; no credible documented case found connecting pressure to published Sakernas/employment figures.** The closest is the Nov 2025 timing critique (union suspicion about November being a budget-burn month — speculation, flagged as such in the press). "Asal-asalan" as fabrication is NOT supported. [Confidence 3 on absence-of-evidence finding]

---

## 5. Quality Evidence — FOR BPS reliability (validations)

1. **Fully published methodology**: frame, stages, strata, weights (manual lingkungan documents), sample sizes, press releases with cross-checks; UN/ILO statements; BPS went through IFPS/QAF (Statcap CERDAS reform, NQAF). [SOURCE :: multiple :: UN World Data Forum presentation; PEDOMAN docs; BPS publications :: 4]
2. **ICLS alignment** 13→19→20→21 with explicit continuity management (double release on ICLS-13 and ICLS-19+ bases), via ILO technical assistance (UNSC statement). [SOURCE :: 2025-02-27 :: unstats statement :: 5]
3. **External aggregate validation**: 
   - Aug 2020 TPT spike (5.30→7.07%) matched the observed shock, timing, and geography (Bali/Jakarta worst — province-level plot review). [SOURCE :: 2025 :: https://www.krisna.or.id/en/post/indahg/ :: 4]
   - Info-Comm wages are highest nationally (Rp5.13M Aug 2023) — cross-check plausible with tech-sector pay; and they DECLINED Aug 2024 (one of three falling sectors) matching the documented 2022–24 tech winter/layoffs. [SOURCE :: 2023/2024 :: BPS press releases/data :: 5]
   - Informal share (57%+) matches World Bank's structural findings on work quality patterns.
4. **ILO modeled/analytical use**: ILO Jakarta publications estimated regional IT employment growth using official series; ADB used Sakernas 2018 for ICT employment (894k); World Bank IEPs use Sakernas hooks extensively. These institutions treat it as usable with noted caveats. [SOURCE :: 2020/2022 :: ADBI WP 1258; ILO sectoral brief :: 4]
5. **CAPI adoption (2024) with near-real-time dashboard; BYOD; audit trail; monthly progress audits** — process modernization that usually reduces transcription/coverage error (early study of one kabupaten found 100% sample achievement and on-schedule completion). [SOURCE :: 2024/2025 :: UNSOED repository (Purbalingga study); Sakernas manuals :: 3–4]
6. **No documented fabrication or political-tampering case for employment series** (searches across Kontan/Kompas/Bisnis/CNBC/Nikkei-class coverage, WB/IMF/ILO files). Headline spike at the start of the pandemic looked exactly like what a truthful survey would produce. Across COVID-era 2020–2021, World Bank IEP narrative never flags BPS labor data as unreliable — only as definitional-light. [Confidence 3–4]

**Weighing the two sides**: FOR wins on aggregate series (TPT, main sector groups, wage orderings); AGAINST wins on granular/sub-sector series, pandemic-era levels, anything from Feb rounds used at provincial detail, the Nov 2025 round, and on formal/informal comparability across 2025 boundary.

---

## 6. Alternatives Independent of BPS

1. **BPJS Ketenagakerjaan**: administrative enrollment series — active participants 48.65M (2025), 45.22M (2024), 41.56M (2023); 875,641 employers (2025); no public sectoral/KBLI cut downloaded; can cross-check formal headcount only. Also DJP-BPJS tax-data integration exists (PMK 228/2017, Inpres 2/2021) but no KBLI-level employment publication downloadable. [SOURCE :: 2025 :: bpjsketenagakerjaan.go.id Integrated Report 2025 (IR_2025.pdf); pajak.go.id press release Aug 2025 :: 4–5]
2. **Kemnaker satudata**: monthly PHK reports by province/sector (e.g., 237,080 Jan–Oct 2023), lowongan (vakancies) data — administrative, non-BPS sources for layoff tracking. [SOURCE :: 2023 :: satudata.kemnaker.go.id Analisis Pasar Kerja 2023 PDF :: 4]
3. **GitHub Octoverse / Innovation Graph**: Indonesia developer accounts 0.9M (2020) → 3.5M+ (2024) → **4.37M** (2025) → **6.34M / #7 globally** (Sep 2026). Accounts ≠ professional employment; massively includes hobbyists/students/bot-assisted, but the cleanest trend signal for the software-creation talent pool and growth (~33% CAGR). [SOURCE :: 2025 :: https://github.blog/news-insights/octoverse/... ; https://octoverse.github.com/; dataexplained.com country table :: 5]
4. **SlashData Developer Nation**: global ~48.4M developers (Q3 2025), survey-based (10k+/wave, GitHub/SO/employment calibration); country cuts purchasable — independent non-BPS anchor. [SOURCE :: 2025 :: https://www.slashdata.co/research/developer-population :: 5]
5. **ILO/ILOSTAT modeled estimates + ICT sector briefs**: ILO Asia-Pacific IT-services (ISIC 62+63) employment ~0.50% of total employment regionally; ILO platform-work brief flags Indonesia among 15 largest online-platform-work countries (~1.5% of workers). International-model numbers, partially BPS-fed — use carefully, flag as hybrid. [SOURCE :: 2022 :: https://www.ilo.org/media/7591/download; Kompas 2024 quoting ILO :: 4]
6. **Komdigi/IMDI digital-talent demand studies**: need of 450–500k/yr (12M by 2030; universities supply ~9M) — demand-side model from Kominfo's own survey of ~150 firms (not a workforce census). [SOURCE :: 2024 :: cnnindonesia, cnbcindonesia, bpsdm.komdigi.go.id :: 3]
7. **LinkedIn/ Indeed/ Glints/ Kalibrr market data**: 2024 Glints SEA talent report (70k vacancies analyzed) documented offshore hiring — directional HR-market data, non-BPS; no single public "software engineers in Indonesia" panel known. [SOURCE :: 2024 :: Kompas 2024 quoting Glints :: 3]

**Recommended cross-check stack for "how many software workers in Indonesia":** (i) BPS Aug Sakernas category J (~1.25M, 2025) as the formal-statistical anchor ~0.85% of employment; (ii) ADB/ADBI-style estimates (~0.9M in ICT, 2018) as the employed-in-ICT-only core; (iii) GitHub (~4–6M accounts) and SlashData as "community/potential" upper bounds; (iv) ILO platform-work brief noting 1.5% share of workforce engaged in online work; → triangulated true "IT professionals earning their living from IT" plausibly in the 900k–1.5M range, of whom a substantial share are freelancers/contractors misclassified by formal/informal and industry coding. All of these have wide error bars and non-BPS numbers are not strictly comparable to BPS ones.

---

## 7. JSON

```json
{
  "bps_audit_verdict": {
    "tpt_series": "USABLE_WITH_CAVEATS",
    "lapangan_usaha_17cat_j_infokom": "USABLE_WITH_CAVEATS_national_only",
    "kbli62_5digit": "USABLE_WEAK_national_trend_only",
    "formal_informal_share": "USABLE_WITH_CAVEATS_series_break_2025",
    "wages_infokom": "USABLE_WITH_CAVEATS_employees_only",
    "nov2025_round": "AVOID",
    "pandemic_levels_2020_2021": "AVOID_for_levels_usable_for_direction"
  },
  "sample_sizes": {"feb_households": "75000-76900", "aug_households": "300000-307880", "rounds": ["Feb", "Aug", "Nov(new 2025)"]},
  "infokom_employment": {"feb2022": "1.09M", "aug2023_delta": "-20k", "feb2025": "1.25M", "ict_2018": "894k"},
  "wages_infokom": {"aug2023": "Rp5.13M", "aug2024": "Rp4.98M", "trend": "declined_during_tech_winter"},
  "corruption_or_tampering_evidence": "not_found",
  "careless_claim_assessment": "partially_supported_operations_disruption_and_small_domain_noise_yes_fabrication_no",
  "alternatives": ["BPJS_Ketenagakerjaan_48.65M_active_no_sector_cut", "Kemnaker_PHK_monthly", "GitHub_Octoverse_6.34M_ID_accounts_2026", "SlashData_global_model", "ILO_platform_work_1.5pct", "Komdigi_demand_side"]
}
```

---

## 8. Data Gaps

- **KBLI 62 (6201–6209) direct published series (2021–2025) not found as a ready online table** — exists inside microdata and possibly longitudinal statistical tables (BPS's "Jenis Lapangan Usaha" 5-digit series, Sirusa indicator 101549); needs BPS microdata portal request. Recommend direct access request or tabelsirusa download for exact 62-level series.
- No public published BPJS-by-KBLI sector series (only aggregate + wage-recipient vs non-wage-recipient split); absence confirmed through 2025 integrated report.
- No public DJP series of IT-sector employees/taxpayers; would need DATIN/data-request route via DJP, likely not extractable for non-official use.
- Exact CVs/standard errors for Sakernas small domains (BLS-style) not published in BRS documents — treatment of uncertainty is not part of the public bread-and-butter release — an objective QoS shortcoming vs international best practice (INCERTAINTY reporting).
- No public survey of remote workers for foreign employers (not a Sakernas 2025 module per available questionnaire documentation) — leave as known unknown.
- Evidence for or against deliberate manipulation remains an absence-of-proof finding — a formal academic or journalistic investigation specifically of BPS employment figures hasn't been found in searches to date; this remains an open item if the user wants deeper forensic digging.
