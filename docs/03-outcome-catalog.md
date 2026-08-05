# 03 — Outcome Catalog

A shared library of business outcomes, organized by the executive who buys them. Each maps to capabilities across multiple practices. Sellers use this to reframe tech-labeled leads into outcome conversations.

**Practice key:** D&AI = Data & AI · C&D = Copilot & Dynamics · SEC = Security & Compliance (incl. Azure) · BC = Business Central ERP

## CFO / Finance

| Outcome | Typical metric | Practices | Microsoft technologies |
|---|---|---|---|
| Faster monthly/quarterly close | Days to close | BC, D&AI, C&D | Business Central, Fabric, Power BI, Copilot for Finance/M365 |
| Forecast accuracy | Forecast vs. actual variance % | D&AI, BC, C&D | Fabric, Power BI, Azure ML, D365 |
| Cash flow / working capital | DSO, DPO, inventory days | BC, D&AI | Business Central, Fabric, Power BI |
| Lower audit & compliance cost | Audit hours, findings count | SEC, BC, D&AI | Purview, Business Central, compliance reporting |
| Consolidation across entities | Time to consolidated view | BC, D&AI | Business Central, Fabric |

## COO / Operations

| Outcome | Typical metric | Practices | Microsoft technologies |
|---|---|---|---|
| Order-to-cash cycle time | Days order → cash | BC, C&D, D&AI | Business Central, D365 Sales, Power Automate, Fabric |
| Inventory optimization | Stockouts, carrying cost, turns | BC, D&AI | Business Central, Fabric, Azure ML |
| Field/service utilization | Utilization %, first-time-fix rate | C&D, D&AI | D365 Field Service, Power BI |
| Process automation | Hours of manual work removed | C&D, D&AI, BC | Power Automate, AI Builder, Copilot Studio |

## CRO / Sales & Marketing

| Outcome | Typical metric | Practices | Microsoft technologies |
|---|---|---|---|
| Win rate / pipeline velocity | Win %, cycle length | C&D, D&AI | D365 Sales, Copilot for Sales, Fabric, Power BI |
| Quote turnaround | Hours quote-to-send | C&D, BC | D365, Power Platform, Business Central pricing |
| Customer retention / churn | NRR, churn % | D&AI, C&D | Fabric, Customer Insights, Azure ML |
| Rep productivity | Selling time per rep | C&D, SEC | Copilot for Sales, M365 Copilot (secured rollout) |

## CISO / Risk

| Outcome | Typical metric | Practices | Microsoft technologies |
|---|---|---|---|
| Reduced breach risk / posture | Secure Score, incidents, MTTR | SEC, D&AI | Defender, Sentinel, Entra |
| Compliance readiness (CMMC, HIPAA, SOC 2...) | Assessment score, gaps closed | SEC, D&AI | Purview, Compliance Manager |
| Safe AI enablement | % data estate labeled/governed; AI incidents | SEC, D&AI, C&D | Purview, Fabric governance, Copilot controls |
| Cyber-insurance readiness | Premium, coverage qualification | SEC | Defender suite, Entra, Sentinel |

## CIO / CHRO / Workforce

| Outcome | Typical metric | Practices | Microsoft technologies |
|---|---|---|---|
| Employee productivity via AI | Hours saved, adoption %, task cycle time | C&D, SEC, D&AI | M365 Copilot, Copilot Studio, Viva Insights |
| IT cost reduction / cloud optimization | Azure spend, license spend | SEC, D&AI | Azure (FinOps), M365 license rightsizing |
| Faster onboarding | Time-to-productivity | C&D, SEC | M365, Entra lifecycle, Copilot |
| Legacy system retirement | Systems retired, maintenance $ | BC, D&AI, SEC | Business Central, Fabric, Azure migration |

## How sellers use this

1. Lead arrives tech-labeled ("we want Power BI").
2. Find the row(s) that tech usually serves ("forecast accuracy," "faster close").
3. Ask the outcome question: *"What decision or result is this reporting supposed to improve?"*
4. The answer selects the play (doc 04) and reveals the practice mix.

## Notes

- Every row is deliberately multi-practice — that's the point of the catalog.
- Metrics listed are the customer's, not ours. Baseline them in discovery (doc 05).
- This catalog should be pressure-tested and extended by each practice director; treat rows as v0.1 hypotheses.
