# Exploratory Data Analysis & Statistical Insights

Exploratory analysis of a cleaned retail transactions dataset (12,575 transactions, 2022 to January 2025), with three hypothesis tests and a summary of the top five findings.

## Files

- eda_statistical_insights.ipynb: the full analysis, with charts and written findings
- clean_dataset.csv: the cleaned dataset used by the notebook

## What the notebook covers

1. Summary statistics: mean, median, standard deviation and quartiles
2. Histograms, box plots and outlier detection (IQR rule)
3. Correlation heatmap and multivariate views (category, payment method, location, month, weekday)
4. Three hypothesis tests: discount vs spend (t-test, Mann-Whitney), discount frequency vs purchase frequency (Spearman), payment method vs channel (chi-square)
5. Top five findings in markdown

## Headline results

- Revenue is spread almost evenly across 8 categories (11.6% to 13.2% each).
- Revenue changes through the year: January is the strongest month on average and October the weakest (a 25% difference).
- None of the three hypotheses was statistically significant, so there is no evidence that discounts change spend or customer retention, or that payment choice depends on channel.

## How to run

Open the notebook in Google Colab, upload clean_dataset.csv, and run all cells.
