# Luxembourg AI Workforce Impact Analysis

> *"57.6% of Luxembourg's workforce holds AI-resilient jobs — but 65,000 workers face high automation risk by 2030."*

A sector-by-sector analysis of how artificial intelligence and automation will reshape Luxembourg's workforce through 2030, including job displacement scenarios, reskilling capacity gaps, and the outsized exposure of Luxembourg's large foreign-worker population.

---

## Why Luxembourg?

Luxembourg is Europe's wealthiest nation per capita — built on Finance, logistics, and a uniquely international workforce where **47% of residents are foreign-born** and **220,000+ cross-border workers** commute in daily. This makes AI disruption here a uniquely human story: the sectors most exposed to automation are also the ones most dependent on immigrant and cross-border labour.

---

## Key Findings

| Metric | Value |
|--------|-------|
| Total Workforce Analysed | 518,020 |
| High Automation Risk Workers | 65,000 (12.6%) |
| Medium Automation Risk | 155,000 (30.0%) |
| AI Resilient Workers | 298,000 (57.6%) |
| Most At-Risk Sector | Retail & Trade (80% AI risk) |
| Safest Sector | Healthcare (15% AI risk) |
| Reskilling Coverage Gap | Finance sector — only 12.6% covered |

---

## Repository Structure

```
Luxembourg-AI-Workforce-Impact/
│
├── data/
│   ├── AI_Impact_Scenarios.csv             # Best/Baseline/Worst job change by 2030
│   ├── AI_Impact_Risk_Distribution.csv     # Workforce split by automation risk level
│   ├── AI_Impact_Sector_Data.csv           # Sector employment + 2030 forecasts
│   ├── Sector_Salary_Data.csv              # Average salaries by sector
│   ├── Foreign_Workers_By_Sector.csv       # % foreign & cross-border workers per sector
│   ├── AI_Adoption_Timeline.csv            # When AI disruption peaks per sector
│   └── Reskilling_Capacity.csv             # Training capacity vs workers at risk
│
└── README.md
```

---

## Scenarios: What Could Happen by 2030?

| Scenario | Net Jobs Change | Wage Growth | Probability |
|----------|----------------|-------------|-------------|
| ✅ Best Case — Reskilling succeeds | **+15,000** | +2.5% | 25% |
| ➡️ Baseline — No intervention | **-4,000** | +0.3% | 50% |
| ⚠️ Worst Case — No reskilling support | **-20,000** | -1.0% | 25% |

The most likely outcome (50% probability) is a net loss of 4,000 jobs — but this hides significant sector-level disruption with winners and losers.

---

## Sector Deep Dive

| Sector | Employment | AI Risk | Foreign Workers | Peak Disruption |
|--------|-----------|---------|----------------|-----------------|
| Healthcare | 45,000 | 🟢 15% | 50% | 2029 |
| Finance | 129,850 | 🟡 55% | 57.8% | 2027 |
| IT & Technology | 28,500 | 🔴 75% | 57.9% | 2026 |
| Public Admin | 67,420 | 🟢 25% | 26.7% | 2030 |
| Construction | 42,300 | 🟡 45% | 66.2% | 2029 |
| Retail & Trade | 78,000 | 🔴 80% | 52.6% | 2026 |
| Manufacturing | 35,200 | 🟡 50% | 59.7% | 2027 |
| Logistics | 28,400 | 🔴 60% | 63.4% | 2028 |
| Education | 22,500 | 🟢 20% | 33.3% | 2030 |
| Other Services | 40,850 | 🟢 30% | 49.0% | 2029 |

> 📌 The sectors with the **highest AI risk** (Retail, Logistics, IT) are also the ones with the **highest concentration of foreign and cross-border workers** — making this an immigration story as much as a technology story.

---

## The Reskilling Gap

Even in the best-case scenario, reskilling programs must scale dramatically. Current capacity falls far short:

| Sector | Workers At Risk | Training Capacity | Coverage |
|--------|----------------|-------------------|---------|
| Finance | 71,418 | 9,000/yr | ⚠️ 12.6% |
| Retail & Trade | 62,400 | 3,000/yr | 🔴 4.8% |
| Construction | 19,035 | 2,000/yr | 🔴 10.5% |
| Education | 4,500 | 5,000/yr | ✅ 100% |
| Healthcare | 6,750 | 4,500/yr | 🟡 66.7% |

The Finance sector alone has **62,418 workers not covered** by existing reskilling programmes — the largest gap in absolute terms.

---

## Connection to Luxembourg Demographics

This project is the companion analysis to [Luxembourg Demographics Analysis](https://github.com/KhadijaTheAnalyst/Luxembourg-Demographics-Analysis). The core insight linking both:

- Luxembourg's workforce is **heavily foreign** (57%+ in Finance, IT, Manufacturing, Logistics)
- These are **the same sectors facing the highest AI disruption**
- Reskilling programmes will need to be multilingual, accessible to cross-border workers, and sensitive to the diverse backgrounds of Luxembourg's workforce

---

## Tools Used

| Tool | Purpose |
|------|---------|
| Python (pandas, NumPy) | Data modelling & scenario analysis |
| Power BI | Interactive sector dashboard |
| Excel | Scenario modelling |
| STATEC / Eurostat | Data sources |

---

## Author

**Khadija Mustafa** — Data Analyst & ML Engineering Student  
📍 Luxembourg | 📧 engr.khadija.hussain@gmail.com  
[LinkedIn](https://www.linkedin.com/in/khadija-mustafa-98344527b/) · [GitHub](https://github.com/KhadijaTheAnalyst)

---
*Data modelled from STATEC 2024–2025, Eurostat Labour Force Survey, and published AI impact research*
