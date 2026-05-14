# Laptop Brand Preferences: Business vs Engineering Students

Python data-analysis project for ENGR 371: Intro to Probability and Statistics
for Engineers (Concordia University, Fall 2025).
Observational study comparing laptop brand usage between Business (JMSB) and
Engineering (Hall Building) students.

## Data

12 observation sessions, 87 laptops total, collected October 2025 across two
campus buildings.

## Methods

- Descriptive statistics (mean, median, variance, standard deviation)
- Two-sample t-test on session-level Mac-usage percentages
- Chi-square test of independence on laptop-level counts
- Effect sizes: Cohen's d and Cramer's V
- 95% confidence intervals
- Visualizations: histograms, box plots, grouped/stacked bar charts, pie charts

## Stack

Python, pandas, numpy, scipy.stats, matplotlib

## Files

- `laptop_study_analysis.ipynb` - full analysis notebook
- `laptop_study_data1.csv` - raw observational data

## Result

JMSB showed higher Mac usage than Hall Building: 60.0% vs. 33.3%, a difference
of 26.7 percentage points. The chi-square test found a statistically significant
association between academic program and laptop brand preference (chi-square =
5.1758, p = 0.022904, Cramer's V = 0.2439).
