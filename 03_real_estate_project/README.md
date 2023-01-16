# Yandex.Realty Project

## Task:
We need to check the data for errors and evaluate their impact on the study. Then, at the preprocessing stage, look for an opportunity to correct the most critical data errors. Then conduct an exploratory analysis and draw a conclusion.

## Description:
Yandex.Realty is a service that helps you rent, buy and find property such as apartments and new constructions in the cities of Moscow, Saint Petersburg etc.
Based on the Yandex.Realty service data, the market value was determined real estate objects of different types, typical parameters of apartments, depending on
distance from the center. Data preprocessing has been carried out. Added new data. Histograms, boxplots, scatterplots were constructed.

## Results:

There were anomalies in the table, such as missing values, explicit and implicit duplicates, typos, fractional numbers. All this had to be corrected and prepared for further work. Objects which term of exposure was 30, 45 or 90 days were deleted, since this is the period of free placement. This information does not give an idea of when the object was sold and at what price. Most likely it was removed before the actual sale.

The average period of placement of ads is 100 days. At the cost of a square meter, as expected the megapolis is leading, 103k rubles per square meter. Next to him is the city of Pushkin, 97k Rub. Almost 2 times cheaper will cost a square meter in Vyborg - 57k rubles.

## Company profile:
Internet services, advertisements website

## Stack:
Python, Pandas, matplotlib, exploratory data analysis, data visualization, data preprocessing

## tags:
data analisys, Python, Pandas
