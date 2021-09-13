# Forecasts-and-predictions-project
 AIMS:  Learn to predict the probability of churn (for the upcoming month) for each customer; Draw up typical user portraits: select the most outstanding groups and describe their main features; Analyze the factors that impact churn most; Draw basic conclusions and develop recommendations on how to improve customer service; Identify target groups; Suggest measures to cut churn; Describe any other patterns you see with respect to interaction with customers


Throughout the analysis, we found out that:

1. 
mean values of features for users who left and remained show that a)Those who have left (Churn=1) have shorter Contract_period, Lifetime, than those who remain (Churn=0); b)Those who are staying have higher Avg_additional_charges_total than those who remained.

users who leave are likely among the youngest users, have the shortest Lifetime, pay less additional charges, usually have around a month till the end of the contract, have lower average class frequency and do not attend classes in the last month.

users who stay most likely live near, are employees of partner companies, often sign up through a friend, often have 6 and 12 months cntracts, take part in group sessions.

almost 3times more users stay than leave.

the higher Lifetime and Avg_class_frequency_current_month, the more likely user is to stay.

![image](https://user-images.githubusercontent.com/26043577/133151249-d79957e2-ea38-41c2-b8ad-41d8fb1d3448.png)

2.
Linear Regression performed better as a model to predict users churn.

The users were divided into 4 main clusters.

![image](https://user-images.githubusercontent.com/26043577/133151366-9846d024-8397-42d4-aeac-1826b72b3416.png)


Users from cluster 0 live far, had the highest lifetime, did not join through a friend and were the the biggest cluster, had the lowest average class frequency and the highest additional charges.

Users from cluster 1 did not join through a friend and were more likely to remain and had the highest average class frequency.

Users from cluster 2 were employees of partnering companies, joined the gym on a 12 month contract, had the highest number of months left before the end of the contract and did not leave.

Users from cluster 3 did not provide their phone number, were the least numerous group and had the second highest additional charges.

![image](https://user-images.githubusercontent.com/26043577/133151505-57528241-f5c7-4bbb-824b-a8fd4e9a6ec6.png)
