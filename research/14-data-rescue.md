# Data Rescue — Indonesia IT Workforce Study (Agent 14)

Date: 2026-11-09. Methods: shell curl + python3 (CSV microdata, PDFs), webfetch, r.jina.ai proxy, Google News RSS.
Infra events: (1) web.archive.org + CDX API returned "Internet Archive: Temporarily Offline" for the whole session → all archive.org-dependent routes dead. (2) websearch (TinyFish) hit 50/50 quota mid-session → later hunting done via jina/curl only. (3) official SO data host `files.survey.stackoverflow.com` is NXDOMAIN (dead).

## Retrieval Log

| # | Target | Status | Method notes |
|---|--------|--------|--------------|
| 1 | Stack Overflow Dev Survey 2024 RAW | **RETRIEVED (full microdata)** | Official zip host DNS-dead; wayback lacks zip; found full official zip (17,703,733 bytes) mirrored in GitHub repo; curl → unzip → python3 csv filter Country=="Indonesia" |
| 2 | Payoneer Freelancer Insights (2022/2023) | **PARTIAL** | Full text of 2023 report page, 2022 report page, 2020 PDF (pubs.payoneer.com direct download), 2015 report PDF (lirneasia.net). No Indonesia-specific hourly rate exists in the retrieved documents — global/regional only |
| 3 | Deel State of Global Hiring | **FAILED (Indonesia data)** | deel.com/global-hiring-report-2024 page = consent-wall; rendered text is cookie-policy junk only; no country tables publicly; report gated behind gated download |
| 3b | Oyster HR Global Employment Report | **FAILED** | URL 404 (report removed/renamed); no APAC/ID figures retrievable |
| 4 | E33G remote-worker KITAS take-up numbers | **FAILED (numbers); PARTIAL (context)** | imigrasi.go.id returns 403 to proxies; Google News ID/EN RSS shows no issuance-count articles; no official statistics page found. Secondary sources give requirements only |
| 5 | Michael Page Indonesia Salary Guide tech tables | **PARTIAL / FAILED for tables** | 2026 guide page live; full role×level tables only inside JS "salary comparison tool" / Salesforce-gated download form; no public PDF URL found; retrieved median + sentiment stats and tech-role JD list |
| 6 | Kalibrr Job Report Indonesia 2024/2025 | **FAILED** | kalibrr.com/resources/jobs-report/ = 404 ("Page not available"); Google News RSS: zero articles. Kalibrr site is now PH-oriented |
| 7 | APTIKNAS member count | **FAILED** | aptiknas.org redirects → www.aptiknas.org which serves a parked/placeholder page ("PT Solarion Energi Alam", no org content); archive.org offline so no historical snapshots |
| 8 | Komdigi published datasets (DTS recap) | **PARTIAL** | Satu Data Komdigi portal live; dataset "Jumlah Peserta Kompeten Berdasarkan Akademi" (DTS recap by academy) exists with metadata, but resource download URL points to internal RFC1918 address `http://172.30.103.58:5000/...` → externally unreachable. Related IMDI/literasi datasets catalogued |
| 9 | LinkedIn-WEF Jobs on the Rise Indonesia 2025 | **PARTIAL-RETRIEVED** | LinkedIn talent blog fetched raw via curl UA; Indonesia top-3 confirmed; full 15-role list with growth % lives in gated LinkedIn Pulse article (not fetchable); WEF story slug 404 |

## Stack Overflow Indonesia Microdata (2024) — GOLD-graded

**Source file**: official public dataset zip (ODbL license) mirrored at https://github.com/sumanndass/StackOverflow-Survey-2024-Python-EDA (raw file `stack-overflow-developer-survey-2024.zip`, 17.7MB, unzipped survey_results_public.csv 159,525,875 bytes + survey schema + official PDF). Survey fielded May 19–Jun 20 2024; 65,437 qualified responses from 185 countries; salaries converted to USD at Jun 11 2024 rate.
Local copies: `research/downloads/so2024.zip`, `research/downloads/indonesia_2024.csv` (354 IDN rows extracted).

