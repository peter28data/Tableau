<h1 align="center">Peter Garay-Robles </h1>

<h3 align="center">A Senior Analyst in SQL and Python.</h3>

---

The files in this folder contain images for Tableau Dashboard visualization in the healthcare industry. 

---

## 📊 Healthcare Company Revenue & Capital Overview

![Global Healthcare Market Cap](https://github.com/peter28data/github/blob/d3a36805bdf274c662389e3d96e1e25c06388bbc/images/healthcare/Healthcare%20Market%20Cap.png)

---


### Executive Summary - Junior Analyst Overview

This dashboard compares revenue and market capitalization across major healthcare companies to understand how different business segments and geographies contribute to overall value. It allows leadership to identify which companies and segments generate the highest reveneue and market cap. This dashboard provides insights for our stakeholders on geographic distribution and the differences in performance across business segments. 

What Makes This Junior Analysis:

- Focused on what is shown
- Limited business implication
- Descriptive

### Business Problem

Healthcare organizations routinely lose revenue due to:
1. Slow denial resolution
2. Preventable claim denials
3. Poor visibility into denial drivers by payer, category, and age

Without a structured denial analytics framework:

- Aging claims become unrecoverable
- High-doller denials remain unresolved
- Staff efforts are misallocated

---

![2020 market cap & revenue](https://github.com/peter28data/Tableau/blob/304786eb388a06fbb5d172a8d20eea930160dbc9/images/healthcare/2020%20Market%20Cap%20%26%20Revenue.png)

---

First, we identify:

The Top 20 Healthcare companies by market capitlization in 2020 reflect how the public market values its future potential at share price by distributed shares. The revenue shows how the healthcare company performed for the year 2020. 

This lets decision-makers switch between those perspectives and identify gaps between current performance and expected growth to identify companies that are undervalued and overvalued.

Eli Lilly:

In 2020, the top 3 healthcare companies by market cap align with the top 3 companies by revenue. 

However, Eli Lilly, the fourth highest market cap, had less than a 5% difference in market cap but its earnings of 24.5B are 42% lower than 41.9B from the third leading competitor.

To compare Eli Lilly to the industry average for the top 20 companies by revenue is 35.5B. 

---

Insight:

Eli Lilly is the fourth highest healthcare company by market but is earning less than the average revenue of the top 20 healthcare companies, signaling underperformance relative to the benchmark.

---

![2020 revenue cat & sub-cats](https://github.com/peter28data/Tableau/blob/304786eb388a06fbb5d172a8d20eea930160dbc9/images/healthcare/2020%20Revenue%20Category%20%26%20Sub-Cats.png)

---

This breakdown of where the revenue is coming fromr

---

### Estimated Financial Impact
For a healthcare organization with $10M annual revenue:

- Reducing denials by just 1.5% of revenue -> $150k recovered
- Improving denial resolution speed by 10-15 days can increase cash flow by $250k-$400k annually

Impact Connection:

The dashboard directly ties denial analytics to cash flow recovery prioritization, and operational efficiency, making it a powerful tool for revenue cycle leadership. 

---


![2020 market cap cats & sub-cats](https://github.com/peter28data/Tableau/blob/304786eb388a06fbb5d172a8d20eea930160dbc9/images/healthcare/2020%20Market%20Cap%20Cats.png)

---

### Methodology
1. Data Extraction & Cleansing (SQL)

- Pulled claims, denial reasons, financial class, aging, and payment data from transactional databases
- Standardized denial codes and rollups

2. Dashboard Development (Tableau)

- Built KPI tiles for: Total denied amount, Distinct Claims, Average Denial Age
- Designed interactive visuals: Treemap of denial reasons by financial impact, Scatterplot by denial age, Trend analysis of denied amounts over time with drop-downs to filter claim-level detail

---


### Results & Business Recommendations - Junior Analyst Perspective

Results:

Oncology and immunology segments contribute significantly to total market cap. Certain financial classes exhibit systematic denial patterns, indicating process or documentation gaps. A small number of denial categories (e.g., duplicate claims, eligibility, billing errors)

Business Recommendations:

Prioritze resolution of top 3 denial categories, which drive the majority of revenue leakage. Focus staff efforts on high-dollar, high-aging claims for maximum recovery. Implement front-end process controls (eligibility and billing validation) to prevent repeat denials. Monitor underperforming segments for improvement opportunities. 

Financial Impact (Estimated):

Improving performance in underperforming segments could increase revenue by 3%-5% for a company with $10M in revenue

---

## 📊 Healthcare Company Revenue & Capital Overview

![Global Healthcare Market Cap](https://github.com/peter28data/github/blob/d3a36805bdf274c662389e3d96e1e25c06388bbc/images/healthcare/Healthcare%20Market%20Cap.png)

---

### Executive Summary - Senior Analyst Overview

This dashboard evaluates how effectively healthcare organizations convert capital into revenue across therapeutic areas, business segments, and geographies. The focus is on capital efficiency, concentration risk, and scalable growth opportunities. The insights are designed to inform portfolio strategy, capital allocation, and market expansion decisions, assisting leadership to shift investment toward segments and geographies with the strongest revenue yield. 

What Makes This Senior Analysis:

- Focused on decision-making
- Connects analytics to strategy
- Outcome-driven

### Senior Analyst Perspective

Capital concentration is not evenly distributed. Specific therapeutic areas generate disporportionate market value relative to revenue, signaling higher growth expectations and pricing power. Geographic clustering suggests operational and R&D efficiences that can be replicated in adjacent markets. Underperforming segments represent opportunities for capital rebalancing rather than cost reduction alone.

Recommendations:

1. Reallocate 2%-3% of annual investment from low-yield segments into high-efficiency therapeutic areas.
2. Expand presence in cities demonstrating both capital density and revenue scalalbility.
3. Establish ongoing capital-efficiency KPIs to guide quarterly investment decisions.

Financial Impact (Estimated)

- A 3% improvement in capital efficiency -> $300k incremental revenue on $10M
- Replicating top-performing segment economics across regions -> $500k-$700k annual uplift

What Makes This Senior Analysis:

- Specific Actions
- Quantified Trade-Offs

---

![2020 immunology market cap](https://github.com/peter28data/Tableau/blob/44609f7b4614ebc3e0b65b23cfa557ced6c75712/images/healthcare/immunology.png)

---

![2020 oncology market cap](https://github.com/peter28data/Tableau/blob/44609f7b4614ebc3e0b65b23cfa557ced6c75712/images/healthcare/oncology.png)

---

### 📊 Revenue Cycle Analyst Dashboard

![weekly claims](https://github.com/peter28data/github/blob/d3a36805bdf274c662389e3d96e1e25c06388bbc/images/healthcare/Denials%20Management.png)

---

### Executive Summary - Junior Analyst

This dashboard tracks denied claims, denial amounts, and average aging of claims to help identify trends and common denial reasons. Users can see which denial categories account for the largest amounts and review claim-level details to support follow-up actions.

The Tableau dashboard helps revenue cycle teams monitor weekly denial performance.

### Results & Business Recommendations

Results:

Duplicate claims and eligibity issues account for the highest denied amounts. Older claims tend to have higher denied values. Some financial classes experience more denials than others.

Recommendations:

Focus on resolving high-dollar denials first. Review processes for common denial reasons. Monitor aging trends to prevent revenue loss.

Financial Impact (Estimated):

Reducing denials could recover 1%-2% of revenue ($100k-$200k for a $10M organization).

---

### 📊 Revenue Cycle Analyst Dashboard

![weekly claims](https://github.com/peter28data/github/blob/d3a36805bdf274c662389e3d96e1e25c06388bbc/images/healthcare/Denials%20Management.png)

---

Executive Summary - Senior Analyst

This dashboard functions as a revenue leakage control system, quantifying where, why, and how quickly revenue is lost through denials. It prioritizes denial categories and claims based on recoverability, financial impact, and aging risk, enabling stakeholders to target changes to the operational process.

The focus is on cash acceleration and denial prevention. 

### Results & Business Recommendations

Results:

Over 50% of denied dollars orginate from a small subset of preventable denial categories, indicating systemic front-end process gaps. High-dollar denials exceeding critical aging thresholds represent immediate write-off risk, not just delayed cash. Financial class-specific patterns suggest payer-driven documentation and authorization failures.

Recommendations:

1. Target the top 3 denial categories with the highest recovery ROI rather than addressing all denials equally.
2. Implement pre-billl edits and eligibility automation to eliminate repeat denials upstream.
3. Align staffing models to pri

Financial Impact (Estimated):

Preventing just 1% of avoidable denials leads to $100k revenue preserved. Improving recovery speedd by 10-15 days improves cash flow by $250k-$400k. This is a combined impact of $400k-$600k annual benefit on a $10M revenue

What Makes This a Senior Analysis:

- Focus on preventable vs non-preventable
- Labor efficiency and ROI framing
- Cash flow, not just recovery

As a senior analyst, framing analysis around decisions, trade-offs, and financial impact offer a more well rounded report on curret trends.

---

## Done! Thank you for Reading
For Project in SQL, click below:

🔗 SQL Portfolio Link: https://github.com/peter28data/SQL

🔗 Python Portfolio Link: https://github.com/peter28data/Python

🔗 Current Portfolio Link: https://github.com/peter28data/github



---
