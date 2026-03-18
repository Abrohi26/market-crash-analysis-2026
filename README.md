# Walmart Might Be The Most Important Stock Standing....Again!
### A $10M Capital Preservation Analysis | Power BI + Historical Market Data

![Power BI](https://img.shields.io/badge/Tool-Power%20BI-F2C811?style=flat&logo=powerbi&logoColor=black)
![Python](https://img.shields.io/badge/Tool-Python-3776AB?style=flat&logo=python&logoColor=white)
![Data](https://img.shields.io/badge/Dataset-1970%20to%202017-0D1F3C?style=flat)
![Status](https://img.shields.io/badge/Status-Complete-1E8449?style=flat)

---

## The Business Problem

A hiring manager is evaluating where to allocate a $10 million portfolio ahead of a potential market correction in 2026. Two macroeconomic triggers are active simultaneously: an ongoing U.S. Iran military conflict driving oil prices toward potentially $200 a barrel, and an AI investment cycle showing early warning signs of a valuation bubble.

The question is not which stocks look attractive right now. The question is: **what does 50 years of verified crash data actually tell us about capital preservation, and what decision should follow from that evidence?**

This project was built to answer that question with data, not opinion.

---

## What I Built

A full business analysis using Power BI across three of the most significant market crashes in modern history:

- **1973 to 1975** — The OPEC Oil Crisis
- **1999 to 2003** — The Dot Com Collapse  
- **2007 to 2010** — The Housing Crisis

The analysis covers 15 companies across 4 sectors over a 47 year period, maps current 2026 conditions against historical crash signatures, and produces a data-driven capital allocation recommendation framework.

---

## The Finding That Changed Everything

Going into this analysis I expected energy companies to be the answer in an oil shock environment. That is the conventional reading of the 1974 crisis.

The data said otherwise.

| Company | Sector | 1974 Return | Verdict |
|---|---|---|---|
| Walmart | Retail | **0.0%** | Held flat. Every other sector fell. |
| ExxonMobil | Energy | -31.6% | Crashed then recovered in 1975 |
| Chevron | Energy | -31.8% | Crashed then recovered in 1975 |
| JP Morgan | Financials | -29.9% | Crashed. Slow recovery. |
| IBM | Technology | -31.9% | Crashed then recovered in 1975 |

Walmart returned zero while every other company lost nearly a third of its value. Then in 1975 it returned 98.5%. The same pattern repeated in 2001 and again in 2008.

**Walmart is not the golden goose in a crisis. The data says Walmart is the titanium goose.**

---

## The $10,000 Simulation

If you invested $10,000 in 1970 and held through 2017 with no trading and no rebalancing:

| Company | Final Value | Multiple |
|---|---|---|
| Walmart (WMT) | $26,717,602 | 2,672x |
| Microsoft (MSFT) | $12,480,655 | 1,248x |
| Amazon (AMZN) | $5,712,437 | 571x |
| Apple (AAPL) | $4,120,742 | 412x |
| ExxonMobil (XOM) | $553,967 | 55x |
| Bank of America (BAC) | $73,421 | 7x |
| SPY (S&P 500 Index) | $24,634 | 2.5x |

The passive index returned $24,634. Walmart returned $26.7 million. Active selection of quality companies with pricing power outperformed the S&P 500 index by more than 1,000 times over 50 years.

---

## Visuals

### $10K Investment Value by Ticker
<img width="2767" height="1600" alt="Chart1_10K_Investment_Value_by_Ticker" src="https://github.com/user-attachments/assets/8853e7e5-a2b8-403f-aa52-d137688d0e17" />


### Total Return by Sector (1970 to 2017)
<img width="2767" height="1600" alt="Chart2_Total_Return_by_Sector_1970_2017" src="https://github.com/user-attachments/assets/2e73a13f-3af5-40c7-a3a0-b138c8bfd674" />


### Walmart Beat the 1974 Oil Crisis
<img width="2767" height="1600" alt="Chart3_Walmart_Beat_1974_Oil_Crisis" src="https://github.com/user-attachments/assets/a7b137b9-9b1f-4c09-abec-6b87e41e2a7f" />


### NVDA Defied the Dot Com Crash Until Consumer Spending Collapsed
<img width="2767" height="1600" alt="Chart4_NVDA_Defied_Dot_Com_Crash" src="https://github.com/user-attachments/assets/9da8d55a-4d43-432f-8414-46807331993e" />


### Three Crashes. Three Decades. One Winner.
<img width="2767" height="1600" alt="Chart5_Three_Crashes_Three_Decades_One_Winner" src="https://github.com/user-attachments/assets/6de13eee-ad3d-4724-afeb-1edc4f9ddb2c" />


---

## Methodology

### Data Sources
- **Primary:** Verified Power BI dataset covering 15 companies across 4 sectors from 1970 to 2017
- **Secondary:** Current market data from 2017 to 2026 sourced from public financial reporting
- **Crash windows analyzed:** 1973 to 1975, 1999 to 2003, 2007 to 2010

### Analytical Steps
1. Isolated each crash window and measured company level annual returns during the crash year, one year prior, and two years after
2. Scored each company on three variables: crash year performance, recovery speed, and long term compounding output
3. Identified cross-crash patterns, specifically which companies appeared in the top performance tier across multiple crash periods
4. Mapped current 2026 macro conditions against historical crash signatures to assess pattern similarity
5. Generated recommendations with explicit confidence levels: Verified, Current, Pattern-Based, or Estimate

### Confidence Level System
| Label | Definition |
|---|---|
| Verified | Direct output from the Power BI dataset. Historical fact. |
| Current | Known market data as of March 2026. Reportable fact. |
| Pattern-Based | Forward projection grounded in a verified historical pattern. |
| Estimate | Analytical projection with no direct historical precedent. |

---

## Key Findings

**Finding 1:** Consumer staples outperformed energy during the 1974 oil crisis. Walmart held flat while every energy company fell 30% or more. *[Verified]*

**Finding 2:** A company can outperform during a bubble burst and still collapse one year later from a separate cause. NVDA returned +305% in 2001 then fell 83% in 2002 when consumer spending contracted. *[Verified]*

**Finding 3:** The Walmart pattern held across three structurally different crashes over three decades. 1974 oil shock, 2001 dot com collapse, 2008 housing crisis. Same result each time. *[Verified]*

**Finding 4:** Active selection of quality consumer facing companies outperforms passive index investing by more than 1,000 times over 50 years. *[Verified]*

**Finding 5:** Current 2026 conditions show a strong pattern match to 1973 to 1974. Active oil shock plus peak AI valuations plus Federal Reserve policy bind. *[Pattern-Based]*

---

## 2026 Conditions vs. Historical Patterns

| Variable | 1974 Reading | 2026 Reading | Match |
|---|---|---|---|
| Oil supply shock | OPEC embargo | Strait of Hormuz threatened | HIGH |
| Fed policy bind | Cannot cut or hike without pain | Same bind active today | HIGH |
| Stock valuations at shock | CAPE ratio at 9. Stocks cheap. | CAPE ratio above 40. Expensive. | LOW similarity |
| Walmart positioning | Low cost trade-down destination | Same structural position | HIGH |

| Variable | Dot Com 2000 | AI Bubble 2026 | Match |
|---|---|---|---|
| Valuation ratio | CAPE hit 44 at peak | CAPE above 40 | HIGH |
| Revenue vs. spending | Companies spending ahead of revenue | OpenAI: $60B spend, $13B revenue | HIGH |
| Enterprise ROI data | B2B internet showing no returns | 95% of orgs report zero AI ROI | HIGH |

---

## Capital Allocation Recommendation Framework

Derived directly from the data findings. Each tier maps to a specific finding.

**Tier 1: Capital Defense (55%)** — Consumer Staples, Healthcare, Utilities, US Treasuries
*Basis: Findings 1, 3, 4. Verified pattern across three crashes.*

**Tier 2: Trigger-Specific Positioning (30%)** — Defense and Aerospace, Energy Producers, Gold
*Basis: Current 2026 triggers mapped against 1974 recovery pattern. Pattern-Based confidence.*

**Tier 3: Recovery Deployment Reserve (15%)** — Cash held to deploy at correction low into Microsoft, Alphabet, Walmart
*Basis: Finding 3, Apple 2008 recovery pattern. Deploy when market drops 30% or more.*

---

## Repository Structure

```
market-crash-analysis-2026/
│
├── README.md
│
├── data/
│   ├── 10K_Investment_Value_by_Ticker.csv
│   ├── Total_Return_by_Sector_1970_2017.csv
│   ├── Walmart_Beat_1974_Oil_Crisis.csv
│   ├── NVDA_Defied_Dot_Com_Crash.csv
│   └── Three_Crashes_Three_Decades_One_Winner.csv
│
├── visuals/
│   ├── Chart1_10K_Investment_Value_by_Ticker.png
│   ├── Chart2_Total_Return_by_Sector_1970_2017.png
│   ├── Chart3_Walmart_Beat_1974_Oil_Crisis.png
│   ├── Chart4_NVDA_Defied_Dot_Com_Crash.png
│   └── Chart5_Three_Crashes_Three_Decades_One_Winner.png
│
└── report/
    └── Walmart_BA_Analysis_FINAL.docx
```

---

## Tools Used

- **Power BI** — Data modeling, visualization, $10K simulation
- **Python** — PDF to PNG extraction, data processing
- **Historical Market Data** — 1970 to 2017 verified dataset
- **Claude AI** — Research framework and report drafting (fact-checked and corrected against verified dataset)

---

## What This Project Demonstrates

- Translating 50 years of raw financial data into a clear business recommendation
- Pattern recognition across multiple historical crash cycles
- Confidence level methodology: distinguishing verified findings from forward projections
- Data-driven decision framework that separates what the data proves from what it suggests
- End-to-end business analysis from problem statement through recommendation

---

## About

This project was built as a business analysis portfolio piece demonstrating the ability to turn historical data into actionable business recommendations. The financial data covers 1970 to 2017 and is verified. The 2026 forward projections are analytical estimates based on pattern analysis and do not constitute financial advice.

---

*March 2026*
