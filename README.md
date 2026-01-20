# Family-Planning-State-Prioritization-Analysis-Multi-Criteria-Decision-Analysis-MCDA-Results-Report-
![](https://github.com/Imisau/Family-Planning-State-Prioritization-Analysis-Multi-Criteria-Decision-Analysis-MCDA-Results-Report-/blob/main/FP_1.png)

# Background & Purpose
‎‎This analysis applies a Multi-Criteria Decision Analysis (MCDA) framework to prioritise states for Family Planning (FP) scale-up using three strategic domains:
‎‎- Need (NDHS-aligned) – where FP gaps are most severe
- ‎‎Health System Readiness (NHMIS/LMIS-aligned) – capacity to absorb investments
- ‎‎Political Will & Governance – likelihood of sustained implementation
‎‎The objective is to support donor and program decision-making by identifying states where FP investments will yield the highest equity, feasibility, and impact returns.
‎
# Methology Summary
‎Domains and Scoring Logic; Domain What It Measures Interpretation
- ‎Need Score Demand pressure for FP services Higher = greater unmet need
- ‎Readiness Score Health system capacity Higher = stronger systems
- ‎Political Score Policy & financing commitment Higher = stronger enabling environment
- ‎Total Score Weighted composite of all domains Higher = higher priority
- ‎State Rank Final prioritization order Rank 1 = highest priority
‎‎All indicators were normalized (0–1) to ensure comparability, and composite scores were generated to produce a transparent and defensible ranking.

# Process
The dataset was downloaded onto local storage and then connected a MySQL workbench for analysis. This include using GROUP BY clause or CASE WHEN statement to calculate aggregate attrition rates base on employee factors other factor like role, department, income, and years with the company. All insight translated to a user friendly visual made in Power BI. Other Functions are used to transform data using DAX and Power Query in Power BI. Data validations, evaluations, predictions and statistical operations are performed using Excel and Jupyter Notebook, using Pandas and Numpy 
‎
## Key Findings
‎Overall Prioritization Pattern
‎The results show substantial variation across states, revealing four clear typologies:
- ‎High Need + High Readiness + Strong Political Will
- High Need but Weak Readiness
- ‎Moderate Need with Strong Systems
- ‎Low Political Commitment despite Need
‎This differentiation is critical for tailored FP investment strategies rather than one-size-fits-all approaches.
‎
# Domain-Specific Insights (Need Domain Findings)

![](https://github.com/Imisau/Family-Planning-State-Prioritization-Analysis-Multi-Criteria-Decision-Analysis-MCDA-Results-Report-/blob/main/FP_2.png)

## ‎Key Observation:
‎States with the **highest Need Scores (≥0.75)** consistently rank among top FP priorities, regardless of readiness variability.
‎What this means:
- ‎High unmet need, low mCPR, and large WRA populations are driving urgency.
- These states represent equity-critical geographies, often with underserved adolescents and rural women.
‎Implication for donors:
‎FP scale-up in these states directly addresses **inequality, unmet demand, and preventable maternal risk.**
‎
# Readiness Domain Findings

![](https://github.com/Imisau/Family-Planning-State-Prioritization-Analysis-Multi-Criteria-Decision-Analysis-MCDA-Results-Report-/blob/main/FP_3.png)
## ‎Key Observation:
‎Readiness Scores show wide dispersion, ranging from 8**near-zero** values to very strong system performance **(>0.80).**

**‎Patterns observed:**
‎Some high-need states suffer from weak facility density, reporting gaps, and commodity stockouts.
‎Others demonstrate strong absorptive capacity, indicating readiness for rapid scale-up.

**‎Implication for programming:**
- ‎High-need but low-readiness states require system strengthening investments (HRH, commodities, data quality).
‎- High-readiness states can immediately absorb FP expansion funding.
‎
# Political Will Domain Findings

![](https://github.com/Imisau/Family-Planning-State-Prioritization-Analysis-Multi-Criteria-Decision-Analysis-MCDA-Results-Report-/blob/main/FP_4.png)

## ‎Key Observation:
‎Political Scores are often decoupled from Need. 

**‎Critical insight:**
‎Several states show **very strong political commitment (scores ≥0.90)** even when readiness is moderate.
‎Conversely, some technically ready states exhibit **weak budget release or coordination,** limiting sustainability.

**‎Implication for donors:**
- ‎Political will is a key risk-mitigation factor.
‎- States with strong political scores are more likely to sustain FP gains beyond donor funding cycles.

## Composite Results (Total Score & Rank)

## High-Priority States (Top Tier)
‎States with Total Scores **≥0.75 and Rank ≤5** represent the strongest candidates for FP scale-up.

**‎Why they matter:**
‎Combine high need, sufficient readiness, and enabling political environments.
‎Offer high return on investment with lower implementation risk.

**‎Recommended action:**
‎ Immediate FP scale-up, demand generation, and service expansion.
‎
## Medium-Priority States
‎States with Total Scores **between 0.60–0.74** form the strategic middle tier.

**‎Key characteristics:**
- ‎Often strong in one or two domains, but constrained in another.
‎- Typically suitable for phased or targeted interventions.

**Recommended action:** 
‎Focused investments addressing specific bottlenecks (e.g., commodities, reporting, coordination).

## Lower-Priority States
‎States with **Total Scores <0.55** rank lower due to:
- ‎Weak readiness,
- ‎Limited political commitment, ‎Or both.

**‎Important nuance:**
‎Low rank does not imply low need, but rather higher implementation risk.

**‎Recommended action:**
Advocacy, policy dialogue, and foundational system strengthening before scale-up.
Strategic Implications for FP Programming
Investment Sequencing
‎
## State Profile Recommended Strategy
- ‎High Need + High Readiness Immediate FP expansion
‎- High Need + Low Readiness Systems strengthening first
- ‎Strong Political Will Leverage co-financing
‎- Low Political Will Advocacy & policy engagement

## Donor Value Proposition
‎This MCDA framework enables donors to:
- ‎Defend why specific states were selected
- ‎Balance equity with feasibility
- ‎Reduce implementation risk
- ‎Align funding with national data systems (NDHS/NHMIS)

![](https://github.com/Imisau/Family-Planning-State-Prioritization-Analysis-Multi-Criteria-Decision-Analysis-MCDA-Results-Report-/blob/main/FP_5.png)
‎
# Key Conclusion
‎‎This analysis demonstrates that effective FP prioritization must go beyond need alone.
‎By integrating **need, readiness, and political feasibility,** the MCDA approach provides a transparent, data-driven, and donor-defensible basis for strategic FP investments.
# ‎Final takeaway:
‎States that combine high unmet need with system readiness and political commitment offer the strongest opportunity for sustainable, equity-focused FP scale-up.

### Author
#### Emmanuel Kyauta
Monitoring, Evaluation, Research & Learning (MERL) | Strategic Health Data Analyst Power BI • DAX • SQL • Python • Donor Decision Analytics

### Interact_with_dataset [Here](https://github.com/Imisau/Family-Planning-State-Prioritization-Analysis-Multi-Criteria-Decision-Analysis-MCDA-Results-Report-/commit/caca9371fbe7678f66eda16290319c26e9934f5e)
