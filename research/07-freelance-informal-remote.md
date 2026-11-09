# 07 — Freelance & Informal IT Economy + Remote Work for Foreign Employers (Market Side)

Research date: 2026-11-09. Researcher subagent session.

## ⚠️ METHOD NOTE — READ FIRST
The dedicated `websearch` tool returned zero results for every query this session (broken). All general-purpose search engines were unavailable or poisoned: DuckDuckGo (transport error/blocked), Brave (429), Mojeek (JS wall), SearXNG instances (anti-bot), and Bing repeatedly returned unrelated/junk organic results (e.g., French ISP forums and Chinese Q&A for "Turing Indonesia developers"), with `site:` operators ignored. Therefore this pass relied on **direct fetches of primary domains** (platform sites, media kits, corporate pages). Verified findings below are direct-fetch evidence. Items marked **GAP** could not be verified this session despite genuine attempts — they remain claims, not established numbers. **Gaps listed at bottom are the real story of this file**: for several questions (Payoneer Indonesia rates, Deel/Oyster Indonesia contractor counts, E33G take-up, APTIKNAS size), no verifiable public figure was reachable; treat any numbers circulating on those topics as unverified until the parent session can re-research with working search.

## Headline Numbers (verified this session)
| # | Figure | Verdict |
|---|--------|---------|
| 1 | Sribu (ex-Sribulancer): **">1.3 juta talenta freelancer"** registered, **40,000–50,000+ clients** served since 2012 | ✅ platform self-claim, ALL categories, not IT-specific |
| 2 | Fastwork Indonesia: **">150,000 pekerjaan" (jobs) completed** | ✅ platform self-claim, ALL categories (design/writing/marketing dominate; IT one of ~9 categories) |
| 3 | Projects.co.id: live and active (IT-centric local marketplace), verified listing web/mobile/desktop dev as core categories; **no published user/project counts** | ✅ verified existence; counts GAP |
| 4 | Turing: no country-level talent counts published; `turing.com/countries/indonesia` = 404 | ❌ "Indonesia top-5 supplier" type claims NOT verifiable |
| 5 | Local-platform IT-freelancing is **small in earnings terms**: the two largest local platforms publish job counts in the low 10^5 across ALL categories combined — consistent with parent session's finding (<10K Indonesians ever earned ≥$1 on Upwork) | inference, moderate confidence |

