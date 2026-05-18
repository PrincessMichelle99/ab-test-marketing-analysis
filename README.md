# A/B Test: Ad Campaign Conversion Rate Analysis

## Overview
This project analyzes the results of an A/B test comparing the effectiveness 
of an ad campaign (test group) vs a public service announcement (control group) 
on user conversion rates.

## Dataset
- Source: [Marketing A/B Testing Dataset](https://www.kaggle.com/datasets/faviovaz/marketing-ab-testing)
- 588,101 users | 2 groups: `ad` vs `psa`
- Key fields: `test group`, `converted`, `total ads`, `most ads day`, `most ads hour`

## Analysis Structure
1. Data Cleaning & Overview
2. Core Metrics Calculation
3. Conversion Rate Visualization
4. Hypothesis Testing (Chi-Square Test)
5. Conversion Rate by Day of Week
6. Conversion Rate by Hour of Day
7. Ad Exposure Bucket Analysis
8. Final Summary & Business Recommendations

## Key Findings
| Metric | PSA (Control) | Ad (Test) |
|--------|--------------|-----------|
| Users | 23,524 | 564,577 |
| Conversion Rate | 1.79% | 2.55% |
| Absolute Lift | — | +0.77pp |
| Relative Lift | — | +43.1% |

- Chi-Square p-value < 0.0001 → statistically significant
- Ad group consistently outperforms PSA across all days of the week
- Peak conversion hours: 14:00–20:00
- Higher ad frequency (21–50 exposures) correlates with higher conversion

## Tools
Python · pandas · scipy · seaborn · matplotlib

## Author
Michelle Qian · [LinkedIn](https://linkedin.com/in/michelle-qian-882abc) · [Kaggle](https://www.kaggle.com)
