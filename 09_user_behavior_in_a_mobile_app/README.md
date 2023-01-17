# Analysis of user behavior in a mobile app

## Task:
Analyze the sales funnel and evaluate the results of A/A/B testing based on data from the use of a mobile application for selling food products

## Description:
In this project, I studied the principles of event analytics. I built a sales funnel, explored the path of users to purchase. Analyzed the results of an A/B test for introducing new fonts. Compared 2 control groups with each other, made sure that the traffic was properly divided, and then compared with the test group. It was revealed that the new font will not significantly affect user behavior.

## Results:
To prepare the data, 1% of duplicates was removed. 1% of users had abnormal activity, but it was decided to leave them, as deleting 1% of users entails deleting 14% of all data, which can distort the final result.

The data in the dataset is presented from 25.07.2019 to 07.08.2019, however, until 01.08.2019, the data was incomplete and the surge in activity will begin only in the last week. First week from the analysis was removed and carried out further actions with the data from 01.08.2019 to 07.08.2019.

The sales funnel of users using the application of a startup selling food was studied. 38% of users "get stuck" on the main screen, this maximum loss occurs at the first step of the funnel, it is worth telling the developers about this and checking the step again for technical problems. 48% of all users reach the purchase.

We can be sure of the accuracy of the AAB experiment, the two control groups turned out to be equal, for this we tested the hypothesis of equality of shares. Next, we conducted pairwise z-testing of 246 and 248 groups, 247 and 248 groups, as well as when testing the combined control group 246_247. Comparison of control groups also helped to understand that there is no statistically significant difference between the proportions of control and experimental groups. It turns out that the new font did not affect users. For z-testing, the significance level alpha = was chosen.05 and 16 tests were conducted. bonferroni_alpha = 0.003125, which is less than all the resulting p-value

Recommendations: Changing the font did not affect users, which means it can be changed in the application. However, the data comes late and the actual events began only from the second week. In the future, this delay should be taken into account.

## Company profile:
start-up, internet services

## Stack:
Python, Pandas, Seaborn, data visualisation, Matplotlib, A/B-testing

## tags:
data analisys, Python, Pandas, presentation