## Local Platforms
- **Sribulancer → Sribu** (sribu.com, PT Sribu Digital Kreatif): Indonesian-owned, founded 2012 as a design-contest platform, later Sribulancer (assisted freelancer marketplace), now rebranded back to Sribu with 200+ job categories including Web & Pemrograman.
  - [Sribu's own media-kit/landing page :: 2024–2025 (page footer © 2026) :: self-published platform claims, no external audit :: https://go.sribu.com/id/media-kit/ (also visible https://go.sribu.com/ and https://www.sribu.com/id) :: CONFIDENCE 4 for the claim text existing, 2 for the numbers being meaningful]
  - Claims found on page: "Akses ke lebih dari **1.3 juta talenta freelancer** terbaik di Indonesia"; "40,000+ Klien UKM & Korporasi Puas dengan Sribu Sejak 2012"; same page elsewhere says "50,000+ bisnis" (internal inconsistency 40K vs 50K — copy-deck drift).
  - Assessment: **registered** ≠ active ≠ earning. No revenue, no active-freelancer, no category split published. For IT specifically: "Web & Pemrograman" is one of ~7 mega-categories → plausibly low-10^4s registered, unknown active. Marketing copy, not audited data.
- **Fastwork** (fastwork.id; parent Fastwork Technologies, originally Thai fastwork.co, also VN fastlance.vn): live, actively marketing AI-services categories (notable pivot 2025–2026 to AI gigs: AI development, chatbot, "Custom AI Development").
  - [Fastwork Indonesia homepage :: 2026 (© 2026) :: self-published platform claim :: https://fastwork.id/ :: CONFIDENCE 4 text / 2 meaning] — "Lebih dari **150.000 pekerjaan** kami selesaikan" (all categories, all 3 countries in Fastwork's case — TH/ID/VN operational sites under one group, so even the 150K is not Indonesia-only).
  - No freelancer count, no GMV, no category split published on-site.
- **Projects.co.id** (projects.co.id, Bandung-based, rekber/escrow model): live, active (fresh blog posts: payment-system update 19/04/2026; tax guide for freelancers 27/10/2026 — evidence of ongoing small-scale operation). Positioning: "Temukan freelancer... untuk Website Development, Android & iOS Development, Desktop Programming, Graphic & Logo Design, Penulisan" — the most IT-centric of the local platforms.
  - [Projects.co.id homepage :: 2026 :: direct observation :: https://projects.co.id/ :: CONFIDENCE 4 operational / counts GAP]
  - Live project board at time of fetch includes micro-projects (e.g., "akun Google developer Console... Rp 3,000,000") — consistent with a small-project, low-ticket marketplace.
- **Sribulancer defunct-status note**: the original sribulancer.com domain now 404s; the brand lives on as Sribu. Any pre-~2022 coverage citing "Sribulancer X freelancer" is historical.
- **Kerja 1001**: could not resolve any live domain (kerja1001.com DNS fails). Presumed defunct or misnamed. [CONFIDENCE 1]

## Global Remote Platforms (Turing / Arc.dev / Toptal / Lemon.io / X-Team / Deel / Oyster)
- **Turing**: `https://www.turing.com/countries/indonesia` → 404. No country-page with Indonesian talent counts exists at that canonical path. Marketing repositioned to "Turing Frontier AI / Enterprise AI" (2026). **No Indonesian-supply figure could be located or verified.** Claims like "Indonesia among top-5 supplying countries" remain UNVERIFIED. [Turing site :: 2026 :: direct fetch :: https://www.turing.com/countries/indonesia (404) :: CONFIDENCE 1 that any count is published]
- **Arc.dev**: live marketplace ("Hire the Top 2% of Talent", arc.dev). No public country-of-supply counts found on accessible pages. Arc's old "state of remote developer" research reports not reachable without search. [https://arc.dev/ :: 2026 :: direct fetch :: CONFIDENCE 2]
- **Toptal / Lemon.io / X-Team**: not fetched this session (no predictable stats URLs, login-gated). Standard knowledge: Toptal publishes only acceptance rate ("top 3%"), never per-country talent counts. **GAP** for all three.
- **Deel** (`deel.com/press` fetched live, 1MB page, no "Indonesia" occurrence found in rendered text; blog is JS-rendered; report URLs `deel.com/state-of-global-hiring*` all 404). Deel's "State of Global Hiring" and "Global Hiring Report" do/did exist historically (widely covered 2022–2024), but **no Indonesia-specific contractor count or growth ranking could be retrieved or verified this session**. Known from parent-session context only: Deel-type EOR growth in ID is repeatedly claimed in press, never with citable absolute numbers. [GAP]
- **Oyster / Remote.com**: candidate report URLs 404 (`remote.com/platform-research-report`, `remote.com/research-reports`, `oysterhr.com/blog`). **GAP** — their country rankings for Indonesia unverifiable this session.
- Working conclusion for the parent model: **the "global-remote-from-Indonesia" headcount is not directly measurable from platform-published data.** No major platform publishes Indonesian talent/contractor counts. Only directional evidence exists (BCG/JobStreet 71% willingness — already in parent brief). Recommend modeling from: (a) Upwork active-earner numbers (parent brief), (b) LinkedIn location-tagged profiles filtered by foreign-employer signals (not doable with current tools), or (c) Deel/Oyster gated reports obtained manually with a form-fill + PDF.

## Earnings
- **Payoneer Freelancer Insights**: neither `payoneer.com/freelancer-insights*` nor `payoneer.com/about/freelancer-insights/` resolves (404); `blog.payoneer.com` is live but WordPress search/sitemap surfaces no accessible "Indonesia rate" post. **No Indonesia-specific hourly-rate figure could be verified. GAP.** Widely-circulated Payoneer country-rate numbers (e.g., "Indonesia ~$5–15/hr") must be treated as unverified secondary citations until the actual report PDF is obtained.
- **Indonesian community salary surveys** ("survey gaji developer remote"): none reachable without search. DevCenter — the one historically credible Indonesian publisher of developer-salary surveys (late-2010s "State of Indonesian Developers" surveys) — **has pivoted**: devcenter.co now redirects the product to **"Gigson by Devcenter"** ("forward deployed engineers", "managed developers", "cross-border compliance... handled by our team") — i.e., DevCenter 2026 is a talent-as-a-service (TaaS)/body-shop-to-foreign-clients vendor, not a survey publisher. No salary data on the current site. [https://www.devcenter.co/ :: 2026 :: direct fetch :: CONFIDENCE 3]
- Consequently **no verified Indonesia freelance/remote IT earnings figure was obtainable this session**. GAP.

## Formalized Contracting & Body-shops (semi-formal segment)
- **Gigson by Devcenter** (devcenter.co): verified, explicit business model = "forward deployed engineers / managed developers" with "contracts, cross-border compliance and statutory requirements handled by our team" — a formalized channel placing Indonesian developers with (incl. foreign) clients under managed contracts. No headcount/throughput published. [2026 :: direct fetch :: https://www.devcenter.co/ :: CONFIDENCE 3 for model existence, GAP for volumes]
- **Ekipa** (ekipa.co): fetch failed (TLS certificate error) — cannot verify it is an operating Indonesian TaaS player this session. [CONFIDENCE 1]
- **Skilvul Talent**: not fetched, unverified. **GAP**.
- **Telkomsigma** (telkomsigma.co.id fetched live): no employee count found in rendered homepage/about text. The known rough figure (Telkomsigma of order 1,000s of employees; major SI/outsourcing arm of Telkom Group placing staff into client IT operations) could not be pinned to a citable statement. [telkomsigma.co.id :: 2026 :: direct fetch, count absent :: CONFIDENCE 1 for counts]
- **BCA/bank vendor-outsourcing ("vendor 1000 karyawan")**: no citable source reachable. **GAP**.
- Contextual verification of the *mechanism* (not numbers): Projects.co.id's blog publishing a "Pajak untuk Freelancer Indonesia: PPh 21/23" guide (Oct 2026) is independent confirmation that Indonesian freelancers operate at the PPh-21/23 withholding boundary — i.e., an economy that is informal-ish but increasingly touched by formal tax-withholding channels. [projects.co.id/blog :: 2026 :: CONFIDENCE 4 for the guide existing]
- The clearest verified structural fact for the semi-formal segment: **industry-visible formalization has migrated to two rails** — (1) local platforms' escrow+tax content (Projects.co.id), and (2) TaaS/EOR-style companies (Gigson/DevCenter model) that package freelance supply as managed, contracted talent. Confirmed directionally; no volumetrics.

## Remote Work State & Visa (E33G etc.)
- **E33G (E-33G) "remote worker"/digital-nomad-style KITAS**, rolled out by Ditjen Imigrasi around 2024 (per parent brief): **no take-up numbers exist on any fetchable official page this session**. Imigrasi release pages were not reachable by direct fetch; media search engines failed. **GAP — high-priority**: take-up (applications issued per 2024/2025/2026) plausibly exists in Ditjen Imigrasi statistics or Kemenkumham press briefings, but could not be retrieved. [CONFIDENCE 1 for any take-up figure]
- JobStreet/LinkedIn hybrid-remote vacancy shares for Indonesia vs region: **GAP** (search-engine failure). Parent brief already holds BCG/JobStreet 2024 willingness (71%) — the best available attitudinal anchor.
- Return-to-office vs tech-remote trend data Indonesia-specific: **GAP**.

## Informal IT Vendor Market (non-LPSE, WhatsApp/community channels)
- **APTIKNAS**: `aptiknas.or.id` and `aptiknas.com` both unresolvable/dead from this environment. If the association publishes size estimates ("X thousand member IT companies"), it was unreachable. **GAP. Note**: also verify the association's exact name/domain with working search (Asosiasi Penyelenggara Teknologi Informasi dan Komunikasi Nusantara is the usual expansion, but I could not confirm the live domain).
- AJSI and equivalent: unverified, likely wrong name for the IT-services association; GAP.
- No credible size estimate of the WhatsApp/RFQ informal software-house channel was obtained. By construction this market is undocumented; nothing found contradicts treating any published "size" claim with suspicion. [GAP, CONFIDENCE 1]
- Only usable directional anchor captured: local platform data implies a very large **registered-vs-active gap** (cf. 2018 scrape 1.2% active, upwork <10K earners — parent brief). Combined with Sribu's "1.3 juta talenta terdaftar" marketing figure vs. its 40–50K clients-over-13-years, the Indonesian freelance-IT market plausibly has **two-plus orders of magnitude more sign-ups than consistent earners**. [INFERENCE from verified claims above :: CONFIDENCE 2]

## Methodology Assessment
- Verified: platforms claim big registries (Sribu 1.3M registered across all categories; Fastwork >150K completed jobs group-wide) — these are **marketing top-lines with known survivorship/selection problems**: no dedup, no activity threshold, multi-country (Fastwork), category conflation. For IT-only slices they are upper bounds of registered users, weak bounds of active freelancers.
- NOT verified and NOT trustworthy without further work: Payoneer Indonesia rates; Deel/Oyster/Remote Indonesia counts; E33G take-up; APTIKNAS membership size; Turing/Arc/Lemon.io Indonesia supply claims; JobStreet hybrid-vacancy share; any "vendor X karyawan" bank-outsourcing claim.
- During this session the following previously-circulating claim types were **checked and failed falsification-by-absence**: Turing country page (404), Deel press page (no Indonesia), Payoneer report URL (gone). Absence of publication ≠ absence of truth, but it does mean: **do not cite numbers for these without the underlying report PDF.**

## JSON (machine-readable)
```json
[
  {"id":"sribu-1.3m","metric":"registered freelancers, all categories (platform claim)","value":1300000,"scope":"all categories not IT-only","source":"Sribu (ex Sribulancer) own media-kit page","year":"2024-2025","method":"self-published marketing copy, no audit","url":"https://go.sribu.com/id/media-kit/","confidence":2,
   "note":"Page also self-inconsistently claims 40,000+ and 50,000+ clients since 2012"},
  {"id":"fastwork-150k","metric":"completed jobs, all categories, TH+ID+VN group (platform claim)","value":150000,"scope":"all categories, not Indonesia-only","source":"Fastwork Indonesia homepage","year":"2026","method":"self-published marketing copy","url":"https://fastwork.id/","confidence":2},
  {"id":"projects-live","metric":"IT-centric local freelance marketplace operational status","value":"live; active blog through Oct 2026; core categories: web/mobile/desktop dev","source":"projects.co.id homepage","year":"2026","method":"direct observation","url":"https://projects.co.id/","confidence":4,
   "note":"no user/project/revenue counts published; prominent escrow(rekber) model; published PPh21/23 freelancer tax guide"},
  {"id":"sribulancer-defunct","metric":"original sribulancer.com status","value":"404; brand merged into Sribu","source":"direct fetch","year":"2026","method":"direct fetch","url":"https://www.sribulancer.com/","confidence":4},
  {"id":"kerja1001","metric":"local platform liveness","value":"unresolvable/likely defunct","source":"DNS failure","year":"2026","method":"direct fetch attempt","url":"https://www.kerja1001.com/","confidence":1},
  {"id":"turing-id","metric":"Indonesian developers on Turing","value":"NO PUBLISHED COUNT; country page 404","source":"turing.com","year":"2026","method":"direct fetch","url":"https://www.turing.com/countries/indonesia","confidence":1,
   "note":"'Indonesia top-5 supplier' claims unverified"},
  {"id":"arc-dev","metric":"Indonesian talent on Arc.dev","value":"NO PUBLISHED COUNTRY COUNT FOUND","source":"arc.dev","year":"2026","method":"direct fetch","url":"https://arc.dev/","confidence":2},
  {"id":"deel-id","metric":"Deel Indonesia contractors/employees","value":"GAP - reports exist historically but no Indonesia figure retrievable; /press has zero 'Indonesia' occurrences; report URLs 404","source":"deel.com/press","year":"2026","method":"1MB page fetch + keyword scan","url":"https://www.deel.com/press","confidence":1},
  {"id":"oyster-remote-gaps","metric":"Oyster/Remote.com Indonesia figures","value":"GAP - report URLs 404","source":"remote.com, oysterhr.com probes","year":"2026","method":"direct fetch probes","url":"https://remote.com/platform-research-report","confidence":1},
  {"id":"payoneer-id","metric":"Indonesia freelance hourly rate (Payoneer)","value":"GAP - report URLs dead; blog reachable but no ID post accessible","source":"payoneer.com probes","year":"2026","method":"direct fetch probes + blog sitemap attempt","url":"https://www.payoneer.com/freelancer-insights-report/","confidence":1},
  {"id":"gigson","metric":"TaaS formalized freelance channel (Indonesian)","value":"Devcenter rebranded product 'Gigson by Devcenter': forward-deployed/managed developers, cross-border compliance handled; no volume published","source":"devcenter.co","year":"2026","method":"direct fetch","url":"https://www.devcenter.co/","confidence":3},
  {"id":"ekipa","metric":"Ekipa (TaaS candidate) operational status","value":"fetch failed (TLS error) - unverified","source":"ekipa.co probe","year":"2026","method":"direct fetch attempt","url":"https://www.ekipa.co/","confidence":1},
  {"id":"telkomsigma","metric":"Telkomsigma employee/vendor-outsourcing count","value":"GAP - site live but no count in rendered text","source":"telkomsigma.co.id","year":"2026","method":"direct fetch + keyword scan","url":"https://www.telkomsigma.co.id/","confidence":1},
  {"id":"e33g","metric":"E33G remote-worker KITAS take-up (applications)","value":"GAP - no figure retrievable this session","source":"n/a (immigration pages unreachable via direct fetch)","year":"2024-2026","method":"failed retrieval; search engines down","url":"-","confidence":1,
   "note":"verify via Ditjen Imigrasi statistics/press when search works"},
  {"id":"aptiknas","metric":"APTIKNAS member-company count","value":"GAP - domains aptiknas.or.id / aptiknas.com unreachable","source":"DNS/connection failures","year":"2026","method":"direct fetch attempts","url":"-","confidence":1},
  {"id":"registered-vs-active","metric":"structural ratio: registered vs earning freelancers (IT slice)","value":"two+ orders of magnitude gap (1.3M registrations all-cat vs 40-50K clients served in 13yr locally; <10K ever earned >=$1K on Upwork per parent brief)","source":"inference combining verified platform claims + parent-session Upwork data","year":"2012-2026","method":"triangulation","url":"-","confidence":2,
   "note":"key modeling anchor for informal/market side: opt-in registrations massively overstate the active workforce"}
]
```

## Data Gaps (priority for parent model)
1. **E33G take-up numbers** — likely exists at Ditjen Imigrasi (statistik ITA/KITAS); needs working search or manual browser.
2. **Payoneer Freelancer Insights Indonesia rates** — needs gated PDF (form fill) or archive.org copy of the 2023 report; the public URLs are dead.
3. **Deel "State of Global Hiring" / Oyster / Remote.com country data for Indonesia** — gated reports; parent should give a subagent manual-browser access, or accept "directionally strong growth, no absolute numbers" as the finding.
4. **Turing/Arc.dev/Lemon.io Indonesia supply claims** — no public numbers found; do not use in model except as unverified directional claims (confidence 1).
5. **APTIKNAS (or correctly-named IT industry association) size estimates** — re-establish correct domain and any member/turnover statistics.
6. **JobStreet/LinkedIn hybrid & remote vacancy shares Indonesia vs region, 2024–2026**, and any RTO-vs-tech-remote split.
7. **Body-shop placement volumes** (Telkomsigma, BCA-linked vendors, SI firms) into banks/telcos — any "vendor X karyawan" claim is currently uncitable.
8. **Community salary surveys** (gaji developer remote) — identify a currently-active survey publisher (DevCenter's old surveys are dead with the rebrand to Gigson); Rekrut/Hacktiv8/Purwadhiki candidates need working search.
9. **Sribu/Fastwork IT-category counts** — worth emailing founders or checking archived Tech in Asia/DailySocial coverage of Sribu Series A (2016) and Fastwork funding rounds for era-specific user counts.
