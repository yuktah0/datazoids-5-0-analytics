# Amazon Pay India — Customer Analytics & Retention Strategy

**DataZoids 5.0 | Pan-India Analytics Case Study Challenge | 2026**

An end-to-end customer analytics case study focused on understanding churn, evaluating customer loyalty, identifying high-value segments, and optimizing cashback strategies for Amazon Pay India.

## Project Overview

This project analyses customer-level data from 5,000 Amazon Pay India users to address five business challenges:

1. **Customer Churn:** Identify factors associated with customer attrition.
2. **Prime Membership:** Evaluate its impact on transaction frequency and loyalty.
3. **Customer Lifetime Value:** Identify and segment high-value customers.
4. **Cashback Effectiveness:** Assess cashback utilization against engagement and retention.
5. **Personalized Retention:** Develop value-based customer targeting and cashback allocation strategies.

## Methodology

| Area | Techniques |
|---|---|
| Exploratory Analysis | Data cleaning, descriptive statistics, visualization |
| Statistical Testing | Welch's t-test, Chi-Square test |
| Churn Analysis | Random Forest, Logistic Regression, 5-fold cross-validation |
| Customer Segmentation | Value-tenure analysis, K-Means clustering |
| Cashback Analysis | Correlation analysis, behavioural segmentation |
| Business Strategy | Financial scenario modelling, retention recommendations |

## Key Findings

- **Churn:** Overall churn rate of 19%; available customer attributes showed limited predictive power.
- **Prime Membership:** No statistically significant difference in transaction frequency or churn between Prime and Non-Prime users.
- **Customer Value:** The top 25% of customers contributed 62.9% of estimated lifetime value.
- **Cashback:** Cashback utilization showed no significant relationship with customer engagement or churn.
- **Retention Strategy:** Proposed five value-based customer tiers with differentiated rewards and retention interventions.

## Business Recommendations

- Prioritize high-value customer retention through targeted rewards.
- Shift from blanket cashback to behaviour-based incentives.
- Strengthen Prime payment engagement through utility and auto-pay benefits.
- Reduce low-return promotional spending.
- Implement a 90-day pilot with a randomized 10% holdout group to measure incremental impact.

## Tech Stack

- **Language:** Python
- **Data Analysis:** Pandas, NumPy
- **Visualization:** Matplotlib, Seaborn
- **Machine Learning:** Scikit-learn
- **Statistical Analysis:** SciPy
- **Environment:** Jupyter Notebook

## Repository Structure

```text
amazon-pay-customer-analytics/
│
├── data/
├── notebooks/
├── problem-statement/
├── Tekton_DataZoids_5_0.pptx
└── README.md
```

- `data/` — Competition-provided customer dataset.
- `notebooks/` — Data analysis, statistical testing, modelling and insights.
- `problem-statement/` — Original competition case study.
- `Tekton_DataZoids.pptx` — Final case competition presentation.

## Analytical Considerations

- Lifetime value is estimated using cumulative transaction GMV and tenure; it is a proxy rather than actual customer profitability.
- Financial projections use explicitly stated modelling assumptions and require validation through controlled experiments.
- The available dataset does not establish external churn causes or demonstrate reliable churn prediction.

## Competition

**DataZoids 5.0 — IIM Kashipur**

[Competition Details](https://unstop.com/competitions/datazoids-50-a-pan-india-analytics-case-study-challenge-iim-kashipur-1774919)

**Team:** Tekton

**Repository:** github.com/yuktah0/datazoids-5-0-analytics
