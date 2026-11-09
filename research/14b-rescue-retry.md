# Data Rescue Retry — SO Microdata + Archived Reports (14b)

Retry of stalled rescue mission. Predecessor file `14-data-rescue.md` NOT found → ran full mission. Date: 2026-11-09.

## Retrieval Log

| # | Target | Status | Method |
|---|--------|--------|--------|
| 1 | Stack Overflow Developer Survey microdata → Indonesia slice | ✅ RETRIEVED (2025 full microdata, 181 IDN respondents) | GitHub official archive StackExchange/Survey via Git LFS media URL (140MB results.csv), python3 CSV filter |
| 2 | LinkedIn "Jobs on the Rise 2025" Indonesia full 1–15 list | ✅ RETRIEVED | websearch → TopCareer.id article quoting LinkedIn (Jan 21, 2025); methodology from CNBC coverage |
| 3 | Kalibrr "Job Report Indonesia" PDF (tech vacancies/salary) | ❌ FAILED | Direct URL, r.jina.ai, websearch ×2, archive.org CDX (archive temporarily offline). kalibrr.com/job-report exists but is login-walled ("Page not available"); no public PDF/press figures found |
| 4 | Payoneer Freelancer Insights, Indonesia hourly rate | ⚠️ PARTIAL | 2023 Freelancer Insights Report PDF retrieved but has NO Indonesia country row; Indonesia figure found in the **2018** Freelancer Income Survey PDF (men $18/hr, women $19/hr); 2015 edition gives Indonesia avg 34.0 hrs/week |
| 5 | Deel State of Global Hiring — Indonesia contractor numbers | ❌ FAILED | Reports 2022–2026 all form-gated on deel.com; press coverage (HCAMag, HR Brew) has regional/global figures only, no Indonesia-specific contractor counts. APAC context: global hiring in APAC +57% in 2023; Singapore top SEA hirer — Indonesia not broken out |
| 6 | E33G remote-worker KITAS issuance numbers | ⚠️ PARTIAL | Official imigrasi.go.id E33G visa page retrieved (requirements, fees, legal basis). Issuance/take-up numbers: NOT published — confirmed by dedicated 2026 tracking site ("DGI has not released visa-code-specific issuance statistics") |
| 7 | data.komdigi.go.id DTS recapis per-track/per-province dataset | ⚠️ PARTIAL | Exact "recapis" per-province dataset not found on portal; equivalent **"Jumlah Peserta Kompeten Berdasarkan Akademi"** dataset retrieved live with per-academy participant counts |

**Item 1 source line:** [StackExchange/Survey GitHub official archive :: 2025 survey (fielded May 29–Jun 23 2025, released Jul 29 2025) :: Git LFS download `media.githubusercontent.com/media/StackExchange/Survey/main/packages/archive/2025/results.csv` + python3 filter :: https://github.com/StackExchange/Survey :: CONFIDENCE 5]

Methodology caveat (required one-liner): SO survey respondents were recruited via Stack Overflow's own channels (onsite messaging, blog, newsletters, social), so the sample is self-selected and skews toward highly-engaged SO users — not a probability sample of Indonesian developers.

**Artifacts saved:**
- `research/so2025_indonesia_microdata.csv` — 181-row Indonesia slice of the 2025 survey (all 111 columns, 640 KB)

## Stack Overflow Indonesia Microdata (2025 survey)

**IDN respondent count: 181** (out of ~65k global).

**MainBranch (identity):**
- Developer by profession: 122 (67.4%)
- Not primarily a developer but write code: 19 (10.5%)
- Learning to code: 16 (8.8%)
- Hobby coder: 12 (6.6%)
- Work with/support developers: 8 (4.4%)
- Former developer: 4 (2.2%)

**Employment status (single-select):**
- Employed: 109 (60.2%)
- Independent contractor / freelancer / self-employed: 34 (18.8%) ← notably high freelance share
- Student: 18 (9.9%)
- Not employed: 15 (8.3%)
- Prefer not to say: 5 (2.8%)

**Remote work (among 131 non-NA):**
- In-person: 50 (27.6% of all; 38.2% of answered)
- Remote: 27 (14.9% / 20.6%)
- Hybrid (lean in-person): 24 (13.3% / 18.3%)
- Hybrid (lean flexible): 19 (10.5% / 14.5%)
- Fully flexible (your choice): 11 (6.1% / 8.4%)
- NA (mostly students/unemployed): 50 (27.6%)

**Org size (among 137 non-NA):**
- <20 employees: 34; 20–99: 38; 100–499: 24; 500–999: 7; 1,000–4,999: 9; 5,000–9,999: 5; 10,000+: 3; Just me/freelancer: 15; DK: 2; NA: 44. → ~65% of IDN respondents work in orgs <500 people.

**Top developer roles (DevType, multi-select; base 181):**
| Role | Count |
|---|---|
| Developer, full-stack | 63 |
| Developer, back-end | 27 |
| Student | 19 |
| Developer, front-end | 12 |
| Developer, mobile | 11 |
| Academic researcher | 5 |
| Developer, desktop/enterprise | 4 |
| Data or business analyst | 4 |
| Developer, AI apps | 3 |
| Cloud infrastructure engineer | 3 |

**Compensation (ConvertedCompYearly, n=81):**
- Median: **USD 5,638/yr** (~IDR 90M/yr) — p25 $2,758, p75 $12,256, min $1 (noise), max $214,487
- Caveat: tiny n, includes part-timers/hobbyists, currency-converted at survey-time FX; treat as directional only. Global professional-developer median for comparison ~$60k–$75k.

## Retrieved Items Detail

### Item 2 — LinkedIn Jobs on the Rise 2025, Indonesia (full 1–15)
[LinkedIn Jobs on the Rise 2025 :: released Jan 2025, growth window Jan 2022–Jul 2024 (job-title growth among LinkedIn members starting jobs; methodology per CNBC Australia coverage of the same global series) :: TopCareer.id article quoting LinkedIn :: https://topcareer.id/linkedin-ungkap-15-pekerjaan-yang-tumbuh-pesat-di-indonesia/ :: CONFIDENCE 4]

1. Travel Consultant
2. Cyber Security Engineer
3. Security Operations Center (SOC) Analyst
4. Behavioral Therapist
5. Director of Food & Beverage
6. BIM Modeler
7. Sales Account Manager
8. BIM Engineer
9. Personal Trainer
10. Piping Engineer
11. 3D Designer
12. Quality Supervisor
13. Audit Supervisor
14. Project Manager
15. Credit Officer

Growth context: LinkedIn flagged Indonesia's rises in **security engineering**, **travel/hospitality** (post-COVID normalization), and in-person service roles; the same global series had AI Engineer topping 15 of 21 countries but **AI Engineer did NOT make Indonesia's list** — Indonesia's tech entries are security-focused (#2 Cyber Security Engineer, #3 SOC Analyst).

Related (different methodology — graduates only, Jan 2022–Dec 2024): LinkedIn **Grad Guide 2025** Indonesia top 10 for fresh grads headed by 1) AI Engineer, 2) SOC Analyst, 3) Environmental Health Safety Specialist (per Detik.com / Jakarta Globe, May 2025); green-skill holders 54.6% more likely to be hired.

