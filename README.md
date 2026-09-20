# zorthex-diffusion-lag

**Public Attention Diffusion Lag (L₁)** — an independent, empirical framework
measuring the temporal gap between when something becomes operationally real
and when public attention structurally consolidates around it.

`Framework v2.0` · `Dataset v2.2` · `71 phenomena` · `7 domains` ·
`three-source verified` · `observation cut-off August 2026`

**Cite as**
Santi, R. (2026). *ZORTHEX — Institutional Adaptation Latency: Public Attention
Diffusion Lag (L₁), v2.0.* Zenodo. https://doi.org/10.5281/zenodo.20589503

---

## What Zorthex measures

    L = t_peak − t_start   (months)

The observable gap between the moment a technology, regulation or phenomenon
becomes operationally real, and the moment public attention consolidates
around it.

What closes that gap is a **legibility event** — a regulatory mandate, an
institutional anchor, or a narrative compression that makes a category
suddenly readable to those who allocate capital and attention. Search volume
does not cause consolidation; it follows it.

Zorthex is **diagnostic, not predictive**. It answers three questions: where
an attention window is open, how wide the gap has historically been, and what
type of breakout the data indicates — sustained or event-driven. It documents
temporal coincidence, never causation, and does not constitute investment or
legal advice.

Full methodology: https://zorthex.com/methodology

### Theoretical position

Rogers (1962), Bass (1969) and Moore (1991) all treat diffusion time as
**endogenous** — shaped by communication, imitation and peer reference inside
the social system. For regulated domains, the driver is **exogenous**: a norm
does not spread by word of mouth. It arrives, and it switches the regime
rather than accelerating an existing curve. No population-scale, real-time
instrument for public attention existed in 1962, 1969 or 1991. This framework
measures that exogenous transition.

---

## Core definitions

| Term | Definition |
|---|---|
| `t_start` | First documented operational emergence, justified with a primary source (Level A–D) |
| `t_peak` | First month of Google Trends ≥ 25/100 (Worldwide) |
| `L` | `t_peak − t_start`, in months — assigned only to STRUCTURAL cases |

The 25/100 threshold and the 12-month rule are **conventional**, not derived.
Both are declared so that anyone can recalculate with different values.

## Classifications

| Class | Rule |
|---|---|
| **STRUCTURAL** | ≥ 25/100 for 12+ consecutive months. `L` is assigned. Permanent. |
| **OBSERVATION** | Above threshold, fewer than 12 consecutive months. `L` provisional. |
| **SPIKE & RETREAT** | Reached threshold, did not sustain 12 months. *New — August 2026. 10 cases.* |
| **BUBBLE** | Sharp spike, rapid collapse. Never consolidated. |
| **PRE / NON-STATIONARY** | Peak predates available data, or an exogenous shock dominates. Excluded from `L` averaging. |

Classification is permanent once earned — like a credit rating at issuance.

### Operational status — *new, August 2026*

A second axis applied **only to STRUCTURAL cases**, updated every 90 days. It
describes current attention and never modifies the classification.

`DOMINANT` (40+ consecutive months) · `ACTIVE` (above threshold now) ·
`RECEDING` (STRUCTURAL, currently below) · `CYCLICAL` (waves) ·
`DEAD` (term replaced or abandoned)

Example: *SMR · STRUCTURAL · Receding* and *Streaming · STRUCTURAL · Dominant*
carry the same classification and describe entirely different realities.

## Four-regime taxonomy

| Regime | Pattern | Examples |
|---|---|---|
| **Policy-Trigger** | Slow multi-year ramp, breakout on a regulatory event | Stablecoins, Open Banking |
| **Institutional Mass** | Years of invisibility, then institution-led adoption | Zero Day Vulnerability, RWA Tokenization |
| **Market-Narrative** | Narrative- and market-driven consolidation | Bitcoin, iPhone, TikTok |
| **Shock/Spoke** | Single-event spike, memory-zero collapse | GDPR, NFT, Metaverse |

---

## Three-source verification

Each case is positioned using three independent attention signals, kept
methodologically distinct rather than blended. **The gap between the three
sources is the signal.**

- **Google Trends** — *operational attention.* Active search. `L` is computed
  here. CSV snapshots downloaded manually and archived (snapshot-locking →
  reproducibility).
- **Wikipedia pageviews** — *informational attention.* Absolute pageviews via
  the Wikimedia API; an independent corrective to search-index
  renormalization.
- **Reddit** — *community attention.* A declared qualitative proxy, never
  converted into a number.

### Why not social media

Search and encyclopaedia traffic record a decision to look for something.
Platform engagement records what an algorithm decided to display. The first
measures demand, the second supply. Feeds are personalised, non-reproducible
and manipulable through paid amplification; Google Trends and Wikipedia are
free, timestamped and archivable. Measuring attention through feeds would
measure the distribution system rather than the interest.

