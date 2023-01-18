# Churn Prediction for Fitness Center

## Task:

Based on data on visitors to a network of fitness centers, predict the probability of an outflow for each client in the next month, and use clustering to form user portraits

## Description:
This project uses machine learning. The probability of outflow (at the level of the next month) for each client was predicted; typical portraits of users have been formed: the brightest groups have been identified, their main properties have been characterized; analyzed the main features that most strongly affect the outflow.

## Results:
The analysis showed that the data contains approximately equal numbers of clients of both sexes, most (85%) of clients live near fitness centers, about half of all clients are employees of a partner company, 30% of clients came by acquaintance or through a promotion, 40% clients go to group classes. The average age of a client is 29 years, the maximum is 41. The average lifetime of a client is 3.7 months, the median is exactly three. The average attendance is 1.9 lessons per week. The maximum number of training sessions is 6. The average cost of additional services is 147 rubles, which is slightly more than the median. This indicates that there are few but very large expenses.

The outflow of customers in the current month is 26%.

Graphs of the distribution of signs showed that those who stayed are older on average and spend more on additional services of the club and regularly attend 2 training sessions per week. The lifetime of those who remain is 4.7 months. On average, those who stay are at the beginning of their subscription - 5.3 months before the end of the subscription discipline. On average, customers leave after 1 month of visiting. It is similar to those who started a new life on Monday and abandoned it without bringing it to any result. Those who left, on average, have less than two months before the end of the subscription period. The graph also shows that those who left rarely take long subscriptions. On the contrary, they rarely leave when there are many months left in the subscription.

Then, using the k-means model, all customers were devided into 5 clusters and identified the top features that affect churn the most.

Outflow affected by:

 - from the proximity of life to fitness centers
 - the presence of a subscription from the company
 - the opportunity to come for a promotion or recommendation
 - participation in group training
 
Outflow is not affected by:

 - floor
 - the presence of a phone number in the questionnaire
 
Recommendations for a customer engagement and retention strategy.

 - It is worth paying special attention to clients whose contract term is suitable (about 3 months before the end). Such clients should make a newsletter and offer to continue the subscription for a longer period on more favorable terms. 
 - Customers who live nearby have a good retention rate, so it is worth attracting customers with targeted advertising
 - It is worth further developing the corporate direction, after a month, 6 and 12 months, you can repeat the request and be reminded of profitable subscriptions from the company.
## Company profile:
start-up, offline

## Stack:
Python, Pandas, Seaborn, data visualisation, Matplotlib, ML, clasters, classification, KMeans, RandomForestClassifier, LogisticRegression, Scikit-learn

## tags:
data analisys, Python, Pandas, marketing analyst
