# Marketing A/B Testing and Conversion Analysis

## Project Overview

This project analyzes the performance of marketing campaigns using A/B testing, statistical hypothesis testing, funnel analysis, and data visualization.

The goal was to determine whether a test marketing campaign improved user engagement, conversion efficiency, and purchase outcomes compared with a control campaign.

The analysis focuses on identifying the relationship between engagement metrics and downstream business value.

---

# Tools and Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* SciPy

---

# Analysis Performed

* Data cleaning and preprocessing
* KPI analysis
* Funnel analysis
* Trend analysis
* Statistical hypothesis testing
* Confidence interval analysis
* Correlation analysis
* Data visualization

---

# KPI Comparison

The test campaign achieved significantly higher click-through rates, indicating stronger top-funnel engagement.

However, the control campaign maintained stronger conversion efficiency and lower acquisition costs.

## CTR Comparison

![CTR Comparison](ctr_chart.png)

## Conversion Rate Comparison

![Conversion Rate](ConversionRate.png)

## Cost per Purchase Comparison

![Cost per Purchase](CostperPurchase.png)

---

# Funnel Analysis

The funnel analysis showed that the test campaign generated more clicks and engagement, but failed to improve downstream conversion performance.

This suggests that the test campaign attracted lower-intent traffic.

![Funnel Comparison](FunnelComparison.png)

---

# Purchase Distribution Analysis

Boxplot analysis showed substantial overlap between the purchase distributions of both campaigns.

This visually supports the statistical testing results indicating no significant difference in purchase outcomes.

![Purchase Distribution](PurchaseDistribution.png)

---

# Trend Analysis

## Purchase Trend

The purchase trends fluctuated heavily over time, with no consistent long-term winner between the two campaigns.

![Purchase Trend](PurchaseTrend.png)

## CTR Trend

The test campaign consistently generated higher CTR values, indicating stronger ad attractiveness and engagement performance.

![CTR Trend](CTRTrend.png)

## Conversion Rate Trend

Although the test campaign generated stronger engagement, the control campaign maintained higher conversion efficiency over time.

![Conversion Rate Trend](ConversionRateTrend.png)

---

# Correlation Analysis

Correlation analysis revealed that engagement metrics such as clicks and impressions had weak relationships with final purchase outcomes.

The strongest behavioral relationship was observed between Add-to-Cart activity and purchases.

This suggests that downstream funnel behavior is more predictive of conversion success than top-funnel engagement metrics.

![Correlation Heatmap](CorrelationHeatmapTrend.png)

---

# Statistical Testing

An independent two-sample t-test was conducted to evaluate whether the test campaign significantly improved purchases.

## Hypothesis

* Null Hypothesis (H0): No significant difference exists between the campaigns.
* Alternative Hypothesis (H1): A significant difference exists between the campaigns.

## Results

* p-value = 0.9761
* 95% Confidence Interval = (-104.94, 101.82)

The results indicated that the purchase difference between the campaigns was not statistically significant.

---

# Key Business Insights

* Higher CTR does not necessarily lead to stronger business outcomes.
* The test campaign improved engagement but attracted lower-quality traffic.
* The control campaign demonstrated stronger conversion efficiency and marketing ROI.
* Add-to-cart behavior was more predictive of purchases than clicks.
* Statistical testing confirmed that the purchase difference was not significant.

---

# Final Recommendation

Although the test campaign successfully improved user engagement and click-through performance, it failed to generate statistically significant improvements in purchases.

The control campaign maintained stronger conversion efficiency and lower acquisition costs, suggesting better overall marketing effectiveness and ROI.

---

# Repository Structure

```text
marketing-ab-testing-analysis/
│
├── data/
│   ├── control_group.csv
│   └── test_group.csv
│
├── notebook/
│   └── marketing_ab_testing.ipynb
│
├── README.md
│
└── requirements.txt
```
