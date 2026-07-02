# D2C Skincare Pricing Strategy — £1.4M ARR Brand · 12 SKUs

**Sector:** D2C · Skincare · £1.4M ARR &nbsp;|&nbsp; **Duration:** ~4 weeks equivalent &nbsp;|&nbsp; **Method:** Van Westendorp PSM + Competitor Benchmarking + Margin Waterfall

---

## The Brief

A D2C skincare brand generating ~£1.4M ARR across 12 SKUs had not changed prices in 3 years. The founder suspected the brand was underpriced — the product was premium in positioning but the prices felt misaligned with where the brand had evolved to.

The engagement was structured as a three-part pricing analysis: survey-based consumer willingness-to-pay research (Van Westendorp PSM), 8-competitor price benchmarking, and a full 12-SKU margin waterfall at current vs proposed prices.

---

## Analytical Framework — Three-Way Triangulation

**Root question:** Is this brand underpriced, and if so by how much — and what is the financial impact of a price correction?

| Branch | Method | What It Answers |
|---|---|---|
| 1 — Van Westendorp PSM | Survey n=340 (brand email list) | Consumer price floor, optimal point, and ceiling for 3 hero SKUs |
| 2 — Competitor Benchmarking | 8 real UK D2C brands, 2024-25 prices | Where this brand sits in the market — revealed preference |
| 3 — Margin Waterfall | 12-SKU model, elasticity -0.8 | GP impact of proposed prices net of volume decline |
| 4 — Triangulated Recommendation | Three-way convergence | Where all three methods agree — that's the recommended price |

---

## Van Westendorp — The Four Intersection Points

The PSM methodology asks 340 survey respondents four questions about each hero SKU. Cumulative frequency curves are plotted and four price thresholds derived:

| Threshold | What It Means |
|---|---|
| PMC — Point of Marginal Cheapness | Below this price, quality doubt begins. Do not price below PMC. |
| IPP — Indifference Price Point | Equal numbers find the price too cheap as too expensive. Maximum ambivalence. |
| OPP — Optimal Price Point | Maximum acceptance — fewest objections. This is the recommended price anchor. |
| PME — Point of Marginal Expensiveness | Above this price, the majority will not buy. The psychological ceiling. |

---

## Key Findings

### Finding 1 — Brand is underpriced (all three methods agree)
PSM OPP sits £2–£8 above current prices on every hero SKU. Competitor analysis shows the brand priced £10–15 below mid-premium peers (REN Clean Skincare, Paula's Choice, Medik8). Current gross margins of 70.6% sit below what the brand's pricing power would support.

### Finding 2 — Top 4 SKUs are 14–22% below the acceptable price ceiling
The PSM PME (the 'expensive but still worth it' threshold) ranges from £35.70 for the Vitamin C Serum to £48.00 for the Retinol. The Retinol is currently priced at £38 — 21% below its consumer ceiling, and below competitors REN (£44) and Medik8 (£42). A premium retinol priced below mid-premium competitors sends a damaging quality signal.

### Finding 3 — Repricing adds £67K in gross profit at conservative elasticity
At a price elasticity of -0.8 (conservative for premium D2C skincare), the price gain on remaining volume more than offsets the volume decline. Net GP uplift: £66,809. Gross margin improves from 70.6% to 74.6%, moving into top-quartile territory for DTC beauty.

### Finding 4 — Packaging refresh is non-negotiable before the price change
A price increase without a visible product refresh looks opportunistic. With it, it reads as brand evolution. New copy, updated packaging, and an "active ingredients" narrative provide the psychological anchor for the new prices.

---

## Competitor Benchmarking — Real Brands, Real Prices

| Brand | Tier | Serum 30ml | Moisturiser 50ml | Retinol 30ml |
|---|---|---|---|---|
| The Ordinary | Accessible | £12.90 | £15.90 | £12.90 |
| The Inkey List | Accessible | £14.99 | £18.99 | £13.99 |
| Byoma | Accessible+ | £17.99 | £21.99 | — |
| Pixi Beauty | Mid-Market | — | £32.00 | — |
| **CLIENT BRAND** | **Mid-Premium (frozen)** | **£28.00** | **£32.00** | **£38.00** |
| REN Clean Skincare | Mid-Premium | £38.00 | £42.00 | £44.00 |
| Paula's Choice | Premium | £44.00 | £48.00 | £49.00 |
| Medik8 | Premium | £39.00 | £42.00 | £42.00 |
| Elemis | Luxury | £70.00 | £75.00 | £72.00 |

Sources: brand websites, Cult Beauty, Boots — 2024-25 prices.

---

## Recommended Prices (Hero SKUs)

| SKU | Current | PSM OPP | PSM PME | Recommended | Increase |
|---|---|---|---|---|---|
| Vitamin C Serum 30ml | £28.00 | £30.20 | £35.70 | £33.00 | +18% |
| HA Moisturiser 50ml | £32.00 | £35.50 | £41.80 | £37.00 | +16% |
| Retinol Night Treatment 30ml | £38.00 | £44.00 | £48.00 | £46.00 | +21% |

All recommendations anchor at or near PSM OPP — maximum acceptance — not at PME ceiling. Prices sit between mid-market and premium competitor range.

---

## Honest Limitations

**PSM is stated preference.** Respondents saying they'd buy at £33 doesn't guarantee they will. Mitigated by: triangulation with competitor market data, pricing at OPP not PME, and 90-day post-change monitoring.

**Elasticity assumption.** A -0.8 elasticity is used — conservative for premium DTC skincare, where brands like REN and Paula's Choice have raised prices 15-20% with minimal volume impact. If actual elasticity is higher (say -1.5), the GP uplift narrows. Rollback trigger: if conversion drops >20% without recovery by week 6.

**Simulated survey data.** Survey responses were generated using normal distributions calibrated to UK D2C skincare price norms. A real engagement would use actual survey responses from the brand's email list via Typeform. The methodology is identical — the calibration reflects the market.

---

## Industry Benchmarks Used

- DTC beauty gross margin: 65–72% typical, median 69.4% (Eightx 2026, citing SEC 10-K: e.l.f. 71.2%, Olaplex 69.4%)
- Premium serum target GM: 60%+ for D2C (Cosmesure UK NPD Playbook)
- Price elasticity for premium D2C skincare: -0.5 to -1.2 (range used: -0.8 conservative)

---

## Files

| File | Description |
|---|---|
| `analysis.py` | Full 4-branch analysis, PSM computation, 6 charts |
| `build_excel.py` | 5-sheet workbook builder |
| `outputs/Skincare_Pricing_Strategy_VaishnaviBhor.xlsx` | Executive Summary → PSM → Competitor → Margin → Recommendation |
| `charts/` | 6 charts (PNG) |

---

## About

**Vaishnavi Bhor** — Business & Data Analyst  
MSc Business Analytics, University of Manchester  
[linkedin.com/in/vaishnavi-bhor-business-analyst](https://linkedin.com/in/vaishnavi-bhor-business-analyst) · vbhor207@gmail.com · [vbho.github.io/portfolio](https://vbho.github.io/portfolio)