### Item 4 — Payoneer Freelancer Insights (partial)
[Payoneer :: 2018 Freelancer Income Survey for Indonesia figures; 2023 Freelancer Insights Report checked and lacks Indonesia row :: direct PDFs (biztips.co mirror of official PDF; pubs.payoneer.com) :: https://pubs.payoneer.com/docs/2023-freelancer-insights-report.pdf :: CONFIDENCE 4 for 2018 figures]
- **Indonesia freelancer average hourly rate (2018 survey, ~23k freelancers/170 countries): Men $18/hr, Women $19/hr** (Indonesia was cited as an example where women out-earn men).
- 2015 edition: Indonesia avg workweek 34.0 hrs (among the lower of surveyed countries).
- 2023 report (2,000+ freelancers, 122 countries): worldwide average $23/hr (women $22, men $24) — no Indonesia breakout. 2022–2024 editions publish no Indonesian country-level figure.

### Item 6 — E33G Remote Worker KITAS (partial)
[Direktorat Jenderal Imigrasi + visa-sector trackers :: rules 2024 (Permenkumham 22/2023, as amended 11/2024), stats as of 2026 :: direct fetch of imigrasi.go.id E33G page :: https://www.imigrasi.go.id/wna/daftar-visa-indonesia/E33G :: CONFIDENCE 5 for rules, n/a for counts]
- Official requirements: income ≥ **USD 60,000/yr** from a company established outside Indonesia; employment contract with foreign company; proof of funds ≥ USD 2,000; fee ~IDR 7,000,000 total for one year; 1-year limited stay, multiple entry; no sponsor required; process ~5 working days.
- Launch: E33G introduced **April 2024** (not Nov — mission note slightly off; some trackers say introduced 2023 legal framework, operational April/May 2024).
- **Issuance/take-up numbers: NOT published.** DGI has not released visa-code-level issuance statistics (confirmed May 2026 by whatise33gvisa.com tracking page, which is run by a visa agency). No credible press figure found either → treat any circulating number as unverified.

### Item 7 — Komdigi DTS recaps (partial)
[Satu Data Komdigi :: dataset "Jumlah Peserta Kompeten Berdasarkan Akademi" created 13 Apr 2026, updated 9 Nov 2026 (appears to be latest DTS cohort recap) :: direct fetch via r.jina.ai :: https://data.komdigi.go.id/opendata/dataset/jumlah-peserta-kompeten-berdasarkan-akademi :: CONFIDENCE 4]
Per-academy (seri) DTS participant counts:

| Akademi | Peserta Kompeten | Peserta Onboarding/Sertifikasi Lanjut | % Capaian |
|---|---|---|---|
| FGA (Fresh Graduate Academy) | 5,142 | 6,752 | 76.16% |
| VSGA (Vocational) | 15,019 | 16,337 | 91.93% |
| TA (Thematic Academy) | 20,581 | 24,712 | 83.28% |
| Pro A (Professional Academy) | 7,643 | 10,039 | 76.13% |
| DEA (Digital Entrepreneurship) | 31,946 | 34,485 | 92.64% |
| GTA (Government Transformation) | 15,482 | 17,752 | 87.21% |
| TSA (Tech Talent/Training?) | 3,458 | 3,809 | 90.78% |
| **Total** | **99,271** | **113,886** | **87.17%** |

Note: the specific "recapis" per-province/per-track dataset (DTS 2023–2024) was not on the public portal; older DTS volumes (2020–2024 program-wide achievement infographic exists: data.komdigi.go.id/article/capaian-digital-talent-scholarship-dts) but per-province breakdown requires PPID request (portal states "Hubungi PPID untuk permintaan data ini").

## JSON

```json
{
  "mission": "data-rescue-retry",
  "date": "2026-11-09",
  "stack_overflow_2025_indonesia": {
    "source": "StackExchange/Survey GitHub official archive (Git LFS)",
    "url": "https://github.com/StackExchange/Survey",
    "idn_respondents": 181,
    "employment": {"employed": 109, "freelancer_contractor": 34, "student": 18, "not_employed": 15, "no_say": 5},
    "remote_work": {"in_person": 50, "remote": 27, "hybrid_inperson_lean": 24, "hybrid_flex_lean": 19, "fully_flexible": 11, "na": 50},
    "top_roles": {"full_stack": 63, "back_end": 27, "student": 19, "front_end": 12, "mobile": 11},
    "comp_usd_yearly": {"n": 81, "median": 5638, "p25": 2758, "p75": 12256},
    "bias_note": "Self-selected sample recruited via Stack Overflow-owned channels; skews to highly-engaged SO users",
    "artifact": "research/so2025_indonesia_microdata.csv"
  },
  "linkedin_jobs_on_the_rise_2025_indonesia": {
    "source": "LinkedIn via TopCareer.id",
    "url": "https://topcareer.id/linkedin-ungkap-15-pekerjaan-yang-tumbuh-pesat-di-indonesia/",
    "methodology": "growth in job titles started by LinkedIn members, Jan 2022 - Jul 2024",
    "list": ["Travel Consultant", "Cyber Security Engineer", "Security Operations Center Analyst", "Behavioral Therapist", "Director of Food and Beverage", "BIM Modeler", "Sales Account Manager", "BIM Engineer", "Personal Trainer", "Piping Engineer", "3D Designer", "Quality Supervisor", "Audit Supervisor", "Project Manager", "Credit Officer"]
  },
  "kalibrr_job_report": {"status": "FAILED", "blocker": "login-walled at kalibrr.com/job-report; no public PDF or press summary of vacancy/salary figures"},
  "payoneer_freelancer_indonesia": {
    "status": "PARTIAL",
    "hourly_rate_usd_2018": {"men": 18, "women": 19},
    "avg_weekly_hours_2015": 34.0,
    "note": "2023 Freelancer Insights Report (world avg $23/hr) has no Indonesia breakout"
  },
  "deel_global_hiring": {"status": "FAILED", "blocker": "reports 2022-2026 form-gated; no Indonesia contractor counts in press coverage; APAC global hiring +57% in 2023 is nearest public datapoint"},
  "e33g_remote_worker_kitas": {
    "status": "PARTIAL",
    "introduced": "2024-04",
    "income_requirement_usd": 60000,
    "fee_idr": 7000000,
    "duration": "1 year, multiple entry",
    "issuance_numbers": "NOT PUBLISHED by Ditjen Imigrasi (confirmed)",
    "url": "https://www.imigrasi.go.id/wna/daftar-visa-indonesia/E33G"
  },
  "komdigi_dts_study": {
    "status": "PARTIAL",
    "dataset": "Jumlah Peserta Kompeten Berdasarkan Akademi",
    "url": "https://data.komdigi.go.id/opendata/dataset/jumlah-peserta-kompeten-berdasarkan-akademi",
    "total_peserta_kompeten": 99271,
    "per_akademi": {"FGA": 5142, "VSGA": 15019, "TA": 20581, "ProA": 7643, "DEA": 31946, "GTA": 15482, "TSA": 3458},
    "note": "per-province recapis dataset not public; requires PPID request"
  }
}
```

## Still Missing

1. **Kalibrr Job Report Indonesia** vacancy counts/salaries — login-walled; would need a Kalibrr account session or a press-archived summary. (Archive.org was temporarily offline during this run — a later CDX retry could find cached report pages.)
2. **Deel Indonesia contractor counts** — full reports are form-gated PDFs; only path is registering for the download or finding a journalist's excerpt with the Indonesia country table.
3. **E33G issuance statistics** — not published anywhere official; would need a FOIA-style PPID request to Ditjen Imigrasi or wait for their annual statistics release.
4. **DTS recapis per-province/per-track 2023–2024** — not on public Satu Data portal; requires PPID request to Komdigi BPSDM.
5. **Payoneer Indonesia figure in a 2022–2024 edition** — the country tables were dropped after ~2020; 2018 figure is the latest verifiable Indonesia number.
