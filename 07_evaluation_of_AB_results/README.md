# Testing hypotheses to increase revenue in an online store - evaluate A/B test results

## Task:
Using the data of the online store, prioritize hypotheses, evaluate the results of A / B testing using various methods

## Description:
Hypotheses were prioritized by ICE and RICE frameworks. Then I analyzed the results of the A / B test, built graphs of cumulative revenue, average check, conversion by group, and then calculated the statistical significance of differences in conversions and average checks for raw and cleaned data. Based on the analysis, I decided that it was not advisable to continue the test.

## Results:
 - There is a statistically significant difference in the conversion rate between the groups for both "raw" and data after filtering anomalies;
 - There is no statistically significant difference in the average check between the groups, either by "raw" or by data after filtering anomalies;
 - The graph of the difference in conversion between groups reports that almost from the very beginning of the test, group B is better than group A.
 - The graph of the difference in the average check fluctuates: that is how anomalies were found. It is impossible to draw certain conclusions from this graph.

There is no point in continuing the test: group B is statistically significantly better than group A in only one of the metrics after the anomalies were removed, the situation has not changed

## Company profile:
e-stores

## Stack:
Python, Pandas, Matplotlib, A/B testing, SciPy

## tags:
data analisys, Python, Pandas, marketing analyst, web-analyst, product-analyst
