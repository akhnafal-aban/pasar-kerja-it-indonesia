# Pasar Kerja IT Indonesia — Papan Data

Dashboard HTML satu file. Data per 9 Nov 2026. Live via GitHub Pages.

Buka `index.html` = semua chart jalan. No CDN, no build, no dependency.

## Apa ini

- Papan data tenaga kerja IT Indonesia: demand per role, gaji per level, siklus pasar 2020-26, pipeline pasokan, komposisi pekerja, formal vs informal, regional, role emerging, audit kredibilitas sumber
- Hero buka kartu: klaim "butuh 9 juta talenta digital" dicoret + rantai asal-usulnya dibongkar (JPM/McKinsey 2016 → World Bank 2018 → salah-atribusi pejabat → putaran media)
- Angka riil: ~950rb IT profesional bekerja (rentang 700rb–1,2jt), inti software engineer 300–600rb

## Metodologi (inti)

**Riset = 19 AI agent paralel, 17 domain.**

- Max 5 agent jalan bareng. Satu slot bebas → agent baru domain lain. Nol duplikasi kerja
- **Demand diukur lintas platform**: LinkedIn (keyword live), JobStreet (SSR SEO), Kalibrr (endpoint resmi, scope ID terverifikasi), Indeed (tier N+), + karir.com/projects.co.id/fastwork sebagai pembanding. Basis hitung tiap platform beda → bandingkan urutan per kolom, bukan angka mentah antar platform
- Tiap domain → 1 berkas riset. Format wajib: headline table, temuan per-sumber + URL, metodologi tiap angka, JSON machine-readable, data gaps
- Label wajib tiap angka: `[sumber :: tahun :: metodologi :: confidence 1-5]`. Angka tanpa metodologi = ditolak
- **BPS diblokir** semua agent riset. 1 agent khusus audit metodologi BPS (Sakernas/KBLI): verdict per seri → pakai-dengan-catatan / lemah / hindari. Hanya seri lolos audit masuk dashboard, selalu bawa caveat
- Klaim harus dilacak ke laporan ASLI. Rantai kutip-menyalin-kutip ditelan. Contoh hasil: "9 juta" = retorika di chaining sitasi tipis; "Gartner IT spend Indonesia" = tidak pernah ada; "77% Manpower Indonesia" = salah atribusi (Indonesia tidak masuk sampel); "butuh X tenaga siber" = folklore
- **Verifikasi ganda**: (1) agent sintesis baca semua berkas, bedah kontradiksi antar-laporan (9M vs 456k vs 600k/tahun; populasi dev 800rb vs 4,37jt), 33 angka ditolak; (2) agent audit beda cek ulang 12 angka headline langsung ke sumber → 7 confirmed, 3 adjusted, 2 unreachable, 0 fabrikasi
- **Microdata asli**: Stack Overflow Developer Survey resmi diunduh, difilter `Country == Indonesia` per-baris (N=354 th 2024, N=181 th 2025) — bukan agregat, bukan klaim
- Angka sensitif-bias diurus eksplisit: "akun GitHub ≠ profesional", "training tickets ≠ pekerjaan", "registrasi platform ≠ penghasilan aktif", gaji "advertised ≠ placement"

## Struktur

```
index.html                       → dashboard (buka langsung di browser)
research/01..19-*.md             → 20 berkas riset lengkap, sumber per klaim
research/_consolidated/dataset.json  → 400+ datapoint merged, siap olah
research/_consolidated/tables.md → tabel salary/layoff/talent-series
```

## Cara baca angka

- **Hover / klik tiap angka** → tooltip: `S:` sumber, `C:` cara hitung/metode, `conf` kepercayaan + berkas asal. Klik luar = tutup. Mobile: tap
- Bandingkan **arah + urutan**, bukan desimal. Ambang ketidakpastian menempel di tiap label
- Meter kepercayaan 5-segmen: `4–5` resmi/audited · `3` survei bermetode · `≤2` konteks doang
- Dua keluarga gaji jangan dicampur: advertised (Glints/NodeFlair = lantai pasar, skew junior) vs placement (Michael Page/RW = plafon, skew senior)

## Batasan (jujur, tidak disembunyi)

- Applicants-per-vacancy IT spesifik: tak ada sumber publik
- Jumlah PNS-IT nasional: tak dipublikasikan siapa pun
- Market-research reports (IT services dll): bias lead-gen, sebaran definisi >2× antar-rumah
- Kaliber layar sempit: chart rata kiri; keseluruhan layout landscape optimal >900px

## Stack di balik layar

- Riset: 19 agent `GLM-5.3 (low effort)` + skill `research` (primary-source discipline) + `dispatching-parallel-agents`
- Build: skill `frontend-design` — terminal pasar ala papan trading, warna = semantik (hijau naik / merah turun / amber warning)
- QA: browser automation + model vision, cek desktop & mobile, misah bug layout bener (panah rantai, angka hero kepotong, nav mobile)

## Kredit data utama

PDDikti/Statistik PT 2025 · Dapodik SMK · DPR-RI brief (DTS audited) · data.komdigi.go.id · Kemnaker JKP · laporan tahunan audited (BCA, GoTo, Telkomsel, Bukalapak, Blibli) · e-Conomy SEA 2025 · NodeFlair payslip-verified · Michael Page/Robert Walters/Kelly · LinkedIn-WEF Jobs on the Rise · Stack Overflow Developer Survey · StartupBlink · ADB Institute · Sustainability/BRIN · IMPF/WDI ekspor ICT

Data = hasil kompilasi riset mandiri, per 9 Nov 2026. Bukan nasihat investasi/karier. Verifikasi sendiri lewat `research/` sebelum keputusan penting.
