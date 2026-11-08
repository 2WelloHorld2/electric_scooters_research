# 🛴 Scooter Rental Analytics

**Product analytics · Statistical hypothesis testing · Python**

## Overview
This project examines rider behavior and subscription economics for a scooter-sharing service. The goal is to understand how subscription status affects usage and revenue, and to evaluate potential marketing decisions.

**[View the Jupyter notebook](project/electric_scooters_research.ipynb)**

## Key questions
- How do ride duration and distance differ between subscribers and non-subscribers?
- Which group generates more monthly revenue?
- What do statistical tests imply about product and marketing hypotheses?
- How might subscriptions and promotions be improved?

## Approach
1. Clean and validate trip and customer data.
2. Explore rider behavior using descriptive statistics and visualizations.
3. Calculate subscription-related revenue metrics.
4. Test group differences using statistical methods, including t-tests.
5. Evaluate marketing scenarios and translate the findings into recommendations.

## Tools
`Python` · `pandas` · `NumPy` · `SciPy` · `Matplotlib` · `Seaborn`

## Findings
In the original analysis, average ride duration did not show a meaningful difference between the subscription groups. Non-subscribers were reported to generate more monthly revenue on average, partly because of unlock fees. The notebook also explores promotion and notification scenarios.

**Interpretation note:** These observations describe the exercise dataset and assumptions, not a causal estimate of the effect of subscription or a validated recommendation to change subscription prices.

## Run
Open the notebook in Jupyter after installing the dependencies:

```bash
pip install jupyter pandas numpy scipy matplotlib seaborn
```

Some input datasets used in the exercise may need to be provided separately.

## Project provenance
Adapted README and notebook copied from [the original project](https://github.com/HendlessWizzard/electric_scooters_research).