- **Indonesia respondents: 354 of 65,437 = 0.54%** (not in top-10 countries)
- MainBranch: dev by profession 226 (63.8%); not primarily a dev 52 (14.7%); learning to code 42 (11.9%); hobby 28 (7.9%); former dev 6 (1.7%)
- **Employment**: Employed full-time (any combination incl. solo) = 206 rows (58.2% — includes 155 purely full-time, 43.8%); Independent contractor/freelancer appears in 90 rows (25.4% of respondents — but many part-year/students); Student (full/part) in ~84 rows; not-employed-looking 39 rows
- **Remote work environment** (n=354): Hybrid 109 (30.8%), In-person 81 (22.9%), Remote 76 (21.5%), NA 88 (24.9%) → among the 266 who answered: Hybrid 41%, In-person 30.5%, Remote 28.6%
- **DevType (multi-select, % of IDN rows)**: Full-stack 114 (32.2%), Back-end 69 (19.5%), Student 45 (12.7%), Front-end 29 (8.2%), Mobile 23 (6.5%), Desktop/enterprise 9 (2.5%), Academic researcher 7 (2.0%), Data engineer 5 (1.4%), Data scientist/ML 4 (1.1%), DevOps 4 (1.1%), QA/test 3, Game/graphics 3, Engineering manager 3, C-suite 3, Cloud infra 3, other roles ≤2
- **Age**: 18–24: 132 (37.3%); 25–34: 145 (41.0%); 35–44: 32 (9.0%); <18: 21 (5.9%); 45–54: 20 (5.6%)
- Currency: 223 report IDR as comp currency; 12 report USD
- **Salary**: rows with ConvertedCompYearly (n=103): median **USD 7,360/yr**, p25 USD 3,067, p75 USD 14,720. Rows in IDR (n=127): median **IDR 96,000,000/yr** (~USD 5,900 at ~16,300/USD). Filtering professional devs only: USD median 11,040 (n=90); IDR median 100,000,000 (n=111). YearsCodePro median for IDN professional devs: 7.5 yrs (n=206). WorkExp median 5.0 yrs (n=153).

Caveats for methodology: n=354 is small; SO sample skews to SO-engaged developers; 25% NA on remote question; salary self-reported, converted at single-day FX rate.

## Retrieved Item Details

