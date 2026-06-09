zorthex-diffusion-lag
![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.20589503.svg)
Institutional Adaptation Latency — an independent, empirical framework measuring the lag with which complex systems metabolise a new reality. The public layer, L₁ (Public Attention Diffusion Lag), measures the temporal gap between when something becomes operationally real and when institutional attention consolidates around it.
Zorthex™ v2.0 · Dataset v2.0 · 70 phenomena · 7 domains · three-source verified · observation cut-off May 2026
---
Cite as
Santi, R. (2026). ZORTHEX — Institutional Adaptation Latency: Public Attention Diffusion Lag (L₁), v2.0 (2.0). Zenodo. https://doi.org/10.5281/zenodo.20589503
---
What is Zorthex
Zorthex is an independent research practice measuring institutional adaptation latency — how long complex systems take to absorb a new reality.
The public metric is L₁:
> **L = t_peak − t_start** (months) — the observable gap between when a technology, regulation, or phenomenon becomes operationally real and when public attention structurally consolidates around it.
What closes that gap is a legibility event — a regulatory mandate, an institutional anchor, or a narrative compression that suddenly makes a category readable to those who allocate capital and attention. Search volume does not cause the consolidation; it follows it.
Zorthex does not predict by sector. It positions by regime. The regime determines the shape of the attention curve and the nature of the trigger.
Zorthex is descriptive only and does not constitute investment or legal advice. It documents temporal coincidence, never causation.
Full methodology: zorthex.com/methodology
---
Framework v2.0 — Key Features
Core Definitions
t_start — first documented public emergence, justified with a primary source (Level A–D)
t_peak — first month of 12 consecutive months ≥25/100 on Google Trends (Worldwide)
L — t_peak − t_start, in months (assigned only for STRUCTURAL cases)
Classifications
STRUCTURAL — ≥25/100 for 12+ consecutive months; L is assigned
OBSERVATION — above threshold, fewer than 12 consecutive months; L provisional
BUBBLE — threshold crossed without sustained consolidation
PRE-DATASET / NON-STATIONARY — peak coincides with start of available data, or an exogenous shock dominates; excluded from L averaging
Four-Regime Taxonomy
Regime	Pattern	Examples
Policy-Trigger	Slow multi-year ramp, breakout on a regulatory trigger	Stablecoins, Open Banking
Institutional Mass	Years of invisibility, then institution-led adoption	Zero Day Vulnerability, Precision Medicine
Market-Narrative	Narrative- and market-driven consolidation	Bitcoin, iPhone, TikTok
Shock/Spoke	Single-event spike, memory-zero collapse	GDPR, NFT, Metaverse
Three-Source Verification
Each case is positioned using three independent attention signals, kept methodologically distinct rather than blended:
Google Trends (operational signal) — active search; the metric L is computed here. CSV snapshots downloaded manually and archived (snapshot-locking → reproducibility).
Wikipedia pageviews (informational signal) — absolute pageviews via the Wikimedia API; a corrective to search-index renormalization.
Reddit (community signal) — a declared qualitative proxy, never converted into a number.
Key Findings (v2.0)
Cluster Renormalization Effect & the "rock rule": a large attention wave (August 2025) retroactively rescales historical Google Trends series. A historical all-time peak yields a stable L; a recent peak within the wave yields a provisional L (marked OBSERVATION).
Dual-velocity attention: in B2B-infrastructure and policy-driven phenomena, operational attention precedes informational/mainstream attention. Declared as a structural finding, not concealed as a limitation.
---
Dataset — Current State
70 phenomena across 7 domains · three-source verified · observation cut-off May 2026 · DOI: 10.5281/zenodo.20589503
Values are subject to revision; re-verification recommended every 90 days, mirroring the dated and revisable nature of credit ratings.
Verified STRUCTURAL cases (L confirmed against snapshot-locked CSV)
Phenomenon	Domain	t_start	t_peak	L (mo)
iPhone	Consumer	2007-01	2009-06	29
Cloud Computing	Security	2006-08	2009-03	31
TikTok	Consumer	2017-09	2020-04	31
Facebook	Consumer	2004-02	2009-01	59
CBDC	Financial	2017-08	2022-09	61
Virtual Reality	Consumer	2010-01	2015-12	71
Open Banking	Financial	2015-10	2022-01	75
Web3	AI Governance	2014-01	2021-12	95
Cryptocurrency	Financial	2013-01	2021-01	96
CRISPR	Biotech	2012-06	2020-09	99
Stablecoins	Financial	2014-10	2025-06	128
Endpoint Security	Security	2007-01	2019-01	144
Cybersecurity	Security	2013-02	2025-02	144
Bitcoin	Financial	2008-10	2020-12	146
Buy Now Pay Later	Financial	2005-07	2018-08	157
Precision Medicine	Biotech	2011-09	2025-06	165
Liquid Biopsy	Biotech	2010-09	2025-06	177
Zero Day Vulnerability	Security	2005-01	2024-04	231
Basel III (L≈0) is retained as an immediate-attention reference case. Cases with extreme lag (e.g. Carbon Capture, mRNA, Digital Nomad) or non-stationary dynamics (Remote Work, Telemedicine) are retained in the full dataset for completeness but excluded from L averaging.
Full dataset (all 70 cases, including Observation, Bubble and Pre-dataset): zorthex.com/dataset
> The August 2025 super-cluster: 27 cases crossed the 25/100 threshold within the same month across 6 domains. Declared temporal clustering — a systemic signal, not a methodological artifact.
---
Research Direction: L₂ (in development)
A second metric — institutional adaptation latency (L₂) — extends the same logic to the gap between a formalized norm and its operational reality. L₂ is recorded here only to document its standing within the broader research programme. It is not part of the public v2.0 dataset, and no L₂ values are published in this repository.
---
Verified Custom Reports (ZCR Series)
ID	Title	L	Status
ZCR-2026-001	Stablecoins as Treasury Infrastructure	128mo	STRUCTURAL Active
ZCR-2026-002	Post-Quantum Cryptography	—	OBSERVATION (under revision)
ZCR-2026-003	Real-World Asset Tokenization	103mo	OBSERVATION Active
Full reports: zorthex.com/research
---
Version Changelog
Version	DOI	Date	Notes
v1.0	10.5281/zenodo.20049068	Apr 2026	Initial, n=11, 3-month window
v1.1	10.5281/zenodo.20072999	May 2026	12-month window, BUBBLE, n=12
v1.2	10.5281/zenodo.20270575	May 2026	t_start policy A–D, CSV locking
v1.3	10.5281/zenodo.20374051	May 2026	4-regime taxonomy, n=50
v2.0	10.5281/zenodo.20589503	Jun 2026	70 cases, 7 domains, three-source verified, dual-velocity finding, rock rule
---
Repository Structure
`index.html` — homepage and live framework app
`dataset.html` — full public dataset, 70 cases, regime and three-factor flags
`methodology.html` — complete methodological documentation
`research.html` — ZCR demonstration reports
`CLAUDE.md` — declared role of Claude in the Zorthex project
`ZCR-2026-00*.html` — verified Custom Reports
`*.csv` — locked Google Trends snapshots per case
---
License & Contact
License: CC BY-NC 4.0
Trademark: ZORTHEX™ — UIBM N.302026000090628
ORCID: 0009-0000-9936-1110
© 2026 Renato Santi · zorthex.com · Powered by Claude
If you follow this pipeline and obtain different results — that is a contribution, not a problem.