---

## Findings

**Cluster renormalization effect ("rock rule").** A large attention wave
retroactively rescales historical Google Trends series. A historical all-time
peak yields a stable `L`; a recent peak within the wave yields a provisional
`L`, marked OBSERVATION.

**The August 2025 super-cluster.** 27 cases crossed the 25/100 threshold
within the same month across 6 domains. Declared temporal clustering — a
systemic signal, not a methodological artifact.

**Dual-velocity — static.** In B2B-infrastructure and policy-driven
phenomena, operational attention precedes informational attention. Declared
as a structural finding, not concealed as a limitation.

**Dual-velocity — transitional.** *New, August 2026.* Wikipedia pageviews
declining while Google Trends holds or rises, observed in 5 of 7 cases
verified at three sources: Stablecoins −46% YoY, Zero Day −42%, Endpoint
−35%, Open Banking −34%, PQC −12%. The reading: specialists stop consulting
the encyclopaedia because they already know the subject, while the public
arrives via search. The signature of a phenomenon crossing from specialist
knowledge into public vocabulary.

**Sustained vs. event-driven.** *New, August 2026.* Phenomena with daily
operational triggers consolidate after breakout. Phenomena with institutional
or policy triggers spike and retreat. Of the 10 Spike & Retreat cases, 8 are
governance or policy phenomena. The trigger type diagnoses the breakout type
— not whether a breakout occurs, but how it unfolds.

---

## Dataset — current state

`71 phenomena` · `7 domains` · `three-source verified` ·
`observation cut-off August 2026` · DOI: 10.5281/zenodo.20589503

Values are subject to revision. Re-verification runs every 90 days, mirroring
the dated and revisable nature of credit ratings.

### August 2026 revision — result

| Outcome | Count |
|---|---|
| STRUCTURAL confirmed | 28 |
| Promoted to STRUCTURAL | 18 |
| Spike & Retreat (new category) | 10 |
| OBSERVATION confirmed | 5 |
| BUBBLE confirmed | 4 |
| PRE → STRUCTURAL | 1 |
| Error corrected | 1 |
| Special notes | 2 |
| **Total** | **71** |

The revision re-ran the full pipeline against updated sources. The Spike &
Retreat category was not hypothesised in advance — it emerged when 10 cases
clustered around a behaviour that existing classifications did not describe.

### Verified STRUCTURAL cases

`L` confirmed against snapshot-locked CSV.

| Phenomenon | Domain | t_start | t_peak | L (mo) |
|---|---|---|---|---|
| iPhone | Consumer | 2007-01 | 2009-06 | 29 |
| Cloud Computing | Security | 2006-08 | 2009-03 | 31 |
| TikTok | Consumer | 2017-09 | 2020-04 | 31 |
| CBDC | Financial | 2017-08 | 2022-09 | 61 |
| Virtual Reality | Consumer | 2010-01 | 2015-12 | 71 |
| Open Banking | Financial | 2015-10 | 2022-01 | 75 |
| Web3 | AI Governance | 2014-01 | 2021-12 | 95 |
| Cryptocurrency | Financial | 2013-01 | 2021-01 | 96 |
| CRISPR | Biotech | 2012-06 | 2020-09 | 99 |
| RWA Tokenization | Financial | TBD | TBD | 103 |
| Stablecoins | Financial | 2014-10 | 2025-06 | 128 |
| Endpoint Security | Security | 2007-01 | 2019-01 | 144 |
| Cybersecurity | Security | 2013-02 | 2025-02 | 144 |
| Bitcoin | Financial | 2008-10 | 2020-12 | 146 |
| Buy Now Pay Later | Financial | 2005-07 | 2018-08 | 157 |
| Precision Medicine | Biotech | 2011-09 | 2025-06 | 165 |
| Liquid Biopsy | Biotech | 2010-09 | 2025-06 | 177 |
| Zero Day Vulnerability | Security | 2005-01 | 2024-04 | 231 |
| Small Modular Reactors | Energy | 2005-05 | 2025-08 | 243 |

**Notes.** *Facebook* was previously listed here with L = 59; as of the August
2026 revision the term is classified **DEAD** (replaced by "Meta"). The
classification remains a historical fact; the word does not. *Basel III*
(L ≈ 0) is retained as an immediate-attention reference case. Cases with
extreme lag or non-stationary dynamics are retained in the full dataset for
completeness but excluded from `L` averaging.

**Duration records.** Streaming 218 months above threshold · iPhone 208 ·
Wind Energy 138 · BNPL 89 · Cloud Computing 62. Longest measured lag: Digital
Nomad, L = 325.

