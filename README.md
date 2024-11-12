# A/B Testing Analysis Project

This project analyzes the results of an A/B test aimed at determining the impact of design changes on the conversion rate from app installation to purchase.

## Project Overview

The goal of this A/B test is to evaluate the effectiveness of a new subscription offer design. Users are divided into two groups:

- **Group A**: Standard subscription offer at $4.99.
- **Group B**: Subscription offer labeled as a "50% discount" for the same price of $4.99.

We aim to determine whether the design change (Group B) results in a higher conversion rate.

## Key Metrics

- **Conversion Rate (CR)**: The percentage of users who convert from installation to purchase.
- **Test Duration**: 21 days.

## Analysis Steps

1. **Data Import and Exploration**:
   - Load the test data and inspect its structure.
   - Calculate key metrics (number of users, conversions, and conversion rates) for both groups.

2. **Statistical Testing**:
   - Perform a t-test to compare the conversion rates of Group A and Group B.
   - Determine if the difference is statistically significant at a 95% confidence level.

3. **Data Visualization**:
   - Plot bar charts with 95% confidence intervals to visualize the differences between groups.
   - Plot cumulative conversion rates over time to observe trends and stability.

## Results

- Group B demonstrated a statistically significant higher conversion rate than Group A.
- Visual analysis confirms that Group B consistently outperforms Group A, with non-overlapping 95% confidence intervals and higher cumulative conversion rates.

## Conclusion

With 95% confidence, the null hypothesis (no difference in conversion rates) is rejected. We recommend implementing the design changes used in Group B to improve overall conversion rates.
