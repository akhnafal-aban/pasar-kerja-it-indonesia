# Macro Reports & Workforce Size Estimates — Indonesia IT Workforce Study

Compiled: 2026-11-09. Scope: third-party/macro estimates of Indonesia's IT workforce, digital-economy context, talent-gap claims + methodology scrutiny. All figures tagged [SOURCE :: YEAR :: METHODOLOGY :: URL :: CONFIDENCE 1–5].

---

## Headline Numbers (quick reference)

| Claim | Value | Verdict |
|---|---|---|
| "9M digital talents needed by 2030" (~600k/yr) | 9,000,000 (2015–2030) | Citation chain → J.P. Morgan–McKinsey "New Skills at Work" (2016) via World Bank desk review (2018). NOT a bottom-up labor model. Widely mutated into "McKinsey 2018" and "Kominfo estimate". |
| IMDI 2024 revised need | 12,000,000 by 2030 (gap 3M; ~500k/yr) | Kominfo own model, built on BPS + education-ministry data. **LINEAGE FLAG: BPS-derived.** |
| BPSDM Komdigi latest (2025) | Need ≈456,000 digital talents/yr | Internal BPSDM modeling using BPS data. **LINEAGE FLAG: BPS.** Claimed by officials as "more precise than World Bank/McKinsey." |
| GitHub developer accounts (Indonesia) | 2.9M (2023) → 4.37M (2025), 5.27M (Q1 2026) → projected 8.7M (2030) | Platform accounts, not professional developers. Includes students, hobbyists, multi-account users. |
| Actual working software engineers (Indonesia) | ~236K (LinkedIn profile search, 2023) to ~660K (consultancy claims) | Weak sources; no rigorous public count of *employed professional developers* exists. |
| AI talent | ~28,000 (2019) → ~96,000 (2024); 0.06% of total workforce | LinkedIn-based (Stanford AI Index / partner report). Selection bias: only LinkedIn members. |
| Digital economy GMV | $90B (2024, +13%) → $99B (2025, +14%); 2030: $180–360B | Google–Temasek–Bain modeling; proprietary but methodology published. Most credible macro series. |
| Internet economy professionals (SEA region, 2018) | >100,000, growing ~10%/yr | e-Conomy SEA 2018 estimate for whole region — tiny relative to the "9M" narrative. |

---

## Origin Tracing

### 1. The "9 million digital talents by 2030" claim

**Trace chain (each step discovered in primary documents):**

