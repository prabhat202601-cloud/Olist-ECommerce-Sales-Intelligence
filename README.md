# Olist E-Commerce Sales Intelligence
### 100,000 Orders · R$15.4M Revenue · 4 Analysis Phases · Built with Claude AI
---
## Overview
A full-stack data intelligence project built on the Olist Brazilian E-Commerce dataset (Kaggle), covering 100,000 orders across 9 merged datasets from 2016 to 2018. The project spans four structured analytical phases — from raw data exploration to RFM customer segmentation to delivery impact and churn analysis — executed entirely inside Claude AI using natural language.
Built to demonstrate end-to-end analytical thinking that connects raw data to decisions a business leadership team can act on.

---

## Dataset

- **Source:** Olist Brazilian E-Commerce Public Dataset (Kaggle)
- **Coverage:** 99,441 orders · September 2016 to October 2018
- **Files merged:** 9 raw datasets → 1 master dataset (32 columns)
- **Total revenue:** R$15.4M across 96,478 delivered orders
- **Missing values:** Only 2 critical issues in the entire dataset

---

## Project Outputs

| File | Description |
|------|-------------|
| `olist_phase1_exploration.html` | Phase 1 interactive dashboard — KPI cards, top categories, revenue by state, order status, payment methods, review scores, and dataset schema |
| `olist_summary_charts.html` | Phases 2, 3 and 4 summary dashboard — monthly revenue, RFM segmentation bubble chart, delivery cliff analysis, and churn risk charts |
| `Olist_ECommerce_Intelligence.pptx` | 13-slide stakeholder presentation covering all 4 phases with full statistical findings and business recommendations |

---

## Workflow — 4 Analysis Phases

```
Phase 1: Data Exploration      →  Merge 9 files, profile 32 columns, identify data quality issues
Phase 2: Revenue & Sales       →  Monthly trends, category analysis, geographic breakdown
Phase 3: RFM Segmentation      →  Score 93,358 customers, build 8 behavioural segments
Phase 4: Delivery & Churn      →  Quantify delivery impact on satisfaction and revenue loss
```

**Zero code written manually.** Every step was prompted in plain English inside Claude AI.

---

## Key Metrics

| KPI | Value |
|-----|-------|
| Total Revenue | R$15.4M |
| Avg Order Value | R$159.86 |
| Avg Review Score | 4.16 / 5 |
| Single-Purchase Rate | 97% |
| Revenue at Risk | R$6.15M |
| YoY Revenue Growth | 22% (2017 → 2018) |
| Peak Month | R$1.15M (Nov 2017, Black Friday) |

---

## Key Findings

### Phase 2 — Revenue & Sales
- Revenue grew from R$128k/month in Jan 2017 to over R$1M/month consistently from late 2017
- Health and Beauty leads all categories at R$1.41M — outperforming electronics significantly
- 37% of all revenue concentrated in São Paulo alone — geographic diversification is the growth opportunity
- Monday is the highest sales day, 32% above Saturday

### Phase 3 — RFM Customer Segmentation

| Segment | Customers | Revenue Share |
|---------|-----------|---------------|
| At Risk | 14.1% | 20.8% |
| Loyal | 15.2% | 19.1% |
| New | 16.1% | 15.9% |
| Champions | 7.0% | 13.1% |
| Hibernating | 15.3% | 13.0% |
| Promising | 7.9% | 7.4% |
| Need Attention | 14.0% | 4.6% |
| Lost | 4.1% | 4.0% |

**Critical insight:** Champions are only 7% of customers but drive 13.1% of revenue. Repeat buyers spend 92% more (R$308 vs R$161). Moving just 5% more customers to a second purchase adds millions without any acquisition spend.

### Phase 4 — Delivery Impact and Churn

| Delivery Timing | Avg Review Score |
|-----------------|-----------------|
| Very early (15d+) | 4.32 stars |
| Early (8-15d) | 4.31 stars |
| Slight early (2-7d) | 4.20 stars |
| On time (0-1d) | 4.12 stars |
| Late (1-7d) | 3.02 stars |
| Late (8-15d) | 1.71 stars |
| Very late (30d+) | 2.04 stars |

- **Pearson correlation:** r = −0.267, p < 0.0001
- **T-test:** t = 125.21 (statistically definitive)
- **Score drop from lateness:** −1.83 points
- **Revenue lost to bad-experience churn:** R$1.72M
- **The cliff:** Being 1-7 days late is recoverable (3.02 stars). Being 8-15 days late is not (1.71 stars). This is not a slope — it is a cliff.

### 5 Findings That Change How You See This Business

1. **Platform growing but concentrated** — 22% YoY growth but 37% of revenue is São Paulo alone
2. **Health and Beauty beats electronics** — R$1.41M vs R$1.03M. Repeat-purchase beauty products outperform one-off electronics buys
3. **97% of customers never come back** — repeat buyers spend 92% more; retention is the biggest untapped lever
4. **Late delivery collapses NPS instantly** — a cliff, not a slope. Office furniture has the worst 1-star rate at 17%
5. **Geography equals logistics equals satisfaction** — Alagoas: 22.9% late rate, 3.86 stars. São Paulo: 5.3% late, 4.25 stars

---

## Tools Used

- **Claude AI** — Agentic workflow, data analysis plugin, prompt engineering
- **Chart.js** — Interactive visualizations rendered in HTML
- **PowerPoint** — 13-slide executive presentation deck
- **Kaggle** — Source dataset

---

## Skills Demonstrated

- Multi-file data merging and exploratory data analysis (EDA)
- Revenue trend analysis and sales pattern identification
- RFM (Recency, Frequency, Monetary) customer segmentation
- Statistical hypothesis testing (Pearson correlation, T-test)
- Churn risk modelling and revenue impact quantification
- Dashboard design and interactive data visualization
- Stakeholder presentation and business storytelling
- Agentic AI workflow with Claude

---

## Repository Structure

```
Olist-ECommerce-Intelligence/
│
├── olist_phase1_exploration.html          # Phase 1 interactive dashboard
├── olist_summary_charts.html             # Phases 2-4 summary charts
├── Olist_ECommerce_Intelligence.pptx     # 13-slide stakeholder deck
└── README.md
```

---

## About

Built by **Puru Tiwari**
Data Analyst | Data Engineer & AI Enthusiast | Open to Work

Connect with me on [LinkedIn](https://www.linkedin.com/in/puru-tiwari-314aab135/)
Available for freelance work : fiverr.com/puru1304
Also see my FIFA World Cup Data Intelligence project: [GitHub](https://github.com/prabhat202601-cloud/FIFA-WorldCup-Data-Intelligence)

---
*Built with Claude AI · Olist Brazilian E-Commerce Dataset (Kaggle) · 2016–2018*