Full dataset, all 71 cases including Observation, Spike & Retreat, Bubble and
Pre-dataset: https://zorthex.com/dataset

---

## Published reports

| ID | Title | Series |
|---|---|---|
| ZSR-2026-001 | The Window Before the Window Closes — Critical Minerals | Signal |
| ZCR-2026-001 | Stablecoins as Treasury Infrastructure | Custom |
| ZCR-2026-002 | Post-Quantum Cryptography | Custom |
| ZCR-2026-003 | Real-World Asset Tokenization | Custom |
| ZCR-2026-004 | The AI Sustainability Gap | Custom |
| ZCR-2026-005 | Small Modular Reactors | Custom |
| ZCR-2026-007 | mRNA Cancer Vaccine | Custom |
| ZSA-2026-001 | Dual-Velocity | Cross-dataset |
| ZSA-2026-002 | Attention Before Action | Cross-dataset |
| ZSA-2026-003 | Stablecoins as Conflict Infrastructure | Cross-dataset |

Full reports: https://zorthex.com/research

---

## Declared limitations

- **It does not predict.** The framework measures when public attention
  arrived. It is a timing instrument, not a forecasting model.
- **The threshold is conventional.** 25/100 is a choice. A phenomenon of
  extreme sectoral importance that never reaches 25 is real but invisible
  here. The threshold measures public legibility, not relevance.
- **`L` is sensitive to `t_start`.** A different anchor date produces a
  different number. Every `t_start` is documented with a source and level.
- **n = 71 is a small sample.** Patterns are observable; distributional
  claims require caution.
- **Attention is not adoption.** `L` measures public visibility, not market
  penetration. The two often correlate; they are not the same thing.
- **Google Trends renormalizes.** The same query downloaded at different
  times yields different absolute values. This is why CSVs are locked and
  timestamped.
- **Retrospective, not real-time.** STRUCTURAL classification requires 12
  months of data and is therefore always at least 12 months behind the
  breakout.

---

## Revision policy

The dataset is revised every 90 days. Each revision may promote, reclassify
or add cases. CSV snapshots are locked and archived.

| Revision | Version | Cases |
|---|---|---|
| August 2026 *(current)* | v2.2 | 71 |
| May 2026 | v2.0 | 70 |
| November 2026 *(next)* | — | — |

Classifications are never downgraded. A STRUCTURAL case remains STRUCTURAL
even if its current score drops to zero; the operational status captures what
happens afterwards.

## Changelog

| Version | DOI | Date | Notes |
|---|---|---|---|
| v1.0 | 10.5281/zenodo.20049068 | Apr 2026 | Initial, n=11, 3-month window |
| v1.1 | 10.5281/zenodo.20072999 | May 2026 | 12-month window, BUBBLE, n=12 |
| v1.2 | 10.5281/zenodo.20270575 | May 2026 | t_start policy A–D, CSV locking |
| v1.3 | 10.5281/zenodo.20374051 | May 2026 | 4-regime taxonomy, n=50 |
| v2.0 | 10.5281/zenodo.20589503 | Jun 2026 | 70 cases, 7 domains, three-source verified, dual-velocity, rock rule |
| v2.2 | — | Sep 2026 | August revision: 71 cases, Spike & Retreat, operational status, transitional dual-velocity |

---

## Repository structure

    index.html            homepage and live framework app
    dataset.html          full public dataset, regime and three-factor flags
    methodology.html      complete methodological documentation
    research.html         published reports
    ZCR-2026-00*.html     verified Custom Reports
    *.csv                 locked Google Trends snapshots, per case
    CLAUDE.md             declared role of Claude in the Zorthex project

---

## License & Contact

**Historical archive (through August 2026).** All dataset revisions published
in this repository — v2.0 (May 2026, 70 cases) and v2.2 (August 2026, 71
cases) — are released under
[CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/). Free to use,
share and adapt for non-commercial purposes with attribution. **This grant is
permanent and will not be withdrawn.**

**From the November 2026 revision onward**, published output moves to a
restricted licence and will not be released in this repository. The
historical archive above stays open and replicable.

Copyright is retained in full by the author. No rights have been assigned or
exclusively licensed to any party.

---

**Trademark** ZORTHEX™ — UIBM N. 302026000090628
**ORCID** [0009-0000-9936-1110](https://orcid.org/0009-0000-9936-1110)
**DOI** [10.5281/zenodo.20589503](https://doi.org/10.5281/zenodo.20589503)
**Web** [zorthex.com](https://zorthex.com)

© 2026 Renato Santi · Powered by Claude

*If you follow this pipeline and obtain different results — that is a
contribution, not a problem.* Open an issue or write to
zorthex.official@gmail.com.
