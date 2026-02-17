# Customer Revenue Driver Analysis — NovaRetail+

## Project Overview

This project presents an exploratory correlation analysis focused on identifying behavioral factors associated with annual revenue generation in an ecommerce environment.

The analysis evaluates customer engagement, purchasing behavior, segmentation variables, and platform interaction metrics to understand which patterns show the strongest statistical association with business value.

The goal is to translate statistical findings into clear, responsible, and business-oriented insights.

---

## Business Objective

Identify customer behavior variables most strongly associated with annual revenue in order to support growth, retention, and strategic decision-making.

---

## Dataset Description

The dataset contains 15,000 customer records with behavioral, demographic, and engagement-related features.

Key variables include:

- Customer age
- Estimated income level
- Monthly visits
- Monthly purchase frequency
- Targeted advertising spend
- Satisfaction score
- Premium membership status
- Churn indicator
- Device type
- Geographic region
- Annual revenue (target variable)

---

## Analytical Approach

The analysis follows a structured exploratory workflow:

1. Data loading and validation
2. Data preparation and assumption documentation
3. Exploratory visualization
4. Correlation analysis using appropriate statistical methods:
   - Pearson correlation (linear relationships)
   - Spearman correlation (monotonic relationships)
   - Point-biserial correlation (binary vs numerical)
   - Cramér's V (categorical associations)
5. Interpretation of findings from a business perspective
6. Discussion of limitations and next steps

---

## Key Insights

- Monthly purchase frequency shows a strong statistical association with annual revenue.
- Customer engagement (visits) presents a moderate relationship with revenue.
- Premium membership has a weak positive association with revenue generation.
- Demographic and categorical variables show limited direct association.

---

## Limitations

- Correlation does not imply causation.
- Potential confounding variables may not be included.
- Aggregated behavioral metrics may mask temporal effects.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Seaborn
- Matplotlib
- Jupyter Notebook