### Payoneer Freelancer Insights (global benchmarks; no IDN rate found)
- [Payoneer 2023 Freelancer Insights Report :: 2023 :: r.jina.ai of live payoneer.com :: https://www.payoneer.com/resources/business/the-payoneer-2023-freelancer-insights-report/ :: CONF 5]
  5th edition; 2,000+ freelancers in 122 countries; 38% raised hourly rates past year vs 15% cut; women $22/hr vs men $24/hr; 55% took more work due to cost of living, 41% raised rates, 32% expanded to new countries.
- [Payoneer 2022 Global Freelancer Income Report :: 2022 :: r.jina.ai of live page :: https://www.payoneer.com/resources/news-events/2022-global-freelancer-income-report-the-ongoing-rise-of-the-freelance-revolution/ :: CONF 5]
  Worldwide avg hourly rate $28 (up from $21 in 2020); women $23 vs men $28 (82%); 40% raised rates during pandemic; 32% higher demand, 45% flat.
- [Payoneer 2020 Freelancer Income Report :: 2020 :: direct PDF curl from pubs.payoneer.com :: https://pubs.payoneer.com/images/2020-Freelancer-Income-Report.pdf (saved research/downloads/payoneer2020.pdf) :: CONF 5 for global; no IDN country figures]
  7,000 freelancers, 150+ countries; global avg $21/hr; Asia 82% under 35.
- [Payoneer Freelancer Income Survey :: 2015 :: direct PDF from lirneasia.net :: https://lirneasia.net/wp-content/uploads/2015/06/freelancer_report_EN_2015.pdf :: CONF 5]
  23,006 freelancers; global avg $21/hr; IT & Programming $21/hr skill-average; global avg 36 hrs/week. Indonesia appears only in hours-per-week chart (values 33.2–34.2 hrs band; pairing of labels ambiguous in text layer → CONF 2 for the pairing; **Indonesia avg between 33 and 34 hrs/week**).
- [Payoneer Top 10 Freelancing Countries :: 2024-25 :: r.jina.ai :: https://www.payoneer.com/resources/business/top-10-freelancing-countries/ :: CONF 4]
  Regional avg hourly rates: North America $44, Western Europe $31. Top-10 markets: USA, UK, Brazil, Pakistan, Ukraine, Philippines, India, Bangladesh, Russia, Serbia — Indonesia absent.
- 2019 Global Gig Economy Index: not directly retrieved (original explore.payoneer.com link, media coverage fragmentary via FB posts in search results — quotes Indonesia 50.9% self-employment growth YoY, but a Facebook post is not reliable primary retrieval → recorded as LEAD ONLY, CONF 2).

### Deel State of Global Hiring
- Report landing pages live: https://www.deel.com/global-hiring-report-2024/ (2023-24), /global-hiring-report-2025/. Content: consent-gated, rendered text = cookie policy only. Search snippets (CONF 3, unverified full docs): 2025 report based on 1M+ contracts / "82% of workers hired were remote in 2024", "domestic hiring rose 104% in 2024", PRNewswire: "AI trainer roles grew 283% cross-border in 2025". **No Indonesia-specific Deel numbers retrieved.**

### E33G Remote Worker KITAS
- Official visa description live: https://www.imigrasi.go.id/wna/daftar-visa-indonesia/E33G (403 to proxies; search snippet CONF 4 for existence & terms). Known terms from multiple secondary sources (CONF 4): min foreign income $60,000/yr, 1-year KITAS, tax-free on foreign income. Launch 2024 (Fragomen notes Apr–Aug 2024 implementation). **Take-up/issuance count: NOT FOUND in any reachable source.** Google News RSS (ID+EN) surfaced no article with issuance numbers as of 2026-11-09.

### Michael Page Indonesia Salary Guide 2026
- [Michael Page Salary Guide 2026 :: 2026 :: r.jina.ai + curl live michaelpage.co.id :: https://www.michaelpage.co.id/salary-guide :: CONF 4]
  - "Median gross yearly salary in Indonesia across all sectors/regions ≈ IDR 660,000,000" (per MP FAQ text, cites national stats framing)
  - 24% of professionals cite salary dissatisfaction as key reason to job-hunt; 72% satisfied with current salary (Talent Trends 2026 data)
  - Salaries shown as IDR gross average monthly, organized by years of experience
  - Full role×level tech tables: only via interactive "salary comparison tool" (only business-role static pages, no IT roles: /salary-comparison-tool/* lists account-manager, product-manager etc.) and gated PDF download form. **FAILED to retrieve full tech tables.**
- Tech roles covered by MP Indonesia JD library (2021-2023, CONF 5 for existence): UI Designer, IT Architect, DPO, Product Owner, Software Architect, Network Admin, IT Support, Service Manager, IT PM, Security Architect, Scrum Master, Cloud Engineer, Systems Engineer, Software Developer, IT Auditor, IT Program Manager, IT Manager, IT Assistant, InfoSec, Full Stack Dev, Frontend Dev, DevOps, Cybersecurity Engineer, Cloud Architect: https://www.michaelpage.co.id/advice/professions/technology

### Komdigi Satu Data portal (DTS recap)
[Satu Data Komdigi :: 2026 :: webfetch jina + curl :: https://data.komdigi.go.id/ :: CONF 5 for catalog, CONF 2 for data values]
- Dataset "Jumlah Peserta Kompeten Berdasarkan Akademi" (DTS competent-participants recap by academy): org BPSDMD Komdigi, created 2026-04-13, resource XLSX last_modified 2026-11-06, 156 downloads. **Resource URL is `http://172.30.103.58:5000/dataset/4be0cef2-d53a-48d6-b6cc-6031e26a3977/resource/8bd179c2-dbfc-4f9d-b293-dda939a62f72/download/jumlah-peserta-kompeten-berdasarkan-akademi.xlsx` — internal RFC1918 host, publicly unreachable → data values NOT retrieved.**
- Also catalogued (same portal, "SDM dan Masyarakat Digital" group): IMDI 2022-2023 (multiple cuts), digital literacy participant counts 2019-2021, literacy indices — all same internal-IP download issue.
- komdigi.go.id main site: 403 Access Denied to curl; Kominfo old domain data.kominfo.go.id: DNS unreachable.

### LinkedIn Jobs on the Rise 2025 — Indonesia
[LinkedIn Talent Blog "The World's Fastest-Growing Jobs in 2025" :: 2025 :: curl raw html :: https://www.linkedin.com/business/talent/blog/talent-acquisition/worlds-fastest-growing-jobs-2025 :: CONF 4]
- Indonesia **top 3**: 1. Travel consultant, 2. Cyber security engineer, 3. Security operations center analyst
- Blog text also confirms *among Indonesia's 15 fastest-growing roles* (unranked mentions): "food and beverage supervisors" (list shared with Canada, India, Germany) and "psychotherapist/psychologist" (list shared with Canada, Singapore, India, Ireland)
- Methodology: LinkedIn ranking of fastest-growing roles over past 3 years, published Jan 2025 for 14 countries (15 roles each). Growth percentages not published in the blog itself.
- Full ranked 15 + growth %: in LinkedIn Pulse article (LinkedIn-News gated) — not retrievable; WEF mirror 404. **PARTIAL.**
- Corroboration (CONF 3): LinkedIn News Asia post "From travel consultant to cyber security engineer…" (activity-7285416395645886464); newszii.com echoes the same top-3.

## JSON

```json
[
 {"id":"so-dev-survey-2024-idn","target":1,"status":"RETRIEVED","year":2024,"method":"GitHub mirror of official zip -> curl -> python3 CSV filter","url":"https://raw.githubusercontent.com/sumanndass/StackOverflow-Survey-2024-Python-EDA/main/stack-overflow-developer-survey-2024.zip","confidence":5,"data":{"n_idn":354,"share_pct":0.54,"dev_by_profession":226,"full_time_incl_mixed_rows":206,"freelancer_mention_rows":90,"remote_hybrid_pct_of_answers":41.0,"remote_pct_of_answers":28.6,"inperson_pct_of_answers":30.5,"devtype_fullstack_pct":32.2,"devtype_backend_pct":19.5,"devtype_mobile_pct":6.5,"median_comp_usd_all":7360,"median_comp_idr_all":96000000,"median_comp_usd_prof_dev":11040,"median_comp_idr_prof_dev":100000000,"median_yearscodepro_prof_dev":7.5,"age_18_34_pct":78.3}},
 {"id":"payoneer-freelancer-2023","target":2,"status":"PARTIAL","year":2023,"method":"r.jina.ai live page","url":"https://www.payoneer.com/resources/business/the-payoneer-2023-freelancer-insights-report/","confidence":5,"data":{"global_women_usd_hr":22,"global_men_usd_hr":24,"raised_rates_pct":38,"n":2000,"countries":122}},
 {"id":"payoneer-freelancer-2022","target":2,"status":"PARTIAL","year":2022,"method":"r.jina.ai live page","url":"https://www.payoneer.com/resources/news-events/2022-global-freelancer-income-report-the-ongoing-rise-of-the-freelance-revolution/","confidence":5,"data":{"global_avg_usd_hr":28,"women_usd_hr":23,"men_usd_hr":28}},
 {"id":"payoneer-freelancer-2020","target":2,"status":"PARTIAL","year":2020,"method":"curl direct PDF","url":"https://pubs.payoneer.com/images/2020-Freelancer-Income-Report.pdf","confidence":5,"data":{"global_avg_usd_hr":21,"n":7000,"asia_82pct_under35":true}},
 {"id":"payoneer-freelancer-2015","target":2,"status":"PARTIAL","year":2015,"method":"curl direct PDF (lirneasia mirror)","url":"https://lirneasia.net/wp-content/uploads/2015/06/freelancer_report_EN_2015.pdf","confidence":3,"data":{"indonesia_hours_per_week":33.5,"note":"chart text-layer pairing ambiguous","global_avg_usd_hr":21,"n":23006}},
 {"id":"deel-global-hiring-2024-2025","target":3,"status":"FAILED","year":2024,"method":"r.jina.ai (consentwalled)","url":"https://www.deel.com/global-hiring-report-2024/","confidence":2,"data":null,"blocker":"consent-wall; no public country tables; Indonesia figures not published openly"},
 {"id":"oyster-global-employment-report","target":3,"status":"FAILED","year":null,"method":"r.jina.ai","url":"https://www.oysterhr.com/resources/report/global-employment-report","confidence":2,"data":null,"blocker":"404 removed"},
 {"id":"e33g-kitas-takeup","target":4,"status":"FAILED","year":2024,"method":"imigrasi.go.id fetch, Google News RSS ID+EN, secondary sources","url":"https://www.imigrasi.go.id/wna/daftar-visa-indonesia/E33G","confidence":2,"data":{"min_income_usd":60000,"duration":"1 year","launched":"2024"},"blocker":"no issuance statistics published in reachable sources; imigrasi.go.id 403 to proxies; archive.org offline"},
 {"id":"michaelpage-id-salary-guide-2026","target":5,"status":"PARTIAL","year":2026,"method":"curl + r.jina.ai live site","url":"https://www.michaelpage.co.id/salary-guide","confidence":3,"data":{"median_yearly_idr_all_sectors":660000000,"salary_dissatisfied_pct":24,"salary_satisfied_pct":72},"blocker":"full role×level tech tables only inside gated interactive tool / lead-gen download; no public PDF"},
 {"id":"kalibrr-job-report","target":6,"status":"FAILED","year":2024,"method":"webfetch + Google News RSS","url":"https://www.kalibrr.com/resources/jobs-report/","confidence":1,"data":null,"blocker":"404; no alternate location found"},
 {"id":"aptiknas-members","target":7,"status":"FAILED","year":null,"method":"curl live + planned archive (archive down)","url":"https://www.aptiknas.org/","confidence":1,"data":null,"blocker":"live domain = parked placeholder page; web.archive.org offline"},
 {"id":"komdigi-dts-recap","target":8,"status":"PARTIAL","year":2026,"method":"curl + jina","url":"https://data.komdigi.go.id/opendata/dataset/jumlah-peserta-kompeten-berdasarkan-akademi","confidence":2,"data":{"dataset_exists":true,"resource":"XLSX updated 2026-11-06"},"blocker":"download URL points to internal RFC1918 host 172.30.103.58:5000 — externally unreachable"},
 {"id":"linkedin-jotr-indonesia-2025","target":9,"status":"PARTIAL","year":2025,"method":"curl raw HTML of LinkedIn talent blog","url":"https://www.linkedin.com/business/talent/blog/talent-acquisition/worlds-fastest-growing-jobs-2025","confidence":4,"data":{"top3":["Travel consultant","Cyber security engineer","Security operations center analyst"],"also_on_list":["Food and beverage supervisor","Psychotherapist/psychologist"],"roles_per_country":15,"method_note":"ranking of fastest-growing roles over 3 years"},"blocker":"full ranked 15 + growth % only in gated LinkedIn Pulse article"}
]
```

## Still-Missing Items

1. Stack Overflow 2025 edition Indonesia rows (2024 retrieved; 2025 raw data link not located — official host dead; if needed, hunt new mirror).
2. Payoneer Indonesia-specific average hourly rate (2022-2024 editions) — not present in retrievable public text; would need the gated full PDFs from discover.payoneer.com.
3. Payoneer 2019 Global Gig Economy Index primary document (Indonesia 50.9% growth claim needs primary confirmation; original PDF URL pubs.payoneer.com/images/q2_global_freelancing_index.pdf known from citation — not attempted yet BUT archive down; live link untested by webfetch — try later).
4. Deel Indonesia contractor/employee counts & growth (gated).
5. Oyster HR report APAC numbers (URL dead).
6. E33G issuance/take-up count (likely unpublished; try imigrasi.go.id press releases or keimigrasian statistics bulletin when reachable, or Kontan/JakartaGlobe when search quota resets).
7. Michael Page Indonesia full technology role×level salary tables (gated interactive tool; try filling the web form / alternate mirrors / Scribd copies later).
8. Kalibrr Job Report 2024/2025 content (page removed).
9. APTIKNAS member count (retry when web.archive.org back online: web.archive.org/web/2023/http://aptiknas.org + news coverage).
10. Komdigi DTS recap XLSX contents (internal-IP download bug on portal; try portal AI assistant or data Permohonan route later).
11. LinkedIn Jobs on the Rise Indonesia 2025 full ranked list 1-15 with growth percentages (gated LinkedIn News Pulse; try again via authenticated browser or LinkedIn News Asia post comments when channels available).

## Files saved (research/downloads/)
- so2024.zip (official 2024 SO survey dataset), survey_results_public.csv (159MB), indonesia_2024.csv (354 IDN rows), 2024 Developer Survey.pdf
- payoneer2015.pdf (+ .txt extraction), payoneer2020.pdf (+ .txt), linkedin.html (LinkedIn talent blog 2025), mp.html, dts.html, e33g*.xml (news RSS)
