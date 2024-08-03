# AB Testing for Click-Through Rate (CTR) Analysis

This project performs an A/B test to determine whether a new experimental setup increases the click-through rate (CTR) compared to the control group. The main steps include data simulation, exploratory data analysis, statistical testing, and result interpretation.

## Steps

1. **Data Simulation**:
   - Simulated data for two groups: experimental (N=10,000) and control (N=10,000).
   - Each group had a certain click probability: 0.4 for the experimental group and 0.2 for the control group.
   - Created dataframes for both groups and combined them into a single dataframe.

2. **Exploratory Data Analysis**:
   - Visualized the distribution of clicks in both groups using count plots.
   - Annotated the plots with click percentages for better understanding.

3. **Statistical Testing**:
   - Calculated the click probabilities for both groups.
   - Computed the pooled click probability and pooled variance.
   - Calculated the standard error and test statistic for the 2-sample z-test.
   - Determined the z-critical value and p-value to evaluate the statistical significance of the results.

4. **Result Interpretation**:
   - Determined whether there is a statistically significant difference in CTR between the two groups.
   - Plotted the standard normal distribution with the rejection region and test statistic.
   - Calculated the 95% confidence interval for the difference in click probabilities.
   - Assessed practical significance based on a predefined delta value.

## Key Findings

- The experimental group had a higher click probability (0.4) compared to the control group (0.2).
- The test statistic indicated a statistically significant difference in CTR between the two groups.
- The confidence interval and practical significance assessment confirmed the effectiveness of the experimental setup.

This project provides a detailed approach to performing an A/B test for CTR analysis, ensuring the results are statistically and practically significant.
