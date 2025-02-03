# Fast Food Marketing A/B Test Analysis

## Overview

This repository contains the analysis of the Fast Food Marketing Campaign A/B test, which evaluates different promotions to determine which yields the highest sales for a new item the company is trying to add to their menu. Different versions of the campaign are used at different stores.

## Dataset

Key columns in the dataset:
- `Week`: Number of Week, in the month promotions were run.

- `Promotion` - Identifies Different campaigns 

- `SalesinThousands`: Sales from Promotion

- `MarketSize`: Size of the Market by sales where promotion is carried out 

- `LocationID`: Unique identifier for store location

- `AgeOfStore`: Age of stores in years

## Methodology

1. Exploratory Data Analysis (EDA)
    - Checked for missing values and outliers.

    - Analyzed sales trends by week and promotion type.

2. Sample Ratio Mismatch (SRM) Test
    - Conducted a chi-square test to check for inconsistencies in group assignment.

3. Statistical Analysis
    - Used t-tests to compare sales between different promotions.

4. Confidence Interval Computation

    -  confidence intervals analytically and via bootstrapping.


## Decision & Recommendations

Determined the best-performing promotion based on statistical significance.

