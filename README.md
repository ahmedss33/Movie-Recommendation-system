# Movie-Recommendation-system
Recommendations using the clustering approach for user-based CF producing

The goal of this project:

1-	Split the data: 943 user and 1682 movies

2-	From the users 200 is sending randomly test data and the remaining 743 for training data

3-	generate 5 suggestion and repeat it 10 times for the user

4-	the average of these transactions is the MAE for active user

5-	number of clusters 3,5,10 and k-closest neighbor selection number 20,40,60

6-	Pearson correlation to calculate the MAE




• While performing the experiments, 200 of all users randomly sent test data. Let the remaining 743
users' data be separated as training data.
• Clustering with K-means: 743 users, active user number of clusters before requesting suggestion, c,
clustered according to. Then, when any active user requests a suggestion, it will be activated first. The
user's set is found. The recommendation is made with this cluster in mind.
• For each active user (200 test data was reserved, one of them is active each time) Suggestions are
generated for 5 products that will be chosen as a user) randomly voted. And these transactions Let it be
repeated 10 times for the user. The average of these transactions is the MAE value of the active user.
gives. Finally, the MAE averages of 200 active users give the overall MAE of the system. 
