# Indonesia IT Workforce — Salary Deep-Dive (Levels, Total Comp, Trends, Company-Type Variation)

Compiled 2026-11-09. All figures IDR unless noted. "jt" = juta (million). "M" in NodeFlair tables = IDR millions/month.
Method rules: every figure tagged [SOURCE :: YEAR :: METHODOLOGY :: URL :: CONFIDENCE 1-5].

## Headline Numbers

| Metric | Value | Tag |
|---|---|---|
| Advertised SE median (payslip-verified, IDN, mid-level) | Rp 9 jt/mo | [NodeFlair Asia Tech Salary Report 2025 :: 2025 :: payslip-verified job listings, percentiles, ⚠<200 data points per many IDN cells :: nodeflair.com/salaries/report-2025.pdf :: 4] |
| Placements-average full-stack dev (Jakarta MNC mix) | Rp 30 jt/mo avg | [Michael Page Salary Guide 2025 :: 2025 :: real placements (client database + consultants) :: jakartasatu.com/wp-content/uploads/2025/03/Indonesia-Salary-Guide-2025.pdf :: 4] |
| Self-reported total comp, SE Jakarta (incl. stock+bonus) | Rp 21.1 jt/mo median (Rp 252.9 jt/yr), N=244 | [Levels.fyi :: 2026 (Nov) :: self-reported w/ outlier removal, tech-co skewed :: levels.fyi/t/software-engineer/locations/jakarta-idn :: 4] |
| Software Developer annual band (recruiter view, basic) | Rp 350m–700m/yr (2023), Rp 300m–650m (2022), Rp 350m–700m (2024) | [Robert Walters Salary Survey :: 2023/2024 :: placement-based calculator bands :: scribd.com/document/737466679 :: 3] |
| Remote-for-foreign expected salary | avg $50,146/yr; senior avg $69,110/yr | [Arc.dev :: 2026 :: self-reported *expected* salaries of vetted remote devs :: arc.dev/salaries/software-engineers-in-indonesia :: 3] |
| Broadest remote-for-foreign dataset | avg $129,472/yr, range $20k–$338k, N=142 | [RubyonRemote :: 2024 :: self-reported, includes US-market-anchored workers :: rubyonremote.com/developer-salaries-in-indonesia :: 2] |
| Increments 2025 & 2026 | 5–8%/yr typical; job movers get 15–25% | [Michael Page 2025 & 2026 guides :: placements :: michaelpage.co.id/salary-guide :: 4] |
| ESOP prevalence | >86% of SEA startups (incl. Indonesia) offer ESOP | [Glints + Monk's Hill Ventures SEA Startup Talent Report 2023 :: 2023 :: 10,000+ proprietary data pts + survey of 500+ talent :: katadata.co.id/digital/startup/6438e1eca04b8/... :: 4] |

Key reading: the three "median software engineer" numbers everyone quotes (Rp 6–9 jt advertised, Rp 21 jt self-reported tech-co, Rp 20–30 jt recruiter placements) are three different populations. Advertised listings over-weight SME hiring; Levels.fyi over-weights unicorns; recruiter guides over-weight MNC placements that go through agencies.

## Salary Guide Tables (role × level, per guide)

### Michael Page Indonesia Salary Guide 2025 — Technology (avg gross monthly, IDR '000,000)
[Michael Page :: 2025 :: placements-based averages, no junior/senior split — seniority implied by title :: https://jakartasatu.com/wp-content/uploads/2025/03/Indonesia-Salary-Guide-2025.pdf :: 4]

Development:
| Role | Avg gross/mo |
|---|---|
| Front-end Developer | 20 |
| QA Engineer | 23 |
| Back-end Developer | 25 |
| Mobile Developer | 25 |
| Full-stack Developer | 30 |
| Tech Lead | 40 |
| Solution Architect | 55 |
| Engineering Manager | 67 |
| Head of Engineering | 81 |
| VP Engineering | 108 |

Analytics/Data:
| Role | Avg/mo |
|---|---|
| BI Analyst | 27 |
| Lead Data Analyst | 30 |
| Business Analytics Manager | 39 |
| Lead Data Engineer | 42 |
| Lead Data Scientist | 46 |
| Data Science Manager | 72 |
| Head of Data | 80 |
| VP Data | 132 |

Cloud & Infrastructure:
| Role | Avg/mo |
|---|---|
| Senior Network Engineer | 25 |
| Senior DevOps Engineer | 35 |
| IT Infrastructure Manager | 39 |
| Cloud Architect | 50 |
| DevOps Manager | 50 |
| Head of Infrastructure | 54 |

Cybersecurity:
| Role | Avg/mo |
|---|---|
| Senior Security Engineer | 35 |
| Security Manager | 55 |
| Head of IT Security | 80 |
| VP Security | 115 |

IT Enterprise:
| Role | Avg/mo |
|---|---|
| ERP Functional SME | 37 |
| IT GRC Manager | 40 |
| IT Manager | 50 |
| Head of IT | 85 |
| IT Director | 120 |

Product & Project:
| Role | Avg/mo |
|---|---|
| Product Manager | 25 |
| Senior Product Manager | 35 |
| Senior Project Manager | 35 |
| UX/UI Designer | 43 |
| Head of Programme Management | 50 |
| Head of Product | 60 |
| VP Product | 90 |

Executive: CIO / CTO / CISO / CDO = 150 each (avg/mo). [same source, confidence 4]

Michael Page 2026 guide (40pp, Scribd) exists but tables are image-only — could not extract this session; narrative: "salaries holding firm, increments 5–8%, higher for acute skills shortages" [michaelpage.co.id/salary-guide :: 2026 :: methodology stated as placements+interviews+proprietary IT system :: 3].

### NodeFlair Asia Tech Salary Report 2025 — Indonesia (base salary percentiles, IDR millions/month, payslip-verified)
[NodeFlair :: 2025 :: "data reliably verified with employee payslips", advertised/listing data across 130,000+ Asia-wide data points; Indonesia cells often flagged ⚠<200 pts :: nodeflair.com/salaries/report-2025.pdf (mirror: static1.squarespace.com/...NodeFlair+Salary+Report+2025.pdf) :: 4]

Software Engineer (2025 vs 2024, YoY on 50th):
| Level | 10th | 30th | 50th | 70th | 90th | YoY |
|---|---|---|---|---|---|---|
| Junior ⚠ | 4.5M | 6.0M | **7.5M** | 9.5M | 12.0M | −5.3% |
| Mid ⚠ | 5.0M | 7.0M | **9.0M** | 11.0M | 15.0M | −6.8% |
| Senior ⚠ | 5.5M | 8.3M | **12.5M** | 17.5M | 24.0M | −13.0% |
| Lead ⚠ | 7.0M | 10.0M | **12.5M** | 17.5M | 25.0M | −23.6% |
Overall Indonesia SE 2025: **−7.7%** vs 2024.

Mobile Engineer (overall +3.2%):
| Level | 10th | 30th | 50th | 70th | 90th | YoY |
|---|---|---|---|---|---|---|
| Junior | 5.0 | 7.0 | **7.8** | 10.0 | 11.5 | +4.4% |
| Mid | 5.8 | 7.5 | **9.5** | 11.0 | 14.0 | +4.9% |
| Senior ⚠ | 7.0 | 8.5 | **11.0** | 14.0 | 22.5 | −11.2% |

Data Scientist (overall −1.0%):
| Level | 10th | 30th | 50th | 70th | 90th | YoY |
|---|---|---|---|---|---|---|
| Junior | 6.3 | 7.5 | **8.5** | 11.0 | 14.0 | +6.8% |
| Mid ⚠ | 7.0 | 8.5 | **11.3** | 12.5 | 21.5 | −1.4% |
| Senior ⚠ | 9.0 | 11.3 | **12.5** | 17.0 | 25.0 | −12.0% |

Quality Assurance (overall −5.8%):
| Level | 10th | 30th | 50th | 70th | 90th | YoY |
|---|---|---|---|---|---|---|
| Junior ⚠ | 4.5 | 5.8 | **6.8** | 8.3 | 10.0 | −7.4% |
| Mid ⚠ | 5.5 | 6.5 | **8.0** | 8.8 | 11.0 | −2.0% |
| Senior ⚠ | 7.3 | 8.5 | **10.0** | 12.0 | 14.5 | −21.3% |

DevOps Engineer (overall −14.5% — steepest fall of any IDN role):
| Level | 10th | 30th | 50th | 70th | 90th | YoY |
|---|---|---|---|---|---|---|
| Junior ⚠ | 6.0 | 7.5 | **8.5** | 9.5 | 12.0 | −8.9% |
| Mid ⚠ | 7.3 | 8.0 | **9.0** | 11.5 | 15.0 | −17.2% |
| Senior ⚠ | 10.0 | 14.0 | **15.0** | 17.5 | 20.0 | −29.0% |

Note: NodeFlair 2025 report contains no Data Analyst, Systems Engineer, or Scrum/PMO tables for Indonesia (those TOC pages exist only for Singapore). Live site (Aug 2026 update, reported by Binar): SE median Rp 9 jt, base range Rp 4.25–20 jt/mo [Binar blog citing NodeFlair :: 2026 :: advertised :: binar.co.id/blog/gaji-developer-di-indonesia :: 3].

### Robert Walters "Tech & Transformation" Indonesia (basic salary, per annum)
[RW Salary Calculator results :: 2023 vs 2024 :: recruiter placement-range estimates :: scribd.com/document/737466679/Robert-Walters-Salary-Survey :: 3]
[RW Indonesia :: 2022 vs 2023 :: same methodology :: scribd doc 629607521 / coursehero.com/file/221887619 :: 3]

| Role | 2022 | 2023 | 2024 |
|---|---|---|---|
| Software Developer (General, perm) | 300m–650m | 350m–700m | 350m–700m |
| Data Scientist | — | 300m–800m | 400m–850m |
| Business Analyst | — | 350m–550m | 350m–550m |
| Business Intelligence Manager | — | 600m–850m | 650m–950m |
| IT Manager | — | 450m–800m | 550m–850m |
| Engineering Manager | — | 520m–1b | 600m–1.1b |
| Infrastructure Manager | — | 600m–1b | 600m–1b |
| Project Manager | — | 500m–1b | 550m–1b |
| Program Manager | — | 550m–1.2b | 550m–1.2b |
| Lead Architect | — | 750m–1.3b | 750m–1.3b |
| Project Director | — | 700m–1.4b | 700m–1.5b |
| Head of IT | — | 950m–2.2b | 950m–2.2b |
| Head of Engineering | — | 950m–2.2b | 950m–2.2b |
| Head of Data | — | 975m–2.3b | 975m–2.3b |
| Head of Infrastructure | — | 650m–1.3b | 550m–1.2b |
| Head of Cyber Security | — | 845m–1.45b | 845m–1.3b |
| CTO/CIO | 1.3b–2.6b (2023) | 1.8b–2.6b | 1.8b–3b |
| Head of Digital | — | 975m–2b | 1.1b–2.3b |
| Head of Product (Digital) | — | 1.3b–1.95b | 1.3b–2.145b |
| Product Manager (Digital) | — | 500m–650m | 500m–750m |
| UX/UI Manager (Digital) | — | 400m–500m | 400m–550m |
| Strategy Manager | — | 400m–850m | 400m–900m |
| Growth Manager | — | 450m–650m | 350m–650m |

(Already-gathered RW 2025/2026 press figures — Rp 440–770M software dev, Rp 450–850M data scientist — sit inside the 2024 bands, i.e., flat.) RW 2024 insight page: 72% of businesses giving pay rises in 2024; 76% of professionals looking for a new job; average tenure 1.7 years; 70% expecting a pay rise; most sought-after: (1) Digital Transformation Leaders, (2) Cybersecurity, (3) IT General Management. [same :: 3]

### Kelly Services (PersolKelly) Salary Guide 2025 — Indonesia Hi-Tech/IT (min–max IDR/mo by experience band)
[Kelly Services :: 2025 :: agency placement data (recruiting agency marketing artifact) :: scribd.com/document/973829703/04-Kelly-Services-2025 :: 3]

| Role | Exp (yrs) | Min–Max/mo |
|---|---|---|
| Android Developer | 1–4 | 10–15 jt |
| Backend Developer | 3–8 | 15–20 jt |
| Backend Engineer | 5–7 | 10–14 jt |
| Cybersecurity Analyst | 5–7 | 10–12 jt |
| Fullstack Software Developer (E) | 2–4 | 7–8 jt |
| Fullstack Software Developer (SE) | 3–5 | 8–12 jt |
| Senior Mobile Developer | 2–4 | 15–20 jt |
| Software Engineer | 1–4 | 10–15 jt |
| Systems/Software Engineer | 1–4 | 22–33 jt |
| Tech Lead | 1–4 | 40–60 jt |
| UI/UX Developer | 3–8 | 15–20 jt |
| QA Engineer (IT-PST) | 1–2 | 6–7 jt |
| Frontend Engineer | 5–7 | 10–14 jt |
| Frontend Developer | 1–4 | (listed 40–60 jt — treat as data-entry artifact) |
| ERP Consultant | 1–4 | 8–15 jt |
| ERP Consultant & SW Engineer | 1–4 | 7–15 jt |
| SAP Consultant (Japan-speaking) | 5+ | 62–79 jt |
| SAP Project Manager | 5+ | 62–79 jt |
| Information Security Specialist | 5+ | 12–15 jt |
| IT Manager | 5+ | 17–25 jt |
| IT PM Manager | 5+ | 20–35 jt |
| IT Support Staff | 1–4 | 7–8 jt |
| IT Staff | 1–4 | 5–8 jt |
| IT Infrastructure Supervisor | 2–4 | 10–12 jt |
| Network Engineer | 1–4 | 7–15 jt |
| Solution Architect | 5 | 30–50 jt |
| Project Manager (Web App) | 1–4 | 20–30 jt |
| PM (Infrastructure Eng) | 1–4 | 20–30 jt |

Kelly 2024 (PersolKelly) Indonesia guide also exists (50pp, scribd 715873110) — not extracted this session. Hays Asia 2024/2025 guides cover Indonesia narratively but not in extracted per-role tables.

### Levels.fyi — Jakarta Software Engineer (total comp = base+stock+bonus)
[Levels.fyi :: updated Nov 2026 :: self-reported with outlier removal :: levels.fyi/t/software-engineer/locations/jakarta-idn :: 4]
- Median: **Rp 21.1 jt/mo** (Rp 252.9 jt/yr), N=244
- Percentiles (USD/yr): 25th $9.5k; median $14.3k; 75th $22.3k; 90th $32.1k
- Top-paying companies (median TC/yr): Grab Rp 672.6 jt; ByteDance Rp 399.0 jt; Gojek Tech Rp 346.2 jt
- Location spread: Tangerang Rp 247 jt/yr; Jakarta Rp 207 jt/yr; Bandung Rp 155 jt/yr
- Recent datapoints: Kredivo SWE 2–4 yrs ≈ $9.3k/yr; Shopee SWE (ML/AI) 3 yrs ≈ $15k/yr (Oct 2026)

### orang.engineer — verified-ish Indonesian comp table (self-reported, N=10 visible rows)
[orang.engineer :: 2026 :: community self-reported comp table ("pusat data kompensasi riil"), small N :: orang.engineer :: 3]
| Company | Role/Level | Base | Est. total/yr | Bonus |
|---|---|---|---|---|
| US stealth AI startup (remote, from Yogya) | Senior Fullstack AI Engineer, 7y | Rp 75 jt/mo | Rp 1.2 B | Rp 150 jt |
| Singapore fintech (remote, from Surabaya) | Senior Fullstack, 6y | Rp 55 jt/mo | Rp 820 jt | Rp 110 jt |
| BCA Digital (blu) — bank | Lead DevOps/SRE, 8.5y | Rp 48 jt/mo | Rp 768 jt | Rp 192 jt |
| GoTo (Gojek/Tokopedia) — unicorn | Senior Backend, 6y | Rp 36 jt/mo | Rp 549 jt | Rp 72 jt |
| Traveloka — unicorn | Senior Frontend, 5.5y | Rp 32 jt/mo | Rp 468 jt | Rp 64 jt |
| Shopee ID — unicorn | Senior QA Automation, 5y | Rp 28 jt/mo | Rp 420 jt | Rp 84 jt |
| Pinhome — startup | Mid Data Engineer, 4y | Rp 23 jt/mo | Rp 330 jt | Rp 46 jt |
| eFishery — startup | Mid Backend, 3.5y | Rp 21 jt/mo | Rp 304 jt | Rp 42 jt |
| DANA — fintech unicorn | Mid Frontend, 3y | Rp 19.5 jt/mo | Rp 273 jt | Rp 39 jt |
| Blibli — e-commerce | Junior SWE, 1.2y | Rp 12.5 jt/mo | Rp 175 jt | Rp 25 jt |

Bonus pattern in this table ≈ 20–33% of base / 2–4 months equivalent.
JobStreet typical monthly salaries (advertised, Aug 2026): Developer Rp 7 jt; SW Engineer Rp 8.5 jt; Backend 7.16 jt; FE 6.8 jt; Full-stack 6.75 jt; Java 9.5 jt; Android 10 jt [JobStreet via Binar :: 2026 :: advertised listings :: binar.co.id/blog/gaji-developer-di-indonesia :: 3].

## Total Comp & Equity

Cash-gross vs total comp gap, quantifiable pieces:
- **THR**: statutory 1-month religious-holiday bonus for employees ≥1 yr (UU 13/2003 as amended by UU 11/2020 pervasive; recruiters/reporters treat it as a hard requirement, not a perk). ⇒ legal minimum extra = 1 month (8.3% of base). [Commonly reported; roaming hiring guide states grace: "full month's salary, hard statutory requirement" :: roamjobs.com/guides/hiring/cost-to-hire-remote-developer-indonesia :: 4]
- **Annual performance bonus**: recruiter-guide and case data converge on 1–3 months typical in tech (orang.engineer table: 2–4 months); banking "tantiem" claimed up to 4–8 months in strong years [single low-quality marketing source — masoemuniversity.ac.id article :: 2026 :: unsupported :: confidence 1].
- **Statutory employer add-ons**: BPJS Kesehatan + BPJS TK ≈ ~10.48% employer contribution on top of gross [RoamJobs hiring guide :: 2026 :: contractor-side arithmetic :: confidence 3].
- **Private health insurance**: standard in banks/MNC/big tech; less common at SMEs; typical in-house benefits surveys (e.g., Mercer Indonesia Benefits Survey) exist but weren't extracted (gap).
- **Equity/ESOP**: 86%+ of SEA startups offer ESOP [Glints+MHV SEA Startup Talent Report 2023 :: 10,000+ proprietary data points + 500-worker survey :: katadata.co.id/digital/startup/6438e1eca04b8 :: 4]. At listed tech cos (GoTo, Bukalapak) RSUs are the norm — that's why Levels.fyi total comp (Rp 252.9 jt/yr median) is ~18% above its base-only equivalents. No survey found giving "% of *tech workers overall* receiving RSU" (gap).
- **Raises**: 5–8%/yr increments standard, both MP guides; job-movers get 15–25% [MP 2026 :: placements :: 4]. 40% of Indonesian professionals expected >10% raise in 2025; 49% of employers report their best people getting counter-offered by competitors [Robert Walters Salary Survey 2025 via SWA :: 2025 :: survey of professionals + employers :: swa.co.id/read/455345 :: 3].
- **Rule of thumb** implied: total comp ≈ base × (1 + ~1.3–1.4) at big tech; base × ~1.12 minimum (THR + MPJS) everywhere else. Levels.fyi's own definition: base + yearly stock + bonus.

## Company-Type Variation

(a) **Tech startups / unicorns** (levels.fyi + orang.engineer):
- Grab median TC Rp 672.6 jt/yr; ByteDance Rp 399 jt; Gojek Rp 346 jt [Levels.fyi :: N per company small :: 3]
- GoTo senior backend base Rp 36 jt/mo; Traveloka senior FE 32 jt; Shopee senior QA 28 jt [orang.engineer :: 3]
(b) **Banks / digital banks**:
- BCA Digital (blu) Lead DevOps/SRE base Rp 48 jt/mo — the highest local (non-remote) base in the orang.engineer table, +33% over GoTo senior backend case [orang.engineer :: 3]
- Bank specialist IT roles quoted (marketing-quality source): Enterprise Architect 35–65 jt/mo, DevSecOps 25–50 jt, Cybersecurity/Pen-tester 28–55 jt, Core-banking dev 22–45 jt [masoemuniversity.ac.id :: 2026 :: unsupported marketing article :: 1] — directionally consistent with RW's Head of Cyber Security 845m–1.3b/yr (~70–108 jt/mo) [RW 2024 :: 3] and MP VP Security 115 jt/mo [MP 2025 :: 4].
- Press consensus: post-tech-winter, bank digital budgets pay a premium over startups for scarce senior infra/security talent; banks also package superior benefits (tantiem, near-0% loans, family health coverage). No rigorous %-difference study found (gap).
(c) **Telcos**: no per-role salary table found for Telkomsel/Telkom Indico/XL etc. this session (gap). Only indirect marker: Systems Engineer band 7–10 jt (Kelly) is dominated by telco/energy outsourcing placements.
(d) **IT outsourcing / PKWT**: no published rate card for developer contractors per hour; BINAR (3,000-talent outsourcing bench) markets cost-vs-hiring savings but does not publish monthly rates; Kelly's lower bands (IT support staff 7–8 jt; junior dev 6–10 jt) reflect where outsourcers pay. PKWT/outsourcing systematically pays below product-company peers — no hard % figure found (gap).
(e) **MNC / regional HQ**: MP 2025 tables (the higher-paid placements, e.g., full-stack 30 jt avg, UX/UI 43 jt "manager-level", ERP SME 37 jt) are dominated by global-in-house-enterprises and MNCs; MP explicitly notes "professionals with multinational exposure command a premium".

## Trend 2021 → 2026 (software engineer, Indonesia)

Series (where data exists for same metric):
| Year | Data point | Tag |
|---|---|---|
| 2022 | RW Software Developer: Rp 300–650m/yr | [RW :: 2023 report :: 3] |
| 2022 | Glints Salary Survey: tech = highest wage-growth sector of 2023 | [Glints Tren HR & Survei Gaji 2023 via detik finance :: survey of Glints platform :: finance.detik.com/berita-ekonomi-bisnis/d-6994346 :: 3] |
| 2022–23 | "Tech winter: supply of talent many, demand few — market stagnant; in 2023 recovery, movers got up to 20% raises" — Glints talent consultant | [Glints Data Gaji 2023 blog :: 2023 :: expert quote + survey (48.9% employers hiring more; 75.5% planning salary increases) :: employers.glints.com/id-id/blog/data-gaji :: 3] |
| 2023 | RW Software Developer +~10–17% bounds: Rp 350–700m/yr | [RW :: 3] |
| 2023 | DevSecOps named highest-growth role for 2024 (Indico hiring lead) | [Glints Data Gaji 2023 :: 3] |
| 2024 | NodeFlair 2024 report: SE mid start −15%, senior max −20%, lead max −? big falls; QA/DevOps/DS all down — the tech-winter repricing is in advertised numbers | [NodeFlair 2024 via safarseptyadi.com/gaji-software-engineer-turun-6-26-di-tahun-2025 :: 2025 :: commentary on payslip-verified report :: 3] |
| 2024 | Glassdoor SE Indonesia total comp est. Rp 12.25 jt/mo avg | [Glassdoor via safarseptyadi :: 2024 :: self-reported est :: 3] |
| 2025 | NodeFlair Indonesia SE overall median −7.7% YoY; DevOps −14.5% overall (senior −29%); Mobile only role up (+3.2%); falls are senior-loaded (lead −23.6%, junior −5.3%) | [NodeFlair 2025 PDF :: 4] |
| 2025 | BUT live-portal figures cited elsewhere: "SE salary +3.3% in 2025 after −1.0%" (Codepolitan, NodeFlair live data) — conflicts with the PDF overall figure; may be measuring different period/window | [Codepolitan via NodeFlair live :: 3] |
| 2025→26 | Glints (already-gathered): advertised tech-median +9.1% H1'24→H1'26 to Rp 6 jt; backend +25%; senior:entry ratio 2.7×→2.9× | [Glints :: 2026 :: advertised :: given by parent session :: 3] |
| 2026 | MP 2026: "steady recovery, salaries holding firm, increments 5–8%, higher for acute skills shortage" | [MP 2026 :: 3] |
| 2026 | AI premium: Shopee SWE-ML reported $15k/yr vs non-ML SWE $9–13k same platform; MP notes premium for AI/data-centre/cloud security talent; AWS (already-gathered): 57% orgs report AI-related skills gap | [Levels.fyi et al. :: 3] |

Interpretation: 2021–22 boom → 2023 first softening (prompted by tech winter; salaries still rose in recruiter books) → 2024–25 real declines concentrated in senior/DevOps/QA advertised rates, entry-level relatively flat → 2026 stabilization with AI/cloud/security premium segmentation. 2021 data point (Glints/other, year-overs-year %) not re-verified — gap.

## Remote-for-Foreign Premium

| Source | Figure | Tag |
|---|---|---|
| Arc.dev | Expected salary avg $50,146/yr; senior $69,110/yr (≈ Rp 66–91 jt/mo). By spec: Frontend $47.8k/$68.6k, Backend $48.7k/$72.1k, Data Scientist $52.6k/$74.2k, App Dev $45.3k/$70.1k, DevOps $54.3k/$79.6k | [Arc.dev :: 2026 :: self-reported expectations of remote devs who passed vetting stages (biased upward) :: arc.dev/salaries/software-engineers-in-indonesia :: 3] |
| RubyonRemote | avg $129,472/yr (range $20k–$338k), N=142 | [RubyonRemote :: 2024 :: self-reported, upward-biased (top of remote market) :: rubyonremote.com/developer-salaries-in-indonesia :: 2] |
| Himalayas | avg $29k/yr, range $2k–61k, N=9 | [Himalayas.app :: 2025 :: self-reported, tiny N :: 2] |
| orang.engineer cases | US remote senior $75 jt/mo base (from Yogyakarta); SG remote senior $55 jt/mo (from Surabaya) | [orang.engineer :: 2026 :: single-case self-reports :: 3] |
| Rain Technovation consulting tiers | junior $800–1,200/mo, mid $1,200–2,000/mo, senior $2,000–3,000/mo, staff $3,000+ | [Rain Technovation :: 2026 :: consulting-rate card / marketing blog :: 2] |
| Medium community guide | mid-level local 12–18 jt/mo → remote-US roles are the single largest achievable pay rise | [kelvindesman on Medium :: 2026 :: practitioner commentary :: 2] |

Premium vs local (medians): local mid SE Rp 9 jt/mo (~$560/mo); mid remote $1.2–2k/mo = — **~1.7×–2.2×** the senior NodeFlair median (Rp 12.5 jt ≈ $780/mo) and ~**2–3×** the mid median. Single Arc "average" implies a ~5–7× premium — unrealistic vs actual negotiated packages; use lower band (orang.engineer + Rain tiers) for the 2–3× estimate. Reliable Point: \*\*$1,200–2,000/mo for mid, $2,000–3,000/mo for senior\*\* working US/SG-remote =~ \*\*2–3× local net\*\*. [mixed sources as above :: overall confidence 2–3]

## Methodology Assessment

- **Recruiter guides** (MP, RW, Kelly, Monroe, SF Consulting etc.): each is a marketing artifact designed to generate placement mandates; incentive is to quote *slightly high* bands to justify recruiter fees. MP states openly: models on its own placements, paid by the hiring company. RW provides no sample sizes. Kelly provides no sample. Across guides, no role-level agreement exists (e.g., backend: NodeFlair median 12.5jt senior vs RW "PM" 500k–650k annual vs Kelly 15–22jt) — the differences reflect the audience (who goes through agencies is the paid sample, not the market average).
- **Advertised-salary trackers** (NodeFlair, Glints): larger N, payslip verification is NodeFlair's genuine differentiator; upward-skew because job posts state *asking* pay.
- **Self-reported survey sites** (Levels.fyi, Glassdoor): big-tech/DKU-skewed, potentially upward-biased, but small-N percentiles (N=244 for a city) have real bias error.
- **Contractor-rate sites** (Arc.dev, Rain): explicit expectation-of-vetted-remote-devs; neither is a market-clearing price.
- No source offers role-level, level-band, statistically representative national sampling (BPS can't do this for IT and is banned by the brief). Best practice remains triangulation across the 3–4 method types above.

## JSON

```json
[
{"role":"Software Engineer","level":"Junior","min":4500000,"max":12000000,"median":7500000,"source":"NodeFlair Asia Tech Salary Report 2025","year":2025,"period_unit":"idr_month","confidence":4},
{"role":"Software Engineer","level":"Mid","min":5000000,"max":15000000,"median":9000000,"source":"NodeFlair 2025","year":2025,"period_unit":"idr_month","confidence":4},
{"role":"Software Engineer","level":"Senior","min":5500000,"max":24000000,"median":12500000,"source":"NodeFlair 2025","year":2025,"period_unit":"idr_month","confidence":4},
{"role":"Software Engineer","level":"Lead","min":7000000,"max":25000000,"median":12500000,"source":"NodeFlair 2025","year":2025,"period_unit":"idr_month","confidence":4},
{"role":"Mobile Engineer","level":"Junior","min":5000000,"max":11500000,"median":7800000,"source":"NodeFlair 2025","year":2025,"period_unit":"idr_month","confidence":4},
{"role":"Mobile Engineer","level":"Mid","min":5800000,"max":14000000,"median":9500000,"source":"NodeFlair 2025","year":2025,"period_unit":"idr_month","confidence":4},
{"role":"Mobile Engineer","level":"Senior","min":7000000,"max":22500000,"median":11000000,"source":"NodeFlair 2025","year":2025,"period_unit":"idr_month","confidence":3},
{"role":"Data Scientist","level":"Junior","min":6300000,"max":14000000,"median":8500000,"source":"NodeFlair 2025","year":2025,"period_unit":"idr_month","confidence":3},
{"role":"Data Scientist","level":"Mid","min":7000000,"max":21500000,"median":11300000,"source":"NodeFlair 2025","year":2025,"period_unit":"idr_month","confidence":3},
{"role":"Data Scientist","level":"Senior","min":9000000,"max":25000000,"median":12500000,"source":"NodeFlair 2025","year":2025,"period_unit":"idr_month","confidence":3},
{"role":"QA Engineer","level":"Junior","min":4500000,"max":10000000,"median":6800000,"source":"NodeFlair 2025","year":2025,"period_unit":"idr_month","confidence":3},
{"role":"QA Engineer","level":"Mid","min":5500000,"max":11000000,"median":8000000,"source":"NodeFlair 2025","year":2025,"period_unit":"idr_month","confidence":3},
{"role":"QA Engineer","level":"Senior","min":7300000,"max":14500000,"median":10000000,"source":"NodeFlair 2025","year":2025,"period_unit":"idr_month","confidence":3},
{"role":"DevOps Engineer","level":"Junior","min":6000000,"max":12000000,"median":8500000,"source":"NodeFlair 2025","year":2025,"period_unit":"idr_month","confidence":3},
{"role":"DevOps Engineer","level":"Mid","min":7300000,"max":15000000,"median":9000000,"source":"NodeFlair 2025","year":2025,"period_unit":"idr_month","confidence":3},
{"role":"DevOps Engineer","level":"Senior","min":10000000,"max":20000000,"median":15000000,"source":"NodeFlair 2025","year":2025,"period_unit":"idr_month","confidence":3},
{"role":"Backend Developer","level":"all (avg)","min":25000000,"max":null,"median":25000000,"source":"Michael Page 2025","year":2025,"period_unit":"idr_month","company_type":"MNC placements","confidence":4},
{"role":"Frontend Developer","level":"all (avg)","min":20000000,"max":null,"median":20000000,"source":"Michael Page 2025","year":2025,"period_unit":"idr_month","company_type":"MNC placements","confidence":4},
{"role":"Fullstack Developer","level":"all (avg)","min":30000000,"max":null,"median":30000000,"source":"Michael Page 2025","year":2025,"period_unit":"idr_month","company_type":"MNC placements","confidence":4},
{"role":"Mobile Developer","level":"all (avg)","min":25000000,"max":null,"median":25000000,"source":"Michael Page 2025","year":2025,"period_unit":"idr_month","confidence":4},
{"role":"QA Engineer","level":"all (avg)","min":23000000,"max":null,"median":23000000,"source":"Michael Page 2025","year":2025,"period_unit":"idr_month","confidence":4},
{"role":"Tech Lead","level":"all (avg)","min":40000000,"max":null,"median":40000000,"source":"Michael Page 2025","year":2025,"period_unit":"idr_month","confidence":4},
{"role":"Product Manager","level":"all (avg)","min":25000000,"max":null,"median":25000000,"source":"Michael Page 2025","year":2025,"period_unit":"idr_month","confidence":4},
{"role":"Senior Product Manager","level":"senior","min":35000000,"max":null,"median":35000000,"source":"Michael Page 2025","year":2025,"period_unit":"idr_month","confidence":4},
{"role":"UX/UI Designer","level":"all (avg)","min":43000000,"max":null,"median":43000000,"source":"Michael Page 2025","year":2025,"period_unit":"idr_month","confidence":4},
{"role":"Business Intelligence Analyst","level":"all (avg)","min":27000000,"max":null,"median":27000000,"source":"Michael Page 2025","year":2025,"period_unit":"idr_month","confidence":4},
{"role":"Lead Data Analyst","level":"lead","min":30000000,"max":null,"median":30000000,"source":"Michael Page 2025","year":2025,"period_unit":"idr_month","confidence":4},
{"role":"Senior DevOps Engineer","level":"senior","min":35000000,"max":null,"median":35000000,"source":"Michael Page 2025","year":2025,"period_unit":"idr_month","confidence":4},
{"role":"Senior Security Engineer","level":"senior","min":35000000,"max":null,"median":35000000,"source":"Michael Page 2025","year":2025,"period_unit":"idr_month","confidence":4},
{"role":"Head of Engineering","level":"head","min":81000000,"max":null,"median":81000000,"source":"Michael Page 2025","year":2025,"period_unit":"idr_month","confidence":4},
{"role":"DevOps Manager","level":"manager","min":50000000,"max":null,"median":50000000,"source":"Michael Page 2025","year":2025,"period_unit":"idr_month","confidence":4},
{"role":"IT Support Staff","level":"all","min":7000000,"max":8000000,"median":7500000,"source":"Kelly Services 2025","year":2025,"period_unit":"idr_month","company_type":"outsourcing/SME-heavy","confidence":3},
{"role":"Backend Developer","level":"3-8 yrs","min":15000000,"max":20000000,"median":17500000,"source":"Kelly Services 2025","year":2025,"period_unit":"idr_month","confidence":3},
{"role":"Software Engineer","level":"1-4 yrs","min":10000000,"max":15000000,"median":12500000,"source":"Kelly Services 2025","year":2025,"period_unit":"idr_month","confidence":3},
{"role":"Tech Lead","level":"1-4 yrs","min":40000000,"max":60000000,"median":50000000,"source":"Kelly Services 2025","year":2025,"period_unit":"idr_month","confidence":2},
{"role":"UI/UX Developer","level":"3-8 yrs","min":15000000,"max":20000000,"median":17500000,"source":"Kelly Services 2025","year":2025,"period_unit":"idr_month","confidence":3},
{"role":"IT PM Manager","level":"5+ yrs","min":20000000,"max":35000000,"median":27500000,"source":"Kelly Services 2025","year":2025,"period_unit":"idr_month","company_type":"PMO/Scrum-lead","confidence":3},
{"role":"Software Developer","level":"all","min":350000000,"max":700000000,"median":null,"source":"Robert Walters Salary Survey 2024 (2023 identical)","year":2024,"period_unit":"idr_year","confidence":3},
{"role":"Data Scientist","level":"all","min":400000000,"max":850000000,"median":null,"source":"Robert Walters Salary Survey 2024","year":2024,"period_unit":"idr_year","confidence":3},
{"role":"Product Manager (Digital)","level":"all","min":500000000,"max":750000000,"median":null,"source":"Robert Walters Salary Survey 2024","year":2024,"period_unit":"idr_year","confidence":3},
{"role":"IT Manager","level":"all","min":550000000,"max":850000000,"median":null,"source":"Robert Walters Salary Survey 2024","year":2024,"period_unit":"idr_year","confidence":3},
{"role":"Head of Cyber Security","level":"head","min":845000000,"max":1300000000,"median":null,"source":"Robert Walters Salary Survey 2024","year":2024,"period_unit":"idr_year","confidence":3},
{"role":"CTO","level":"exec","min":1800000000,"max":3000000000,"median":null,"source":"Robert Walters Salary Survey 2024","year":2024,"period_unit":"idr_year","confidence":3},
{"role":"Software Engineer","level":"all (total comp)","min":9100000,"max":32100000,"median":21100000,"source":"Levels.fyi Jakarta, N=244, updated Nov 2026","year":2026,"period_unit":"idr_month","company_type":"unicorns/big tech over-represented","confidence":4},
{"role":"Software Engineer","level":"senior","min":36000000,"max":null,"median":36000000,"source":"orang.engineer (GoTo senior backend)","year":2026,"period_unit":"idr_month","company_type":"startup-unicorn","confidence":3},
{"role":"DevOps Lead","level":"lead","min":48000000,"max":null,"median":48000000,"source":"orang.engineer (BCA Digital blu)","year":2026,"period_unit":"idr_month","company_type":"bank digital","confidence":3},
{"role":"Fullstack AI Engineer","level":"senior","min":75000000,"max":null,"median":75000000,"source":"orang.engineer (US remote)","year":2026,"period_unit":"idr_month","company_type":"US-startup-remote","confidence":3},
{"role":"Backend Developer","level":"mid","min":21000000,"max":null,"median":21000000,"source":"orang.engineer (eFishery, Bandung)","year":2026,"period_unit":"idr_month","company_type":"startup (non-unicorn, Bandung)","confidence":3},
{"role":"Remote Software Engineer","level":"mid (expected)","min":19700000,"max":32800000,"median":26300000,"source":"Arc.dev $1.2k–2k/mo tiers (mid)","year":2026,"period_unit":"idr_month","company_type":"remote-for-foreign","confidence":3},
{"role":"Remote Software Engineer","level":"senior (expected)","min":32800000,"max":49200000,"median":41000000,"source":"Arc.dev $2k–3k/mo tiers (senior)","year":2026,"period_unit":"idr_month","company_type":"remote-for-foreign","confidence":3}
```

## Data Gaps

1. **2021 baseline**: no verified per-role Indonesian figure for 2021 found this session (Glints 2022 report exists as PDF/ebook but salary table content not re-extracted) — trend series pre-2022 incomplete.
2. **Glints 2024 survey medians (parent session) vs 2023 versus 2022 tables** — back issues need enterprise e-book extraction to build full continuous series.
3. **Michael Page 2026 tables**: image-only in available sources — need PDF from michaelpage.co.id's "salary insights" interactive tool; if parent session needs 2026 numbers per role, fetch via their postal endpoint or their benchmark tool.
4. **Telco per-role salaries** (Telkomsel/Telkom/XL/Indosat): no published table found. Likely need to check BUMN remuneration disclosures or union/vacancy data.
5. **Outsourcing (PKWT) rate cards**: no public monthly/annual rates for contractor developers; Kelly's low bands + Binar's undisclosed pricing are indirect evidence only.
6. **ESOP receiver shares and vesting economics** (e.g., median % equity for a senior eng at Series-A Indonesian startup): Glints-MHV report — % who *receive* ESOP at companies that offer — exists in the full 2023/2024 PDF (not re-extracted this session; only 86%-of-startups-offer stat verified via Katadata).
7. **Bank-digital premium quantification**: no rigorous published "bank vs startup for same role" % study found.
8. Non-engineering NodeFlair tables for Indonesia (data analyst, PM, Scrum) — published only for Singapore in the 2025 report.
9. % of *all* Indonesian tech employees receiving RSUs — no survey found (would fight against the usual "ESOP-offered ≠ vested").
