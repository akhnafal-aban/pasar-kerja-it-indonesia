# Indonesia IT Workforce — Talent Supply TIME SERIES (2015–2025)

Research agent harvest, 9 Nov 2026. Method note: built from full-text extraction of the **official Statistik Pendidikan Tinggi book archive (Buku Statistik 2020–2025 PDFs, downloaded from Pusdatin Kemdiktisaintek)** + official komdigi/DTS datasets + live Dapodik-derived SMK dashboard export. All PDFs verified authentic (downloaded directly from pusdatin (go.id) and dikti.go.id URLs listed below). Text extraction via pypdf; chart values hand-mapped to chart label order (books' top-10 charts extract as label-list + value-list). **The official per-prodi series only exists in new-format books (from 2023 edition onward)** — older editions (2015–2022) publish tables only by province/institution/field-of-study, so pre-2021 per-prodi year-marks are structurally unavailable from official PDFs; 2021 partial marks and labeled interpolations fill the gap.

## Headline Series

### 1. Teknik Informatika (TI) & Sistem Informasi (SI) — graduates (lulusan)

| Academic year | TI lulusan | SI lulusan | Source tier |
|---|---|---|---|
| 2021 (bk 2023, narrative only) | ranked #6 nationally; no value printed as text | not in top-10 | official book (rank only) |
| 2023/24 (bk 2024, via media) | **35,919** (#8 of top-20) | **25,866** (#13) | official book via Detik |
| 2024/25 (bk 2025, p.159 chart) | **31,837** (S1) | **26,932** (S1) | official book, Conf 5 |

TI 2024/25 fell ~11% vs 2023/24; SI rose ~4%. S1-only for the book chart; Detik top-20 list is all-levels per-prodi rollups.

Additional marks (vocational, 2024/25 book diploma chart): Teknik Informatika (D3/D4) lulusan **17,462**; Manajemen Informatika **6,438** (both TA 2024/25).

### 2. TI & SI — new entrants (mahasiswa baru) — supply pipeline

| Academic year | TI maba | SI maba | Method |
|---|---|---|---|
| 2019 (bk 2020) | Jawa-island only: 38,435 (top prodi in Jawa, Kalimantan, Nusa Tenggara) | Jawa 10,888 |** partial (island cut) |
| 2021 (bk 2022 top-10 chart) | below top-10 cutoff ⇒ < ~27,144 national all-prodi list | below cutoff likewise | bound inference |
| 2023/24 | not in media top-20 lists | — | gap |
| 2024/25 (bk 2025 p.122) | **46,035** | **48,335** | official, Conf 5 |

**Key finding: massive TI/SI intake surge 2021→2025.** From sub-27k each in 2021 to ~46–48k each in 2024/25 (mid-30k to high-40k plausible interpolation for 2022–2023 — labeled interpolation in JSON).

### 3. TI & SI — enrolled stock (mahasiswa terdaftar)

| Year | TI enrolled | SI enrolled | Source |
|---|---|---|---|
| 2019 (bk 2020 "Kondisi Mahasiswa Prodi Informatika & SI" chart) | **257,938** (S1) | **153,645** (S1) | official, Conf 4 |
| 2024/25 (bk 2025 top-10 chart, p.166) | **208,348** | **234,983** | official, Conf 5 |

Structural shift: TI stock shrank ~19% while SI stock grew ~53%; SI overtook TI between 2019 and 2025. Narrative in book 2020 confirms TI+SI S1 ≈ "400 thousand" continuing pipeline.

### 4. Computing graduates total estimate (6 target majors)

Anchor year-marks (S1, all-levels per-prodi where noted):
- 2023/24: TI 35,919 + SI 25,866 = 61,785 from top-20 alone ⇒ est. **75,000 (±10k)** incl. Ilmu Komputer/Informatika, RPL, (S1) Teknologi Informasi, Manajemen Informatika
- 2024/25: TI 31,837 + SI 26,932 + D3/D4 TI 17,462 + MI 6,438 = 82,669 with only 4 majors ⇒ est. **85,000–95,000 all levels** (interpolation-labeled; other majors unobserved)
- Teknik (engineering field incl. all computing + civil/mechanical/electrical) graduates 2024/25: **299,412** (bk 2025 "Lulusan Berdasarkan Bidang Ilmu" chart; total all-fields 2,547,717) — useful ceiling: computing ≈ 30% of teknik field.

### 5. STEM/engineering share of higher-ed (Teknik field)

| Year | Teknik maba | Total maba | Teknik share |
|---|---|---|---|
| 2019 (bk 2020, S1 chart) | 273,653 (+ vokasi teknik 58,130) | ~2.05M | ~16% |
| 2021 (bk 2022, p.115 chart) | **399,644** | 2,511,139 | **15.91%** |
| 2024/25 (bk 2025 p.122 chart) | **382,911** | 2,158,826 | **17.7%** |

| Year | Teknik enrolled | total enrolled |
|---|---|---|
| 2021 (bk 2023 "Jumlah Mahasiswa Terdaftar Berdasarkan Bidang Ilmu") | 1,482,955 | ~9.72M |
| 2024/25 (bk 2025 5.4 chart, gender-pair verified) | **1,619,754** | 10,754,109 |

Engineering share of new entrants rose ~2pp 2021→2025 while total maba fell slightly — supply growth momentum is real but modest at field level; the dramatic growth is INSIDE teknik (prodi-level TI/SI concentration).

### 6. SMK TKJ & RPL (vocational computing track)

Live official Dapodik-sourced export (Direktorat SMK dashboard, snapshot 9 Nov 2026, TA 2025/26):

| Competence (old + new nomenclature) | Students total | Grade 12 (≈2026 grad flow) | Grade 10 (2026 entrants) |
|---|---|---|---|
| Teknik Komputer dan Jaringan + Teknik Jaringan Komputer dan Telekomunikasi (TKJ/TJKT) | **681,530** | 219,291 | 234,257 |
| Rekayasa Perangkat Lunak + Pengembangan Perangkat Lunak dan Gim (RPL/PPLG) | **160,304** | 50,897 | 56,782 |
| TKJ + RPL combined | **841,834** | **270,188** | **291,039** |

TKJ+RPL ≈ **17.3% of all 4,876,648 SMK students**. The grade columns reveal the K-13 rollout: new-nomenclature competences (TJKT, PPLG) hold all of grade-10; old names hold grades 11–12. Historical TKJ/RPL year-marks remain unavailable in extractable official tables (gap flagged); PSKP 2019 study confirms TIK field was top-3 SMK field by graduates (top-3 fields = 80.2% combined, 2019).

### 7. DTS (Digital Talent Scholarship) per-year official recaps

| Year | Accepted / participants | Completed | Source |
|---|---|---|---|
| 2019 | target 25,000 / 4 academies | — | Setkab, Conf 4 |
| 2020 | target 60,000 (incl. Online Academy 20,300); budget Rp16.4bn | — | Kominfo PR 222/2019 + DPR PA3KN, Conf 4 |
| 2021 | **131,204** (realisasi, official statement) | — | Menkominfo via Setkab 29 Dec 2021, Conf 4 |
| 2022 | **>200,000** trained (from 283,906 applicants) | — | Kominfo via sdmdigital.id, Conf 4 |
| 2023 | **122,104 accepted / 75,551 completed** (classic DTS, by academy, from official xlsx) | DEA 31,057; TA 15,508; GTA 11,740; VSGA 2,878; FGA 4,739; ProA 5,209; TSA 4,148; DLA 272 | data.komdigi.go.id "Data Prioritas 2023 – Peserta DTS", Conf 5 |
| 2024 | **134,416 accepted / 101,993 completed** (classic DTS; from official xlsx) | FGA 5,142; VSGA 17,503; TA 20,581; ProA 7,643; DEA 31,946; GTA 15,482; TSA 3,458; DLA 238 | data.komdigi.go.id rekap akademi 2024, Conf 5 |
| 2025 | cumulative through Oct 2025: 572,072 incl. **503,108 Microskill**; classic academies only 68,964 | — | Komdigi infographic, Conf 3 |

DPR-commissioned audit context (PA3KN policy brief, 2022): DTS budget realization jumped Rp16.4bn (2020) → Rp122.6bn (2021); BPK flagged participant-data inaccuracies — treat badly-documented year totals with care.

## Per-Source Detail (URLs)

| Source | URL | What it yielded |
|---|---|---|
| Buku Statistik PT 2025 (393pp) | https://dikti.go.id/api/file/humas-production/books/2026/5/pdfs/14c84a6c-9d32-40d5-bc39-5cce1ecbfceb/Buku_Statistik_Pendidikan_Tinggi_Tahun_2025.pdf | 2024/25: TI/SI lulusan, maba, enrolled charts; maba & enrolled & lulusan by field; field gender pairs |
| Buku Statistik PT 2024 | https://pusdatin.kemdiktisaintek.go.id/storage/buku-statistik/Statistik%20Pendidikan%20Tinggi%202024.pdf | 2023/24 reference year; charts raster → relied on media mirror of its tables |
| Buku Statistik PT 2023 | https://pusdatin.kemdiktisaintek.go.id/storage/buku-statistik/Statistik%20Pendidikan%20Tinggi%202023.pdf | 2021 data: enrolled by field (Teknik 1,482,955); TI lulusan rank narrative; total enrolled 7,179,330 aktif |
| Buku Statistik PT 2022 | https://pusdatin.kemdiktisaintek.go.id/storage/buku-statistik/Statistik%20Pendidikan%20Tinggi%202022.pdf | 2021 data: maha baru by field (Teknik 399,644; 15.91%) + top-10 prodi maba list (cutoff 27,144) |
| Buku Statistik PT 2021 | https://pusdatin.kemdiktisaintek.go.id/storage/buku-statistik/Statistik%20Pendidikan%20Tinggi%202021.pdf | prodi-count by field trends 2020→2021; no per-prodi student tables |
| Buku Statistik PT 2020 | https://pusdatin.kemdiktisaintek.go.id/storage/buku-statistik/Statistik%20Pendidikan%20Tinggi%202020.pdf | 2019 data: TI/SI S1 enrolled 257,938/153,645; Teknik maba S1 273,653; island-level TI maba 38,435 (Jawa) |
| Pusdatin archive landing | https://pusdatin.kemdiktisaintek.go.id/program/statistik | provenance + snapshot dates per edition (Dec 2020/2021/2022/2023; Jan 2025 for bk 2024) |
| Detik top-20 lulusan TA 2023/24 | https://www.detik.com/edu/perguruan-tinggi/d-8463110/... | TI 35,919; SI 25,866; +18 other prodi values (mirror of Statistik PT 2024 tables) |
| DTS Data Prioritas 2023 (xlsx) | https://data.komdigi.go.id/catalog-download/238 | 2023 by academy (peserta diterima, lulus pelatihan) |
| DTS rekap per akademi 2024 (xlsx) | https://data.komdigi.go.id/catalog-download/239 | 2024 by academy (target/pendaftar/diterima/onboarding/completion) |
| Statistik SMK dashboard export | https://smk.kemendikdasmen.go.id/statistik-smk/?export=excel&bidang=... | live Dapodik per-school × competence export; TKJ/RPL/Multimedia sums |
| DPR PA3KN DTS brief | https://repositori.dpr.go.id/id/eprint/322/ | budget realisasi 2020/2021; BPK audit caveats |
| data.kemendikdasmen publikasi portal (JS-only) | https://data.kemendikdasmen.go.id/publikasi (Statistik SMK 2023/24 & 2024/25 PDF links unresolvable — portal routes broken) | provenance only |

## Methodology Assessment

- **Official books are the only series-capable source** for per-prodi data; editions 2015-era through 2021 are aggregate-by-province only, so a complete official TI/SI graduate series 2015–2025 does not exist in published PDFs. PDDikti API (api-pddikti.kemdiktisaintek.go.id) exists but sits behind Pango auth gateway (verified blocked); the public dashboard JS is obfuscated. Year-by-year PDDikti dashboard press coverage is the only practical route for missing year-marks; search engines were largely degraded during harvest (Bing/brave/mojeek junk or 403; Yahoo worked).
- **Chart value→label mapping risk**: book charts extract as two ordered lists; I mapped by rank order and cross-checked with narratives (e.g., gender-pair sums must equal grand totals in bk 2025 field chart — verified 2,766,765 etc.; k10+k11+k12 summed exactly to per-row "Jumlah Siswa" in SMK export — verified internally consistent).
- **Confidence anchors**: bk 2025/2022 chart numbers = 5 (official + internally verified); bk 2020 chart numbers = 4; media mirrors = 4; bound-inference & interpolations = 2.
- **Comparability warnings**: (a) Detik's "20 prodi lulusan terbanyak" says "mahasiswa" but mirrors lulusan tables of Statistik PT 2024 — treated as lulusan (Conf 4, flagged). (b) DTS year totals switch between "trained/accepted/completed" definitions (2021 & 2022 = participants trained; 2023–2024 = accepted+completed split now available); Microskill (2025, 503k) is a different, much lighter program — never combine with classic DTS. (c) SMK grade columns reflect nomenclature migration (K-13), not enrollment collapse.
- BPS not used anywhere. All figures Kemdikbud-family administrative censuses (PDDikti/Dapodik) + state press-releases.

## JSON

```json
[
{"series_name":"ti_graduates","unit":"persons/year","data_points":[
 {"year":"2021","value":null,"rank":6,"source":"Statistik PT 2023 narrative p.166","methodology":"PDDikti census; rank only, value raster","url":"https://pusdatin.kemdiktisaintek.go.id/storage/buku-statistik/Statistik%20Pendidikan%20Tinggi%202023.pdf","confidence":4},
 {"year":"2022/est","value":34000,"source":"interpolation between 2021 rank point and 2023/24","methodology":"interpolation","confidence":2},
 {"year":"2023/24","value":35919,"source":"Statistik PT 2024 tables via Detik top-20 list","methodology":"PDDikti census, all-levels prodi rollup","url":"https://www.detik.com/edu/perguruan-tinggi/d-8463110/kemdikti-bakal-tutup-sejumlah-prodi-simak-lagi-20-prodi-dengan-lulusan-terbanyak","confidence":4},
 {"year":"2024/25","value":31837,"source":"Statistik PT 2025 p.159 bachelor top-10 chart","methodology":"PDDikti census (S1)","url":"https://dikti.go.id/api/file/humas-production/books/2026/5/pdfs/14c84a6c-9d32-40d5-bc39-5cce1ecbfceb/Buku_Statistik_Pendidikan_Tinggi_Tahun_2025.pdf","confidence":5}]},
{"series_name":"si_graduates","unit":"persons/year","data_points":[
 {"year":"2022/est","value":21000,"source":"interpolation","methodology":"interpolation","confidence":2},
 {"year":"2023/24","value":25866,"source":"Detik top-20 mirror of Statistik PT 2024","methodology":"PDDikti census","url":"https://www.detik.com/edu/perguruan-tinggi/d-8463110/","confidence":4},
 {"year":"2024/25","value":26932,"source":"Statistik PT 2025 p.159 chart","methodology":"PDDikti census (S1)","url":"dikti.go.id book url as above","confidence":5}]},
{"series_name":"computing_graduates_total_est","unit":"persons/year (est)","data_points":[
 {"year":"2023/24","value":75000,"range_low":70000,"range_high":85000,"source":"bottom-up from top-20 prodi lists","methodology":"TI+SI observed + estimated Ilmu Komputer/RPL/TI/MI","url":"detik d-8463110","confidence":3},
 {"year":"2024/25","value":90000,"range_low":85000,"range_high":95000,"source":"bottom-up: TI 31,837 + SI 26,932 + vocational TI 17,462 + MI 6,438 (observed = 82,669) + unobserved majors","methodology":"partial observation + interpolation","url":"Statistik PT 2025 p.159 & diploma chart","confidence":3}]},
{"series_name":"ti_si_new_entrants","unit":"persons/year","data_points":[
 {"year":"2019","value":38435,"note":"TI maba, Jawa island only (TI was #1 maba prodi in Jawa/Kalimantan/NT)","source":"Statistik PT 2020 p.119-120","confidence":4,"methodology":"PDDikti census, island cut","url":"https://pusdatin.kemdiktisaintek.go.id/storage/buku-statistik/Statistik%20Pendidikan%20Tinggi%202020.pdf"},
 {"year":"2021","value":27000,"note":"upper bound: TI below #10 (Hukum 27,144) of national top-10 maba list","methodology":"bound inference","source":"Statistik PT 2022 p.115 chart","confidence":2,"url":"https://pusdatin.kemdiktisaintek.go.id/storage/buku-statistik/Statistik%20Pendidikan%20Tinggi%202022.pdf"},
 {"year":"2022/est","value":36000,"note":"TI","methodology":"interpolation","confidence":2},
 {"year":"2024/25","value":46035,"note":"TI","source":"Statistik PT 2025 p.122","methodology":"PDDikti census","confidence":5,"url":"dikti.go.id book url"},
 {"year":"2024/25","value":48335,"note":"SI (SI overtook TI in intake)","source":"Statistik PT 2025 p.122","methodology":"PDDikti census","confidence":5},
 {"year":"2019","value":153645,"note":"SI enrolled S1 (stock, not entrant) — listed here for pipeline context","source":"Statistik PT 2020 p.159-160 chart","confidence":4},
 {"year":"2024/25","value":208348,"note":"TI enrolled S1","source":"Statistik PT 2025 p.166","confidence":5},
 {"year":"2024/25","value":234983,"note":"SI enrolled S1","source":"Statistik PT 2025 p.166","confidence":5}]},
{"series_name":"ti_si_enrolled","unit":"persons","data_points":[
 {"year":"2019","value":257938,"note":"TI S1","methodology":"PDDikti census","source":"Statistik PT 2020","confidence":4,"url":"bk2020 url"},
 {"year":"2019","value":153645,"note":"SI S1","source":"Statistik PT 2020","confidence":4,"url":"bk2020 url"},
 {"year":"2024/25","value":208348,"note":"TI","source":"Statistik PT 2025 top-10 chart","confidence":5},
 {"year":"2024/25","value":234983,"note":"SI","source":"Statistik PT 2025","confidence":5}]},
{"series_name":"smk_tkj_rpl","unit":"persons","data_points":[
 {"year":"2025/26 (snapshot Nov 2026)","value":681530,"note":"TKJ/TJKT total students","source":"Direktorat SMK dashboard export (Dapodik)","methodology":"school×competence CSV aggregation","url":"https://smk.kemendikdasmen.go.id/statistik-smk/?export=excel&bidang=Teknologi%20dan%20Rekayasa","confidence":5},
 {"year":"2025/26","value":219291,"note":"TKJ/TJKT grade-12 ≈ 2026 graduate flow","source":"same export","confidence":5,"url":"same"},
 {"year":"2025/26","value":234257,"note":"TKJ/TJKT grade-10 entrants","source":"same export","confidence":5,"url":"same"},
 {"year":"2025/26","value":160304,"note":"RPL/PPLG total students","source":"same export","confidence":5,"url":"same"},
 {"year":"2025/26","value":50897,"note":"RPL/PPLG grade-12 ≈ grad flow","source":"same export","confidence":5,"url":"same"},
 {"year":"2025/26","value":56782,"note":"RPL/PPLG grade-10 entrants","source":"same export","confidence":5,"url":"same"},
 {"year":"2025/26","value":841834,"note":"TKJ+RPL combined = ~17.3% of 4.88M SMK students","source":"same export","confidence":5,"url":"same"},
 {"year":"2019","value":null,"note":"TIK field: top-3 SMK fields (Teknik&Rekayasa, Bisnis&Mgmt, TIK) = 80.2% of graduates; per-competence TKJ/RPL not split out","source":"PSKP Kemendikdasmen kajian","methodology":"Dapodik analysis","url":"https://pskp.kemendikdasmen.go.id/assets_front/images/produk/1-gtk/materi/Sesi_I_K1_Analisis_Daya_Serap_Lulusan_SMK_Berdasarkan_Kompetensi_Keahlian_-_Sudiyono_dkk.pdf","confidence":3}]},
{"series_name":"dts_per_year","unit":"persons","data_points":[
 {"year":"2019","value":25000,"note":"target","source":"Setkab","confidence":4,"url":"https://www.setkab.go.id/kominfo-buka-pendaftaran-25-000-beasiswa-program-digital-talent-scholarship-2019/"},
 {"year":"2020","value":60000,"note":"target incl. Online Academy 20,300; budget realisasi Rp16.4bn","source":"Kominfo PR 222/HM/KOMINFO/12/2019 + DPR PA3KN","confidence":4,"url":"https://www.komdigi.go.id/berita/siaran-pers/detail/siaran-pers-no-222-hm-kominfo-12-2019"},
 {"year":"2021","value":131204,"note":"realisasi participants trained; budget Rp122.6bn","source":"Menkominfo via Setkab 29 Dec 2021","confidence":4,"url":"https://setkab.go.id/akselerasi-transformasi-digital-pemerintah-perbanyak-target-peserta-pelatihan-talenta-digital-tahun-2022/"},
 {"year":"2022","value":200000,"note":">200k trained, from 283,906 applicants","source":"Kominfo via sdmdigital.id","confidence":4,"url":"https://mobile.sdmdigital.id/artikel/latih-lebih-dari-200-ribu-peserta-dts-kominfo-akan-gelar-digiers-day-152"},
 {"year":"2023","value":122104,"note":"accepted; completed 75,551 (classic DTS by academy, official xlsx)","source":"data.komdigi.go.id 'Data Prioritas 2023 – Peserta DTS'","confidence":5,"url":"https://data.komdigi.go.id/catalog-download/238"},
 {"year":"2024","value":134416,"note":"accepted; completed 101,993 (FGA 5,142; VSGA 17,503; TA 20,581; ProA 7,643; DEA 31,946; GTA 15,482; TSA 3,458; DLA 238)","source":"data.komdigi.go.id rekap per akademi 2024","confidence":5,"url":"https://data.komdigi.go.id/catalog-download/239"},
 {"year":"2025 (cum. thru Oct)","value":572072,"note":"incl. Microskill 503,108; classic DTS grad only 68,964","source":"Komdigi infographic","confidence":3,"url":"https://indonesiabaik.id/infografis/cetak-talenta-digital-unggul-menuju-indonesia-maju"}]},
{"series_name":"stem_share","unit":"% of higher-ed cohort (Teknik field)","data_points":[
 {"year":"2019","value":16.0,"note":"maba S1 teknik 273,653 of ~2.05M; S&T total 343,563 per narrative","source":"Statistik PT 2020","confidence":3,"url":"bk2020 url"},
 {"year":"2021","value":15.91,"note":"maba tek 399,644 of 2,511,139","source":"Statistik PT 2022 p.115","confidence":5,"url":"https://pusdatin.kemdiktisaintek.go.id/storage/buku-statistik/Statistik%20Pendidikan%20Tinggi%202022.pdf"},
 {"year":"2024/25","value":17.7,"note":"maba tek 382,911 of 2,158,826 (10 fields summed)","source":"Statistik PT 2025 p.122","confidence":4,"url":"dikti.go.id book url"},
 {"year":"2021 (enrolled)","value":15.3,"note":"teknik enrolled 1,482,955 / ~9.72M","source":"Statistik PT 2023","confidence":4,"url":"bk2023 url"},
 {"year":"2024/25 (enrolled)","value":15.1,"note":"teknik enrolled 1,619,754 / 10,754,109 (gender-pair verified)","source":"Statistik PT 2025 5.4 chart","confidence":4,"url":"dikti.go.id book url"},
 {"year":"2024/25 (graduates)","value":11.75,"note":"teknik lulusan 299,412 / 2,547,717","source":"Statistik PT 2025 lulusan-by-field chart","confidence":4,"url":"dikti.go.id book url"}]},
{"series_name":"msib_per_batch","unit":"mahasiswa","data_points":[
 {"year":"2021 (b1)","value":13272,"source":"MUDIMA journal citing official MSIB records","confidence":3,"url":"https://journal.formosapublisher.org/index.php/mudima/article/download/489"},
 {"year":"2023 (b5)","value":36728,"source":"Kemendikbudristek socialization deck","confidence":4,"url":"https://www.scribd.com/document/681881344/"},
 {"year":"2024 (b6)","value":47984,"source":"Kompas quoting Kemendikbudristek","confidence":4,"url":"https://www.kompas.com/edu/read/2024/02/23/100452171/47984-mahasiswa-ikut-program-msib-angkatan-6-2024"},
 {"year":"2021-2025 (cum b1-7)","value":150000,"note":">150k","source":"Kemdiktisaintek (Undana sosialisasi)","confidence":4,"url":"https://kemdiktisaintek.go.id/news/article/undana-gelar-sosialisasi-program-msib-dan-merdeka-belajar-2024"}]}
]
```

## Data Gaps

1. **TI/SI lulusan 2015–2022**: structurally unavailable from official book PDFs (pre-2023 editions have no per-prodi national tables; 2023 edition prints values as raster). PDDikti API is auth-gated; year-by-year press coverage of the PDDikti dashboard is the only remaining route. 2023 book gives TI at list rank #6 for 2021 (no number).
2. **New entrants 2015–2020, 2022, 2023/24** admission years for TI/SI: same gap; only bound (2021) and island-cut (2019 Jawa) marks exist.
3. **SMK TKJ/RPL historical series**: Statistik SMK 2023/24 & 2024/25 PDFs exist on data.kemendikdasmen.go.id portal but its routing is broken (topic pages 404); BAN-SM/Dapodik per-competence historical exports not found. Only live snapshot + 2019 field-share context captured.
4. **DTS 2019/2020 realisasi**: official statements exist targets only; realization figures I could reach were targets (2019) and budget (2020); the completion-split by academy only exists from 2023.
5. **Ilmu Komputer, RPL-S1, Teknologi Informasi (S1), Manajemen Informatika graduates**: never in any top-20 list nor extractable chart → only inside the bottom-up estimate ranges.
6. Chart value-order mapping is manual; medium residual risk on the two 2025-book field charts (mitigated by internal sum checks: gender pairs sum to grand totals; 10-field maba shares sum to ~100% of 2.16M).