1. **Deepest traceable origin (2016):** Tan, K. & Tang, J., *"New skills at work: Managing skills challenges in ASEAN-5"* (J.P. Morgan / McKinsey-sponsored series, 2016). This is what a 2018 World Bank project document cites for "the country currently falls short of 9 million ICT-skilled workers."
   - The number appears as **"projected shortage of 9 million skilled and semi-skilled ICT workers 2015–2030"** — a 15-year cumulative net shortfall of *all ICT-related* workers (not "talents", not developers, not jobs).
   - No public methodology of how the 9M was computed was found in derivatives. Flag: the underlying J.P. Morgan/McKinsey estimate is itself not fully public.
   - [J.P. Morgan "New Skills at Work" ASEAN-5 / Tan & Tang :: 2016 :: unknown published methodology; likely macro labor-demand modeling :: cited via World Bank PID doc: https://documents1.worldbank.org/curated/en/594741563369992590/pdf/Concept-Stage-Program-Information-Document-PID-Indonesia-Skills-Development-Project-P166693.pdf :: CONFIDENCE 3 that 9M originates here]

2. **Carrier document (March 2018):** **World Bank, "Preparing ICT Skills for Digital Economy: Indonesia within the ASEAN Context"** — a *Rapid Assessment*, explicitly "desk research and qualitative study methods, carried out Dec 2017–Feb 2018." Its country table states: *"Projected shortage of 9 million skilled and semi-skilled ICT workers 2015–2030."*
   - This is the document Indonesian officials, media, ERIA, MDPI journals, Geekhunter, Jakarta Post etc. all cite as "World Bank 2018."
   - **Methodology verdict: NOT original research.** A 3-month desk/qualitative rapid assessment repeating the 2016 figure. This single line is the origin of Indonesia's most-quoted workforce number.
   - [World Bank :: 2018 :: desk research + qualitative interviews, 3 months :: https://www.almendron.com/tribuna/wp-content/uploads/2022/07/preparing-ict-skills-for-digital-economy.pdf :: CONFIDENCE 5 for identification of this document as the canonical carrier]

3. **Amplification by officials (2019–2024):** Menkominfo Rudiantara (DPR, Jan 2019): "McKinsey sebut gap 2015–2030 ada 9 juta skill… 600 ribu setahun." Menristek Bambang Brodjonegoro (Nov 2019) attributed it to "Bank Dunia dan McKinsey. **Note the mutation**: one figure, two claimed institutional origins, cited loosely by ministers with no primary source.
   - [CNN Indonesia :: 2019 :: ministerial statement in DPR :: https://www.cnnindonesia.com/teknologi/20190116180149-185-361330/indonesia-butuh-cetak-600-ribu-tenaga-ti-tiap-tahun :: CONFIDENCE 5]

4. **Further mutation (2024):** BPSDM Kominfo chief Hary Budiarto said the 9M was from "McKinsey atau WEF di Tahun 2015" — a *third* attribution (World Economic Forum, 2015). No WEF 2015 report containing the 9M figure was located. The misattribution itself is evidence nobody tracked the primary source.
   - [BicaraIndonesia / IMDI 2024 launch :: 2024 :: official statement :: https://bicaraindonesia.id/news/19734/imdi-2024-indonesia-butuh-12-juta-talenta-digital-di-tahun-2030/ :: CONFIDENCE 5 the statement was made]

5. **Updated figure (2024):** Kominfo's own **IMDI 2024** (Indonesia Digital Society Index): need = **12 million by 2030**; universities can supply ~9M; gap ~3M; ~500k/yr to train. Built "berbasis data-data Badan Pusat Statistik dan Kemendikbudristek" — **LINEAGE FLAG: BPS-derived**.
   - [Kominfo IMDI 2024 :: 2024 :: index built on BPS + education ministry data :: https://intimedia.id/read/digital-talent-gap-in-indonesia-kominfo-releases-the-2024-indonesia-digital-society-index :: CONFIDENCE 4]

6. **Latest revision (2025):** BPSDM Komdigi now says need = **456,000/year** (also stated as 458,043/yr earlier, from a "kajian ketersediaan dan kebutuhan talenta digital 2023–2030"), explicitly called *more precise* than the World Bank/McKinsey 600k. Uses "BPS data and internal modeling" — **LINEAGE FLAG: BPS**. DTS program trains only ~100k/yr (budget-capped).
   - [Komdigi BPSDM statements :: 2025 :: internal modeling over BPS data :: https://bpsdm.komdigi.go.id/berita-pengembangan-talenta-digital-dalam-menghadapi-tantangan-pada-era-perubahan-46-1926 and Medcom.id Oct 2025 :: CONFIDENCE 4]

**Verdict: SOLID OR RHETORIC?** → *Political rhetoric built on a thin citation chain.* The 9M is (a) a 15-year cumulative semi-skilled ICT-worker shortage, (b) from a non-public McKinsey/JPM model, (c) carried in a 3-month World Bank desk review, (d) re-attributed three different ways by Indonesian officials, (e) implicitly superseded by Komdigi's own lower 456k/yr figure in 2025 — yet still quoted as "9M needed" in 2026 (e.g., a July 2026 LinkedIn consulting post). Also note definitional inflation: "9 million ICT-skilled workers" ≠ "9 million digital talents" ≠ "9 million developers."

**Related figure (independent):** Korn Ferry Global Talent Crunch 2018: Indonesia TMT (tech/media/telecom) deficit 600K–1.2M by 2030 — an order of magnitude smaller than 9M, exposing how definitions drive the numbers. [Korn Ferry :: 2018 :: global talent-deficit modeling :: cited via https://geekhunter.co/artikel/tech-talent-shortage-in-indonesia/ :: CONFIDENCE 3]

Also: Ministry of Education official Nizam (2021) estimated supply 150–200K IT grads/yr vs 600K/yr need → gap 400–450K/yr; and Digital Workforce Gap study (MDPI, Sustainability 2023) explicitly criticizes the 9M report for not showing year-by-year numbers. [MDPI Sustainability 15(1):754 :: 2022 :: literature review :: https://www.mdpi.com/2071-1050/15/1/754 :: CONFIDENCE 4]

---

## Developer Population Estimates

### GitHub Octoverse (most-cited "Indonesia developer" numbers)
- **2023:** 2.9M+ Indonesian developers on GitHub; +31% YoY growth; 3rd largest community in APAC after India & China; generative-AI projects +213% YoY.
  [GitHub Octoverse 2023 :: 2023 :: platform account/activity data :: https://www.liputan6.com/tekno/read/5453801/github-punya-29-juta-developer-dari-indonesia-terbesar-ketiga-di-asia-pasifik :: CONFIDENCE 4 for count; means accounts]
- **2022:** Indonesia entered GitHub's top 10 communities (#10 in 2021, #9 in 2022–2023).
  [Octoverse 2022 :: https://octoverse.github.com/2022/global-tech-talent :: CONFIDENCE 4]
- **2025:** Indonesia **4.37M accounts**, #8 globally, up 3 places — biggest climb in top 10; developer count more than **quadrupled 2020→2025** (0.9M in 2020); projected **8.7M by 2030** (mean of 5 GitHub forecast models); cited "accounts for nearly half of SEA's online economy". Innovation Graph: 5.27M accounts by Q1 2026.
  [GitHub Octoverse 2025 :: 2025 :: based on GitHub accounts placed by profile location/IP; public-activity metrics :: https://github.blog/news-insights/octoverse/octoverse-a-new-developer-joins-github-every-second-as-ai-leads-typescript-to-1/ + https://www.secondtalent.com/resources/countries-with-most-software-developers/ :: CONFIDENCE 4]
- **Methodology caveat (critical):** counts *GitHub accounts*, not people-who-code-for-pay. Dual accounts, students, note-storage users all inflate it. Indonesian commentary itself notes LinkedIn keyword searches ("software engineer/developer/programmer", Indonesia) yield ~**236K profiles** — a stark reality check on "2.9M developers."
  [Safar Septyadi blog :: 2024 :: LinkedIn keyword search, unverified :: https://safarseptyadi.com/jumlah-programmer-indonesia-meningkat-pesat-menempati-9-di-dunia/ :: CONFIDENCE 2]

### SlashData Developer Nation
- Global: **48.4M developers (Q3 2025)**; 2025 growth 10%/yr. Methodology: bottom-up model calibrated on GitHub + Stack Overflow accounts/activity + US/EU **employment statistics**, weighted against their own 10k+/wave survey (29 waves). Explicitly: no pageview/download proxies, no cross-country extrapolation from US/EU employment stats.
  [SlashData :: 2025 :: survey (10k+/wave) calibrated to activity indicators :: https://www.slashdata.co/research/developer-population + https://www.slashdata.co/blog/global-developer-population-trends-2025 :: CONFIDENCE 4 for global; Indonesia NOT published per-country]
- Indonesia granularity (2022 blog): "rest of East Asia" = 9% of global developer population; **Indonesia = 32% of rest-of-East-Asia** developers (largest in that group, ahead of Japan 21%). With global ~27M (2022), implied Indonesia ≈ **~0.75–0.8M developers (2022) — derived, not published**. Also: Indonesian devs learn via avg 3 methods; highest self-taught/online-course/bootcamp usage in East Asia.
  [SlashData blog :: 2022 :: survey share × regional extrapolation :: https://www.slashdata.co/blog/china-and-the-rest-of-east-asia-developer-market :: CONFIDENCE 3 for the 32% share; CONFIDENCE 2 for my derived absolute]
- **Note:** SlashData's country-level data is paid; the derived ~0.8M (probably 1–1.5M by 2025 given growth) is the best defensible "people actively coding" estimate, far below the 4.37M GitHub-account figure and far above the 236K LinkedIn-profile figure.

### Evans Data Corporation
- Publishes *Worldwide Developer Population Report* (39th edition, 2025; 5-yr forecasts, country-level incl. Top 15 countries). Global ~27M (2024) — **professional developers** only. Methodology: secondary data + proprietary statistical model + semi-annual Global Development Survey (185k-member panel).
  [Evans Data :: 2024/2025 :: proprietary model + survey panel :: https://evansdata.com/devpopulation + http://www.evansdata.com/press/viewRelease.php?pressID=365 :: CONFIDENCE 3]
- **Indonesia-specific count is paywalled and was not found in public sources.** Data gap — do not cite Evans numbers for Indonesia without purchasing the report.

### Stack Overflow Developer Survey
- Indonesia respondents: **2021: 632 (0.76% of 83,439)** · **2024: 351 (0.6% of 65,437)** · **2025: 180 (0.5% of ~49,019)**. Trend: shrinking Indonesian share while global respondent base shrank too; self-selected sample skews to English-speaking, high-income countries; no country weights.
  [Stack Overflow Developer Survey :: 2021/2024/2025 :: self-selected online survey, unweighted :: https://survey.stackoverflow.co/2021/ , https://survey.stackoverflow.co/2024/developer-profile , https://survey.stackoverflow.co/2025/developers :: CONFIDENCE 4 for counts; survey not representative of Indonesia]
- No Indonesia median salary published in the public country tables (only US and a few markets appear in compensation analyses; n=180 is too small). **Data gap.**

### Local/other estimates
- **Access Partnership / Google Play "app economy" (2023):** ~10,000 app-developer *companies* in Indonesia; 42,000 local Android apps; **162,000 app-economy jobs** (≈36,000 direct technical devs, 36,000 indirect, 90,000 spillover).
  [Access Partnership for Google :: 2023 :: economic-impact modeling :: https://www.cnbcindonesia.com/tech/20230911161150-37-471439/google-beberkan-penghasilan-developer-aplikasi-di-ri-cek :: CONFIDENCE 3]
- **ASPIlUKI/PANDI (Aug 2026):** "jumlah developer Indonesia diperkirakan ~2 juta" + app-sector investment Rp54.18T (2025). No methodology given — likely second-hand or GitHub-influenced.
  [ASPIlUKI/Detik/Antara :: 2026 :: no methodology :: https://inet.detik.com/business/d-8620672/ri-punya-2-juta-developer-mengapa-produk-teknologi-lokal-belum-mendunia :: CONFIDENCE 2]
- **Consulting claim (2026, LinkedIn):** ~660K working professional software engineers, 36% in Greater Jakarta, fresh-grad cost ~USD 11K/yr — source/methodology undisclosed.
  [LinkedIn post (Adam Li) :: 2026 :: undisclosed, references GitHub data :: CONFIDENCE 1]
- **Historical:** Kominfo DG Semuel (2017): 1,000 quality startups need ~100k quality programmers. Access Partnership's job counts and the LinkedIn ~236K suggest actual professional core is **low hundreds of thousands**, not millions.

**Contradiction summary (developer population):** 236K (LinkedIn profile search) < ~660K (consultant) / ~800K (SlashData-derived 2022) < 2M (Aspiluki, no method) < 4.37M (GitHub accounts 2025). The spread is ~20×; definitional chaos (accounts vs coders vs professionals) fully explains it.

---

## Digital Economy Context (Google–Temasek–Bain e-Conomy SEA)

**Methodology (published in report):** multi-year research program (Google+Temasek since 2016, Bain lead partner since 2019); leverages Temasek insights, Bain analysis, Google Trends, third-party research-partner data, expert interviews, consumer survey via Kantar (~7,900 SEA respondents; e.g. 2023 wave Aug–Sep 2023), VC investor survey. GMV ≠ GDP: transaction value of e-commerce, transport/food, online travel, online media + digital financial services GTV separately.

- **e-Conomy SEA 2024:** Indonesia GMV **$90B (+13% YoY)**, largest in SEA (≈34% of SEA-6 $263B). E-commerce $65B (+11%); transport+food $9B (+13%); travel $9B (+24%); media $8B (+12%). Digital payments GTV $404B (largest in SEA); digital lending $9B. 2030: **$200–360B**. Data-center capacity planned +268% (202MW). H1-2024 funding: $300M/51 deals; 65% of investors expect funding to rise 2025–30.
  [Google–Temasek–Bain :: 2024 :: Bain modeling + research-partner data + Kantar survey :: https://services.google.com/fh/files/misc/indonesia_e_conomy_sea_2024_report.pdf :: CONFIDENCE 4]
- **e-Conomy SEA 2025:** Indonesia GMV **≈$99B ("cusp of $100B", +14%)**; still largest in SEA. E-commerce $71B (+14%, from revised $62B 2024 base). **Revision note: 2024 e-commerce restated down from $65B to $62B** — the series gets revised annually. Travel $9B (+11%); transport+food $10B (+13%); online media $9B (+16%, fastest). Digital payments GTV $538B (+27%); lending $13B (+29%). 2030 floor: **$180–340B**.
  [Google–Temasek–Bain :: 2025 :: same methodology :: https://services.google.com/fh/files/misc/indonesia_e_conomy_sea_2025_report.pdf + https://blog.google/intl/id-id/company-news/outreach-initiatives/e-conomy-report-2025-indonesia/ :: CONFIDENCE 4]
- **Talent chapters:** e-Conomy SEA 2018: internet economy employs **>100K skilled professionals across SEA**, growing ~10%/yr (whole region!) — a sobering comparator to Indonesia's "9M" narratives. 2021 edition: "Talent, especially shortage of technical talent, remains a challenge"; 68% of SEA tech hiring managers took >3 months to fill tech roles; 70% said shortage slowed product dev (2021 survey).
  [e-Conomy SEA 2018/2021 :: survey of tech hiring managers :: https://www.thinkwithgoogle.com/_qs/documents/6847/Report_e-Conomy_SEA_2018_by_Google_Temasek2.pdf , https://www.bain.com/globalassets/noindex/2021/e_conomy_sea_2021_report.pdf :: CONFIDENCE 3]
- **Salary data (startup sector):** Glints × Monk's Hill SEA Tech Talent Report 2023/24 (10,000+ data points + 72-startup survey): Indonesia junior engineer salaries −7% YoY (layoffs), senior engineers +2–3%; engineering still pays ~29% premium vs non-tech; DevOps/ML/AI/cloud command premiums; Indonesia senior full-stack pay 3.8× lower than Singapore.
  [Glints × MHV :: 2024 :: proprietary salary dataset from platform :: https://assets-global.website-files.com/...SEASTTR%202024.pdf :: CONFIDENCE 3]

---

## AI Shift (2025–2026)

- **WEF/LinkedIn "Jobs on the Rise 2025 Indonesia":** top-3 fastest-growing roles (ranking of hiring growth Jan 2022–Jul 2024, LinkedIn member job-starts): **Travel Consultant, Cyber Security Engineer, SOC Analyst**. Rest of top 15: behavioral therapist, F&B director, BIM modeler/engineer, sales AM, personal trainer, piping engineer, 3D designer, quality supervisor, audit supervisor, project manager, credit officer. **No AI role tops Indonesia's 2025 list** (unlike global list, where AI Engineer is #1). Tech presence = security roles only.
  [LinkedIn Jobs on the Rise 2025 (published by LinkedIn/covered by WEF press) :: 2025 :: Economic Graph member job-start growth ranking :: https://www.kompas.com/edu/read/2025/01/15/165201771/15-pekerjaan-dengan-lowongan-terbanyak-di-indonesia-versi-linkedin :: CONFIDENCE 4]
- **LinkedIn Grad Guide 2025:** fastest-growing grad career paths in Indonesia (Jan 2022–Dec 2024): **#1 AI Engineer**, #2 SOC Analyst, #3 Environmental Health Safety Specialist.
  [LinkedIn :: 2025 :: same Economic Graph method :: cited via https://www.idnresearchinstitute.com/english/indonesia-s-job-market-employment-confidence-index-falls-00-314l1-mt4n5g :: CONFIDENCE 3]
- **Stanford HAI AI Index 2025:** Indonesia **AI-talent concentration +191% (2016–2024)** — share of LinkedIn members with ≥2 AI skills or AI job; 10th of 15 shown. Stanford itself cautions Indonesia has low LinkedIn coverage of workforce (with India, Korea, Hungary).
  [Stanford HAI AI Index 2025, Fig 4.2.18 :: 2025 :: LinkedIn member data :: via https://www.idnresearchinstitute.com/english/indonesia-s-job-market-employment-confidence-index-falls-00-314l1-mt4n5g :: CONFIDENCE 3 with explicit coverage caveat]
- **Stanford HAI AI Index 2026:** Indonesia AI-talent concentration **+108% (2019–2025)**, 6th fastest globally, **fastest relative AI-hiring growth in the world in 2025 (+31.7%)** (AI hires vs all-hires growth). Note: concentration ≠ headcount; base small.
  [AI Index 2026 :: 2026 :: LinkedIn Economic Graph :: https://aiadoption.org/data/ai-talent-concentration-growth/ + https://www.secondtalent.com/resources/asia-ai-hiring-outlook-2027/ :: CONFIDENCE 4]
- **AI talent headcount (Indonesia):** ~**28,000 (2019) → 96,000 (2024)**; = 0.06% of total workforce (vs Malaysia 0.08%, Singapore 0.12%, US 0.16%); >70% of Indonesian AI talent is reskilled from other professions; 10 universities have dedicated AI programs.
  [LinkedIn-based partner report (per Kompas.id, Dec 2025) :: 2024/2025 :: LinkedIn profile data :: https://www.kompas.id/artikel/en-berdaulat-dengan-talenta-ai-indonesia :: CONFIDENCE 3]
- **Government/industry AI programs:** elevAIte Indonesia (Komdigi×Microsoft, Dec 2024): target 1M AI-skilled talents; hit 1.2M in 8 months; renamed Microsoft Elevate targeting 500K certified by 2026. Indosat IndigoCampID → IDCamp AI tracks (440–456 hrs). Indonesia 3rd-largest ChatGPT users globally (129M, 45% of population, per same report — **this ChatGPT figure looks implausibly high vs official 204.7M internet users; treat with suspicion**).
  [Microsoft News Indonesia :: 2024–2026 :: program self-reporting :: via idnresearchinstitute + kompas.id :: CONFIDENCE 3]
- **e-Conomy SEA 2025 AI chapter (Indonesia):** 80% of Indonesian AI users interact daily (2nd highest in SEA); **AI-app revenue +127% H1-2024→H1-2025, highest in SEA**; 79% of workers actively upskilling AI; AI funding only $91M vs Singapore $1.31B; 45+ AI startups vs Singapore 495+.
  [Google–Temasek–Bain :: 2025 :: app-marketplace revenue data + surveys :: Indonesia country report PDF :: CONFIDENCE 4]

---

## Multilateral Institution Reports

- **World Bank "Preparing ICT Skills…" (2018)** — covered above; the 9M carrier. [CONFIDENCE 5 identified]
- **World Bank "Beyond Unicorns: Harnessing Digital Technologies for Inclusion in Indonesia" (2021):** big-data + survey-based analyses (incl. online job platform data). Key numbers: gig workers +6.2% hourly earnings vs informal peers; 49 hrs/wk; 13.2M workers (10.4% of employed) engaged in e-commerce (2019); 71% of e-commerce sellers sell only via social/chat; gig work: 85% male, 87% urban, 69% transport sector; 33% of gig jobs are first jobs. **Uses its own survey + platform data, some labor stats from official Indonesian sources — mixed lineage.**
  [World Bank :: 2021 :: household/firm surveys + online platforms data :: https://documents1.worldbank.org/curated/en/321071627050744463/pdf/Beyond-Unicorns-Harnessing-Digital-Technologies-for-Inclusion-in-Indonesia.pdf :: CONFIDENCE 4]
- **World Bank "Services Competitiveness for Growth and Jobs in Indonesia" (2026, Lakatos et al.):** current flagship on services incl. digital skills. [https://documents1.worldbank.org/curated/en/099011526034524340/pdf/P506981-dd17a3b9-e242-47e9-9f9d-904833cbe12b.pdf :: not yet content-mined → CONFIDENCE 2]
- **World Bank India-adjacent estimate (via World Bank survey 2019, cited in Caribou/.Caribou report):** ≥1.2M Indonesians in gig work; ~13M in e-commerce. [World Bank high-frequency survey :: 2019 :: survey :: Caribou PDF :: CONFIDENCE 3]
- **ADB:** Marsela, N.M.K. & Limbongan, K., *Indonesian ICT Workers: Determinants and Strategy to Support National Digital Transformation* (ADB, 2021); ERIA *Accelerating Digital Transformation Indonesia* (2022) re-uses the World Bank 9M figure (illustrating circular citation risk in multilateral literature). [https://www.eria.org/uploads/Accelerating-Digital-Transformation-Indonesia-rev3.pdf :: CONFIDENCE 3]
- **Key contradiction — multilateral implementation:** the most concrete labor-market data World Bank published for Indonesia (e-Conomy-era analyses, "Fire" job-posting database) points to an ICT professional base in the **hundreds of thousands**, not the millions implied by the 9M/12M gap narratives that the same institution helped popularize.

---

## Freelance / Remote Economy (macro)

- **Registered online-freelance profiles (9 platforms, web-crawled Oct 2018):** 171,033 Indonesian profiles — Fiverr 837 / Upwork 13,945 / Projects.co.id 115,558 / Freelancer 16,639 / Sribulancer 9,841 / Fastwork 1,456 / Guru 11,276 / PeoplePerHour 464 / Microworkers 1,017. **Only 2,062 (1.2%) active in prior 28 days.**
  [Sucahyo et al. via DIODE network :: 2018-10 :: web scraping (verifiable method, small sample periods) :: https://diode.network/2019/10/15/numbers-type-and-income-of-online-gig-workers-in-indonesia/ :: CONFIDENCE 4; data is stale]
- **Upwork-specific:** ~189,000 Sribulancer registered freelancers (2016, per RAND-World Bank Perspective); RAND (2017) profiled online outsourcing for Indonesia youth: ~1M registered users on Freelancer.com (2016) and, per Sribulancer reports, ~189,000 users; Elance-oDesk: Indonesia 2nd-highest freelancers-per-capita in EAP after Philippines (2013). LSE study: **fewer than 10,000 searchable Indonesian Upwork profiles ever earned ≥$1**; 169 earned >$100k; concentration of active profiles: software dev/tech 37%; design/creative 35%; writing/translation 13%.
  [RAND PE-271 :: 2016 :: platform registration data + interviews :: https://www.rand.org/content/dam/rand/pubs/perspectives/PE200/PE271/RAND_PE271.pdf :: CONFIDENCE 3; LSE blog :: 2023 :: Upwork scrape + earnings analysis :: https://blogs.lse.ac.uk/seac/2023/11/13/the-gig-economy-as-a-stepping-stone-career-trajectories-of-online-platform-workers-in-indonesia/ :: CONFIDENCE 3]
- **Platform livelihoods (Caribou/Caribou Digital–Mastercard Center, 2025):** 2022 order-of-magnitude: ~**20M** Indonesians earn at least some income from online marketplaces/platforms; ~**4.5M do so exclusively**; ~**2.25M active gig workers (delivery/ride-hail, mostly GoTo/Grab, non-exclusive overlap)**; ~171K freelancer profiles (re-survey per Sucahyo 2019).
  [Caribou Digital :: 2024/25 :: platform-public reports triangulated + fiduciary sources :: https://caribou.global/wp-content/uploads/2025/04/Indonesia-report-Final-Master-for-Web-1.pdf :: CONFIDENCE 3; authors themselves call platform self-reports unreliablegiatan aggregation]
- **Local platforms now:** Sribu.com: 1.38M cumulative users/freelancers (Apr 2025, 13 yrs operation). Fastwork numbers not published in found sources (data gap).
  [Sribu.com via Bisnis.com :: 2025 :: platform self-report, cumulative signups :: https://ekonomi.bisnis.com/read/20250422/12/1871086/tren-jasa-freelancer-di-sribucom-meningkat-di-tengah-badai-phk :: CONFIDENCE 3]
- **BPS "freelance/pkerja lepas" count (flagged):** 13.6M "freelancers" (Feb 2026) and 46.47M (2023) — **INEAGE FLAG: BPS, definition is "people who work for others on a non-permanent basis, ag & non-ag"** — i.e., casual/informal day laborers riding-hailing etc., NOT digital freelancers. Banned-as-primary; listed only to document the definitional mismatch when media call these "freelancers."
  [BPS via Databoks :: 2026 :: BPS Sakernas labor-force survey — methodology includes survey design but definition mismatch for gig economy :: https://databoks.katadata.co.id/en/employment/statistics/6a3dd8b1c7e23/ :: CONFIDENCE 2 for any digital-freelancer interpretation]
- **Remote work macros:** (a) JobStreet×BCG "Decoding Global Talent 2024" (n=19,154 Indonesian workers; 150k global): **71% of Indonesian workers willing to remote-work for foreign employers** (up from 55% in 2020). (b) Logitech Hybrid Work Survey Indonesia 2023 (n=500 white-collar): 62% prefer hybrid, 21% full remote, 16% full office. (c) JobStreet Hiring/Comp/Benefits 2024 (n=1,180 TA pros): 61% of companies still required daily office in 2023, hybrid shift expected. (d) HP Work Relationship Index 2024 (n=1,000 Indonesian knowledge workers): 96% would trade ~14–15% salary for WFA/flexibility.
  [JobStreet/BCG :: 2024 :: online panel survey :: https://www.tempo.co/ekonomia/minat-pekerja-indonesia-ke-luar-negeri-turun-71-persen-pekerja-pilih-remote-working-49849 :: CONFIDENCE 3; Logitech :: 2023 :: n=500 online survey :: PDF link :: CONFIDENCE 3; HP :: 2024 :: n≥1,000/12-country survey :: https://tekno.kompas.com/read/2024/09/25/09010057/riset-96-persen-karyawan-di-indonesia-rela-potong-gaji-demi-bisa-wfa :: CONFIDENCE 3]
- Buffer Remote Work Report does not publish an Indonesia country cut in sources found (their surveys are ~70% US/EU). Data gap.

---

## Methodology Assessment

| Source | Method transparency | Coupling to reality | Verdict |
|---|---|---|---|
| World Bank rapid assessment 2018 | Cites prior est, no primary computation | Reproduces a 2016 consultancy number; became the canonical national statistic | **Weak; desk-research citation, not research** |
| McKinsey Digital Archipelago 2018 | Provides case-study + survey detail, but online-commerce "26M jobs supported (2022)" later out by 2× — such projections are directional | Impact modeling around consumer surveys; e-commerce-to-jobs estimate ($65B by 2022; actual e-commerce GMV ~ $60B-ish by 2024) **overshot 2022 target by ~2 years at half the size** | **Directional only** |
| GitHub Octoverse 2023/2025 | **High** (public tool: Innovation Graph; placement by location/IP) | Measures accounts/activity, not paid developers — systematically overcounts "developers" as commonly read | **Good for platform trend; misuse risk high** |
| SlashData | High-on-paper methodology (direct-activity calibration, per-region survey weights), paid source | Only provider that attempts "people who code" globally; Indonesia only inferable via rest-of-East-Asia (32% share) — **derived number only usable with caveat** | **Best-in-class but Indonesia granularity poor (my derived ~0.8M 2022)** |
| Evans Data | Methodology described in promo material; proprietary model | n/a for Indonesia — paywalled country cuts | **Data gap** |
| Stack Overflow Survey | Public methodology: self-selected, unweighted | Non-representative, tiny n for Indonesia (180–632 respondents) — descent trend likely reflects survey reach, not dev population | **Not usable to size workforce** |
| e-Conomy SEA 2024/2025 | Published multi-method | Revises retroactively (2024 e-commerce $65B → later restated $62B); only 6 sectors; GMV ≠ value-add | **Useful, transparent, volatile ±5%** |
| Komdigi IMDI 2024/2025 | Own survey (18k individuals + 11k firms 2025) 4-pillar G20 Toolkit framework, G20 Toolkit definition set | 2024's "12M needed by 2030" is **demand-projection modeling built on BPS + Kemendikbudristek data**, not survey counts. 2025's 456K/yr is internal BPSDM modeling on BPS data. **LINEAGE FLAG: BPS** | **Government policy instrument, not independent measure** |
| LinkedIn/Stanford AI Index | Published but LinkedIn-membership only; Stanford itself flags Indonesia low LinkedIn coverage | Reveals rate-of-change not absolute counts; concentration metric explicitly non-census | **Useful trend signal only, with coverage bias** |
| Access Partnership (for Google) | Explicit modeling, self-serve counts | Roughly comparable to LinkedIn-profile range (~36K direct technical jobs in app economy) | **Moderate; sector-scope narrow** |
| JobStreet/BCG, Logitech, HP surveys | Sample sizes/dates published | Attitudes of online white-collar populations | **Snapshot sentiment data only** |
| BPS freelancers (13.6M) | Survey-based labor stats body but definition mismatch, banned per project rules | Weekday informal workers, not digital gig | **Banned / lineage-flagged wherever multilateral reports lean on it** |

**Overall conclusion:** Indonesia's IT workforce has **no single credible point estimate**. Defensible range: ~250K–1M *working professional* developers (LinkedIn search 236K; app-economy 36K direct; SlashData-derived ~0.8M; consultant 660K), with **~4.4M GitHub accounts (2025)** marking the very wide aspirational top of the funnel. The famous 9M gap is a repurposed 2016 consultancy estimate of cumulative 15-year shortfall in *semi-skilled ICT workers* — use for narrative only, never as data.

---

## JSON (machine-readable)

```json
[
  {"id":"origin-9m","claim":"Indonesia needs 9M digital talents by 2030 (~600k/yr)","source":"J.P. Morgan/McKinsey 'New Skills at Work' ASEAN-5 (Tan & Tang); carried by World Bank 'Preparing ICT Skills for Digital Economy: Indonesia within ASEAN Context'","year":[2016,2018],"methodology":"non-public consultancy labor-demand model; WB carrier was 3-month desk research + qualitative; counts cumulative 2015-2030 shortage of skilled AND semi-skilled ICT workers","url":"https://www.almendron.com/tribuna/wp-content/uploads/2022/07/preparing-ict-skills-for-digital-economy.pdf","confidence":3,"verdict":"weak citation chain; widely misattributed (McKinsey 2018 / WEF 2015 / Kominfo)"},
  {"id":"imdi-12m","claim":"Indonesia needs 12M digital talents by 2030","source":"Kominfo IMDI 2024","year":2024,"methodology":"Kominfo model built on BPS + Kemendikbudristek data; ~9M supplyable by universities, gap 3M, ~500k/yr","url":"https://intimedia.id/read/digital-talent-gap-in-indonesia-kominfo-releases-the-2024-indonesia-digital-society-index","confidence":4,"lineage_flag":"BPS-derived","verdict":"government demand-projection; supersedes 9M in official use"},
  {"id":"bpsdm-456k","claim":"Indonesia needs ~456,000 digital talents per year","source":"BPSDM Komdigi internal study","year":[2024,2025],"methodology":"internal BPSDM modeling using BPS data (described as more precise than WB/McKinsey)","url":"https://bpsdm.komdigi.go.id/berita-pengembangan-talenta-digital-dalam-menghadapi-tantangan-pada-era-perubahan-46-1926","confidence":4,"lineage_flag":"BPS"},
  {"id":"gh-octoverse-2023","claim":"2.9M Indonesian developers on GitHub, +31% YoY, 3rd in APAC","source":"GitHub Octoverse 2023","year":2023,"methodology":"platform accounts (placement by profile location/IP)","url":"https://www.liputan6.com/tekno/read/5453801/","confidence":4,"caveat":"accounts not paid developers"},
  {"id":"gh-octoverse-2025","claim":"4.37M Indonesian GitHub accounts 2025 (#8 globally), quadrupled since 2020, projected 8.7M by 2030; 5.27M by Q1 2026","source":"GitHub Octoverse 2025 / Innovation Graph","year":[2025,2026],"methodology":"account-based, 5-model forecast mean for 2030","url":"https://github.blog/news-insights/octoverse/octoverse-a-new-developer-joins-github-every-second-as-ai-leads-typescript-to-1/","confidence":4,"caveat":"see above"},
  {"id":"slashdata-id","value":"Indonesia = 32% of 'rest of East Asia' developer population; derived absolute ~0.8M in 2022 (global 48.4M by Q3 2025; Indonesia per-country count NOT published)","source":"SlashData Developer Nation","year":[2022,2025],"methodology":"bottom-up global model calibrated on GitHub/Stack Overflow activity + US/EU employment stats + 10k+/wave weighted surveys","url":"https://www.slashdata.co/blog/china-and-the-rest-of-east-asia-developer-market","confidence":3,"caveat":"Indonesia absolute derived by me from region shares"},
  {"id":"evans","value":"Evans Data publishes per-country developer counts (incl. Indonesia) but paywalled; global ~27M professional devs 2024","source":"Evans Data Worldwide Developer Population Report","year":[2024,2025],"methodology":"proprietary model + semi-annual Global Development Survey (185k panel)","url":"https://evansdata.com/devpopulation","confidence":3,"note":"data gap for Indonesia specifics"},
  {"id":"so-survey","value":"Stack Overflow respondents from Indonesia: 632 (2021, 0.76%), 351 (2024, 0.6%), 180 (2025, 0.5%)","source":"Stack Overflow Developer Survey","year":[2021,2024,2025],"methodology":"self-selected unweighted online survey","url":"https://survey.stackoverflow.co/2025/developers","confidence":4,"caveat":"not representative; no IDN salary published"},
  {"id":"linkedin-236k","claim":"~236K Indonesian software engineer/developer/programmer LinkedIn profiles (2023 keyword search)","source":"Indonesian tech blogger via LinkedIn search","year":2023,"methodology":"LinkedIn keyword search count — informal, unreproducible","url":"https://safarseptyadi.com/jumlah-programmer-indonesia-meningkat-pesat-menempati-9-di-dunia/","confidence":2},
  {"id":"app-economy","claim":"10,000 app-dev companies; 162,000 app-economy jobs (36K direct technical)","source":"Access Partnership for Google","year":2023,"methodology":"economic-impact modeling + app-store data","url":"https://www.cnbcindonesia.com/tech/20230911161150-37-471439/","confidence":3},
  {"id":"ai-talent-count","value":"AI talent ~28K (2019) → ~96K (2024), 0.06% of workforce; >70% reskilled","source":"LinkedIn-based report (per Kompas.id)","year":[2019,2024],"methodology":"LinkedIn member profiles","url":"https://www.kompas.id/artikel/en-berdaulat-dengan-talenta-ai-indonesia","confidence":3,"caveat":"LinkedIn coverage of Indonesian workforce is low (flagged by Stanford HAI)"},
  {"id":"ai-index-2025","value":"+191% AI talent concentration growth 2016–2024 (10th of 15)","source":"Stanford HAI AI Index 2025","year":2025,"methodology":"LinkedIn concentration (share of members with ≥2 AI skills or AI job)","url":"via https://www.idnresearchinstitute.com/english/indonesia-s-job-market-employment-confidence-index-falls-00-314l1-mt4n5g","confidence":3},
  {"id":"ai-index-2026","value":"+108% AI talent concentration 2019–25 (6th globally); +31.7% relative AI hiring growth 2025 — highest in world","source":"Stanford HAI AI Index 2026 / LinkedIn Economic Graph","year":2026,"url":"https://aiadoption.org/data/ai-talent-concentration-growth/","confidence":4,"caveat":"concentration ratio, not headcount"},
  {"id":"jobs-on-rise-id","claim":"Top fastest-growing roles Indonesia 2025: Travel Consultant, Cyber Security Engineer, SOC Analyst (AI Engineer #1 for grads only)","source":"LinkedIn Jobs on the Rise 2025 Indonesia","year":2025,"methodology":"LinkedIn Economic Graph job-start growth ranking (2022-01 to 2024-07)","url":"https://www.kompas.com/edu/read/2025/01/15/165201771/","confidence":4},
  {"id":"econsea-2024","value":"Indonesia digital economy GMV $90B 2024 (+13%), e-comm $65B, 2030 $200-360B","source":"Google-Temasek-Bain e-Conomy SEA 2024","year":2024,"methodology":"Bain analysis + research partners + Kantar consumer survey + investor interviews","url":"https://services.google.com/fh/files/misc/indonesia_e_conomy_sea_2024_report.pdf","confidence":4},
  {"id":"econsea-2025","value":"GMV ≈$99B 2025 (+14%); e-comm $71B (2024 restated to $62B); payments GTV $538B; AI-app revenue +127%; 80% daily AI use","source":"e-Conomy SEA 2025","year":2025,"methodology":"same multi-method","url":"https://services.google.com/fh/files/misc/indonesia_e_conomy_sea_2025_report.pdf","confidence":4},
  {"id":"econsea-2018-talent","value":">100K skilled internet-economy professionals across all SEA (2018), growing ~10%/yr","source":"e-Conomy SEA 2018","year":2018,"url":"https://www.thinkwithgoogle.com/_qs/documents/6847/Report_e-Conomy_SEA_2018_by_Google_Temasek2.pdf","confidence":3,"note":"order of magnitude vs '9M Indonesia' claim"},
  {"id":"mckinsey-archipelago","claims":["online commerce to support ~26M jobs by 2022","$65B online commerce revenue by 2022","$150B digital GDP impact 2025 (2016 report)"],"source":"McKinsey 'The Digital Archipelago' (2018) / 'Unlocking Indonesia's Digital Opportunity' (2016)","year":[2016,2018],"methodology":"consumer survey + macro modeling; actual 2022 e-commerce ~$60B-ish → revenue/gmv projection ~2 years late / low","url":"https://www.mckinsey.com/~/media/mckinsey/featured%20insights/asia%20pacific/the%20digital%20archipelago%20how%20online%20commerce%20is%20driving%20indonesias%20economic%20development/the-digital-archipelago-how-online-commerce-is-driving-indonesias-economic-development.pdf","confidence":4,"verdict":"directional only"},
  {"id":"kornferry","claim":"Indonesia TMT talent deficit 600K-1.2M by 2030","source":"Korn Ferry Global Talent Crunch","year":2018,"methodology":"global supply-demand model","url":"https://geekhunter.co/artikel/tech-talent-shortage-in-indonesia/","confidence":3},
  {"id":"gig-profiles","value":"171,033 Indonesian freelancer profiles across 9 platforms (Oct 2018); only 2,062 (1.2%) active in prior 28 days; Upwork: 13,945 profiles / 449 active","source":"Sucahyo et al. (DIODE)","year":2018,"methodology":"web scraping of Upwork/Fiverr/Sribulancer/Fastwork etc.","url":"https://diode.network/2019/10/15/numbers-type-and-income-of-online-gig-workers-in-indonesia/","confidence":4,"note":"data stale (2018)"},
  {"id":"upwork-active","value":"<10,000 searchable Indonesian Upwork profiles with ≥$1 earnings; 169 above $100K; software-dev 37% of IDN freelancers","source":"LSE blog study (Permana)","year":2023,"methodology":"Upwork scrape/earnings analysis","url":"https://blogs.lse.ac.uk/seac/2023/11/13/the-gig-economy-as-a-stepping-stone-career-trajectories-of-online-platform-workers-in-indonesia/","confidence":3},
  {"id":"platform-livelihoods","claims":["~20M Indonesians earn some income via platforms (2022)","~4.5M exclusively","~2.25M active ride-hail/delivery gig workers"],"source":"Caribou Digital / Mastercard Center report","year":[2022,2024],"methodology":"triangulation of platform self-reports + World Bank surveys (author-acknowledged unreliable platform numbers)","url":"https://caribou.global/wp-content/uploads/2025/04/Indonesia-report-Final-Master-for-Web-1.pdf","confidence":3},
  {"id":"bps-freelance-flag","value":"BPS: 13.6M 'freelancers' (Feb 2026); 46.47M (2023)","source":"BPS Sakernas","year":[2023,2026],"methodology":"national labor-force survey; definition = non-permanent workers incl. agriculture (informal casual labor, NOT digital freelancers)","url":"https://databoks.katadata.co.id/en/employment/statistics/6a3dd8b1c7e23/","confidence":2,"verdict":"BANNED per project rules; flagged for definitional misuse"},
  {"id":"remote-71pct","value":"71% of Indonesian workers willing to remote-work for foreign employers (55% in 2020)","source":"JobStreet×BCG×The Network 'Decoding Global Talent 2024'","year":2024,"methodology":"global online panel survey, n=19,154 Indonesian (of 150k+)","url":"https://www.tempo.co/ekonomia/minat-pekerja-indonesia-ke-luar-negeri-turun-71-persen-pekerja-pilih-remote-working-49849","confidence":3},
  {"id":"logitech-hybrid","value":"62% prefer hybrid / 21% fully remote / 16% fully office","source":"Logitech Hybrid Work Trend Insights Indonesia 2023","year":2023,"methodology":"online survey n=500 Indonesian white-collar","url":"https://info.logitech.com/rs/201-WGH-889/images/Logitech-Hybrid-Work-Trend-Insights-Indonesia-2023.pdf","confidence":3},
  {"id":"hp-wri","value":"96% of Indonesian knowledge workers would trade 14-15% of salary for flexibility/WFA","source":"HP Work Relationship Index 2024","year":2024,"methodology":"survey n=1,000 IDN knowledge workers + 200 IT + 100 leaders","url":"https://tekno.kompas.com/read/2024/09/25/09010057/","confidence":3},
  {"id":"glints-salary","value":"Indonesia junior engineer salaries -7% YoY 2023, senior +2-3%; tech premium +29% vs non-tech","source":"Glints×Monk's Hill SEA Startup Tech Talent Report 2023/24","year":2023,"methodology":"proprietary salary dataset 10,000+ data points + 72-startup survey","url":"https://assets-global.website-files.com/...SEASTTR%202024.pdf","confidence":3},
  {"id":"wb-beyond-unicorns","claims":["Internet-using gig workers earn +6.2%/hr vs informal peers, 49 hrs/wk","13.2M Indonesians (10.4% of employed) engaged in e-commerce (2019)","71% sell only via social/chat"],"source":"World Bank, Beyond Unicorns: Harnessing Digital Technologies for Inclusion in Indonesia","year":2021,"methodology":"household/firm surveys + online platform data; some official-stats lineage","url":"https://documents1.worldbank.org/curated/en/321071627050744463/pdf/Beyond-Unicorns-Harnessing-Digital-Technologies-for-Inclusion-in-Indonesia.pdf","confidence":4,"lineage_flag":"mixed official statistics"},
  {"id":"aspiiluki-2m","claim":"~2M developers in Indonesia","source":"ASPIlUKI/PANDI statements (developerday.id launch)","year":2026,"methodology":"none given","url":"https://inet.detik.com/business/d-8620672/","confidence":2,"verdict":"no methodology; probably GitHub-influenced"},
  {"id":"dts-100k","value":"Digital Talent Scholarship trains ~100k/yr (budget-capped)","source":"Kominfo/Komdigi (program data)","year":[2022,2025],"methodology":"program completion counts","url":"https://www.cnnindonesia.com/teknologi/20241014092531-185-1154998/kominfo-klaim-talenta-digital-indonesia-melonjak-di-era-jokowi","confidence":3,"note":"output metrics only; excludes quality/outcome evidence"}
]
```

---

## Data Gaps

1. **No professional developer headcount for Indonesia with public methodology.** Evans Data has one (paywalled); SlashData publishes regions not countries. Best triangulation: 236K (LinkedIn keyword) to ~800K (SlashData-derived) — a 3.4× spread.
2. **Stack Overflow survey lacks Indonesian salary/compen cut** and has tiny, shrinking IDN n (180 in 2025).
3. **J.P. Morgan/McKinsey ASEAN-5 2016 methodology behind "9M"** was never publicly documented, so the number cannot be reproduced or falsified from primary materials.
4. **IMDI 2024's "12M demand" and BPSDM's "456K/yr" modeling inputs are not public** (BPS-derived, internal model), so they cannot be independently verified — precisely the user's BPS distrust.
5. **Fastork current freelancer counts** not published in located sources; Upwork/Fiverr do not publish Indonesian developer counts (profile scraps last done 2018–2023, STALE).
6. **LinkedIn China-specific-equivalent for Indonesia membership base** (total members, workforce coverage %) not public — needed to convert concentration ratios into headcounts.
7. **Buffer State of Remote Work has no Indonesia cut**; typical Indonesia remote-work surveys are corporate white- collar polls (n≤1,200), not labor-market measures.
8. **BPS "freelancer" series**, while banned/flagged, is the only official time series — a structural gap if project rules prohibit BPS.
9. **AI engineering demand beyond LinkedIn**: no public count of AI job postings (Lightcast data for Indonesia not published in AI Index 2026 country tables found).

---

## Contradictions to carry into synthesis

- **9M/12M gap claims vs actual counts:** even at the most generous (2M developers, Aspiluki), the gap narrative outstrips any plausible employed base by 4–10×. At the LinkedIn-search count (236K), the "need" is 38× the *visible professional supply* — implausible unless "digital talent" means basic-digital-literacy workers (which the 2016 origin's "semi-skilled" language suggests).
- **Definitional inflation documented:** "9M skilled+semi-skilled ICT workers 2015–2030" (2016/2018) → "9M digital talents by 2030" (2019) → "9M per variously McKinsey/WEF/World Bank" (2019–2026).
- **Komdigi's own numbers are inconsistent:** 600k/yr (parroting McKinsey pre-2024) → 12M total demand, 500k/yr (IMDI 2024) → 456k-458k/yr (BPSDM 2024–2025) — the ministry quietly halved the pace while keeping the "shortage" frame.
- **GitHub accounts (4.37M) vs professional core (likely < 1M):** Indonesian GitHub account growth is real and even celebrated internationally, but is a poor proxy for employable engineers, as Indonesian tech writers themselves concede.
