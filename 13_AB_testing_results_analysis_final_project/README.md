# Evaluate the correctness of the conduct of an A/B test

## Task:
To evaluate the correctness of the conduct and analyze the results of the A / B test using a dataset with user actions and terms of reference.

## Description:
To solve the set tasks, the obtained data were checked for compliance with the terms of reference, followed by an exploratory analysis of the data and a z-test to check the statistical difference between the criteria. Based on the analysis, a decision was made about the incorrectness of this test.

## Results:
The actions of new users are given for the period from December 7, 2020 to December 30, 2020, although according to the terms of reference test ends on January 4, 2021. This may be the cause of a technical failure, or incorrect data upload. Or for some other reason, the organizers had to end the test earlier. Due to the fact that the end of the test did not meet the terms of reference, the test participants from Dec 31 until Jan 4 had to be excluded. The participant must "live" for 14 days, so people registered after December 18 must be excluded too. The recommender_system_test was run in parallel with another interface_eu_test. Both of these tests can directly affect the conversion of the funnel steps, because they are closely related in meaning. Both improving the recommender system and refining the interface can affect sales. The seasonality of the test is not taken into account, the Christmas sale is the worst time to try out an improvement in the interface and try to evaluate the conversion. In funnels, the expected result in increasing conversion by 10% for each step is not achieved.

Recommendations:

 - eliminate identified problems related to the test procedure
 - repeat the test, taking into account seasonality
 - if the test results show a deterioration in conversion, it is recommended to abandon the improved recommender system
 
## Stack:
Python, Pandas, Matplotlib, Seaborn, AB-testing

## tags:
data analisys, Python, Pandas
