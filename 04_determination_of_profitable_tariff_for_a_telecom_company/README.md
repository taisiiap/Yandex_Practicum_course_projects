# Telecom Project

## Task:
Determination of a profitable tariff for a telecom company

## Description:
A preliminary analysis of the use of 2 tariffs on a sample of customers was carried out, analyzed the behavior of customers when using the services of the operator and recommended optimal sets of services for users. Pre-processing done data, their analysis. The hypotheses about the difference in the revenue of subscribers of different tariffs and difference in revenue of subscribers from Moscow and other regions.

## Results:
After analysis of the users behaviour I came to the conclusion that:

- Ultra tariff brings 60% more profit per month than Smart tariff
- However, users of Ultra tariff never exceed the threshold for the minutes and messages used, but regularly spend more GB than is included in the monthly tariff.
- Smart tariff users usualy do not fit into the monthly threshhold and pay extra for each service - calls, SMS and GB
- Users from Moscow do not bring more profit than users from other cities. However, every user from Moscow pays at least 550 rubles a month.

Ultra tariff brings the company more money in terms of invested resources, i.e. they provided less services, but received more. However, the Smart tariff is more popular, more users use it, the total revenue of the tariff is higher. Ultra may appeal to businessmen because of the expensive, but wide package of calls and SMS.

My recomendation is to:

- Reduce the threshold for minutes and SMS for Ultra, and increase for Smart
- increase the GB threshold for Ultra and Smart
- Two users terminated the contract in less than a month, we need to check and get feedback.
- There are several peaks in the `calls_df` dataset at 5, 10, 15 and 20 minutes, you need to clarify what these spikes are related to
- Promote Ultra in VIP and business segment
- Promote the Smart tariff among ordinary users

## Company profile:
Telecom

## Stack:
Python, Pandas, Matplotlib, NumPy, SciPy, descriptive statistics, testing of statistical hypotheses

## tags:
data analisys, Python, Pandas, histogram, boxplot
